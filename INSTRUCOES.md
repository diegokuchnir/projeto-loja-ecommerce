# Instruções para Completar o Projeto

## 📋 Passo a Passo

### 1. **Adicionar Imagens dos Produtos**

As imagens devem ser salvas na pasta `img/` com os nomes:
- `produto1.jpg` - The Legend of Zelda
- `produto2.jpg` - Elden Ring
- `produto3.jpg` - Cyberpunk 2077
- `produto4.jpg` - Hollow Knight
- `produto5.jpg` - Hades
- `produto6.jpg` - Stardew Valley

**Dica:** Se não tiver as imagens, você pode:
- Fazer download do Google Images
- Redimensionar para aproximadamente 300x250px
- Salvar na pasta `img/` com os nomes acima

### 2. **Substituir Imagens de Placeholder**

No arquivo `css/style.css`, se você tiver imagens locais, altere:

```css
/* De: */
#img-1 {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

/* Para: */
#img-1 {
    background-image: url("../img/produto1.jpg");
    background-size: cover;
    background-position: center;
}
```

### 3. **Personalizar os Produtos**

Edite o `index.html` para:
- Mudar nomes dos produtos
- Alterar preços
- Adicionar descrições personalizadas

### 4. **Mudar as Cores**

No `css/style.css`, encontre a paleta de cores:

```css
/* Cores principais */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
color: #667eea;
```

Você pode usar cores diferentes como:
- `#FF6B6B` (Vermelho)
- `#4ECDC4` (Turquesa)
- `#FFE66D` (Amarelo)
- `#95E1D3` (Verde água)

### 5. **Alterar Header e Footer**

**No `index.html`:**

```html
<h1>🎮 Loja Gamer</h1>
<p>Os melhores jogos para você!</p>
```

**No Footer:**

```html
<p>Email: contato@lojasgamer.com</p>
<p>Telefone: (11) 9999-9999</p>
```

## 🎨 Estrutura de Pastas Final

```
projeto-loja-ecommerce/
├── index.html
├── css/
│   └── style.css
├── img/
│   ├── produto1.jpg
│   ├── produto2.jpg
│   ├── produto3.jpg
│   ├── produto4.jpg
│   ├── produto5.jpg
│   └── produto6.jpg
└── README.md
```

## 📝 Alterações Importantes

### HTML - Como Adicionar um Novo Produto

```html
<div class="product">
    <div class="product-image" id="img-7"></div>
    <h3>Nome do Novo Produto</h3>
    <p class="description">Descrição</p>
    <span class="price">R$ 99,90</span>
    <a href="#" class="btn">Comprar</a>
</div>
```

### CSS - Como Estilizar Novos IDs

```css
#img-7 {
    background: linear-gradient(135deg, #newColor1 0%, #newColor2 100%);
}
```

## ✨ Recursos Avançados (Opcional)

- Adicionar mais produtos
- Incluir seção de "Produtos em Destaque"
- Criar página de detalhes do produto
- Adicionar carrinho de compras (com JavaScript)
- Implementar barra de busca

## 🚀 Como Fazer Download como ZIP

1. Acesse: https://github.com/diegokuchnir/projeto-loja-ecommerce
2. Clique em **Code** (botão verde)
3. Selecione **Download ZIP**
4. Descompacte na sua máquina

## 📞 Dúvidas Comuns

**P: Qual tamanho de imagem devo usar?**
R: Recomendado 300x250px ou 400x300px. Não precisa ser exato, o CSS vai ajustar.

**P: Posso usar ícones em vez de imagens?**
R: Sim! Você pode usar Font Awesome ou outro ícone library.

**P: Como mudar o número de colunas?**
R: Altere no CSS: `grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));`

---

**Pronto para começar! 🎉**
