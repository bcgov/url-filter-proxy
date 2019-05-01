# url-filter-proxy

## Getting Started

```
docker build --tag url_filter_proxy .

docker run --rm -ti --name url-filter-proxy \
 -e UPSTREAM_URL="https://google.com" \
 -e LOOKUP_URL="http://localhost/stub" \
 -p 4444:80 \
 url_filter_proxy

```
