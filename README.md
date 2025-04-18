# Projeto Bootcamp Santander

## Diagrama de Classes

``` mermaid
  

classDiagram
class Usuario {
+String name
}
class Conta {
+String number
+String agency
+float balance
+float limit
}
class Feature {
+String icon
+String description
}
class Cartao {
+String number
+float limit
}
class Novidade {
+String icon
+String description
}
Usuario "1" *-- "n" Conta
Usuario "1" *-- "N" Feature
Usuario "1" *-- "1" Cartao
Usuario "1" *-- "N" Novidade

```
 
  