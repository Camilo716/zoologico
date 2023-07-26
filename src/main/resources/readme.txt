Solución preguntas

- ¿Cuántas clases tiene el proyecto?
    R/ 3

- ¿En cuál clase se define el programa principal?
    R/ Zoologico

- ¿Cuántos objetos de la clase Animal se crean en la clase principal?
    R/ Explicitamente 2, pero al llamar el método tenerHijo() este crea internamente otro objeto Animal

- ¿Cuántos y cuáles son los atributos de la clase Animal?
    R/ 4:
      String nombre;
      String genero;
      double peso;
      Animal pareja;

- ¿Cuáles atributos de la clase Animal no son primitivos?
    R/ nombre, genero, pareja

- ¿Qué pasa si eliminamos la línea 17 de la clase Zoologico?
    R/ Nunca se le encontraría pareja a "papa", por lo que al invocar el método tenerHijo() no se tendría un hijo, y por
       ende generaría una exepción al intentar escribir el hijo en imprimirFamilia() ya que hijo sería null


- ¿Cuántos métodos tiene la clase Familia?
    R/ 3: El constructor familia, tenerHijo, e imprimirFamilia