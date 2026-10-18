# AEGIS

**Área:** Cibersegurança · **Status:** conceito documentado, ainda sem implementação.

AEGIS é uma plataforma modular de **monitoramento, defesa e investigação digital**. A inspiração vem de centrais tecnológicas de ficção científica, mas a implementação será uma ferramenta original, com funções reais e documentadas.

## Objetivo

Reunir sinais de segurança de um computador, identificar alterações relevantes, preservar registros para análise e apoiar ações defensivas previamente autorizadas.

## Primeira versão pretendida

- Monitorar diretórios escolhidos pelo usuário e verificar alterações de integridade.
- Manter um histórico local com data, origem e tipo de evento.
- Exibir alertas simples e permitir revisar evidências.
- Incluir testes automatizados e um modelo de permissões explícito.

## Evolução possível

Correlacionar eventos de processos e rede, adicionar regras de detecção, classificação de ocorrências e mecanismos seguros de resposta. Não será tratado como antivírus completo ou EDR comercial enquanto tais capacidades não forem comprovadas.

**Stack a avaliar:** Python, SQLite, FastAPI e uma interface web/desktop leve. A escolha final depende do primeiro protótipo.

> Projeto independente em planejamento. Nenhuma detecção, defesa ou auditoria está implementada ainda. Testes de segurança apenas em equipamentos próprios ou expressamente autorizados.
