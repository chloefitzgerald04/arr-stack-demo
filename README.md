# Arr stack demo

Built for my personal testing with terraform but decided to stick it in a public repo for ease of use and also public access because why not. Contains basics needed- radarr/sonarr for films and TV respectively, prowlarr set up with a few public trackers and qbittorrent as the download client. Uses a docker network to allow services to communicate via domain name so in theory should be plug and play. May add more later




## How to use

1. Clone the repo `git clone https://github.com/chloefitzgerald04/arr-stack-demo.git`
2. cd into the newly made directory
3. Optional - adjust mount paths
4. `docker compose up -d` to bring it up
5. Done
6. Optional - Use the import tools within Radarr and Sonarr if using a premade directory for media.


## Credentials
Credentials for all the services
```
Username - admin
Password - Admin123 
```
Please change this password before actually deploying this k thx
