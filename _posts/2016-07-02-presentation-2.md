---

title: Presentation 2
layout: post
permalink: /presentation-2/

---
<section>
  <section>
    <h1>Sensores Ópticos</h1>
    <p>1.1.1 Tipos:</p><br>
      <ol>
        <li>Fotodiodos/Fototransistores: Detectan la intensidad de la luz.</li>
        <li>Células Fotovoltaicas: Generan energía a partir de la luz solar.</li>
      </ol>
  </section>
  <section>
    <h1>Sensores Ópticos</h1>
    <p>1.1.1 Tipos:</p><br>
    <ol>
        <li>Sensores de Fibra Óptica: Utilizan cambios en la luz transmitida a través de fibras ópticas.</li>
        <li>Sensores Infrarrojos (IR): Detectan radiación infrarroja para medir distancia o detectar objetos.</li>
    </ol>
  </section>
</section>
<section>
  <p>1.1.2</p><br>
  <h2>Funcionamiento</h2>
  <p>Los sensores ópticos funcionan captando o emitiendo luz y midiendo su variación, reflexión o interrupción. Pueden usar diferentes longitudes de onda<span class="fragment highlight-red">(visible, UV o infrarrojo)</span> y dependen del material y diseño para la conversión de la luz en una señal eléctrica.</p>
</section>
<section>
  <p>1.1.3</p><br>
  <h2>Caracteriaticas</h2>
  <ol>
    <li clas="fragment">Sensibilidad a la luz</li>
    <li>Rango de detección <span class="fragment highlight-red">(distancia, intensidad).</span></li>
    <li>Precisión y tiempo de respuesta.</li>
    <li>Resistencia a interferencias ambientales <span class="fragment highlight-red">(polvo, humedad).</span></li>
  </ol>
</section>
<section>
  <p>1.1.4.</p>
  <h2>Modo de Comunicación</h2>
  <p>Señales análogas <span class="fragment highlight-red">(variación de voltaje o corriente)</span>. Digital mediante protocolos como I2C o SPI para transmisión de datos.</p>
</section>


{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1><p>{{ slide.slide-data | newline_to_br }}</p></section>
                    
{% endfor %}
