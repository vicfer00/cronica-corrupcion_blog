---
layout: letter
title: "Crónica de una Corrupción Anunciada"
---
<img src="/assets/images/indexBanner.png" alt="Crónica de una Corrupción Anunciada Banner" style="width: 100%; max-width: 1000px; display: block; margin: 0 auto 2rem;">

> *“Perú es el país de las oportunidades perdidas.”*  
> — Julio Ramón Ribeyro

Bienvenido a esta bitácora del absurdo.  
Aquí comienza tu recorrido por **Crónica de una Corrupción Anunciada**, un espacio donde la sátira se vuelve instrumento de memoria, rabia y (a veces) risa.  
En este blog intento recordarle al peruano desmemoriado, a través de ironías y verdades incómodas, la historia que se entierra — o se niega — cada cinco años, justo antes de votar.

Este no es un blog objetivo.  
Es una colección de cartas abiertas escritas desde el exilio físico y emocional, firmadas por un testigo harto pero no indiferente.  
No esperes imparcialidad. Espera honestidad.  
No esperes análisis técnico. Espera bisturí emocional.  
Aquí se denuncia con humor, se recuerda con sarcasmo y se escribe con el hígado.

Y esta es la entrada del día.  
Mañana... veremos si hay país para escribir.

---

> ⚠️ **Advertencia**: Este blog puede contener verdades, sarcasmos y recuerdos que incomodan.

---

<h2 style="text-align: center;">⏳ Faltan <span id="countdown"></span> para que Perulandia elija su nuevo elenco</h2>

<script>
  const targetDate = new Date("April 12, 2026").getTime(); // Update if date changes

  const countdown = setInterval(function() {
    const now = new Date().getTime();
    const distance = targetDate - now;

    if (distance < 0) {
      document.getElementById("countdown").innerHTML = "¡Es hoy!";
      clearInterval(countdown);
      return;
    }

    const days = Math.floor(distance / (1000 * 60 * 60 * 24));
    const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));

    document.getElementById("countdown").innerHTML = days + " días, " + hours + "h " + minutes + "m";
  }, 1000);
</script>


---

## 🗞️ Últimas Cartas

{% for post in site.posts limit:5 %}
- 📝 **[{{ post.title }}]({{ post.url }})** <br>
  <span style="color:#777;">{{ post.date | date: "%d/%m/%Y" }}</span>
{% endfor %}

---


¿Quieres más?  
Explora el [Archivo](/archive/), conoce al [Autor](/about/), o si estás buscando algo específico, visita las [Categorías](/categories/).

<p class="signature">— Criollo Desubicado</p>
