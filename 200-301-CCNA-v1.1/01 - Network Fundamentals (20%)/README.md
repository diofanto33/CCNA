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

### Tolerancia a fallas 
Una red tolerante a fallas está diseñada para **limitar el impacto de fallos de hardware o software** y **recuperarse rápidamente** cuando ocurren.
#### Conceptos clave:
- **Redundancia:** existen enlaces o rutas alternativas entre el origen y el destino.
- **Enrutamiento automático:** si un enlace falla, el tráfico se redirige por otro camino de manera **transparente al usuario**.
- **Arquitectura robusta:** tanto la infraestructura física como los procesos lógicos se planifican para aprovechar la redundancia.
- **Objetivo:** garantizar que la red permanezca disponible y funcional, cumpliendo con los estándares de alta disponibilidad actuales

### **Escalabilidad en redes**
La **escalabilidad** se refiere a la capacidad de una red para **crecer o adaptarse** a un aumento de usuarios, dispositivos o tráfico, **sin afectar el rendimiento**.
#### Conceptos clave:
- **Crecimiento controlado:** la red debe poder expandirse agregando más dispositivos, enlaces o servicios.
    
- **Flexibilidad:** la infraestructura y los protocolos deben soportar cambios sin interrupciones importantes.
    
- **Ejemplos de implementación:**
    
    - Añadir **routers y switches** adicionales para segmentar tráfico.
        
    - Usar **VLANs** para dividir grandes redes en subredes manejables.
        
    - Protocolos de enrutamiento dinámico (**OSPF, EIGRP, BGP**) que adaptan rutas automáticamente.
        
- **Objetivo:** mantener **eficiencia, rendimiento y disponibilidad** incluso cuando la red crece.