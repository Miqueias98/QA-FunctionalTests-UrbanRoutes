🧩 Projeto: Testes Funcionais – Aplicativo Urban Routes

Repositório sugerido: QA-FunctionalTests-UrbanRoutes

⸻

🧠 Visão Geral

Este projeto apresenta a execução de testes funcionais manuais realizados no aplicativo Urban Routes, com o objetivo de validar os principais comportamentos da interface de mapa e garantir que as funcionalidades estejam de acordo com os requisitos do sistema.

O documento contém 24 casos de teste e 6 bugs identificados, cobrindo desde interações simples de zoom e rolagem até modos avançados como Street View e Relevo.

⸻

🎯 Objetivo

Garantir a qualidade funcional e a conformidade visual do aplicativo Urban Routes, verificando o correto funcionamento dos elementos de interface e a resposta do sistema às ações do usuário.

As principais metas deste projeto foram:
	•	Verificar se os componentes de navegação e visualização funcionam conforme o design esperado.
	•	Validar a responsividade dos campos de entrada (“De” e “Para”) e exibição de endereços.
	•	Identificar e registrar falhas com base em comportamento real vs. esperado.

  🧪 Estrutura de Testes

  Tipo de Teste
Descrição
Testes Funcionais
Verificação do comportamento de botões, campos e modos do mapa.
Testes de Interface
Checagem de layout e elementos visuais conforme o design.
Testes de Fluxo
Validação de interações sequenciais (abrir, clicar, preencher, limpar campos).

📋 Principais Casos de Teste
	•	Rolagem e zoom do mapa.
	•	Interação com os campos “De” e “Para”.
	•	Exibição e limpeza de endereços.
	•	Exibição de objetos 3D, parques, pontos de referência e estações de metrô.
	•	Ativação dos modos Relevo, Satélite e Street View.
	•	Abertura e fechamento da janela de informações.

  🐞 Bugs Identificados

  ID do Bug
Descrição
Severidade
Resultado Esperado
Resultado Real
URBANROU-01
Lista de estações não abre ao digitar “Subway” no campo “Para”.
Pequeno
Lista de estações exibida.
Campo fica vermelho e nada acontece.

PINOENDE-02
Pino de endereço não aparece após preencher o campo “De”.
Grave
Zoom no pino de endereço.
Nenhum movimento no mapa.

BUGPINOEND-03
Pino de endereço não aparece ao preencher o campo “Para”.
Grave
Zoom no pino de endereço.
Nenhum movimento no mapa.

LOGOURBAN-04
Logotipo “Urban Routes” não exibe informações do aplicativo.
Pequeno
Exibir informações.
Nenhuma resposta.

TITULOSMAP-05
Títulos das áreas do mapa são clicáveis.
Trivial
Nenhuma ação ao clicar.
Abre aba com informações indevidas.

CAMPODE-06
Campo “De” não fica vazio ao clicar.
Grave
Campo vazio.
Sugestão automática permanece.

🧰 Ferramentas e Recursos Utilizados
	•	Planilha Google Sheets (para registro de casos e bugs)
	•	Técnicas de teste funcional manual
	•	Critérios de aceitação baseados em comportamento esperado

⸻

🧠 Aprendizados

Durante este projeto, foram desenvolvidas e aprimoradas as seguintes competências:
	•	Escrita e execução de casos de teste manuais claros e objetivos.
	•	Registro e priorização de bugs funcionais.
	•	Comunicação eficiente dos resultados de QA.
	•	Compreensão prática do ciclo planejar → executar → reportar.
	•	Organização e rastreabilidade entre casos de teste e defeitos.

⸻

📊 Resultado Final
	•	Casos de teste executados: 24
	•	Casos aprovados: 18
	•	Casos reprovados: 6
	•	Bugs registrados: 6 (3 graves, 2 pequenos, 1 trivial)

⸻

👤 Autor

Miqueias Ferreira
Analista de QA | Testes Manuais | Automação em formação
