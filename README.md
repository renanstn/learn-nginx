# Learn NGINX

## Reverse proxy

Anotações referentes ao meu estudo de NGINX, com base [neste](https://www.youtube.com/watch?v=pPlcC5hDMCs) vídeo.

Arquivo principal de conf fica em:

```
/etc/nginx/nginx.conf
```

Crie seus arquivos próprios de configuração em:

```
/etc/nginx/conf.d/*.conf
```

Exibir os arquivos de configuração carregados:

```sh
nginx -t
```

Recarregar o NGINX:

```sh
nginx -s reload
```
## Cache

Implementado um esquema simples de cache, para estudo, seguindo esta [documentação](https://docs.nginx.com/nginx/admin-guide/content-cache/content-caching/) e alguns vídeos do YouTube.
