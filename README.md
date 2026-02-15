# Marco Carnevali's Portfolio

A simple, terminal-style personal portfolio website with a typing animation.

## How to run

To view the website locally, you can use Python's built-in HTTP server:

```bash
python3 -m http.server 3000
```

Then open your browser at `http://localhost:3000`.

## Features

- Terminal-like typing animation with skip functionality.
- Professional "terminal" aesthetic with green accents.
- Responsive design for mobile and desktop.
- Social links (LinkedIn, Email).
- Dynamic copyright year.

## Deployment

Since this is a static website, you can host it for free on several platforms:

### GitHub Pages
1. Push your code to a GitHub repository.
2. Go to **Settings** > **Pages**.
3. Under **Build and deployment**, select the branch you want to deploy from (usually `main`).
4. Your site will be live at `https://<username>.github.io/<repository-name>/`.

### Vercel / Netlify
1. Connect your GitHub repository to [Vercel](https://vercel.com) or [Netlify](https://www.netlify.com).
2. They will automatically detect the static files and deploy them.
3. Every time you push to your repository, the site will be updated automatically.

### Manual Upload (Surge.sh)
If you have `npm` installed, you can use Surge:
```bash
npx surge .
```
