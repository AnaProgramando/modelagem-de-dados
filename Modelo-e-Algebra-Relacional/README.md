# <img align="center" alt="Ana-Modelagem" height="40" src="https://github.com/AnaProgramando/modelagem-de-dados/blob/dece58aefaadbb4ef6863de565b986604a5f287e/database.png"> Modelagem de banco de dados relacional: Modelo e Álgebra Relacional

<img src="https://img.shields.io/static/v1?label=Status&message=complete&color=32CD32&style=for-the-badge"/>

<p align="center"> O curso desse projeto está disponível na Plataforma da <a href="https://www.alura.com.br/" > Alura </a> </p>

<p align="center">
 <a href="https://github.com/AnaProgramando/modelagem-de-dados" > Home do Projeto </a> |
 <a href="#-welcome">Welcome</a> |
 <a href="#-features">Features</a> | 
 <a href="#-fa%C3%A7a-voc%C3%AA-mesma-o">Faça você mesma (o)</a> | 
 <a href="#-d%C3%BAvidas">Dúvidas</a> | 
 <a href="#%EF%B8%8F-contatos">Contatos</a> | 
 <a href="#%EF%B8%8F-autora">Autora</a>
</p>

# 🤗 Welcome

Olá, seja muito bem vinda(o)! 

Tive a ideia de compartilhar alguns projetos para quem tem interesse em aprender sobre Modelagem de Dados, por isso os exercícios começam bem simples e vão dificultando aos poucos para quem gostaria de iniciar na programação ou precisa melhorar as suas habilidades, e também coloquei alguns comentários para facilitar o entendimento.

📚 Aproveite o material

👩‍💻 Refaça do seu jeito

😉 Se tiver qualquer dúvida, me contate

## ✅ Features

- [X] Compreensão do modelo relacional, entendendo os domínios, atributos, relações, tuplas e chaves
- [X] Realização das operações de Álgebra Relacional: Seleção, Projeção, União e Diferença
- [X] Uso de Junção, Divisão e Produto cartesiano
- [X] Instalação de software Relational
- [X] Aplicação das operações de Álgebra Relacional utilizando o software Relational
- [X] Execução dos desafios propostos

## ⬇️ Instalação do Relational

1. Baixe o <a href="https://ltworf.github.io/relational/index.html" > Relational </a> </p>
2. Execute o SetupRelational.exe para realizar a instalação do Relational
3. Pronto! Agora já pode usar.

## ✏️ Criando as relações

### Criando a Relação: teste

1. Crie uma nova relação no Relational clicando no botão New
2. Através dos botões Add Tuple (linha) e Add Column (coluna), inclua os dados da relação (inclusive o nome dos atributos), da tabela abaixo:

Nome_Projeto | Numero_Projeto | Local_Projeto | Numero_Departamento
------------ | ------------- | ------------- | -------------
Produto X | 1 | Santo André | 5
Produto Y | 2 | Itu | 5
Produto Z| 3 | São Paulo | 5
Informatização | 10 | Mauá | 4
Reorganização | 20 | São Paulo | 1
Novos Benefícios	 | 30 | Mauá | 4

3. Clique em OK
4. Inclua o nome da relação, que será "teste"
5. Clique em OK

### Criando a Relação: departamento

1. Crie uma nova relação
2. Inclua os dados da relação da tabela abaixo:

Nome_Departamento | Numero_Departamento | Cpf_Gerente | Data_Inicio_Gerente
------------ | ------------- | ------------- | -------------
Pesquisa | 5 | 33344555587 | 22-05-1988
Administraçăo | 4 | 98765432168 | 01-01-1995
Matriz | 1 | 88866555576 | 19-06-1981

3. Clique em OK
4. Inclua o nome da relação, que será "departamento"
5. Clique em OK

### Criando a Relação: dependente


1. Crie uma nova relação
2. Inclua os dados da relação da tabela abaixo:

Cpf_Funcionario	| Nome_Dependente | Sexo | Data_Nascimento | Parentesco
------------ | ------------- | ------------- | ------------- | -------------
33344555587	| Alicia	| F	| 05-04-1986 | Filha
33344555587	| Tiago	    | M	| 25-10-1983 | Filho
33344555587	| Janaína	| F	| 03-05-1958 | Esposa
98765432168	| Antonio	| M	| 28-02-1942 | Marido
12345678966	| Michael	| M	| 04-01-1988 | Filho
12345678966	| Alicia	| F	| 30-12-1988 | Filha
12345678966	| Elizabeth	| F	| 05-05-1967 | Esposa

3. Clique em OK
4. Inclua o nome da relação, que será "dependente"
5. Clique em OK


### Criando a Relação: funcionario


1. Crie uma nova relação
2. Inclua os dados da relação da tabela abaixo:

Primeiro_Nome	| Nome_Meio	| Ultimo_Nome	| Cpf	| Data_Nascimento	| Endereco	| Sexo	| Salario	| Cpf_Supervisor	| Numero_Departamento
------------ | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | -------------
Joăo	| B	| Silva	    | 12345678966 | 09-01-1965 | Rua das Flores 751 Săo Paulo SP	| M | 30000 | 33344555587	| 5
Fernando| T	| Wong	    | 33344555587 | 08-12-1955 | Rua da Lapa 34 Săo Paulo SP	    | M | 40000 | 88866555576	| 5
Alice	| J	| Zelaya	| 99988777767 | 19-01-1968 | Rua Souza Lima 35 Curitiba PR	    | F | 25000 | 98765432168	| 4
Jeniffer| S	| Souza	    | 98765432168 | 20-06-1941 | Av Arthur de Lima 54 Santo André	| F | 43000 | 88866555576	| 4
Ronaldo	| K	| Lima	    | 66688444476 | 15-09-1962 | Rua Rebouças 65 Piracicaba SP	    | M | 38000 | 33344555587	| 5
Joice	| A	| Leite	    | 45345345376 | 31-07-1972 | Av. Lucas Obes 74 Săo Paulo SP	    | F | 25000 | 33344555587	| 5
André	| V	| Pereira	| 98798798733 | 29-03-1969 | Rua Timbira 35 Săo Paulo SP	    | M | 25000 | 98765432168	| 4
Jorge	| E	| Brito	    | 88866555576 | 10-11-1937 | Rua do Horto 35 Sáo Paulo SP	    | M | 55000 | 	            | 1

3. Clique em OK
4. Inclua o nome da relação, que será "funcionario"
5. Clique em OK


### Criando a Relação: localizacoes_departameto


1. Crie uma nova relação
2. Inclua os dados da relação da tabela abaixo:

Cpf_Funcionario	 | 	Nome_Departamento	 | 	Sexo	 | 	Data_Nascimento	 | 	Parentesco
------------ | 	------------ | 	------------ | 	------------ | 	------------
33344555587	 | 	Alicia	 | 	F	 | 	05-04-1986	 | 	Filha
33344555587	 | 	Tiago	 | 	M	 | 	25-10-1983	 | 	Filho
33344555587	 | 	Janaína	 | 	F	 | 	03-05-1958	 | 	Esposa
98765432168	 | 	Antonio	 | 	M	 | 	28-02-1942	 | 	Marido
12345678966	 | 	Michael	 | 	M	 | 	04-01-1988	 | 	Filho
12345678966	 | 	Alicia	 | 	F	 | 	30-12-1988	 | 	Filha
12345678966	 | 	Elizabeth	 | 	F	 | 	05-05-1967	 | 	Esposa

3. Clique em OK
4. Inclua o nome da relação, que será "localizacoes_departameto"
5. Clique em OK


### Criando a Relação: projeto


1. Crie uma nova relação
2. Inclua os dados da relação da tabela abaixo:

Nome_Projeto	 | 	Numero_Projeto	 | 	Local_Projeto	 | 	Numero_Departamento
------------ | 		------------ | 		------------ | 		------------ | 
Reorganizaçăo	 | 	20	 | 	Săo Paulo	 | 	1
Produto Y	 | 	2	 | 	Itu	 | 	5
Novos Benefícios	 | 	30	 | 	Mauá	 | 	4
Produto X	 | 	1	 | 	Santo André	 | 	4
Informatizaçăo	 | 	10	 | 	Mauá	 | 	4
Produto Z	 | 	3	 | 	Săo Paulo	 | 	5

3. Clique em OK
4. Inclua o nome da relação, que será "projeto"
5. Clique em OK


### Criando a Relação: trabalha_em


1. Crie uma nova relação
2. Inclua os dados da relação da tabela abaixo:

Cpf_Funcionario	 | 	Numero_Projeto	 | 	Horas
------------	 | 	------------	 | 	------------
12345678966	 | 	1	 | 	32.5
12345678966	 | 	2	 | 	7.5
66688444476	 | 	3	 | 	40
45345345376	 | 	1	 | 	20
45345345376	 | 	2	 | 	20
33344555587	 | 	2	 | 	10
33344555587	 | 	3	 | 	10
33344555587	 | 	10	 | 	10
33344555587	 | 	20	 | 	10
99988777767	 | 	30	 | 	30
99988777767	 | 	10	 | 	10
98798798733	 | 	10	 | 	35
98798798733	 | 	30	 | 	5
98765432168	 | 	30	 | 	5
98765432168	 | 	20	 | 	20
88866555576	 | 	20	 | 	

3. Clique em OK
4. Inclua o nome da relação, que será "trabalha_em"
5. Clique em OK



## ❓ Dúvidas

Qualquer dúvida, interaja aqui:
  * Faça perguntas
  * Dê sugestões de melhoria para o projeto
  * Compartilhe suas ideias
  * E interaja sobre o assunto

😉Lembre-se de que esta é uma comunidade que construímos juntos 💪.

## ✉️ Contatos

Se precisar de ajuda, entre em contato comigo 😉

[<img align="left" alt="Gmail" width="80px" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>](mailto:anabe.valentim@gmail.com)
[<img align="left" alt="LinkedIn" width="100px" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>](https://www.linkedin.com/in/ana-beatriz-valentim)
[<img align="left" alt="Beacons" width="80px" src="https://github.com/AnaProgramando/AnaProgramando/blob/31ac40741768033915a37ec0f949984bf6aad2d1/beacons_logo.png"/>](https://beacons.page/anaprogramando)
<br>


## 🙋‍♀️ Autora

<div>
  <img align="left" alt="Ana Valentim" width="100px" src="https://avatars.githubusercontent.com/u/31097110?v=4"/>
</div>

<br>
✏️ Feito com ❤️ e Dados 🎲 por <a href="https://github.com/AnaProgramando">Ana Valentim</a>.

💙 Se você gostou desse projeto, dê uma ⭐ e compartilhe!


<br><br>
[⬆ Voltar ao top](https://github.com/AnaProgramando/CSharp_Entrada-Saida-com-streams/blob/main/README.md#) <br>


 <div>
  <img align="center" alt="Pixel-Art" width="1000px" src="https://github.com/AnaProgramando/modelagem-de-dados/blob/32b70227df02e525f6b22fb62aaaa253df865053/y.gif"/>
</div>
