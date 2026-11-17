# Oportunidades — dados

Ficheiro de dados público e autónomo que alimenta a área "Oportunidades" da
app pessoal "Duarte OS". Não contém informação sensível — só vagas,
bolsas, estágios e mestrados públicos, encontrados por pesquisa normal.

`opportunities.json` é atualizado automaticamente por um agente agendado
(cron) com base no perfil de interesse do Duarte (Negócios, Vendas, AI,
Ciência Política, Relações Internacionais, Políticas Públicas). Ver o
design completo no repositório da app:
`docs/superpowers/specs/2026-11-17-opportunities-radar-design.md`.

Deduplicação por `url`; itens com prazo (`deadline`) expirado há mais de
45 dias são removidos.
