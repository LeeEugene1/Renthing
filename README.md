## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

## tailwindCSS
- 설치
```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init
```
- postcss.config.js변경, tailwind.config.js변경
- globals.css를 전부 지우고 이와같이 변경
```
@tailwind base;
@tailwind components;
@tailwind utilities;

html,
body,
:root{
  height: 100%;
}
```
- 참고: https://tailwindcss.com/docs/installation/using-postcss