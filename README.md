# Asistente de voz
Este programa fue diseñado en Júpiter, realiza tareas básicas que los usuarios necesiten en su hogar y en su día a dia. Para su ejecución es necesario instalar unas librerías en anaconda.
* playsound.
* gTTS.
* speech_recognition.
* pandas.

Una vez iniciado el programa, este esperará que el usuario diga su nombre, en este caso el asistente fue llamado: "celeste".
El asistente al detectar que fue llamado dirá que está dispuesto a escuchár alguna orden, entre las órdenes que esté puede atender se encuentra: 
* Envío de mensajes.
   * Solicitará el nombre de la persona a la cual se quiere enviar un mensaje.
* Lectura del último mensaje enviado.
* Encendedor algún aparato electrónico.
* Realizar operaciones artimeticas.
   * Suma.
   * Resta.
   * Multiplicación.
   * Division.
* Dar el clima.
  * Dar la probabilidad de lluvia.
* Dar la hora.
   * Posibilidad de colocar alguna alarma.

Si el usuario quiere mandar un mensaje, le debera decir al asistente que desea mandar o redactar un mensaje, inmediatamente el asistente respondera que esta listo para escuchar el mensaje en ese momento el usuario se lo debera decir, posteriormente el asistente solicitara el nombre de la persona a la cual se enviara el mensaje, si el nombre de dicha persona se encuentra entre la lista de contactos del usuario, se le notificará que el mensaje fue enviado correctamente, en caso contrario se le avisará al usuario que la persona no se encuentra entre su lista de contactos y que el mensaje no fue enviado.

Si el usuario solicita la lectura del último mensaje enviado y no se ha enviado nada, el asistente responderá que no ha mandado mensaje alguno, en caso contrario el asistente leerá el último mensaje y dira el nombre de a quien fue enviado.

Si el usuario solicita encender algún aparato electrónico, el asistente responderá que fue encendido.

Si el usuario necesita realizar alguna operación aritmética, este necesita decir que eso desea, posteriormente tendrá que decir cuál operación va a efectuar y el asistente responderá con el resultado.

Si el usuario solicita saber cómo está el clima en ese momento, el asistente responderá con un mensaje aleatorio referente al clima, adicionalmente será posible preguntarle al asistente cuál es la probabilidad de lluvia que hay actualmente y nuevamente el asistente responderá con un mensaje aleatorio referente a dicha probabilidad.

Si el usuario pide que el asistente le dé la hora, el asistente se la proporcionará y adicionalmente a ello el asistente preguntara si es que el usuario necesita colocar una alarma, si es el caso bastará con que el usuario diga en cuanto tiempo a partir de que solicita la alarma quiere que se le avisé ya ha pasado el tiempo que establezca.

Finalmente el asistente preguntara si necesita realizar alguna otra tarea, si el usuario da una respuesta afirmativa el asistente responderá que está lista para escuchar la orden, en caso contrario el asistente responderá con algún mensaje de despedida y concluira el programa.

![asistente](https://www.elsevier.com/__data/assets/image/0020/1040447/Imagen_Articulo_Asistentes-Virtuales_SP_op1.jpg)