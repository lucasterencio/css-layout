# Projeto de Layout com Flexbox e CSS Grid

Este projeto, proposto pelo professor <a href="https://www.linkedin.com/in/augusto-cesar-oliveira-7ab3081ba/" target="_blank">Augusto César</a>  da Universidade de Pernambuco (UPE), demonstra a criação de layouts utilizando **Flexbox** e **CSS Grid**. O objetivo é comparar as abordagens de layout para entender suas características e as melhores práticas para diferentes tipos de design responsivo.

- Link do projeto: https://lucasterencio.github.io/css-layout/

## Características do Layout com **Flexbox**

- **Distribuição Flexível**: Flexbox é utilizado para distribuir o espaço entre os itens de um container de forma flexível.
- **Layout Linear**: Ou seja, o flexbox trabalha com linhas ou colunas.
- **Alinhamento e Distribuição**: Flexbox permite o controle fácil de alinhamento com propriedades como `justify-content`, `align-items`, e `align-self`.
- **Responsividade**: Flexbox é ótimo para criar layouts fluidos que se ajustam automaticamente a diferentes tamanhos de tela.

### Exemplo de uso:
- **header**: Utiliza Flexbox para alinhar o `span` e o `nav` em linha.
- **main**: Flexbox distribui os itens no layout, permitindo que eles se ajustem conforme o espaço disponível.

---

## Características do Layout com **CSS Grid**

- **Layout Bidimensional**: CSS Grid permite o controle completo sobre linhas e colunas, oferecendo um layout mais estruturado e preciso.
- **Maior Precisão no Posicionamento**: Utilizando propriedades como `grid-template-columns`, `grid-template-rows`, `grid-column`, e `grid-row`, você tem controle total sobre onde os itens devem ser posicionados.
- **Ideal para Layouts Complexos**: O Grid é perfeito para criar layouts mais complexos, como grades com várias colunas e linhas. No grid, é possível ter uma flexbilidade maior ao colocar itens onde deseja, ocupando quantas linhas ou colunas forem necessárias.
- **Responsividade**: O Grid permite uma personalização maior do layout em diferentes tamanhos de tela, podendo modificar colunas, linhas e áreas dinamicamente.

### Exemplo de uso:
- **main**: O layout é estruturado com Grid, dividindo a tela em colunas e linhas definidas.
- **section-1** e **aside**: Posicionamento específico de elementos em áreas do grid para criar uma distribuição precisa do conteúdo.

---

## Diferenças Entre **Flexbox** e **CSS Grid**

| Característica               | **Flexbox**                      | **CSS Grid**                     |
|------------------------------|-----------------------------------|-----------------------------------|
| **Tipo de Layout**            | Unidimensional (linha ou coluna)  | Bidimensional (linhas e colunas)  |
| **Complexidade**              | Simples, ideal para layouts básicos| Mais complexo, ideal para layouts estruturados |
| **Controle de Itens**         | Bom para distribuição simples     | Excelente para posicionamento preciso em múltiplas linhas/colunas |
| **Uso Combinado**             | Pode ser combinado com Grid para detalhes internos de layout | Flexbox pode ser usado dentro de um Grid para controle flexível de itens |

---



