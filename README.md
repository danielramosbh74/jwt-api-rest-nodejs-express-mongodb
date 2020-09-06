# Instruções

1. Você pode configurar o Banco de dados como achar melhor, mas no meu caso particular instalei o MongoDB usando o Docker, então é necessário iniciá-lo via Docker toda vez que reiniciar o computador.

```sudo su```

```docker start mongodb```

2. Logo após iniciar o mongodb via Docker, lembrar também de iniciar a API em si lá terminal, ou seja, ```node src/index.js``` antes de tentar fazer alguma requisição via Insomnia, pois caso contrário obteremos o erro de que não conseguimos nos conectar com o servidor. Apesar disso ser meio óbvio, às vezes esquecemos de "um detalhe" e perdemos tempo procurando por erros que não existem no código...

3. Sugiro assistir e estudar o vídeo original abaixo para entender o funcionamento. 

4. Estou deixando esta API compartilhada aqui pelos seguintes motivos:
- Backup de meus arquivos
- Me lembrar futuramente do seu funcionamento caso precise
- Facilitar a vida de outras pessoas também, pois se queremos ser ajudados quando precisamos acho que também devemos ajudar quando podemos. ;)


# Observações

- Fonte: Diego Fernandes - Rocketseat - https://www.youtube.com/watch?v=BN_8bCfVp88&list=PL85ITvJ7FLoiXVwHXeOsOuVppGbBzo2dp
- Não estou conseguindo acessar via https (erro SSL), consigo acessar apenas via http.
