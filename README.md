# Questionário para estágio de desenvolvedor web (PHP/JavaScript)

Para responder a este questionário, crie um fork do repositório e responda às perguntas no arquivo README.md. Em seguida, envie o link do seu fork para análise.

## Questionário

<br>- Explique o que é um framework web e qual a sua importância.</br>
<details>
  <summary><strong>:heavy_check_mark: Resposta</strong></summary>
  <br/>
  
É um conjunto de bibliotecas, é um esqueleto genérico para resolver uma necessidade “x” de desenvolvimento de software, baseado na linguagem especifica, ele é importante pois diminui o tempo de desenvolvimento, além de padronizar os projetos.
  
  </details>
  
<br>- Quais são os principais frameworks web PHP?.</br>
<details>
  <summary><strong>:heavy_check_mark: Resposta </strong></summary>
  <br />
  
-  Laravel
-  Symfony
-  Cake PHP
-   CodeIgniter
-  Zend
  
  </details>
  
<br>- Quais são os principais frameworks web JavaScript?</br>
<details>
  <summary><strong>:heavy_check_mark: Resposta</strong></summary>
  <br />
  
-  React
-  Angular
-  Vue

  </details>

<br>- Explique o que é um banco de dados relacional e quais são os seus componentes.</br>
<details>
  <summary><strong>:heavy_check_mark: Resposta</strong></summary>
  <br />
  É um banco baseado no relacionamento das tabelas, onde cada linha representa um ID e as colunas seus atributos. Ele é composto por:

-  Tabelas
-  Coluna
-  Registros
-  Relacionamento
-  Chave Primária
-  Chave Estrangeira
  </details>
  
<br>- Quais são os principais tipos de dados em SQL?</br>
<details>
  <summary><strong>:heavy_check_mark: Resposta</strong></summary>
  <br />
  Alguns deles são: 

  -  int
-  float
-  char
-  string
-  datetime
-  text
-  bit
  </details>
  
<br>- Crie uma função em PHP que receba um nome e uma idade como parâmetros e retorne uma mensagem de boas-vindas.</br>
<details>
 <summary><strong>:heavy_check_mark: Resposta</strong></summary>
  <br />
  
```php
<?php
function mensagemBoasVindas($nome, $idade) {
    if ($idade < 0) {
        return "Idade inválida.";
    } else {
        return "Olá, $nome! Parabéns pelos seus $idade anos, seja bem-vindo(a)";
    }
}
?>
```


  </details>
  
<br>- Crie uma função em JavaScript que receba um número como parâmetro e retorne o seu fatorial.</br>
<details>
  <summary><strong>:heavy_check_mark: Resposta</strong></summary>
  <br />
  
```java
function fatorial(numero) {
    if (numero === 0 || numero === 1) {
        return 1; 
    } 
   
else {
        return numero * fatorial(numero - 1);
    }
}
```

  </details>
  
<br>- Crie uma query em SQL que retorne todos os registros de uma tabela.</br>
<details>
  <summary><strong>:heavy_check_mark: Resposta</strong></summary>
  <br />
  
SELECT * FROM database.tabela;
  </details>
  
<br>- Explique o que é uma API e quais são os seus benefícios.</br>
<details>
<summary><strong>:heavy_check_mark: Resposta</strong></summary>
  <br />
  
É um conjunto de normas que possibilita a comunicação entre sistemas, com ela os sistemas conseguem trocar informações e se comunicar, integrando essas informações e permitindo a reutilização das suas funcionalidades por outras aplicações ou software, os benefícios são a segurança e aumento da eficiência dos sistemas.
  </details>
  
<br>- Descreva um projeto de desenvolvimento web que você já realizou.</br>
<details>
 <summary><strong>:heavy_check_mark: Resposta</strong></summary>
  <br />
Os meus projetos mais completos foram realizados durante a minha formação técnica. O que mais me destaco é o meu Trabalho de Conclusão de Curso (TCC), que consiste em um site de receitas com base nos ingredientes disponíveis. Utilizamos a linguagem C# e o MySQL , sendo minha responsabilidade a gestão de parte do banco de dados e todo o desenvolvimento da interface gráfica.
  </details>
  

## Entrega

Ao finalizar o desafio, envie o link do seu fork para nós. Avaliaremos a estrutura, clareza, boas práticas e funcionamento correto.
Boa sorte!
