# Code-Server running with docker-compose, nginx proxy and ssl secured

[Code-server](https://coder.com/) is __VS Code__ running on a container, secured with ssl and LetsEncrypt certificate.

## Containers used
- [LinuxServer -> Code-Server](https://hub.docker.com/r/linuxserver/code-server)
- [jwilder -> Nginx Proxy](https://hub.docker.com/r/jwilder/nginx-proxy)
- [jrcs -> LetsEncrypt nginx](https://hub.docker.com/r/jrcs/letsencrypt-nginx-proxy-companion)

## Parameters to adjust

vscode Container:
- PASSWORD=
- SUDO_PASSWORD=
- PROXY_DOMAIN=
- VIRTUAL_HOST=
- LETSENCRYPT_HOST=

## License

<img src="./img/by-sa.png">

This work is under [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

Please read the LICENSE files for more details.
