**FACULDADE DE TECNOLOGIA DE FRANCA**

**BRENDON HEITOR BESSA SILVA**
**KHELVIN WILLIAN BARBOSA RIBEIRO**
**LUIS FELIPE CARVALHO DE SOUZA**
**VINICIUS DE SOUZA SALVIANO**
**VITOR GABRIEL DOS REIS GLEGORIO**

**Artilheiro da Esperança**
**UCE - Engenharia de Software I**

**FRANCA**
**2025.2**
**BRENDON HEITOR BESSA SILVA**
**KHELVIN WILLIAN BARBOSA RIBEIRO**
**LUIS FELIPE CARVALHO DE SOUZA**
**VINICIUS DE SOUZA SALVIANO**
**VITOR GABRIEL DOS REIS GLEGORIO**

**Valentes de Davi**
**UCE - Engenharia de Software I**

Relatório Parcial de Unidade Curricular de Extensão – UCE de Engenharia de Software I, apresentado ao curso de Análise e Desenvolvimento de Sistemas da Faculdade de Tecnologia de Franca, para atender às disposições da Resolução nº 7 de 18 de dezembro de 2018, que estabelece as Diretrizes para a Extensão na Educação Superior.

Prof. Responsável: Me. Carlos Alberto Lucas

**FRANCA**
**2025.2**

**SUMÁRIO**

# 1 INTRODUÇÃO

O coordenador do curso de Análise e Desenvolvimento de Sistemas da Faculdade de Tecnologia de Franca, no cumprimento de suas atribuições e em atendimento à Resolução nº 7, estabeleceu a construção de soluções sistêmicas para Instituições Filantrópicas. O grupo de alunos do 1º semestre de ADS Noturno optou pelo desenvolvimento de um sistema de gestão e uma Landing Page para a ONG **Valentes de Davi**, que atua na formação de crianças através do esporte e princípios éticos.
Após a organização em grupo, buscamos a definição do cliente e nos reunimos com os responsáveis, o Diretor Kaliton Mota Coutinho, para levantar os problemas e as regras de negócio. O principal desafio identificado foi a gestão de dados manual (cadastro e frequência), que resultava em ineficiência e riscos de segurança.
A partir destas questões, iniciamos o desenvolvimento dos artefatos de Engenharia de Software, fundamentais para a documentação e o planejamento da solução. Este projeto atende às indicações da ONU, articulando-se com os Objetivos do Desenvolvimento Sustentável (ODS) como a ODS 8 (Trabalho Decente e Crescimento Econômico) e ODS 9 (Indústria, Inovação e Infraestrutura), ao fornecer uma solução tecnológica para o terceiro setor.

# 2 PROJETO DE UNIDADE CURRICULAR DE EXTENSÃO - UCE
O presente projeto descreve o sistema desenvolvido por um grupo de estudantes do curso de Análise e Desenvolvimento de Sistemas da Faculdade de Tecnologia de Franca, designado para criar uma plataforma digital robusta e integrada, concebida para atender às necessidades estratégicas e operacionais da ONG **Valentes de Davi**. A solução visa modernizar a gestão interna e ampliar a visibilidade externa da organização, superando desafios como a gestão manual de dados, a baixa visibilidade de marketing e a vulnerabilidade na segurança das informações.
**OBJETIVO GERAL** 
O principal objetivo do projeto é implementar uma plataforma digital integrada que otimize a gestão administrativa (Cadastro de Assistidos e Controle de Frequência) e fortaleça a presença online da ONG, garantindo a segurança dos dados e fornecendo ferramentas de gestão para a diretoria.
**Justificativa** 
A justificativa para a realização deste projeto reside na necessidade de modernizar a infraestrutura tecnológica da ONG, que atualmente enfrenta a ausência de um sistema de gestão de dados centralizado, o que gera falta de precisão, dificulta a geração de relatórios e expõe informações sensíveis a riscos de segurança (LGPD). A implementação do sistema reduzirá a carga administrativa dos Voluntários e permitirá que a Diretoria atue de forma proativa no combate à frequência irregular dos alunos (evasão), alinhando-se aos valores institucionais de eficiência e transparência.
**OBJETIVOS ESPECÍFICOS (Metas do Projeto)** 
O projeto busca resolver as fraquezas identificadas na ONG (gestão manual, risco de segurança e baixa visibilidade online) através dos seguintes objetivos específicos, conforme detalhado no Termo de Abertura do Projeto (TAP):
**Digitalizar 100% do Processo de Cadastro:** Eliminar formulários de papel, permitindo o preenchimento de dados do assistido e responsável, anexo de documentos digitais, geração e armazenamento do Termo de Responsabilidade e criação de matrícula única.
**Automatizar o Controle de Frequência:** Fornecer aos Voluntários uma ferramenta digital para registrar presença/falta em aula de forma ágil.
**Habilitar a Gestão Proativa de Evasão:** Criar mecanismos automáticos de alerta para a Diretoria, disparando notificações quando o aluno atinge um limite predefinido de faltas.

METODOLOGIA
A análise SWOT é uma ferramenta de planejamento estratégico usada para identificar os pontos fortes (Strengths), pontos fracos (Weaknesses), oportunidades (Opportunities) e ameaças (Threats) de uma organização ou projeto. A sigla SWOT vem das iniciais desses quatro fatores em inglês. Essa análise é amplamente utilizada para avaliar a posição competitiva de uma empresa e desenvolver estratégias eficazes.
A análise SWOT é importante por várias razões:
Identificação de Potenciais Estratégicos: Ajuda a identificar as áreas onde a empresa pode maximizar suas forças e aproveitar as oportunidades, ao mesmo tempo em que mitiga as fraquezas e se prepara para as ameaças.
Tomada de Decisões Informadas: Fornece uma visão clara das circunstâncias internas e externas, permitindo que os gestores tomem decisões mais informadas e estratégicas.
Planejamento Estratégico: Auxilia no desenvolvimento de estratégias de curto e longo prazo, alinhando os objetivos da empresa com o ambiente em que ela opera.
Comunicação e Alinhamento: Facilita a comunicação e o alinhamento dentro da organização, pois fornece uma linguagem comum para discutir os fatores que afetam o sucesso da empresa.
De acordo com Boone & Kurtz (1998), a análise SWOT, também referida como FOFA (Forças, Oportunidades, Fraquezas e Ameaças), configura-se como uma ferra- menta de planejamento estratégico valiosa para organizações. Essa ferramenta possibilita a avaliação sistemática de fatores internos e externos que influenciam o sucesso organizacional (Barney, 1991).

A identificação das fraquezas em uma empresa é crucial para a implementação de medidas corretivas e o aprimoramento contínuo de suas operações. Uma das fraquezas críticas frequentemente encontradas é a ausência de um controle de cadastro e relatórios eficazes, ausência de um cadastro e relatórios eficazes podem resultar em problemas como falta de controle e gerenciamento, falta clareza nos levantamentos periódicos (mensais ou semanais). Isso pode à uma desqualificação da ONG no quesito organização.
O 5W2H é uma ferramenta de gestão e planejamento que ajuda a estruturar e detalhar ações ou projetos. A sigla 5W2H deriva das iniciais em inglês das sete perguntas que devem ser respondidas para garantir que todas as dimensões de uma ação sejam consideradas:
**What (O que?):** O que será feito?
**Why (Por que?):** Por que será feito?
**Who (Quem?):** Quem fará?
**When (Quando?):** Quando será feito?
**Where (Onde?):** Onde será feito?
**How (Como?):** Como será feito?
**How much (Quanto custará?):** Quanto custará fazer?

O 5W2H é uma ferramenta de planejamento que se baseia em sete perguntas para organizar ideias, planos e projetos. O acrônimo 5W2H deriva do inglês e significa, segundo Chiavenato (2014, p. 142):
Clareza e Objetividade: Proporciona uma visão clara e objetiva sobre todas as etapas e responsabilidades envolvidas em um projeto ou ação. Cada aspecto é detalhado, reduzindo a ambiguidade e aumentando a compreensão de todos os envolvidos.
Planejamento Eficaz: Facilita a elaboração de um plano de ação detalhado, assegurando que todas as variáveis importantes sejam consideradas antes do início da execução.
Comunicação: Melhora a comunicação entre os membros da equipe e partes interessadas, proporcionando um formato padrão para a discussão e documentação de projetos.
Eficiência e Produtividade: Contribui para a eficiência e produtividade, eliminando suposições e fornecendo um roteiro claro para a execução das tarefas.
Abaixo está a 5W2H esquematizada diante do desenvolvimento de cadastro e sistematização institucional da ONG:

O plano de ação desenvolvido para a resolução das fraquezas apontadas na Matriz SWOT, teve como objetivo a solução integral de cada uma das fraquezas a partir de duas soluções possíveis. Cada uma das soluções trouxe o entendimento necessário para a resolução dos problemas, além do detalhamento passo a passo para ser realizado.
Diante ao documento pronto e validado com o docente responsável, foi levantado as seguintes possíveis soluções: Criação de um sistema de cadastro e controle de assistidos da ONG.
A elicitação de requisitos é uma etapa fundamental no desenvolvimento de sistemas, sendo realizada através de diversas técnicas. Algumas das principais técnicas incluem entrevistas, que podem ser estruturadas, com questões pré-definidas, não estruturadas, com conversas mais livres, ou semiestruturadas, que combinam as duas abordagens. Além disso, questionários e pesquisas são distribuídos para muitos usuários potenciais, enquanto workshops e sessões de brainstorming promovem reuniões colaborativas para discussão de ideias e requisitos.
Outra técnica importante é a observação e o job shadowing, onde se observa diretamente os usuários em suas tarefas diárias para compreender melhor suas necessidades. A análise de documentação envolve a revisão de documentos existentes, como manuais de usuário e requisitos de sistemas anteriores. A prototipagem, que pode ser funcional ou de baixa fidelidade, é utilizada para coletar feedback dos usuários.
Um processo de elicitação eficaz resulta em um sistema de alta qualidade que atende ou supera as expectativas dos usuários, levando a uma maior satisfação do cliente. Por fim, garante que todos os requisitos sejam documentados de maneira clara e compreensível, servindo como referência ao longo do ciclo de vida do projeto. Em suma, a elicitação de requisitos é uma etapa essencial que, quando realizada de forma adequada, contribui significativamente para o sucesso de um projeto de desenvolvimento de sistemas.
A elicitação de requisitos foi realizada por meio de entrevistas com os diretores da ONG. Foram conduzidas duas entrevistas, cada uma com duração média de trinta minutos, para esclarecer dúvidas.
Além disso, a equipe visitou a Associação com o objetivo de conhecer mais detalhadamente os processos realizados diariamente e compreender melhor as necessidades dos usuários em relação ao sistema em desenvolvimento. Durante a visita, a equipe teve a oportunidade de interagir com o diretor e os voluntários e usuários que não participaram das entrevistas, mapeando de forma mais precisa os processos necessários para o desenvolvimento dos artefatos do sistema.
O BPMN, sigla para **Business Process Model and Notation** (Modelagem e Notação de Processos de Negócio), é um padrão gráfico utilizado para modelar processos de negócios. Ele fornece uma notação compreensível para todos os stakeholders, incluindo analistas de negócios, que criam e refinam os processos, e técnicos responsáveis pela implementação e execução dos processos.
O BPMN é usado para criar diagramas de processos de negócios que representam o fluxo de trabalho dentro de uma organização. Isso ajuda a visualizar e compreender como os processos funcionam e como diferentes tarefas e atividades se inter-relacionam. 
Fornece uma documentação clara e padronizada dos processos de negócios, facilitando a comunicação entre diferentes departamentos e partes interessadas. O BPMN também Ajuda a identificar ineficiências, gargalos e oportunidades de melhoria nos processos existentes, permitindo a otimização contínua dos processos de negócios.
### A importância do BPMN se encontra em diversos pontos, dentre eles:
Clareza e Compreensão: BPMN utiliza uma notação gráfica intuitiva que é fácil de entender por todos os stakeholders, independentemente de seu nível técnico. Isso facilita a comunicação e o alinhamento dentro da organização.
Padronização: Proporciona uma linguagem padronizada para a modelagem de processos, o que é crucial para garantir consistência e precisão na documentação e análise dos processos de negócios.
Facilitação da Automação: Modelos BPMN podem ser convertidos em processos automatizados, facilitando a implementação de soluções de BPM e a integração com sistemas de TI, melhorando a execução e monitoramento dos processos.
Redução de Erros e Retrabalho: A modelagem detalhada dos processos permite identificar e corrigir problemas antes que eles se manifestem na prática, reduzindo erros e retrabalho.
A especificação Business Process Model and Notation (BPMN) oferece uma notação gráfica para a representação de processos de negócios em um diagrama específico.
Seu propósito principal é facilitar a Modelagem de Processos de Negócios, fornecendo uma notação comum compreensível tanto para usuários não técnicos quanto para usuários técnicos, com a capacidade de expressar de forma precisa a complexidade semântica dos processos. 
De acordo com a revista Object Management Group (OMG) (2022?), o principal objetivo do BPMN é estabelecer uma notação que seja facilmente compreensível por todos os participantes envolvidos no ciclo de vida de um processo de negócios. 
Desde os analistas de negócios, que elaboram os esboços iniciais dos processos, até os desenvolvedores técnicos responsáveis pela implementação da tecnologia que dará vida a esses processos, e por fim, aos empresários que irão gerenciar e monitorar esses processos. 
Assim, o BPMN estabelece uma padronização que preenche a lacuna entre o design do processo de negócios e sua posterior implementação.

Abaixo está BPMN esquematizado diante do desenvolvimento de estoque da Associação.

# 3 ESTUDOS TEÓRICOS

**4 ****ATORES E ENTREVISTAS COM A COMUNIDADE**

Na ONG, os stakeholders desempenham papéis essenciais na condução e funcionamento da instituição. O membro mais importante da instituição é o Diretor da mesma: Kaliton
A comunidade social visitada é a ONG **Valentes de Davi**, localizada em Franca-SP. A instituição opera há mais de dois anos, com a missão de **"Contribuir para a formação de caráter de crianças, promovendo um tempo de qualidade que combina lazer, aprendizado e o fortalecimento de valores éticos, preparando-as para um futuro mais consciente e promissor."**
**Visão:** Expandir de forma sustentável as atividades do projeto para impactar positivamente um número crescente de crianças, levando as ferramentas do esporte, lazer e princípios éticos como meio de inclusão e desenvolvimento pessoal.
**Valores:** Respeito aos colegas e aos pais, e o incentivo para que sonhem em se tornar adultos dignos e íntegros no futuro.
A coleta de dados foi realizada por meio de entrevistas semi-estruturadas com o Diretor Kaliton Mota Coutinho e Voluntários, além de visitas ao local de treino para observação dos processos "como estão" (AS-IS).
O começo do Projeto Interdisciplinar (PI) focado na elaboração de uma solução sistêmica para a Associação tem início em fevereiro, e a partir disso formou-se equipes de cinco estudantes para cada área constituinte do projeto, seus gerentes foram selecionados assim como seus tópicos, formando-se os blocos.
Em agosto iniciou-se os trabalhos, realizando a primeira entrevista com o diretor da ONG e logo após foi desenvolvido a matriz SWOT e 5W2H.
Em setembro foi desenvolvido a EAP e as perguntas que seriam efetuadas na segunda entrevista com as coordenadoras. O grupo também visitou a Associação e logo após desenvolveu o BPMN.
No mês de outubro foi construído a documentação de requisitos, o diagrama de classes, a introdução do TAP. Foi desenvolvido também o diagrama de caso de uso e a documentação de caso de uso. Os demais artefatos serão construídos futuramente para o desenvolvimento do projeto. O sistema será entregue em julho/2025 com todos os artefatos desenvolvidos. Portanto, os próximos artefatos poderão sofrer mudança de prazo com base no andamento do projeto.

Vitor Gabriel Dos Reis Glegorio: Gerente, responsável pelo desenvolvimento do Missão Visão e Valor, SWOT, 5W2H, Perguntas da Entrevista, BPMN, TAP, Prototipação de Telas e Proposta Comercial.
Vinicius de Souza Salviano: Vice gerente, responsável pelo desenvolvimento do SWOT, 5W2H, Perguntas da Entrevista, BPMN, TAP e Matriz de Rastreabilidade.
Luiz Felipe Carvalho de Souza: Responsável pelo desenvolvimento do SWOT, 5W2H, perguntas da entrevista, BPMN, Documentação de Requisitos, Diagrama de Classe.
Brendon Heitor Bessa da Silva: Responsável pelo desenvolvimento do SWOT, 5W2H, perguntas da entrevista, BPMN, Documentação de Requisitos.
Khelvin Willian Barbosa Ribeiro: Responsável pelo desenvolvimento do SWOT, 5W2H, perguntas da entrevista, BPMN, Diagrama de Caso de Uso, Documentação do Diagrama de Caso de Uso.
Eduardo de Paula Figueiredo: Responsável pelo desenvolvimento do SWOT, 5W2H, perguntas da entrevista, BPMN, EAP.
INSERIR FOTOS AQUI

# 5. INTERVENÇÕES

**Levantamento de Requisitos - Elicitação e especificação dos Requisitos **

No desenvolvimento de software, é crucial compreender as necessidades e expectativas dos usuários para o sucesso de um projeto. A elicitação de requisitos, o processo de levantamento e a documentação dessas necessidades, são fundamentais nessa jornada.

Um requisito funcional é uma especificação que define uma função que um sistema ou componente de software deve executar. Esses requisitos descrevem o comportamento do sistema em termos das suas funcionalidades e capacidades, detalhando as ações que o sistema deve ser capaz de realizar para atender às necessidades dos usuários e aos objetivos do negócio. Eles são fundamentais no desenvolvimento de software, pois guiam o processo de design, desenvolvimento, teste e validação do sistema.

**Requisitos Funcionais:**

Abrir Formulário de Novo Assistido no Sistema
Preencher dados pessoais do Assistido
Coletar dados de endereço e contato
Anexar cópias de documentos do Assistido
Preencher dados do Responsável
Anexar cópia de documento do Responsável
Preencher informações médicas relevantes
Corrigir pendências no formulário
Imprimir o Termo de Responsabilidade
Fazer Upload do Termo Digitalizado e Coletar Físico Assinado
Clicar no Botão "Finalizar Cadastro"
Gerar Documento "Termo de Responsabilidade"
Preenchimento de Campos Obrigatórios
Criar Registro na Tabela 'ASSISTIDOS'
Salvar Anexos (Documentos, Foto) no Diretório do Servidor
Gerar Código/Matrícula Única para o Assistido
Enviar E-mail de Confirmação para o Responsável
Abrir Tela De Chamada Da Turma X Do Sistema
Carregar Lista de Assistidos Inscritos na Turma X
Verificar Presença de [Nome do Assistido]
Registar Presença Para O Assistido X Na Aula Y do dia Z
Registrar Falta Para O Assistido X Na Aula Y Do Dia Z
Incrementar Contador De Faltas Do Assistido X
Enviar Alerta de Faltas Para o Coordenador Da Ong
Abaixo estão as imagens das tabelas a respeito da Documentação de Requisitos realizada diante do desenvolvimento de cadastro da ONG:

**Matriz de Rastreabilidade - Regras de Negócio**
 	Regras de negócio são diretrizes, políticas, práticas ou condições que definem ou restringem os aspectos operacionais de uma organização. Elas determinam como as atividades devem ser conduzidas, descrevendo o que pode ou não ser feito em determinadas situações. As regras de negócio são essenciais para garantir que os processos e operações da empresa estejam alinhados com seus objetivos estratégicos, regulamentos e padrões de qualidade.
 	Regras de negócio asseguram que as operações da organização estão em conformidade com regulamentos legais, normas industriais e políticas internas. Promovem a consistência nos processos de negócio, garantindo que as mesmas condições sejam tratadas da mesma maneira em todas as situações e contribuem para a qualidade e eficiência dos processos ao definir claramente como as atividades devem ser conduzidas.

	Uma matriz de rastreabilidade é um documento ou ferramenta que ajuda a conectar e relacionar diferentes elementos de um projeto, como requisitos, design, desenvolvimento, testes e implementação. É usada para garantir que todos os requisitos especificados inicialmente sejam completamente atendidos em todas as fases do projeto, desde a concepção até a entrega final.
 		A matriz de rastreabilidade assegura que todos os requisitos iniciais sejam totalmente implementados e validados, prevenindo lacunas ou falhas no produto e facilita o gerenciamento de mudanças, permitindo rastrear quais requisitos foram modificados e como essas mudanças impactam outros elementos do projeto.

Abaixo está o Matriz de Rastreabilidade esquematizado diante do desenvolvimento de cadastro da ONG.

# Estrutura Analítica do Projeto (EAP)

	A Estrutura Analítica do Projeto (EAP), também conhecida como Work Breakdown Structure (WBS) em inglês, é uma ferramenta fundamental no gerenciamento de projetos. Ela organiza e define o escopo total de um projeto, dividindo-o em partes menores e mais manejáveis, chamadas de pacotes de trabalho (work packages). Cada pacote de trabalho representa uma unidade de trabalho específica e tangível, que pode ser planejada, executada, monitorada e controlada.
 	A Estrutura Analítica do Projeto (EAP) ajuda a definir e comunicar claramente o escopo do projeto, evitando ambiguidades e assegurando que todos os envolvidos tenham um entendimento comum do que será realizado.
Facilita o planejamento detalhado do projeto, permitindo a identificação de todas as atividades necessárias para completar o projeto e auxilia na alocação eficiente de recursos, pois cada pacote de trabalho pode ser detalhado em termos de tempo, custo, pessoal e materiais necessários. 
Abaixo está a EAP esquematizada diante do desenvolvimento de cadastro.

# Termo de Abertura do Projeto (TAP)
	De acordo com o Guia PMBOK, o TAP é um dos documentos que faz parte de todo o ciclo de vida de um projeto. Nele, irá constar os objetivos e benefícios do projeto, estudos de viabilidade, as restrições de prazo e orçamento (ARTIA, 2024).
	É a partir do TAP que é permitida a autorização de inicialização do projeto.
	O quadro apresenta de forma parcial, algumas informações contempladas neste documento tão importante para o sucesso deste projeto.

1. Situação Atual
A ONG Valentes de Davi opera há mais de dois anos , com uma missão clara de "contribuir para a formação de caráter de crianças" e um "alto impacto social"  reconhecido na comunidade. No entanto, sua infraestrutura operacional e de gestão de dados não acompanhou seu crescimento, criando gargalos significativos.
A análise do cenário "AS-IS" (como está) revela que a gestão de dados é predominantemente manual. O cadastro de novos assistidos, o arquivamento de documentos (incluindo termos de responsabilidade de menores) e o controle de frequência são feitos em papel ou planilhas não integradas. A comunicação com os pais e entre os voluntários é não estruturada, dependendo de canais avulsos.

Essa abordagem manual resulta em várias ineficiências e riscos:
Carga Administrativa: Os Voluntários gastam um tempo precioso em tarefas administrativas (papelada de cadastro, contagem manual de faltas) que compete diretamente com seu tempo de preparação de aulas, palestras e organização de treinos.
Risco de Segurança de Dados: A gestão física de documentos de menores de idade apresenta um risco elevado na segurança dos dados, podendo expor a ONG a problemas legais (LGPD) e quebrar a confiança dos Pais.
Falta de Visibilidade: Uma das ameaças identificadas é a "frequência irregular dos alunos". Sem um sistema, é impossível medir esse indicador de forma confiável, identificar padrões de evasão ou intervir proativamente.

Barreira ao Crescimento: A "alta competição por financiamento"  exige profissionalismo. A gestão manual dificulta a geração de relatórios e métricas de impacto, essenciais para atrair novos parceiros e doações.
Apesar dessas fraquezas, a ONG possui uma força interna crucial: um "uso eficiente de recursos financeiros" e uma cultura de "respeito" e "integridade", o que favorece a implementação de uma nova solução sistêmica.

2. Justificativa do Projeto
A existência contínua de processos manuais é um freio direto à "Visão" da ONG de "expandir de forma sustentável". O projeto justifica-se pela necessidade de transformar a gestão da ONG, movendo-a de um modelo reativo e analógico para um modelo proativo, digital e centralizado.
A implementação deste sistema atacará diretamente as Fraquezas (Gestão manual, Risco na segurança dos dados)  identificadas na análise SWOT, convertendo-as em Forças. Ao automatizar o cadastro e a frequência, o sistema liberará os Voluntários (atores-chave ) para que se concentrem em suas atividades-fim: "dar aula", "realizar palestras" e "ajudar na organização dos treinos".
Além disso, o sistema criará uma base de dados confiável. Isso permite à Diretoria tomar decisões baseadas em dados (ex: quais turmas têm mais evasão) e profissionaliza a gestão, o que é fundamental para mitigar a Ameaça da "dependência de doações voláteis" e capitalizar a Oportunidade de "novas parcerias", apresentando uma organização estruturada e transparente.

3. Propósito do Projeto e Metas
O propósito deste projeto é desenvolver e implantar uma solução de software (Sistema Web) que automatiza e centraliza os processos de cadastro de assistidos e registro de frequência, garantindo a segurança dos dados e fornecendo ferramentas de gestão para a diretoria da ONG Valentes de Davi.

As metas detalhadas para alcançar este propósito são:

Meta 1: Digitalizar 100% do Processo de Cadastro (Módulo de Cadastro)

Descrição: Eliminar totalmente a necessidade de formulários de papel no primeiro contato com o assistido.
Indicadores de Sucesso (Requisitos-chave):
Sistema permite preencher dados completos do assistido (RF-002) e do responsável (RF-005).
Sistema permite anexar documentos digitais do assistido (RF-004) e do responsável (RF-006).
Sistema gera (RF-012) e armazena o Termo de Responsabilidade assinado digitalmente (RF-010).
O Sistema gera uma matrícula única para cada assistido (RF-016).
O sistema envia confirmação automática por e-mail ao responsável (RF-017).

Meta 2: Automatizar o Controle de Frequência (Módulo de Frequência)
Descrição: Fornecer aos Voluntários uma ferramenta digital e ágil para realizar a chamada em aula.
Indicadores de Sucesso (Requisitos-chave):
O sistema exibe a lista de alunos da turma (RF-018, RF-019).
Voluntário consegue marcar "Presente" (RF-020, RF-021) ou "Ausente" (RF-022).
O sistema persiste (salva) o histórico de frequência no banco de dados para consultas futuras.

Meta 3: Habilitar a Gestão Proativa de Evasão (Módulo de Gestão)
Descrição: Criar mecanismos automáticos de alerta para que a Diretoria possa agir antes que o aluno abandone o projeto.
Indicadores de Sucesso (Requisitos-chave):
O sistema incrementa um contador de faltas automaticamente ao registrar uma ausência (RF-023).
O sistema dispara um alerta automático ao Diretor quando o assistido atinge um limite X de faltas (RNF-024).
O Sistema permite aos Pais (ator ) verificar a presença do dependente.

4. Descrição do Projeto (Escopo)
O escopo do projeto é o desenvolvimento de uma aplicação web composta por dois processos centrais, conforme mapeado nos diagramas BPMN e detalhado nos Requisitos Funcionais (RFs) . O sistema será dividido em "piscinas" (swimlanes) que definem as responsabilidades dos atores: Voluntário, Responsável e Sistema.
Módulo 1: Fluxo "Cadastro de Novo Assistido" O ator Voluntário inicia o processo no sistema (RF-001). Ele preenche uma série de formulários com os dados do assistido (RF-002), endereço (RF-003), informações médicas (RF-007) e dados do Responsável  (RF-005). O Voluntário também anexa os documentos de ambas as partes (RF-004, RF-006). Neste ponto, o Sistema gera o Termo de Responsabilidade (RF-012), que é impresso (RF-009)  e coletado. O Voluntário então digitaliza e faz o upload deste termo assinado (RF-010). O Voluntário clica em "Finalizar Cadastro" (RF-011). O Sistema executa uma validação crítica (RF-013)  para verificar se todos os campos obrigatórios foram preenchidos.
Se NÃO (Pendências): O fluxo é desviado e o Voluntário deve corrigir as pendências (RF-008).
Se SIM (Sucesso): O Sistema executa as ações de persistência: cria o registro na tabela 'ASSISTIDOS' (RF-014), salvar os anexos no servidor (RF-015), gera a matrícula única (RF-016) e envia a confirmação ao responsável (RF-017). O processo é concluído com sucesso.
Módulo 2: Fluxo "Registrar Frequência em Aula" O ator Voluntário (neste contexto, "Voluntário da Aula") inicia o processo abrindo a tela de chamada da sua turma (RF-018). O Sistema consulta o Banco de Dados e carrega a lista de assistidos inscritos naquela turma (RF-019). O Voluntário realiza a verificação de presença. Para cada aluno, o Voluntário marca "Presente" (RF-020) ou mantém o padrão "Ausente". Após a verificação, o Sistema persiste essa informação: registra "Presença" (RF-021) ou "Falta" (RF-022)  no banco de dados, associada à data da aula. Se uma "Falta" é registrada, o Sistema executa uma ação automática: incrementar o contador de faltas daquele assistido (RF-023). O Sistema então verifica se o total de faltas atingiu o limite predefinido (RNF-024).
Se SIM: O Sistema envia um alerta ao Diretor.
Se NÃO: O processo de registro de frequência é finalizado.

5. Premissas
As seguintes premissas são consideradas verdadeiras para o planejamento e execução do projeto:
Disponibilidade do Cliente: Assume-se que o Diretor Kaliton Mota Coutinho e os Voluntários designados terão disponibilidade para participar de reuniões de validação (como a de 29/09/2025 ), sessões de prototipação  e testes.
Ambiente Tecnológico Mínimo: Assume-se que os Voluntários terão acesso a dispositivos (computadores ou smartphones) com conexão à internet nos locais de cadastro e treino para operar o sistema web. Esta premissa é um pilar da análise de portabilidade.
Autoridade do Ponto de Contato: O Diretor Kaliton Mota Coutinho é o Product Owner (PO) do projeto, com autoridade total para "passar ao 'Grupo' quais são as necessidades"  e aprovar as entregas, evitando ambiguidades de escopo.
Infraestrutura de Hospedagem: Assume-se que, devido à "dependência de doações voláteis", o sistema deverá ser hospedado em uma infraestrutura de baixo ou zero custo (ex: plataformas Free Tier ou servidor da própria FATEC, se disponível).
Comprometimento da Equipe: Assume-se que os membros do "Grupo Tela Azul"  permanecerão no projeto durante todo o semestre letivo, dedicando as horas necessárias para a conclusão dos artefatos e do software.

6. Restrições
O projeto está limitado pelos seguintes fatores:
Restrição de Recursos Humanos: A equipe de desenvolvimento ("Grupo Tela Azul") é composta por estudantes do 1º Semestre de ADS Noturno. Isso impõe uma restrição severa no total de horas/semanas disponíveis para o projeto, exigindo um gerenciamento de escopo rigoroso.
Restrição Financeira (Orçamento Zero): O projeto opera com um orçamento de R$ 0,00. Esta restrição, impulsionada pela natureza da ONG ("dependência de doações voláteis" ), proíbe o uso de qualquer software proprietário, API paga, licenças ou serviços de hospedagem premium.

Restrição de Prazo (Acadêmica): O projeto possui um prazo final não-negociável, ditado pelo calendário acadêmico da FATEC Franca para a Unidade de Competência (UCE) de Engenharia de Software. Todas as entregas devem ser concluídas dentro deste período.
Restrição de Usabilidade (Adoção): O sistema deve ser visivelmente mais simples e rápido de usar do que o processo manual atual. Uma interface complexa resultará em baixa adesão pelos Voluntários, levando ao fracasso do projeto.
Restrição de Portabilidade: A solução deve ser desenvolvida para operar na infraestrutura de hardware e software existente ou minimamente viável da ONG, conforme a ser levantado no F.A.P. (Formulário de Análise de Portabilidade) .

7. Stakeholders (Partes Interessadas)
Diretor (Kaliton Mota Coutinho): O Patrocinador (Cliente). Responsável por "Determinar o futuro da ONG" e "Decidir a mensagem". No projeto, é o ponto focal para "dar feedback sobre o andamento"  e validar as entregas.
Voluntários: Os Usuários-Chave. Responsáveis por "Dar aula", "Realizar palestras" e, crucialmente para este sistema, "Cadastrar novos assistidos"  e realizar a chamada. Seu feedback de usabilidade é essencial.
Pais: Usuários Externos. Responsáveis por "Levar seus dependentes" para o cadastro (fornecendo os dados) e "Acompanhar as chamadas pelo sistema".
Assistidos: Os Beneficiários Finais. O objetivo do projeto é melhorar a organização para que eles possam "Participar dos treinos" e "Assistir às palestras"  com mais eficiência.
Grupo Tela Azul: A Equipe de Desenvolvimento. Responsável por "Desenvolver uma página focada em solucionar problemas" e "Consultar o diretor e voluntários"  para garantir que a solução atenda às necessidades.
FATEC Franca (Corpo Docente): A entidade Supervisora. Responsável por definir a metodologia ("Guia Projeto UCE" ) e avaliar a qualidade dos artefatos e do software produzido pelo "Grupo Tela Azul".

8. Riscos (Iniciais)
Risco de Segurança e Privacidade (Alto):
Descrição: O sistema armazenará dados sensíveis de menores (RG, CPF, endereço, dados médicos ). Uma falha de segurança (vazamento de dados) teria consequências legais e de reputação devastadoras.
Mitigação: Aderência estrita às melhores práticas de desenvolvimento seguro (OWASP Top 10), criptografia de dados sensíveis em repouso e em trânsito, e implementação de controle de acesso rigoroso baseado em perfis (Voluntário, Diretor).

Risco de Adoção pelo Usuário (Médio):
Descrição: Os Voluntários podem resistir à mudança do processo manual  se o sistema for lento, complexo ou não funcionar bem em dispositivos móveis no campo.
Mitigação: Envolvimento direto dos Voluntários no processo de design. Usar a técnica de Prototipação  para coletar feedback cedo. Priorizar a simplicidade da interface (Usabilidade) acima de funcionalidades complexas.

Risco de Manutenção e Sustentabilidade (Médio/Alto):
Descrição: A ONG depende de "doações voláteis". O custo de manter o sistema no ar (hospedagem, domínio) após a saída do "Grupo Tela Azul" pode se tornar um fardo.
Mitigação: O sistema será construído exclusivamente com tecnologias de código aberto (open-source). A documentação (conforme Guia UCE ) será extremamente detalhada para facilitar a transição para futuros voluntários de tecnologia ou para a própria equipe da ONG.

Risco de Scope Creep (Aumento de Escopo) (Médio):
Descrição: Durante o desenvolvimento, o cliente (Diretor ou Voluntários) pode solicitar novas funcionalidades não previstas nos 24 RFs iniciais (ex: "módulo financeiro", "gestão de eventos").
Mitigação: Aderência estrita ao escopo definido neste TAP e nos documentos de requisitos. O Gerente de Projeto do "Grupo Tela Azul" deve usar a Matriz de Rastreabilidade  para validar o escopo. Novas ideias serão registradas em um backlog para uma "Fase 2" do projeto.

9. Marco (Milestones / Cronograma Macro)
O projeto seguirá as fases e entregas de artefatos definidas pelo "Guia Projeto UCE":

M1: Iniciação e Levantamento (Concluído)
Descrição: Reunião de Kick-off e entrevistas com o Diretor Kaliton Mota Coutinho (realizada em 29/09/2025 ) para entendimento da Missão, Visão, Valores e Atores.

M2: Análise Estratégica e de Viabilidade
Descrição: Entrega dos artefatos de diagnóstico: Análise SWOT , EAP (Estrutura Analítica de Projetos) e este TAP (Termo de Abertura do Projeto). Validação com o cliente.

M3: Modelagem de Processos de Negócio
Descrição: Entrega e validação dos diagramas BPMN  (AS-IS e TO-BE), detalhando os fluxos de "Cadastro de Novo Assistido" e "Registrar Frequência".

M4: Engenharia de Requisitos e Modelagem de Sistema
Descrição: Entrega da documentação de Requisitos Funcionais (RFs) e Não Funcionais (RNFs) , da Matriz de Rastreabilidade e dos Diagramas de Caso de Uso.

M5: Protótipo e Validação de Usabilidade
Descrição: Apresentação de um protótipo de alta fidelidade (Prototipação ) para os Voluntários e Diretor, coletando feedback sobre os fluxos de tela antes do início da codificação intensiva.

M6: Entrega do MVP (Produto Mínimo Viável)
Descrição: Entrega da primeira versão funcional do sistema, com os módulos de Cadastro (RF-001 a RF-017) e Frequência (RF-018 a RNF-024) operacionais para testes em ambiente de homologação.

M7: Entrega Final, Implantação e Encerramento
Descrição: Implantação do sistema no ambiente de produção final, treinamento oficial dos Voluntários, entrega de toda a documentação do projeto e Formulário de Análise de Portabilidade (FAP). Apresentação final para a FATEC e para a ONG.

10. Responsabilidades
Cliente (Diretor Kaliton Mota Coutinho):
Atribuições: Atuar como a voz do cliente e Patrocinador. É o ponto focal para a tomada de decisões estratégicas do projeto. É responsável por "Passar ao 'Grupo' quais são as necessidades da ong", validar e aprovar os artefatos (BPMN, RFs) e protótipos em tempo hábil, e garantir a disponibilidade dos Voluntários para as sessões de teste e feedback.

Equipe de Desenvolvimento (Grupo Tela Azul):
Atribuições: Responsável por todo o ciclo de vida do projeto, conforme o "Guia Projeto UCE". Isso inclui "Desenvolver uma página focada em solucionar problemas" , gerenciar o cronograma e os riscos, "Consultar o diretor e voluntários"  para refinar requisitos, realizar a codificação, garantir a qualidade do software (testes) e produzir toda a documentação formal exigida.

Usuários-Chave (Voluntários da ONG):
Atribuições: Atuar como especialistas no domínio do negócio. São essenciais para "Ajudar na organização dos treinos, planejamentos" e, no contexto do projeto, devem participar ativamente das sessões de levantamento de requisitos (entrevistas, etnografia ), testar os protótipos e o sistema final (Testes de Aceitação do Usuário - UAT), e fornecer feedback honesto e construtivo para garantir a usabilidade e o sucesso da ferramenta.

# 6 PRINCIPAIS RESULTADOS

Até o momento, o projeto está em sua fase inicial, concentrando-se na construção da base fundamental necessária para dar suporte às etapas subsequentes, que incluirão o desenvolvimento das telas, programação e implementação do software. 
Nesta etapa inicial, o foco está na elaboração dos documentos essenciais que fornecerão a estrutura para todo o projeto. Estes documentos estão sendo meticulosamente elaborados, levando em consideração todas as informações coletadas junto à Associação.

a. Melhoria dos processos, utilizando as informações dos documentos para geração dos processos. 
b. Gestão dos assistidos da ONG.
c. Possuir um banco de dados para o cadastro e validação dos assistidos.
d. Obter recursos necessários de organização.
e. Monitorar o número de assistidos da ONG.

Comunicação:
a. Os processos possuem uma velocidade maior por informação, sendo eles automatizados. 
b. Os processos se aproximam cada vez mais de uma exatidão ao percorrer as instâncias necessárias.
c. Capacidade de mostrar a falta de recursos.

Otimização dos processos:
a. Identificação de riscos e inconsistências com agilidade.
b. Cadastramento de produtos

Diminuição de problemas:
a. Cálculos de quantidade de assistidos
b. Controle de presença e falta

Cada detalhe dos documentos está sendo cuidadosamente planejado e desenvolvido, utilizando as informações obtidas da associação como base para garantir que todas as necessidades e requisitos sejam adequadamente endereçados. Isso inclui a compreensão das demandas dos membros da associação, suas expectativas, desafios enfrentados e objetivos esperados.
Essa abordagem visa estabelecer uma sólida fundação para o projeto, garantindo que todas as etapas subsequentes sejam executadas de maneira eficiente e eficaz. Ao construir uma base sólida agora, podemos garantir que o projeto tenha uma direção clara e uma estrutura robusta para o desenvolvimento futuro.
A colaboração estreita com a Associação desempenha um papel essencial neste processo, permitindo que suas necessidades específicas sejam compreendidas e incorporadas desde o início do projeto. Essa parceria assegura que o resultado seja verdadeiramente alinhado com as expectativas da associação e atenda às suas necessidades de forma abrangente.
À medida que avançamos nesta fase inicial, estamos confiantes de que estamos estabelecendo as bases sólidas necessárias para o sucesso do projeto. Com uma abordagem cuidadosa e centrada nas necessidades da associação, estamos no caminho certo para entregar um sistema de estoque eficaz e altamente funcional que beneficie não apenas a ONG, mas também toda a comunidade que ela serve.
A equipe está empenhada em desenvolver um sistema de cadastro sob medida para atender às necessidades específicas da ONG. Reconhecendo a importância de um controle eficiente de estoque para a instituição, nosso objetivo é proporcionar uma solução tecnológica que não apenas otimize os processos internos, mas também ofereça oportunidades para aprimorar a organização e a eficiência operacional.
Para alcançar esse objetivo, optamos por utilizar uma abordagem moderna e robusta, desenvolvendo o sistema como uma aplicação web. Isso permitirá acesso fácil e flexível a partir de diferentes dispositivos e locais, garantindo a acessibilidade necessária para os membros da associação.
No que diz respeito à arquitetura do sistema, decidimos adotar uma abordagem de desenvolvimento full-stack, utilizando Java para o backend e React para o frontend. O backend, desenvolvido em Java, fornecerá a lógica de negócios e manipulação dos dados, garantindo um desempenho estável e seguro. Por outro lado, o frontend, baseado em React, oferecerá uma experiência de usuário moderna e responsiva, com uma interface intuitiva e amigável.
Quanto ao armazenamento de dados, optamos por utilizar o PostgreSQL como nosso sistema de gerenciamento de banco de dados. Conhecido por sua confiabilidade, desempenho e capacidade de escalabilidade, o PostgreSQL oferece uma base sólida para armazenar e gerenciar os dados críticos do sistema de estoque da associação.
Além disso, reconhecendo a importância da usabilidade e da experiência do usuário, o projeto incluirá telas cuidadosamente projetadas e desenvolvidas para atender às necessidades específicas de um sistema de cadastro de assistidos. Desde a visualização e atualização de tabelas até o controle de presença, cada tela será projetada com foco na facilidade de uso e na eficiência operacional.
Em resumo, nosso sistema de cadastro para a ONG será uma solução abrangente e personalizada, desenvolvida com tecnologias modernas e uma abordagem centrada no usuário. Estamos confiantes de que esse sistema não apenas melhorará o controle de cadastro e movimentação de assistidos da ONG, mas também abrirá novas oportunidades para aprimorar sua organização e eficiência operacional.
As restrições enfrentadas pela Associação são um fator importante a ser considerado durante a implementação do novo sistema de estoque. Uma das principais limitações é a falta de familiaridade dos funcionários com computadores e software. 
Muitos deles podem não estar acostumados a trabalhar com tecnologia ou podem sentir-se desconfortáveis ao utilizar sistemas informatizados. Isso pode representar um desafio significativo durante a fase de implementação do sistema, uma vez que a adaptação e o treinamento dos funcionários serão essenciais para garantir uma transição suave e bem-sucedida para o novo sistema.
Além disso, outro aspecto a ser considerado é a falta de recursos de tecnologia no estabelecimento. A ONG pode enfrentar dificuldades para fornecer os equipamentos necessários, como computadores, tablets ou smartphones, para acessar e utilizar o sistema de cadastro. A falta desses recursos pode limitar a capacidade dos funcionários de interagir e utilizar efetivamente o novo sistema, comprometendo assim sua eficácia e utilidade.

# 7 CONSIDERAÇÕES FINAIS

Em resumo, este projeto atingiu o marco de conclusão da fase de Análise e Requisitos, transformando a necessidade de modernização da ONG Valentes de Davi em uma documentação de software completa e rastreável. O objetivo geral de desenvolver uma solução digital integrada para otimizar o cadastro e a frequência foi solidamente detalhado nos 24 Requisitos Funcionais e Não Funcionais e nas 16 Regras de Negócio.
As fragilidades da gestão manual foram explicitadas na SWOT e o plano de ação (5W2H e TAP) foi desenhado para mitigar os riscos inerentes, como o Risco de Segurança e Privacidade (LGPD) e o Risco de Adoção pelo Usuário. A próxima etapa será a codificação do Módulo de Cadastro, conforme o cronograma macro. Estamos confiantes de que a base documental robusta estabelecida permitirá um desenvolvimento eficaz e alinhado às necessidades reais da ONG.

# 8 CONTRIBUIÇÕES DA UCE PARA A FORMAÇÃO DISCENTE

A Unidade Curricular de Extensão (UCE) de Engenharia de Software I se mostrou de extrema relevância para a formação do grupo. Através do desenvolvimento do projeto para a ONG Valentes de Davi, foi possível aplicar, em um contexto real, as melhores práticas teóricas de Engenharia de Software.
O contato direto com o cliente (Diretor e Voluntários) nas entrevistas e visitas permitiu o desenvolvimento da habilidade de Elicitação de Requisitos e a compreensão de um domínio de negócio real, indo além do ambiente acadêmico. A criação de artefatos como o BPMN, EAP, TAP, Matriz de Rastreabilidade, e os Diagramas UML (Casos de Uso, Atividades, Sequência) permitiu exercitar a Modelagem de Sistemas de forma prática e rigorosa.
A gestão das Restrições (como o Orçamento Zero) e Riscos do projeto forçou o grupo a tomar decisões estratégicas, como a escolha de tecnologias open-source (PHP/MySQL) para garantir a Portabilidade e Sustentabilidade da solução para a comunidade. Esta experiência de ponta a ponta na fase de planejamento reforça a capacidade do grupo de desenvolver soluções com qualidade e alinhadas aos objetivos estratégicos de uma organização.