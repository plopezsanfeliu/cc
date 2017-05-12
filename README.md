# TDMA
*Time division multiple access*
cada frame de time tiene diversos slots, uno para cada usuario
# FDMA
*Frequency division multiple access*
Cada usuario usa un rango de frecuencias distinto
# CDMA
*Code division multiple access*
cada bits se multiplexa con c´odigo ortogonal distinto

# CSMA/CA
## Exponential backoff
Tiempo aleatorio (dado con cierto número de caras) y uso el slot de tiempo N.
## Uso
Mandamos trama y esperamos ACK. Si no lo recibimos esperamos y cojemos un dado de N caras, donde hay el doble de caras que el anterior.
## Problema
Se puede saturar canal si hay muchas estaciones pues las retransmisiones "ensucian" el medio.
## Problema del nodo oculto
