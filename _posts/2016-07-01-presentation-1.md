title: Presentation 1
layout: post
permalink: /presentation-1/
background: '#0a5'
slides:
 - title: Sensores Ópticos
   slide-data: |
     Tipos: <br>
     - Fotodiodos  
     - Fototransistores  
     - Células fotovoltaicas  
     - Sensores de fibra óptica  
     - Sensores infrarrojos
     
     Funcionamiento: <br>
     Detectan o emiten luz y miden su variación, reflexión o interrupción.
     
 - title: Características de Sensores Ópticos
   slide-data: |
     Características: <br>
     - Sensibilidad a la luz  
     - Rango de detección  
     - Precisión  
     - Resistencia a interferencias
     
     Modo de comunicación: <br>
     Señales analógicas o digitales (I2C, SPI).

 - title: Sensores de Temperatura
   slide-data: |
     Tipos: <br>
     - Termistores  
     - Termopares  
     - Sensores infrarrojos  
     - RTD
     
     Funcionamiento: <br>
     Detectan cambios de temperatura a través de variaciones en resistencia, voltaje o radiación infrarroja.

 - title: Características de Sensores de Temperatura
   slide-data: |
     Características: <br>
     - Rango de temperatura  
     - Precisión  
     - Tiempo de respuesta
     
     Modo de comunicación: <br>
     Señal análoga o digital (I2C, SPI, 1-Wire).

 - title: Sensores de Presión
   slide-data: |
     Tipos: <br>
     - Piezoresistivos  
     - Capacitivos  
     - Piezoeléctricos  
     - Manómetros
     
     Funcionamiento: <br>
     Miden la presión a través de cambios en resistencia, capacitancia o generación de corriente eléctrica.

 - title: Características de Sensores de Presión
   slide-data: |
     Características: <br>
     - Rango de presión  
     - Precisión  
     - Linealidad
     
     Modo de comunicación: <br>
     Señal analógica o digital (I2C, SPI).

 - title: Sensores de Proximidad
   slide-data: |
     Tipos: <br>
     - Inductivos  
     - Capacitivos  
     - Ópticos  
     - Ultrasónicos
     
     Funcionamiento: <br>
     Detectan objetos mediante campos magnéticos, eléctricos, luz o sonido.

 - title: Características de Sensores de Proximidad
   slide-data: |
     Características: <br>
     - Distancia de detección  
     - Precisión  
     - Detección de diferentes materiales
     
     Modo de comunicación: <br>
     Salida digital discreta o protocolos como I2C, SPI.

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1><p>{{ slide.slide-data | newline_to_br }}</p></section>
                    
{% endfor %}
