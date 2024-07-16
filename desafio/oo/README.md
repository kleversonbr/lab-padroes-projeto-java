# Desafio POO - Trilha Java Básico


Desafio para realização de Modelagem e Diagramação da representação UML do componente iPhone, abrangendo suas funcionalidades como Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.

## 💻 Objetivo

- Criar um diagrama UML que represente as funcionalidades descritas acima.
- Implementar as classes e interfaces correspondentes em Java (Opcional).

## ✨ Como foi feito ?

- Utilização da ferramenta Web [MERMAID](https://mermaid.js.org/intro/) para modelagem e diagramação.
- Utilizado vídeo de Lançamento iPhone 2007, disponível no [YouTube](https://www.youtube.com/watch?v=9ou608QQRq8) - Minutos relevantes: 00:15 até 00:55

## 📚 Diagrama UML

[![](https://mermaid.ink/img/pako:eNqFksFuwjAMhl8lyqnT4AUqhIS2yw5DaEw79WIS01pL48pN0Abj3ZfSgkAdWi9p7D_O5z8-aMMWda6Ng7Z9JigF6sKr9NGqYo9q9jOdqjdshG0MLK-xJQNuLFk0IOgqfkeHW_ZkeKxZwg5LsCwvPqB4DDeSXD2ug5AvlY81Ct9J1ieCO8koCa3PnToak6tDn1ZqNqMOYwsG5_NzcBrYgGQPl30Dsb0JtKlBQ-xhqJj1QHlPMOiO1wxjay4M9ygclenS3ofbyikJAb3FayZKRQnkiUWQ-IP32V8cI_v_xcAv2pCsoCQPWfJ2jGKp92LJO1hsILumjOBoD-fjZyI90amrGsimsTsRFDpUWGOh8_RrQT4LXfhOB-nd1t_e6DxIxIkWjmWl8y24Nu1iY5MTw8xeomipe-xhqrvl-AsJrPB0?type=png)](https://mermaid.live/edit#pako:eNqFksFuwjAMhl8lyqnT4AUqhIS2yw5DaEw79WIS01pL48pN0Abj3ZfSgkAdWi9p7D_O5z8-aMMWda6Ng7Z9JigF6sKr9NGqYo9q9jOdqjdshG0MLK-xJQNuLFk0IOgqfkeHW_ZkeKxZwg5LsCwvPqB4DDeSXD2ug5AvlY81Ct9J1ieCO8koCa3PnToak6tDn1ZqNqMOYwsG5_NzcBrYgGQPl30Dsb0JtKlBQ-xhqJj1QHlPMOiO1wxjay4M9ygclenS3ofbyikJAb3FayZKRQnkiUWQ-IP32V8cI_v_xcAv2pCsoCQPWfJ2jGKp92LJO1hsILumjOBoD-fjZyI90amrGsimsTsRFDpUWGOh8_RrQT4LXfhOB-nd1t_e6DxIxIkWjmWl8y24Nu1iY5MTw8xeomipe-xhqrvl-AsJrPB0)

## 🛠️ Implementação das classes 

```
interface ReprodutorMusical {
    void tocar();
    void pausar();
    void selecionarMusica(String musica);
}

interface AparelhoTelefonico {
    void ligar(String numero);
    void atender();
    void iniciarCorreioVoz();
}

interface NavegadorInternet {
    void exibirPagina(String url);
    void adicionarNovaAba();
    void atualizarPagina();
}

class iPhone implements ReprodutorMusical, AparelhoTelefonico, NavegadorInternet {
    // Implementação dos métodos de ReprodutorMusical
    public void tocar() { /* Código para tocar música */ }
    public void pausar() { /* Código para pausar música */ }
    public void selecionarMusica(String musica) { /* Código para selecionar música */ }

    // Implementação dos métodos de AparelhoTelefonico
    public void ligar(String numero) { /* Código para ligar */ }
    public void atender() { /* Código para atender */ }
    public void iniciarCorreioVoz() { /* Código para iniciar correio de voz */ }

    // Implementação dos métodos de NavegadorInternet
    public void exibirPagina(String url) { /* Código para exibir página */ }
    public void adicionarNovaAba() { /* Código para adicionar nova aba */ }
    public void atualizarPagina() { /* Código para atualizar página */ }
}
```

## 👨‍💻 Aluno

KLEVERSON BRANDALIZE
