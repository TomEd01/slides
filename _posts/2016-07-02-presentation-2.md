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
<section>
  <section data-background="{{site.baseurl}}/_posts/temperatura.jpg" data-background-repeat="repeat" data-background-size="100px">
    <p>1.2</p>
    <h2>Sensores de Temperatura</h2>
  </section>
  <section>
    <p>1.2.1</p>
    <h2>Tipos</h2>    
    <ol>
      <li>Termistores: Cambian su resistencia con la temperatura <span class="fragment highlight-red">(NTC y PTC)</span>.</li>
      <li>Termopares: Generan voltaje dependiendo de la diferencia de temperatura entre dos metales.</li>
      <li>Sensores de Infrarrojos: Detectan la temperatura de objetos basándose en la radiación infrarroja.</li>
      <li>RTD <span class="fragment highlight-red">(Resistance Temperature Detector)</span>: Miden temperatura a través de un cambio en la resistencia de un material metálico <span class="fragment highlight-red">(como el platino)</span>.</li>
    </ol>
  </section>
</section>
<section>
  <p>1.2.2.</p>
  <h2>Funcionamiento</h2>
  <p>Cada tipo de sensor de temperatura opera midiendo cambios físicos o eléctricos debidos a la temperatura. Los termistores y RTD cambian su resistencia eléctrica; los termopares generan una diferencia de potencial,   mientras que los sensores IR miden la radiación emitida por un objeto.</p>
</section>


{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1><p>{{ slide.slide-data | newline_to_br }}</p></section>
                    
{% endfor %}
