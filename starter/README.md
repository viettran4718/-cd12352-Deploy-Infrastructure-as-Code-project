# CD12352 - Infrastructure as Code Project Solution
# [YOUR NAME HERE]

## Spin up instructions

### Create
./create.sh udagram-network-stack network.yml network-parameters.json
./create.sh udagram-web-app-stack udagram.yml udagram-parameters.json

### Update
./update.sh udagram-network-stack network.yml network-parameters.json
./update.sh udagram-web-app-stack udagram.yml udagram-parameters.json

## Tear down instructions

### Delete
./delete.sh udagram-web-app-stack
./delete.sh udagram-network-stack

## Web URL
http://udagra-webse-omwc6duibyp7-335350373.us-east-1.elb.amazonaws.com/