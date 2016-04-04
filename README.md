## README

Esse é o projeto base de Rails da CJR. Ele deve ser clonado afim de iniciar um novo projeto. Ele possuí as seguintes caracteristicas:

+ Ruby Version: 2.2.3
+ Rails Version: 4.2.4
+ Usa Slim, Sass (SCSS)
+ Usa [Smacss](https://smacss.com/) para modularizar stylesheets
+ Usa Bootstrap
+ Usa FontAwesome
+ Usa Rails 12Factor
+ Usa Mailcatcher
+ Usa Rubocop para análise do código Ruby

**ATENÇÃO**: crie um arquivo local_env.yml em config/ e coloque as seguintes informações:

```
GMAIL_USERNAME: 'email'
GMAIL_PASSWORD: 'senha'
```

Para compilar esse arquivo, use `rake doc:app`
