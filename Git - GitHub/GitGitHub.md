# Git/GitHub 

#### 1. O que é o Git?

Git é um **sitema distribuído *opensource* de controle de versão**, sendo utilizado para registro de edições de quaisquer arquivos, por exemplo trabalhos de TCC e monografias de doutorado, contudo, o uso mais comum desse sistema se dá na área da programação. 

Dentro deste universo, o objetivo do Git é **registrar todas as mudanças feitas no código-fonte de um projeto**, evitando que algo importante se perca no meio do caminho.

#### 2. Principais comandos do Git

- **Git init**: Ao iniciar um projeto que ainda não seja um repositório, esse comando costuma ser utilizado, uma vez que ele cria um repositório vazio ou transforma uma pasta que você já tem e que não está com controle de versão em um repositório.
  Exemplo: git init

- **Git clone**: É o comando utilizado para baixar o código-fonte existente de um repositório remoto (por exemplo o GitHub)
  Exemplo: git clone <https://url-do-link>

- **Git status:** Utilizado para fornecer algumas informações importantes sobre a branch em que você estiver no momento, incluindo se ela está atualizada em relação à master e quais arquivos foram alterados.
  Exemplo: git status

- **Git add:** Ao realizar alterações em um arquivo, ou quando críamos ou excluímos algum, essas alterações ocorrem somente no repositório local, e não serão incluídas no próximo commit até solicitarmos com o comando. Para que essas alterações sejam incluídas é necessário usar o comando **git add**.
  Exemplo: Para adicionar de uma vez todos os arquivos, utilizamos o comando **git add -a**, caso queira adicionar apenas um arquivo, utilizamos **git add arquivo**.

- **Git commit:** Comando utilizado para definir um ponto de verificação no processo de desenvolvimento, para o qual você pode voltar mais tarde, caso seja necessário.
  Exemplo: **git commit -m** **"mensagem explicando a mudança feita"**

- **Git push**: Após confirmar as alterações, a próxima etapa é enviar essas informações para o servidor remoto, para isso utilizamos o comando **git push**.
  Exemplo: **git push origin nome**.

  ***Nota: Foram listados apenas alguns comandos utilizados na introdução ao Git/GitHub, existem vários comandos à serem explorados ao longo dos estudos.***

  

#### 3. O que é o GitHub?

Em resumo, o GitHub é um plataforma que funciona como repositório de dados compartilhados, que permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo.