# Redocly-Docker

<img src="https://teamcity.eiprova.com/app/rest/builds/buildType:Public_Redocly/statusIcon" />

A very simple image to use redoc. Read their [official documentation](https://github.com/Redocly/redoc) for more information.

Example usage, assuming you have an `openapi-schema.json` file in the current directory:

```sh
docker run --rm -v `pwd`:/data iprova/redocly redoc-cli bundle -t /root/template.html openapi-schema.json
```

