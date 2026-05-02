# lp-construction

AI-powered construction landing page from Aurora Market.

## Local preview

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Deployment

This repository is a static site (`index.html`) and is ready for Vercel deployment.

1. Import the repo into Vercel.
2. Keep the root directory as `.`.
3. Vercel will use `vercel.json` and serve `index.html`.

## Environment variables

Documented in `.env.example`:

- `NEXT_PUBLIC_APP_URL`
- `NODE_ENV`
- `STRIPE_SECRET_KEY`
- `STRIPE_WEBHOOK_SECRET`
- `NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY`
- `DATABASE_URL`
- `OPENAI_API_KEY`

## License

See LICENSE file for details.
