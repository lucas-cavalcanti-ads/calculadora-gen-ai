# AI MULTI-AGENT SYSTEM PLAYBOOK

## OBJETIVO

Este repositório utiliza um sistema multi-agente para construir software de forma estruturada, simulando uma squad de engenharia completa.

O objetivo é:

* Garantir qualidade
* Evitar decisões precipitadas
* Promover colaboração entre especialistas
* Produzir código pronto para execução

---

## ESTRUTURA DO SISTEMA

Os agentes estão definidos em:

/agents/

Cada agente possui:

* papel específico
* responsabilidades claras
* forma de interação com outros agentes

---

## AGENTES DISPONÍVEIS

* Product Manager
* Tech Lead
* Facilitador
* Software Engineer
* Software Reviewer
* QA
* DevOps
* Tech Writer
* Quality Guard

---

## PRINCÍPIO FUNDAMENTAL

Nenhum problema deve ser resolvido diretamente.

Todo trabalho deve seguir um fluxo estruturado de agentes.

---

## FLUXO PADRÃO

1. Product Manager → define problema
2. Tech Lead → define arquitetura
3. Facilitador → consolida decisão
4. Tech Lead → gera plano (tasks)
5. Software Engineer → implementa
6. Reviewer → revisa
7. QA → valida
8. DevOps → prepara execução
9. Tech Writer → documenta
10. Quality Guard → valida sistema completo

---

## REGRAS DE EXECUÇÃO

* Sempre seguir o fluxo de agentes
* Não pular etapas
* Não executar código sem planejamento
* Validar antes de avançar
* Iterar quando necessário

---

## COLABORAÇÃO ENTRE AGENTES

* Agentes podem questionar decisões anteriores
* Conflitos devem ser resolvidos pelo Facilitador
* Outputs devem ser claros e acionáveis

---

## CRITÉRIOS DE QUALIDADE

Antes de finalizar qualquer tarefa:

* O código deve estar funcional
* Deve haver validação (QA)
* Deve haver revisão
* Deve haver documentação mínima

---

## COMO UTILIZAR

Para iniciar uma tarefa, use:

"Use o sistema de agentes definido neste PLAYBOOK para resolver o seguinte problema: <descrição>"

---

## DIRETRIZES IMPORTANTES

* Prefira simplicidade
* Evite overengineering
* Priorize clareza
* Produza artefatos reais (código, arquivos, docs)

---

## OBJETIVO FINAL

Produzir software:

* funcional
* bem estruturado
* validado
* pronto para uso real
