What we want/need:
* Scalable web application tier, where we could do both rolling updates (for zero downtime updates) and automatic and manual horizontal scaling of the server.
* Mountable persistent storage with automatic snapshots/backups.
* Managed robust database (Postgresql) with automatic backups and easy replication to read-only instances.
* Managed solution to store secrets (such as Heroku's ENV support). Never store production configuration in the source code.
* Docker images support without us having to build custom infrastructure to deploy.
* Static external IP addresses for integrations that required a fixed IP.
* SSL termination so we could connect to CloudFlare (CDN is mandatory, but not enough, in 2018 we need some level of DDoS protection).
* Enough security by default, so everything is - in theory - lockdown unless we decide to open it.
* High-availability in different data center regions and zones.
