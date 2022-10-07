# Desafio cinematográfico

A nova configuração do mercado cinematográfico exige do cineasta — e dos artistas em geral — que se torne empreendedor. Isso significa resolver problemas que não são propriamente artísticos em boa parte do tempo.

Captação de clientes, atendimento, relatórios, comprovação de gastos, controle financeiro… São muitas as habilidades que um profissional autônomo da área de Cinema deve desenvolver, mesmo que superficialmente.

Uma rede de cinemas da cidade de São Carlos/ SP gostaria de otimizar a sua renda, hoje eles possuem 2 salas de cinema uma maior, com capacidade para 150 pessoas e 1 sala menor, com capacidade para 84 pessoas.

A cada mês, a rede precisa decidir quais filmes adquirir para obter o maior número de espectadores e gostariam de fazer uma decisão mais baseada em dados. Hoje é a Juliana, funcionária mais antiga do cinema que toma essas decisões muito baseada na sua experiência a 6 anos trabalhando no ramo, mas muitas vezes as sessões não enchem como gostariam.

Também existe a possibilidade de adquirir uma nova área no shopping onde o cinema está localizado para a criação de uma sala VIP, com 100 lugares, mas existe uma dúvida se haverá retorno no investimento, se o mercado de filmes realmente está crescendo e qual tipo de filme deveria passar nessa sala nova para justificar o preço do ingresso, que custará 30% a mais do que o valor do ingresso nas salas atuais.

A Juliana, também se formou recentemente em cinema e tem pressionado o administrador do cinema a adquirir mais filmes nacionais e dublados, a teoria dela é que isso irá atrair mais clientes para o cinema, principalmente fora dos períodos de férias escolares.
Gostaríamos muito da sua ajuda para conseguir responder as seguintes perguntas:
- O mercado de filmes está crescendo ou diminuindo?
- A teoria da Juliana que os filmes nacionais têm tido cada vez mais aceitação é verdade?
- Quais outros insights podemos tirar sobre os filmes?
- Existe algum padrão em filmes que tem alta renda?
- Existe algum padrão para filmes que ficam mais tempo em cartaz do que outros?
- Existem distribuidoras que trazem filmes com mais renda?

Além disso, seria muito bom que tivéssemos um modelo que ao receber um filme, se vale a pena comprá-lo, e nos dissesse quanto tempo devemos deixar em cartaz ou quantas sessões devemos criar para ele.

## Sobre a Fonte de Dados

Criada em 2001, a Agência Nacional de Cinema é uma agência reguladora criada em 2001. Mesmo com autonomia administrativa em relação ao governo, sua diretoria é aprovada pelo Senado e está submetida ao Ministério da Cidadania depois da extinção do Ministério da Cultura. Para ajudar os profissionais desta área, o Ministério fornece dados públicos sobre o mercado nos últimos anos:

Dicionário das colunas
- TITULO_ORIGINAL: String – Nome original do filme
- TITULO_BRASILEIRO: String – Nome do filme no Brasil
- GENERO: String Genero do Filme, podendo ser Ficção, Animação, etc.
- PAIS_ORIGEM: String País de Origem da produtora do filme
- CPB_ROE: String Código do Filme
- COPIAS: Numero inteiro -  Quantas cópias foram distribuidas
- SALAS: Numero inteiro – Quantas salas de cinema passaram o filme
- DT_INICIO_EXIBICAO: Data – Data de estréia do filme no Brasil
- DT_FIM_EXIBICAO: Data – Data da ultima sessão do filme no Brasil
- PUBLICO: Numero inteiro Quantidade de expectadores
- RENDA: Numero com decimais: Valores arrecadados com bilheteria
- RAZAO_SOCIAL_DISTRIBUIDORA: String – Nome da distribuidora
- REGISTRO_DISTRIBUIDORA: Numero inteiro – Numero do registro na Ancine
- CNPJ_DISTRIBUIDORA: String – CNPJ da distribuidora
- ANO_CINEMATOGRAFICO: Numero – Ano da produção