# mayaagnihotri.com

My personal website — built with Node.js and Express.

## Running Locally

```bash
npm install
npm run dev
```

Then open [http://localhost:3000](http://localhost:3000).

## Project Structure

```
├── server.js              # Express server
├── package.json           # Dependencies
├── public/
│   ├── index.html         # Main site (Home + My Work pages)
│   └── images/            # Headshot, favicons
└── .gitignore
```

## Deploying

This is a Node.js app. To host it, use a platform that supports Node.js like [Vercel](https://vercel.com), [Render](https://render.com), or [Railway](https://railway.app). Alternatively, since the site is fully self-contained (inline CSS/JS), you can serve `public/index.html` as a static file via GitHub Pages.
