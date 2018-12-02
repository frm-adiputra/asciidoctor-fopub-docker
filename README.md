# How to use this image

Just run:

```bash
docker run -it --rm -v <your directory>:/documents/ frma/asciidoctor-fopub
```

Your directory will be directly mapped with `/documents` of the container.

Once the container has started, you can convert DocBook files to PDF using commands like:

```bash
fopub sample.xml
```
