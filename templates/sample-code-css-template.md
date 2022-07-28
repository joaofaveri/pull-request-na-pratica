<!-- Cabeçalho da Linguagem do Código -->
<!-- Alterar o Título abaixo de acordo com o conteúdo:
        - Propriedades CSS
        - Seletores CSS
        - Pseudo-Classes CSS
        - Pseudo-Elementos CSS
        - Regras at (@rules) CSS
        - Tipos de Dados CSS -->
# <img src="./../images/css.svg" width="40"> Propriedades CSS

<!-- Tabela Síntese -->
<!-- O Nível pode ser uma das seguintes opções:
        - Iniciante
        - Intermediário
        - Avançado -->
<!-- NÃO EDITAR O CABEÇALHO -->
| Código CSS | Tópicos | Nível | Lançamento | Atualização |
| :--------: | :-----: | :---: | :--------: | :---------: |
| ``align-self`` | #alinhamento #itens-flex #flex | Iniciante | 2022-07-28 | - |

<!-- Título do conteúdo que será incluído no repositório -->
## align-self

<!-- Incluir um resumo -->
A propriedade CSS ``align-self`` alinha ``itens-flex`` da linha flex alvo, sobreescrevendo o valor ``align-items``. Se alguma dos eixos das margens do dado item está estabelecido como auto, então ``align-self`` é ignorado.

<!-- Citar os Valores ou outra informação relavante -->
<!-- utilize uma lista não numerada -->
### Valores

- auto
- normal
- self-start
- self-end
- flex-start
- flex-end
- center
- baseline
- stretch
- safe
- unsafe

<!-- Exemplo de Sintaxe -->
```css
/* Alinhamento de posicionamento */
/* align-self não recebe valores left e right */
align-self: center; /* Coloca o item em torno do centro */
align-self: start; /* Coloca o item no início */
align-self: end; /* Coloca o item no fim */
align-self: self-start; /* Alinha o item flush no início */
align-self: self-end; /* Alinha o item flush no fim */
align-self: flex-start; /* Coloca o item flex no início */
align-self: flex-end; /* Coloca o item flex no fim */
```
