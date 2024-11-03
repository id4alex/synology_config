```
mkdir -p /volume1/docker/docker-compose/mysql
rm -rf /volume1/docker/docker-compose/mysql/docker-compose.yml
curl https://raw.githubusercontent.com/id4alex/synology_config/refs/heads/main/docker/mysql/docker-compose.yml > /volume1/docker/docker-compose/mysql/docker-compose.yml
cd /volume1/docker/docker-compose/mysql && docker-compose up -d


mkdir -p /volume1/docker/docker-compose/nginxproxymanager
rm -rf /volume1/docker/docker-compose/nginxproxymanager/docker-compose.yml
curl https://raw.githubusercontent.com/id4alex/synology_config/refs/heads/main/docker/nginxproxymanager/docker-compose.yml > /volume1/docker/docker-compose/nginxproxymanager/docker-compose.yml
cd /volume1/docker/docker-compose/nginxproxymanager && docker-compose up -d



mkdir -p /volume1/docker/docker-compose/gitea
rm -rf /volume1/docker/docker-compose/gitea/docker-compose.yml
curl https://raw.githubusercontent.com/id4alex/synology_config/refs/heads/main/docker/gitea/docker-compose.yml > /volume1/docker/docker-compose/gitea/docker-compose.yml
cd /volume1/docker/docker-compose/gitea && docker-compose up -d



mkdir -p /volume1/docker/docker-compose/sun-panel
rm -rf /volume1/docker/docker-compose/sun-panel/docker-compose.yml
curl https://raw.githubusercontent.com/id4alex/synology_config/refs/heads/main/docker/sun-panel/docker-compose.yml > /volume1/docker/docker-compose/sun-panel/docker-compose.yml
cd /volume1/docker/docker-compose/sun-panel && docker-compose up -d


mkdir -p /volume1/docker/docker-compose/vaultwarden
rm -rf /volume1/docker/docker-compose/vaultwarden/docker-compose.yml
curl https://raw.githubusercontent.com/id4alex/synology_config/refs/heads/main/docker/vaultwarden/docker-compose.yml > /volume1/docker/docker-compose/vaultwarden/docker-compose.yml
cd /volume1/docker/docker-compose/vaultwarden && docker-compose up -d
```
