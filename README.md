# nginx-freecodecamp

## Quick Start

Start nginx with custom config:

```bash
sudo nginx -c ./nginx-freecodecamp/nginx.conf
```

Reload after config changes:

```bash
sudo nginx -s reload
```

Stop nginx:

```bash
sudo nginx -s quit
```

## Config Notes

- Uses `user yukisola;` to avoid permission issues
- Serves files from `mysite/` directory
- Listens on port 80
