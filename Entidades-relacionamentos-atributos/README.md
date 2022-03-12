# <img align="center" alt="Ana-Modelagem" height="40" src="https://github.com/AnaProgramando/modelagem-de-dados/blob/dece58aefaadbb4ef6863de565b986604a5f287e/database.png"> Modelagem de banco de dados relacional: Entidades, relacionamentos e atributos

----

<img src="https://img.shields.io/static/v1?label=Status&message=complete&color=32CD32&style=for-the-badge"/>

<p align="center"> O curso desse projeto está disponível na Plataforma da <a href="https://www.alura.com.br/" > Alura </a> </p>

<p align="center">
 <a href="https://github.com/AnaProgramando/modelagem-de-dados" > Home do Projeto </a> |
 <a href="#-welcome">Welcome</a> |
 <a href="#-features">Features</a> | 
 <a href="#%EF%B8%8F-brmodelo">brModelo</a> | 
 <a href="#-fa%C3%A7a-voc%C3%AA-mesma-o">Faça você mesma (o)</a> | 
 <a href="#%EF%B8%8F-diagramas-prontos">Diagramas prontos</a> | 
 <a href="#-d%C3%BAvidas">Dúvidas</a> | 
 <a href="#%EF%B8%8F-contatos">Contatos</a> | 
 <a href="#%EF%B8%8F-autora">Autora</a>
</p>

# 🤗 Welcome

Olá, seja muito bem vinda(o)! 

Tive a ideia de compartilhar alguns projetos para quem tem interesse em aprender sobre Modelagem de Dados, por isso os exercícios começam bem simples e vão dificultando aos poucos para quem gostaria de iniciar na programação ou precisa melhorar as suas habilidades, e também coloquei alguns comentários para facilitar o entendimento.

Nesse projeto abordo o estudo da Modelagem de dados, o processo de criação de um modelo de dados para que o dado de software seja gravado em um banco de dados. Partindo da criação de diagramas de entidade relacionamento, banco de dados, operações da álgebra relacional, mapeamento relacional, normalização, e linguagem SQL, usada para manipular os dados de um banco de dados.

📚 Aproveite o material

👩‍💻 Refaça do seu jeito

😉 Se tiver qualquer dúvida, me contate

## ✅ Features

### Modelagem de banco de dados relacional - Entidades, relacionamentos e atributos

- [X] Construção de diagrama de entidade e relacionamentos;
- [X] Modelagem do diagrama de entidade e relacionamentos;
- [X] Compreensão de relacionamento, relacionamento de identificação, atributos, atributos chaves, atributos multivalorados, atributos compostos e atributos derivados;
- [X] Representação da cardinalidade dos relacionamentos entre as entidades;
- [X] Criação de modelo prático.

## ⬇️ brModelo

1. Baixe e instale o <a href="https://www.java.com/pt-BR/download/" > Java </a>
2. Baixe e instale o <a href="https://www.sis4.com/brModelo/download.html" > brModelo.jar </a>
3. Crie uma pasta e cole dentro dela o arquivo baixado do brModelo
4. Clique duas vezes no brModelo
5. Selecione o Java(TM) Platform SE binary para executar o brModelo
6. Pronto! Agora você já pode usar o brModelo

## 📝 Faça você mesma (o)

#### Diagrama_Livraria_v001
1. No menu superior do brModelo clique em Diagrama
2. Clique na opção Nova Entidade e adicione a sua tela para iniciar a criação do modelo
3. Nas propriedades à esquerda, mude o valor de Nome para PEDIDO
4. Crie mais quatro entidades e mude os seus valores de Nome para LIVRO, CLIENTE, EDITORA e ESTOQUE
5. No menu superior, clique em Arquivo e depois em Salvar Como
6. Salve em um diretório, como Diagrama_Livraria_v001

#### Diagrama_Livraria_v002
1. Crie mais uma entidade
2. Deixe o Nome em branco
3. Arraste o retângulo para que este fique em volta da entidade PEDIDO 
_
![image](https://user-images.githubusercontent.com/31097110/158001567-02e19758-eb43-4e0b-b20c-90e7264632ea.png)
4. Repita esse processo com LIVRO e ESTOQUE
5. Salve como Diagrama_Livraria_v002

#### Diagrama_Livraria_v003
1. No menu à direita, chamado Artefatos, clique no ícone de relacionamento (uma linha ligando em dois pontos, localizado acima do ícone de lata de tinta)_
![image](https://user-images.githubusercontent.com/31097110/158001636-a59678b2-b164-40ba-b696-42526381518a.png)
2. Com a tecla Ctrl pressionada, clique nas entidades CLIENTE e PEDIDO
3. Nas propriedades à esquerda, mude o valor Nome para FAZ
4. Agora, repita o processo e crie relacionamentos entre:
   -   LIVRO e EDITORA (chamado PERTENCE)
   -   ESTOQUE e LIVRO (chamado EXISTE)
   -   PEDIDO e LIVRO (chamado CONTÉM)
5. Salve como Diagrama_Livraria_v003

#### Diagrama_Livraria_v004
1. Clique na pequena bolinha ao lado da ponta do relacionamento com a entidade 
![image](https://user-images.githubusercontent.com/31097110/158001475-b7e8411e-5015-45a0-be3b-f6dcfcd3f796.png)
2. Arraste a bolinha para acima da entidade para posicionar as ligações da melhor forma visual possível
3. Repita o procedimento com as outras entidades
4. Clique sobre a cardinalidade de CLIENTE e mude o valor de Cardinalidade para (1,1)
5. Clique sobre a cardinalidade de PEDIDO, no relacionamento com CLIENTE, e mude o valor de Cardinalidade para (1,N)
6. Clique sobre a cardinalidade de LIVRO, no relacionamento com EDITORA, e mude o valor de Cardinalidade para (1,N)
7. Clique sobre a cardinalidade de EDITORA e mude o valor de Cardinalidade para (1,1)
8. Clique sobre a cardinalidade de ESTOQUE e mude o valor de Cardinalidade para (0,n)
9. Clique sobre a cardinalidade de LIVRO, no relacionamento com ESTOQUE, e mude o valor de Cardinalidade para (1,1)
10. Apague o relacionamento Contém
11. No menu à direita, chamado Artefatos, clique no botão com ícone de losango dentro de um retângulo, para criar uma entidade associativa_
![image](https://user-images.githubusercontent.com/31097110/158001724-bf67538a-ece4-41f7-9687-a11ef47920c5.png)
12. Nas propriedades à esquerda, em Diagrama, mude o valor Nome para ITEM_PEDIDO
13. Em em Relacionamento, mude o valor de Nome para CONTÉM
14. Ligue PEDIDO com CONTÉM e CONTÉM com LIVRO
15. Clique sobre a cardinalidade de PEDIDO, no relacionamento com LIVRO, e mude o valor de Cardinalidade para (1,N)
16. Clique sobre a cardinalidade de LIVRO, no relacionamento com PEDIDO, e mude o valor de Cardinalidade para (1,N)
17. Salve como Diagrama_Livraria_v004


## ✔️ Diagramas prontos

Faça o donwload dos diagramas prontos: 

- <a href="https://github.com/AnaProgramando/modelagem-de-dados/blob/511bd290ed8d4c7667f37799d8787f4cf985bb6f/Entidades-relacionamentos-atributos/Diagrama_Livraria_v001.brM3" > Diagrama_Livraria_v001 </a>
- <a href="https://github.com/AnaProgramando/modelagem-de-dados/blob/511bd290ed8d4c7667f37799d8787f4cf985bb6f/Entidades-relacionamentos-atributos/Diagrama_Livraria_v002.brM3" > Diagrama_Livraria_v002 </a>
- <a href="https://github.com/AnaProgramando/modelagem-de-dados/blob/511bd290ed8d4c7667f37799d8787f4cf985bb6f/Entidades-relacionamentos-atributos/Diagrama_Livraria_v003.brM3" > Diagrama_Livraria_v003.1 </a>
- <a href="https://github.com/AnaProgramando/modelagem-de-dados/blob/511bd290ed8d4c7667f37799d8787f4cf985bb6f/Entidades-relacionamentos-atributos/Diagrama_Livraria_v003a.brM3" > Diagrama_Livraria_v003.2 </a>
- <a href="https://github.com/AnaProgramando/modelagem-de-dados/blob/511bd290ed8d4c7667f37799d8787f4cf985bb6f/Entidades-relacionamentos-atributos/Diagrama_Livraria_v004.brM3" > Diagrama_Livraria_v004.1 </a>
- <a href="https://github.com/AnaProgramando/modelagem-de-dados/blob/511bd290ed8d4c7667f37799d8787f4cf985bb6f/Entidades-relacionamentos-atributos/Diagrama_Livraria_v004a.brM3" > Diagrama_Livraria_v004.2 </a>
- <a href="https://github.com/AnaProgramando/modelagem-de-dados/blob/511bd290ed8d4c7667f37799d8787f4cf985bb6f/Entidades-relacionamentos-atributos/Diagrama_Livraria_v005.brM3" > Diagrama_Livraria_v005 </a>
- <a href="https://github.com/AnaProgramando/modelagem-de-dados/blob/511bd290ed8d4c7667f37799d8787f4cf985bb6f/Entidades-relacionamentos-atributos/Diagrama_Livraria_v006.brM3" > Diagrama_Livraria_v006 </a>
- <a href="https://github.com/AnaProgramando/modelagem-de-dados/blob/511bd290ed8d4c7667f37799d8787f4cf985bb6f/Entidades-relacionamentos-atributos/Diagrama_Livraria_v007.brM3" > Diagrama_Livraria_v007 </a>
- <a href="https://github.com/AnaProgramando/modelagem-de-dados/blob/511bd290ed8d4c7667f37799d8787f4cf985bb6f/Entidades-relacionamentos-atributos/Diagrama_Livraria_v008.brM3" > Diagrama_Livraria_v008 </a>


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
