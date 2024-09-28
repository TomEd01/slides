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
     - Sensores de fibra óptica  
     
     Funcionamiento: <br>
     Detectan luz y miden su variación.
     
 - title: Características de Sensores Ópticos
   slide-data: |
     Características: <br>
     - Sensibilidad a la luz  
     - Rango de detección  
     
     Modo de comunicación: <br>
     Señales analógicas o digitales (I2C, SPI).

 - title: Sensores de Temperatura
   slide-data: |
     Tipos: <br>
     - Termistores  
     - Termopares  
     - RTD  
     
     Funcionamiento: <br>
     Miden cambios de temperatura.

 - title: Características de Sensores de Temperatura
   slide-data: |
     Características: <br>
     - Rango de temperatura  
     - Precisión  
     
     Modo de comunicación: <br>
     Señal análoga o digital (I2C, SPI).

 - title: Sensores de Presión
   slide-data: |
     Tipos: <br>
     - Piezoresistivos  
     - Capacitivos  
     
     Funcionamiento: <br>
     Miden la presión mediante cambios eléctricos.

 - title: Características de Sensores de Presión
   slide-data: |
     Características: <br>
     - Rango de presión  
     - Precisión  
     
     Modo de comunicación: <br>
     Señal analógica o digital (I2C, SPI).

 - title: Sensores de Proximidad
   slide-data: |
     Tipos: <br>
     - Inductivos  
     - Ópticos  
     
     Funcionamiento: <br>
     Detectan objetos mediante campos eléctricos o luz.

 - title: Características de Sensores de Proximidad
   slide-data: |
     Características: <br>
     - Distancia de detección  
     - Precisión  
     
     Modo de comunicación: <br>
     Salida digital discreta o protocolos como I2C, SPI.

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1><p>{{ slide.slide-data | newline_to_br }}</p></section>
                    
{% endfor %}
