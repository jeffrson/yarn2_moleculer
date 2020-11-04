# yarn2_moleculer

1. cd app
1. yarn v2init
1. yarn
1. yarn start

[TIME] FATAL server-1/BROKER: The 'nats' package is missing! Please install it with 'npm install nats --save' command.
Error: moleculer tried to access nats, but it isn't declared in its dependencies; this makes the require call ambiguous and unsound.

It works with v1 though:
    
1. git clean -ffdx
1. yarn
1. yarn start

...
[TIME] ERROR server-1/TRANSPORTER: NATS error. Could not connect to server: Error: getaddrinfo ENOTFOUND nats.server
...
