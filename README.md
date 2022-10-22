# livro-sass
Código relativo ao livro: Sass

Que poderá ser adquirido no site : https://www.casadocodigo.com.br/products/livro-sass

Neste repositório armazendo os códigos usados no meu aprendizado com SAAS.


#Introdução

SAAS é um pré processador de CSS, regado de boas práticas para desenvolvimento front-end e que surgiu para salvar a vida do programador quando o assunto é reaproveitamento de código. Nesta página, registro meu aprendizado sobre o assunto. A fonte de estudo é o livro: Sass: Aprendendo pré-processadores CSS de Natna Souza,
Casa do Código.

#Como usar?

No livro usado como referência deste artigo, foi necessário realizar a instalação do Ruby e do Sass para que o SCSS fosse compilado e executado pelo navegador. Esse mesmo processo é necessário para quem quiser seguir este manual como base de aprendizado do SCSS.    
    * Computadores que rodam o sistema operacional da Apple não requerem a instalção do Ruby, somente do Saas.*
    
    
 
#Instalando os recursos necessários
    
    Conforme mencionado, para que seja possível compilar um código SCSS, é necessário realizar a instalação do Ruby e do Saas.
    
    ## Instalando o RUBY e o SASS:
    
    ### Realizando a instalação do Ruby
    
    Para realizar a instalação do Ruby, basta visitar a sua página e realizar o download da aplicação normalmente.
    
    *Lembrando que no ato da instalção, a opção “Add Ruby executable to your PATH!” deve estar marcada*
    
    Realizada a instalação, será necessário instalar o SAAS.
    
    ### Realizando a instalação do SAAS
    
    1. Acesse o prompt de comando da sua máquina.
        1. Você pode acessar usando Ctrl + R e digitando “CMD” através do Windows.
    
    1. Com o CMD do seu sistema operacional aberto, digite os seguintes comandos:
    
    ```bash
    gem install sass // *caso dê algum erro, confira se o ruby está realmente instalado e tente novamente*
    
    ```
    
    Com isso, basta conferir se a instalação de ambos foram finalizadas com sucesso, em:
    
    ```bash
    ruby -v
    
    // e depois
    
    sass -v
    
    // Se tudo estiver ok, você terá como resposta, a versão do pacote instalado
    
    
   #Mantendo o servidor ativo, recebendo as atualizações do código:
   
   Para que as alterações sejam realizadas sem que você tenha o trabalho de atualizar o servidor pelo cmd, basta no terminal, dentro da pasta do arquivo CSS, digitar o comando:
   
   #sass --watch estilos.scss:estilos.css
   
 
