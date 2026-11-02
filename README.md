# Sarah Itafa — Portfolio

A responsive React + Vite portfolio with an electric-blue theme, subtle binary background, and screenshots of four projects.

## Start locally

```bash
npm install
npm run dev
```

Open the local URL shown in the terminal.

## Customize before publishing

In `src/App.jsx`, update `CONTACT_EMAIL` with your public email address and `BOOKING_URL` with your future call-scheduling URL. Both are intentionally blank for now. The WhatsApp link is configured as `https://wa.me/18674459179`.

The four screenshots are in `public/images`. Project links, descriptions, and skill tags are in the `projects` and `skills` arrays in `src/App.jsx`.

The four listed languages are English, Arabic, Oromo and Amharic; adjust if your preferred four differ. Project tech tags are conservative estimates based on your description; verify against the original project repositories before publishing.

## Production

```bash
npm run build
```

Deploy the generated `dist` directory to a static host such as Netlify or Vercel.
