# docker-compose.yml for Drone.io (Bitbucket integration)

## How to use it?

1. Go to [Drone.io Docs](https://docs.drone.io/server/provider/bitbucket-cloud/) and read step 1 (how to get bitbucket access credentials).
2. Install **docker** and **docker-compose** on your server machine.
3. You can skip steps 2,3,4,5 because it useless.
4. Copy files `drone-docker-compose.yml` and `drone.env` to your server machine.
5. Insert access credentials and domain name inside `drone.env` file.
6. Make sure your domain accesible from internet. Link domain to you server.
6. Run `docker-compose up` command or `docker-compose up -d` for background mode.
