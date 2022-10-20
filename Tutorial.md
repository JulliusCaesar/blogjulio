Testando os códigos do MarkDown


# Isso é um título
Se eu iniciar a linha com um # ela virá um título  
Se eu não colocar nada, fica normal (ou seja, um texto simples)

# Quebra de linhas

Temos 3 formas de quebrar linha:
- Deixando uma linha em branco
- Usando o \<br\>
- Deixar dois espaços no final da linha (Não é recomendado)

PS: Linhas em branco mudam o contexto. Quando não queremos o contexto, usamos o \<br\>

# Blocos de citação/Comentário

Posso fazer um bloco de citação/comentário iniciando a linha por >

> Isso é um exemplo

# Sub-Títulos
Eu posso colocar mais de uma hashtag no inicio da linha.<br>
A cada # a mais que eu coloco ela vai virando um sub-titulo<br>
Se eu colocar ## -> Subtitulo (h2)<br>
Se eu colocar ### -> Subsubtitulo (h3)

# Imagens

Para imagens eu faço o seguinte:

\![descrição da imagem](link da imagem)

EX:
![Logo da ByLearn](https://i.imgur.com/NWsIvL4.png)

# Negrito e Italico

Podemos colocar em negrito através do duplo asterisco \*\***Dessa forma**\*\*

Podemos também fazer com o italico usando o underline \__Dessa Forma_\_

Posso também combinar ambos: \*\***Por exemplo, \__dessa forma_\_ aqui!**\*\*

**Exemplo Negrito**

_Exemplo Itálico_

**Exemplos _ambos_**

Podemos fazer listas colocando um traço na terceira linha (-)

Podemos dar um TAB no inicio da linha, antes do traço, para colcoar sub itens

Dessa forma:
- \- Item
  - \- Sub Item
- \- Item

Exemplo:
- Doces
  - Bala
  - Pirulito
  - Chiclete
- Frutas
  - Maça
  - Banana
  - Uva

# Códigos de programação

Nós criamos uma linha com 3 crases e o nome da linguagem de programação na frente: <br>
\`\`\` python

Em seguida, colocamos todo nosso código.

Por fim, criamos outra linha com apenas 3 crases: <br>
\`\`\`

Dessa forma:

\`\`\` python<br>
 ~ Meu codigo aqui ~<br>
\`\`\`<br>

Como exemplo:

``` python
numero1 = 10
numero2 = 20

soma = numero1 + numero2
print(soma)

```

# Quebra de seção (Linha Horizontal)

Podemos inserir uma linha horizontal criando uma nova linha e colocando apenas 3 traços (simbolo de menos)

Dessa forma:
\-\-\-

Exemplo:
---

---

---

# Links

Podemos criar links da seguinte forma:

\[Texto do Link](meu link)

Exemplo:

[Link do Google](https://www.google.com.br)

# Tecla de Escape

Podemos usar a tecla de escape (\\) para "Ignorar o poder" de um caractere.

Exemplo, o underline faz virar itálico, então \__Teste_\_ fica em itálico.

Porém, se eu digitar \\\_Teste\\\_ ele não fica, pois a \\ 'ignorou o poder' do underline.

Dessa forma:

\\\_sem underline\\\_

Exemplo:

\_Sem Underline\_


## Pull request para aprender

https://github.com/topics/hacktoberfest

https://www.codetriage.com/

http://issuehub.io/

http://www.pullrequestroulette.com/

https://gauger.io/contrib/

https://fixme.ossn.club/
