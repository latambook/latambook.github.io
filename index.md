<style>
/* Reduce fair photos size */
.fair-card img {
  width: 100%;
  height: 160px;   /* antes 240px */
  object-fit: cover;
  border-bottom: 1px solid #e5e7eb;
}

  /* Intro de distribución EN / ES en dos columnas */
.distribution-intro {
  display: grid;
  grid-template-columns: 1fr;
  gap: 1.5rem;
  margin-bottom: 1.5rem;
}

.distribution-intro p {
  margin: 0;
}

/* En escritorio: dos columnas y separador vertical */
@media (min-width: 860px) {
  .distribution-intro {
    grid-template-columns: 1fr 1fr;
    align-items: flex-start;
  }
  .distribution-intro > div + div {
    border-left: 1px solid #e5e7eb;
    padding-left: 1.5rem;
  }
}

/* Botón azul (si no lo tenías ya) */
.btn {
  display: inline-block;
  margin-top: 6px;
  padding: 6px 12px;
  background: #0f5cc0;
  color: #ffffff !important;
  border-radius: 6px;
  font-size: 14px;
  text-decoration: none;
  font-weight: 500;
}
.btn:hover {
  background: #094089;
}

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
       style="height: 110px;">
</div>

<header>
  <div class="wrap">
    <h2>📚 Editorial Services | Distributor for Latin America 🌐</h2>
    <p class="tagline">
      📞 <a href="https://wa.me/5491151011262">+54 9 11 5101 1262</a> · 
      ✉️ <a href="mailto:ventas@latambook.com">ventas@latambook.com</a> · 
      IG: <a href="https://instagram.com/latambook" target="_blank">@latambook</a>
           📍 <b>Buenos Aires · Rosario | Argentina </b>
    </p>
  </div>
</header>

<div class="wrap">

  <div class="two">
    <div>
      <h2>🇺🇸About us</h2>
      <p><b>LATAMBOOK</b> is a Latin American book distributor with a regional client network. We manage sales, logistics and publisher representation, and provide editorial services (editing, design, translation, copy-editing; <b>ISBN/barcode</b> issuance registered at the Argentine Book Chamber).</p>
      <p>Through our publishing imprints <b>La Mora</b> (literary–poetic) and <b>SurAmerica</b> (specialized in human and social sciences), both founded in 2010, we produce books in both print and digital formats.</p>
    </div>

    <div>
      <h2>🇦🇷Sobre nosotros</h2>
      <p><b>LATAMBOOK</b> opera como distribuidora editorial con red de clientes en toda Latinoamérica. Gestionamos ventas, logística y representación de sellos locales, y también ofrecemos servicios de <i>edición</i>, diseño, traducción, corrección y tramitación de <b>ISBN / código de barras</b> (registrados en la Cámara Argentina del Libro).</p>
      <p>Desde 2010 brindamos servicios editoriales a través de nuestros sellos: <b>La Mora</b> — orientado a poesía y literatura — y <b>SurAmerica ediciones</b> — especializado en Ciencias Humanas y Sociales.</p>
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
        <li><b>Publishing</b> — print edition, digital version, print on demand.</li>
        <li><b>Commercialization</b> - representation and distribution</li>
      </ul>
    </div>

    <div>
      <h2>👷‍♀️Servicio editorial integral</h2>
      <p class="muted">Profesionalismo en todas las etapas de producción editorial.</p>
      <ul>
        <li><b>Corrección de estilo</b> — revisión lingüística, coherencia y sentido.</li>
        <li><b>Traducción</b> — español ↔ inglés u otros idiomas.</li>
        <li><b>Diseño gráfico</b> — diseño de portada e identidad visual.</li>
        <li><b>Diagramación</b> — maquetación del interior del libro.</li>
        <li><b>Gestión de ISBN y código de barras</b> — tramitación en la Cámara Argentina del Libro.</li>
        <li><b>Publicación</b> — impresión, versión digital, impresion bajo demanda</li>
        <li><b>Comercialización</b> - representación y distribución</li>
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
      <p class="muted">Sello: <b>SurAmerica</b> · Autor: Roberto Retamoso · ISBN: 9789872593919</p>
    </article>

     <article class="card">
      <img src="img/IMG_9373.jpeg" alt="Disculpen – portada" loading="lazy">
      <h3>Disculpen</h3>
      <p class="muted">Sello: <b>La Mora</b> · Autor: Juan Cairo · ISBN: 9789872593735</p>
    </article>

     <article class="card">
      <img src="img/IMG_9369.jpeg" alt="Manual de Etica – portada" loading="lazy">
      <h3>Manual de Etica para corredores inmobiliarios</h3>
      <p class="muted">Sello: <b>SurAmerica</b> · Autor: Lic. Julio Farah · ISBN: 9789872593926</p>
    </article>

    <article class="card">
      <img src="img/La-linea-de-tu-mano.jpeg" alt="La linea de tu mano – portada" loading="lazy">
      <h3>La linea de tu mano</h3>
      <p class="muted">Sello: <b>La Mora</b> · Autor: Maria Vilaltas · ISBN: 9789872593728</p>
    </article>

    <article class="card">
      <img src="img/historia-oral.jpeg" alt="Historia oral – portada" loading="lazy">
      <h3>Historia Oral</h3>
      <p class="muted">Sello: <b>SurAmerica</b> · Autor: Laura benadiba · ISBN: 9789872593902</p>
    </article>
    
  </section>

</div>
<!-- DISTRIBUCIÓN ACADÉMICA -->
<h2>📚 Academic Book Distribution</h2>

  Specialized distribution of academic, technical and professional books (print & e-books).
  <p class="muted">
</p>

<div class="distribution-intro">
  <div>
    <p>
      <b>EN</b> — LATAMBOOK is a distributor of academic, professional, and scientific books in Spanish.
Our catalogue includes medicine, nursing, psychology, neuroscience, neurodevelopment, education, technology, economics, social sciences, and humanities.
We provide <strong>👩🏻‍💻commercial management, 📦specialized logistics, and ✈️international DHL shipping worldwide</strong>
    </p>
  </div>
  <div>
    <p>
      <b>ES</b> — LATAMBOOK es una distribuidora de libros académicos, profesionales y científicos en español.
Nuestro catálogo abarca medicina, enfermería, psicología, neurociencias, neurodesarrollo, educación, tecnología, ciencias económicas, ciencias sociales y humanidades.
Ofrecemos <strong>👩🏻‍💻gestión comercial, 📦logística especializada y ✈️envíos internacionales vía DHL</strong> a todo el mundo 
    </p>
  </div>
</div>
<!-- ========================= -->
<!--   Separador + Título Sellos en Distribución -->
<!-- ========================= -->

<hr style="border:0; border-top:1px solid #e2e2e2; margin:40px 0 24px;">

<div class="wrap" style="text-align:center; margin-bottom:32px;">
  <h2 style="margin-bottom:4px;">📚 Publishing Houses in Distribution</h2>
  
</div>

<!-- Grid de editoriales en distribución -->
<div class="grid">

  <!-- Manual Moderno -->
  <article class="card">
    <img src="img/Manual-Moderno.png" alt="Manual Moderno logo" class="publisher-logo">
    <h3>Manual Moderno</h3>
    <p class="muted">Medicine · Psychology</p>
    <a href="mailto:ventas@latambook.com?subject=Request%20price%20list%20Manual%20Moderno"
       class="btn">Request price list</a>
  </article>

  <!-- Akadia -->
  <article class="card">
    <img src="img/AKADIA.webp" alt="Akadia logo" class="publisher-logo">
    <h3>Akadia</h3>
    <p class="muted">Psychology · Education</p>
    <a href="mailto:ventas@latambook.com?subject=Request%20price%20list%20Akadia"
       class="btn">Request price list</a>
  </article>

  <!-- Neuroaprendizaje Infantil -->
  <article class="card">
    <img src="img/neuroaprendizaje%20infantil.png" alt="Neuroaprendizaje Infantil logo" class="publisher-logo">
    <h3>Neuroaprendizaje Infantil</h3>
    <p class="muted">Neurodiversity · Neurodevelopment</p>
    <a href="mailto:ventas@latambook.com?subject=Request%20price%20list%20Neuroaprendizaje%20Infantil"
       class="btn">Request price list</a>
  </article>

  <!-- Amorrortu -->
  <article class="card">
    <img src="img/amorrortu.jpeg" alt="Amorrortu logo" class="publisher-logo">
    <h3>Amorrortu</h3>
    <p class="muted">Psychology · Social sciences</p>
    <a href="mailto:ventas@latambook.com?subject=Request%20price%20list%20Amorrortu"
       class="btn">Request price list</a>
  </article>

  <!-- Tres Olas -->
  <article class="card">
    <img src="img/tres%20olas.png" alt="Tres Olas logo" class="publisher-logo">
    <h3>Tres Olas</h3>
    <p class="muted">Education · Psychology</p>
    <a href="mailto:ventas@latambook.com?subject=Request%20price%20list%20Tres%20Olas"
       class="btn">Request price list</a>
  </article>

  <!-- Panamericana -->
  <article class="card">
    <img src="img/panamericana.jpeg" alt="Panamericana logo" class="publisher-logo">
    <h3>Panamericana</h3>
    <p class="muted">Medicine · Health sciences</p>
    <a href="mailto:ventas@latambook.com?subject=Request%20price%20list%20Panamericana"
       class="btn">Request price list</a>
  </article>

  <!-- Journal -->
  <article class="card">
    <img src="img/journal-logo.png" alt="Journal logo" class="publisher-logo">
    <h3>Journal</h3>
    <p class="muted"> Medicine · Neurosciences</p>
    <a href="mailto:ventas@latambook.com?subject=Request%20price%20list%20Journal"
       class="btn">Request price list</a>
  </article>

  <!-- El Ateneo -->
  <article class="card">
    <img src="img/el%20ateneo.png" alt="El Ateneo logo" class="publisher-logo">
    <h3>El Ateneo</h3>
    <p class="muted">Medicine · Health sciences</p>
    <a href="mailto:ventas@latambook.com?subject=Request%20price%20list%20El%20Ateneo"
       class="btn">Request price list</a>
  </article>

  <!-- Bonum -->
  <article class="card">
    <img src="img/bonum.webp" alt="Bonum logo" class="publisher-logo">
    <h3>Bonum</h3>
    <p class="muted">Education · Neurodiversity</p>
    <a href="mailto:ventas@latambook.com?subject=Request%20price%20list%20Bonum"
       class="btn">Request price list</a>
  </article>

  <!-- Siglo XXI -->
  <article class="card">
    <img src="img/siglo%20xxi%20edit.jpeg" alt="Siglo XXI logo" class="publisher-logo">
    <h3>Siglo XXI</h3>
    <p class="muted">Psychology · Education</p>
    <a href="mailto:ventas@latambook.com?subject=Request%20price%20list%20Siglo%20XXI"
       class="btn">Request price list</a>
  </article>

  <!-- La Crujía -->
  <article class="card">
    <img src="img/la%20crujia.jpeg" alt="La Crujía logo" class="publisher-logo">
    <h3>La Crujía</h3>
    <p class="muted">Communication · Social sciences</p>
    <a href="mailto:ventas@latambook.com?subject=Request%20price%20list%20La%20Crujia"
       class="btn">Request price list</a>
  </article>

  <!-- Fundación Garrahan -->
  <article class="card">
    <img src="img/fundacion%20garrahan.png" alt="Fundación Garrahan logo" class="publisher-logo">
    <h3>Fundación Garrahan</h3>
    <p class="muted">Pediatrics · Child health</p>
    <a href="mailto:ventas@latambook.com?subject=Request%20price%20list%20Fundacion%20Garrahan"
       class="btn">Request price list</a>
  </article>

  <!-- Eureka Digital (Panamericana) -->
  <article class="card">
    <img src="img/EUREKA%20DIGITAL.jpg" alt="Eureka Digital logo" class="publisher-logo">
    <h3>Eureka Digital</h3>
    <p class="muted">Digital library · Medicine · Health</p>
    <a href="mailto:ventas@latambook.com?subject=Request%20price%20list%20Eureka%20Digital"
       class="btn">Request price list</a>
  </article>

  <!-- Alfaomega -->
  <article class="card">
    <img src="img/alfaomega.png" alt="Alfaomega logo" class="publisher-logo">
    <h3>Alfaomega</h3>
    <p class="muted">Technology · Economics · Informatics</p>
    <a href="mailto:ventas@latambook.com?subject=Request%20price%20list%20Alfaomega"
       class="btn">Request price list</a>
  </article>

  <!-- Eudeba -->
  <article class="card">
    <img src="img/eudeba.jpeg" alt="Eudeba logo" class="publisher-logo">
    <h3>Eudeba</h3>
    <p class="muted">Academic · University presses</p>
    <a href="mailto:ventas@latambook.com?subject=Request%20price%20list%20Eudeba"
       class="btn">Request price list</a>
  </article>

  <!-- Hogrefe -->
  <article class="card">
    <img src="img/hogrefe.png" alt="Hogrefe logo" class="publisher-logo">
    <h3>Hogrefe</h3>
    <p class="muted">Psychology · Neurodiversity</p>
    <a href="mailto:ventas@latambook.com?subject=Request%20price%20list%20Hogrefe"
       class="btn">Request price list</a>
  </article>

</div>

<!-- ========================= -->
<!--   International Fair Representation – Elegant Section -->
<!-- ========================= -->

<hr style="border:0; border-top:1px solid #e2e2e2; margin:40px 0 32px;">

<section class="fairs-section">

  <div class="fairs-header">
    <h2>🌍 Representation at International Book Fairs & Events</h2>
    <p class="muted">Professional presence in Latin American and global publishing events</p>
  </div>

  <div class="fairs-grid">

    <!-- PHOTO 1 -->
    <div class="fil-2024">
      <img src="img/FIL2024.jpg" alt="International Book Fair – Latambook">
      <div class="fair-card-content">
        <h3>Guadalajara International Book Fair</h3>
        <p>Meeting with Universidad de Guadalajara – Institutional Stand</p>
      </div>
    </div>

    <!-- PHOTO 2 -->
    <div class="fair-card">
      <img src="img/fair2.jpeg" alt="Editorial Networking Event">
      <div class="fair-card-content">
        <h3>Professional Editorial Networking</h3>
        <p>Meetings with authors, publishers and distributors</p>
      </div>
    </div>

    <!-- PHOTO 3 -->
    <div class="fair-card">
      <img src="img/fair3.jpeg" alt="Latambook – Book Presentation">
      <div class="fair-card-content">
        <h3>Book Presentation & Catalog Showcase</h3>
        <p>Institutional representation of our imprints</p>
      </div>
    </div>

  </div>

</section>

<!-- Divider -->
<hr style="border:0; border-top:1px solid #e2e2e2; margin:50px 0 32px;">

<!-- Contact Block -->
<section class="wrap" style="margin-bottom: 60px;">

  <h2 style="font-size:22px; margin-bottom:10px;">📞 Contact & Institutional Information</h2>

  <p style="margin:6px 0; font-size:15px;">
    📍 <b> Buenos Aires</b>, Argentina  
    <br>📍 <b>Rosario</b>, Argentina
  </p>

  <p style="margin:6px 0; font-size:15px;">
    📞 WhatsApp: <a href="https://wa.me/5491151011262">+54 9 11 5101 1262</a><br>
    ✉️ Email: <a href="mailto:ventas@latambook.com">ventas@latambook.com</a>
  </p>

  <p style="margin:6px 0; font-size:15px;">
    🧾 <b>CUIT:</b> 27-34579681-5  
  </p>

  <p style="margin:6px 0; font-size:15px; color:#444;">
    📚 <b>Argentine Book Chamber Partner – Nº 2100</b>  
    <b>|LATAMBOOK |La Mora |SurAmerica - All rights reserved®️</b> 
  </p>

</section>


