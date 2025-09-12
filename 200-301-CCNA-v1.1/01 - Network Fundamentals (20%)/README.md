#### Reflexiones sobre las comunicaciones en red. 

En las conexiones con cables, el medio puede ser cobre, que transmite señales eléctricas,
o fibra óptica, que transmite señales de luz. En las conexiones inalámbricas, el medio es la atmósfera de la tierra o espacio y las señales son microondas. En un viaje típico a través de Internet, un mensaje puede viajar en una variedad de medios.

Las personas generalmente buscan enviar y recibir distintos tipos de mensajes a través de aplicaciones informáticas; estas aplicaciones necesitan servicios para funcionar en la red. Algunos de estos servicios incluyen World Wide Web, e‐mail, mensajería instantánea y telefonía IP. Los dispositivos interconectados a través de medios para proporcionar servicios deben estar gobernados por reglas o protocolos. En el cuadro se enumeran algunos servicios y un protocolo vinculado en forma más directa con ese servicio.
Los protocolos son las reglas que utilizan los dispositivos de red para comunicarse entre sí. Actualmente el estándar de la industria en redes es un conjunto de protocolos denominado TCP/IP (Protocolo de control de transmisión/Protocolo de Internet). TCP/IP se utiliza en redes comerciales y domésticas, siendo también el protocolo primario de Internet. Son los protocolos TCP/IP los que especifican los mecanismos de formateo, de direccionamiento y
de enrutamiento que garantizan que nuestros mensajes sean entregados a los destinatarios correctos.


| Servicio             | Protocolo o Regla                                                                                                             |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| World Wide Web (www) | HTTP                                                                                           (Hypertext Transport Protocol) |
| E-mail               | SMTP (Simple Mail Transport Protocol)                                         POP (Post Office Protocol)                      |
| Mensaje Instantaneo  | XMPP  OSCAR                                                                                                                   |
| Telefonia IP         | SIP (Session Initiation Protocol)                                                                                             |

#### Que es un Servicio? 
Los servicios de red son programas de computación que respaldan la red humana. Distribuidos en toda la red, estos servicios facilitan las herramientas de comunicación en línea como e‐mails, foros de discusión/boletines, salas de chat y mensajería instantánea. Por ejemplo: en el caso un servicio de mensajería instantánea proporcionado por dispositivos en la nube, debe ser accesible tanto para el emisor como para el receptor.

#### Que es una Regla? 
Aspectos importantes de las redes que **no son dispositivos ni medios**, son reglas o protocolos. Estas reglas son las normas o protocolos que especifican la manera en que se envían los mensajes, cómo se direccionan a través de la red y cómo se interpretan en los dispositivos de destino. Por ejemplo: en el caso de la mensajería instantánea Jabber, los
protocolos XMPP, TCP e IP son importantes conjuntos de reglas que permiten que se realice la comunicación.

--- 

 Debido a que Internet evoluciona, al igual que las redes en general, descubrimos que existen cuatro características básicas que la arquitectura subyacente necesita para cumplir con las expectativas de los usuarios: tolerancia a fallas, escalabilidad, calidad del servicio y seguridad.

#### Tolerancia a fallas 
La expectativa de que Internet está siempre disponible para millones de usuarios que confían en ella requiere de una arquitectura de red diseñada y creada con tolerancia a fallas. Una red tolerante a fallas es la que limita el impacto de una falla del software o hardware y puede recuperarse rápidamente cuando se produce dicha falla. Estas redes dependen de enlaces o rutas redundantes entre el origen y el destino del mensaje. Si un enlace o ruta falla, los procesos garantizan que los mensajes pueden enrutarse en forma instantánea en un enlace diferente transparente para los usuarios en cada extremo. Tanto las infraestructuras físicas como los procesos lógicos que direccionan los mensajes a través de la red están diseñados para adaptarse a esta redundancia. Ésta es la premisa básica de la arquitectura de redes actuales.

