# Biome Config

Shared [Biome](https://biomejs.dev/) linting/formatting configuration.

- [Requirements](#requirements)
- [Usage](#usage)
- [License](#license)

## Requirements

This library requires the following to run:

- [Node.js](https://nodejs.org/) 18+

## Usage

Install with [bun](https://www.bun.sh/) (`biome` will be installed as a peer dependency):

```sh
bunx jsr add --save-dev @tomi/biome-config
```

Add this to your `biome.json` file:

```json
{
  "extends": ["@tomi/biome-config/biome"]
}
```

## License

Licensed under the [MIT](LICENSE) license.<br/>
Copyright &copy; 2024, Tomi Studio
