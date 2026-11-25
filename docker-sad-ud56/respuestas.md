# Respuestas · Batería UD5 + UD6

> Esto es para ti: no se entrega ni cuenta. Pero si sabes contestar aquí, en la defensa de la Práctica 2 vas sobrado.

## UD5 · IDS/IPS y WAF

1. Un IDS detecta un ataque. ¿Lo para? ¿Por qué? ¿Qué tendrías que cambiar para que lo cortara?

>No ya que un ids lo detecta, al contrario que un ips que lo para.Para que lo cortara como he mencionado tendrias que configurar el ips.

2. En tu regla de la inyección SQL pusiste el destino `any` y no `$HOME_NET`. ¿Por qué? (pista: el DNAT del firewall).

>

3. El WAF está en `DetectionOnly` y llega `?id=1' OR '1'='1`. ¿Qué código recibe el atacante? ¿Dónde queda apuntado?

>

4. El WAF bloquea el comentario de una clienta. ¿Qué nombre tiene ese problema? ¿Cómo lo arreglaste **sin** abrir la puerta a toda la web?

>

## UD6 · Bastionado

5. ¿Por qué `PermitRootLogin no`, si root es el administrador? ¿Cómo entra entonces el administrador?

> Por que si el atacante prueba a entrar, o condigue acceder como root por cualquier casual se podria meter. Lo que se hace es permitir que se meta con la clave generada anteriormente.

6. Explica, con tus palabras y paso a paso, cómo Fail2ban deja fuera a una IP que prueba contraseñas.

>Deja fuera a la ip ya que hemos puesto un baneo si prueba mas de 3 veces, por ende si no lo acierta, la ip que intente acaba baneada por el tiempo qeu pongamos nosotros.

7. Lynis te daba 58 y ahora da 63. ¿Por qué no llega a 100? ¿Significa que el servidor sigue inseguro?

>Me daba 57 pero si, no llega a 100 ya que siempre hay algo que se pueda mejorar, al final eso es una nota orientativa para hacer un baremo de lo qeu hay en el servidor.
