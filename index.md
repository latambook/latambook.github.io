<style>
  /* Oculta el título "LATAMBOOK" que pone el theme de GitHub */
  .site-title,
  .site-name,
  header h1 {
    display: none !important;
  }

  :root { --max: 980px; }

  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
    line-height: 1.55;
    margin: 0;
    color:#0a0a0a;
  }

  header {
    padding: 16px 16px 24px;
    background:#f5f7fb;
    border-bottom:1px solid #e6e9f2;
  }

  .wrap {
    max-width: var(--max);
    margin: 0 auto;
    padding: 0 16px;
  }

  h1 {
    margin: 0 0 8px;
    font-size: 32px;
    letter-spacing:.3px;
  }

  .tagline {
    color:#5b667a;
    margin:0 0 8px;
  }

  .meta {
    color:#6b7280;
    font-size:14px;
    margin:0;
  }

  h2 {
    margin-top: 32px;
    font-size: 22px;
  }

  p  {
    margin: 10px 0;
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
    gap: 16px;
  }

  .card {
    border:1px solid #e6e9f2;
    border-radius:12px;
    padding:14px;
    background:#fff;
  }

  .card img {
    width: 100%;
    height: 300px;
    object-fit: cover;
    border-radius:8px;
  }

  .card h3 {
    margin:10px 0 4px;
    font-size:16px;
  }

  .muted {
    color:#6b7280;
    font-size: 14px;
  }

  .two {
    display:grid;
    grid-template-columns: 1fr;
    gap:20px;
  }

  @media (min-width: 860px){
    .two { grid-template-columns: 1fr 1fr; }
  }

  .footer {
    margin: 40px 0 60px;
    color:#6b7280;
    font-size:14px;
  }

  a {
    color:#0f5cc0;
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }

  /* Sección Servicios editoriales / Complete editorial process */
  .services-grid {
    max-width: 1100px;
    margin: 3rem auto;
    display: grid;
    grid-template-columns: repeat(2, minmax(320px, 1fr));
    column-gap: 3rem;
    row-gap: 2rem;
  }

  .services-grid h2 {
    margin-bottom: 0.25rem;
  }

  .services-grid .muted {
    margin-bottom: 1rem;
  }

  @media (max-width: 768px) {
    .services-grid {
      grid-template-columns: 1fr;
      padding: 0 1.25rem;
    }
  }
</style>

<!-- LOGO -->
<div class="wrap" style="padding-top: 24px; padding-bottom: 8px;">
  <img src="img/latambook-logo.png"
       alt="LatamBook Logo"
       style="height: 70px;">
</div>

<header>
  <div class="wrap">
    <h2>📚 Editorial Services | Distributor for Latin America 🌐</h2>
    <p class="tagline">
      📍 Buenos Aires / Rosario – Argentina · 
      📞 <a href="https://wa.me/5491151011262">+54 9 11 5101 1262</a> · 
      ✉️ <a href="mailto:ventas@latambook.com">ventas@latambook.com</a> · 
      IG: <a href="https://instagram.com/latambook" target="_blank">@latambook</a>
    </p>
  </div>
</header>

<div class="wrap">

  <div class="two">
    <div>
      <h2>About us(EN)</h2>
      <p><b>LATAMBOOK</b> is a Latin American book distributor with a regional client network. We manage sales, logistics and publisher representation, and provide editorial services (editing, design, translation, copy-editing; <b>ISBN/barcode</b> issuance registered at the Argentine Book Chamber).</p>
      <p>Through our publishing imprints <b>La Mora</b> (literary–poetic, founded in 2010) and <b>SurAmerica</b> (human sciences, founded in 2010) — we produce books in both print and digital formats.</p>
    </div>

    <div>
      <h2>Sobre nosotros(ES)</h2>
      <p><b>LATAMBOOK</b> opera como distribuidora editorial con red de clientes en toda Latinoamérica. Gestionamos ventas, logística y representación de sellos locales, y también ofrecemos servicios de <i>edición</i>, diseño, traducción, corrección y tramitación de <b>ISBN / código de barras</b> (registrados en la Cámara Argentina del Libro).</p>
      <p>Desde 2010 brindamos servicios editoriales a través de nuestros sellos: <b>La Mora</b> — orientado a poesía y literatura — y <b>SurAmerica ediciones</b> — especializado en Ciencias Humanas.</p>
    </div>
  </div>

  <hr class="divider">

  <section id="servicios-editoriales" class="services-grid">
    <div>
      <h2>🏗️Complete editorial process</h2>
      <p class="muted">Professional support through every stage of the publishing process.</p>
      <ul>
        <li><b>Copy editing</b> — language and consistency review.</li>
        <li><b>Translation</b> — Spanish ↔ English or other languages depending on the project.</li>
        <li><b>Graphic design</b> — cover art and visual identity creation.</li>
        <li><b>Layout and typesetting</b> — interior book design.</li>
        <li><b>ISBN &amp; barcode management</b> — registered with the Argentine Book Chamber.</li>
        <li><b>Publishing</b> — print editions and/or digital platforms.</li>
      </ul>
    </div>

    <div>
      <h2>👷‍♀️Servicio editorial integral</h2>
      <p class="muted">Desde nuestra casa editorial La Mora gestionamos todas las etapas del proceso editorial y productivo.</p>
      <ul>
        <li><b>Corrección de estilo</b> — revisión lingüística y de coherencia.</li>
        <li><b>Traducción</b> — español ↔ inglés u otros idiomas.</li>
        <li><b>Diseño gráfico</b> — diseño de portada e identidad visual.</li>
        <li><b>Diagramación</b> — maquetación del interior del libro.</li>
        <li><b>Gestión de ISBN y código de barras</b> — tramitación en la Cámara Argentina del Libro.</li>
        <li><b>Publicación</b> — impresión y/o plataformas digitales.</li>
      </ul>
    </div>
  </section>

  <h2>📚Editorial Production Samples💡</h2>

  <section id="catalogo" class="grid">
    <article class="card">
      <img src="img/con-permiso-de-hablar.jpeg" alt="Con permiso de hablar – portada" loading="lazy">
      <h3>Con permiso de hablar</h3>
      <p class="muted">Sello: <b>La Mora</b> · Autora: María Vilalta ·ISBN: 9789872445584</p>
    </article>

    <article class="card">
      <img src="img/IMG_9372.jpeg" alt="MANOS – portada" loading="lazy">
      <h3>MANOS. Antología de Poemas</h3>
      <p class="muted">Sello: <b>La Mora</b> · Autor: Miguel Catalá · ISBN: 9789872593742</p>
    </article>

    <article class="card">
      <img src="img/IMG_9371.jpeg" alt="Rumbo al trabajo feliz – portada" loading="lazy">
      <h3>Rumbo al trabajo feliz</h3>
      <p class="muted">Sello: <b>SurAmerica</b> · Autora: Carolina Casiello · ISBN: 9789872593933</p>
    </article>

    <article class="card">
      <img src="img/IMG_9370.jpeg" alt="Escrituras de la política – portada" loading="lazy">
      <h3>Escrituras de la política</h3>
      <p class="muted">Sello: <b>SurAmerica</b> · Autor: Roberto Retamoso · Formato: Rústica</p>
    </article>
  </section>

</div>
