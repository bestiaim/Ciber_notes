---
layout: default
title: Ciber-Notes Bestiaim
---

<style>
/* =========================================================
   BESTIAIM - Página inicial personalizada
   ========================================================= */

/* Oculta el encabezado automático del tema Hacker */
body > header {
  display: none !important;
}

/* Ajusta el contenido al ocultar el encabezado del tema */
#main_content {
  padding-top: 20px !important;
}

/* Fondo general */
body {
  background: #0b0f14 !important;
  color: #d1d5db !important;
}

/* Contenedores del tema */
.markdown-body,
.container-lg,
.wrapper,
#main_content {
  background: #0b0f14 !important;
  color: #d1d5db !important;
}

/* Contenedor principal */
.cibernotes-home {
  max-width: 1080px;
  margin: 0 auto;
  padding: 20px 15px 60px;
}

/* Encabezado propio */
.hero {
  text-align: center;
  padding: 30px 15px 38px;
  border-bottom: 1px solid #1f2937;
  margin-bottom: 38px;
}

/* Logo BESTIAIM */
.hero-logo {
  display: block;
  width: 100%;
  max-width: 360px;
  height: auto;
  margin: 0 auto 22px;
  border-radius: 14px;
  box-shadow: 0 0 35px rgba(56, 189, 248, 0.22);
}

/* Título principal */
.hero h1 {
  margin: 0;
  color: #38bdf8;
  font-size: 2.8rem;
  letter-spacing: 2px;
  text-shadow: 0 0 14px rgba(56, 189, 248, 0.35);
}

/* Subtítulo */
.hero p {
  margin-top: 14px;
  color: #cbd5e1;
  font-size: 1.05rem;
}

/* Información del repositorio */
.repo-mini {
  margin-top: 16px;
  color: #9ca3af;
  font-size: 0.92rem;
}

/* Botón de GitHub */
.repo-mini a {
  display: inline-block;
  margin-top: 12px;
  padding: 7px 14px;
  border: 1px solid #22c55e;
  border-radius: 999px;
  background: #020617;
  color: #22c55e !important;
  font-size: 0.86rem;
  font-weight: 600;
  text-decoration: none;
}

.repo-mini a:hover {
  background: #22c55e;
  color: #020617 !important;
  text-decoration: none;
}

/* Títulos de sección */
.section-title {
  margin: 35px 0 20px;
  padding-bottom: 10px;
  border-bottom: 1px solid #1f2937;
  color: #e5e7eb;
  font-size: 1.8rem;
}

/* Tarjetas */
.machine-card {
  display: flex;
  align-items: center;
  gap: 24px;
  margin: 26px 0;
  padding: 18px;
  border: 1px solid #1f2937;
  border-left: 4px solid #22c55e;
  border-radius: 14px;
  background: #111827;
  box-shadow: 0 0 18px rgba(34, 197, 94, 0.08);
  transition:
    border-color 0.2s ease-in-out,
    transform 0.2s ease-in-out,
    box-shadow 0.2s ease-in-out;
}

.machine-card:hover {
  border-color: #22c55e;
  transform: translateY(-2px);
  box-shadow: 0 0 25px rgba(34, 197, 94, 0.18);
}

/* Imagen de la tarjeta */
.machine-card img {
  width: 330px;
  height: 185px;
  flex-shrink: 0;
  object-fit: cover;
  border: 1px solid #334155;
  border-radius: 10px;
  background: #020617;
}

/* Contenido de la tarjeta */
.machine-content {
  flex: 1;
  min-width: 0;
}

.machine-content h2 {
  margin-top: 0;
  margin-bottom: 10px;
  font-size: 1.55rem;
}

.machine-content h2 a {
  color: #f9fafb !important;
  text-decoration: none;
}

.machine-content h2 a:hover {
  color: #38bdf8 !important;
  text-decoration: none;
}

.machine-content p {
  margin-bottom: 12px;
  color: #cbd5e1;
  line-height: 1.6;
}

/* Etiquetas */
.tags {
  margin: 12px 0;
}

.tag {
  display: inline-block;
  margin-right: 6px;
  margin-bottom: 6px;
  padding: 4px 10px;
  border: 1px solid #334155;
  border-radius: 999px;
  background: #1e293b;
  color: #38bdf8;
  font-size: 0.82rem;
}

/* Metadatos */
.meta {
  margin-top: 10px;
  color: #9ca3af;
  font-size: 0.9rem;
}

/* Botones de las tarjetas */
.card-actions {
  margin-top: 14px;
}

.btn-writeup {
  display: inline-block;
  padding: 8px 14px;
  border: 1px solid #22c55e;
  border-radius: 8px;
  background: #16a34a;
  color: #ffffff !important;
  font-weight: 600;
  text-decoration: none;
}

.btn-writeup:hover {
  background: #22c55e;
  color: #020617 !important;
  text-decoration: none;
}

/* Caja de aviso */
.warning-box {
  margin-top: 38px;
  padding: 16px;
  border-left: 4px solid #f97316;
  border-radius: 10px;
  background: #111827;
  color: #d1d5db;
  line-height: 1.6;
}

.warning-box strong {
  color: #fb923c;
}

/* Ajuste para pantallas pequeñas */
@media (max-width: 850px) {
  .machine-card {
    flex-direction: column;
    align-items: flex-start;
  }

  .machine-card img {
    width: 100%;
    height: auto;
    max-height: 320px;
  }

  .hero h1 {
    font-size: 2.1rem;
  }

  .hero-logo {
    max-width: 280px;
  }
}
</style>

<div class="cibernotes-home">

  <div class="hero">
    <img
      class="hero-logo"
      src="assets/img/logo-bestiaim.png"
      alt="Logo de BESTIAIM"
    >

    <h1>Ciber-Notes Bestiaim</h1>

    <p>
      Write-ups, apuntes e informes de laboratorios de ciberseguridad.
    </p>

    <div class="repo-mini">
      <span>
        Repositorio personal de documentación técnica, laboratorios de pentesting
        y notas de ciberseguridad.
      </span>

      <br>

      <a
        href="https://github.com/bestiaim/Ciber_notes"
        target="_blank"
        rel="noopener noreferrer"
      >
        Ver repositorio en GitHub
      </a>
    </div>
  </div>

  <h2 class="section-title">Máquinas resueltas e informes</h2>

  <!-- =====================================================
       NodeCeption
       ===================================================== -->

  <div class="machine-card">
    <img
      src="assets/img/cards/nodeception.png"
      alt="Máquina vulnerable NodeCeption"
    >

    <div class="machine-content">
      <h2>
        <a href="maquinas/nodeception.html">
          NodeCeption - Pentesting Lab
        </a>
      </h2>

      <p>
        Resolución paso a paso de la máquina vulnerable NodeCeption. El laboratorio
        incluye reconocimiento, escaneo de puertos, enumeración web, análisis de
        endpoints expuestos, explotación mediante el abuso de una automatización
        en n8n y escalada local de privilegios hasta obtener acceso root.
      </p>

      <div class="tags">
        <span class="tag">Linux</span>
        <span class="tag">n8n</span>
        <span class="tag">Web</span>
        <span class="tag">REST API</span>
        <span class="tag">Reverse Shell</span>
        <span class="tag">Privilege Escalation</span>
      </div>

      <div class="meta">
        Laboratorio académico · Write-up de pentesting
      </div>

      <div class="card-actions">
        <a
          class="btn-writeup"
          href="maquinas/nodeception.html"
        >
          Ver write-up
        </a>
      </div>
    </div>
  </div>

  <!-- =====================================================
       Cyberpunk
       ===================================================== -->

  <div class="machine-card">
    <img
      src="assets/img/cards/cyberpunk.png"
      alt="Máquina vulnerable Cyberpunk"
    >

    <div class="machine-content">
      <h2>
        <a href="maquinas/cyberpunk.html">
          Cyberpunk - Pentesting Lab
        </a>
      </h2>

      <p>
        Resolución técnica de la máquina Cyberpunk. El proceso documenta acceso
        FTP anónimo, exposición de archivos mediante Apache, carga de archivos en
        el webroot, ejecución de PHP, obtención de una shell inicial y escalada de
        privilegios mediante Python Library Hijacking.
      </p>

      <div class="tags">
        <span class="tag">Linux</span>
        <span class="tag">FTP</span>
        <span class="tag">Apache</span>
        <span class="tag">PHP</span>
        <span class="tag">Webroot Upload</span>
        <span class="tag">Python Hijacking</span>
      </div>

      <div class="meta">
        Laboratorio académico · Write-up de pentesting
      </div>

      <div class="card-actions">
        <a
          class="btn-writeup"
          href="maquinas/cyberpunk.html"
        >
          Ver write-up
        </a>
      </div>
    </div>
  </div>

  <!-- =====================================================
       Pentest Active Directory
       ===================================================== -->

<div class="machine-card">
    <img
      src="assets/img/cards/pentest-ad.png"
      alt="Informe de pentest Active Directory"
    >

<div class="machine-content">
  <h2>
    <a
      href="maquinas/pentest-ad.html"
    >
      Pentest Active Directory - Laboratorio
    </a>
  </h2>

  <p>
    Informe técnico anonimizado de una prueba de penetración ejecutada sobre
    un entorno Active Directory controlado. El laboratorio documenta
    exposición de respaldos web, extracción de información mediante
    esteganografía, enumeración anónima de LDAP y RPC, AS-REP Roasting,
    Kerberoasting, revisión de SYSVOL y Group Policy Preferences, análisis
    con BloodHound y validación de privilegios administrativos.
  </p>

  <div class="tags">
    <span class="tag">Windows Server</span>
    <span class="tag">Active Directory</span>
    <span class="tag">LDAP</span>
    <span class="tag">Kerberos</span>
    <span class="tag">AS-REP Roasting</span>
    <span class="tag">Kerberoasting</span>
    <span class="tag">BloodHound</span>
    <span class="tag">GPP</span>
  </div>

  <div class="meta">
    Laboratorio autorizado · Informe público anonimizado
  </div>

  <div class="card-actions">
    <a
      class="btn-writeup"
      href="maquinas/pentest-ad.html"
    >
      Ver informe
    </a>
  </div>
</div>
</div>
  <div class="warning-box">
    <strong>Aviso de uso:</strong>
    todo el contenido publicado corresponde a laboratorios controlados,
    máquinas vulnerables académicas o entornos autorizados. No se debe aplicar
    ninguna técnica descrita contra sistemas reales, redes de terceros o activos
    sin autorización explícita.
  </div>

</div>
