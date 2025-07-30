---
layout: page
title: Proyectos
subtitle: Portfolio de trabajos en NLP, SEO y Data Science
---

<div class="projects-container">
  <!-- Filtros de proyectos -->
  <div class="project-filters">
    <button class="filter-btn active" data-filter="all">Todos</button>
    <button class="filter-btn" data-filter="nlp">NLP</button>
    <button class="filter-btn" data-filter="seo">SEO</button>
    <button class="filter-btn" data-filter="data">Data Science</button>
  </div>

  <!-- Proyectos NLP -->
  <div class="project-section" data-category="nlp">
    <h2> Procesamiento del Lenguaje Natural</h2>
    
    <div class="project-item">
      <h3>Análisis del Lenguaje Tóxico en Español</h3>
      <div class="project-meta">
        <span class="project-date">2024</span>
        <span class="project-status">Completado</span>
      </div>
      
      <p><strong>Problema:</strong> Necesidad de detectar y clasificar contenido tóxico en español para plataformas digitales.</p>
      
      <p><strong>Solución:</strong> Desarrollé un sistema de clasificación usando BERT preentrenado para español.</p>
      
      <p><strong>Tecnologías:</strong></p>
      <div class="tech-stack">
        <span class="tech-tag">Python</span>
        <span class="tech-tag">BERT</span>
        <span class="tech-tag">Transformers</span>
        <span class="tech-tag">scikit-learn</span>
        <span class="tech-tag">Pandas</span>
      </div>
      
      <div class="project-results">
        <h4>Resultados:</h4>
        <ul>
          <li> <strong>% de precisión</strong> en clasificación </li>
          <li> <strong>Reducción del %</strong> en falsos positivos vs. sistemas anteriores</li>
          <li> <strong>Procesamiento en tiempo real</strong> de + textos por minuto</li>
        </ul>
      </div>
      
      <div class="project-links">
        <a href="#" class="btn btn-primary">Ver Código</a>
        <a href="#" class="btn btn-outline">Demo</a>
      </div>
    </div>

    <div class="project-item">
      <h3>Sistema RAG </h3>
      <div class="project-meta">
        <span class="project-date">2024</span>
        <span class="project-status">En desarrollo</span>
      </div>
      
      <p><strong>Problema:</strong> .</p>
      
      <p><strong>Solución:</strong> .</p>
      
      <div class="tech-stack">
        <span class="tech-tag">.</span>
        <span class="tech-tag">OpenAI GPT</span>
        <span class="tech-tag">.</span>
        <span class="tech-tag">.</span>
      </div>
      
      <div class="project-results">
        <h4>Resultados Preliminares:</h4>
        <ul>
          <li> <strong>% relevancia</strong> en respuestas generadas</li>
          <li> <strong>Reducción del %</strong> en tiempo de búsqueda bibliográfica</li>
        </ul>
      </div>
      
      <div class="project-links">
        <a href="#" class="btn btn-primary">Ver Código</a>
        <a href="#" class="btn btn-outline">Documentación</a>
      </div>
    </div>
  </div>

  <!-- Proyectos SEO -->
  <div class="project-section" data-category="seo">
    <h2> SEO y Marketing Digital</h2>
    
    <div class="project-item">
      <h3>Dashboard SEO - AIO (All-in-One)</h3>
      <div class="project-meta">
        <span class="project-date">2024</span>
        <span class="project-status">Completado</span>
      </div>
      
      <p><strong>Problema:</strong> Agencias digitales necesitaban una herramienta unificada para monitoreo SEO de múltiples clientes.</p>
      
      <p><strong>Solución:</strong> Dashboard interactivo que integra datos de Google Search Console, Analytics, y herramientas de terceros, con alertas automáticas y reportes personalizados.</p>
      
      <div class="tech-stack">
        <span class="tech-tag">Python</span>
        <span class="tech-tag">Dash/Plotly</span>
        <span class="tech-tag">Google APIs</span>
        <span class="tech-tag">PostgreSQL</span>
      </div>
      
      <div class="project-results">
        <h4>Resultados:</h4>
        <ul>
          <li> <strong>Reducción del %</strong> en tiempo de reportes manuales</li>
          <li> <strong>+ clientes</strong> monitoreados simultáneamente</li>
          <li> <strong>Detección automática</strong> de caídas de tráfico en <24h</li>
        </ul>
      </div>
      
      <div class="project-links">
        <a href="#" class="btn btn-primary">Ver Demo</a>
        <a href="#" class="btn btn-outline">Caso de Estudio</a>
      </div>
    </div>
  </div>

  <!-- Proyectos Data Science -->
  <div class="project-section" data-category="data">
    <h2> Análisis de Datos y Machine Learning</h2>
    
    <div class="project-item">
      <h3>MiBiblio: Análisis de Préstamos Bibliotecarios</h3>
      <div class="project-meta">
        <span class="project-date">2024</span>
        <span class="project-status">Completado</span>
      </div>
      
      <p><strong>Problema:</strong> Insights sobre patrones de préstamo y preferencias de usuarios para optimizar su colección.</p>
      
      <p><strong>Solución:</strong> Análisis integral combinando visualización de datos, topic modeling y chatbot asistente para consultas.</p>
      
      <div class="tech-stack">
        <span class="tech-tag">Python</span>
        <span class="tech-tag">Pandas</span>
        <span class="tech-tag">Matplotlib/Seaborn</span>
        <span class="tech-tag">LDA</span>
        <span class="tech-tag">Streamlit</span>
      </div>
      
      <div class="project-results">
        <h4>Resultados:</h4>
        <ul>
          <li> <strong> categorías temáticas</strong> identificadas automáticamente</li>
          <li> <strong>Patrones estacionales</strong> en préstamos detectados</li>
          <li> <strong>Recomendaciones</strong> para optimización de inventario</li>
        </ul>
      </div>
      
      <div class="project-links">
        <a href="#" class="btn btn-primary">Ver Análisis</a>
        <a href="#" class="btn btn-outline">Chatbot Demo</a>
      </div>
    </div>
  </div>
</div>

<style>
.project-filters {
  text-align: center;
  margin-bottom: 30px;
}

.filter-btn {
  background: #f8f9fa;
  border: 1px solid #dee2e6;
  padding: 8px 16px;
  margin: 0 5px;
  border-radius: 20px;
  cursor: pointer;
  transition: all 0.3s ease;
}

.filter-btn.active,
.filter-btn:hover {
  background: #007bff;
  color: white;
  border-color: #007bff;
}

.project-item {
  background: white;
  border: 1px solid #e1e5e9;
  border-radius: 8px;
  padding: 25px;
  margin-bottom: 30px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.project-meta {
  display: flex;
  gap: 15px;
  margin-bottom: 15px;
}

.project-date {
  background: #6c757d;
  color: white;
  padding: 2px 8px;
  border-radius: 12px;
  font-size: 0.8em;
}

.project-status {
  background: #28a745;
  color: white;
  padding: 2px 8px;
  border-radius: 12px;
  font-size: 0.8em;
}

.tech-stack {
  margin: 15px 0;
}

.tech-tag {
  background: #007bff;
  color: white;
  padding: 3px 10px;
  border-radius: 12px;
  font-size: 0.8em;
  margin-right: 8px;
  margin-bottom: 5px;
  display: inline-block;
}

.project-results {
  background: #f8f9fa;
  padding: 15px;
  border-radius: 5px;
  margin: 15px 0;
}

.project-links {
  margin-top: 20px;
}

.project-links .btn {
  margin-right: 10px;
}
</style>

<script>
// Filtro de proyectos
document.addEventListener('DOMContentLoaded', function() {
  const filterBtns = document.querySelectorAll('.filter-btn');
  const projectSections = document.querySelectorAll('.project-section');
  
  filterBtns.forEach(btn => {
    btn.addEventListener('click', function() {
      // Remover clase active de todos los botones
      filterBtns.forEach(b => b.classList.remove('active'));
      // Agregar clase active al botón clickeado
      this.classList.add('active');
      
      const filter = this.getAttribute('data-filter');
      
      projectSections.forEach(section => {
        if (filter === 'all' || section.getAttribute('data-category') === filter) {
          section.style.display = 'block';
        } else {
          section.style.display = 'none';
        }
      });
    });
  });
});
</script>
