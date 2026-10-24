# Como contribuir
Este guia apresenta um fluxo simples para colaborar com o FinanCont usando Git e GitHub.

## 1. Crie uma branch
Atualize a branch `main` e crie uma branch para sua tarefa. Use o padrão `feature/nome-da-tarefa`, com palavras minúsculas separadas por hífen.

```bash
git checkout main
git pull origin main
git checkout -b feature/tela-de-login
```

## 2. Faça commits claros
Use uma mensagem curta que explique a mudança. Comece com um tipo, seguido de dois-pontos:

```text
feat: adiciona tela de login
fix: corrige validação do formulário
docs: atualiza instruções do projeto
```

Tipos comuns: `feat` para funcionalidade, `fix` para correção e `docs` para documentação.

## 3. Envie a branch e abra um pull request
Envie sua branch ao GitHub:

```bash
git push -u origin feature/tela-de-login
```

No GitHub, abra um pull request da sua branch para `main`. Dê um título claro, descreva o que mudou e como testar. Revise as alterações e solicite a revisão da equipe.

## 4. Revise antes de aprovar
- A mudança atende ao objetivo descrito no pull request?
- O código é compreensível e está relacionado à tarefa?
- Há erros visíveis ao testar a funcionalidade?
- As alterações mantêm o padrão e a estrutura do projeto?
- A documentação foi atualizada quando necessário?

Se encontrar algo a corrigir, deixe comentários claros no pull request. Aprove somente quando estiver confortável com as alterações.
