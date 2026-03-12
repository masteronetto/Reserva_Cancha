# Reserva_Cancha
# Metodos_get_post

## Get http://localhost:8081/canchas
## Get by id http://localhost:8081/canchas/1 http://localhost:8081/canchas/2
## Post http://localhost:8081/canchas 
{

  "nombre": "Cancha B",

  "tipo": "Fútbol",

  "precioPorHora": 15000

}

{

    "nombre":"Cancha A",

    "tipo":"Tenis",

    "precioPorHora" : 20000

}
## Get http://localhost:8082/reservas
## Get by id http://localhost:8082/reservas/1 http://localhost:8082/reservas/2
## Post http://localhost:8082/reservas
{

    "canchaId" : 1,

    "nombreCliente" : "Ana García",

    "fecha" : "2025-06-20",

    "horaInicio" : "10:00",

    "horaFin" : "11:00"

}

{

    "canchaId" : 2,

    "nombreCliente" : "Carlos lópez",

    "fecha" : "2025-06-21",

    "horaInicio" : "14:00",

    "horaFin" : "15:00"

}
