> Antes de começar, lembre-se: **Não faça commit na branch master**

# Desafio CSS
Este conteúdo tem por objetivo auxiliar no aprendizado de CSS e SASS aplicando suas regras em projeto simulado. Serão vários desafios com temáticas específicas, focando em pequenos assuntos para melhor o aprendizado.
Vamos treinar um pouco as técnicas do CSS, focando em uma abordagem dividida em três passos:

* Um protótipo será apresentado
* O HTML estará escrito e não deve ser alterado
* O CSS estará vazio, e ele deve ser escrito para fazer o HTML se comportar corretamente

# Como enviar seu resultado?
* Clone este repositório
* Crie uma branch com seu nome, todo em minusculo: `git checkout -b nome-sobrenome`
* Após finalizado, basta realizar o commit e o push.
* Me envie uma mensagem avisando do seu commit para que eu possa validar seu resultado.

# Desafio 2
Neste desafio, vamos aprender mais sobre as pseudo-classes.
Este é um assunto um pouco mais abrangente, por isso, dividiremos em alguns desafios.

## Desafio Pseudo-classes - Parte 1
Uma **pseudo-classe** CSS é uma palavra-chave adicionada a seletores que especifica um estado especial do elemento selecionado. Por exemplo, `:hover` pode ser usado para alterar a cor de um botão quando o usuário passar o cursor sobre ele.

Vamos abordar em um primeiro momento os pseudo classes comuns para links, botões: `:hover`, `:focus`, `:link`, `:active`, `:active`:

### Hover
Usamos a pseudo-classe `:hover` para modificar um elemento quando o mouse está parado sobre ele.

```css
nav > a {
   color: blue;
}

nav > a:hover {
    color: red;
}
```

### Focus
Usamos a pseudo-classe `:focus` para modificar um elemento quando o foco do navegador está sobre o elemento.

```css
nav > a {
   color: blue;
}

nav > a:focus {
    border: 1px solid red;
}
```

### Active
Usamos a peseudo-classe `:active` para modificar um elemento quando estamos com o mouse posicionado sobre ele e com o botão esquerdo pressionado.

```css
nav > a {
   color: blue;
}

nav > a:focus {
   font-weight: bold;
}
```

### Link
Usamos a pseudo-classe `:link` para identificar os elementos `<a>` que possuem URL associada.
```html
<nav>
  <a href="">Link</a>
  <a href="#1">Link 2</a>
</nav>
```

```css
a:link {
  color: yellow;
}
```

No exemplo acima, apenas o segundo <a> receberá a cor amarela pois ele possui um valor atribuido ao atributo `href`.


