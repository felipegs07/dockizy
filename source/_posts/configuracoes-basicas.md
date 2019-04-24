---
title: Configurações Básicas
order: 2
---

Há algumas poucas configurações básicas que você pode fazer para definir parâmetros como as cores da documentação, título descrição e imagem padrão.

Essas configuração serão feitas no arquivo **_config.yml** do projeto.

### Configurações do Tema

Logo no topo do arquivo terão as configurações do site, o bloco se encontrará por padrão assim:
```bash
    # Site
    title: Dockizy
    description: >-
    Dockizy é um tema simples, fácil e rápido para criar documentações.
    img: "/img/dockizy.png" # logo of the documentation
    background_color: "#0D83CD" # color of background on hover
    text_color: "#000" #color of the text on hover
```

- **title:** o nome do seu projeto ou produto.
- **description:** uma pequena descrição da sua documentação, aparecerá no menu lateral.
- **img:** imagem do seu projeto que também fica localizada no menu lateral.
- **background_color:** cor do *background* no evento *hover* nos itens do menu lateral ou no botão de menu na versão *mobile* (aceita rgb, hex, nome da cor).
- **text_color:** cor do texto dos itens do menu no evento *hover*.

### Configurações de URL

Essas configurações são necessárias para preparar o **Dockizy** para integrar com seu site ou gerar o site estático de forma correta. As configurações de site aparecerá assim:
```bash
    # URL
    ## If your site is put in a subdirectory, set url as 'http://yoursite.com/child' and root as '/child/'
    url: http://yoursite.com
    root: /
    permalink: :title/
    permalink_defaults:
```
- **url:** será o link do seu site, com domínio e etc.
- **root:** o root serve para definir um link inicial diferente, se a documentação ficará inicialmente como  http://yoursite.com/docs/, o root dele deverá ser configurada aqui. Nesse exemplo ficaria assim:

```bash
    root: /docs/
```

Pronto, seu **Dockizy** está pronto para criar sua documentação!