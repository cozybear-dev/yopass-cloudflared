# yopass-cloudflared
Local yopass hosting with reverse tunnel using Cloudflare(d).

.env.example has two options;

- on disk
- fetch it using unlocked Bitwarden CLI

If you care about security, use Bitwarden CLI option.

To import in your shell;

```
source .env
```

Configure Cloudflare tunnel to `http://yopass`.

It includes watchtower for the sake of updating, remove if unwanted.

Networks are segmented.