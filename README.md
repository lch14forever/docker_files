# Docker files for building images

## Usage

```
cat [docker_file] | docker build  - -t [image_name]
```

For example:
```
cat  DOCKER_tiny_rmarkdown | docker build -t tiny_rmarkdown -
```

## Available
* DOCKER_tiny_rmarkdown
    * based on yihui's [TinyTeX](https://yihui.name/en/2017/12/test-tinytex/)

