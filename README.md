# Github Webhook Test

## Install

To install run:

``` shell
$ npm install
```

## Run server

Firstly you need to proxy the webhooks.

Install smee client.

``` shell
$ npm install --global smee-client
```

Set up a smee proxy URL at https://smee.io/ 

Start the smee client for the URL from above.

``` shell
$ smee --url https://smee.io/<your url> --path /webhook --port 3000
```

Then you can start the server on port 3000.

``` shell
$ npm run start
```

