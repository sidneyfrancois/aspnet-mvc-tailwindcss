# ASP.NET MVC 6 with Tailwind

```
npm init -y
```

```
npm install -D tailwindcss cross-env
```

```
npx tailwindcss init
```

```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./**/*.{razor,cshtml,html}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
