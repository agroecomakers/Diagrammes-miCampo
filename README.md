# miCampoApp – Cooperativa Digital Agroecológica

Este paquete contiene la página web principal de **miCampoApp**, una vitrina digital trilingüe (Español, Francés, Inglés) para presentar el sistema cooperativo agroecológico y las aplicaciones web y móviles asociadas.

---

## 📁 Contenido

- `index.html` — Página principal (HTML + Tailwind CSS via CDN)
- `Campesino.svg`, `Cliente.svg`, `Investigador.svg`, `productor_c.svg`, `saber más.svg`, `spg.svg`, `Transport.svg`, `workshop.svg` — Ilustraciones vectoriales usadas en la página.

---

## 🚀 Publicación en GitHub Pages

1. Crea o abre tu repositorio (por ejemplo: `AgroecomakersDiagrams`).
2. Copia todos los archivos de este paquete (`index.html` y SVGs) en la raíz del repositorio.
3. Sube los cambios:

```bash
git add .
git commit -m "Add miCampoApp static webpage"
git push
```

4. En GitHub, ve a **Settings → Pages → Source**, selecciona la rama `main` (o `gh-pages`) y carpeta `/root`.

Tu sitio estará disponible en:
```
https://agroecomakers.github.io/AgroecomakersDiagrams/
```

---

## 🌐 Publicación en tu servidor (agromakers.org)

1. Conéctate por SSH a tu servidor:
```bash
ssh usuario@agromakers.org
```

2. Copia los archivos al directorio web (por ejemplo `/var/www/agromakers.org/`):
```bash
scp index.html *.svg usuario@agromakers.org:/var/www/agromakers.org/
```

3. Verifica en tu navegador:
```
https://agromakers.org
```

---

## 📲 Enlaces integrados

- **Webmaster App:** [https://webmaster.agromakers.org/login](https://webmaster.agromakers.org/login)
- **Usuario Web App:** [https://app.agromakers.org/login](https://app.agromakers.org/login)
- **Descargar APK:** [https://webmaster.agromakers.org/micampo.apk](https://webmaster.agromakers.org/micampo.apk)
- **Instalar en iPhone (PWA):** [https://app.agromakers.org](https://app.agromakers.org)

---

## 🧩 Tecnologías

- HTML5 + Tailwind CSS (via CDN)
- SVGs optimizados
- Diseño responsivo compatible con dispositivos móviles

---

**Autor:** Proyecto Agroecomakers – IRD / Agrosavia / Universidad Paris-Saclay / KARLO / CIP
