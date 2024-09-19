# desafio-poo
# Utilizando o Mermaid Editor para criar a Diagrama UML.
Codificação no Editor
classDiagram
    class IReprodutorMusical {
        +tocar()
        +pausar()
        +selecionarMusica(String musica)
    }

    class IAparelhoTelefonico {
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
    }

    class INavegadorInternet {
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina()
    }

    class iPhone {
        +tocar()
        +pausar()
        +selecionarMusica(String musica)
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina()
    }

    iPhone --|> IReprodutorMusical
    iPhone --|> IAparelhoTelefonico
    iPhone --|> INavegadorInternet

# Diagrama UML    

![alt text](<Untitled diagram-2024-09-19-190211.png>)