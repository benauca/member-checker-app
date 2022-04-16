# teams-checker

> A GitHub App built with [Probot](https://github.com/probot/probot) that Review that dont exist users without teams

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
docker build -t teams-checker .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> teams-checker
```

## Contributing

If you have suggestions for how teams-checker could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2022 benauca <benauca@gmail.com>
