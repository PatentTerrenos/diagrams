## ✅ Requisitos Funcionais (ISO/IEC/IEEE 29148:2018)Requisitos Funcionais



| ID     | Título                                | Descrição                                                                                                                 | Tipo      | Prioridade | Origem                                   | Critério de Aceitação                                                                           |
| ------ | ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- | --------- | ---------- | ---------------------------------------- | ----------------------------------------------------------------------------------------------- |
| RF-001 | Cadastro de Terreno                   | O sistema deverá permitir ao administrador cadastrar terrenos utilizando coordenadas geográficas (latitude, longitude).   | Funcional | Alta       | Descrição do sistema e análise de escopo | O sistema deverá executar corretamente a funcionalidade: cadastro de terreno.                   |
| RF-002 | Cadastro Imutável via Blockchain      | O sistema deverá registrar os cadastros de terrenos de forma imutável na blockchain, assegurando a integridade dos dados. | Funcional | Alta       | Descrição do sistema e análise de escopo | O sistema deverá executar corretamente a funcionalidade: cadastro imutável via blockchain.      |
| RF-003 | Análise em Tempo Real                 | O sistema deverá realizar análise contínua e em tempo real de imagens de satélite sobre os terrenos cadastrados.          | Funcional | Alta       | Descrição do sistema e análise de escopo | O sistema deverá executar corretamente a funcionalidade: análise em tempo real.                 |
| RF-004 | Detecção de Alterações com IA         | O sistema deverá utilizar IA para detectar alterações físicas em terrenos com base em imagens de satélite.                | Funcional | Alta       | Descrição do sistema e análise de escopo | O sistema deverá executar corretamente a funcionalidade: detecção de alterações com IA.         |
| RF-005 | Identificação de Obras Irregulares    | O sistema deverá identificar e classificar atividades e obras irregulares automaticamente.                                | Funcional | Alta       | Descrição do sistema e análise de escopo | O sistema deverá executar corretamente a funcionalidade: identificação de obras irregulares.    |
| RF-006 | Geração de Alertas de Irregularidade  | O sistema deverá emitir alertas ao proprietário e à administração sempre que forem identificadas obras irregulares.       | Funcional | Alta       | Descrição do sistema e análise de escopo | O sistema deverá executar corretamente a funcionalidade: geração de alertas de irregularidade.  |
| RF-007 | Notificação de Proprietário           | O sistema deverá enviar notificações automáticas ao proprietário em caso de detecção de anomalias no terreno.             | Funcional | Alta       | Descrição do sistema e análise de escopo | O sistema deverá executar corretamente a funcionalidade: notificação de proprietário.           |
| RF-008 | Registro e Validação de Documentos    | O sistema deverá permitir o envio de documentos comprobatórios e realizar a sua validação quanto à titularidade.          | Funcional | Alta       | Descrição do sistema e análise de escopo | O sistema deverá executar corretamente a funcionalidade: registro e validação de documentos.    |
| RF-009 | Consulta de Propriedades              | O sistema deverá permitir que usuários consultem informações atualizadas sobre a titularidade de um terreno.              | Funcional | Alta       | Descrição do sistema e análise de escopo | O sistema deverá executar corretamente a funcionalidade: consulta de propriedades.              |
| RF-010 | Consulta de Histórico de Titularidade | O sistema deverá permitir a consulta do histórico completo de titularidade de cada terreno.                               | Funcional | Alta       | Descrição do sistema e análise de escopo | O sistema deverá executar corretamente a funcionalidade: consulta de histórico de titularidade. |
| RF-011 | Registro de Eventos de Propriedade    | O sistema deverá registrar eventos como fraude, perda, venda ou alteração de titularidade sem apagar dados anteriores.    | Funcional | Alta       | Descrição do sistema e análise de escopo | O sistema deverá executar corretamente a funcionalidade: registro de eventos de propriedade.    |



## pontos em aberto:

- (Como resolver conflitos, em casos em que há 2 documentos para a mesma residência?)
Há necessidade de intervenção humana (administração) para validação da titularidade;

- Os sistemas devem estar correlacionados de maneira que no futuro os documentos para a 
 titularidade sejam gerados na plataforma;

- Uma vez que o cadastro é imutável, caso uma titularidade for registrada de maneira errada ou fraudulenta
  o sistema não apaga esse histórico, porém fica registrada a operção
  (fraude, perda, venda, ou alguma outra causa que fez com que a pessoa dexasse de ser o proprietário);

- ✅ A principio o registro deverá ser feito acompanhado de especialista, pelas questões de cordenadas geográfica, dimensões e documentos (Orgãos da administração no caso)
- ✅ O cliente poderá acompanhar o processo e o estado do cadastro, bem como consultar titularidades e outras operações que não necessitem intervenção de um especialista
