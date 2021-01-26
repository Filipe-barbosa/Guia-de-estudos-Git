# Guia-de-estudos-Git.
  Olá seja bem-vindo ao guia de inicialização ao Git, me chamo Filipe Barbosa e assim como você sou um entusiasta dos códigos e aluno da PodCodar.

  Já ouviu falar em Git? Do que se trata? Para que serve? Bem, vamos responder todas essas questões no decorrer do texto. 
Git é uma ferramenta de gerenciamento de controle de versão de código, ou seja, ele registra todas as alterações feitas no decorrer do código, e você ou qualquer membro da organização podem acessar sempre que quiserem e recuperar versões especificas do produto. Bacana não?!

  Com o uso do **Git** os membros do time podem acessar o código a qualquer momento e trazê-los para sua máquina, fazer as alterações necessárias e subir o código novamente evitando assim conflitos, e que sempre possa desenvolver em cima de uma versão mais atual do código.
Abaixo segue o link de uma boa explicação do que é o Git

<https://www.youtube.com/watch?v=WVLhm1AMeYE>

  Esta apresentação mostra um pouco de como funciona o Git na máquina, mas para conseguir subir o nosso código precisamos de um lugar na nuvem para que ele fique guardado e também para que possamos subir e baixar o código, para isso iremos utilizar o Git hub, um servidor on-line onde iremos criar nossa conta  dar início a hospedagem.
<https://github.com/>

### Comandos 
  Abaixo irei listar uma lista dos primeiros comandos do Git juntamente com a função de cada um deles.
  
 Comando | Função
--------- | ------
git clone link do repositório  | Comando usado para clonar um repositório para a sua maquina 
git status | Mostra o status dos arquivos dentro da pasta (adicionados ou nao)
git add . | Adiciona todos os arquivos modificados na pasta para um commit. **Obs** (No lugar do . você pode colocar o nome do arquivo que você quer ou só um tipo específico, tipo .js, sobe só arquivos .js)
git commit -m "Meu commit" | Cria um commit, para subir os arquivos alterados
git push | Comando  que sobi as alterações feiras para o git hub **Obs** (Na primeira vez que é realizado um push e um branch iremos ultilizar o seguinte comando:**git push --set-upstream origin minha branch**)
git pull | Baixa os arquivos (ou atualizações  de uma branch) do repo para a maquina 
git branch | Exibe todas as branchs presentes no repositório.
git branch minha branch| Cria uma branch Nova 
git checkout minha branch| Seleciona uma branch
git  fetch | Puxa as branchs remotas
git branch -D minha branch| apaga a branch 
git log| Mosta a seguencia de commits realizados

### É hora de treinar !!
Agora que já conhecemos todos esses comandos tem um site muito legal onde da pra aplicar um pouco deles e ver o que está acontecendo em nosso repositório, assim podemos melhorar nosso entendimento e familiarizar com a ferramenta antes de iniciar no dia a dia em nossos projetos.
<https://learngitbranching.js.org/?locale=pt_BR>

Espero que tenha gostado desse material e não se esqueça !

# Sim Você PodCodar

