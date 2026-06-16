# Verificador MPI² — Verificação Integrada de Medicamentos Potencialmente Inapropriados para Pessoas Idosas

Ferramenta educativa e de apoio à revisão farmacoterapêutica de pessoas idosas, baseada nos principais critérios internacionais e nacionais de medicamentos potencialmente inapropriados (MPI).

---

## O que é

O **Verificador MPI²** é uma ferramenta de apoio à decisão clínica que permite, a partir da lista de medicamentos em uso e das condições clínicas do paciente, identificar:

- Medicamentos potencialmente inapropriados (Critérios de Beers AGS 2023)
- Critérios STOPP (prescrições a revisar) e START (possíveis omissões terapêuticas) — versão 3, 2023
- Interações medicamentosas clinicamente relevantes
- Duplicidades terapêuticas
- Cascatas prescritivas
- Sobrecarga de medicamentos com ação no sistema nervoso central
- Carga anticolinérgica acumulada (ACB)
- Estimativa de função renal e sinalização de ajuste de dose
- Polifarmácia

Inclui ainda:
- Alternativas farmacológicas e não farmacológicas por alerta (AGS 2025)
- Recursos para desprescrição (Deprescribing.org)
- Camada informativa de verificações dependentes de exame
- Relatório clínico exportável (PDF/impressão)
- Relatório em linguagem acessível ao paciente
- Comparação histórica com o Consenso Brasileiro de MPI 2016 (camada experimental)

---

## Como usar

A ferramenta funciona diretamente no navegador, sem instalação:

**Acesso online:** [link do GitHub Pages aqui]

Ou baixe o arquivo `index.html` e abra no navegador de sua preferência (Chrome, Firefox, Edge, Safari). Não requer conexão com internet após o download.

---

## Bases científicas

| Diretriz | Referência |
|---|---|
| Critérios de Beers AGS 2023 | 2023 AGS Beers Criteria® Update Expert Panel. *J Am Geriatr Soc.* 2023;71(7):2052–2081. doi:10.1111/jgs.18372 |
| Alternativas AGS 2025 | Steinman MA et al. *J Am Geriatr Soc.* 2025;73(9):2657–2677. doi:10.1111/jgs.19500 |
| STOPP/START v3 | O'Mahony D et al. *Eur Geriatr Med.* 2023;14(4):625–632. doi:10.1007/s41999-023-00777-y |
| STOPP/START v3 (errata) | O'Mahony D et al. *Eur Geriatr Med.* 2023;14(4):633. doi:10.1007/s41999-023-00812-y |
| Consenso Brasileiro MPI 2016 | Oliveira MG et al. *Geriatr Gerontol Aging.* 2016;10(4):168–181. doi:10.5327/Z2447-211520161600054 |

---

## Alcance da ferramenta

A ferramenta avalia os critérios identificáveis a partir de **medicamentos em uso** e **condições clínicas**. Critérios que dependem de valores de exame, sinais vitais, dose, duração ou sequência terapêutica estão fora do escopo do motor de alertas — quando pertinente, são apresentados como camada informativa ("verificações dependentes de exame"), sem geração de alerta.

A cobertura atual é de **78/133 critérios STOPP** e **33/57 critérios START** avaliáveis dentro desse escopo.

---

## Natureza e limitações

> **Esta ferramenta é educativa e de apoio à decisão clínica. Não tem caráter diagnóstico ou prescritivo. Os alertas não constituem contraindicação automática nem recomendação de suspensão imediata. A ausência de alerta não exclui riscos. Qualquer modificação do tratamento deve ser realizada por profissional habilitado.**

---

## Autoria e desenvolvimento

**Idealização e curadoria técnico-científica:** Profa. Dra. Angelina Monteiro Furtado

**Ferramentas de IA utilizadas no desenvolvimento:** Claude Pro (Anthropic, modelo Claude Sonnet 4.6) e ChatGPT Plus (OpenAI, modelo GPT-5.5 Thinking), sob curadoria técnico-científica da autora.

---

## Versão

Protótipo 1.0 — junho de 2026
