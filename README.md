# k3s-letsencrypt-experiment

Manifests to setup k3s with letsencrypt, following [this guide](https://opensource.com/article/20/3/ssl-letsencrypt-k3s)

The guide is fine (except for some small formatting issues in `.yaml` files). The manifests here include a stock-standard nginx deployment, so that http requests get answered by a default http backend.
