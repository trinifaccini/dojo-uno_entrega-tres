# DOJO NUMERO UNO - GRUPO F

![Tinkercard](https://github.com/trinifaccini/dojo-uno/blob/main/img/DOJO_UNO-GRUPO_F-ENTREGA_TRES.png)

## Integrantes 
- Sol Rubinetti
- Yamila Sueldo
- Adrian Barrientos
- Lautaro Torres
- Trinidad Faccini

## Consigna
El gobierno de la ciudad quiere actualizar los semáforos que tiene instalados. La empresa  “UTNFRA Robotics” ganó la licitación y ahora les toca a los desarrolladores de la empresa generar  un proyecto low cost que cumpla con las especificaciones que el gobierno de la ciudad nos  impone, a saber las especificaciones son las siguientes. 

### Tercer entrega: 


## Descripción

Creamos un semáforo con señalización para no videntes. 

## Finalidad del proyecto
Demostrar los conocimientos aprendidos en la materia Sistema de Procesamiento de Datos.

## Función principal

Esta función se encarga de hacer sonar al buzzer la cantidad de veces recibida por parametro, por un tiempo y con una intensidad que tambien
son recibidos por parametro. 

~~~ C++ 
// ESTA FUNCION VA A DURAR LO QUE duren las funciones: 
// sonarBuzzer() + silenciarBuzzer() * veces
void sonarSilenciarBuzzer(int buzzer, int tiempo, int intensidad, int veces)
{
  int contador = 0;
  
  while (contador < veces)
  {
    sonarBuzzer(buzzer, tiempo, intensidad);
    silenciarBuzzer(buzzer, tiempo);
    contador = contador + 1;
  }
}
~~~

## :robot: Link al proyecto
- [Tinkercard-Sol Rubinetti]()
- [Tinkercard-Yamila Sueldo]()
- [Tinkercard-Adrian Barrientos]()
- [Tinkercard-Lautaro Torres]()
- [Tinkercard-Trinidad Faccini](https://www.tinkercad.com/things/4z3mhxVozQW-dojo-uno-grupo-f-entrega-dos/editel?sharecode=w1-w-rqWAS2D5xQI_Y1ASwRkBqFLPSaJrfb6A1xqPrc)
