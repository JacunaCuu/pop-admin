POP Admin — Instrucciones rápidas

1) Requisitos (una sola vez)
   - Tener un proyecto en Firebase con Authentication (Google), Firestore y Storage habilitados.
   - Agregar "localhost" en Authentication > Settings > Authorized domains.
   - Tener Node.js instalado (LTS).

2) Edita el archivo (si quieres ser admin ya)
   - Abre "index.html" con un editor de texto.
   - Busca: const ADMIN_EMAILS = ["tu.correo@empresa.com"];
   - Cambia por tu correo real (o agrega varios).

3) Probar en tu computadora
   - Abre una terminal en esta carpeta.
   - Ejecuta: npx serve
   - Abre la URL que te muestre (ej. http://localhost:3000)
   - Clic "Iniciar sesión" con Google.
   - Si tu correo está en ADMIN_EMAILS, verás el panel de "Subir material".
   - Sube un material y prueba Aprobar/Rechazar.

4) Subir a Vercel (hosting gratis)
   - Crea cuenta en vercel.com
   - Instala CLI: npm i -g vercel
   - En esta carpeta ejecuta: vercel
   - Copia la URL de producción.
   - Agrega ese dominio en Firebase > Authentication > Authorized domains.
   - Listo.
