---
layout: page
title: Get in touch
sitemap: false
---

I am addressing addressing complex engineering challenges, speaking and advocating for science in K-12, creating workshops, publishing research findings, and building open source and commercial tools in deep tech, biomechanics and embedded IoT.

There's always work to be done in my wheelhouse!

<!-- <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
  <label for="name">Name</label>
  <input type="text" name="name" id="name" required><br />
  
  <label for="email">Email</label>
  <input type="email" name="email" id="email" required><br />
  
  <label for="message">Message</label>
  <textarea name="message" id="message" rows="5" required></textarea><br />
  
  <button type="submit">Send</button>
</form> -->

<div class="contact-form-wrapper">
  <form action="https://formspree.io/f/mzdqlgzp" method="POST" class="contact-form">
    <div class="form-field">
      <label for="name">Name</label>
      <input type="text" name="name" id="name" required>
    </div>
    <div class="form-field">
      <label for="email">Email</label>
      <input type="email" name="email" id="email" required>
      <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>      
    </div>
    <div class="form-field">
      <label for="message">Message</label>
      <textarea name="message" id="message" rows="5" required></textarea>
    </div>

    <button type="submit">Send Message</button>
  </form>
</div>

<style>
  .contact-form-wrapper {
    max-width: 680px;
    margin: 2rem auto;
    padding: 2rem;
    background: #ffffff;
    border: 1px solid #e2e2e2;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.04);
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  }

  .contact-form {
    display: flex;
    flex-direction: column;
    gap: 1.25rem;
  }

  .form-field {
    display: flex;
    flex-direction: column;
    gap: 0.4rem;
  }

  .form-field label {
    font-size: 0.875rem;
    font-weight: 600;
    color: #333333;
  }

  .form-field input,
  .form-field textarea {
    font-family: inherit;
    font-size: 1rem;
    padding: 0.65rem 0.75rem;
    border: 1px solid #cccccc;
    border-radius: 6px;
    background: #fafafa;
    transition: border-color 0.15s ease, box-shadow 0.15s ease;
  }

  .form-field input:focus,
  .form-field textarea:focus {
    outline: none;
    border-color: #4a90e2;
    box-shadow: 0 0 0 3px rgba(74, 144, 226, 0.15);
    background: #ffffff;
  }

  .form-field textarea {
    resize: vertical;
    min-height: 120px;
  }

  .contact-form button {
    align-self: flex-start;
    padding: 0.7rem 1.75rem;
    font-size: 1rem;
    font-weight: 600;
    color: #ffffff;
    background: #4a90e2;
    border: none;
    border-radius: 6px;
    cursor: pointer;
    transition: background 0.15s ease;
  }

  .contact-form button:hover {
    background: #3a7bc8;
  }

  .contact-form button:focus-visible {
    outline: 2px solid #2c5a8c;
    outline-offset: 2px;
  }

  @media (max-width: 480px) {
    .contact-form-wrapper {
      padding: 1.25rem;
      margin: 1rem;
    }

    .contact-form button {
      align-self: stretch;
    }
  }
</style>

<!-- #### {{< fa envelope >}} &nbsp; masiello@uw.edu -->
<!-- #### {{< fa envelope >}} &nbsp; bulusu@gwu.edu -->
<!-- #### {{< fa phone >}} &nbsp; 206-543-5579 -->

<!-- #### {{< fa map-location-dot >}} &nbsp; Department of Chemistry, CHB 304F, Seattle, WA 98195-1700 -->
#### Address: 
Department of Mechanical and Aerospace Engineering, <br />
Suite 3000, <br />
800 22nd street NW <br />
Washington DC 20052

<!-- 
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />
<style>
  #map { height: 400px; }
</style>

<div id="map"></div>

<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
<script>
  document.addEventListener("DOMContentLoaded", function () {
    const map = L.map("map").setView([38.900051, -77.049426], 17);

    L.tileLayer("https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png", {
      attribution: "&copy; OpenStreetMap contributors"
    }).addTo(map);

    L.marker([38.900051, -77.049426]).addTo(map);
  });
</script> -->

<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />
<style>
  #map { height: 400px; }
</style>
<div id="map"></div>
<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
<script>
  function initMap() {
    const map = L.map("map").setView([38.900051, -77.049426], 17);
    L.tileLayer("https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png", {
      attribution: "&copy; OpenStreetMap contributors"
    }).addTo(map);
    L.marker([38.900051, -77.049426]).addTo(map);
  }

  if (document.readyState === "loading") {
    document.addEventListener("DOMContentLoaded", initMap);
  } else {
    initMap();
  }
</script>