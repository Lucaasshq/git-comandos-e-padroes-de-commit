

## 👩‍💻 COMANDOS ESSENCIAIS 

git init: iniciar repositorio dentro da pasta

git add <nome-arquivo>: incluir as alterações para commit

git commit -m "mesagem-exemplo": salvar as altereções no repositorio local

git remote add origin https://github.com/Lucaasshq/git-commands-course.git: preparar arquivo para enviar para repositorio local para github

git push -u origin master: enviar arquivo preparado para repositorio remoto

git branch: Listar branchs

git checkout -b "Nova-branch":Criar uma Nova branch

git checkout Nome-da-branch: entrar na branch escolhida

git merge nome-da-branch-do-merge: mesclar a branch main com a ramificação escolhida

git pull:trazer alterações do repositorio remoto para o repositorio do local do computador

git clone http://exemplo.git":Clonar repositorio do github

git branch -M "nome-da-nova-branch": renomear a branch com o novo nome 

# 🎯 Padrão de Commits (Conventional Commits)

## 🔹 Estrutura
```plaintext
<tipo>(<escopo opcional>): <mensagem breve>

<descrição opcional mais detalhada>

BREAKING CHANGE: <explicação opcional sobre mudança que quebra compatibilidade>
```

---

## 🔹 Tipos de Commit
- **feat**: Adiciona um novo recurso (feature).  
  - Exemplo: `feat(auth): adiciona login com Google`  
- **fix**: Corrige um bug.  
  - Exemplo: `fix(api): corrige erro ao buscar usuários`  
- **docs**: Atualizações na documentação.  
  - Exemplo: `docs(README): adiciona instruções de instalação`  
- **style**: Mudanças de formatação (espaços, indentação, etc.) sem afetar a lógica.  
  - Exemplo: `style(css): ajusta padding do botão`  
- **refactor**: Refatoração de código sem mudar funcionalidade.  
  - Exemplo: `refactor(controller): melhora a organização do código`  
- **perf**: Melhorias de desempenho.  
  - Exemplo: `perf(query): otimiza busca de produtos`  
- **test**: Adição ou alteração de testes.  
  - Exemplo: `test(user): adiciona testes unitários para login`  
- **chore**: Mudanças em tarefas auxiliares (build, ferramentas, etc.).  
  - Exemplo: `chore(deps): atualiza dependências`  
- **ci**: Configuração ou ajustes de integração contínua.  
  - Exemplo: `ci(actions): corrige workflow do GitHub Actions`  

---

## 🔹 Exemplo Completo
```plaintext
feat(cart): adiciona opção de cupom de desconto

Agora o usuário pode inserir cupons de desconto no checkout.

BREAKING CHANGE: altera estrutura do banco de dados para suportar cupons.
```


