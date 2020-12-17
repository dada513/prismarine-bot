# prismarine-bot

> A GitHub App built with [Probot](https://github.com/probot/probot) that A bot for PrismarineJS

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t prismarine-bot .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> prismarine-bot
```

## Contributing

If you have suggestions for how prismarine-bot could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2020 dada513 <kontakt@dada513.eu>