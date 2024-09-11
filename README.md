# Estudo sobre CSS

**Flaxbox**
https://flexboxfroggy.com/

**Grid**
https://cssgridgarden.com/

**Taillwindcss**
https://tailwindcss.com/

**Position**
https://chenhuijing.com/blog/understanding-positioning-in-css/

**Figma**
https://www.figma.com

https://www.youtube.com/watch?v=n4R2E7O-Ngo

**Less**
https://lesscss.org/


**Sobre Media Query**



1. O que é CSS?
CSS (Cascading Style Sheets) é uma linguagem usada para descrever a apresentação de documentos HTML. Ele define como os elementos devem ser exibidos em tela, papel, ou em outros meios.

2. Estrutura Básica
Você pode incluir CSS de três formas principais:
* Inline CSS: Dentro de uma tag HTML.
```css
<p style="color: blue;">Texto azul</p>
```
* Internal CSS: Dentro de uma tag <style> no <head> do seu documento HTML.
```css
<style>
  p {
    color: red;
    background-color: red;
  }
</style>
```

* External CSS: Em um arquivo separado com a extensão .css, referenciado no seu HTML.
**Para incluir a linha digite `link` e pressione *tab*.**
```css
<link rel="stylesheet" href="styles.css">
```

3. Seletores
Seletores são usados para selecionar elementos HTML que você deseja estilizar. Alguns exemplos:

* Seletores de tipo: Seleciona todos os elementos de um tipo específico.
```css
p {
  color: green;
}

```
* Seletores de classe: Seleciona elementos com uma classe específica.

```css
.minha-classe {
  font-size: 20px;
}
```

* Seletores de ID: Seleciona um elemento com um ID específico.
```css
#meu-id {
  background-color: black;
}
```


* Comment
>A sintaxe para incluir comentários em CSS é bastante simples: um comentário começa com /* e termina com */. >Qualquer texto que seja inserido entre essas duas sequências de caracteres será considerado um comentário e, portanto, não afetará a aparência da página.
```css
/* meu comentário */
```
