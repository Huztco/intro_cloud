Introdução a Cloud Computing (Computação em Nuvem)

A cloud computing oferece serviços como armazenamento e processamento de dados via web, eliminando a necessidade de uma infraestrutura própria (on premise).
Os usuários acessam os recursos ofertados sob demanda, com escalabilidade e flexibilidade, pagando conforme o uso. Hoje, existem três tipos de cloud, são elas:

- Pública (Fonte: https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-are-private-public-hybrid-clouds):
  - As nuvens públicas são a maneira mais comum de implantação da computação em nuvem. Os recursos de nuvem (como servidores e armazenamento) pertencem a um provedor de serviço de nuvem terceirizado,
são operados por ele e entregues pela Internet. Com uma nuvem pública, todo o hardware, software e outras infraestruturas de suporte são de propriedade do provedor de nuvem e gerenciadas por ele.
  - Vantagens:
    - Redução de custos — não há necessidade de comprar hardware ou software e você paga somente pelos serviços que usa.
    - Sem manutenção — seu provedor de serviços fornece a manutenção.
    - Escalabilidade quase ilimitada — recursos sob demanda estão disponíveis para atender às suas necessidades de negócios.
    - Alta confiabilidade — uma ampla rede de servidores assegura contra falhas.

- Privada (Fonte: https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-are-private-public-hybrid-clouds):
  - Uma nuvem privada consiste em recursos de computação em nuvem usados exclusivamente por uma única empresa ou organização. A nuvem privada pode estar localizada fisicamente no datacenter local da sua organização ou pode ser hospedada por um provedor de serviços terceirizado. Mas em uma nuvem privada, os serviços e a infraestrutura são sempre mantidos na rede privada e o hardware e o software são dedicados unicamente à sua organização.
  - Vantagens:
    - Maior flexibilidade — sua organização pode personalizar seu ambiente de nuvem para atender a necessidades de negócios específicas.
    - Maior controle — os recursos não são compartilhados com outros usuários, portanto, é possível um nível maior de controle e privacidade.
    - Maior escalabilidade — nuvens privadas geralmente oferecem mais escalabilidade em comparação com a infraestrutura local.

- Híbrida (Fonte: https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-are-private-public-hybrid-clouds):
  - Uma plataforma de nuvem híbrida oferece às organizações muitas vantagens, como maior flexibilidade, mais opções de implantação, segurança, conformidade e obtenção de mais valor da infraestrutura existente que elas têm.
    Quando a demanda de computação e processamento oscila, a computação em nuvem híbrida proporciona às empresas a capacidade de escalar verticalmente com facilidade a infraestrutura local delas para a nuvem pública a fim de
    operar qualquer estouro, sem que datacenters de terceiros tenham acesso completo aos dados delas. As organizações adquirem a flexibilidade e a inovação que a nuvem pública fornece ao executar determinadas cargas de
    trabalho na nuvem, mantendo dados altamente confidenciais no datacenter delas para atender às necessidades do cliente ou a requisitos regulatórios.
  - Vantagens:
    - Controle — sua organização pode manter uma infraestrutura privada para ativos confidenciais ou cargas de trabalho que exigem latência baixa.
    - Flexibilidade — você poderá usufruir de recursos adicionais na nuvem pública sempre que precisar deles.
    - Custo-benefício — com a capacidade de escalar para a nuvem pública, você paga por potência de computação adicional somente quando necessário.
    - Facilidade — a transição para a nuvem não precisa ser turbulenta porque você pode migrar gradualmente, passando as cargas de trabalho ao longo do tempo.

--> Comparativo entre CapEx e OpEX:
    - CapEx (Capital Expenditure): 
        Refere-se aos gastos iniciais de capital na infraestrutura de uma empresa, com por exemplo: máquinas, equipamentos,         infraestrutura, etc.
      As despesas do CapEx têm um valor que se reduz ao longo do tempo.
    - OpEx (Operational Expenditure):
        Refere-se aos gastos diários da companhia para manter suas operações, como por exemplo: Salários, aluguel, insumos,         etc., em resumo, são gastos baseados no uso.

  Aplicando esses conceitos em provedores de nuvem, temos um modelo que se baseia no consumo, onde os usuários pagam somente pelos recursos que utilizam.

Benefícios da nuvem:
- Alta Disponibilidade: Este ponto concentra-se em garantir a máxima disponibilidade possível independente de interrupções ou demais eventos. Tais disponibilidades são medidas e controladas por contratos de níveis de serviço (SLA - Service Level Agreement)
- Escalabilidade: Refere-se aos ajustes de recursos conforme a demanda do usuário. Sendo possível aumentar/reduzir  recursos para atender melhor o cenário atual do usuário. Com isso, o usuário arca com os custos do que de fato consumiu. Exemplo: Caso a demanda venha a cair, é reduzido os recursos e assim reduzir os custos. No cenário de um desenvolvimento de uma aplicação, caso necessitasse de mais processamento, poderia atribuir mais CPU, RAM à máquina virtual.
- Elasticidade: Na situação em que seus serviços sejam mais solicitados, seus recursos podem expandir de forma equivalente a fim de atender a crescente demanda, isto pode ser atribuído automaticamente ou manualmente, sendo essa última observável em menos frequência, em cenários específicos e clientes específicos. Da mesma forma em que os recursos podem ser expandidos, podem ser reduzidos diminuindo também o custo. Um exemplo muito prático deste benefício da nuvem é a Black Friday.
- Confiabilidade: A nuvem possui um design mais descentralizado garantindo assim uma estrutura confiável e resiliente, podendo também ter recursos implantados ao redor do mundo. Mesmo que em alguma região haja algum problema com os servidores, seus serviços seguiram disponíveis.
- Previsibilidade: É a capacidade de antecipar e gerenciar com confiança o desempenho e os custos de uma aplicação ou serviço. Na nuvem da Microsoft, este ponto (muito importante) é influenciado pelo Azure Well-Architected Framework que se trata de uma estrutura que fornece princípio orientadores, pontos de decisão arquitetônicos e ferramentas de revisão para projetar e implementar soluções de nuvem de alta qualidade.
- Segurança: A nuvem oferece recursos de segurança que atendem as necessidades dos clientes. Ex.: Serviço de autententicação. Porém, uma parte significativa deve ser realizada pelo cliente, mesmo a infraestrutura oferencendo recursos físicos, o usuário ainda será capaz de gerenciar sistemas operacionais, softwares instalados e atualizações de ambiente. Neste último caso, é possível adotar recursos de SaaS para uma melhor estratégia de nuvem.
- Governança: Neste ponto, será possível identificar e sinalizar quaisquer recursos que estejam em desconformidade com os padrões corporativos e oferece estratégias para a mitigação destes apontamentos. Aqui também podem ser aplicados pacotes de segurança a fim de ajudar na governança e segurança.
Quanto antes adotar medidas de governança, melhor gerido será sua experiência em nuvem garantindo mais segurança e uma boa gestão dela.
- Gerenciabilidade: Este ponto é um dos principais benefícios da computação em nuvem, pois é possível gerenciar seus recursos em nuvem, como por exemplo, escalar automaticamente a implantação de recursos com base na necessidade. Implementando um modelo pré-configurado, é possível remover a necessidade de configuração manual. Em resumo, refere-se à maneira de gerenciar seu ambiente de nuvem e seus recursos, seja tanto por meio de linha de comando quanto por um portal WEB.
------------------------------------------------------------------------------------------------------------------------
--> Iniciando a jornada com o Microsoft Azure:

  Pelo link: "https://azure.microsoft.com", temos a opção de realizar o login caso tenha cadastro ou selecionar dois tipos de cadastro, que são eles:
  -  Conta gratuíta do Azure:
      IMPORTANTE: Disponível SOMENTE para novos clientes
     É ofertado USD 200 para utilizar apenas dentro dos primeiros 30 dias após a criação da conta.
     Dica importante, uma das validações do cadastro do Azure é incluir um cartão de crédito, a dica é utilizar um cartão temporável (que duram 24h) afim de evitar cobranças inesperadas durante o período de teste (lembrando que é de 30 dias).

  -  Conta com pagamento conforme o uso (gerenciabilidade)
      Ideal para clientes que necessitam criar cargas de trabalho.
    
    




























   
