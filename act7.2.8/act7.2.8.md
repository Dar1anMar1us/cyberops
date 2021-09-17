# Packet Tracer: Verifique el direccionamiento IPv4 e IPv6

La técnica dual-stack permite que IPv4 e IPv6 coexistan en la misma red. En esta actividad, investigará una implementación de doble pila ,incluida la documentación de la configuración IPv4 e IPv6 para dispositivos finales, probar la conectividad para IPv4 e IPv6 mediante ping y trazar la ruta de acceso de extremo a extremo para IPv4e IPv6. Complete la documentación de la tabla de direcciones.

- PC1 <ul>
        <li>IPv4: ``10.10.1.100``</li>
        <li>IPv6: ``2001:DB8:1:1::A``</li>
        <li>Mask: ``225.225.225.224``</li>
        <li>Mask: ``10.10.1.97``</li>
    </ul>

![text](./pc1.PNG)

- PC2 <ul>
        <li>IPv4: ``10.10.1.20``</li>
        <li>IPv6: ``2001:DB8:1:4::A``</li>
        <li>Mask: ``225.225.225.240``</li>
        <li>Mask: ``10.10.1.17``</li>
    </ul>

![text](./pc2.PNG)

Vemos que podemos hacer ping entre ellos. Tanto por IPv4 como por IPv6.

![text](./ping.PNG)


Si hacemos un `tracert` podemos ver por donde pasa hasta llegar al destino:

![text](./tracert.PNG)

Vemos que pasan por el switch directo de cada PC y despues por sus routers en la dirreción a la que van.

Es decir en el caso de PC2 pasa por su default gateway que es el switch 10.10.1.17 y despues por dos routers con las IP ``10.10.1.9`` y ``10.10.1.6`` y despues por el default gateway de PC1.