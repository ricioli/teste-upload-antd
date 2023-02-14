# teste-upload-antd

```bash
docker run -d --name node-upload --rm -e LANG=C.UTF-8 -v ~/.gitconfig:/root/.gitconfig -v ~/.ssh/id_rsa:/root/.ssh/id_rsa -v $(pwd):/usr/src -w /usr/src -p 5173:5173 --add-host host.docker.internal:host-gateway node npm run dev
```
