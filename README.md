# Desafio DIO - Diagrama de Classes Poo - Uml
desafio de codigo proposto no bootcamp dio innovation

## Diagrama de Classse - Iphone

```mermaid


classDiagram
  interface Iphone {
    + Conta de Usuarios
    + Musica
    + Telefone
    + Internet
  }

  class Conta_de_Usuarios {
    - email: String
    - numero: String
    - operadora: String
    - identificador: String
  }

  class Musica {
    + Reproduzir()
    + Tocar()
    + Pausar()
  }

  class Telefone {
    + Ligar()
    + Atender()
    + IniciarCorreioVoz()
  }

  class Internet {
    + Pagina()
    + AdicionarNovaAba()
    + AtualizarPagina()
  }

  Iphone --|> Conta_de_Usuarios
  Iphone --|> Musica
  Iphone --|> Telefone
  Iphone --|> Internet

classDiagram


```
