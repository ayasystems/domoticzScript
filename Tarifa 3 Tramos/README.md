# Descrinación horaria 3 tramos

1. Necesitamos crear un selector switch llamado TarifaLuz:

   - Level 0 -> Valle
   - Level 10 -> Llano
   - Level 20 -> Punta

2. Ahora tenemos que crear 3 dummies virtuales de tipo Electric (Instant+Counter)

   - PPunta
   - PLlano
   - PValle



3. Solo nos queda crear dos nuevo eventos en DZEvents.
   - DHA_3T

     **Especial atención al device PZEM, cambiar según corresponda, debe ser el que mide el consumo de la casa**

   - TRAMOS_HORARIOS


Puedes acceder a más scripts y tutoriales en https://domotuto.com/
