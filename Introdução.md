# 📚 Atividade – WAI-ARIA (Web Accessibility Initiative – Accessible Rich Internet Applications)

## Oque é **WAI-ARIA**?
WAI-ARIA é um conjunto de atributos que foram criados pelo grupo W3C, eles ajudam a tornar paginas web mais acessíveis para pessoas portadores de deficiencias, ou seja, são atributos que fornecem informação adicionais para tecnologias assistivas facilitando pessoas portadoras de deficiência compreenderem corretamente a função de cada elemento, tornando páginas web mais acessíveis.

---

## Exemplo:

```html
<button
    class="navbar-toggler"
    type="button"
    aria-controls="menuPrincipal"
    aria-expanded="false"
    aria-label="Abrir menu">
    Menu
</button>
```
---

## Qual é a função do atributo `aria-controls`?
Esse atributo serve para estabelecer uma relação entre dois elementos, indicando qual elemento será controlado.

## O que informa o atributo `aria-expanded`?
Informa se o elemento esta aberto ou fechado, sendo indicado por 'false' ou 'true'.

## Qual é a importância do atributo `aria-label` para usuários que utilizam leitores de tela?
É importante pois nos permite a dar nome a um elemento, tornando a leitura atraves de um leitor de tela ou ferramentas de acessibilidade mais clara e objetiva.
