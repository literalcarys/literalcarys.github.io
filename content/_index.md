---
title: "Home"
---

Welcome! I am a Master's student in Astrophysics at the **University of Cape Town**, specialising in **X-Ray Astronomy** and **Active Galactic Nuclei (AGN)**.

My current research focuses on the multiwavelength analysis of local AGN from the 12-Micron Galaxy Sample (12MGS). I work with data from X-ray observatories such as **Chandra**, **XMM-Newton** and **NuSTAR**, as well as radio data from **MeerKAT**, to characterise the properties of AGN and their host galaxies.

Outside of Astronomy you can generally find me hanging out with my two cats, <a href="#" id="frodo-link">Frodo</a> and <a href="#" id="turnip-link">Turnip</a>!

<script>
document.addEventListener('DOMContentLoaded', function() {
  function catLightbox(linkId, src) {
    var link = document.getElementById(linkId);
    link.addEventListener('click', function(e) {
      e.preventDefault();
      var overlay = document.createElement('div');
      overlay.style.cssText = 'position:fixed;inset:0;z-index:999;background:rgba(0,0,0,0.5);display:flex;align-items:center;justify-content:center;cursor:pointer;';
      var img = document.createElement('img');
      img.src = src;
      img.style.cssText = 'max-width:90vw;max-height:90vh;border-radius:8px;';
      overlay.appendChild(img);
      overlay.addEventListener('click', function() { overlay.remove(); });
      document.body.appendChild(overlay);
    });
  }
  catLightbox('frodo-link', '/img/frodo.jpeg');
  catLightbox('turnip-link', '/img/turnip.jpeg');
});
</script>
