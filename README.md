# dishpointer
Apuntador Satelital grafico de órbita Geo Estacionaria
 
Como dato de entrada se le da la Latitud y Longitud de la antena receptora y como resultado se obtiene un mapa o dashboard de apuntamiento para el set de satélites Geoestacionarios del listado entregado, pueden ser agregados otros.

Recordar que la Longitud Oeste (W) es Negativa y la Este (E) es Positiva, lo mismo con la Latitud Norte (N) es Positiva y Sur (S) es Negativa

Además se genera una Cinta Plantilla imprimible para el tubo vertical de la antena satelital, el cual se usa para medir la vuelta o media vuelta los 180°, se cuentan las rayas, este número se ingresa en el formulario y como resultado se genera la Cinta imprimible para apuntamiento perfecto de todos el set de satélites ingresados, facilitando mucho el trabajo, es importante que al pegar la cinta en el tubo, esta apunte hacia el norte o sur donde dice norte. (da lo mismo si es norte o sur ya que esta espejada la cinta)

Si se fijan la cinta tiene un área para cubrir el tubo por completo, pero esta espejada, de manera tal que la pueden ver desde adelante o desde atrás y serán los mismos puntos de orientación.

También podrán notar que en vez de utilizar el Azimut, se utiliza la referencia del Norte, lo que hace mucho más simple el apuntamiento, aquí no se hace referencia a los 360 grados, si no, a que tan distante están del Norte, positivo es grados al Este y Negativo son grados hacia el Oeste.

#Sugerencia# antes de pegar la Cinta de referencia en el tubo, **orienten** la antena o al menos **la cinta hacia el Norte**, de esta forma calzara perfecto.

Suele ocurrir que durante el apuntamiento hacia el satélite, lo más sensible sea la altitud, por lo que, este es el punto crítico, sin embargo la orientación en referencia al Norte suele tener mayor juego disponible, puede que un par de grados aun tome el satélite y en cuanto al giro del LNB este es menos sensible, basta con quedar aproximadamente al giro indicado y funcionara, finalmente el foco del LNB es solo para afinar, este es cuando puedes mover el LNB hacia adelante o hacia atrás un poquito, lo que solo depende de una combinación de la base del LNB, la forma del LNB y de la forma de la antena.

Al generar el resultado de apuntamiento para un set de satélites en vez de solo uno a la vez, es más fácil comprender donde están posicionados y como corregir la orientación, también como se irán recorriendo a medida que se desplaza la antena. y que tan lejos están unos de otros.

Para comprender mejor hay que saber que los satélites Geoestacionarios de televisión, están todos ubicados en la latitud del Ecuador, fijos, estos giran desplazándose junto con la tierra a unos 35700 km de distancia aprox (considerando que Ud. esta aprox 6300km del centro de la tierra), por eso no se mueven desde nuestro punto de vista, de hecho imagínese un arco en el ecuador, donde hay un punto justo en el centro del Norte y ese es su punto ideal y este es el más alto desde su punto (lat, long), corresponde a su latitud, todos los otros satélites que estén mas a la izquierda o derecha comenzaran a estar más bajos (desde su perspectiva), hasta llegar a aprox los 30 grados de elevación, inferior a eso será muy difícil captarlos, los satélites que podrá captar bien están desde -70 hasta los 70 grados de su norte, pasados estos hay un rango que se puede llegar a captar por reflexión, pero hay que ser demasiado preciso y es muy probable que no envie señal (pisada) a su zona.

La pisada de un satélite es importante, ya que estos poseen varias antenas emisoras y que cubren solo algunas zonas, incluso poseen marcos para dar forma a su área limite, y estos suelen tener pisada dentro de un rango próximo a los 70 grados e incluso mucho menos y en ocasiones solo hacia la zona norte o la sur del planeta.

La razón del Giro del LNB debido a que se captan señales en horizontal y vertical, (si ve el LNB por dentro tiene dos metales o antenas en cruz uno en horizontal y el otro vertical) si este no se encuentra en la inclinación correcta no captara la señal, por lo que, debe girar aproximadamente lo sugerido en el cálculo, si el satélite está a la derecha de su norte, deberá girarlo a la derecha y lo mismo si está a la izquierda, claro si esta próximo al norte (frente a Ud.), este no requiere ningún giro, considere que el satélite emite señal desde su punto hacia un objetivo, que suele esta en frente y así tiene orientada su antena.

Señales FTA: (Free to Air) estas son las señales abiertas, que no requieren de ningún decodificador, ni suscripción y cada satélite tiene al menos una señal FTA la cual sirve para su captura.

Al apuntar y buscar satélites se le llama Cazar satélites, esto se hace con ayuda de un TP (Transponder) que es el equivalente una señal o frecuencia especifica de una radio, estos en la banda Ku se dividen en cuatro partes, bajas, altas, Vertical, Horizontal, el LNB es capaz de sintonizar la combinación indicada por el receptor o STB (Set of Box) que envía voltajes al LNB para indicarle que requiere

Con el TP y la posición del satélite se comienza a buscar señal, pero una vez cazado, hay que, buscar todos sus TP, es como escanear la radio en busca de sintonías claras y fuertes, luego cada TP posee en forma digital un set de canales comprimidos, estos pueden ser de radio, tv, subtítulos, textos, audios, agenda y otras cosas

Una vez cazado el satélite y detectado algunos TP con canales o radios FTA (libres) podrás comenzar a buscar la mejor calidad posible de orientación, este es el paso para finar el apuntamiento y probar todos los canales captados.

Finalmente lo que se suele hacer es **MARCAR** la elevación, orientación norte y el giro del LNB, (hacer una raya entre el área fija del metal y la que se mueve) para luego poder volver cuando quieras a ese punto sin tener que realizar tantos pasos, ni dedicar tanto tiempo.


Próximamente agregare la corrección del Norte Magnético, pero como alternativa inmediata, habiendo apuntando un satélite, puede pegar otra vez la cinta en el tubo fijando ese satélite en su posición real (así corrigen todas las posiciones en un solo paso) y verificar la diferencia entre el Norte y el norte magnético que le dará cualquier brújula, suele ser mínima la diferencia que como les comente este es un punto no es tan crítico y permite holgura, ya que, suele cubrir un par de grados a cada lado gracias a la forma de la antena parabólica y el ancho de la señal emitida.

Para cerrar informarles que no se requiere mucho para hacer funcionar esta App, con solo tener el archivo app.html en un teléfono móvil, no requiere internet, ni nada extra para funcionar. Solo ingresen su posición dan a Calcular y listo. Incluso se la pueden enviar por whatsapp y ejecutarla offline desde ahí.

Suerte con la cacería !!!
y que el FTA te bendiga

![Screenshot of Apuntador Dishpointer v0.1](sample.png)
