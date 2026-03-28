# Projeto Integrador - Modelo

_AQUA: Monitoramento de câmeras públicas e dados hidrometeorológicos no apoio à gestão de alagamentos urbanos. 🌧️_

## 1. Contexto e Problema

Joinville enfrenta recorrentes **alagamentos e enchentes**, resultado de sua **posição geográfica entre morros e bacias hidrográficas**, além de fatores urbanos que **dificultam o escoamento das águas pluviais**.  
Nos últimos anos, **eventos hidrológicos extremos** têm se tornado mais frequentes — especialmente no verão — trazendo **desafios à gestão urbana**, à **tomada de decisões preventivas** e à **mitigação de riscos**.

## 💡 2. Proposta da Solução

A proposta consiste no **desenvolvimento de uma aplicação web** voltada ao **monitoramento em tempo real de alagamentos**.  
A solução integra **câmeras públicas localizadas em pontos estratégicos**, aplicando **visão computacional**, **aprendizado de máquina** e **reconhecimento de padrões** para **comparar imagens em tempo real com registros históricos**, identificando **áreas afetadas com maior precisão**.

Professor: [Marco André Mendes](github.com/marcoandre)

Equipe:

- [Bianca Isadora Joselli de Souza](https://github.com/BiancaJoselli)
- [Helena Soares Pereira](https://github.com/helenasoaresp)
- [Matheus Miguel Michalski](https://github.com/matheusmichalski)
- [Nicole Ferreira Melo](https://github.com/nicolefemello)
- [Rafael August Otto](https://github.com/rafael-otto)
- [Vitor André da Silva](https://github.com/VitorAndreSilva)

Links do projeto:

- Backend: [Repositório](https://github.com/AQUA-Monitoring/hackathon_backend) e [Publicação](http://api.aqua.michalski.app/)
- Frontend: [Repositório](https://github.com/AQUA-Monitoring/hackathon_frontend) e [Publicação](http://aqua.michalski.app/)

# 1. Desenvolvimento

**Ordem de Serviço (O.S.)**

**Ocorrência de Alagamentos**

Joinville enfrenta recorrentes alagamentos e enchentes devido à sua posição geográfica entre morros e bacias hidrográficas, além de fatores urbanos que dificultam o escoamento das águas da chuva. Diante dessa situação, surgiu a necessidade de uma solução que auxilie no monitoramento dessas ocorrências.
Para isso, foi proposto o desenvolvimento do sistema AQUA, uma aplicação web voltada ao acompanhamento de áreas com risco de alagamento. O sistema utilizará câmeras públicas instaladas em pontos estratégicos da cidade e técnicas de visão computacional para analisar imagens em tempo real e compará-las com registros históricos. Dessa forma, será possível identificar áreas afetadas com maior precisão e disponibilizar informações que auxiliem na prevenção de riscos.

# 2. Situação Problema

A empresa fictícia **AQUA Monitoramento Ambiental** desenvolveu um sistema voltado ao acompanhamento de condições climáticas e ao monitoramento de áreas com risco de alagamento em Joinville. O sistema foi criado com o objetivo de auxiliar a Defesa Civil e a população no acompanhamento de situações de risco relacionadas a chuvas intensas, transbordamento de rios e acúmulo de água em vias urbanas.

O projeto foi idealizado por uma equipe de desenvolvedores interessados em utilizar tecnologia e análise de dados para auxiliar na prevenção de alagementos na cidade.

Atualmente, a **Defesa Civil** enfrenta dificuldades relacionadas ao acompanhamento de áreas com risco de alagamento. Grande parte do trabalho realizado por esses órgãos ainda depende de processos manuais e da consulta a diversas fontes de informação separadas.

Em muitos casos, os profissionais precisam acessar diferentes plataformas para verificar dados meteorológicos, níveis de chuva, condições de rios e registros históricos de enchentes. Essas informações nem sempre estão centralizadas em um único sistema, o que torna o processo de análise mais demorado e complexo.

Além disso, o acompanhamento de ocorrências em tempo real pode exigir a consulta de câmeras públicas, registros de chamados da população e dados meteorológicos atualizados. Como essas informações estão distribuídas em diferentes sistemas ou plataformas, os profissionais responsáveis pelo monitoramento precisam reunir manualmente esses dados para compreender a situação de determinada região.

Esse cenário pode dificultar a identificação rápida de áreas com maior risco de alagamento, especialmente durante períodos de chuvas intensas. A falta de uma visualização centralizada das informações também pode tornar mais difícil o planejamento de ações preventivas ou emergenciais.

Pensando nesses desafios, surgiu a proposta do sistema **AQUA**, que busca reunir diferentes tipos de informações ambientais em uma única plataforma digital. O sistema permite visualizar dados climáticos, acompanhar regiões monitoradas e identificar áreas com maior probabilidade de alagamento por meio de mapas e indicadores.

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

![Modelo Entidade-Relacionamento (MER)](/src/images/modeling.png)

Organiza-se, previamente, nestes moldes o Modelo Entidade-Relacionamento(MER).
Dadas as Entidades e seus campos e/ou relacionamentos:

- **user**
  - Função: armazena os usuários do sistema.
  - Principais atributos: nome, email, data_nascimento, tipo, google_sub, created_at, updated_at.
  - Relações: 1:N com `payment_type`.

- **payment_type**
  - Função: guarda dados de pagamento (cartão, PIX, etc.).
  - Principais atributos: tipo_identificacao, numero, emissor.
  - Relações: N:1 com `user`; 1:N com `donation`.

- **donation**
  - Função: registra doações.
  - Principais atributos: valor, descricao, data, payment_type_id.

- **region**
  - Função: regiões geográficas monitoradas.
  - Principais atributos: nome, cidade, geometria (região geométrica), created_at, updated_at.
  - Relações: 1:N com `neighborhood`.

- **neighborhood**
  - Função: bairros dentro de uma região.
  - Principais atributos: nome, cidade, geometria.
  - Relações: N:1 com `region`; 1:N com `address`.

- **address**
  - Função: endereços físicos (onde há câmeras, protocolos etc.).
  - Principais atributos: cep, cidade, estado, latitude, longitude.
  - Relações: N:1 com `neighborhood`; 1:N com `camera`, `protocol`, `flood_detection_record`.

- **camera**
  - Função: câmeras instaladas para monitoramento.
  - Principais atributos: nome, url_video, descricao, status, address_id.
  - Relações: N:1 com `address`; 1:N com `flood_detection_record`.

- **flood_detection_record**
  - Função: resultados da detecção automática de enchentes.
  - Principais atributos: is_flooded (boolean), probabilidade (normal/médio/inundado), nivel_medio, data_imagem, camera_id, address_id.

- **protocol**
  - Função: protocolos administrativos (ocorrências formais).
  - Principais atributos: status, assunto, descricao, arquivos, address_id.
  - Relações: 1:N com `response`.

- **response**
  - Função: respostas associadas a um protocolo.
  - Principais atributos: mensagem, arquivo, protocol_id.

- **weather**
  - Função: dados meteorológicos coletados.
  - Principais atributos: data, latitude, longitude, chuva, temperatura, umidade, pressao, vazao_rio.
  - Relações: 1:N com `flood_point`, 1:N com `notification`.

- **flood_point**
  - Função: pontos com probabilidade de enchente baseada em dados climáticos.
  - Principais atributos: cidade, regiao, bairro, probabilidade, geometria, weather_id.

- **notification**
  - Função: notificações sobre risco de enchente.
  - Principais atributos: data_inicio, data_fim, situacao, bairro, weather_id.

- **forecast**
  - Função: previsões meteorológicas futuras.
  - Principais atributos: latitude, longitude, data probabilidade.
  - Entidade isolada: sem relacionamento explícito.

  Observações: Estuda-se o relacionamento dessa entidade com a `notification`.

- **occurrence**
  - Função: registro de ocorrências históricas de enchentes.
  - Principais atributos: data, situacao, tipo, bairro, cidade.
  - Entidade isolada: sem relacionamento explícito.

  Observações: Estuda-se o relacionamento dessa entidade com `weather`.

- Observa-se, majoritariamente, a utilização dos atributos create_at e update_at, para uma melhor validação das alterações em cada instância.

---

# 5. Diagrama de Caso de Uso

![Diagrama de Caso de Uso do Sistema AQUA](/src/images/DiagramaAQUA.drawio.png)

## Atores

Os atores identificados no sistema são:

- **Visitante**: pode cadastrar-se, visualizar informações como o mapa interativo e as câmeras de monitoramento;
- **Usuário autenticado**: possui acesso a funcionalidades adicionais, como gerenciamento de perfil e realização de doações;
- **Administrador**: responsável por funcionalidades mais avançadas, como registrar ocorrências, gerenciar câmeras e cadastrar pontos de alagamento.

# 5. Requisitos funcionais

## Entradas

**RF001 – Registro de Usuários:**  
Permite o cadastro de novos usuários no sistema para possibilitar acesso às funcionalidades da plataforma.

Dados necessários: nome, e-mail, data de nascimento, senha.  
Usuários: visitantes.

**RF002 – Autenticação de Usuários:**  
Permite que o usuário acesse o sistema utilizando credenciais válidas ou autenticação via conta Google.

Dados necessários: e-mail, senha, conta Google (OAuth).  
Usuários: todos os usuários.

**RF003 – Recuperação de Conta:**  
Permite que o usuário recupere o acesso à conta caso esqueça sua senha.

Dados necessários: e-mail.  
Usuários: todos os usuários.

**RF004 – Envio de Código de Recuperação:**  
Envia um código de verificação para o e-mail informado durante o processo de recuperação de senha.

Dados necessários: e-mail, código de recuperação, tempo de validade.  
Usuários: sistema.

**RF005 – Validação de Código de Recuperação:**  
Verifica se o código de recuperação informado pelo usuário é válido.

Dados necessários: código de recuperação, tempo de validade.  
Usuários: sistema.

**RF006 – Indicação de Resultado da Recuperação:**  
Exibe ao usuário o resultado do processo de recuperação de senha.

Dados necessários: status da recuperação.  
Usuários: todos os usuários.

**RF007 – Cadastro de Pontos de Alagamento:**  
Permite que administradores registrem pontos de alagamento monitorados no sistema.

Dados necessários: latitude, longitude, cidade, bairro, índice de chuva, umidade do ar, probabilidade, duração do evento, pressão atmosférica, vazão do rio.  
Usuários: administradores.

**RF008 – Cadastro de Ocorrências:**  
Permite registrar ocorrências relacionadas a eventos de risco ou alagamento.

Dados necessários: situação, tipo, cidade, bairro.  
Usuários: administradores.

**RF009 – Cadastro de Câmeras de Monitoramento:**  
Permite registrar câmeras públicas utilizadas para monitoramento das ruas.

Dados necessários: nome da câmera, latitude, longitude, bairro ou região, status.  
Usuários: administradores.

**RF010 – Configuração de Notificações:**  
Permite que administradores configurem alertas de risco para regiões específicas.

Dados necessários: situação, cidade, bairro, descrição.  
Usuários: administradores.

**RF011 – Cadastro de Dados Climáticos:**  
Permite registrar dados ambientais coletados para análise de risco.

Dados necessários: precipitação, umidade do ar, pressão atmosférica, vazão do rio.  
Usuários: sistema / administradores.

## Processos

**RF012 – Processamento de Dados Climáticos:**  
Analisa dados ambientais e históricos para estimar riscos de alagamento.

Dados necessários: dados climáticos, histórico de alagamentos, altitude.  
Usuários: sistema.

**RF013 – Cálculo de Probabilidade de Alagamento:**  
Calcula a probabilidade de ocorrência de alagamentos utilizando modelos de aprendizado de máquina.

Dados necessários: dados climatológicos, dados topográficos, histórico de eventos.  
Usuários: sistema.

**RF014 – Classificação de Nível de Criticidade:**  
Classifica o risco conforme níveis de criticidade definidos.

Dados necessários: índice de risco, parâmetros de classificação.  
Usuários: administradores.

**RF015 – Confirmação de Alteração de Criticidade:**  
Solicita confirmação antes da alteração de nível de criticidade.

Dados necessários: nível atual, novo nível selecionado.  
Usuários: administradores.

**RF016 – Envio de Notificações:**  
Envia alertas aos usuários quando há alteração significativa no nível de risco.

Dados necessários: nível de risco, região, mensagem de alerta.  
Usuários: sistema e administradores.

**RF017 – Filtragem de Registros Históricos:**  
Permite aplicar filtros para análise de dados históricos.

Dados necessários: categoria, tipo, bairro, data, situação.  
Usuários: administradores.

**RF018 – Processamento de Doações:**  
Processa contribuições financeiras realizadas pelos usuários.

Dados necessários: valor da doação, forma de pagamento, dados do cartão ou Pix.  
Usuários: usuários autenticados.

**RF019 – Gerenciamento de Cartões:**  
Permite armazenar e validar dados de cartões utilizados em doações.

Dados necessários: nome do titular, número do cartão, validade, CPF, CVV.  
Usuários: usuários autenticados.

**RF020 – Confirmação de Pagamento:**  
Apresenta tela de confirmação antes da finalização da doação.

Dados necessários: valor, forma de pagamento, dados do cartão mascarados.  
Usuários: usuários autenticados.

**RF021 – Geração de QR Code Pix:**  
Gera código e QR Code para pagamento via Pix.

Dados necessários: valor, código Pix, tempo de validade.  
Usuários: usuários autenticados.

**RF022 – Gerenciamento de Perfil:**  
Permite que o usuário visualize e edite seus dados pessoais.

Dados necessários: nome, e-mail, data de nascimento, senha, foto de perfil.  
Usuários: usuários autenticados.

**RF023 – Exclusão de Conta:**  
Permite que o usuário exclua sua conta permanentemente.

Dados necessários: confirmação de exclusão.  
Usuários: usuários autenticados.

## Saídas

**RF024 – Visualização do Mapa Interativo:**  
Exibe mapa contendo pontos de alagamento monitorados.

Dados necessários: latitude, longitude, bairro, probabilidade, duração do evento.  
Usuários: todos os usuários.

**RF025 – Visualização de Gráficos Climáticos:**  
Apresenta gráficos com indicadores ambientais.

Dados necessários: precipitação, vazão do rio, umidade do ar, pressão atmosférica.  
Usuários: administradores.

**RF026 – Visualização de Previsões Climáticas:**  
Permite visualizar previsões para diferentes intervalos de tempo.

Dados necessários: intervalo de previsão, dados climáticos.  
Usuários: administradores.

**RF027 – Visualização de Dashboard:**  
Exibe indicadores gerais de monitoramento em tempo real.

Dados necessários: indicadores climáticos, níveis de risco, alertas ativos.  
Usuários: administradores.

**RF028 – Visualização de Histórico:**  
Permite consultar registros históricos de eventos monitorados.

Dados necessários: data, categoria, bairro, tipo de evento.  
Usuários: administradores.

**RF029 – Visualização de Lista de Pontos:**  
Exibe lista de pontos monitorados com resumo das informações.

Dados necessários: bairro, probabilidade, duração do evento.  
Usuários: administradores.

**RF030 – Visualização de Probabilidade de Alagamento:**  
Apresenta em tempo real o nível de risco em determinada região.

Dados necessários: região, índice de risco, nível de criticidade.  
Usuários: todos os usuários.

**RF031 – Visualização de Câmeras:**  
Permite visualizar imagens de câmeras públicas em tempo real.

Dados necessários: identificação da câmera, localização, imagem.  
Usuários: todos os usuários.

**RF032 – Visualização de Informações das Câmeras:**  
Apresenta dados básicos de cada câmera monitorada.

Dados necessários: nome da câmera, bairro, região.  
Usuários: todos os usuários.

**RF033 – Visualização de Blog:**  
Exibe publicações informativas sobre enchentes.

Dados necessários: título, imagem, resumo.  
Usuários: todos os usuários.

**RF034 – Exibição de Publicações Populares:**  
Apresenta as publicações mais acessadas no blog.

Dados necessários: número de acessos, título da publicação.  
Usuários: todos os usuários.

**RF035 – Visualização da Página Sobre Nós:**  
Exibe informações institucionais sobre a equipe e objetivos do projeto.

Dados necessários: texto institucional, integrantes da equipe.  
Usuários: todos os usuários.

**RF036 – Exibição de Ícones de Nível de Risco:**  
Apresenta cores e ícones no mapa para representar níveis de criticidade.

Dados necessários: nível de risco, cores, ícones.  
Usuários: todos os usuários.

**RF037 – Busca de Regiões no Mapa:**  
Permite pesquisar regiões ou pontos monitorados.

Dados necessários: nome da região ou bairro.  
Usuários: todos os usuários.

**RF038 – Exibição de Perfil do Usuário:**  
Mostra foto de perfil e nome do usuário autenticado.

Dados necessários: nome, foto de perfil.  
Usuários: usuários autenticados.

**RF039 – Acesso à Página de Perfil:**  
Permite acessar a página com dados pessoais do usuário.

Dados necessários: dados do usuário.  
Usuários: usuários autenticados.

**RF040 – Visualização de Dados da Conta:**  
Exibe informações completas da conta do usuário.

Dados necessários: nome, e-mail, data de nascimento, data de criação da conta.  
Usuários: usuários autenticados.

**RF041 – Acesso ao Dashboard:**  
Permite acessar a área principal de monitoramento do sistema.

Dados necessários: dados de monitoramento.  
Usuários: usuários autenticados.

**RF042 – Acesso à Página de Segurança:**  
Permite acessar área de gerenciamento da conta.

Dados necessários: dados da conta do usuário.  
Usuários: usuários autenticados.

**RF043 – Edição de Dados Pessoais:**  
Permite alterar dados cadastrais do usuário.

Dados necessários: nome, e-mail, data de nascimento.  
Usuários: usuários autenticados.

**RF044 – Alteração de Senha:**  
Permite alterar a senha da conta mediante validação da senha atual.

Dados necessários: senha atual, nova senha, confirmação da senha.  
Usuários: usuários autenticados.

**RF045 – Confirmação de Ações Críticas:**  
Solicita confirmação antes de ações importantes no sistema.

Dados necessários: ação solicitada, confirmação do usuário.  
Usuários: usuários autenticados.

**RF046 – Exclusão Permanente de Conta:**  
Permite excluir permanentemente a conta do usuário após confirmação.

Dados necessários: confirmação de exclusão.  
Usuários: usuários autenticados.

# 7. Requisitos não funcionais

**RNF001** – O sistema deve armazenar senhas de forma criptografada, utilizando algoritmo seguro (ex.: bcrypt ou Argon2).

**RNF002** – O sistema deve utilizar protocolo HTTPS em todas as requisições para garantir a confidencialidade e integridade dos dados transmitidos.

**RNF003** – O sistema deve carregar a página inicial em até 5 segundos em condições normais de rede.

**RNF004** – O sistema deve estar disponível 24 horas por dia, 7 dias por semana, com no mínimo 99% de uptime mensal.

**RNF005** – O sistema deve realizar backups automáticos semanais do banco de dados.

**RNF006** – O sistema deve ser responsivo e se adaptar automaticamente a diferentes resoluções de tela (desktop, tablet e mobile).

**RNF007** – O sistema deve disponibilizar interface intuitiva, priorizando navegação simplificada e conteúdo objetivo.

**RNF008** – O sistema deve ser desenvolvido utilizando Clean Architecture e Domain Driven Design, permitindo fácil manutenção e expansão.

**RNF009** – O sistema deve manter logs de erros e acessos, permitindo auditoria e monitoramento.

---

# 8. Regras de negócio

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
