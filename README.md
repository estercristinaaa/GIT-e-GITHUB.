# GIT-e-GITHUB.
Principais funções do Git:

O Git é um sistema de controle de versão distribuído, ou seja, ele permite controlar e registrar as alterações feitas em arquivos de um projeto ao longo do tempo.

Controle de versões:

Permite registrar e acompanhar todas as alterações feitas no código-fonte de um projeto.
Cada "commit" no Git cria um ponto de restauração, para que você possa voltar a qualquer versão anterior do código, caso necessário.
Branching (Ramificação):

O Git permite criar branches (ramificações) para que você possa trabalhar em novas funcionalidades ou corrigir erros sem afetar o código principal. Após a finalização, você pode merge (mesclar) essas alterações de volta ao branch principal.
Trabalhar offline:

Como o Git é distribuído, você pode realizar muitas operações (como commits e branches) sem precisar de uma conexão com a internet. A sincronização é feita quando você decide compartilhar suas mudanças.
Desfazer alterações:

Git oferece ferramentas para desfazer alterações de forma segura, seja voltando um commit ou desfechando modificações locais.
Merge e Resolução de Conflitos:

O Git facilita a combinação de diferentes ramificações de código (merge). Quando ocorrem conflitos, o Git ajuda a identificar e resolver essas situações.
Histórico de alterações:

Git mantém um histórico completo de todas as mudanças feitas no código, incluindo quem fez a mudança e quando. Isso facilita auditorias, revisões de código e rastreamento de bugs.
Principais funções do GitHub:
O GitHub é uma plataforma baseada na web para hospedar repositórios Git e facilitar o trabalho colaborativo entre desenvolvedores. Ele adiciona funcionalidades de colaboração ao Git.

Hospedagem de repositórios Git:

O GitHub permite armazenar repositórios Git na nuvem, tornando o acesso e a colaboração mais fáceis, sem precisar de servidores locais.
Colaboração em equipe:

Facilita a colaboração em projetos, permitindo que múltiplos desenvolvedores trabalhem no mesmo repositório simultaneamente.
Ferramentas como pull requests permitem que os desenvolvedores revisem, discutam e integrem alterações propostas por outros membros.
Issues (Problemas):

O GitHub possui um sistema de gerenciamento de problemas, onde você pode registrar bugs, sugerir melhorias ou discutir novas funcionalidades com a equipe.
GitHub Actions:

Permite automação de processos, como integração contínua (CI) e entrega contínua (CD). Isso ajuda a testar, compilar e implantar seu código de maneira automática a cada commit.
Wiki e Documentação:

O GitHub oferece suporte a wikis e páginas de documentação diretamente no repositório, permitindo que a equipe mantenha um registro claro de como o projeto funciona e como contribuir.
Visibilidade e Networking:

Repositórios públicos no GitHub permitem que outros desenvolvedores vejam seu trabalho e até contribuam com ele. Isso é ideal para projetos open source.
Fork e Pull Request:

No GitHub, você pode forkar um repositório, ou seja, fazer uma cópia dele em sua conta para trabalhar em mudanças. Depois, pode criar um pull request para sugerir que suas alterações sejam integradas ao repositório original.
Integração com outras ferramentas:

GitHub permite a integração com diversas ferramentas de desenvolvimento, como Slack, Jira, Trello, e mais, otimizando o fluxo de trabalho.

Comandos do Git:

Gerenciamento de Repositórios
git init: Cria um novo repositório Git.
git clone <url>: Clona um repositório remoto para o seu diretório local.
Comandos de Estado
git status: Exibe o status do repositório, mostrando arquivos modificados, adicionados ou não rastreados.
git diff: Exibe as diferenças entre a versão atual dos arquivos e a última versão registrada.
Comandos de Alteração de Código
git add <arquivo>: Adiciona arquivos ao índice, preparando-os para o commit.
git commit -m "<mensagem>": Registra as alterações no repositório com uma mensagem descritiva.
git commit --amend: Modifica o último commit (útil para corrigir pequenos erros).
Trabalhando com Branches
git branch: Exibe as branches locais.
git branch <nome-branch>: Cria uma nova branch.
git checkout <nome-branch>: Alterna para outra branch.
git merge <nome-branch>: Mescla uma branch ao branch atual.
git rebase <nome-branch>: Reaplica os commits da branch atual sobre uma nova base.
Comandos Remotos
git remote -v: Exibe os repositórios remotos configurados.
git push: Envia as mudanças locais para o repositório remoto.
git reset <commit>: Move o ponteiro do branch para um commit anterior.
git reset --hard <commit>: Faz reset e descarta todas as alterações no diretório de trabalho.

Comandos do GitHub

git remote add origin <url-do-repositório>: Conecta um repositório local ao repositório remoto no GitHub.
git push -u origin <branch>: Envia uma branch local para o repositório remoto no GitHub.
git pull origin <branch>: Baixa mudanças de uma branch remota no GitHub para o seu repositório local.
Usando Pull Requests no GitHub:
No GitHub, a criação de Pull Requests (PRs) é feita através da interface web do GitHub, mas você pode usá-los com GitHub CLI:

gh pr create: Cria um novo pull request.
gh pr status: Exibe o status dos pull requests no repositório.
gh pr merge: Mescla um pull request aprovado ao repositório.
GitHub Actions:
GitHub Actions permite configurar workflows automáticos diretamente no repositório. Esses workflows são definidos em arquivos YAML.

gh actions status: Exibe o status dos workflows no repositório.
gh actions run: Executa manualmente um workflow de ação.

COMO POSTAR UM GIT e GITHUB ONLINE

Inicializar repositório local: git init
Adicionar arquivos ao repositório: git add .
Fazer commit: git commit -m "Mensagem do commit"
Adicionar repositório remoto: git remote add origin <URL do repositório>
Enviar para o GitHub: git push -u origin main ou git push -u origin master


