<style>
  :root { --max: 980px; }
  body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif; 
         line-height: 1.55; margin: 0; color:#0a0a0a; }
  header { padding: 48px 16px 24px; background:#f5f7fb; border-bottom:1px solid #e6e9f2; }
  .wrap { max-width: var(--max); margin: 0 auto; padding: 0 16px; }
  h1 { margin: 0 0 8px; font-size: 32px; letter-spacing:.3px; }
  .tagline { color:#5b667a; margin:0 0 8px; }
  .meta { color:#6b7280; font-size:14px; margin:0; }
  h2 { margin-top: 32px; font-size: 22px; }
  p  { margin: 10px 0; }
  .grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 16px; }
  .card { border:1px solid #e6e9f2; border-radius:12px; padding:14px; background:#fff; }
  .card img { width: 100%; height: 300px; object-fit: cover; border-radius:8px; }
  .card h3 { margin:10px 0 4px; font-size:16px; }
  .muted { color:#6b7280; font-size: 14px; }
  .two { display:grid; grid-template-columns: 1fr; gap:20px; }
  @media (min-width: 860px){ .two { grid-template-columns: 1fr 1fr; } }
  .footer { margin: 40px 0 60px; color:#6b7280; font-size:14px; }
  a { color:#0f5cc0; text-decoration: none; }
  a:hover { text-decoration: underline; }
</style>

<header>
  <div class="wrap">
    <h2>📚LATAMBOOK🌐</h2>
    <p class="tagline">| Servicios editoriales | Distribuidora para Latinoamérica |</p>
    <p class="meta">📍 Buenos Aires / Rosario – Argentina · ✉️ ventas@latambook.com · IG: <a href="https://instagram.com/latambook" target="_blank">@latambook</a></p>
  </div>
</header>

<div class="wrap">

  <div class="two">
    <div>
      <h2>Sobre nosotros 🇪🇸</h2>
      <p><b>LATAMBOOK</b> opera como distribuidora editorial con red de clientes en toda Latinoamérica. 
         Gestionamos ventas, logística y representación de sellos locales, y también ofrecemos servicios de 
         <i>editing</i>, diseño, traducción, corrección y tramitación de <b>ISBN / código de barras</b> (registrados en la Cámara Argentina del Libro).</p>
      <p>Trabajamos en alianza con <b>Editorial La Mora</b> (Rosario, 2010) para conectar autores con sus obras.</p>
    </div>
    <div>
      <h2>About us 🇺🇸</h2>
      <p><b>LATAMBOOK</b> is a Latin American book distributor with a regional client network. We manage sales, logistics and publisher representation, and provide editorial services (editing, design, translation, copy-editing; <b>ISBN/barcode</b> issuance registered at the Argentine Book Chamber).</p>
      <p> We work in association with <b>La Mora Publishing House</b> (Rosario, 2010) to connect authors with their works..</p>
    </div>
  </div>

<!-- Catálogo | Muestra -->
<section id="catalogo" class="grid">
  <article class="card">
    <img src="img/con-permiso-de-hablar.jpg" alt="Con permiso de hablar – portada">
    <h3>Con permiso de hablar</h3>
    <p class="muted">Autora: María Vilalta · Idioma: Español · Formato: Rústica</p>
  </article>
</section>
