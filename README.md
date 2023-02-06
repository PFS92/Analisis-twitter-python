# Analisis-twitter-python
Accede a la web de desarrolladores de Twitter y crea una cuenta y aplicación. Guarda tus claves (consumer_key, consumer_secret, token y secret).
Utilizando estas claves y la librería tweepy invoca un comando para escuchar tweets incluyendo algún tema de actualidad que te resulte de interés.
Almacena estos tweets en un fichero, utilizando el formato que prefieras.
A continuación, crea un dataframe con pandas con las siguientes columnas, el usuario del tweet, el texto del tweet, fecha de creación, localización, número de palabras del texto y número de caracteres del tweet (estos dos últimos campos deberás calcularlos a partir del texto del tweet).
Añade una columna al dataframe que refleje la hora del tweet (P.ej. Si el tweet tiene la fecha u'Mon May 23 14:46:46 +0000 2016' vamos a convertirlo a 14). Llama a este nuevo campo hora.
Agrega el dataframe por el campo hora y muestra por pantalla el número de tweets por hora.
