# Custom JavaFX Project

Repositório padrão de projeto JavaFX para facilitar as configurações de uso da biblioteca gráfica JavaFX

## Dependências

1. <a href="https://www.oracle.com/br/java/technologies/javase-downloads.html">Java JDK </a> (JDK 8+) instalada em sua máquina, de preferência a JDK 16.
2. <a href="https://gluonhq.com/products/scene-builder/">Scene Builder</a> para criação das interfaces FXML.
3. Biblioteca gráfica <a href="https://gluonhq.com/products/javafx/">JavaFX</a>

{
  "title": "Configurações Auxiliares"
}
[/block]
1. Clonar o repositório ``` git clone https://github.com/jhollyferr/custom-javafx.git```
2. Baixar a biblioteca <a href="https://gluonhq.com/products/javafx/">JavaFX</a>
3. Abrir o projeto no seu Visual Studio Code
4. Adicionar todas as referências da JDK JavaFX 
   ```Java Projects > Referenced Libraries > + > javafx > lib```

   Após isto você terá a seguinte estrutura em seu projeto
[block:image]
{
  "images": [
    {
      "image": [
        "https://files.readme.io/0783040-Capturar.PNG",
        "Capturar.PNG",
        435,
        284,
        "#24222b"
      ]
    }
  ]
}
[/block]
4. Editar a path ``` C:/javafx/lib ``` para sua path local em ``` "vmArgs"```, ```.vscode > launch.json ``
[block:api-header]
{
  "title": "Executando o Projeto"
}
[/block]
Após todas as configurações da seção anterior, exectue o projeto em:

``` App > Run ```

Após executar, você terá o seguinte resultado:
[block:image]
{
  "images": [
    {
      "image": [
        "https://files.readme.io/ae23994-Capturar.PNG",
        "Capturar.PNG",
        436,
        368,
        "#d3d3d5"
      ]
    }
  ]
}
[/block]
Agora é só você desenvolver seu projeto no Visual Studio Code seguindo a seguinyr estrutura de pacotes
[block:image]
{
  "images": [
    {
      "image": [
        "https://files.readme.io/05fdeba-Capturar.PNG",
        "Capturar.PNG",
        212,
        144,
        "#201e28"
      ]
    }
  ]
}
[/block]
<br>
&copy; By Jhollyfer Rodrigues