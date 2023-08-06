# Colombia earthquake intensity and depth simple map (april/2023)

## Overall context

Due to Colombia's location on the Nazca and Caribbean tectonic plates, which are constantly moving and colliding with the South American plate, it can be asserted that the country is situated in one of the most active areas in the world in terms of seismic activity. These continuous interactions between the Nazca and South American plates have led to the formation of mountains, mountain ranges, and geological faults in different regions of the country.

As such, seismic events in Colombia are mainly due to two factors: activity in the Colombian Pacific subduction zone (related to the Pacific Ring of Fire) and active geological faults in the country. The main area that produces the largest number of earthquakes of various magnitudes is located in Los Santos, situated in the department of Santander and just around 60km (37.28 miles) away from Bucaramanga, the city where I live and where my university is located. In fact, Los Santos is known as the "Seismic Nest of Bucaramanga," and up to 20 earthquakes can be recorded there per day, making it responsible for more than 50% of seismic events in the country.

*Sources:* 
- https://www.idiger.gov.co/rsismico
- https://caracol.com.co/2023/03/18/por-que-tiembla-tanto-en-la-mesa-de-los-santos-santander-es-un-nido-sismico/
- https://www.eltiempo.com/colombia/otras-ciudades/temblores-en-colombia-los-santos-el-municipio-donde-hay-mas-sismos-por-que-772495

## About the code

The code you can find in this folder uses cv2, numpy, and matplotlib. Since it's a "simple map", I didn't use a dataset but randomly selected data from seven earthquakes that occurred between April and May, taken from an Excel file provided by the Colombian Geological Service (SGC) website. By mathematical analysis, I positioned the points (whose size varied according to the magnitude) based on their real latitudes and longitudes on a simple map of Colombia taken from Google Images. My way of verifying that the code worked was checking that the drawn points coincided with the location of the earthquake's origin and that their radii were consistent with the magnitude value.

---

# Mapa simple de la intensidad y profundidad de sismos en Colombia (abril/2023)

## Contexto general

Dado que en Colombia se encuentran las placas tectónicas de Nazca y del Caribe, las cuales están en constante movimiento y colisión con la placa Suramericana, se puede afirmar que el país está situado en una de las áreas más activas del mundo en cuanto a actividad sísmica. Estas interacciones continuas entre las placas de Nazca y Suramericana han propiciado a la formación de montañas, cordilleras y fallas geológicas en distintas regiones del país.

En sí, los eventos sísmicos en Colombia se deben principalmente por dos factores: la actividad en la zona de subducción del Pacífico colombiano (relacionado con el Cinturón de Fuego del Pacífico) y las fallas geológicas activas en el país. La principal área que produce la mayor cantidad de sismos y de múltiples magnitudes se encuentra en Los Santos, ubicado en el departamento de Santander y apenas alrededor de 60km de Bucaramanga, la ciudad donde resido y donde se ubica mi universidad. De hecho, Los Santos es conocido como el "Nido sísmico de Bucaramanga" y se pueden llegar a registrar hasta 20 sismos por día, lo que la hace responsable de la zona donde más del 50% de eventos sísmicos ocurren en el país.

*Fuentes:* 
- https://www.idiger.gov.co/rsismico
- https://caracol.com.co/2023/03/18/por-que-tiembla-tanto-en-la-mesa-de-los-santos-santander-es-un-nido-sismico/
- https://www.eltiempo.com/colombia/otras-ciudades/temblores-en-colombia-los-santos-el-municipio-donde-hay-mas-sismos-por-que-772495

## Sobre el código

El código disponible en la presente carpeta hace uso de cv2, numpy y matplotlib. Dado que es un "mapa simple", no usé un dataset sino que seleccioné aleatoriamente datos de siete sismos ocurridos entre abril y mayo, tomados de un excel propiciado por la página del Servicio Geológico Colombiano (SGC). Por análisis matemático, ubiqué los puntos (cuyo tamaño variaba según la magnitud) de acuerdo con las latitudes y longitudes reales en un simple mapa de Colombia tomado de google imágenes. Mi manera para verificar que el código funcionaba era rectificando que los puntos dibujados coincidían con el lugar donde se originó el sismo y qué el valor de sus radios fueran congruentes con el valor de la magnitud.
