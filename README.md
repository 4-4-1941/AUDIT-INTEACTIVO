<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - AUDIT SIP SYSTEM</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            max-width: 900px;
            margin: 40px auto;
            padding: 20px;
            background: #f8fafc;
            color: #1e293b;
            line-height: 1.7;
        }
        .card {
            background: white;
            padding: 30px;
            border-radius: 16px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.06);
            margin-bottom: 25px;
        }
        h1 { color: #0b3b5c; border-bottom: 3px solid #2563eb; padding-bottom: 12px; }
        h2 { color: #1e4a7a; margin-top: 28px; }
        .badge {
            display: inline-block;
            background: #2563eb;
            color: white;
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 600;
            margin-right: 6px;
        }
        .badge-green { background: #16a34a; }
        .badge-yellow { background: #d97706; }
        .badge-red { background: #dc2626; }
        ul { padding-left: 22px; }
        li { margin-bottom: 6px; }
        .idiomas-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 12px;
            margin: 15px 0;
        }
        .idioma-item {
            background: #f1f5f9;
            padding: 10px 14px;
            border-radius: 10px;
            text-align: center;
            font-weight: 600;
        }
        .footer {
            text-align: center;
            padding: 25px 0 10px;
            border-top: 2px solid #e2e8f0;
            font-size: 0.85rem;
            color: #64748b;
        }
        .version-tag {
            background: #1e293b;
            color: white;
            padding: 2px 12px;
            border-radius: 12px;
            font-size: 0.75rem;
        }
        @media (max-width: 600px) {
            body { padding: 12px; }
            .card { padding: 18px; }
        }
    </style>
</head>
<body>

<div class="card">
    <h1>🧪 Cuestionario AUDIT</h1>
    <p style="font-size:1.1rem; color:#475569;">
        <strong>Test de Identificación de Trastornos por Consumo de Alcohol</strong><br>
        <span style="font-size:0.9rem;">Basado en el manual oficial de la <strong>Organización Mundial de la Salud (OMS)</strong> · 2001</span>
    </p>
    <p>
        <span class="badge">v2.0</span>
        <span class="badge badge-green">OMS</span>
        <span class="badge badge-yellow">Tamizaje</span>
        <span class="badge badge-red">Preventivo</span>
    </p>
</div>

<div class="card">
    <h2>🌍 Adaptación lingüística para Perú</h2>
    <p>Herramienta diseñada para ser aplicada en <strong>diversas regiones del Perú</strong>, con traducciones culturalmente adaptadas:</p>
    <div class="idiomas-grid">
        <div class="idioma-item">🇪🇸 Español</div>
        <div class="idioma-item">🏔️ Quechua</div>
        <div class="idioma-item">🏔️ Aymara</div>
        <div class="idioma-item">🌳 Conihua</div>
        <div class="idioma-item">🌳 Shipibo</div>
    </div>
    <p style="font-size:0.9rem; color:#475569;">
        <strong>📌 Nota:</strong> Cada adaptación incluye traducción exacta de las 10 preguntas, notas contextuales y términos locales para "trago estándar".
    </p>
</div>

<div class="card">
    <h2>📋 Características principales</h2>
    <ul>
        <li><strong>✅ Pregunta por pregunta</strong> — Experiencia interactiva con indicador de progreso</li>
        <li><strong>⚡ Auto-avance</strong> — Al seleccionar una respuesta, avanza automáticamente</li>
        <li><strong>⌨️ Navegación por teclado</strong> — Flechas ← → y Enter para avanzar</li>
        <li><strong>📊 Interpretación clínica</strong> — Zonas de riesgo I-IV según manual OMS</li>
        <li><strong>🎯 Punto de corte diferenciado</strong> — 8 (general) · 7 (mujeres y >65 años)</li>
        <li><strong>© Copyright</strong> — SIP SYSTEM INTELLIGENCE PLATFORM</li>
        <li><strong>📱 Responsive</strong> — Funciona en móviles, tablets y escritorio</li>
        <li><strong>🖨️ Imprimible</strong> — Versión optimizada para impresión</li>
    </ul>
</div>

<div class="card">
    <h2>🏥 Aplicación y uso</h2>
    <ul>
        <li><strong>Autoevaluación:</strong> Para que las personas puedan conocer su nivel de riesgo</li>
        <li><strong>Personal de salud:</strong> Herramienta de tamizaje en consultorios y campañas</li>
        <li><strong>Zonas rurales:</strong> Adaptado para comunidades quechuas, aymaras y amazónicas</li>
        <li><strong>Investigación:</strong> Base para estudios epidemiológicos en Perú</li>
    </ul>
</div>

<div class="card">
    <h2>📚 Base científica</h2>
    <p>El cuestionario está basado en el <strong>Manual del AUDIT</strong> de la OMS (2001), desarrollado por:</p>
    <ul>
        <li><strong>Thomas F. Babor</strong> — University of Connecticut</li>
        <li><strong>John C. Higgins-Biddle</strong> — University of Connecticut</li>
        <li><strong>John B. Saunders</strong> — University of Queensland</li>
        <li><strong>Maristela G. Monteiro</strong> — Organización Mundial de la Salud</li>
    </ul>
    <p style="font-size:0.85rem; color:#475569; margin-top:8px;">
        🔗 <a href="https://www.who.int/publications/i/item/WHO-MSD-MSB-01.6a" target="_blank">WHO/MSD/MSB/01.6a</a>
    </p>
</div>

<div class="card">
    <h2>📁 Estructura del proyecto</h2>
    <pre style="background:#f1f5f9; padding:12px 16px; border-radius:8px; font-size:0.85rem; overflow-x:auto;">
📂 audit-peru/
├── 📄 index.html          # Cuestionario AUDIT (principal)
├── 📄 README.html         # Esta documentación
└── 📄 LICENSE             # Creative Commons BY-NC
    </pre>
</div>

<div class="card">
    <h2>📞 Contacto</h2>
    <p>
        <strong>© 2026 SIP SYSTEM INTELLIGENCE PLATFORM</strong><br>
        Herramienta de tamizaje basada en el manual oficial de la OMS (2001).<br>
        Adaptación lingüística para Perú: Quechua, Aymara, Conihua, Shipibo.
    </p>
</div>

<div class="footer">
    <strong>© 2026 SIP SYSTEM INTELLIGENCE PLATFORM</strong> — Todos los derechos reservados.<br>
    <span style="font-size:0.75rem;">Desarrollado con ❤️ para la salud pública en Perú</span>
</div>

</body>
</html>
