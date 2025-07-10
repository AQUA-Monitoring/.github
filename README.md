# The Infinity Gauntlet

## 📌 Padrões de Commit

Os commits devem ser escritos **em inglês** no seguinte formato:  
`<tipo>: <mensagem do commit> #número-da-issue`

**Exemplo:**  
`feat: create sidebar component #01`

Siga a especificação [Conventional Commits](https://www.conventionalcommits.org/) para garantir consistência e compatibilidade com ferramentas de automação.

---

### Tipos de Commit

- **`feat`**  
  Adiciona uma **nova funcionalidade** ao código.  
  _(Relacionado ao **MINOR** do versionamento semântico)._

- **`fix`**  
  Corrige um **bug**.  
  _(Relacionado ao **PATCH** do versionamento semântico)._

- **`docs`**  
  Mudanças apenas na **documentação** (ex: README).  
  _(Sem alterações no código de produção)._

- **`test`**  
  Adiciona ou modifica **testes unitários**.  
  _(Sem alterações no código de produção)._

- **`build`**  
  Mudanças relacionadas ao **sistema de build ou dependências**.

- **`perf`**  
  Alterações de código que **melhoram a performance**.

- **`style`**  
  Mudanças de **formatação** (espaços, ponto e vírgula, etc).  
  _(Sem alterações funcionais)._

- **`refactor`**  
  **Refatoração** de código que não corrige bug nem adiciona funcionalidade.

- **`chore`**  
  **Tarefas de manutenção** (ex: atualizar .gitignore, ajustes em ferramentas).

- **`ci`**  
  Mudanças na **configuração de integração contínua**.

- **`raw`**  
  Mudanças em **configurações, dados, features ou parâmetros**.

- **`cleanup`**  
  Remoção de **código comentado ou desnecessário**.

- **`remove`**  
  Exclusão de **arquivos, diretórios ou funcionalidades obsoletas**.

---

## 🧾 Utilização de Issues

### Título da Issue

O título deve seguir o padrão do commit final gerado pela conclusão da Issue.

Os titulos devem ser escritos **em inglês** no seguinte formato:  
`<Classificação>:<título da Issue>`

**Exemplo:** FEAT: Create sidebar component

**Resumo:** Apresente brevemente o objetivo daquela tarefa.

---

### **Descrição**

Descreva o que precisa ser feito ou corrigido, em detalhes de maneira clara.

- A descrição deve ser feita em **inglês**.

---

#### Informações Adicionais

- **Assignees** (_responsável pela realização da Issue_)
- **Label** (_legenda relacionada ao responsável da Issue_): `FRONTEND` |
  `SVG` |
  `BACKEND` |
  `DESIGN` |
  `DOCS` |

- **Priority** (_prioridade para a realização da Issue_):
  `HIGH` | `MEDIUM` |`LOW`

- **Status** (_Fase de desenvolvimento da Issue_):
  `Backlog` | `Ready` |`In progress` | `Done`

---

## 🚀 Utilização de Pull Requests

### Título do Pull Request

O título deve seguir o padrão do commit principal realizado durante a implementação.

Os títulos devem ser escritos **em inglês** no seguinte formato:  
`<Classificação>:<descrição do Pull Request>`

**Resumo:** Apresente uma descrição breve sobre o propósito e impacto do Pull Request.

---

### Descrição

Detalhe as alterações realizadas de forma clara e objetiva:

- **Funcionalidades implementadas**
- **Bugs corrigidos**
- **Melhorias de código**
- **Refatorações**

> A descrição deve ser feita em **inglês**.

---

#### Informações Adicionais

- **Reviewers:** (\_pessoas responsáveis pela revisão das alterações realizas)
- **Assignees:** (_pessoas responsáveis pelas alterações realizadas_)
- **Label:** (_categoria relacionada às mudanças realizadas_):
  - `FRONTEND`
  - `SVG`
  - `BACKEND`
  - `DESIGN`
  - `DOCS`

---

## Prática

1. Selecione a aba `Pull requests`em seu repositório:

![Minha Imagem](<./src/PR(1).png>)

1. Após isso, selecione a branch de onde você deseja realizar o pull para a branch que você realizará o push:

- No exemplo estamos realizando o pull da branch `add-badges-to-readme` para a branch `main`.
- Ou seja, comparando os arquivos de `add-badges-to-readme` com os da `main`.

![Minha Imagem](<./src/PR(2).png>)

3.  Depois disso, adicione as propriedades desejada em seu Pull Request

- Neste exemplo, foi adicionado propriedade aos campos `Reviwers`, `Assignees`, `Labels` e `Projects`.

![Minha Imagem](<./src/PR(3).png>)

4. Após a aprovação dos usuários predefinidos como `Reviwers`, confirme o `merge` das branchs e o `Pull request estará concluído`.

![Minha Imagem](<./src/PR(4).png>)
