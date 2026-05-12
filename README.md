<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1.0"/>
<title>Política de Privacidad — Enbio Logistics S.A.</title>
<meta name="description" content="Política de Privacidad de Enbio Logistics S.A. Cédula Jurídica 3-101-793496."/>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet"/>
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --navy:#0B1F3A;
  --navy-light:#1A3557;
  --blue:#1D6FA4;
  --blue-light:#E8F3FA;
  --text:#1A1A2E;
  --muted:#5A6A7A;
  --border:#D8E4EE;
  --bg:#F7F9FC;
  --white:#FFFFFF;
}
body{font-family:'Inter',system-ui,sans-serif;background:var(--bg);color:var(--text);line-height:1.7;font-size:15px}
/* HEADER */
header{background:var(--navy);border-bottom:4px solid var(--blue)}
.header-inner{max-width:1000px;margin:0 auto;padding:1.5rem 2rem;display:flex;align-items:center;gap:1.5rem}
.header-inner img{height:40px;filter:brightness(0) invert(1)}
.divider{width:1px;height:36px;background:rgba(255,255,255,.2)}
.company-info{flex:1}
.company-name{font-size:1.1rem;font-weight:700;color:#FFF;letter-spacing:-.01em}
.company-sub{font-size:.75rem;color:rgba(255,255,255,.55);margin-top:2px}
.doc-badge{background:var(--blue);color:#FFF;font-size:.65rem;font-weight:600;letter-spacing:.1em;text-transform:uppercase;padding:.35rem .9rem;border-radius:4px}
/* BREADCRUMB BAR */
.breadcrumb{background:var(--navy-light);padding:.6rem 2rem}
.breadcrumb-inner{max-width:1000px;margin:0 auto;font-size:.75rem;color:rgba(255,255,255,.55)}
.breadcrumb-inner span{color:rgba(255,255,255,.9)}
/* HERO */
.hero{background:var(--white);border-bottom:1px solid var(--border)}
.hero-inner{max-width:1000px;margin:0 auto;padding:3rem 2rem;display:flex;align-items:center;gap:3rem}
.hero-text h1{font-size:2rem;font-weight:700;letter-spacing:-.03em;color:var(--navy);line-height:1.2;margin-bottom:.75rem}
.hero-text h1 span{color:var(--blue)}
.hero-text p{color:var(--muted);max-width:520px;font-size:.95rem}
.hero-meta{display:flex;gap:1rem;margin-top:1.25rem;flex-wrap:wrap}
.meta-pill{display:flex;align-items:center;gap:.4rem;background:var(--blue-light);border:1px solid #BDD6E8;border-radius:4px;padding:.4rem .9rem;font-size:.75rem;color:var(--navy);font-weight:500}
.hero-shield{font-size:5rem;flex-shrink:0;opacity:.15}
/* LAYOUT */
main{max-width:1000px;margin:2.5rem auto;padding:0 2rem;display:grid;grid-template-columns:220px 1fr;gap:2rem}
/* SIDEBAR */
.sidebar{align-self:flex-start;position:sticky;top:2rem}
.toc-card{background:var(--white);border:1px solid var(--border);border-radius:8px;overflow:hidden}
.toc-header{background:var(--navy);color:#FFF;font-size:.7rem;font-weight:600;letter-spacing:.1em;text-transform:uppercase;padding:.8rem 1rem}
.toc-card a{display:block;padding:.6rem 1rem;font-size:.82rem;color:var(--muted);text-decoration:none;border-bottom:1px solid var(--border);border-left:3px solid transparent;transition:all .15s}
.toc-card a:last-child{border-bottom:0}
.toc-card a:hover{color:var(--blue);border-left-color:var(--blue);background:var(--blue-light)}
.contact-card{background:var(--navy);border-radius:8px;padding:1.25rem;margin-top:1rem}
.contact-card-title{font-size:.65rem;font-weight:600;letter-spacing:.1em;text-transform:uppercase;color:rgba(255,255,255,.5);margin-bottom:.75rem}
.contact-item{display:flex;flex-direction:column;margin-bottom:.75rem}
.contact-item:last-child{margin-bottom:0}
.contact-label{font-size:.65rem;color:rgba(255,255,255,.4);text-transform:uppercase;letter-spacing:.08em}
.contact-value{font-size:.8rem;color:#FFF;margin-top:2px}
.contact-value a{color:#5BC4F0;text-decoration:none}
/* CONTENT */
.content{}
.section{background:var(--white);border:1px solid var(--border);border-radius:8px;margin-bottom:1rem;overflow:hidden}
.section-header{display:flex;align-items:center;gap:.75rem;padding:1.25rem 1.5rem;border-bottom:1px solid var(--border);background:var(--bg)}
.section-num{width:28px;height:28px;background:var(--navy);color:#FFF;border-radius:6px;display:flex;align-items:center;justify-content:center;font-size:.75rem;font-weight:700;flex-shrink:0}
.section-title{font-size:.95rem;font-weight:600;color:var(--navy)}
.section-body{padding:1.5rem}
.section-body p{color:var(--muted);font-size:.9rem;margin-bottom:.75rem}
.section-body p:last-child{margin-bottom:0}
.section-body ul{padding-left:1.25rem}
.section-body li{color:var(--muted);font-size:.9rem;margin-bottom:.4rem}
.section-body li::marker{color:var(--blue)}
.alert{background:var(--blue-light);border:1px solid #BDD6E8;border-left:4px solid var(--blue);border-radius:4px;padding:1rem;margin-top:.75rem}
.alert p{color:var(--navy);font-size:.85rem;margin:0}
.info-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:.75rem;margin-top:.75rem}
.info-card{background:var(--bg);border:1px solid var(--border);border-radius:6px;padding:.9rem}
.info-label{font-size:.65rem;text-transform:uppercase;letter-spacing:.1em;color:var(--muted);margin-bottom:.3rem}
.info-value{font-size:.85rem;font-weight:500;color:var(--text)}
.info-value a{color:var(--blue);text-decoration:none}
strong{color:var(--text)}
/* SOCIAL */
.social-row{display:flex;gap:.75rem;margin-top:.75rem;flex-wrap:wrap}
.social-link{display:flex;align-items:center;gap:.4rem;background:var(--bg);border:1px solid var(--border);border-radius:4px;padding:.4rem .8rem;font-size:.8rem;color:var(--muted);text-decoration:none;transition:all .15s}
.social-link:hover{border-color:var(--blue);color:var(--blue)}
/* FOOTER */
footer{background:var(--navy);margin-top:2rem}
.footer-inner{max-width:1000px;margin:0 auto;padding:2rem;display:flex;align-items:center;justify-content:space-between;gap:1rem;flex-wrap:wrap}
.footer-inner img{height:28px;filter:brightness(0) invert(1);opacity:.6}
.footer-text{font-size:.75rem;color:rgba(255,255,255,.4);text-align:right}
@media(max-width:720px){
  main{grid-template-columns:1fr}
  .sidebar{position:static}
  .hero-shield{display:none}
  .hero-inner{flex-direction:column;gap:1rem}
}
</style>
</head>
<body>
<!-- HEADER -->
<header>
  <div class="header-inner">
    <img src="https://www.enbiocr.com/static/media/enbio-logo-tiny.bd5f6dd6433fb280092d.png" alt="Enbio Logistics"/>
    <div class="divider"></div>
    <div class="company-info">
      <div class="company-name">Enbio Logistics S.A.</div>
      <div class="company-sub">Cédula Jurídica: 3-101-793496 · Costa Rica, Heredia, Belén</div>
    </div>
    <div class="doc-badge">Documento Oficial</div>
  </div>
</header>
<div class="breadcrumb">
  <div class="breadcrumb-inner">
    <a href="https://www.enbiocr.com" style="color:rgba(255,255,255,.55);text-decoration:none">enbiocr.com</a> › <span>Política de Privacidad</span>
  </div>
</div>
<!-- HERO -->
<div class="hero">
  <div class="hero-inner">
    <div class="hero-text">
      <h1>Política de <span>Privacidad</span></h1>
      <p>Este documento regula el tratamiento de datos personales efectuado por Enbio Logistics S.A. en el marco de sus operaciones comerciales y canales de comunicación digital.</p>
      <div class="hero-meta">
        <div class="meta-pill">📅 Vigente desde Mayo 2025</div>
        <div class="meta-pill">⚖️ Ley N.° 8968 — Costa Rica</div>
        <div class="meta-pill">🔒 Versión 1.0</div>
      </div>
    </div>
    <div class="hero-shield">🔐</div>
  </div>
</div>
<!-- MAIN -->
<main>
  <!-- SIDEBAR -->
  <aside class="sidebar">
    <div class="toc-card">
      <div class="toc-header">Contenido</div>
      <a href="#s1">1. Responsable</a>
      <a href="#s2">2. Datos recopilados</a>
      <a href="#s3">3. Finalidad</a>
      <a href="#s4">4. WhatsApp Business</a>
      <a href="#s5">5. Almacenamiento</a>
      <a href="#s6">6. Derechos</a>
      <a href="#s7">7. Seguridad</a>
      <a href="#s8">8. Terceros</a>
      <a href="#s9">9. Contacto</a>
    </div>
    <div class="contact-card">
      <div class="contact-card-title">Contacto Rápido</div>
      <div class="contact-item">
        <span class="contact-label">Oficial</span>
        <span class="contact-value"><a href="tel:+50672737654">(+506) 7273-7654</a></span>
      </div>
      <div class="contact-item">
        <span class="contact-label">Administración</span>
        <span class="contact-value"><a href="tel:+50688928269">(+506) 8892-8269</a></span>
      </div>
      <div class="contact-item">
        <span class="contact-label">Email</span>
        <span class="contact-value"><a href="mailto:info@enbiocr.com">info@enbiocr.com</a></span>
      </div>
      <div class="contact-item">
        <span class="contact-label">Web</span>
        <span class="contact-value"><a href="https://www.enbiocr.com" target="_blank">www.enbiocr.com</a></span>
      </div>
    </div>
  </aside>
  <!-- CONTENT -->
  <div class="content">
    <div class="section" id="s1">
      <div class="section-header">
        <div class="section-num">1</div>
        <h2 class="section-title">Responsable del Tratamiento de Datos</h2>
      </div>
      <div class="section-body">
        <p>El responsable del tratamiento es <strong>Enbio Logistics S.A.</strong>, empresa debidamente constituida bajo las leyes de la República de Costa Rica, dedicada a la importación, logística de carga y mensajería nacional e internacional.</p>
        <div class="info-grid">
          <div class="info-card"><div class="info-label">Razón Social</div><div class="info-value">Enbio Logistics S.A.</div></div>
          <div class="info-card"><div class="info-label">Cédula Jurídica</div><div class="info-value">3-101-793496</div></div>
          <div class="info-card"><div class="info-label">Dirección</div><div class="info-value">Heredia, Belén, San Antonio, Costa Rica</div></div>
          <div class="info-card"><div class="info-label">Sitio Web</div><div class="info-value"><a href="https://www.enbiocr.com" target="_blank">www.enbiocr.com</a></div></div>
        </div>
      </div>
    </div>
    <div class="section" id="s2">
      <div class="section-header">
        <div class="section-num">2</div>
        <h2 class="section-title">Datos Personales que Recopilamos</h2>
      </div>
      <div class="section-body">
        <p>En el marco de la prestación de nuestros servicios, podemos recopilar las siguientes categorías de datos:</p>
        <ul>
          <li><strong>Identificación:</strong> Nombre completo, número de cédula o pasaporte.</li>
          <li><strong>Contacto:</strong> Número de teléfono (WhatsApp), correo electrónico, dirección física de entrega.</li>
          <li><strong>Transacciones:</strong> Historial de envíos, guías de seguimiento, facturas y comprobantes.</li>
          <li><strong>Comunicaciones:</strong> Mensajes intercambiados vía WhatsApp Business API, registrados en CRM interno.</li>
          <li><strong>Técnicos:</strong> Dirección IP y datos de sesión en plataformas propias.</li>
        </ul>
      </div>
    </div>
    <div class="section" id="s3">
      <div class="section-header">
        <div class="section-num">3</div>
        <h2 class="section-title">Finalidad del Tratamiento</h2>
      </div>
      <div class="section-body">
        <p>Los datos personales son tratados exclusivamente para:</p>
        <ul>
          <li>Gestionar y ejecutar servicios de importación, logística y mensajería.</li>
          <li>Comunicar el estado de envíos, guías y entregas.</li>
          <li>Emitir facturas electrónicas y comprobantes tributarios.</li>
          <li>Atender consultas, reclamos y solicitudes de soporte.</li>
          <li>Cumplir con obligaciones legales vigentes en Costa Rica.</li>
        </ul>
        <div class="alert"><p>⚡ <strong>No compartimos, vendemos ni transferimos</strong> datos personales a terceros con fines publicitarios o comerciales sin consentimiento expreso del titular.</p></div>
      </div>
    </div>
    <div class="section" id="s4">
      <div class="section-header">
        <div class="section-num">4</div>
        <h2 class="section-title">Canal de Comunicación — WhatsApp Business API</h2>
      </div>
      <div class="section-body">
        <p>Enbio Logistics S.A. utiliza la <strong>WhatsApp Business Cloud API</strong> de Meta Platforms, Inc. Al enviarnos un mensaje vía WhatsApp usted acepta que:</p>
        <ul>
          <li>Sus mensajes son procesados por infraestructura de Meta según sus <a href="https://www.whatsapp.com/legal/privacy-policy" target="_blank">Términos de Servicio</a>.</li>
          <li>El contenido de la conversación puede almacenarse en nuestra plataforma CRM (Chatwoot), alojada en servidores seguros en la Unión Europea.</li>
          <li>El acceso a las conversaciones está restringido exclusivamente al personal autorizado de Enbio.</li>
          <li>Puede solicitar la eliminación de su historial en cualquier momento escribiendo a <a href="mailto:admin@enbiocr.com">admin@enbiocr.com</a>.</li>
        </ul>
      </div>
    </div>
    <div class="section" id="s5">
      <div class="section-header">
        <div class="section-num">5</div>
        <h2 class="section-title">Almacenamiento y Conservación</h2>
      </div>
      <div class="section-body">
        <ul>
          <li><strong>Ubicación:</strong> Servidores en Alemania (UE), bajo jurisdicción del RGPD.</li>
          <li><strong>Cifrado:</strong> Transmisión protegida con TLS 1.3 y almacenamiento cifrado en reposo.</li>
          <li><strong>Retención:</strong> Mientras dure la relación comercial y hasta 5 años adicionales por obligaciones fiscales.</li>
          <li><strong>Acceso:</strong> Restringido mediante autenticación multifactor y control por roles.</li>
        </ul>
      </div>
    </div>
    <div class="section" id="s6">
      <div class="section-header">
        <div class="section-num">6</div>
        <h2 class="section-title">Derechos del Titular de Datos</h2>
      </div>
      <div class="section-body">
        <p>Conforme a la <strong>Ley N.° 8968 de Costa Rica</strong>, usted tiene derecho a:</p>
        <ul>
          <li><strong>Acceso:</strong> Solicitar información sobre sus datos personales que tratamos.</li>
          <li><strong>Rectificación:</strong> Corregir datos incorrectos o desactualizados.</li>
          <li><strong>Supresión:</strong> Solicitar eliminación cuando no sean necesarios para la finalidad original.</li>
          <li><strong>Oposición:</strong> Oponerse al tratamiento en determinadas circunstancias.</li>
          <li><strong>Portabilidad:</strong> Recibir sus datos en formato estructurado y legible por máquina.</li>
        </ul>
        <div class="alert"><p>📩 Para ejercer sus derechos, contáctenos a <a href="mailto:admin@enbiocr.com"><strong>admin@enbiocr.com</strong></a>. Atendemos en un plazo máximo de <strong>30 días hábiles</strong>.</p></div>
      </div>
    </div>
    <div class="section" id="s7">
      <div class="section-header">
        <div class="section-num">7</div>
        <h2 class="section-title">Medidas de Seguridad</h2>
      </div>
      <div class="section-body">
        <ul>
          <li>Cifrado end-to-end en todas las comunicaciones digitales.</li>
          <li>Control de acceso por roles y perfiles de usuario autorizados.</li>
          <li>Monitoreo continuo de la infraestructura tecnológica.</li>
          <li>Copias de seguridad periódicas y planes de recuperación ante desastres.</li>
          <li>Firewall de perímetro con política de puertos mínimos.</li>
        </ul>
      </div>
    </div>
    <div class="section" id="s8">
      <div class="section-header">
        <div class="section-num">8</div>
        <h2 class="section-title">Proveedores Tecnológicos (Terceros)</h2>
      </div>
      <div class="section-body">
        <p>Para la prestación de servicios trabajamos con los siguientes proveedores que pueden tener acceso limitado y controlado a datos:</p>
        <ul>
          <li><strong>Meta Platforms, Inc.:</strong> Infraestructura WhatsApp Business Cloud API.</li>
          <li><strong>Cloudflare, Inc.:</strong> Seguridad de red y proxy perimetral.</li>
          <li><strong>Contabo GmbH:</strong> Alojamiento de servidores (Alemania, UE).</li>
        </ul>
        <p>Todos están sujetos a acuerdos de confidencialidad y normativas de protección de datos aplicables.</p>
      </div>
    </div>
    <div class="section" id="s9">
      <div class="section-header">
        <div class="section-num">9</div>
        <h2 class="section-title">Contacto y Canales Oficiales</h2>
      </div>
      <div class="section-body">
        <div class="info-grid">
          <div class="info-card"><div class="info-label">Tel. Oficial</div><div class="info-value"><a href="tel:+50672737654">(+506) 7273-7654</a></div></div>
          <div class="info-card"><div class="info-label">Administración</div><div class="info-value"><a href="tel:+50688928269">(+506) 8892-8269</a></div></div>
          <div class="info-card"><div class="info-label">Info</div><div class="info-value"><a href="mailto:info@enbiocr.com">info@enbiocr.com</a></div></div>
          <div class="info-card"><div class="info-label">Admin</div><div class="info-value"><a href="mailto:admin@enbiocr.com">admin@enbiocr.com</a></div></div>
          <div class="info-card"><div class="info-label">Dirección</div><div class="info-value">Heredia, Belén, San Antonio, CR</div></div>
          <div class="info-card"><div class="info-label">Web</div><div class="info-value"><a href="https://www.enbiocr.com" target="_blank">www.enbiocr.com</a></div></div>
        </div>
        <div class="social-row">
          <a href="https://www.facebook.com/enbiocr" target="_blank" class="social-link">📘 Facebook</a>
          <a href="https://www.instagram.com/enbio_cr" target="_blank" class="social-link">📸 Instagram</a>
          <a href="https://www.tiktok.com/@enbioenbio" target="_blank" class="social-link">🎵 TikTok</a>
        </div>
        <div class="alert" style="margin-top:.75rem"><p>🔄 Esta política puede actualizarse periódicamente. Notificaremos cambios significativos a través de nuestros canales oficiales.</p></div>
      </div>
    </div>
  </div>
</main>
<!-- FOOTER -->
<footer>
  <div class="footer-inner">
    <img src="https://www.enbiocr.com/static/media/enbio-logo-tiny.bd5f6dd6433fb280092d.png" alt="Enbio Logistics"/>
    <div class="footer-text">
      <p>Enbio Logistics S.A. · Cédula 3-101-793496 · Heredia, Belén, Costa Rica</p>
      <p>Importación USA & China → CR | Vuelos diarios ✈️ | Atención 5⭐</p>
      <p style="margin-top:.5rem">Política de Privacidad v1.0 — Mayo 2025 · Ley N.° 8968 de Costa Rica</p>
    </div>
  </div>
</footer>
</body>
</html>
