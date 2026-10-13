# ICMS Ceará por NCM — Consulta e Leitor de XML (NF-e / NFC-e)

Site estático (arquivo único, 100% local, sem servidor e sem internet) para consultar a
tributação do ICMS no estado do Ceará por NCM, a partir da tabela SISCOEX.

## O que faz

- **Consulta por NCM ou descrição** — 14.225 registros (11.841 ativos): regime SISCOEX,
  agregação/alíquota, pauta fiscal, rotina e inciso do RICMS, artigos e fundamentação legal.
- **Leitor de XML de NF-e/NFC-e** — por arquivo(s), pasta ou `.zip` (descompactação no
  navegador): agrupa NCMs × tributação ICMS-CE, com caixas de ICMS sem ST / ICMS ST
  (soma dos valores dos itens), ISS com/sem retenção digitáveis e total geral.
- **Camada de vigência (auditoria 10/2026)** — selos automáticos: alíquota histórica 18%
  (vigente 20% desde 01/01/2024, Lei 18.305/2023), NCM extinto na TIPI vigente (reforma
  HS 2022), prazo de benefício vencido, carga efetiva com FECOP, regime monofásico
  (LC 192/2022) e regra geral de 20% para NCM não localizado.
- **Seção Atualizações 2026** — decretos CE (37.422, 37.280, 37.500, 37.460, INs 13 e
  01/2026) e convênios CONFAZ com impacto na base.
- Exportação dos resultados em CSV.

## Como usar

Abra o `index.html` no Chrome ou Edge. Não requer instalação.

## Bases e fontes

- `Tabela_produtos_NCM_ICMS.xlsm`, aba "PRODUTOS SISCOEX ATIVOS" (atualização 08/2023);
- TIPI vigente (Dec. 11.158/2022 e alterações) para marcação de NCMs extintos;
- RICMS/CE (Dec. 33.327/2019), Lei 18.305/2023, LC 192/2022, SEFAZ/CE e CONFAZ.

## Aviso

Uso orientativo. A base original é de 08/2023 e os selos de vigência não substituem a
leitura da legislação nem a análise do caso concreto (origem, operação, CNAE, regime
tributário). Sempre confirme no RICMS/CE e nas normas vigentes.
