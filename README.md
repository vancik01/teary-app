# teary-app

Landing page for Teary — dried-tear microscopy classifier + Lacrima keepsake range.

Single static `index.html`, inline CSS/JS, assets in `assets/`.

## Deploy (Coolify)

1. New Resource → Public Repo → `https://github.com/vancik01/teary-app`
2. Build Pack: **Dockerfile**
3. Port: `80`
4. Deploy

The included `Dockerfile` runs `nginx:alpine` and serves the repo root.

## Local

```
docker build -t teary .
docker run -p 8080:80 teary
```

Then open `http://localhost:8080`.
