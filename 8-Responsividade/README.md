# Responsividade

## O que é Responsividade?

Responsividade é a capacidade de um site se ajustar a diferentes tamanhos de tela e dispositivos. Existem quatro técnicas principais para criar layouts responsivos:

1. **CSS Framework**: Utilização de frameworks como Bootstrap ou Foundation.
2. **CSS Float Property**: Utilização da propriedade `float` para criar layouts flutuantes.
3. **CSS Flexbox**: Uso de flexbox para organizar e alinhar elementos de forma flexível.
4. **CSS Grid**: Criação de layouts em grade, permitindo um controle preciso da posição dos elementos.

### Exemplo de Layout Responsivo com Flexbox:
```css
.container {
    display: flex;
    flex-direction: column;
}

@media (min-width: 600px) {
    .container {
        flex-direction: row;
    }
}
```