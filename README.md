# TPAE-Endividamento

Projeto aplicado de extensão – PSAE00320 Técnicas de Pesquisa e Análise Econômica II (2026.2)

## Equipe
- Leonardo Henrique Serra
- Luan Emanuel
- Kalani Gabrielle

## Problema de pesquisa
> *A preencher: qual pergunta o projeto busca responder sobre endividamento? Qual o recorte (população, região, período)?*

## Fontes de dados
Resumo abaixo; detalhes em [`docs/inventario_fontes.md`](docs/inventario_fontes.md).

| Base | Instituição | Cobertura | Licença |
|------|-------------|-----------|---------|
|  Abras/NielsenIQ e Banco Central) | https://www.abras.com.br/economia-e-pesquisa/monitoramento-semanal-nielseniq-e-abras/2026| Variações semanais de consumo de alimentos e queda de transações Pix citadas no documento.| |
| Câmara dos Deputados|https://www.congressonacional.leg.br/materias/medidas-provisorias/-/mpv/175871|Notícia sobre a MP nº 1.394, de 25/09/2026, conforme documento.||
|CNC / Portal do Comércio (Peic)|https://portaldocomercio.org.br/acoes-institucionais/cnc-inadimplencia-e-endividamento-das-familias-brasileiras-recuam-em-setembro/|Percentual de famílias endividadas e inadimplentes em setembro de 2026.||


## Estrutura do repositório
```
README.md
.gitignore
.env.example        # modelo de variáveis de ambiente (sem valores reais)
data/raw/           # dados originais permitidos (bases grandes/restritas NÃO são versionadas)
data/processed/     # dados tratados (regeneráveis pelos notebooks)
notebooks/          # aquisição, tratamento e análise
docs/               # inventário, dicionário, plano de aquisição, memórias
outputs/            # tabelas, gráficos e produtos
```

## Como reproduzir
1. Clonar o repositório.
2. Instalar as dependências *(a definir: requirements.txt ou renv)*.
3. Se houver chaves de API, copiar `.env.example` para `.env` e preencher.
4. Executar os notebooks de `notebooks/` em ordem numérica (ex.: `01_aquisicao`, `02_tratamento`, `03_analise`).
5. Os arquivos baixados serão gravados em `data/raw/` (ignorado pelo Git). Ver [`data/raw/README.md`](data/raw/README.md).

## Segurança
Nunca versionar senhas, tokens, chaves, dados pessoais, documentos internos ou bases restritas.

## Tarefas
Acompanhadas em *Issues* do GitHub, com responsável e prazo.

## Uso de IA
Para a formatação do README, para a cunhagem do modelo apenas.
