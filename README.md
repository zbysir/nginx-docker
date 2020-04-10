# nginx-docker
nginx docker image with alpine & proxy_cache_purge

tips: 构建需要很长时间, 在dockerhub上需要17min, 请耐心等待

## alpine-purge
Add "ngx_cache_purge" module(v2.5) for official nginx/alpine:1.14 image.

Module from https://github.com/nginx-modules/ngx_cache_purge, This Module support "[Partial Keys](https://github.com/nginx-modules/ngx_cache_purge#partial-keys)".

