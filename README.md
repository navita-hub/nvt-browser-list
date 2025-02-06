# nvt-browser

## Finalidade

Este repositório tem como objetivo guardar o arquivo principal de restrição de acesso as urls do NVT-BROWSER. Quando o aplicativo é iniciado no device do cliente, é recuperado as informações contidas dentro do arquivo e aplicadas durante o uso.

## Como adicionar ou remover restrições

### Adicionando restrição
Devemos adicionar uma url sempre em uma nova linha do arquivo, lembrando que devemos usar uma url mais simplista possível para ser mais acertivo quando a restrição. Ex:

* Temos a URL https://www.linkedin.com/feed/ da qual queremos restringir. Se usarmos dessa forma, qualquer outra url que comece com https://www.linkedin.com/ não será aplicado a restrição, com exceção do /feed. 
Para este caso, devemos cadastrar uma URL mais simplista, ex: https://www.linkedin.com e desta forma iremos bloquear qualquer coisa nesse domínio.

### Removendo restrição
Devemos remover a linha da qual encontra a URL desejada a ser removida. O importante é não deixar embranco a linha, e sim remover ela em sua totalidade.

### Como aplicar
Devemos usar o fluxo do github para tal, entrando no arquivo, clicando no lado direito em uma figua de lápis ("Edit this file") da qual irá redirecionar para uma outra página de edição, realizar a edição necessária, seja inclusão ou remoção e após clicar no botão verde do lado direito superior ("Commit changes").
Na modal que irá abrir, podes colocar um comentário sobre a mudança na descrição e após isso, ir em "Commit changes" presente nesta modal. Após isso, o arquivo atualizado estará disponível para download pelo APP.
Para aplicar essas restrições no APP, devemos reiniciar o mesmo para tal. Ou seja, toda vez que abre o aplicativo, ele carrega a última atualização do arquivo automaticamente sem a necessidade de solicitar ao aplicativo que faça isso.

### URL do arquivo principal

https://github.com/navita-hub/nvt-browser-list/blob/master/url-bloqueio-sites.txt
