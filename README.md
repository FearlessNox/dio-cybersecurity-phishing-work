# dio-cybersecurity-phishing-work
Curso de Cybersecurity. Trabalho com foco em entender como é feita a coleta de dados e clonagem de site, com métodos do setools no kali linux

Comandos utilizados: 

Acessar o root: sudo su

Acessar o toolkit: `setoolkit`

Opção 1:  `Social-Engenineering Attacks`

Opção 2:  `Website Attack Vectors`

Opção 3:  `Credential Garvester Attack Method`

Opção 2:  `Site Cloner`

**Digitar o IP para host**

**Digitar o site que será clonada a interface, site utilizado:** `http://www.facebook.com/`

## Problemas

Ao utilizar os comandos acima, caso tenha tido o retorno de um erro, o mesmo se dá por ocorrer por conta da versão do navegador. Para isto, podemos alterar da ultima opção, `Site Cloner`, para:

`Web Templates` -> Templates pré-prontos de sites conhecidos, como google e antigo twitter

`Custom import` -> Faz a importação de um arquivo HTML, deverá especificar o caminho do diretório, e o arquivo deverá ter o nome de index.html, exemplo: "/home/kali/Pshishing/index.html"

## Resultado

Saída esperada do terminal: 

![image](https://github.com/user-attachments/assets/55189d8f-e9ee-471a-9c57-86a3d7e2d97e)

Após encerrar o phishing, ele gera um arquivo xml com o relatório dos dados coletados
