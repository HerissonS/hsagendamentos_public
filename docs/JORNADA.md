# Jornada do projeto

Como o HSAgendamentos foi pensado, construído e amadureceu, em fases.

## Fase 1 · Do problema à primeira solução

O ponto de partida foi uma necessidade real: negócios de serviços com agenda manual, faltas sem aviso, confirmações feitas uma a uma e pouca visibilidade financeira. A solução foi desenvolvida com o apoio de IA como acelerador, sempre com revisão e decisão humanas.

## Fase 2 · Segurança desde cedo

Em paralelo à minha especialização em Segurança Cibernética com foco em DevOps, passei a aplicar no projeto ferramentas usadas no mercado, como **Semgrep, Trivy e CycloneDX**. A ideia: não tratar segurança como etapa final, e sim como parte do desenvolvimento.

## Fase 3 · Automação das verificações

A verificação virou processo contínuo:

- workflows no GitHub Actions executados a cada push na branch principal e em pull requests;
- um workflow de monitoramento periódico;
- alertas por e-mail com o resultado, sem depender de verificação manual.

Veja os detalhes conceituais em [DEVSECOPS.md](DEVSECOPS.md).

## Fase 4 · Reconstrução e evolução do produto (v2)

O produto foi reorganizado numa arquitetura moderna e containerizada, com:

- agendamento de vários serviços em sequência;
- aprovações prévias por profissional;
- integrações com agenda do Google, WhatsApp e cobrança;
- painel administrativo com vendas, estoque, planos e relatórios;
- suporte a vários clientes, cada um com seu ambiente isolado.

## Fase 5 · Profissionalização da entrega

Imagens imutáveis e assinadas, ambientes por cliente, backup automático antes de cada publicação, verificação de saúde, rollback automático e relatórios por e-mail.

## Fase 6 · Evolução contínua

Versões frequentes, guiadas por feedback de clientes, com cada lançamento documentado. Veja a [linha do tempo](LINHA_DO_TEMPO.md).

## Como trabalho

- A IA acelera o desenvolvimento; a validação e a decisão continuam sendo minhas.
- Segurança como parte do ciclo de desenvolvimento.
- Mudanças pequenas, verificadas e automatizadas.
- Aprender na prática: é aplicando que a teoria vira solução.
