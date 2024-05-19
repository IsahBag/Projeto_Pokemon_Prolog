# Projeto Final de Prolog

*Projeto de final de semestre da matéria de Programação em Lógica da Fatec, utilizando Prolog.*

## 💻 Tecnologias utilizadas:

* [SWI-Prolog](https://www.swi-prolog.org/)
* [Chat GPT](https://chatgpt.com/)

## 💡 Sobre o projeto:

Quis fazer um programinha que retornasse dentre dois pokémons escolhidos, qual venceria. Também criei uma listagem para mostrar todos os pokémons que derrotariam, seriam derrotados e empatariam com um pokémon escolhido.

Para o início do projeto, pesquisei no chat GPT a tabela com todos os pokémons de Kanto e seus dados, e também quais as vantagens e desvantagens que cada tipo possui sobre os demais.

Feita a pesquisa, criei uma base de dados com todos os pokémons, incluindo seu tipo primário, tipo secundário, ataque, defesa e HP. Para incluir essas informações, escrevi a seguinte cláusula para cada pokemon, sendo que cada uma dessas cláusulas corresponde ao um 'fato' segundo a lógica do prolog:
```
pokemon(nome_pokemon, tipo_1, tipo_2, ataque, defesa, HP).
```

Em seguida, criei uma outra base para definir todos os tipos de pokémons existentes, além de indicar sobre quais os tipos possui vantagens e desvantagens. Para isso, foram criados os seguintes formatos de cláusulas (fatos):
```
tipo(nome_tipo, [tipos_vantagens], [tipos_desvantagens]).
```

Depois de incluir todos os dados necessários, foi necessário desenvolver todas as regras para chegar ao resultado desejado.

Por fim, coloquei como as consultas ao sistemas devem ser feitas para o retorno correto do resultado.

🎆 [Clique aqui](/program/projeto_final.pl) para acessar o programinha pronto!