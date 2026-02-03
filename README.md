# Chat Service API Documentation

Interactive API documentation generated from the Swagger/OpenAPI spec.

## Run Locally

```bash
# Option 1: Using npx (no install needed)
npx serve . -p 3001

# Option 2: Using Python
python3 -m http.server 3001

# Option 3: Using npm script
npm run serve
```

Then open **http://localhost:3001** in your browser.

## Deploy / Host

These are static files—you can host them anywhere:

| Platform | How |
|----------|-----|
| **Netlify** | Drag the folder to [app.netlify.com/drop](https://app.netlify.com/drop) or connect your Git repo |
| **Vercel** | `npx vercel` in this directory |
| **GitHub Pages** | Push to a repo, enable Pages in Settings, set source to main branch |
| **AWS S3** | Upload the folder to an S3 bucket and enable static website hosting |
| **Any static host** | Upload `index.html` and `chat-service-swagger.yml` |

## Files

- `index.html` - Swagger UI wrapper
- `chat-service-swagger.yml` - OpenAPI 2.0 spec
