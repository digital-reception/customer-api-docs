# Customer API Docs

Demo: https://digital-reception.github.io/customer-api-docs/

This repo is intended to host our Customer endpoint OpenAPI Spec (aka Swagger) for customer developers.

It is powered by [Swagger UI](https://swagger.io/tools/swagger-ui/), and is insipred by Patric Gutersohn's [
repo](https://github.com/pguso/openapi-petstore-ui.github.io) and [article](https://pguso.medium.com/host-openapi-documentation-with-github-pages-ec16f75e9762).

## Run locally

Browsers don't like loading local files these days, so we can spin up a simple web server to "host" the files.

Run this:

```bash
ruby -run -e httpd . -p 5000
```

Then visit: `http://localhost:5000/`
