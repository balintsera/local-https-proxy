generate keys:

```bash
sudo openssl req -x509 -sha256 -newkey rsa:2048 -keyout cert.key -out cert.pem -days 1024 -nodes -subj '/CN=dev-auth.omoplanet.com'
```



then move them to `ssl/`

then docker-compose up


credits: https://www.shanestillwell.com/2016/10/03/create-a-local-https-proxy-server/
