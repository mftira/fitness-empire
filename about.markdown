---
layout: default
title: About
permalink: /about/
---

<div class="about-page">

  <div class="about-container">
    <div class="about-header">
      <h1 class="gradient-text">About Fitness Empire</h1>
      <p class="about-subtitle">Your Ultimate Health & Fitness Resource</p>
    </div>

    <div class="about-content">
      <section class="about-section">
        <h2>Our Vision</h2>
        <p>Fitness Empire is devoted to helping individuals thrive in their health and wellness journey. We curate the most valuable content 
        on workouts, nutrition, wellness practices, motivation techniques, and healthy lifestyle choices that drive 
        measurable results for people of all fitness levels.</p>
      </section>

      <section class="about-section">
        <h2>What We Cover</h2>
        <div class="features-grid">
          <div class="feature-card">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <path d="M18 8h1a4 4 0 010 8h-1"></path>
              <path d="M2 8h16v9a4 4 0 01-4 4H6a4 4 0 01-4-4V8z"></path>
              <line x1="6" y1="1" x2="6" y2="4"></line>
              <line x1="10" y1="1" x2="10" y2="4"></line>
              <line x1="14" y1="1" x2="14" y2="4"></line>
            </svg>
            <h3>Workout Routines</h3>
            <p>Comprehensive guides on strength training, cardio, flexibility, and specialized workout programs</p>
          </div>
          <div class="feature-card">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <path d="M12 20v-6M6 20V10M18 20V4"></path>
            </svg>
            <h3>Nutrition & Diet</h3>
            <p>Expert insights on meal planning, macronutrients, supplements, and nutrition strategies for performance</p>
          </div>
          <div class="feature-card">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <path d="M4 19.5A2.5 2.5 0 0 1 6.5 17H20"></path>
              <path d="M6.5 2H20v20H6.5A2.5 2.5 0 0 1 4 19.5v-15A2.5 2.5 0 0 1 6.5 2z"></path>
            </svg>
            <h3>Wellness Practices</h3>
            <p>Holistic approaches to health including sleep optimization, stress management, and recovery techniques</p>
          </div>
          <div class="feature-card">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <polygon points="13 2 3 14 12 14 11 22 21 10 12 10 13 2"></polygon>
            </svg>
            <h3>Motivation & Mindset</h3>
            <p>Strategies for building consistency, overcoming plateaus, and developing a healthy relationship with fitness</p>
          </div>
        </div>
      </section>

      <section class="about-section">
        <h2>The Fitness Empire Advantage</h2>
        <ul class="benefits-list">
          <li>✓ Actionable content from fitness experts</li>
          <li>✓ Science-backed approaches to health</li>
          <li>✓ Up-to-date with latest fitness research</li>
          <li>✓ Practical insights for all fitness levels</li>
        </ul>
      </section>

      <section class="about-section contact-section">
        <h2>Connect With Us</h2>
        <p>For collaborations, partnerships, or inquiries, please contact us at:</p>
        <a href="mailto:{{ site.email }}" class="contact-button">{{ site.email }}</a>
      </section>
    </div>
  </div>
</div>

<style>
.about-page {
  background: var(--bg-primary);
}

.about-header {
  text-align: center;
  margin-bottom: 4rem;
}

.about-subtitle {
  font-size: 1.25rem;
  color: var(--text-secondary);
  margin-top: 1rem;
}

.about-section {
  margin-bottom: 4rem;
}

.features-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.feature-card {
  background: var(--card-bg);
  padding: 2rem;
  border-radius: 0.5rem;
  border: 1px solid var(--border-color);
  text-align: center;
  transition: all 0.3s ease;
}

.feature-card:hover {
  transform: translateY(-5px);
  box-shadow: var(--shadow-lg);
}

.feature-card svg {
  color: var(--accent-color);
  margin-bottom: 1rem;
  width: 40px;
  height: 40px;
}

.benefits-list {
  list-style: none;
  padding: 0;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
  margin-top: 2rem;
}

.benefits-list li {
  padding: 1rem;
  background: var(--card-bg);
  border-radius: 0.5rem;
  border: 1px solid var(--border-color);
}

.contact-section {
  text-align: center;
}

.contact-button {
  display: inline-block;
  padding: 1rem 2rem;
  background: var(--accent-color);
  color: white;
  border-radius: 0.5rem;
  margin-top: 1rem;
  transition: all 0.3s ease;
}

.contact-button:hover {
  background: var(--accent-hover);
  transform: translateY(-2px);
}

@media (max-width: 768px) {
  .features-grid {
    grid-template-columns: 1fr;
  }
  
  .benefits-list {
    grid-template-columns: 1fr;
  }
}
</style>
