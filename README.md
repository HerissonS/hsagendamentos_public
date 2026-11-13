# HSAgendamentos

> Plataforma proprietária de agendamentos e gestão para negócios de serviços, em produção, projetada e operada de ponta a ponta com foco em **DevOps e DevSecOps**.

> [!NOTE]
> Este repositório é **somente documental** (portfólio). O código-fonte é privado e proprietário; aqui não há código, regras de negócio detalhadas, endpoints, credenciais ou configurações de infraestrutura.

**Autor:** Herisson ([@HerissonS](https://github.com/HerissonS))
**Status:** Em produção · versão estável 2.x · código fechado

---

## O que é

O HSAgendamentos é uma plataforma completa para negócios que vivem de agenda (barbearias, clínicas, estúdios etc.). Ela cobre desde o agendamento online feito pelo cliente final até a gestão interna da operação: equipe, serviços, vendas, estoque, planos e relatórios.

Nasceu de uma necessidade real: o primeiro cliente, uma barbearia, precisava substituir processos manuais por algo confiável, e o produto evoluiu para uma plataforma preparada para atender **vários clientes** (modelo multi-cliente), cada um com seu próprio ambiente isolado.

## Para quem quer contratar o produto

Se você tem um negócio baseado em agenda e quer reduzir faltas, automatizar confirmações e ter a operação organizada, o HSAgendamentos é uma solução pronta, **mantida com práticas profissionais de segurança e entrega**: atualizações testadas, com backup e rollback automáticos. Fale comigo pelo perfil abaixo.

## Visão geral das funcionalidades

- **Agendamento online** com experiência moderna e responsiva, inclusive de vários serviços em sequência.
- **Confirmação e reagendamento** pelo próprio cliente, por link enviado via WhatsApp.
- **Aprovação prévia** de atendimentos que exigem validação do profissional, com central de aprovações.
- **Notificações automáticas** por WhatsApp e e-mail (confirmações, lembretes, pesquisas e reativação de clientes).
- **Integração com agenda do Google** para sincronizar a agenda dos profissionais.
- **Painel administrativo** com equipe, serviços, produtos, estoque, vendas, planos e relatórios.
- **Cobrança integrada** com gateway de pagamentos.
- **Identidade visual configurável** por cliente.

## Segurança como parte do produto

O desenvolvimento combina o apoio de IA com **validação contínua e automatizada**. Com a especialização em Segurança Cibernética com foco em DevOps, adotei ferramentas usadas no mercado, como **Semgrep, Trivy e CycloneDX**, integradas a workflows no GitHub Actions que rodam a cada push e pull request, com monitoramento periódico e alertas por e-mail.

> **A IA acelera o desenvolvimento, e a segurança é validada de forma automatizada a cada mudança.** Segurança faz parte do ciclo de desenvolvimento, não é uma preocupação depois da entrega.

Conheça a história completa em [docs/JORNADA.md](docs/JORNADA.md).

## Tecnologias (visão de alto nível)

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

Também fazem parte do ecossistema: Evolution API (WhatsApp), Google Calendar, gateway de pagamentos, Semgrep, Trivy, CycloneDX e Cosign.

## Foco em DevOps e DevSecOps

Mais do que o produto em si, este projeto é meu laboratório e vitrine de **entrega confiável e segura de software**. Detalhes em [docs/DEVSECOPS.md](docs/DEVSECOPS.md). Em resumo:

- **Pipeline de CI/CD** automatizado no GitHub Actions.
- **Segurança embutida no pipeline:** análise estática de código, varredura de vulnerabilidades e configurações, geração de inventário de componentes (SBOM) e relatório consolidado.
- **Imagens de contêiner imutáveis**, publicadas em registry e **assinadas criptograficamente** (sem chaves persistentes).
- **Deploy seguro por cliente**, com ambientes isolados e segredos separados.
- **Backup automático antes de cada deploy**, verificação de saúde pós-deploy e **rollback automático** em caso de falha.
- **Relatórios e alertas** por e-mail e resumo de execução, com comparação do antes e depois.
- **Gestão de configuração** que detecta novas variáveis necessárias e avisa quando é preciso ação manual.

## Documentação deste repositório

| Documento | Conteúdo |
|---|---|
| [docs/JORNADA.md](docs/JORNADA.md) | Como o projeto foi pensado e as fases de desenvolvimento |
| [docs/DEVSECOPS.md](docs/DEVSECOPS.md) | Abordagem de DevOps e segurança |
| [docs/LINHA_DO_TEMPO.md](docs/LINHA_DO_TEMPO.md) | Evolução resumida das versões |
| [docs/APRENDIZADOS.md](docs/APRENDIZADOS.md) | Lições aprendidas |

## Contato

Interessado em conversar sobre o projeto? Entre em contato pelo meu perfil: [@HerissonS](https://github.com/HerissonS).

---

© Herisson. Todos os direitos reservados. O HSAgendamentos é um software proprietário; este repositório contém apenas material descritivo.

