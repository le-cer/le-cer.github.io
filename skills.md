---
layout: page
title: Habilidades
subtitle: Stack tecnológico y competencias profesionales
---

<div class="skills-container">
  
  ## Stack Tecnológico

  ### Lenguajes de Programación
  <div class="skill-category">
    <div class="skill-item">
      <span class="skill-name">Python</span>
      <div class="skill-bar">
        <div class="skill-level" style="width: 95%">95%</div>
      </div>
    </div>
    <div class="skill-item">
      <span class="skill-name"></span>
      <div class="skill-bar">
        <div class="skill-level" style="width: 85%">%</div>
      </div>
    </div>
    <div class="skill-item">
      <span class="skill-name">SQL</span>
      <div class="skill-bar">
        <div class="skill-level" style="width: 90%">90%</div>
      </div>
    </div>
    <div class="skill-item">
      <span class="skill-name"></span>
      <div class="skill-bar">
        <div class="skill-level" style="width: 75%">%</div>
      </div>
    </div>
  </div>

  ### Procesamiento de Lenguaje Natural
  <div class="skill-category">
    <div class="skill-grid">
      <div class="skill-card">
        <h4>Librerías Core</h4>
        <ul>
          <li>NLTK & spaCy</li>
          <li>Transformers (Hugging Face)</li>
          <li>Gensim</li>
          <li>scikit-learn</li>
        </ul>
      </div>
      <div class="skill-card">
        <h4>Modelos y Técnicas</h4>
        <ul>
          <li>BERT, GPT, RoBERTa</li>
          <li>Topic Modeling (LDA, BERTopic)</li>
          <li>Named Entity Recognition</li>
          <li>Sentiment Analysis</li>
        </ul>
      </div>
      <div class="skill-card">
        <h4>Frameworks</h4>
        <ul>
          <li>LangChain</li>
          <li>OpenAI API</li>
          <li>TensorFlow/PyTorch</li>
          <li>FastAPI</li>
        </ul>
      </div>
    </div>
  </div>

  ### SEO y Marketing Digital
  <div class="skill-category">
    <div class="skill-grid">
      <div class="skill-card">
        <h4>Herramientas SEO</h4>
        <ul>
          <li>Google Search Console</li>
          <li>Google Analytics 4</li>
          <li>SEMrush / Ahrefs</li>
          <li>Screaming Frog</li>
        </ul>
      </div>
      <div class="skill-card">
        <h4>Técnicas</h4>
        <ul>
          <li>Keyword Research</li>
          <li>Technical SEO</li>
          <li>Content Strategy</li>
          <li>Link Building</li>
        </ul>
      </div>
      <div class="skill-card">
        <h4>Analytics</h4>
        <ul>
          <li>Google Tag Manager</li>
          <li>Data Studio/Looker</li>
          <li>A/B Testing</li>
          <li>Conversion Tracking</li>
        </ul>
      </div>
    </div>
  </div>

  ### Data Science y Machine Learning
  <div class="skill-category">
    <div class="skill-grid">
      <div class="skill-card">
        <h4>Análisis de Datos</h4>
        <ul>
          <li>Pandas & NumPy</li>
          <li>Matplotlib & Seaborn</li>
          <li>Plotly & Dash</li>
          <li>Jupyter Notebooks</li>
        </ul>
      </div>
      <div class="skill-card">
        <h4>Machine Learning</h4>
        <ul>
          <li>scikit-learn</li>
          <li>XGBoost & LightGBM</li>
          <li>Feature Engineering</li>
          <li>Model Deployment</li>
        </ul>
      </div>
      <div class="skill-card">
        <h4>Big Data</h4>
        <ul>
          <li>Apache Spark</li>
          <li>PostgreSQL & MongoDB</li>
          <li>Docker & Kubernetes</li>
          <li>AWS/GCP</li>
        </ul>
      </div>
    </div>
  </div>

  ## Competencias Profesionales

  <div class="soft-skills">
    <div class="row">
      <div class="col-md-6">
        <h3>Habilidades Técnicas</h3>
        <ul class="competency-list">
          <li> **Pensamiento Analítico:** Capacidad para descomponer problemas complejos en componentes manejables</li>
          <li> **Visualización de Datos:** Creación de dashboards e infografías que comunican insights claramente</li>
          <li> **Automatización:** Desarrollo de pipelines y procesos que reducen trabajo manual</li>
          <li> **Testing y Validación:** Implementación de pruebas A/B y validación estadística</li>
        </ul>
      </div>
      <div class="col-md-6">
        <h3>Habilidades Blandas</h3>
        <ul class="competency-list">
          <li> **Comunicación Técnica:** Traducción de resultados complejos a stakeholders no técnicos</li>
          <li> **Gestión de Proyectos:** Experiencia con metodologías ágiles y entrega de proyectos en tiempo</li>
          <li> **Aprendizaje Continuo:** Adaptación rápida a nuevas tecnologías y frameworks</li>
          <li> **Trabajo en Equipo:** Colaboración efectiva con equipos multidisciplinarios</li>
        </ul>
      </div>
    </div>
  </div>

  
</div>

<style>
.skills-container {
  max-width: 1000px;
  margin: 0 auto;
}

.skill-category {
  margin-bottom: 40px;
}

.skill-item {
  display: flex;
  align-items: center;
  margin-bottom: 15px;
}

.skill-name {
  width: 120px;
  font-weight: 600;
}

.skill-bar {
  flex: 1;
  background: #e9ecef;
  height: 20px;
  border-radius: 10px;
  overflow: hidden;
  margin-left: 20px;
}

.skill-level {
  height: 100%;
  background: linear-gradient(45deg, #007bff, #0056b3);
  color: white;
  display: flex;
  align-items: center;
  justify-content: flex-end;
  padding-right: 10px;
  font-size: 0.8em;
  font-weight: 600;
  transition: width 2s ease-in-out;
}

.skill-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
  margin-bottom: 30px;
}

.skill-card {
  background: white;
  border: 1px solid #e1e5e9;
  border-radius: 8px;
  padding: 20px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.skill-card h4 {
  color: #007bff;
  margin-bottom: 15px;
  border-bottom: 2px solid #e9ecef;
  padding-bottom: 5px;
}

.skill-card ul {
  list-style: none;
  padding: 0;
}

.skill-card li {
  padding: 5px 0;
  border-bottom: 1px solid #f8f9fa;
}

.skill-card li:before {
  content: "▶ ";
  color: #007bff;
  font-weight: bold;
}

.competency-list {
  list-style: none;
  padding: 0;
}

.competency-list li {
  margin-bottom: 10px;
  padding-left: 0;
}

.certifications {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
}

.cert-item {
  background: #f8f9fa;
  padding: 15px;
  border-radius: 8px;
  border-left: 4px solid #007bff;
}

.cert-date {
  color: #6c757d;
  font-size: 0.9em;
  float: right;
}

@media (max-width: 768px) {
  .skill-item {
    flex-direction: column;
    align-items: flex-start;
  }
  
  .skill-bar {
    width: 100%;
    margin-left: 0;
    margin-top: 5px;
  }
  
  .skill-grid {
    grid-template-columns: 1fr;
  }
}
</style>
