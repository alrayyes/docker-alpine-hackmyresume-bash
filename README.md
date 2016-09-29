[![Latest release][img-release]][latest-release] [![](https://images.microbadger.com/badges/image/andthensome/alpine-hackmyresume-bash.svg)](http://microbadger.com/images/andthensome/alpine-hackmyresume-bash "Get your own image badge on microbadger.com") [![](https://images.microbadger.com/badges/version/andthensome/alpine-hackmyresume-bash.svg)](http://microbadger.com/images/andthensome/alpine-hackmyresume-bash "Get your own version badge on microbadger.com")

# Docker Alpine Hackmyresume Bash

(Not so) Minimal container with [Hackmyresume](https://www.npmjs.com/package/hackmyresume), [wkhtmltopdf](http://wkhtmltopdf.org/)  & Bash installed. Built to be used with [wercker](http://wercker.com/). Leverages [mhart/alpine-node](https://hub.docker.com/r/mhart/alpine-node/) base image.

Hopefully will use [official wkhtmltopdf package](https://pkgs.alpinelinux.org/package/edge/testing/x86_64/wkhtmltopdf) once it's in stable

## Usage

	docker run --rm andthensome/alpine-hackmyresume-bash
