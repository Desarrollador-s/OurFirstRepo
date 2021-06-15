# Ejercicio Código postal
Para que podáis ir toqueteando y viendo cómo funciona git. 

Vamos a hacer el ejercicio de recuperación del código postal.

El código postal
El sistema de código postal español está formado por una serie de códigos cuya finalidad es la de mejorar el funcionamiento del servicio postal. Los códigos postales fueron intro- ducidos en España en 1981, coincidiendo con la puesta en marcha de los procesos de auto- matización de clasificación de la correspondencia.
En la actualidad en España hay 11 752 códigos postales.
Los códigos postales españoles constan de cinco cifras, de las que las dos primeras hacen referencia a cada provincia, seguidas de las ciudades de Ceuta y Melilla.
En esta tabla puedes ver el código de dos cifras que le corresponde a cada provincia:

01. Álava
02. Albacete
03. Alicante
04. Almería
05. Ávila
06. Badajoz
07. Islas Baleares 08. Barcelona 09. Burgos
10. Cáceres
11. Cádiz
Qué se pide
12. Castellón 13. Ciudad Real 14. Córdoba
15. La Coruña 16. Cuenca
17. Gerona
18. Granada
19. Guadalajara 20. Guipúzcoa 21. Huelva
22. Huesca
23. Jaén 24. León 25. Lérida 26. La Rioja 27. Lugo 28. Madrid 29. Málaga 30. Murcia 31. Navarra 32. Orense 33. Asturias
34. Palencia
35. Las Palmas
36. Pontevedra
37. Salamanca
38. Santa Cruz de Tenerife
39. Cantabria 40. Segovia 41. Sevilla 42. Soria
43. Tarragona
44. Teruel 45. Toledo 46. Valencia 47. Valladolid 48. Vizcaya 49. Zamora 50. Zaragoza 51. Ceuta
52. Melilla


Se propone realizar un programa que valide los códigos postales de las provincias españo- las, para realizar la comprobación la herramienta deberá leer los dos primeros números del código postal introducido.
La herramienta deberá:
 Contener un formulario con dos campos input (en los que el usuario introduzca pro- vincia y código postal) y dos botones, uno para validar y otro para borrar datos.
 Verificar que el código postal se corresponde con la provincia adecuada, una vez que se validen los datos introducidos.
 Implementar un sistema de alertas que advierta mediante un mensaje que se han in- troducido datos erróneos (por ejemplo; el nombre erróneo que no corresponde a ninguna provincia, números en lugar de letras o si el campo está vacío) y que solicite
que se vuelvan a insertar los datos.
 Indicar con un mensaje en pantalla (no con una alerta) el resultado de la búsqueda.
El mensaje será de color rojo en el caso de que la validación sea errónea y de color verde cuando sea correcta.
 Validar que en el campo "código postal" realmente se han introducido cinco números, que no hay letras y que no está vacío.
El programa ha de cumplir los siguientes requisitos:
 Incluir los campos para introducir la dirección (calle, número, código postal, provincia).
 Validar las distintas entradas mediante alertas (calle, número, código postal y la pro- vincia).
 Mostrar mensajes de confirmación mediante el DOM.
