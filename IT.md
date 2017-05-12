# TDMA
*Time division multiple access* - cada frame de time tiene diversos slots, uno para cada usuario.
# FDMA
*Frequency division multiple access* - cada usuario usa un rango de frecuencias distinto.
# CDMA
*Code division multiple access* - cada bits se multiplexa con código ortogonal distinto.

# CSMA/CA
## Exponential backoff
Tiempo aleatorio (dado con cierto número de caras) y uso el slot de tiempo N.
## Uso
Mandamos trama y esperamos ACK. Si no lo recibimos esperamos y cojemos un dado de N caras, donde hay el doble de caras que el anterior.
## Problema
Se puede saturar canal si hay muchas estaciones pues las retransmisiones "ensucian" el medio.
## Problema del nodo oculto
Router entre dos habitaciones, desde una habitación no se oye la transmisión de la otra. Se dan colisiónes.
### Solución
RTS/CTS: request/clear to send. [Ampliar]
## Problema del nodo expuesto
Uno no transmite porqué oye los paquetes de otra red (vecino),

# Zigbee - 802.15.4
## Definición
Redes que no constan con acceso a internet. Motivo: dispositivos con muy poca memoria -> no stack TCP/IP y tramas tienen mucho overhead en headers.
## 15.4E
Cambio de protocolo de acceso al medio -> tenemos varios canales que cambian con timeslots
