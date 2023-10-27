# dishpointer
Apuntador Satelital grafico de orbita GeoEstacionaria

Como dato de entrada se le da la Latitud y Longitud de la antena receptora y como resultado se obtiene un mapa o dashboard de apuntamiento para el set de satelites Geoestacionarios del listado entregado, pueden ser agregados otros.

Recordar que la Longitud Oeste (W) es Negativa y la Este (E) es Positiva, lo mismo con la Latitud Norte (N) es Positiva y Sur (S) es Negativa

Ademas se genera una Cinta Plantilla imprimible para el tubo vertical de la antena satelital, el cual se usa para medir la vuelta o media vuelta los 180°, se cuentan las rayas, este numero se ingresa en el formulario y como resultado se genera la Cinta imprimible para apuntamiento perfecto de todos el set de satelites ingresados, facilitando mucho el trabajo, es importante que al pegar la cinta en el tubo, esta apunte hacia el norte donde dice norte.

Si se fijan la cinta tiene un area para cubrir el tubo por completo, pero esta espejada, de manera tal que la pueden ver desde adelante o desde atras y seran los mismos puntos de orientacion.

Tambien podran notar que en vez de utilizar el Azimut, se utiliza la referencia del Norte, lo que hace mucho mas simple el aputamiento, aqui no se hace referencia a los 360 grados, si no, a que tan distante estan del Norte, positivo es grados al Este y Negativo son grados hacia el Oeste.

#Sugerencia# antes de pegar la Cinta de referencia en el tubo, **orienten** la antena o al menos **la cinta hacia el Norte**, de esta forma calzara perfecto.

Suele ocurrir que durante el apuntamiento hacia el satelite, lo mas sensible sea la altitud, por lo que, este es el punto critico, sin embargo la orientacion en referencia al Norte suele tener mayor juego disponible, puede que un par de grados aun tome el satelite y en cuanto al giro del LNB este es menos sensible, basta con quedar aproximadamente al giro indicado y funcionara, finalmente el foco del LNB es solo para afinar, este es cuando puedes mover el LNB hacia adelante o hacia atras un poquito, lo que solo depende de una combinacion de la base del LNB, la forma del LNB y de la forma de la antena.

Al generar el resultado de apuntamiento para un set de satelites en vez de solo uno a la vez, es mas facil comprender donde estan posicionados y como corregir la orientacion, tambien como se iran recorriendo a medida que se desplaza la antena. y que tan lejos estan unos de otros.

Para comprender mejor hay que saber que los satelites Geoestacionarios de television, estan todos ubicados en la latitud del Ecuador, fijos, estos giran desplazandose junto con la tierra a unos 35700 km de distancia aprox (considerando que Ud esta aprox 6300km del centro de la tierra), por eso no se mueven desde nuestro punto de vista, de hecho imaginese un acro en el ecuador, donde hay un punto justo en el centro del Norte y ese es su punto ideal y este es el mas alto desde su punto (lat, long), corresponde a su latitud, todos los otros satelites que esten mas a la izquierda o derecha comenzaran a estar mas bajos (desde su perspectiva), hasta llegar a aprox los 30 grados de elevacion, inferior a eso sera muy dificil captarlos, los satelites que podra captar bien estan desde -70 hasta los 70 grados de su norte, pasados estos hay un rango que se puede llegar a captar por reflexion, pero hay que ser demasiado preciso y es muy probable que no envie señal (pisada) a su zona.

La pisada de un satelite es importante, ya que estos poseen varias antenas emisoras y que cubren solo algunas zonas, incluso poseen marcos para dar forma a su area limite, y estos suelen tener pisada dentro de un rango proximo a los 70 grados e incluso mucho menos y en ocaciones solo hacia la zona norte o la sur del planeta.

La razon del Giro del LNB debido a que se captan señales en horizontal y vertical, (si ve el LNB por dentro tiene dos metales o antenas en cruz uno en horizontal y el otro vertical) si este no se encuentra en la inclinacion correcta no captara la señal, por lo que, debe girar aproximadamente lo sugerido en el calculo, si el satelite esta a la derecha de su norte, debera girarlo a la derecha y lo mismo si esta a la izquierda, claro si esta proximo al norte (frente a ud), este no requiere ningun giro, considere que el satelite emite señal desde su punto hacia un objetivo, que suele esta en frente y asi tiene orientada su antena.

Señales FTA: (Free to Air) estas son las señales abiertas, que no requieren de ningun decodificador, ni suscripcion y cada satelite tiene al menos una señal FTA la cual sirve para su captura.

Al apuntar y buscar satelites se le llama Cazar satelites, esto se hace con ayuda de un TP (Transponder) que es el equivalente una señal o frecuencia especifica de una radio, estos en la banda Ku se dividen en cuatro partes, bajas, altas, Vertical, Horizontal, el LNB es capas de sintonizar la combinacion indicada por el receptor o STB (Set of Box) que envia voltajes al LNB para indicarle que requiere

Con el TP y la posicion del satelite se comienza a buscar señal, pero una vez cazado, hay que, buscar todos sus TP, es como escanear la radio en busca de sintonias claras y fuertes, luego cada TP posee en forma digital un set de canales comprimidos, estos pueden ser de radio, tv, subtitulos, textos, audios, agenda y otras cosas

Una vez cazado el satelite y detectado algunos TP con canales o radios FTA (libres) podras comenzar a buscar la mejor calidad posible de orientacion, este es el paso para finar el apuntamiento y probar todos los canales captados.

Finalmente lo que se suele hacere es **MARCAR** la elevacion, orientacion norte y el giro del LNB, (hacer una ralla entre el area fija del metal y la que se mueve) para luego poder volver cuando quieras a ese punto sin tener que realizar tantos pasos, ni dedicar tanto tiempo.

Suerte con la caceria !!!
y que el FTA te bendiga

![Screenshot of Apuntador Dishpointer](sample.png)
