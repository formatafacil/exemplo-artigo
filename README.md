# Exemplo de artigo com o formatafacil

Este repositório contém um exemplo de artigo formatado com [formatafacil](https://github.com/formatafacil/formatafacil).


O artigo original pode ser encontrado em: <http://dx.doi.org/10.1590/1982-4017-150104-1014>, juntamente com seu [pdf](http://www.scielo.br/scielo.php?script=sci_pdf&pid=S1518-76322015000100061&lng=pt&nrm=iso&tlng=pt).

Para validar o uso da ferramenta, escolhemos um artigo aleatório
para utilização.

## Estrutura de arquivos

- artigo.md
- config/resumo.md

## Configurando a geração no servidor (Webhook)

### Criando uma cópia do projeto (fork)

- Criar um [fork deste projeto](https://github.com/formatafacil/exemplo-artigo/fork)

- Perceber que foi criado uma cópia do projeto com o seu usuário

- Configurando o endereço do servidor

- Entrar na [configuração do projeto, na opção Webhooks & Services](./settings/hooks)

- Clicar em [adicionar um webhook](./settings/hooks/new&hook_url=http://146.148.88.138/artigo) (*Add webhook*)

. Configurar o campo *Payload URL* com http://146.148.88.138/artigo
. Apagar o campo *Secret*
. Confirmar inclusão clicando *Add webhook*

