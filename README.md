# soabpm
Clase Demo de GitHub

H2, Web, JPA, DevTools, Jersey(JAX-RS)


## Patrón
- Vista (Web)
- Servicio (SOA) => Utilizaremos las herramientas JAX-RS para mostrar los servicios REST. (REST = JSON)
    - @RestController => Trasforma la clase en Rest.
    - @RequestMapping("/NombreMetodo") 
- Reglas de Negocio(Business)
- DAO (JPA)
    - @Entity => Transforma la clase a tabla.
    - @ID => Para la PK.
    - @GeneratedValue => Para autoincrementar la ID.
- DB (H2)
