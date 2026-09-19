# AutoServer

Talk to your VPS. An AI installer plus skills (panels, bots, and more) that run on your machine.

**Not open source.** Application source is not in this repository. This repo is a public storefront only.

## Install

1. Create an API key at [autoserver.org](https://autoserver.org) (one key = one server).
2. On your linux VPS as root:

```bash
curl -fsSL https://autoserver.org/install.sh | bash -s -- --key as_live_xxxx
```

Do not `git clone` this repository onto the server.

## Move to a new VPS

In the dashboard, unbind the machine from that key, then install again with the same key.

## License

See [LICENSE](LICENSE). Copying, redistributing, or reselling this product is not allowed.
