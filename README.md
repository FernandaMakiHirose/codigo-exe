# Transformando Códigos em Python para Executáveis
## Objetivo
Os arquivos do jupyter que temos até aqui no curso são scripts que podemos usar para rodar códigos e fazer diversas tarefas.
Mas, algumas vezes, não seremos nós que iremos rodar os códigos e também não necessariamente o computador que vai executar o código não necessariamente tem python instalado.
Por isso, podemos transformar esses códigos em arquivos .exe (executáveis que funcionam em qualquer computador).

## Requisitos 
- Jupyter Notebook (anaconda 3)
- Python
- Importar as bibliotecas 

## Licença
Distribuido sob a licença MIT License. Veja `LICENSE` para mais informações.

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
