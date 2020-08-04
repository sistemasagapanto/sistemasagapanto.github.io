---
layout: default
title: "Facturación electrońica"
date: 2020-07-26 05:00:00 +0200
published: 2020-07-26 05:00:00 +0200
comments: true
categories: development
tags: [facturación, api, dian, electronica, facturacion-electronica]
github: "https://github.com/sistemasagapanto"
---

La facturación electrónica es un requisito para muchas empresas y deberia implementarce no solo por temas de transparencia en las organizaciones sino tambien porque representa un mecanismo electrónico de firmado que garantiza que los documentos no se modifiquen en el tiempo, o que si sufren alguna degradación por el medio en el que fue almacenado se logre identificar a través de la huella digital que se le asigna a estos documentos.

Nosotros hemos desarrollado una solución, basada en nuestra propia necesidad de facturar electrónicamente y la queremos compartir con todos, esta implementación esta pensada para poder integrar con otros sistemas atraves de una API

<!--more-->

## Modalidad

La DIAN plantea 3 modelos para la facturacion electrónica: 

- Software propio: La empresa cuenta con la infraestructura y el software para facturar electrónicamente, ademas cuenta con la firma electrónica aprbada por la ONAC
- Atraves de un proveedor tecnológico: La empresa contrata un proveeor tecnologico que normalmente cobra por el numero de facturas que emita la entidad.
- Software gratuito de la DIAN: Pensado para pequeñas empresas que emiten hasta 15 facturas mensuales.

Nosostros pensamos que la solución mas adecuada, para cualquier empresa que facture mas de 15 facturas mensuales es la de software propio, ya que no tendrá limitaciónes a la hora de facturar, ejemplo las empresas que emitan grandes cantidades de facturas a bajo precio entonces la factura no puede costar mas que el mismo pedido.

## Solución - Software propio

En Sistemas Agapanto SAS hemos automatizado todo el proceso de implementación de la factura electrónica, y tenemos la infraestructura para ponerla en un ambiente de producción por muy bajo costo, el servicio que nosostros le ofrecemos es un ambiente preconfigurado con todas las herramientas que se requieren para la implementación del software propio con las siguientes caracteristicas:

    - Procesador 4x
    - 10GB de almacenamiento
    - 8GB memoria RAM
    - Sistema Operativo Linux Alpine
    - Software de facturación preinstalado y configurado.
    - Capacitación y acompañamiento.
    - Ancho de banda 120 MB/S Fibra óptica
    
Todo esto por un costo de $<strike>300.000</strike> $150.000 COP mensuales, si su empresa requiere caracteristicas especiales de infraestructura escribanos al correo de contacto.
Ademas, si adquiere este servicio de infraestructura tendrá acceso a los demás módulos que hemos desarrollado para su empresa.
## Modulos administrativos

    - Activos Fijos  
    - Modulo Clientes
    - Modulo Contabilidad
    - Modulo Compras
    - Modulo Ventas
    - Modulo Inventarios
    
Para empezar dirijase a la url <a href="https://tiendas.agapanto.com.co">https://tiendas.agapanto.com.co</a> y registrese como usuario ingresando un correo valido que debera revisar por el enlace de verificación; una ves este completado el registro verá en el menú el enlace para registrar su empresa, puede registrar mas de una;  necesitará a la mano el rut y la identificación de la persona natural o juridica.

### Advertencia

Para firmar electrónicamente los documentos se requiere de la firma electrónica aprobada por la ONAC y tiene un costo de aproximadamente 300.000 COP anuales, dependiendo de la entidad en la que se adquiera, nosotros recomendamos entidades como https://web.certicamara.com/ o  https://andesscd.com.co/ y es un costo adicional que se debe tener en cuenta para facturar electrónicamente
