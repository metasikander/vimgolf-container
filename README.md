# vimgolf-container
a container for playing vimgolf

```sh
podman build . -t vimgolf
podman run --rm -it -e "key=<player id>" vimgolf <challenge id>
```
