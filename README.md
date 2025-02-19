Siguiendo la arquitectura propuesta en clase crear una endpoint que se llame jugadores/agregar.php  que reciba el siguiente json. 
{
  "Jugador": {
    "Id": 1,
    "Nombre": "pedro alfosno",
    "Apodos": "el peti",
    "Club": {
      "Nombre": "Club provincial de san luis",
      "Fundacion": "2 de agosto de 1970"      
    },
    "Edad": 18
  }
}
Y debe responder un JSON similar al siguiente:
{
 "IsOk":true,
 "Mensaje": "[Jugador menor de edad | Jugador mayor de edad]" 
}
El mensaje puede ser “Jugador menor de edad” o “Jugador mayor de edad” dependiendo de la edad.
Si edad <18 “Jugador menor de edad”
Si edad >=18 “Jugador mayor de edad”
