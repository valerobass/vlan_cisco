Para que este laboratorio funcione correctamente tenemos que hacer una configuración a mano, no podemos automatizarla por un problema con la configuración interna del OS de Cisco en los switches relacionado con el modo trunk.

Esta es la topología del laboratorio.

![image](https://github.com/user-attachments/assets/2ba84048-0d60-49dc-aad4-c74b7ea0fc0c)

Lo que tenemos que hacer es entrar por ssh en Sw2 e introducir manualmente las vlan 10, vlan 20 y vlan 30.

![image](https://github.com/user-attachments/assets/7ebe0044-e693-45e6-a267-bbfaf16ce001)

Tras esta pequeña configuración el resto del laboratorio funciona correctamente. Los routers dentro de la misma vlan se ven y no ven a los demás y viceversa.

Ping r1 a sí mismo y al router de su misma vlan.

![image](https://github.com/user-attachments/assets/825c6dce-ee38-4ca7-9897-1bd68803698f)

Ping r2 a sí mismo. El resto serán con resultado negativo ya que no está conectado con ningún otro, está solo en su vlan.

![image](https://github.com/user-attachments/assets/d3a862bf-8c80-4572-a34f-22b0812228af)

Ping r3 a sí mismo y al router de su misma vlan.

![image](https://github.com/user-attachments/assets/729a12fc-48d8-4158-9d54-665a51e90e41)





