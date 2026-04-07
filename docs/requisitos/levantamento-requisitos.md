✅ ONG (Missão / Visão / Valor)
***COMPILADO LEVANTAMENTO DE REQUISITOS UCE I***

✅ ATORES
***ATORES***

✅ ANÁLISE SWOT
***ANÁLISE SWOT***

✅ TABELA 5W2H
***TABELA 5W2H***

✅ BPMN

✅ DOCUMENTO DE REQUISITOS (desenvolver)

✅ LANDING PAGE (desenvolver)
***LANDING PAGE*****(desenvolver)**
***(obs: desconsiderar as cédulas na cor cinza)***

✅ EAP
# EAP

✅ TAP
**1. Situação Atual**
A ONG Valentes de Davi opera há mais de dois anos , com uma missão clara de "contribuir para a formação de caráter de crianças" e um "alto impacto social"  reconhecido na comunidade. No entanto, sua infraestrutura operacional e de gestão de dados não acompanhou seu crescimento, criando gargalos significativos.

A análise do cenário "AS-IS" (como está) revela que a gestão de dados é predominantemente manual. O cadastro de novos assistidos, o arquivamento de documentos (incluindo termos de responsabilidade de menores) e o controle de frequência são feitos em papel ou planilhas não integradas. A comunicação com os pais e entre os voluntários é não estruturada, dependendo de canais avulsos.

Essa abordagem manual resulta em várias ineficiências e riscos:
Carga Administrativa: Os Voluntários gastam um tempo precioso em tarefas administrativas (papelada de cadastro, contagem manual de faltas) que compete diretamente com seu tempo de preparação de aulas, palestras e organização de treinos.

Risco de Segurança de Dados: A gestão física de documentos de menores de idade apresenta um risco elevado na segurança dos dados, podendo expor a ONG a problemas legais (LGPD) e quebrar a confiança dos Pais.

Falta de Visibilidade: Uma das ameaças identificadas é a "frequência irregular dos alunos". Sem um sistema, é impossível medir esse indicador de forma confiável, identificar padrões de evasão ou intervir proativamente.

Barreira ao Crescimento: A "alta competição por financiamento"  exige profissionalismo. A gestão manual dificulta a geração de relatórios e métricas de impacto, essenciais para atrair novos parceiros e doações.
Apesar dessas fraquezas, a ONG possui uma força interna crucial: um "uso eficiente de recursos financeiros" e uma cultura de "respeito" e "integridade", o que favorece a implementação de uma nova solução sistêmica.

**2. Justificativa do Projeto**
A existência contínua de processos manuais é um freio direto à "Visão" da ONG de "expandir de forma sustentável". O projeto justifica-se pela necessidade de transformar a gestão da ONG, movendo-a de um modelo reativo e analógico para um modelo proativo, digital e centralizado.

A implementação deste sistema atacará diretamente as Fraquezas (Gestão manual, Risco na segurança dos dados)  identificadas na análise SWOT, convertendo-as em Forças. Ao automatizar o cadastro e a frequência, o sistema liberará os Voluntários (atores-chave ) para que se concentrem em suas atividades-fim: "dar aula", "realizar palestras" e "ajudar na organização dos treinos".

Além disso, o sistema criará uma base de dados confiável. Isso permite à Diretoria tomar decisões baseadas em dados (ex: quais turmas têm mais evasão) e profissionaliza a gestão, o que é fundamental para mitigar a Ameaça da "dependência de doações voláteis" e capitalizar a Oportunidade de "novas parcerias", apresentando uma organização estruturada e transparente.

**3. Propósito do Projeto e Metas**
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

**4. Descrição do Projeto (Escopo)**
O escopo do projeto é o desenvolvimento de uma aplicação web composta por dois processos centrais, conforme mapeado nos diagramas BPMN e detalhado nos Requisitos Funcionais (RFs) . O sistema será dividido em "piscinas" (swimlanes) que definem as responsabilidades dos atores: Voluntário, Responsável e Sistema.

Módulo 1: Fluxo "Cadastro de Novo Assistido" O ator Voluntário inicia o processo no sistema (RF-001). Ele preenche uma série de formulários com os dados do assistido (RF-002), endereço (RF-003), informações médicas (RF-007) e dados do Responsável  (RF-005). O Voluntário também anexa os documentos de ambas as partes (RF-004, RF-006). Neste ponto, o Sistema gera o Termo de Responsabilidade (RF-012), que é impresso (RF-009)  e coletado. O Voluntário então digitaliza e faz o upload deste termo assinado (RF-010). O Voluntário clica em "Finalizar Cadastro" (RF-011). O Sistema executa uma validação crítica (RF-013)  para verificar se todos os campos obrigatórios foram preenchidos.

Se NÃO (Pendências): O fluxo é desviado e o Voluntário deve corrigir as pendências (RF-008).

Se SIM (Sucesso): O Sistema executa as ações de persistência: cria o registro na tabela 'ASSISTIDOS' (RF-014), salvar os anexos no servidor (RF-015), gera a matrícula única (RF-016) e envia a confirmação ao responsável (RF-017). O processo é concluído com sucesso.

Módulo 2: Fluxo "Registrar Frequência em Aula" O ator Voluntário (neste contexto, "Voluntário da Aula") inicia o processo abrindo a tela de chamada da sua turma (RF-018). O Sistema consulta o Banco de Dados e carrega a lista de assistidos inscritos naquela turma (RF-019). O Voluntário realiza a verificação de presença. Para cada aluno, o Voluntário marca "Presente" (RF-020) ou mantém o padrão "Ausente". Após a verificação, o Sistema persiste essa informação: registra "Presença" (RF-021) ou "Falta" (RF-022)  no banco de dados, associada à data da aula. Se uma "Falta" é registrada, o Sistema executa uma ação automática: incrementar o contador de faltas daquele assistido (RF-023). O Sistema então verifica se o total de faltas atingiu o limite predefinido (RNF-024).

Se SIM: O Sistema envia um alerta ao Diretor.

Se NÃO: O processo de registro de frequência é finalizado.

**5. Premissas**
As seguintes premissas são consideradas verdadeiras para o planejamento e execução do projeto:

Disponibilidade do Cliente: Assume-se que o Diretor Kaliton Mota Coutinho e os Voluntários designados terão disponibilidade para participar de reuniões de validação (como a de 29/09/2025 ), sessões de prototipação  e testes.

Ambiente Tecnológico Mínimo: Assume-se que os Voluntários terão acesso a dispositivos (computadores ou smartphones) com conexão à internet nos locais de cadastro e treino para operar o sistema web. Esta premissa é um pilar da análise de portabilidade.

Autoridade do Ponto de Contato: O Diretor Kaliton Mota Coutinho é o Product Owner (PO) do projeto, com autoridade total para "passar ao 'Grupo' quais são as necessidades"  e aprovar as entregas, evitando ambiguidades de escopo.

Infraestrutura de Hospedagem: Assume-se que, devido à "dependência de doações voláteis", o sistema deverá ser hospedado em uma infraestrutura de baixo ou zero custo (ex: plataformas Free Tier ou servidor da própria FATEC, se disponível).

Comprometimento da Equipe: Assume-se que os membros do "Grupo Tela Azul"  permanecerão no projeto durante todo o semestre letivo, dedicando as horas necessárias para a conclusão dos artefatos e do software.

**6. Restrições**
O projeto está limitado pelos seguintes fatores:

Restrição de Recursos Humanos: A equipe de desenvolvimento ("Grupo Tela Azul") é composta por estudantes do 1º Semestre de ADS Noturno. Isso impõe uma restrição severa no total de horas/semanas disponíveis para o projeto, exigindo um gerenciamento de escopo rigoroso.

Restrição Financeira (Orçamento Zero): O projeto opera com um orçamento de R$ 0,00. Esta restrição, impulsionada pela natureza da ONG ("dependência de doações voláteis" ), proíbe o uso de qualquer software proprietário, API paga, licenças ou serviços de hospedagem premium.

Restrição de Prazo (Acadêmica): O projeto possui um prazo final não-negociável, ditado pelo calendário acadêmico da FATEC Franca para a Unidade de Competência (UCE) de Engenharia de Software. Todas as entregas devem ser concluídas dentro deste período.

Restrição de Usabilidade (Adoção): O sistema deve ser visivelmente mais simples e rápido de usar do que o processo manual atual. Uma interface complexa resultará em baixa adesão pelos Voluntários, levando ao fracasso do projeto.

Restrição de Portabilidade: A solução deve ser desenvolvida para operar na infraestrutura de hardware e software existente ou minimamente viável da ONG, conforme a ser levantado no F.A.P. (Formulário de Análise de Portabilidade) .

**7. Stakeholders (Partes Interessadas)**
Diretor (Kaliton Mota Coutinho): O Patrocinador (Cliente). Responsável por "Determinar o futuro da ONG" e "Decidir a mensagem". No projeto, é o ponto focal para "dar feedback sobre o andamento"  e validar as entregas.

Voluntários: Os Usuários-Chave. Responsáveis por "Dar aula", "Realizar palestras" e, crucialmente para este sistema, "Cadastrar novos assistidos"  e realizar a chamada. Seu feedback de usabilidade é essencial.

Pais: Usuários Externos. Responsáveis por "Levar seus dependentes" para o cadastro (fornecendo os dados) e "Acompanhar as chamadas pelo sistema".

Assistidos: Os Beneficiários Finais. O objetivo do projeto é melhorar a organização para que eles possam "Participar dos treinos" e "Assistir às palestras"  com mais eficiência.

Grupo Tela Azul: A Equipe de Desenvolvimento. Responsável por "Desenvolver uma página focada em solucionar problemas" e "Consultar o diretor e voluntários"  para garantir que a solução atenda às necessidades.
FATEC Franca (Corpo Docente): A entidade Supervisora. Responsável por definir a metodologia ("Guia Projeto UCE" ) e avaliar a qualidade dos artefatos e do software produzido pelo "Grupo Tela Azul".

**8. Riscos (Iniciais)**
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

**9. Marco (Milestones / Cronograma Macro)**
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

**10. Responsabilidades**
Cliente (Diretor Kaliton Mota Coutinho):

Atribuições: Atuar como a voz do cliente e Patrocinador. É o ponto focal para a tomada de decisões estratégicas do projeto. É responsável por "Passar ao 'Grupo' quais são as necessidades da ong", validar e aprovar os artefatos (BPMN, RFs) e protótipos em tempo hábil, e garantir a disponibilidade dos Voluntários para as sessões de teste e feedback.

Equipe de Desenvolvimento (Grupo Tela Azul):

Atribuições: Responsável por todo o ciclo de vida do projeto, conforme o "Guia Projeto UCE". Isso inclui "Desenvolver uma página focada em solucionar problemas" , gerenciar o cronograma e os riscos, "Consultar o diretor e voluntários"  para refinar requisitos, realizar a codificação, garantir a qualidade do software (testes) e produzir toda a documentação formal exigida.

Usuários-Chave (Voluntários da ONG):

Atribuições: Atuar como especialistas no domínio do negócio. São essenciais para "Ajudar na organização dos treinos, planejamentos" e, no contexto do projeto, devem participar ativamente das sessões de levantamento de requisitos (entrevistas , etnografia ), testar os protótipos e o sistema final (Testes de Aceitação do Usuário - UAT), e fornecer feedback honesto e construtivo para garantir a usabilidade e o sucesso da ferramenta.
✅ DIAG. C. de USO

✅ DOC C. de USO

✅ DIAG. DE ATIVIDADES

✅ DIAG. DE MÁQ. DE ESTADO
                       **DIAGRAMA DE MÁQUINA E ESTADO**
✅ DIAG. SEQUÊNCIA

_______________________________________________________________________

✅ MATRIZ. RAST.
**Regras do negócio**

**Matriz de rastreabilidade**

✅ PORTABILIDADE
**Portabilidade
**
Dados da empresa

Infraestrutura (Hardware - Redes de Dados (quantidade e descrição))

Infraestrutura (Hardware - Redes elétrica (quantidade))

Infraestrutura (Hardware – Computadores Pessoais (quantidade e descrição))

Infraestrutura (Hardware – Periféricos (quantidade e descrição))

Licenças (Software – quantidade e descrição) 

Recursos Humanos

Descreva a configuração mínima para que a solução (que o grupo está desenvolvendo) funcione eficientemente. (Arquitetura, processador, memória, HD) + (Servidores - descrever as características – se web, arquivos, e-mail, domínio, BD).

Nome dos componentes do grupo (entrevistadores)

✅ PROP. COMERCIAL
**Proposta Comercial**
### 1. Introdução
O projeto tem como objetivo principal reduzir o retrabalho e a sobrecarga administrativa atualmente atribuída a voluntários da ONG Valentes de Davi. Por meio da digitalização das tarefas que hoje são realizadas manualmente, um novo sistema web será desenvolvido e implantado. Este sistema integrará funcionalidades de cadastro de assistidos e controle de frequência. Também será desenvolvida e hospedada uma landing page institucional, cujo objetivo é ampliar a presença digital da ONG e alcançar um público mais amplo, potencialmente interessado em seus projetos e nas ações da instituição.
### 2. Solução Proposta
O projeto tem como justificativa o desenvolvimento de um software para auxiliar em todas as etapas do processo de gestão da ONG Valentes de Davi, visando otimizar tarefas que atualmente são realizadas de forma manual, como o registro de assistidos e o controle de frequência em aulas. Esse processo exige que os voluntários gastem um tempo significativo em atividades administrativas, o que pode ser mitigado por uma solução digital.
### 3. Visão Geral da Solução
O sistema a ser desenvolvido será composto pelos seguintes módulos principais:
a. **Módulo de Cadastro de Assistidos:** Para registro completo e seguro de novos alunos e seus responsáveis. b. **Módulo de Controle de Frequência:** Para registrar presença e falta em aulas de forma ágil pelos voluntários. c. **Módulo de Gestão de Faltas:** Para monitoramento e alertas automáticos ao coordenador sobre frequência irregular. d. **Landing Page Institucional:** Para aprimorar a presença online da ONG. e. **Módulo de Usuários e Perfis:** Gerenciamento de acessos para voluntários e coordenadores. f. **Hospedagem e Configuração do Domínio:** Implantação da solução em ambiente web de baixo custo.
### 4. Escopo da Solução
Este projeto compreende o desenvolvimento de uma aplicação web abrangente e uma landing page institucional. O escopo inclui a digitalização completa do processo de cadastro de assistidos (RF-001 a RF-017), a automação do controle de frequência (RF-018 a RF-023 e RNF-024) e a implementação de alertas de evasão.
**Processos centrais abordados:**
**Cadastro de Novo Assistido:** Permite ao voluntário cadastrar dados, anexar documentos, gerar termos de responsabilidade e finalizar o cadastro com validações sistêmicas.
**Registro de Frequência em Aula:** Permite ao voluntário abrir a chamada da turma, carregar a lista de assistidos e marcar presenças/ausências, com atualização automática do contador de faltas e alertas ao coordenador.
O sistema será desenvolvido considerando a necessidade de segurança de dados (LGPD), usabilidade para voluntários e diretoria, e portabilidade para operar na infraestrutura da ONG.
### 5. Prazos
A cada semestre será realizada a entrega de uma documentação e um relatório. O prazo final de conclusão e entrega do projeto completo está previsto para **julho de 2028**.
### 6. Investimentos
Após a definição do diagrama de classes, serão detalhados os requisitos de infraestrutura e possíveis otimizações. **Atualmente, o projeto opera com orçamento de R$ 0,00 para a ONG**, utilizando tecnologias open-source e hospedagem de baixo/zero custo para garantir a sustentabilidade a longo prazo.
### 7. Nome dos alunos
Brendon Heitor Bessa Silva
Eduardo de Paula Figueiredo
Khelvin Willian Barbosa Ribeiro
Luís Felipe Carvalho de Souza
Vinicius de Souza Salviano
Vitor Gabriel dos reis Glegorio

🖥️ PROTÓTIPO LANDING PAGE

📸 FOTOS (ONG e GRUPO)