# 🚚 Dashboard de Logística e Supply Chain (OTIF)

## 🏢 O Desafio de Negócio
Uma grande transportadora global precisava monitorar a eficiência de suas entregas, mas enfrentava um problema de dados: o sistema registrava as datas de envio, mas **não possuía uma "Data Prometida" clara** para comparação. Sem essa meta, era impossível calcular o **OTIF** (*On Time In Full* - Entregue no Prazo e Completo) e identificar gargalos reais na operação.

## 🛠️ Solução Implementada
Atuei como Analista de BI para estruturar as regras de negócio e desenvolver um painel de controle estratégico.
* **Engenharia de Dados (Power Query):** Criação de regras de SLA (*Service Level Agreement*) baseadas no Modal de Envio (ex: *Same Day* = 0 dias, *Standard* = 5 dias) para gerar datas de entrega esperadas.
* **Modelagem e DAX:** Cálculo de métricas de performance (Taxa de Sucesso vs. Atrasos) e inteligência de tempo.
* **UX/UI Design:** Interface moderna com navegação por **Menu Lateral** (Sidebar) e aplicação de **Drill-through** (Detalhamento) para análise profunda por país.

## 📊 Principais Funcionalidades
* **Cálculo de OTIF Real:** Monitoramento da taxa de sucesso global (74,6%) contra a meta de mercado (90%).
* **Mapa de Calor Global:** Visualização geográfica dos países com maiores índices de atraso.
* **Análise de Tendência:** Gráfico histórico para identificar se a performance está melhorando ou piorando ano a ano.
* **Navegação Drill-through:** Recurso interativo que permite clicar em um país no mapa e ser direcionado para uma visão detalhada dos pedidos e produtos específicos daquela região.

## 💡 Insights Descobertos
1.  **Gargalo no Modal Padrão:** O tipo de frete "Standard Class", apesar de ter o maior prazo (5 dias), é o maior ofensor da meta, indicando falhas operacionais na gestão de alto volume.
2.  **Alta Performance no Expresso:** As entregas "Same Day" e "First Class" possuem índices de OTIF superiores, sugerindo que a infraestrutura rápida funciona bem.
3.  **Tendência de Queda:** A análise temporal revelou uma queda na pontualidade nos últimos 2 anos, alertando para a necessidade de revisão de processos.

---
**Ferramentas:** Microsoft Power BI, Power Query, DAX.
**Desenvolvido por:** Guilherme Risson
