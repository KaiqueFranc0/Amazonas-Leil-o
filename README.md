# Projeto Amazonasleilao

## Sobre o projeto

Este projeto é um site demonstrativo de leilões de animais de criação. A ideia é apresentar os animais e destacar o cuidado com a origem, a documentação e o bem-estar deles.

Usei o figma para criação inicial do site e para ter ideia de como iria funcionar o site, locais das imagens, utilizei IA para gerar as imagens, juntamente com os textos do site, após ter todo o site já desenhado como seria as quatro paginas comecei apenas a passar para o codigo, para revisão de semantica, utilizei o chatgpt para verificar.

Cada página ficou em um arquivo separado para facilitar a organização. Utilizando a materia do Rafael sobre modularização, para organização dos arquivos.

## Integrantes da equipe

Luiz Miguel
Kaique
Mario 
Stephany 
Ryan

## Organização dos arquivos

- `index.html`: página inicial, com a apresentação do site e os lotes de animais.
- `sobre.html`: explica a proposta do projeto, os princípios e a equipe fictícia.
- `login.html`: apresenta o formulário de acesso demonstrativo.
- `trabalhe-conosco.html`: mostra as vagas fictícias e a seção de candidatura.
- `imagens/`: guarda as imagens retiradas do documento de referência.


## Como o HTML foi organizado

Usei `header` para o cabeçalho, `nav` para os menus, `main` para o conteúdo principal e `footer` para o rodapé. Também usei `section` para separar os assuntos, `article` para conteúdos como lotes e vagas, e `aside` para informações complementares.

Cada página tem um título principal com `h1`. Os outros títulos usam os níveis seguintes, de acordo com a divisão do conteúdo.

Os menus permitem acessar as quatro páginas. Alguns links levam para uma parte da própria página, usando o identificador `id`.

## Acessibilidade

O idioma das páginas está definido como português do Brasil. As imagens têm uma descrição no atributo `alt` e os campos do login possuem rótulos com `label`.

Também existe o link “Pular para o conteúdo principal”, que ajuda quem navega pelo teclado. O atributo `aria-current` indica qual página está aberta no menu.

## Formulário e limitações

O login usa `required` para exigir o preenchimento dos campos e `type="email"` para verificar o formato do e-mail. Essa verificação é feita pelo próprio navegador.

## Uso de IA

Foi utilizada IA para ajudar na criação dos textos e também das imagens para desenvolver o projeto primeiramente no figma para não termos problemas com copyright com as imagens.
