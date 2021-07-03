# receptor - basic example

This example creates two receptor nodes, called `arceus` and `celebi`.

## Commands

```bash
# Build and run
docker-compose up -d

# Destroy and cleanup
docker-compose down
rm -rf ./socks/

# Run commands on receptorctl
./ctl.sh <args>

# Examples
./ctl.sh ping celebi
./ctl.sh ping arceus
```
