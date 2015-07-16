# Exemplo de artigo com o formatafacil

- [Artigo na nuvem](http://146.148.88.138/artigo/formatafacil/exemplo-artigo) - ([no servidor local](http://localhost:4567/artigo/formatafacil/exemplo-artigo/))

## Arquivos


- [artigo.md](https://github.com/formatafacil/exemplo-artigo/edit/master/artigo.md) 
- [resumo.d](https://github.com/formatafacil/exemplo-artigo/edit/master/config/resumo.md) 
- [abstract.md](https://github.com/formatafacil/exemplo-artigo/edit/master/config/abstract.md)
- [README.md](https://github.com/formatafacil/exemplo-artigo/edit/master/README.md)

### Artigo original

- [Artigo original](http://www.scielo.br/scielo.php?script=sci_pdf&pid=S1518-76322015000100061&lng=pt&nrm=iso&tlng=pt) -- [doi](http://dx.doi.org/10.1590/1982-4017-150104-1014)

## Descrição

Este repositório contém um exemplo de artigo formatado com [formatafacil](https://github.com/formatafacil/formatafacil).

Para validar o uso da ferramenta, escolhemos um artigo aleatório
para utilização.


## Configurando a geração no servidor (Webhook)

### Criando uma cópia do projeto (fork)

1. Criar um [fork deste projeto](https://github.com/formatafacil/exemplo-artigo/fork)

2. Perceber que foi criado uma cópia do projeto com o seu usuário

3. Configurando o endereço do servidor

4. Entrar na [configuração do projeto, na opção Webhooks & Services](./settings/hooks)

5. Clicar em [adicionar um webhook](./settings/hooks/new&hook_url=http://146.148.88.138/artigo) (*Add webhook*)

6. Configurar o campo *Payload URL* com http://146.148.88.138/artigo

7. Apagar o campo *Secret*

8. Confirmar inclusão clicando *Add webhook*

