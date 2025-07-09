# 2025 Entwicklungs-Portfolio

<style>
.portfolio-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

.category-section {
  margin-bottom: 40px;
}

.category-title {
  font-size: 2em;
  color: #2d3748;
  margin-bottom: 20px;
  padding-bottom: 10px;
  border-bottom: 3px solid #4299e1;
  display: flex;
  align-items: center;
  gap: 10px;
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.project-card {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  border-radius: 12px;
  padding: 24px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  color: white;
  position: relative;
  overflow: hidden;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.2);
}

.project-card.web {
  background: linear-gradient(135deg, #11998e 0%, #38ef7d 100%);
}

.project-card.automation {
  background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%);
  color: #2d3748;
}

.project-card.infrastructure {
  background: linear-gradient(135deg, #a8edea 0%, #fed6e3 100%);
  color: #2d3748;
}

.project-card.hardware {
  background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 100%);
  color: #2d3748;
}

.project-card.specialized {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

.project-header {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-bottom: 16px;
}

.project-icon {
  font-size: 2.5em;
  opacity: 0.9;
}

.project-title {
  font-size: 1.4em;
  font-weight: bold;
  margin: 0;
}

.project-description {
  margin: 12px 0;
  font-size: 0.95em;
  opacity: 0.9;
  line-height: 1.5;
}

.project-links {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 16px;
}

.project-link {
  background: rgba(255, 255, 255, 0.2);
  padding: 6px 12px;
  border-radius: 20px;
  text-decoration: none;
  color: inherit;
  font-size: 0.85em;
  transition: background 0.3s ease;
  display: flex;
  align-items: center;
  gap: 4px;
}

.project-link:hover {
  background: rgba(255, 255, 255, 0.3);
  color: inherit;
}

.toc-container {
  background: #f7fafc;
  border-radius: 12px;
  padding: 20px;
  margin: 20px 0;
  border-left: 4px solid #4299e1;
}

.toc-title {
  font-size: 1.3em;
  color: #2d3748;
  margin-bottom: 15px;
  font-weight: bold;
}

.toc-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 10px;
}

.toc-item {
  background: white;
  padding: 12px 16px;
  border-radius: 8px;
  border: 1px solid #e2e8f0;
  transition: all 0.3s ease;
}

.toc-item:hover {
  background: #edf2f7;
  border-color: #4299e1;
}

.toc-item a {
  text-decoration: none;
  color: #4299e1;
  font-weight: 500;
}

.hero-section {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 40px 20px;
  border-radius: 12px;
  text-align: center;
  margin-bottom: 40px;
}

.hero-title {
  font-size: 2.5em;
  margin-bottom: 10px;
  font-weight: bold;
}

.hero-subtitle {
  font-size: 1.2em;
  opacity: 0.9;
}

.quickstart-section {
  background: #f7fafc;
  border-radius: 12px;
  padding: 30px;
  margin: 40px 0;
}

.quickstart-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.quickstart-card {
  background: white;
  padding: 20px;
  border-radius: 10px;
  border-left: 4px solid #4299e1;
  transition: transform 0.3s ease;
}

.quickstart-card:hover {
  transform: translateX(5px);
}

@media (max-width: 768px) {
  .projects-grid {
    grid-template-columns: 1fr;
  }
  
  .hero-title {
    font-size: 2em;
  }
  
  .category-title {
    font-size: 1.5em;
  }
}
</style>

<div class="portfolio-container">

<div class="hero-section">
  <h1 class="hero-title">🚀 2025 Entwicklungs-Portfolio</h1>
  <p class="hero-subtitle">Willkommen in meinem umfassenden Entwicklungs-Portfolio mit innovativen Projekten</p>
</div>

<div class="toc-container">
  <h2 class="toc-title">📋 Schnellnavigation</h2>
  <div class="toc-list">
    <div class="toc-item"><a href="#net-c-entwicklung">💻 .NET & C# Entwicklung</a></div>
    <div class="toc-item"><a href="#web-entwicklung">🌐 Web-Entwicklung</a></div>
    <div class="toc-item"><a href="#automatisierung-tools">🔧 Automatisierung & Tools</a></div>
    <div class="toc-item"><a href="#infrastruktur-devops">🏭 Infrastruktur & DevOps</a></div>
    <div class="toc-item"><a href="#3d-druck-hardware">🖨️ 3D-Druck & Hardware</a></div>
    <div class="toc-item"><a href="#spezialisierte-anwendungen">🏗️ Spezialisierte Anwendungen</a></div>
  </div>
</div>

<div class="category-section" id="net-c-entwicklung">
  <h2 class="category-title">💻 .NET & C# Entwicklung</h2>
  <div class="projects-grid">
    
    <div class="project-card">
      <div class="project-header">
        <div class="project-icon">☁️</div>
        <h3 class="project-title">AKS - Azure Kubernetes Service</h3>
      </div>
      <p class="project-description">
        Professionelle Azure Kubernetes Service Konfiguration mit C# Implementierung und Excel-Import-Funktionalität.
      </p>
      <div class="project-links">
        <a href="./AKS/AKS.cs" class="project-link">📄 AKS.cs</a>
        <a href="./AKS/AKS.md" class="project-link">📚 Dokumentation</a>
        <a href="./AKS/Excel import/" class="project-link">📊 Excel Import</a>
        <a href="./AKS/README.md" class="project-link">📖 README</a>
      </div>
    </div>

    <div class="project-card">
      <div class="project-header">
        <div class="project-icon">📱</div>
        <h3 class="project-title">MyApp - Konsolenanwendung</h3>
      </div>
      <p class="project-description">
        Cross-Platform Konsolenanwendung mit .NET 8 und Multi-Platform-Unterstützung.
      </p>
      <div class="project-links">
        <a href="./App-C-Sharp/MyApp/Program.cs" class="project-link">💻 Program.cs</a>
        <a href="./App-C-Sharp/MyApp/MyApp.csproj" class="project-link">📄 Projekt</a>
        <a href="./App-C-Sharp/MyApp/MyApp_MultiPlatform.csproj" class="project-link">🌐 Multi-Platform</a>
      </div>
    </div>

    <div class="project-card">
      <div class="project-header">
        <div class="project-icon">🔥</div>
        <h3 class="project-title">MyBlazorApp - MAUI Blazor</h3>
      </div>
      <p class="project-description">
        Moderne MAUI Blazor-Anwendung für Android, iOS, MacCatalyst, Windows und Tizen mit umfassender Dokumentation.
      </p>
      <div class="project-links">
        <a href="./App-C-Sharp/MyBlazorApp/MyBlazorApp.csproj" class="project-link">📄 Projekt</a>
        <a href="./App-C-Sharp/MyBlazorApp/Readme.md" class="project-link">📖 README</a>
        <a href="./App-C-Sharp/MyBlazorApp/Readme-structure.md" class="project-link">🏗️ Struktur</a>
        <a href="./App-C-Sharp/PDF/_NET MAUI Entwicklung auf Manjaro Linux - Setup Guide.pdf" class="project-link">📚 PDF Guide</a>
      </div>
    </div>

    <div class="project-card">
      <div class="project-header">
        <div class="project-icon">🌐</div>
        <h3 class="project-title">MyBlazorWeb - Web Blazor</h3>
      </div>
      <p class="project-description">
        Web-basierte Blazor-Anwendung mit strukturierter Dokumentation und modernem Design.
      </p>
      <div class="project-links">
        <a href="./App-C-Sharp/MyBlazorWeb/MyBlazorWeb.csproj" class="project-link">📄 Projekt</a>
        <a href="./App-C-Sharp/MyBlazorWeb/Readme.md" class="project-link">📖 README</a>
        <a href="./App-C-Sharp/MyBlazorWeb/Readme-structure.md" class="project-link">🏗️ Struktur</a>
      </div>
    </div>

  </div>
</div>

<div class="category-section" id="web-entwicklung">
  <h2 class="category-title">🌐 Web-Entwicklung</h2>
  <div class="projects-grid">
    
    <div class="project-card web">
      <div class="project-header">
        <div class="project-icon">📄</div>
        <h3 class="project-title">PDF-Viewer</h3>
      </div>
      <p class="project-description">
        Webbasierter PDF-Reader mit Editor-Funktionalität und modernem Styling.
      </p>
      <div class="project-links">
        <a href="./PDF-Viewer/index.html" class="project-link">🏠 Haupt-App</a>
        <a href="./PDF-Viewer/edit.html" class="project-link">✏️ Editor</a>
        <a href="./PDF-Viewer/index_I.html" class="project-link">🔄 Alternative</a>
        <a href="./PDF-Viewer/style/styles-v4.css" class="project-link">🎨 Styling</a>
      </div>
    </div>

    <div class="project-card web">
      <div class="project-header">
        <div class="project-icon">💰</div>
        <h3 class="project-title">Steuer-Calc</h3>
      </div>
      <p class="project-description">
        Professioneller Steuer- und Krankenversicherungsrechner mit Tailwind CSS und Versionshistorie.
      </p>
      <div class="project-links">
        <a href="./steuer-calc/steuer_kv_rechner.html" class="project-link">🧮 Rechner</a>
        <a href="./steuer-calc/README.md" class="project-link">📖 README</a>
        <a href="./steuer-calc/styles/" class="project-link">🎨 Styles</a>
        <a href="./steuer-calc/archiv/" class="project-link">📁 Archiv</a>
      </div>
    </div>

    <div class="project-card web">
      <div class="project-header">
        <div class="project-icon">🔍</div>
        <h3 class="project-title">WebVisu GitHub Pages</h3>
      </div>
      <p class="project-description">
        Professionelle GitHub Pages Website mit Bootstrap-Framework und Custom CSS.
      </p>
      <div class="project-links">
        <a href="./webvisu.github.io/index.html" class="project-link">🏠 Website</a>
        <a href="./webvisu.github.io/css/" class="project-link">🎨 Bootstrap CSS</a>
        <a href="./webvisu.github.io/README.md" class="project-link">📖 README</a>
      </div>
    </div>

  </div>
</div>

<div class="category-section" id="automatisierung-tools">
  <h2 class="category-title">🔧 Automatisierung & Tools</h2>
  <div class="projects-grid">
    
    <div class="project-card automation">
      <div class="project-header">
        <div class="project-icon">💾</div>
        <h3 class="project-title">BackUp-mit-Rsynch</h3>
      </div>
      <p class="project-description">
        Automatisierte Backup-Lösung mit Rsync, Web-Interface und Konfiguration für externe Festplatten.
      </p>
      <div class="project-links">
        <a href="./BackUp-mit-Rsynch/doc.md" class="project-link">📚 Dokumentation</a>
        <a href="./BackUp-mit-Rsynch/index.html" class="project-link">🌐 Web-Interface</a>
        <a href="./BackUp-mit-Rsynch/externe Festplatte/" class="project-link">💿 Externe HDD</a>
        <a href="./BackUp-mit-Rsynch/laufendes System/" class="project-link">⚙️ System-Config</a>
      </div>
    </div>

    <div class="project-card automation">
      <div class="project-header">
        <div class="project-icon">🐍</div>
        <h3 class="project-title">Live-Server-Python</h3>
      </div>
      <p class="project-description">
        Python-basierter Live-Server mit umfassender PDF-Anleitung und Versionskontrolle.
      </p>
      <div class="project-links">
        <a href="./Live-Server-python/Readme.md" class="project-link">📖 README</a>
        <a href="./Live-Server-python/PDF/Python Live Server Anleitung.pdf" class="project-link">📚 PDF-Guide</a>
        <a href="./Live-Server-python/v1/" class="project-link">🔄 Version 1</a>
      </div>
    </div>

    <div class="project-card automation">
      <div class="project-header">
        <div class="project-icon">📦</div>
        <h3 class="project-title">Distrobox</h3>
      </div>
      <p class="project-description">
        Container-Virtualisierung mit Distrobox, Screenshots und Custom-Styling.
      </p>
      <div class="project-links">
        <a href="./distrobox/README.md" class="project-link">📖 README</a>
        <a href="./distrobox/style.css" class="project-link">🎨 Styling</a>
        <a href="./distrobox/screen/ships.webp" class="project-link">🖼️ Screenshots</a>
      </div>
    </div>

    <div class="project-card automation">
      <div class="project-header">
        <div class="project-icon">🤖</div>
        <h3 class="project-title">Prompt-Generator</h3>
      </div>
      <p class="project-description">
        AI-Prompt-Generator für Coding-Projekte mit benutzerfreundlicher HTML-Oberfläche.
      </p>
      <div class="project-links">
        <a href="./Prombt-Generator/coding_prompt_generator.html" class="project-link">🔧 Generator</a>
      </div>
    </div>

  </div>
</div>

<div class="category-section" id="infrastruktur-devops">
  <h2 class="category-title">🏭 Infrastruktur & DevOps</h2>
  <div class="projects-grid">
    
    <div class="project-card infrastructure">
      <div class="project-header">
        <div class="project-icon">🏭</div>
        <h3 class="project-title">Codesys</h3>
      </div>
      <p class="project-description">
        Industrielle Automatisierungslösung mit Codesys, Lizenzierung und umfassender Dokumentation.
      </p>
      <div class="project-links">
        <a href="./codesys/README.md" class="project-link">📖 README</a>
        <a href="./codesys/LICENSE" class="project-link">📜 Lizenz</a>
      </div>
    </div>

    <div class="project-card infrastructure">
      <div class="project-header">
        <div class="project-icon">🔍</div>
        <h3 class="project-title">LLMS-SEO-WebSite</h3>
      </div>
      <p class="project-description">
        SEO-Optimierung mit AI-Integration, Automatisierungs-Projekten und LLM-Konfiguration.
      </p>
      <div class="project-links">
        <a href="./LLMS-SEO-WebSite/llms.txt" class="project-link">📄 LLMS Config</a>
        <a href="./LLMS-SEO-WebSite/llms_txt_automation_projects.md" class="project-link">🤖 Automatisierung</a>
        <a href="./LLMS-SEO-WebSite/README.md" class="project-link">📖 README</a>
      </div>
    </div>

  </div>
</div>

<div class="category-section" id="3d-druck-hardware">
  <h2 class="category-title">🖨️ 3D-Druck & Hardware</h2>
  <div class="projects-grid">
    
    <div class="project-card hardware">
      <div class="project-header">
        <div class="project-icon">🖨️</div>
        <h3 class="project-title">OrcaSlicer</h3>
      </div>
      <p class="project-description">
        3D-Druck-Konfiguration mit OrcaSlicer, SolidWorks-Modellen und Projekt-Screenshots.
      </p>
      <div class="project-links">
        <a href="./OrcaSlicer/README.md" class="project-link">📖 README</a>
        <a href="./OrcaSlicer/screen/" class="project-link">🖼️ Screenshots</a>
        <a href="./OrcaSlicer/solidworks -3ds/solidworks/" class="project-link">🔧 3D-Modelle</a>
      </div>
    </div>

    <div class="project-card hardware">
      <div class="project-header">
        <div class="project-icon">⚙️</div>
        <h3 class="project-title">Y3D-Printer-Config</h3>
      </div>
      <p class="project-description">
        Professionelle 3D-Drucker-Konfiguration mit Sicherheits-Optimierungen und Versions-Management.
      </p>
      <div class="project-links">
        <a href="./y3d-Printer-config-Optimierung/v3-print.cfg" class="project-link">⚙️ Aktuelle Config</a>
        <a href="./y3d-Printer-config-Optimierung/v3-doc-safety.md" class="project-link">🛡️ Sicherheit</a>
        <a href="./y3d-Printer-config-Optimierung/v3-print.md" class="project-link">📚 Dokumentation</a>
        <a href="./y3d-Printer-config-Optimierung/BackUp-Print.cfg" class="project-link">💾 Backup</a>
      </div>
    </div>

  </div>
</div>

<div class="category-section" id="spezialisierte-anwendungen">
  <h2 class="category-title">🏗️ Spezialisierte Anwendungen</h2>
  <div class="projects-grid">
    
    <div class="project-card specialized">
      <div class="project-header">
        <div class="project-icon">🏢</div>
        <h3 class="project-title">V-Strom-Messung-ISO9972</h3>
      </div>
      <p class="project-description">
        Professionelle Blower-Door-Test-Anwendung nach ISO 9972 mit umfassendem JavaScript-Framework und Protokoll-System.
      </p>
      <div class="project-links">
        <a href="./V-Strom-Messung-ISO9972-html/index.html" class="project-link">🏠 Haupt-App</a>
        <a href="./V-Strom-Messung-ISO9972-html/Readme.md" class="project-link">📖 README</a>
        <a href="./V-Strom-Messung-ISO9972-html/js/" class="project-link">⚙️ JS-Module</a>
        <a href="./V-Strom-Messung-ISO9972-html/sites/protocol.html" class="project-link">📋 Protokoll</a>
      </div>
    </div>

  </div>
</div>

<div class="quickstart-section">
  <h2 class="category-title">🚀 Schnellstart-Guide</h2>
  <div class="quickstart-grid">
    
    <div class="quickstart-card">
      <h3>💻 .NET-Entwicklung</h3>
      <p>Beginnen Sie mit den <a href="./App-C-Sharp/">C# Projekten</a> und erkunden Sie MAUI Blazor-Apps</p>
    </div>

    <div class="quickstart-card">
      <h3>🌐 Web-Entwicklung</h3>
      <p>Testen Sie den <a href="./PDF-Viewer/">PDF-Viewer</a> oder den <a href="./steuer-calc/">Steuer-Rechner</a></p>
    </div>

    <div class="quickstart-card">
      <h3>🔧 Automatisierung</h3>
      <p>Starten Sie mit <a href="./BackUp-mit-Rsynch/">BackUp-Rsynch</a> für System-Automatisierung</p>
    </div>

    <div class="quickstart-card">
      <h3>🖨️ 3D-Druck</h3>
      <p>Konfigurieren Sie <a href="./OrcaSlicer/">OrcaSlicer</a> oder optimieren Sie Ihre <a href="./y3d-Printer-config-Optimierung/">Drucker-Settings</a></p>
    </div>

    <div class="quickstart-card">
      <h3>🏗️ Professionelle Messungen</h3>
      <p>Nutzen Sie die <a href="./V-Strom-Messung-ISO9972-html/">ISO 9972 Blower-Door-App</a> für Luftdichtheitsmessungen</p>
    </div>

  </div>
</div>

<div style="text-align: center; padding: 40px 20px; background: #f7fafc; border-radius: 12px; margin-top: 40px;">
  <h2 style="color: #2d3748; margin-bottom: 15px;">📞 Kontakt & Support</h2>
  <p style="color: #718096; margin-bottom: 20px;">
    Bei Fragen zu einzelnen Projekten schauen Sie bitte in die jeweiligen README.md-Dateien der Projektordner.
  </p>
  <div style="display: flex; justify-content: center; gap: 20px; margin-top: 20px;">
    <span style="background: #48bb78; color: white; padding: 8px 16px; border-radius: 20px;">🟢 Aktiv in Entwicklung</span>
    <span style="background: #4299e1; color: white; padding: 8px 16px; border-radius: 20px;">📅 Letzte Aktualisierung: Juli 2025</span>
  </div>
</div>

</div>

---

*Diese README wird regelmäßig aktualisiert, um neue Projekte und Änderungen zu reflektieren.*