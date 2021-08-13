# Transformando Códigos em Python para Executáveis
## Objetivo
Os arquivos do jupyter que temos até aqui no curso são scripts que podemos usar para rodar códigos e fazer diversas tarefas.
Mas, algumas vezes, não seremos nós que iremos rodar os códigos e também não necessariamente o computador que vai executar o código não necessariamente tem python instalado.
Por isso, podemos transformar esses códigos em arquivos .exe (executáveis que funcionam em qualquer computador).

## Cuidados
Para códigos simples, basta fazermos a conversão de python para executável, mas em muitos códigos, temos que pensar se precisamos fazer alguma adaptação.

Ex: Se o nosso código abre algum arquivo do nosso computador, temos que tornar essa ação de abrir o arquivo algo que funcione em qualquer computador.

Sempre precisamos olhar o código e pensar: ele funcionaria em qualquer computador? Tem alguma coisa aqui nele que impede de funcionar no computador de outro pessoa? Se necessário, fazemos as adaptações. Vamos aprender como.

## Funcionamento
1) Seu código deve estar funcionando sem erros no jupyter
2) Transformar o código jupyter em scripts python padrão (extensão .py). Seu código deve estar funcionando nesse formato também: Jupyter > File > Download as > Python
3) Vá no terminal do anaconda, vá no diretório onde seu arquivo se encontra e digite 'python' + o nome da pasta que você baixou: python pasta
Dica: se o arquivo tem espaços coloque-o entre aspas duplas
4) Digite no terminal: pip install pyinstaller
5) Digite no terminal: pyinstaller -w nomedoprograma.py
6) Vá na pasta dist criada, compacte essa pasta e pode distribuir essa página

## Pré-requisitos 
- Jupyter Notebook (anaconda 3)
- Python
- Importar as bibliotecas 

## Sobre a Autora
Oi, eu sou a Fernanda! Estou aqui para contribuir com meu conhecimento e espero poder ajudar no desenvolvimento profissional de cada um de vocês.

[![Linkedin Badge](https://img.shields.io/badge/-Fernanda_Maki_Hirose-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/fernanda-maki-hirose-801117208/)](https://www.linkedin.com/in/fernanda-maki-hirose-801117208/)  [![Gmail Badge](https://img.shields.io/badge/-femahi2020@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:femahi2020@gmail.com)](mailto:femahi2020@gmail.com)
