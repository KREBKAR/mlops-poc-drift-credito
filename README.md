# POC — Monitoramento de Drift em Modelos de Crédito
**FGV MBA IA & Analytics | Disciplina: MLOps | Karen Krebs | Junho/2026**

---

## O que é esta POC

Esta prova de conceito demonstra o funcionamento de um sistema de monitoramento automático de drift aplicado a um modelo de concessão de crédito. Ela foi desenvolvida como complemento prático ao Trabalho Individual de MLOps, com foco na Onda 1 do plano de evolução: implementar feedback proativo antes que o negócio perceba a degradação do modelo.

A base utilizada é o German Credit Dataset, público e amplamente usado em estudos de crédito. Os dados são sintéticos — sem qualquer informação real do Banco A.

---

## Como rodar

1. Acesse [https://colab.research.google.com](https://colab.research.google.com)
2. Clique em `Arquivo` → `Fazer upload de notebook`
3. Selecione o arquivo `MLOPS_Analise_de_credito_karen_krebs_v2.ipynb`
4. Clique em `Ambiente de execução` → `Executar tudo`

Tempo estimado: 3 a 5 minutos.

---

## O que o notebook faz

| Bloco | O que acontece |
|---|---|
| Importações | Carrega as bibliotecas necessárias |
| Base de dados | Carrega o German Credit Dataset |
| Base de referência | Define o perfil original dos clientes |
| Simulação de drift | Simula mudança no perfil dos clientes ao longo do tempo |
| Visualização | Compara graficamente os dois perfis |
| Detecção com KS | Detecta drift estatisticamente com teste KS |
| Alertas automáticos | Gera alertas quando drift é confirmado |
| Evidently AI | Gera relatório visual automático de drift |

---

## Arquivos

- `MLOPS_Analise_de_credito_karen_krebs_v2.ipynb` — notebook principal
- `relatorio_evidently.html` — relatório gerado pelo Evidently AI

---

## Declaração

Desenvolvido com apoio de IA Generativa (Claude, Anthropic), conforme declarado no trabalho individual.
