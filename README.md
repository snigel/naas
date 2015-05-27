# naas
Netid as a Service

NaaS is a docker file building eggdrop + megahal in a convenient way.

1. Configure eggdrop.conf
See official documentation: http://eggwiki.org/Eggdrop.conf

2. Build naas
sudo docker build --tag=naas .

3. Run naas
sudo docker run naas
