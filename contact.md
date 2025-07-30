---
layout: page
title: Contacto
subtitle: ¿Tienes un proyecto interesante? ¡Hablemos!
---

<div class="contact-container">
  <div class="row">
    <div class="col-md-8">
      <div class="contact-intro">
        <h2>¡Construyamos algo increíble juntos!</h2>
        <p>
          Estoy siempre interesada en proyectos desafiantes que involucren 
          <strong>NLP</strong>, <strong>SEO</strong> o <strong>Data Science</strong>. 
          Ya sea que necesites consultoría, desarrollo de productos o colaboración 
          en investigación, me encantaría conocer más sobre tu proyecto.
        </p>
      </div>

      <div class="contact-form">
        <h3>Envíame un mensaje</h3>
        <form action="https://formsubmit.co/tu.email@ejemplo.com" method="POST">
          <div class="form-group">
            <label for="name">Nombre *</label>
            <input type="text" id="name" name="name" required>
          </div>
          
          <div class="form-group">
            <label for="email">Email *</label>
            <input type="email" id="email" name="email" required>
          </div>
          
          <div class="form-group">
            <label for="company">Empresa/Organización</label>
            <input type="text" id="company" name="company">
          </div>
          
          <div class="form-group">
            <label for="project-type">Tipo de Proyecto</label>
            <select id="project-type" name="project-type">
              <option value="">Selecciona una opción</option>
              <option value="nlp">Procesamiento de Lenguaje Natural</option>
              <option value="seo">SEO y Marketing Digital</option>
              <option value="data-science">Data Science y Analytics</option>
              <option value="consulting">Consultoría General</option>
              <option value="collaboration">Colaboración en Investigación</option>
              <option value="other">Otro</option>
            </select>
          </div>
          
         
          
          <div class="form-group">
            <label for="message">Cuéntame sobre tu proyecto *</label>
            <textarea id="message" name="message" rows="6" required 
                      placeholder="Describe tu proyecto, objetivos, desafíos y cómo crees que puedo ayudarte..."></textarea>
          </div>
          
          <input type="hidden" name="_subject" value="Nuevo mensaje desde el portafolio">
          <input type="hidden" name="_captcha" value="false">
          <input type="hidden" name="_next" value="https://tu-dominio.github.io/thank-you">
          
          <button type="submit" class="btn btn-primary btn-large">Enviar Mensaje</button>
        </form>
      </div>
    </div>
    
    <div class="col-md-4">
      <div class="contact-info">
        <h3>Información de Contacto</h3>
        
        <div class="contact-item">
          <i class="fas fa-envelope"></i>
          <div>
            <strong>Email</strong><br>
            <a href="mailto:tu.email@ejemplo.com">tu.email@ejemplo.com</a>
          </div>
        </div>
        
        <div class="contact-item">
          <i class="fab fa-linkedin"></i>
          <div>
            <strong>LinkedIn</strong><br>
            <a href="https://linkedin.com/in/tu-perfil" target="_blank">linkedin.com/in/tu-perfil</a>
          </div>
        </div>
        
        <div class="contact-item">
          <i class="fab fa-github"></i>
          <div>
            <strong>GitHub</strong><br>
            <a href="https://github.com/tu-usuario" target="_blank">github.com/tu-usuario</a>
          </div>
        </div>
        
        <div class="contact-item">
          <i class="fab fa-twitter"></i>
          <div>
            <strong>Twitter</strong><br>
            <a href="https://twitter.com/tu-usuario" target="_blank">@tu-usuario</a>
          </div>
        </div>
      </div>
      
      <div class="availability-status">
        <h4>📅 Disponibilidad</h4>
        <div class="status-indicator available">
          <span class="status-dot"></span>
          Disponible para nuevos proyectos
        </div>
        <p><small>Tiempo de respuesta promedio: 24-48 horas</small></p>
      </div>
      
      <div class="collaboration-types">
        <h4>🤝 Tipos de Colaboración</h4>
        <ul>
          <li>✅ Proyectos freelance</li>
          <li>✅ Consultoría técnica</li>
          <li>✅ Investigación colaborativa</li>
          <li>✅ Mentoring y capacitación</li>
          <li>✅ Oportunidades de empleo</li>
        </ul>
      </div>
    </div>
  </div>
</div>

<style>
.contact-container {
  max-width: 1000px;
  margin: 0 auto;
}

.contact-intro {
  background: #f8f9fa;
  padding: 30px;
  border-radius: 8px;
  margin-bottom: 40px;
  border-left: 4px solid #007bff;
}

.contact-form {
  background: white;
  padding: 30px;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.form-group {
  margin-bottom: 20px;
}

.form-group label {
  display: block;
  margin-bottom: 5px;
  font-weight: 600;
  color: #333;
}

.form-group input,
.form-group select,
.form-group textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ddd;
  border-radius: 4px;
  font-size: 16px;
  transition: border-color 0.3s ease;
}

.form-group input:focus,
.form-group select:focus,
.form-group textarea:focus {
  outline: none;
  border-color: #007bff;
  box-shadow: 0 0 0 2px rgba(0,123,255,0.25);
}

.btn-large {
  padding: 15px 30px;
  font-size: 18px;
  font-weight: 600;
}

.contact-info {
  background: white;
  padding: 25px;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  margin-bottom: 30px;
}

.contact-item {
  display: flex;
  align-items: flex-start;
  margin-bottom: 20px;
  padding-bottom: 15px;
  border-bottom: 1px solid #f1f1f1;
}

.contact-item:last-child {
  border-bottom: none;
  margin-bottom: 0;
}

.contact-item i {
  font-size: 20px;
  margin-right: 15px;
  margin-top: 5px;
  color: #007bff;
  width: 25px;
}

.contact-item a {
  color: #007bff;
  text-decoration: none;
}

.contact-item a:hover {
  text-decoration: underline;
}

.availability-status {
  background: #e8f5e8;
  padding: 20px;
  border-radius: 8px;
  margin-bottom: 30px;
  border: 1px solid #c3e6c3;
}

.status-indicator {
  display: flex;
  align-items: center;
  margin-bottom: 10px;
}

.status-dot {
  width: 12px;
  height: 12px;
  border-radius: 50%;
  margin-right: 10px;
}

.available .status-dot {
  background: #28a745;
  animation: pulse 2s infinite;
}

@keyframes pulse {
  0% { opacity: 1; }
  50% { opacity: 0.5; }
  100% { opacity: 1; }
}

.collaboration-types {
  background: white;
  padding: 25px;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.collaboration-types ul {
  list-style: none;
  padding: 0;
}

.collaboration-types li {
  margin-bottom: 8px;
  font-size: 0.95em;
}

@media (max-width: 768px) {
  .contact-container {
    padding: 0 15px;
  }
  
  .contact-intro,
  .contact-form,
  .contact-info,
  .collaboration-types {
    padding: 20px;
  }
}
</style>
