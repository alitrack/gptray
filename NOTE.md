
# Note

```bash
git submodule add https://github.com/alitrack/node-chatgpt-api server
git submodule add https://github.com/alitrack/PandoraAI client

wget -c https://caddyserver.com/api/download -O caddy
chmod +x caddy
./caddy start 

ssh -R gptray.serveo.net:80:localhost:8433 serveo.net
```
