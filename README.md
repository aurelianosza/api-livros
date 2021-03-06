# api-livros
Exemplo de API simples de cadastro de livros

## Pré requisitos:
* Docker
    > Caso não possua Docker instalado, veja sua instalação.
    > * [Instalação no Windows](https://docs.microsoft.com/pt-br/virtualization/windowscontainers/manage-docker/configure-docker-daemon)
    > * [Instalação no Linux](https://www.hostinger.com.br/tutoriais/install-docker-ubuntu)
* docker-compose compatível com a versão 3
    > Veja aqui como instalar o docker-compose.
    > * [Como instalar e executar o docker-compose](https://www.alura.com.br/artigos/compondo-uma-aplicacao-com-o-docker-compose)
* npm
    > Instalação do nodeJS e npm
    > * [Instalaço no Windows](https://dicasdejavascript.com.br/instalacao-do-nodejs-e-npm-no-windows-passo-a-passo/)
    > * [Instalação no linux](https://www.digitalocean.com/community/tutorials/como-instalar-o-node-js-no-ubuntu-16-04-pt)
* insomnia (Realização de chamadas a api e teste)
    > Instalação do Insomnia
    > * [Insomnia](https://support.insomnia.rest/article/23-installation)
    
## Como executar:
  * Faça o download do repositório.
    > * Fazendo download como .zip
    >    * Clique no botão __Clone or download__ e selecione a opção __Download ZIP__.
    
    >   * Fazendo Download com o git.
    >       * Caso não possua git, faça o [download](https://git-scm.com/downloads) e instale.
    >       * No terminal de comandos do git, digite o comando     `git clone https://github.com/aurelianosza/api-livros.git`   e espere o término do download do repositório.
        
  * Abra o terminal no diretório __service__ dentro da pasta baixada do projeto, e execute o comando `npm install`, aguarde a instalação dos módulos da API.
  * Vá até o diretório raiz do projeto(pasta baixada a partir do diretório) e execute o comando `docker-compose up`, aguarde o download e início dos containeres.
  * Importe a documentação da API.
   >    * Com a aplicação do insomnia aberta, clique na opção __Insomnia__ e selecione a opção __Import/Export__ .
   >    * Clique no botão __Import Data__ e selecione a opção __From File__.
   >    * Na janela de seleção de arquivos, selecione o arquivo __requisicoes.json__, disponível na pasta raiz do projeto.
  
  
