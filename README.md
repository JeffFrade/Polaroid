# Polaroid
---

Esse repositório contém uma pequena biblioteca de efeito Polaroid para imagens.

## Como Instalar
---

Basta copiar o arquivo `polaroid.css` para dentro da sua aplicação ou site, fazer a chamada dentro do `HTML` ou afins e utilizar.

### Como Utilizar
---

```HTML
<!-- Classe que monta os espaços necessários para o efeito Polaroid -->
<div class="polaroid-row">
    <!-- Monta o efeito Polaroid para a imagem -->
    <div class="polaroid">
        <img src="images/image-1.jpg" alt="Image 1" title="Image 1"/>
    </div>
    
    <!-- Monta o efeito Polaroid para a imagem e deixa a polaroid inclidada para a esquerda -->
    <div class="polaroid polaroid-left">
        <img src="images/image-2.jpg" alt="Image 2" title="Image 2"/>
    </div>
    
    <!-- Monta o efeito Polaroid para a imagem e deixa a polaroid inclidada para a direita -->
    <div class="polaroid polaroid-left">
        <img src="images/image-3.jpg" alt="Image 3" title="Image 3"/>
    </div>
    
    <!-- Monta o efeito Polaroid para a imagem e deixa a polaroid inclidada para a direita e adiciona um pequeno texto (Descrição) a foto -->
    <div class="polaroid polaroid-right">
        <img src="images/image-4.jpg" alt="Image 4" title="Image 4"/>
        <div class="polaroid-description">
            <h3>My Short Description</h3>
        </div>
    </div>
</div>
```
