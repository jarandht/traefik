Check expiery:
sudo openssl x509 -dates -noout -in cert.pem

Create cert:
sudo certbot certonly --manual --preferred-challenges dns -d "*.DOMAIN"