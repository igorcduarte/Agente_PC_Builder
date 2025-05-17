# Assistente de Montagem de PCs com IA
Este projeto implementa um sistema baseado em agentes de Inteligência Artificial para auxiliar na escolha e montagem de computadores personalizados, atendendo às necessidades e orçamento fornecidos pelo usuário. O sistema é composto por sete agentes que trabalham de forma colaborativa, desde a coleta de requisitos até a simulação de desempenho


## Fluxo do Sistema

**Agente Coletor de Necessidades**: Coleta informações sobre as necessidades do usuário (uso previsto) e o orçamento disponível.

**Agente Pesquisador de Componentes**: Busca e filtra componentes compatíveis com base nos requisitos coletados.

**Agente Planejador de Build**: Planeja uma configuração de PC ideal com os componentes pesquisados.

**Agente Validador Técnico**: Verifica a compatibilidade e a adequação da build planejada.

**Agente Otimizador de Preços**: Busca os melhores preços para os componentes em lojas confiáveis e apresenta o custo total.

**Agente Simulador de Performance**: Simula o desempenho da configuração planejada em diferentes cenários (jogos, edição de vídeo, multitarefa, etc.).

**Agente Revisor e Sugestões Extras**: Faz uma revisão técnica final e sugere melhorias opcionais.

## Execução do Sistema

Ao iniciar o programa, o usuário fornece:
&nbsp;
* Necessidades: Descrição de como pretende usar o computador. Ex: jogos, edição de vídeo, trabalho, etc.
&nbsp;
* Orçamento: Valor máximo disponível para a montagem. **Deve ser escrito da seguinte forma: Ex. 4.000**
&nbsp;

O sistema então realiza as seguintes etapas:
&nbsp;
1. O Agente Coletor de Necessidades interpreta os dados fornecidos pelo usuário.
&nbsp;
2. O Agente Pesquisador de Componentes encontra peças relevantes.
&nbsp;
3. O Agente Planejador de Build cria um plano inicial para o PC.
&nbsp;
4. O Agente Validador Técnico revisa a build quanto à compatibilidade.
&nbsp;
5. O Agente Otimizador de Preços busca pelos melhores valores em lojas confiáveis.
&nbsp;
6. O Agente Simulador de Performance estima o desempenho baseado na build final.
&nbsp;
7. O Agente Revisor e Sugestões Extras oferece uma revisão final e melhorias adicionais.

## Ferramentas e Modelos Utilizados
&nbsp;
* Google Search API: Para busca de componentes e preços.
&nbsp;
* Modelos de IA: Baseados no modelo "gemini-2.0-flash" para simulação e planejamento.
&nbsp;
## Resultados Gerados
&nbsp;
* Tabela de Componentes Otimizados: Com os menores preços e links para compra.
&nbsp;
* Estimativas de Performance: FPS em jogos, tempos de renderização e eficiência em multitarefas.
&nbsp;
* Relatório Final: Revisão e sugestões extras para melhorar o setup.
&nbsp;

## Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para mais informações.
