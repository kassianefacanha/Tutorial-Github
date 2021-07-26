# Tutorial-Github

É necessário ter uma conta no Github para s
## Instalação e Uso

### Por comandos
1º PASSO: Intalar git no
Faça o download no site https://git-scm.com/downloads e execute como adm e siga os passos de instalação até a conclusão.

Façan
2º PASSO: Verificar se tá instalado git
```
git --version

```
3º PASSO: Assinatura

Antes de continuar precisamos nos identificar no Git para que todos pontos na história tenham nossa assinatura. Execute os dois seguintes comandos com seu nome e e-mail respectivamente:
```
git config --global user.name "Seu nome"
git config --global user.email "seu-email@example.com"
```
Agora, em uma pasta vazia vamos indicar que utilizaremos Git nesse projeto com o comando git init. Esse comando irá criar uma pasta oculta chamada .git no seu projeto onde ficarão armazenados todos os arquivos referentes à história do projeto. Se você deletar essa pasta, todo histórico é perdido.

Você deve receber um retorno como esse:
```
Initialized empty Git repository in C:/Users/SEU_USUARIO/projeto/.git/
```
Tudo pronto! Agora vamos criar nosso primeiro arquivo dentro dessa pasta. Abra seu editor de preferência e crie um arquivo chamado arquivo.txt na raiz do diretório.

**Principais Comandos do Git**

- git config -–list » Lista as configurações do Git, se estiver dentro do repositório, lista mais itens
- git config -–global user.name "Meu Nome" » Define o nome de usuário para o Git
- git config -–global user.email "email@dominio.com" » Define o e-mail de usuário para o Git (tem de ser o cadastrado no GitHub)
- git config -–global core.editor vim » Define o editor de texto padrão para abrir automaticamente arquivos informados pelo Git
- git init » Inicializa um repositório Git
- git status » Vê o estado atual do projeto
- git add arquivo.txt » Adiciona o arquivo arquivo.txt ao projeto

Opções do parâmetro add

git-add # mesmo comando que 'git add'
O comando git-add não irá adicionar arquivos ignorados por padrão a menos que seja utilizado o parâmetro '-f'
git add -A # Adiciona todos arquivos que foram modificados, mesmo que: --all, --no-ignore-removal
git add *.txt # Adiciona todos os arquivos '.txt' que foram modificados
man git-add # manual completo sobre git-add

- git commit -m "Minhas mudanças efetuadas" » Armazena as mudanças efetuadas e descreve o que foi alterado
- git log » Mostra todas as mudanças que já foram efetuadas: commit, autor e data
- git push -u origin master » Envia todos os arquivos modificados e “commitados” para o repositório no github
- -u - faz com que o Git armazene esse comando e da próxima vez basta utilizarmos git push
- origin- diz que o repositório no github possui o mesmo nome do projeto/diretório que você está enviando
- master - é o nome da branch (indicador) Clique aqui para saber mais sobre branches
- git pull origin master » Verifica as mudanças efetuadas por outros colaboradores do projeto
- git diff HEAD » Verifica as partes dos arquivos alterados no último commit, veja mais opções em man git-diff
- git reset arquivo.txt » Remove um arquivo do projeto
- git checkout – arquivo.txt » Desfaz a última alteração feita num arquivo
- git rm "*.txt" » Remove 1 ou mais arquivos utilizando “curinga”
- git clone https://github.com/user/project.git » Copia um projeto pro seu PC
- info git » Obtém a Documentação do git
- man git » Obtém o Manual do git

Mais comandos em:
https://training.github.com/downloads/pt_BR/github-git-cheat-sheet.pdf
### Pelo VSCode

### Pelo Github Desktop
