# teste-devops
# Teste para vaga de DevOps 

Olá aspirante, seja bem-vindo ao seu teste.

Esperamos que tenha dado tudo certo até aqui e desejamos a você um ótimo teste.


Disclaimer: Os CNPJs e CPFs utilizados nos testes foram gerados em https://www.4devs.com.br/gerador_de_cnpj

## Stack
*Backend*: python com Django

*Froentend*: html com jquery, Angular, React ou vue

*Database*: MySQL

*Ambiente*: Kubernetes, protainer, grafana, zabbix, github action

*Obs*: Você pode utilizar frameworks e bibliotecas.

## O Problema e O que Esperamos

Para este teste esperamos que voce crie um pequeno cluste contendo um ambiente que possa ser colocado em produção.
1. crie um pipeline para subir um cluster kubernetes com portainer, grafana, zabbix e mysql. alem desses subir tambem a API RESTFull que sera desenvolvida em python suba tambem um container de frontend
2. Crie um pipeline github action para que seja alterado somente os container de Backend e Frontend.
3. crie as integrações com zabbix para monitoramento de memoria cpu e armazemanaemto de cada conteiner
4. integre com grafana para monitoramento da vida do serviço para verificação de bug em tempo real
5. Você deve criar uma API REST capaz de cadastrar e obter informações de Formulario de contato( abertura de tiket).
6. Os dados recebidos devem ser armazenados num banco de dados criado pelo candidato.
7. Também deve ser criado uma(s) página(s) para que seja possível visualizar os dados cadastrados e o formulario de contato.

Registre tudo: testes que foram executados, ideias que gostaria de implementar se tivesse tempo (explique como você as resolveria, se houvesse tempo), decisões que foram tomadas e seus porquês, arquiteturas que foram testadas e os motivos de terem sido modificadas ou abandonadas. Crie um arquivo COMMENTS.md ou HISTORY.md no repositório para registrar essas reflexões e decisões.

## Prazo
O prazo de entrega é de 4 dias corridos, contados a partir do recebimento deste teste.


## Exemplos de Requisições

### Exemplo de JSON de Cadastro e recuperação de Contato
```
{
  
  "name": "W Technology",
  "doc": "60.429.484/0001-10",
  "email": "teste@teste.com.br"
  "subject": "Software4u, uma empresa especializada em inovar",
  "message": "Software4u, uma empresa especializada em inovar e que no momento esta em busca de Novos colaboradores"
}
```


## Entrega
Coloque seu código em um repositório privado no Github e adicione o @JefteCosta como um de seus colaboradores. Essa conta no Github (JefteCosta) é utilizada exclusivamente para aplicação e revisão de testes.

# Dicas

Use ferramentas e bibliotecas open source, mas documente as decisões e porquês;

Automatize o máximo possível;

Em caso de dúvidas, pergunte.

## Considerações Finais
Sinta-se livre para impressionar na sua solução e apresentação.

Bom teste!!

#NaVelocidadeDoSeuTalento #EnjoyTheRide

