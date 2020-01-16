# Heroku-apollo-server-standalone-with-data

add mutation from html axios post >...• 

• Servidor apollo para alojar objetos json desacoplados del cliente en heroku y cargarlos desde afuera
((( = mecanismo de pulsación flush() para sse o socket io desde •

HTML sse load from the EventSource API interface o socket io client <...(((•

     server heroku          server y     
   |    apollo     |  | client html 1 | 
   |               |  |  	            | 

                           server z
		                  | client html 2 |
                      |	              |

    porque no usar socket io : no sería posible 
    tener el front y el back apollo en diferentes 
    servidores porque los namespaces se requieren
    definir en el mismo ambito (server) es decir
    para socket io la interfase html requeriría
    estar en el servidor que provee socket io


