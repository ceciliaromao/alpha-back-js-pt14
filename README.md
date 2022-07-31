![](https://portal.alphaedtech.org.br/images/edtech/logo-edtech.webp)

# Back-End

## Módulo 7 - JavaScript - Part 14

### Exercícios de classe 🏫

#### Questão 1
Crie uma página simples de uma ‘doceria’, de forma que: 
* Contenha a página principal, de brigadeiros, de cupcakes, de doces e o arquivo de roteamento, isto é, são 5 (cinco arquivos ao total);
* As páginas devem ser carregadas utilizando-se o conceito de SPA. Assim, ao clicar em cada link das demais páginas, o navegador não deve ‘recarregar’ a página inteira, isto é, apenas o elemento do DOM específico deve ser atualizado;
* Deve-se existir um arquivo principal ‘index.js’ que contém a rota para as demais páginas. Utilize o sistema de ‘modules’ do Javascript para carregar as demais páginas;
* O sistema de gerenciamento de rotas deve alterar o endereço do navegador sem recarregar a página (utilize o ‘pushState’ para o ‘history’);
* Como a alteração do endereço do navegador por si só não dispara nenhum evento de alteração de estado do tipo ‘onstatechange’, criar uma função que faça a atualização do history e dispare um evento que servirá como forma de identificar qual rota a sua página deve exibir:
  - Por exemplo: Ao clicar em ‘brigadeiros’, o endereço do navegador deve ser algo do tipo ‘http://localhost/brigadeiros’.
  - A função deve além de alterar o endereço do navegador emitir um CustomEvent ‘onstatechange’ com o dado em details ‘/brigadeiros’.
  - A sua página identificará que houve um evento emitido e ‘renderizará’ a página respectiva de brigadeiros.
  - Realizar o mesmo para ‘/’, ‘/cupcackes’ e ‘/doces’.

###### tags: `módulo 7` `back-end` `JavaScript`

