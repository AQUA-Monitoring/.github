# Projeto Integrador - Modelo

_AQUA: Monitoramento de câmeras públicas e dados hidrometeorológicos no apoio à gestão de alagamentos urbanos. 🌧️_

---

## 1. Contexto e Problema

Joinville enfrenta recorrentes **alagamentos e enchentes**, resultado de sua **posição geográfica entre morros e bacias hidrográficas**, além de fatores urbanos que **dificultam o escoamento das águas pluviais**.  
Nos últimos anos, **eventos hidrológicos extremos** têm se tornado mais frequentes — especialmente no verão — trazendo **desafios à gestão urbana**, à **tomada de decisões preventivas** e à **mitigação de riscos**.

---

## 💡 2. Proposta da Solução

A proposta consiste no **desenvolvimento de uma aplicação web** voltada ao **monitoramento em tempo real de alagamentos**.  
A solução integra **câmeras públicas localizadas em pontos estratégicos**, aplicando **visão computacional**, **aprendizado de máquina** e **reconhecimento de padrões** para **comparar imagens em tempo real com registros históricos**, identificando **áreas afetadas com maior precisão**.

---

Professor: [Marco André Mendes](github.com/marcoandre)

Equipe:

- [Bianca Isadora Joselli de Souza](https://github.com/BiancaJoselli)
- [Helena Soares Pereira](https://github.com/helenasoaresp)
- [Matheus Miguel Michalski](https://github.com/matheusmichalski)
- [Nicole Ferreira Melo](https://github.com/nicolefemello)
- [Rafael August Otto](https://github.com/rafael-otto)
- [Vitor André da Silva](https://github.com/VitorAndreSilva)

Links do projeto:

- Backend: [Repositório](https://github.com/AQUA-Monitoring/hackathon_backend) e [Publicação](https://aqua.fabricadesoftware.ifc.edu.br/)
- Frontend: [Repositório](https://github.com/AQUA-Monitoring/hackathon_frontend) e [Publicação](http://aquaapi.fabricadesoftware.ifc.edu.br/)
- [Requisitos](https://docs.google.com/document/d/1A_C9lhOZsPZwYGqqcZxbWc6av3OE1GLHt0uzGKmLIPI/edit?tab=t.3zpt241go3s)
- [Regras de Negócio](https://docs.google.com/document/d/1A_C9lhOZsPZwYGqqcZxbWc6av3OE1GLHt0uzGKmLIPI/edit?tab=t.3zpt241go3s)

# 1. Desenvolvimento

**1.1 Modelos de Sistemas**

**1.1.3 Ordem de Serviço (O.S.)**

**Ocorrência de Alagamentos**

Joinville enfrenta recorrentes alagamentos e enchentes devido à sua posição geográfica entre morros e bacias hidrográficas, além de fatores urbanos que dificultam o escoamento das águas da chuva. Diante dessa situação, surgiu a necessidade de uma solução que auxilie no monitoramento dessas ocorrências. 
Para isso, foi proposto o desenvolvimento do sistema AQUA, uma aplicação web voltada ao acompanhamento de áreas com risco de alagamento. O sistema utilizará câmeras públicas instaladas em pontos estratégicos da cidade e técnicas de visão computacional para analisar imagens em tempo real e compará-las com registros históricos. Dessa forma, será possível identificar áreas afetadas com maior precisão e disponibilizar informações que auxiliem na prevenção de riscos.
# 2. Situação Problema

_(Nessa parte a equipe deve descrever a situação problema que será resolvida pelo sistema. O texto abaixo descreve o que essa etapa deve conter e pode ser apagado depois.)_

![Ciclo da Venda](docs/ciclo_da_venda.webp "Ciclo da Venda")

Descrevem o que acontece atualmente na empresa em um contexto global,
abordando o funcionamento da empresa como um todo, não apenas os “problemas” que lá ocorrem.

Sabendo disso, seu papel é **detalhar o funcionamento da empresa escolhida na
atualidade, ou seja, antes de seu novo software**, usando como base a situação que passamos, mas aprofundando os detalhes de como as coisas acontecem.

- Pesquise sobre empresas do ramo escolhido
  para entender como funcionam;
- Aproveite seus conhecimentos previamente adquiridos na área da empresa que escolheu, se houver;
- Simule uma situação real. Lembre-se que são propostas com empresas fictícias, sendo assim, você terá que tomar certas decisões sobre como a empresa funciona em relação às coisas que não estão definidas no documento base (por exemplo, no caso da padaria, dizemos que seu Genival contratou mais funcionários, mas saber quantos e o que fazem pode ser relevante para o software), então tente “visualizar” a empresa funcionando, como se você estivesse lá acompanhando o dia-a-dia;

Seguindo essas dicas, você deve ser capaz de descrever o dia-a-dia da empresa selecionada. E para ajudar na organização do texto, indicamos uma abordagem em 3 etapas:

- **Introdução**: comece com um parágrafo apresentando a empresa (nome, o que faz, tempo de existência, o dono, funcionários, etc);
- **Situação-problema**: Aborde em detalhes como a empresa funciona, procurando seguir uma ordem lógica dos acontecimentos e organizando parágrafos diferentes para cada coisa diferente que for explicar (como faria em uma redação);
- **Conclusão**: tenha um parágrafo de conclusão focando nos problemas que você notou dentro da situação problema analisada e aponte brevemente como um software poderia ajudar a resolvê-los.

# 3. Descrição da proposta

Após entender o problema, proponha uma solução que será útil nos aspectos de dificuldade encontrados. Assim, aqui você deverá **explicar de maneira resumida, e preferencialmente mais textual, como o software funcionará**. Pense nesse texto como uma **introdução ao seu cliente** do que você pretende fazer por ele, para que ele confirme se realmente está dentro do desejado e permita sua continuidade.

**Alguns pontos importantes a se destacar são:**

- **Qual o foco de ação do software** relacionado com os problemas levantados na análise da situação-problema. O que realmente o software vai fazer. Por exemplo, o foco de ação do Gmail é permitir o envio e recebimento de e-mails.
- **Os níveis de usuário do sistema**. Somente o gestor tem acesso? E os funcionários? Talvez seja para ambos, ou para funcionários de cargos
  diferentes, etc.
- **O que poderá ser feito no software**.Apenas o principal, sem pensar em telas ou detalhes específicos, pois isso será feito em outro momento.
- **Se houver mais de um nível de usuário**, ressaltar as diferenças entre eles na descrição da proposta.

Tenha em mente que essa é uma etapa relativamente breve. Não é necessário um texto gigantesco, apenas dar uma noção do funcionamento do sistema. Mais adiante
precisaremos ser bem detalhistas, todavia agora a intenção é apenas fazer algo que permita ao cliente nos dizer se estamos no caminho certo.

# 4. Modelagem de Dados

A modelagem de dados do sistema **AQUA** foi definida por meio de um Diagrama Entidade-Relacionamento (DER), que representa as principais entidades do sistema e seus relacionamentos.

A entidade **User** armazena os dados dos usuários da plataforma, enquanto **Address** registra as informações de localização associadas a usuários, organizações e câmeras. A entidade **NGO** representa organizações que podem atuar em ações de apoio à população.

O sistema também possui as entidades **Camera** e **Flood_Point**, responsáveis por registrar as câmeras utilizadas no monitoramento e os pontos de alagamento identificados. As entidades **Neighborhood** e **Region** organizam as informações geográficas da cidade.

Além disso, o sistema registra dados meteorológicos por meio das entidades **Weather** e **Forecast**, que armazenam informações climáticas e previsões do tempo. As entidades **Protocol**, **Response** e **Occurrence** são utilizadas para registrar ocorrências e ações relacionadas a eventos monitorados.

Por fim, **Notification** armazena notificações geradas pelo sistema e **Donation** registra doações realizadas, incluindo o tipo de pagamento armazenado em **Payment_Type**.

# 4. Regras de negócio

**RN01** – O sistema deve permitir o cadastro de usuários com nome, e-mail, data de nascimento e senha.

**RN02** – Apenas usuários administradores poderão acessar funções de gerenciamento do sistema.

**RN03** – O cadastro, edição e remoção de pontos de monitoramento será restrito a usuários administradores.

**RN04** – Cada ponto de monitoramento deve possuir coordenadas geográficas válidas (latitude e longitude).

**RN05** – Os pontos monitorados devem estar localizados dentro da região de Joinville ou áreas próximas.

**RN06** – O sistema deve registrar dados climáticos associados a cada ponto monitorado.

**RN07** – Os dados climáticos devem incluir informações como precipitação, umidade do ar, pressão atmosférica e vazão do rio.

**RN08** – O sistema deve armazenar o histórico de registros de monitoramento para consultas futuras.

**RN09** – A visualização completa do histórico de registros será restrita a usuários administradores.

**RN10** – O sistema deve calcular a probabilidade de alagamento com base em dados ambientais e históricos.

**RN11** – A probabilidade de alagamento será gerada por um modelo de aprendizado de máquina.

**RN12** – O sistema deve atualizar periodicamente os indicadores de risco de alagamento.

**RN13** – Cada ponto monitorado deve possuir um índice de risco de alagamento associado.

**RN14** – O sistema deve classificar o nível de risco conforme níveis de criticidade definidos.

**RN15** – Os níveis de criticidade disponíveis devem ser: Crise, Alerta, Atenção, Mobilização e Normalidade.

**RN16** – O sistema deve gerar notificações quando o índice de risco ultrapassar limites estabelecidos.

**RN17** – As notificações devem estar associadas a regiões ou pontos monitorados.

**RN18** – O sistema deve registrar o histórico de notificações enviadas.

**RN19** – Os usuários poderão ativar ou desativar o recebimento de notificações por e-mail.

**RN20** – O sistema deve monitorar alterações nos indicadores de risco em tempo real.

**RN21** – O sistema deve permitir o registro de ocorrências relacionadas a eventos de alagamento.

**RN22** – Cada ocorrência deve possuir informações de localização e situação do evento.

**RN23** – O sistema deve integrar dados provenientes de câmeras públicas para apoio ao monitoramento.

**RN24** – As câmeras cadastradas devem possuir identificação, localização e status de funcionamento.

**RN25** – O sistema deve registrar estatísticas de acesso e consulta aos dados de monitoramento.

# 5. Requisitos funcionais

(_Nessa parte a equipe deve descrever os requisitos funcionais que serão implementados no sistema. O texto abaixo descreve o que essa etapa deve conter e pode ser apagado depois._)

**5.1 O que são requisitos funcionais?**

Um requisito funcional é uma declaração de como um sistema deve se comportar. Define o que o sistema deve fazer para atender às necessidades ou expectativas do usuário. Os requisitos funcionais podem ser pensados ​como recursos que o usuário detecta.

Os requisitos funcionais são compostos de duas partes:
**função** e **comportamento**.

- A **função** é o que o sistema **faz**. Por exemplo: _“calcular imposto sobre vendas”_.
- O **comportamento** é **como** o sistema faz. Por exemplo: _“O sistema deve calcular o imposto sobre vendas multiplicando o preço de compra pela alíquota do imposto.”_.

**5.2 Tipos de requisitos funcionais**

Os requisitos funcionais podem ser classificados em:

- Regulamentos de Negócios
- Requisitos de Certificação
- Requisitos de relatório
- Funções Administrativas
- Níveis de autorização
- Rastreamento de auditoria
- Interfaces Externas
- Gestão de dados
- Requisitos Legais e Regulamentares

**5.3 Diretrizes para a elaboração de requisitos funcionais**

Cada requisito funcional precisa ser:

- **Específico** sobre o que o sistema deve fazer.
- **Mensurável** para que você possa dizer se o sistema está fazendo isso
- **Alcançável** dentro do prazo que você definiu
- **Relevante** para seus objetivos de negócios
- **Limitado** no tempo para que você possa
  acompanhar o progresso

**5.4 Estrutura do requisito funcional**

Um requisito funcional deve ser estruturado da seguinte forma:

- **Nome do requisito funcional:** descrição do
  requisito.
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

**5.4.1 Nome do requisito funcional**

**R.F. 99 - Nome do requisito funcional:** é o nome da função que o software terá. Sugerimos, por padronização, que tenha o prefixo R.F. (requisito funcional)
seguida da numeração, para melhor identificação do requisito, acrescido do formato _“Substantivo + onde será feita a ação”_.
Por exemplo:

- R.F. 01 - Registro de Funcionários
- R.F. 15 - Gerenciamento de consultas
- R.F. 04 - Débito em conta corrente

Deixe para definir as numerações ao final, tendo em vista que mudanças podem acontecer e não é prático sempre ficar reajustando os números.

**5.4.2 Descrição do requisito funcional**

**Descrição do requisito:** local para descrever a função deste requisito.

Sempre se preocupe em esclarecer dois pontos: o que o requisito faz e o motivo de sua existência. Isso é especialmente importante se a ação executada nesse requisito não for algo que já acontece naturalmente na empresa.
Um exemplo é um Registro de funcionários, que talvez não exista hoje mas para o software é necessário para viabilizar uma autenticação de
usuários. Outro exemplo é algo que faz sentido apenas para um software, como a própria autenticação.

**5.4.3 Dados necessários**

**Dados necessários:** aqui devem ser colocados os nomes dos dados que serão usados para que esse requisito atenda o que precisa fazer.

Nas **entradas** e **processos**, em geral, são os dados que serão salvos (seja algo digitado pelo usuário ou captado do sistema, como a hora atual).

Já nas **saídas**, são os dados que serão exibidos em tela (sejam eles vindos diretamente do banco, ou criados por um cálculo ou busca na sessão do usuário).

**5.4.4 Usuários**

**Usuários:** aqui devem ser colocados os nomes dos usuários que terão acesso a esse requisito, conforme enumerados na descrição do sistema.

**5.4.5 Exemplo de requisito funcional**

- **R.F. 01 - Autenticação de usuário:** tem como propósito autenticar o acesso ao sistema, verificando se o usuário pode acessá-lo e, caso possa, o direcionando
  para a página principal de seu perfil de acesso.
  - **Dados necessários:** login, senha, nível de permissão.
  - **Usuários:** todos os níveis de usuário.

**5.4.6 Organização dos requisitos funcionais**

As funcionalidades devem ser organizadas em: entradas, processos e saídas.

**Entradas:** São as funcionalidades que alimentarão o software com as informações essenciais para seu uso.

**Exemplos de entradas:**

- “**Registro de usuário**” (para permitir depois seu acesso ao software).
- “**Registro de paciente**” (que seria útil caso nosso software fosse ppara uma clínica, evitando registrar várias vezes os mesmos dados da pessoa a cada consulta e viabilizando um histórico de seus
  atendimentos).

**Processos:** Em geral, englobam toda ação que executa cálculos, processamentos de tomada de decisão ou transforma dados em novos dados.

**Exemplos de processos:**

- “**Autenticação de usuário**”, que usará os dados de “**Registro de usuário**” em sua execução.
- “**Agendamento de consulta**”, que usará dados do “**Registro de paciente**” e talvez do “**Registro de funcionário**” em sua execução.

**Saídas:** São os relatórios, gráficos, impressões, etc., que utilizarem os dados do software para gerar informações pertinentes ao
negócio, mas sem intenção de alterá-los, apenas permitindo sua visualização e filtragem.

**Exemplos de saídas:**

- “Relatório de consultas por paciente”.
- Relatório de vendas”.
- “Log de usuários autenticados”.

Todos esses podem ser consideradas saídas, pois usam informações de entradas e processos de modo a mostrar informações relevantes ao
negócio. Lembre-se que, diferentemente das entradas e processos, aqui os dados necessários devem ser os que a tela exibirá.

**5.4.7 Exemplo de organização dos requisitos funcionais**

(_A seguir, um exemplo de organização de requisitos funcionais, com entradas, processos e saídas._)

**Entradas:**

- **R.F. 01 - Nome do requisito funcional:** descrição do requisito.
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

- **R.F. 02 - Nome do requisito funcional:** descrição do requisito.
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

**Processamento:**

- **R.F. 03 - Nome do requisito funcional:** descrição do requisito.
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

- **R.F. 04 - Nome do requisito funcional:** descrição do requisito.
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

**Saídas:**

- **R.F. 05 - Nome do requisito funcional:** descrição do requisito.
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

- **R.F. 06 - Nome do requisito funcional:** descrição do requisito.
  - **Dados necessários:** dado 1, dado 2, dado 3.
  - **Usuários:** todos os níveis de usuário.

# 6. Requisitos não funcionais

**RNF001** – O sistema deve armazenar senhas de forma criptografada, utilizando algoritmo seguro (ex.: bcrypt ou Argon2).

**RNF002** – O sistema deve utilizar protocolo HTTPS em todas as requisições para garantir a confidencialidade e integridade dos dados transmitidos.

**RNF003** – O sistema deve carregar a página inicial em até 5 segundos em condições normais de rede.

**RNF004** – O sistema deve estar disponível 24 horas por dia, 7 dias por semana, com no mínimo 99% de uptime mensal.

**RNF005** – O sistema deve realizar backups automáticos semanais do banco de dados.

**RNF006** – O sistema deve ser responsivo e se adaptar automaticamente a diferentes resoluções de tela (desktop, tablet e mobile).  
Responsável: Nicole (Vue)

**RNF007** – O sistema deve disponibilizar interface intuitiva, priorizando navegação simplificada e conteúdo objetivo.  
Responsáveis: Rafael, Bianca e Nicole (Figma e Vue)

**RNF008** – O sistema deve ser desenvolvido utilizando Clean Architecture e Domain Driven Design, permitindo fácil manutenção e expansão.  
Responsáveis: Vitor, Matheus e Nicole (Vue e Django)

**RNF009** – O sistema deve manter logs de erros e acessos, permitindo auditoria e monitoramento.

# 7. Diagrama de Caso de Uso

**7.1 Introdução**

O diagrama de caso de uso é uma ferramenta de modelagem que descreve o comportamento de um sistema a partir da perspectiva do usuário. Ele é usado para capturar os requisitos funcionais de um sistema.

- Especificam a visão externa do sistema.
- Descrevem como o sistema é percebido por seus usuários.
- Descrevem as interações entre os usuários e o sistema.

![Diagrama de Caso de Uso](img/dcu1.png "Diagrama de Caso de Uso")

**Os casos de uso:**

- Descrevem como os **usuários interagem com o sistema** (as funcionalidades do sistema)
- Facilitam a **organização dos requisitos** de um sistema.
- Dão uma **visão externa** do sistema
- O conjunto de casos de uso deve ser capaz de comunicar a **funcionalidade** e o **comportamento** do sistema para o cliente.
- Descrevem **o que** o sistema faz, mas **não** especificam **como** isso deve ser feito.

**7.2 Elementos do diagrama de caso de uso**

7.2.1 **Atores**

- Representam os papéis desempenhados por **elementos externos** ao sistema
  - Ex: humano (usuário), dispositivo de hardware ou outro sistema (cliente)
- Elementos que **interagem** com o sistema

Notação:

![Atores Notação](img/dcu_atores_notacao.png "Atores Notação")

**Exemplo: Loja de CDs**

**Identificando os atores**

- Uma loja de CDs possui discos para venda. Um cliente pode comprar uma quantidade ilimitada de discos para isto ele deve se dirigir à loja.
- A loja possui um **atendente** cuja função é atender os clientes durante a venda dos discos. A loja também possui um **gerente** cuja função é administrar o estoque para que não faltem discos. Além disso é ele quem dá folga ao atendente, ou seja, ele também atende os clientes durante a venda dos discos.

![Identificando os atores](img/dcu_identificando_atores.png "Identificando os atores")

**E o cliente?**

- Não é ator pois ele **não interage** com o sistema!

**7.2.2 Casos de uso**

- Representam **funcionalidades** do sistema (requisitos funcionais).
- São iniciados por **atores** ou por outros casos de uso.

> **Dica**: nomeie os casos de uso com **verbos** no **infinitivo**.

Notação:

![Casos de uso Notação](img/dcu_casos_de_uso_notacao.png "Casos de uso Notação")

**Exemplo: Loja de CDs**

**Identificando os casos de uso**

- Uma loja de CDs possui discos para venda. Um cliente pode comprar uma quantidade ilimitada de discos para isto ele deve se dirigir à loja. A loja possui um atendente cuja função é atender os clientes durante a **venda dos discos**.
- A loja também possui um gerente cuja função é **administrar o estoque** para que não faltem discos. Além disso é ele quem dá folga ao atendente, ou seja, ele também atende os clientes durante a **venda dos discos**.

![Identificando os casos de uso](img/dcu_identificando_casos_de_uso.png "Identificando os casos de uso")

**7.2.3 Relacionamentos**

**7.2.3.1 Relacionamento de associação**

- Indica que um ator **participa** de um caso de uso, ou seja, o ator **interage** (comunica-se) com o caso de uso.
- É representado por uma **linha sólida**.
- Um ator pode se relacionar com **um ou mais casos de uso**.

> Dicas:
>
> - Não use setas nas linhas de associação.
> - Associações não representam fluxo de informação.

![Relacionamento de associação](img/dcu_relacionamento_de_associacao.png "Relacionamento de associação")

**Exemplo: Loja de CDs**

**Identificando os relacionamentos de associação**

- Uma loja de CDs possui discos para venda. Um cliente pode comprar uma quantidade ilimitada de discos para isto ele deve se dirigir à loja. A loja possui um _atendente_ cuja função é atender os clientes durante a **venda dos discos**.
- A loja também possui um _gerente_ cuja função é **administrar o estoque** para que não faltem discos. Além disso é ele quem dá folga ao _atendente_, ou seja, ele também atende os clientes durante a **venda dos discos**.

![Identificando os relacionamentos de associação](img/dcu_identificando_relacionamentos_de_associacao.png "Identificando os relacionamentos de associação")

**7.2.3.2 Relacionamento de generalização/especialização**

**Generalização de atores**

- Quando dois ou mais atores podem se **comunicar com o mesmo conjunto de casos de uso**.
- Indica que um ator **herda** as características de outro ator.
  – Um filho (herdeiro) pode se comunicar com todos os casos de uso que seu pai se comunica.

> **Dica:** coloque os herdeiros **embaixo**.

**Notação:**

![Relacionamento de generalização/especialização de atores - notação](img/dcu_relacionamento_de_generalizacao_especializacao_notacao_de_atores.png "Relacionamento de generalização/especialização de atores - notação")

**Exemplo: Loja de CDs**

**Identificando os relacionamentos de generalização/especialização de atores**

![Identificando os relacionamentos de generalização/especialização de atores](img/dcu_identificando_relacionamentos_de_generalizacao_especializacao_de_atores.png "Identificando os relacionamentos de generalização/especialização de atores")

**Generalização de casos de uso**

– O caso de uso filho herda o comportamento e o significado do caso de uso pai.
– O caso de uso filho pode incluir ou sobrescrever o comportamento do caso de uso pai.
– O caso de uso filho pode substituir o caso de uso pai em qualquer lugar que ele apareça.

> **Dica:** deve ser aplicada quando uma condição resulta na definição de
> diversos fluxos alternativos.

Notação:

![Relacionamento de generalização/especialização de casos de uso - notação](img/dcu_relacionamento_de_generalizacao_especializacao_notacao_de_casos_de_uso.png "Relacionamento de generalização/especialização de casos de uso - notação")

**Exemplo: Loja de CDs**

**Identificando os relacionamentos de generalização/especialização de casos de uso**

**Novos requisitos:**

- As vendas podem ser **à vista** ou **a prazo**. Em ambos os casos o estoque é
  atualizado e uma nota fiscal, entregue ao consumidor.
- No caso de uma **venda à vista**, clientes cadastrados na loja e que compram mais de 5 CDs de uma só vez ganham um desconto de 1% para cada ano de cadastro.
- No caso de uma **venda a prazo**, ela pode ser parcelada em 2 pagamentos com um
  acréscimo de 20%. As vendas a prazo podem ser pagas no **cartão** ou no **boleto**.
  - Para pagamento com **boleto**, são gerados boletos bancários que são entregues ao cliente e armazenados no sistema para lançamento posterior no caixa.
  - Para pagamento com **cartão**, os clientes com mais de 10 anos de cadastro na loja ganham o mesmo desconto das compras à vista.

![Identificando os relacionamentos de generalização/especialização de casos de uso](img/dcu_identificando_relacionamentos_de_generalizacao_especializacao_de_casos_de_uso.png "Identificando os relacionamentos de generalização/especialização de casos de uso")

**Identificando mais relacionamentos de generalização/especialização de casos de uso**

![Identificando mais relacionamentos de generalização/especialização de casos de uso](img/dcu_identificando_mais_relacionamentos_de_generalizacao_especializacao_de_casos_de_uso.png "Identificando mais relacionamentos de generalização/especialização de casos de uso")

**7.2.3.3 Relacionamento de dependência**

**Extensão**

- Representa uma variação/extensão do comportamento do caso de uso base.
- O caso de uso estendido só é executado sob certas circunstâncias.
- Separa partes obrigatórias de partes opcionais.
  - Partes obrigatórias: caso de uso base.
  - Partes opcionais: caso de uso estendido.
- Fatorar comportamentos variantes do sistema (podendo reusar este comportamento
  em outros casos de uso).

**Notação:**

![Relacionamento de dependência (extensão) - notação](img/dcu_relacionamento_de_dependencia_extensao_notacao.png "Relacionamento de dependência (extensão) - notação")

**Exemplo: Loja de CDs**

**Identificando os relacionamentos de dependência (extensão)**

**Novos requisitos:**

- No caso de uma venda à vista, clientes cadastrados na loja e que compram mais
  de 5 CDs de uma só vez ganham um **desconto** de 1% para cada ano de cadastro.
- No caso de uma venda a prazo...
  - ...Para pagamento com cartão, os clientes com mais de 10 anos de cadastro na loja ganham o mesmo **desconto** das compras à vista.

![Identificando os relacionamentos de dependência (extensão)](img/dcu_identificando_relacionamentos_de_dependencia_extensao.png "Identificando os relacionamentos de dependência (extensão)")

**Inclusão**

- Evita repetição ao fatorar uma atividade
  comum a dois ou mais casos de uso.
- Um caso de uso pode incluir vários casos de uso.

**Notação:**

![Relacionamento de dependência (inclusão) - notação](img/dcu_relacionamento_de_dependencia_inclusao_notacao.png "Relacionamento de dependência (inclusão) - notação")

**Exemplo: Loja de CDs**

**Novos requisitos:**
Para efetuar vendas ou administrar estoque, atendentes e gerentes terão que **validar** suas respectivas senhas de
acesso ao sistema.

![Identificando os relacionamentos de dependência (inclusão)](img/dcu_identificando_relacionamentos_de_dependencia_inclusao.png "Identificando os relacionamentos de dependência (inclusão)")

**7.2.4 Fronteira do sistema**

- Elemento opcional (mas essencial para um bom
  entendimento).
- Serve para definir a área de atuação do sistema, ou seja, seus limites.

**Identificando a fronteira do sistema**

![Identificando a fronteira do sistema](img/dcu_identificando_a_fronteira_do_sistema.png "Identificando a fronteira do sistema")

---
