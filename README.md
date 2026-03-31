# Packsify Creator Growth Playbook

Elite Partner Edition - Q2 2026

Static HTML site deployed to `creatorplaybook.packsify.com`

## Deploy

Connected to Vercel. Push to `main` to deploy.

## Structure

```
public/
  index.html    # The full playbook (self-contained, no dependencies)
vercel.json     # Vercel routing config
```

## Notes

- Fully self-contained single HTML file (CSS inline, logo embedded as base64)
- No build step needed - pure static deployment
- Separate from the Growth Playbook app (playbook.packsify.com)
