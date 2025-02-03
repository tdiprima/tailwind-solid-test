```sh
npm create vite@latest
Need to install the following packages:
create-vite@5.2.3
Ok to proceed? (y) y
✔ Project name: ... tailwind-solid-test
✔ Select a framework: › Solid
✔ Select a variant: › JavaScript

Scaffolding project in tailwind-solid-test...

Done. Now run:

  cd tailwind-solid-test
  npm install
  npm run dev
```

http://localhost:5173/

[Get started with Tailwind CSS](https://tailwindcss.com/docs/installation/using-postcss)

```sh
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init
```

Add Tailwind to your PostCSS configuration

Configure your template paths

Replace index.css with

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Go to App.jsx

Remove everything from return and put 

```html
<h1>Hello Solid!</h1>
```

### Licensing Notice

This project may include third-party open-source code, which remains subject to its original licenses.<br>
Attribution is provided in the source code where applicable.  

If you believe there is an issue with licensing, please **open an issue** or **contact the repository owner** for resolution.

<br>
