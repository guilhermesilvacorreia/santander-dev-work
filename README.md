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
Usuario "-- Conta
Usuario "-- Feature
Usuario "-- Cartao
Usuario "-- Novidade

```
 
  