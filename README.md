# catapult-testnet
## Quick start
Make sure that docker and docker-compose is installed. Assumption that catapult-testnet is installed under
~/catapult-testnet/

To run a peer node
```
cd ~/catapult-testnet/peer-assembly
sudo docker-compose up -d

```
To run api components (api node, api broker, rest-gateway mongodb)
```
cd ~/catapult-testnet/api-assembly
sudo docker-compose up -d
```
