# 1. Referensi

- https://www.youtube.com/watch?v=VDdMAgZD4tg

# 2. Instalasi

- npx create-react-app frontend --template typescript
- cd frontend
- npm start
- npm install sweetalert2
- npm install -D tailwindcss
- npx tailwindcss init
- npm install axios
- npm install @reduxjs/toolkit react-redux

# 3. Konfigurasi Tailwind CSS

## 1. File tailwind.config.js

- Buka file tailwind.config.js
- Ubah bagian

```
content: [],
```

- Menjadi berikut ini

```
content: [
    "./src/**/*.{js,jsx,ts,tsx}",
],
```

## 2. File src/index.css

- Buka file src/index.css
- Hapus code berikut

```
body {
  margin: 0;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen',
    'Ubuntu', 'Cantarell', 'Fira Sans', 'Droid Sans', 'Helvetica Neue',
    sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
```

- Ganti dengan code tailwind

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

# 4. Buat File TypeScript

- src/interfaces/Person.ts
- src/services/person.service.ts
- src/configs/axios.ts
- src/features/person/personSlice.ts
- src/app/store.ts
- src/app/App.tsx
- src/components/Form/index.tsx
- src/components/Table/index.tsx
- src/index.tsx

# 5. Testing Postman
