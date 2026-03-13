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

**Ordem de Serviço (O.S.)**

**Ocorrência de Alagamentos**

Joinville enfrenta recorrentes alagamentos e enchentes devido à sua posição geográfica entre morros e bacias hidrográficas, além de fatores urbanos que dificultam o escoamento das águas da chuva. Diante dessa situação, surgiu a necessidade de uma solução que auxilie no monitoramento dessas ocorrências. 
Para isso, foi proposto o desenvolvimento do sistema AQUA, uma aplicação web voltada ao acompanhamento de áreas com risco de alagamento. O sistema utilizará câmeras públicas instaladas em pontos estratégicos da cidade e técnicas de visão computacional para analisar imagens em tempo real e compará-las com registros históricos. Dessa forma, será possível identificar áreas afetadas com maior precisão e disponibilizar informações que auxiliem na prevenção de riscos.

# 2. Situação Problema

A empresa fictícia **AQUA Monitoramento Ambiental** desenvolveu um sistema voltado ao acompanhamento de condições climáticas e ao monitoramento de áreas com risco de alagamento em Joinville. O sistema foi criado com o objetivo de auxiliar a Defesa Civil e a população no acompanhamento de situações de risco relacionadas a chuvas intensas, transbordamento de rios e acúmulo de água em vias urbanas.

O projeto foi idealizado por uma equipe de desenvolvedores interessados em utilizar tecnologia e análise de dados para melhorar a prevenção de desastres naturais nas cidades. O sistema busca reunir informações ambientais e geográficas em uma única plataforma, facilitando o acesso a dados importantes para tomada de decisões em momentos de risco.

---

Atualmente, a **Defesa Civil** enfrenta dificuldades relacionadas ao acompanhamento de áreas com risco de alagamento. Grande parte do trabalho realizado por esses órgãos ainda depende de processos manuais e da consulta a diversas fontes de informação separadas.

Em muitos casos, os profissionais precisam acessar diferentes plataformas para verificar dados meteorológicos, níveis de chuva, condições de rios e registros históricos de enchentes. Essas informações nem sempre estão centralizadas em um único sistema, o que torna o processo de análise mais demorado e complexo.

Além disso, o acompanhamento de ocorrências em tempo real pode exigir a consulta de câmeras públicas, registros de chamados da população e dados meteorológicos atualizados. Como essas informações estão distribuídas em diferentes sistemas ou plataformas, os profissionais responsáveis pelo monitoramento precisam reunir manualmente esses dados para compreender a situação de determinada região.

Esse cenário pode dificultar a identificação rápida de áreas com maior risco de alagamento, especialmente durante períodos de chuvas intensas. A falta de uma visualização centralizada das informações também pode tornar mais difícil o planejamento de ações preventivas ou emergenciais.

Pensando nesses desafios, surgiu a proposta do sistema **AQUA**, que busca reunir diferentes tipos de informações ambientais em uma única plataforma digital. O sistema permite visualizar dados climáticos, acompanhar regiões monitoradas e identificar áreas com maior probabilidade de alagamento por meio de mapas e indicadores.

---

Diante desse contexto, percebe-se que a ausência de ferramentas integradas pode tornar o trabalho de monitoramento ambiental mais lento e complexo para órgãos como a Defesa Civil. A necessidade de consultar diversas fontes de informação e reunir dados manualmente pode dificultar a análise rápida das condições climáticas e dos riscos existentes em determinadas regiões.

Com a utilização do sistema **AQUA**, torna-se possível centralizar informações importantes em uma única plataforma, facilitando a visualização dos dados e o acompanhamento das condições ambientais. Dessa forma, o sistema pode contribuir para melhorar o monitoramento de áreas com risco de alagamento e auxiliar na tomada de decisões em situações de emergência.

# 3. Descrição da proposta

## Proposta de Solução

Diante das dificuldades no monitoramento de áreas com risco de alagamento, propõe-se o desenvolvimento do **AQUA**, um sistema digital que reúne informações em uma única plataforma. O objetivo do software é **auxiliar no acompanhamento de regiões com risco de alagamento**, facilitando o acesso a dados que hoje estão espalhados em diferentes fontes.

O sistema permitirá acompanhar situações de risco por meio de **câmeras públicas localizadas em pontos estratégicos da cidade**, possibilitando a visualização de determinadas áreas em tempo real. Essas imagens serão utilizadas para auxiliar na identificação de possíveis alagamentos e no acompanhamento das condições das ruas.

O **AQUA** terá **dois tipos de usuários**. O primeiro é o **usuário público**, que poderá acessar o sistema para visualizar o mapa com os pontos monitorados, consultar regiões com risco de alagamento e acompanhar as imagens das câmeras disponíveis.

O segundo é o **administrador**, responsável por gerenciar as informações do sistema. Esse usuário poderá **cadastrar pontos de monitoramento, registrar ocorrências e adicionar câmeras utilizadas no acompanhamento das regiões**.

Com o **AQUA**, as informações sobre possíveis alagamentos ficam **centralizadas e mais fáceis de visualizar**, ajudando órgãos como a Defesa Civil no monitoramento das áreas de risco e permitindo que a população tenha acesso a informações importantes sobre a situação das regiões monitoradas.

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

## Entradas

**R.F. 01 – Registro de Usuários:**  
Permite o cadastro de novos usuários no sistema para possibilitar acesso às funcionalidades da plataforma.

Dados necessários: nome, e-mail, data de nascimento, senha.  
Usuários: visitantes.

---

**R.F. 02 – Autenticação de Usuários:**  
Permite que o usuário acesse o sistema utilizando credenciais válidas ou autenticação via conta Google.

Dados necessários: e-mail, senha, conta Google (OAuth).  
Usuários: todos os usuários.

---

**R.F. 03 – Recuperação de Conta:**  
Permite que o usuário recupere o acesso à conta caso esqueça sua senha.

Dados necessários: e-mail.  
Usuários: todos os usuários.

---

**R.F. 04 – Envio de Código de Recuperação:**  
Envia um código de verificação para o e-mail informado durante o processo de recuperação de senha.

Dados necessários: e-mail, código de recuperação, tempo de validade.  
Usuários: sistema.

---

**R.F. 05 – Validação de Código de Recuperação:**  
Verifica se o código de recuperação informado pelo usuário é válido.

Dados necessários: código de recuperação, tempo de validade.  
Usuários: sistema.

---

**R.F. 06 – Indicação de Resultado da Recuperação:**  
Exibe ao usuário o resultado do processo de recuperação de senha.

Dados necessários: status da recuperação.  
Usuários: todos os usuários.

---

**R.F. 07 – Cadastro de Pontos de Alagamento:**  
Permite que administradores registrem pontos de alagamento monitorados no sistema.

Dados necessários: latitude, longitude, cidade, bairro, índice de chuva, umidade do ar, probabilidade, duração do evento, pressão atmosférica, vazão do rio.  
Usuários: administradores.

---

**R.F. 08 – Cadastro de Ocorrências:**  
Permite registrar ocorrências relacionadas a eventos de risco ou alagamento.

Dados necessários: situação, tipo, cidade, bairro.  
Usuários: administradores.

---

**R.F. 09 – Cadastro de Câmeras de Monitoramento:**  
Permite registrar câmeras públicas utilizadas para monitoramento das ruas.

Dados necessários: nome da câmera, latitude, longitude, bairro ou região, status.  
Usuários: administradores.

---

**R.F. 10 – Configuração de Notificações:**  
Permite que administradores configurem alertas de risco para regiões específicas.

Dados necessários: situação, cidade, bairro, descrição.  
Usuários: administradores.

---

**R.F. 11 – Cadastro de Dados Climáticos:**  
Permite registrar dados ambientais coletados para análise de risco.

Dados necessários: precipitação, umidade do ar, pressão atmosférica, vazão do rio.  
Usuários: sistema / administradores.

---

## Processos

**R.F. 12 – Processamento de Dados Climáticos:**  
Analisa dados ambientais e históricos para estimar riscos de alagamento.

Dados necessários: dados climáticos, histórico de alagamentos, altitude.  
Usuários: sistema.

---

**R.F. 13 – Cálculo de Probabilidade de Alagamento:**  
Calcula a probabilidade de ocorrência de alagamentos utilizando modelos de aprendizado de máquina.

Dados necessários: dados climatológicos, dados topográficos, histórico de eventos.  
Usuários: sistema.

---

**R.F. 14 – Classificação de Nível de Criticidade:**  
Classifica o risco conforme níveis de criticidade definidos.

Dados necessários: índice de risco, parâmetros de classificação.  
Usuários: administradores.

---

**R.F. 15 – Confirmação de Alteração de Criticidade:**  
Solicita confirmação antes da alteração de nível de criticidade.

Dados necessários: nível atual, novo nível selecionado.  
Usuários: administradores.

---

**R.F. 16 – Envio de Notificações:**  
Envia alertas aos usuários quando há alteração significativa no nível de risco.

Dados necessários: nível de risco, região, mensagem de alerta.  
Usuários: sistema e administradores.

---

**R.F. 17 – Filtragem de Registros Históricos:**  
Permite aplicar filtros para análise de dados históricos.

Dados necessários: categoria, tipo, bairro, data, situação.  
Usuários: administradores.

---

**R.F. 18 – Processamento de Doações:**  
Processa contribuições financeiras realizadas pelos usuários.

Dados necessários: valor da doação, forma de pagamento, dados do cartão ou Pix.  
Usuários: usuários autenticados.

---

**R.F. 19 – Gerenciamento de Cartões:**  
Permite armazenar e validar dados de cartões utilizados em doações.

Dados necessários: nome do titular, número do cartão, validade, CPF, CVV.  
Usuários: usuários autenticados.

---

**R.F. 20 – Confirmação de Pagamento:**  
Apresenta tela de confirmação antes da finalização da doação.

Dados necessários: valor, forma de pagamento, dados do cartão mascarados.  
Usuários: usuários autenticados.

---

**R.F. 21 – Geração de QR Code Pix:**  
Gera código e QR Code para pagamento via Pix.

Dados necessários: valor, código Pix, tempo de validade.  
Usuários: usuários autenticados.

---

**R.F. 22 – Gerenciamento de Perfil:**  
Permite que o usuário visualize e edite seus dados pessoais.

Dados necessários: nome, e-mail, data de nascimento, senha, foto de perfil.  
Usuários: usuários autenticados.

---

**R.F. 23 – Exclusão de Conta:**  
Permite que o usuário exclua sua conta permanentemente.

Dados necessários: confirmação de exclusão.  
Usuários: usuários autenticados.

---

## Saídas

**R.F. 24 – Visualização do Mapa Interativo:**  
Exibe mapa contendo pontos de alagamento monitorados.

Dados necessários: latitude, longitude, bairro, probabilidade, duração do evento.  
Usuários: todos os usuários.

---

**R.F. 25 – Visualização de Gráficos Climáticos:**  
Apresenta gráficos com indicadores ambientais.

Dados necessários: precipitação, vazão do rio, umidade do ar, pressão atmosférica.  
Usuários: administradores.

---

**R.F. 26 – Visualização de Previsões Climáticas:**  
Permite visualizar previsões para diferentes intervalos de tempo.

Dados necessários: intervalo de previsão, dados climáticos.  
Usuários: administradores.

---

**R.F. 27 – Visualização de Dashboard:**  
Exibe indicadores gerais de monitoramento em tempo real.

Dados necessários: indicadores climáticos, níveis de risco, alertas ativos.  
Usuários: administradores.

---

**R.F. 28 – Visualização de Histórico:**  
Permite consultar registros históricos de eventos monitorados.

Dados necessários: data, categoria, bairro, tipo de evento.  
Usuários: administradores.

---

**R.F. 29 – Visualização de Lista de Pontos:**  
Exibe lista de pontos monitorados com resumo das informações.

Dados necessários: bairro, probabilidade, duração do evento.  
Usuários: administradores.

---

**R.F. 30 – Visualização de Probabilidade de Alagamento:**  
Apresenta em tempo real o nível de risco em determinada região.

Dados necessários: região, índice de risco, nível de criticidade.  
Usuários: todos os usuários.

---

**R.F. 31 – Visualização de Câmeras:**  
Permite visualizar imagens de câmeras públicas em tempo real.

Dados necessários: identificação da câmera, localização, imagem.  
Usuários: todos os usuários.

---

**R.F. 32 – Visualização de Informações das Câmeras:**  
Apresenta dados básicos de cada câmera monitorada.

Dados necessários: nome da câmera, bairro, região.  
Usuários: todos os usuários.

---

**R.F. 33 – Visualização de Blog:**  
Exibe publicações informativas sobre enchentes.

Dados necessários: título, imagem, resumo.  
Usuários: todos os usuários.

---

**R.F. 34 – Exibição de Publicações Populares:**  
Apresenta as publicações mais acessadas no blog.

Dados necessários: número de acessos, título da publicação.  
Usuários: todos os usuários.

---

**R.F. 35 – Visualização da Página Sobre Nós:**  
Exibe informações institucionais sobre a equipe e objetivos do projeto.

Dados necessários: texto institucional, integrantes da equipe.  
Usuários: todos os usuários.

---

**R.F. 36 – Exibição de Ícones de Nível de Risco:**  
Apresenta cores e ícones no mapa para representar níveis de criticidade.

Dados necessários: nível de risco, cores, ícones.  
Usuários: todos os usuários.

---

**R.F. 37 – Busca de Regiões no Mapa:**  
Permite pesquisar regiões ou pontos monitorados.

Dados necessários: nome da região ou bairro.  
Usuários: todos os usuários.

---

**R.F. 38 – Exibição de Perfil do Usuário:**  
Mostra foto de perfil e nome do usuário autenticado.

Dados necessários: nome, foto de perfil.  
Usuários: usuários autenticados.

---

**R.F. 39 – Acesso à Página de Perfil:**  
Permite acessar a página com dados pessoais do usuário.

Dados necessários: dados do usuário.  
Usuários: usuários autenticados.

---

**R.F. 40 – Visualização de Dados da Conta:**  
Exibe informações completas da conta do usuário.

Dados necessários: nome, e-mail, data de nascimento, data de criação da conta.  
Usuários: usuários autenticados.

---

**R.F. 41 – Acesso ao Dashboard:**  
Permite acessar a área principal de monitoramento do sistema.

Dados necessários: dados de monitoramento.  
Usuários: usuários autenticados.

---

**R.F. 42 – Acesso à Página de Segurança:**  
Permite acessar área de gerenciamento da conta.

Dados necessários: dados da conta do usuário.  
Usuários: usuários autenticados.

---

**R.F. 43 – Edição de Dados Pessoais:**  
Permite alterar dados cadastrais do usuário.

Dados necessários: nome, e-mail, data de nascimento.  
Usuários: usuários autenticados.

---

**R.F. 44 – Alteração de Senha:**  
Permite alterar a senha da conta mediante validação da senha atual.

Dados necessários: senha atual, nova senha, confirmação da senha.  
Usuários: usuários autenticados.

---

**R.F. 45 – Confirmação de Ações Críticas:**  
Solicita confirmação antes de ações importantes no sistema.

Dados necessários: ação solicitada, confirmação do usuário.  
Usuários: usuários autenticados.

---

**R.F. 46 – Exclusão Permanente de Conta:**  
Permite excluir permanentemente a conta do usuário após confirmação.

Dados necessários: confirmação de exclusão.  
Usuários: usuários autenticados.

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
