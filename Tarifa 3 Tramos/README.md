# Discriminación horaria 3 tramos  🚀

1. Necesitamos crear un **selector switch** llamado TarifaLuz:

   - Level 0 -> Valle
   - Level 10 -> Llano
   - Level 20 -> Punta


![Web](https://github.com/ayasystems/domoticzScript/blob/master/Tarifa%203%20Tramos/tarifaLuz.png)


2. Creamos 3 **dummies virtuales** de tipo **Electric (Instant+Counter) computo de energía desde dispositivo**

   - PPunta
   - PLlano
   - PValle

2. Creamos 4 **dummies virtuales** de tipo **Counter incremental**, los editamos y ponemos **type: counter y value units: cent€**

   - CPunta
   - CLlano
   - CValle
   - CTotal

4. Solo nos queda crear dos nuevo eventos en DZEvents.
   - DHA_3T

     **Especial atención al device PZEM, cambiar según corresponda, debe ser el que mide el consumo de la casa**

   - TRAMOS_HORARIOS
      **Este script necesita tener funcionando y actualizado el script de precios de PVPC https://github.com/ayasystems/domoticzScript/blob/master/PrecioPVPC.txt **

Puedes acceder a más scripts y tutoriales en https://domotuto.com/


## Expresiones de Gratitud 🎁
* Dale una estrella al proyecto
* Comenta a otros sobre este proyecto 📢
* Invita una cerveza 🍺 o un café ☕ a alguien del equipo. 
* Da las gracias públicamente 🤓.
