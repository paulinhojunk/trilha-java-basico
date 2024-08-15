# Desafio Java - Basico - POO

Desafio realizado no dia 15 de agosto de 2024.


## Documentação

segue o projeto em UML criado no Mermaid.

    classDiagram
    
    iPhone --|> ReprodutorMusical
    iPhone --|> AparelhoTelefonico
    iPhone --|> NavegadorInternet 
    iPhone : + void tocar() 
    iPhone : + void pausar()
    iPhone : + void selecionarMusica()
    iPhone : + void ligar()
    iPhone : + void atender()
    iPhone : + void iniciarCorreioVoz()
    iPhone : + void exibirPagina()
    iPhone : + void adcionarNovaAba()
    iPhone : + void atualizarPagina()  
    
    class ReprodutorMusical {
      + void tocar()
      + void pausar()
      + void selecionarMusica(String musica)
    }
    class AparelhoTelefonico {
      + void ligar(String numero)
      + void atender()
      + void iniciarCorreioVoz()
    }
    class NavegadorInternet {
      + exibirPagina(String url)
      + adcionarNovaAba()
      + atualizarPagina()
    }