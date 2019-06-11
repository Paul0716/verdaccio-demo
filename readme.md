### verdaccio demo 

[![Build Status](https://drone.paultaku.tw/api/badges/Paul0716/verdaccio-demo/status.svg)](https://drone.paultaku.tw/Paul0716/verdaccio-demo)

This is as demo setup project for verdaccio host on linode

##### local run command 
`docker run -it -v ${PWD}/storage:/verdaccio/storage -v ${PWD}/conf:/verdaccio/conf --name verdaccio -p 4873:4873 --rm verdaccio/verdaccio:4`