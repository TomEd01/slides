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
  <section>
    <p>1.2.2.</p>
    <h2>Funcionamiento</h2>
    <p>Cada tipo de sensor de temperatura opera midiendo cambios físicos o eléctricos debidos a la temperatura. Los termistores y RTD cambian su resistencia eléctrica; los termopares generan una diferencia de potencial, mientras que los sensores IR miden la radiación emitida por un objeto.</p>
  </section>
  <section>
    <p>1.2.3</p>
    <h2>Caracteristicas</h2>
    <ol>
      <li>Rango de temperatura.</li>
      <li>Precisión y estabilidad a largo plazo.</li>
      <li>Sensibilidad <span class="fragment highlight-red">(cómo responden a pequeños cambios de temperatura)</span>.</li>
      <li>Tiempo de respuesta <span class="fragment highlight-red">(cuán rápido detectan cambios de temperatura)</span>.</li>
    </ol>
  </section>
  <section>
    <p>1.2.4</p>
    <h2>Modo de Comunicación</h2>
    <ol>
      <li>Señal análoga: Generalmente a través de una variación de voltaje o resistencia.</li>
      <li>Señal digital: Utilizando I2C, SPI, o 1-Wire.</li>
    </ol>
  </section>
</section>
<section>
  <section><h2>1.3 Sensores de Presión</h2></section>
  <section>
    <p>1.3.1.</p>
    <h2>Tipos</h2>
    <ol>
      <li>Piezoresistivos: Cambian su resistencia al aplicarse presión.</li>
      <li>Capacitivos: Detectan cambios en la capacitancia entre dos superficies cuando la presión varía.</li>
      <li>Piezoeléctricos: Producen una corriente eléctrica en respuesta a una presión mecánica.</li>
      <li>Manómetros: Utilizan un tubo o membrana flexible para medir la presión.</li>
    </ol>
  </section>
  <section>
    <p>1.3.2</p>
    <h2>Funcionamiento</h2>
    <p>Los sensores de presión miden la fuerza aplicada a un área. Pueden basarse en la deformación de materiales (piezoresistivos y capacitivos) o en la generación de cargas eléctricas (piezoeléctricos). Las variaciones de presión alteran las propiedades eléctricas del sensor, generando una señal que puede medirse.</p>
  </section>
  <section>
    <p>1.3.3</p>
    <h2>Caracteristica</h2>
    <ol>
      <li>Rango de presión (desde presiones bajas hasta extremadamente altas).</li>
      <li>Precisión y sensibilidad</li>
      <li>Linealidad y estabilidad de la señal a lo largo del tiempo.</li>
      <li>Resistencia a entornos agresivos (altas temperaturas, humedad).</li>
    </ol>
  </section>
  <section>
    <p>1.3.4</p>
    <h2>Modo de Comunicación</h2>
    <ol>
      <li>Rango de presión <span class="fragment highlight-red">(desde presiones bajas hasta extremadamente altas).Analógico (voltaje o corriente proporcional a la presión)</span>.</li>
      <li>Digital <span class="fragment highlight-red">(I2C, SPI, interfaces de bus industrial)</span>.</li>
    </ol>
  </section>
</section>
<section>
  <section><h2>1.4 Sensores de Proximidad</h2></section>
  <section>
    <p>1.4.1</p>
    <h2>Tipos</h2>
    <ol>
      <li>Inductivos: Detectan objetos metálicos mediante la alteración de un campo magnético.</li>
      <li>Capacitivos: Miden la variación en un campo eléctrico, detectando materiales conductores y no conductores.</li>
      <li>Ópticos: Emplean luz para detectar objetos mediante reflexión.</li>
      <li>Ultrasónicos: Emite ondas de sonido de alta frecuencia y mide el eco reflejado por un objeto.</li>
    </ol>
  </section>
  <section>
    <p>1.4.2</p>
    <h2>Funcionamiento</h2>
    <p>Cada tipo de sensor de proximidad detecta la presencia o cercanía de un objeto de manera distinta. Los inductivos responden a objetos metálicos, los capacitivos a variaciones en capacitancia, los ópticos a la reflexión de luz, y los ultrasónicos al tiempo que tarda un pulso de sonido en regresar al sensor.</p>
  </section>
  <section>
    <p>1.4.3</p>
    <h2>Caracteristica</h2>
    <ol>
      <li>Distancia máxima de detección.</li>
      <li>Precisión y resolución.</li>
      <li>Capacidad de detección de diferentes materiales.</li>
      <li>Resistencia a interferencias externas como el polvo o la humedad.</li>
    </ol>
  </section>
  <section>
    <p>1.4.4</p>
    <h2>Modo de comunicación</h2>
    <p>Salida digital discreta <span class="fragment highlight-red">(alta o baja, para indicar presencia)</span>. Protocolos de comunicación como I2C, SPI en versiones más avanzadas o complejas.</p>
  </section>
</section>


{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1><p>{{ slide.slide-data | newline_to_br }}</p></section>
                    
{% endfor %}
