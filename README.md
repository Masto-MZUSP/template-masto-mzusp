<!--
COMO USAR ESTE MODELO

1. Substitua todas as informações entre [colchetes].
2. Preencha o arquivo CITATION.cff com os dados bibliográficos do projeto.
3. Mantenha apenas as seções aplicáveis ao projeto e remova as instruções entre comentários antes da publicação.
4. Escolha as licenças adequadas: LICENSE (MIT) para código e LICENSE-docs.md (CC BY 4.0) para textos, protocolos e figuras.
5. Configure os topics do repositório na seção "About" do GitHub, seguindo as regras da organização descritas em CONTRIBUTING.md.
6. Documente as versões dos programas, pacotes e dependências, além dos parâmetros necessários para reproduzir as análises.
-->

# [Título do projeto]

[Apresente brevemente o contexto científico, a pergunta de pesquisa e os principais objetivos do projeto, bem como o conteúdo deste repositório. Informe quais materiais, dados, scripts ou ferramentas estão disponíveis.]

**Tipo:** [pesquisa | análise | pipeline | protocolo | dados | curadoria | tutorial | ensino]

**Status:** [em desenvolvimento | concluído | estável | arquivado]

**Período:** [AAAA–AAAA]

## Equipe e contribuições

| Nome | Contribuição | Vínculo | ORCID |
| --- | --- | --- | --- |
| [Nome Sobrenome] | [Desenvolvimento / execução / autoria] | [Mestrado / Doutorado / IC / Pós-doc] | [0000-0000-0000-0000] |
| Joyce Rodrigues do Prado | Orientação / supervisão | Docente | 0000-0002-2025-5479 |

**Instituição:** Laboratório de Mastozoologia, Museu de Zoologia da Universidade de São Paulo (MZUSP).

## Financiamento

<!-- Informe as fontes de financiamento relacionadas ao projeto, incluindo o nome completo da agência, número do processo e modalidade. Inclua bolsas individuais dos integrantes quando aplicável. -->

- [Fundação de Amparo à Pesquisa do Estado de São Paulo (FAPESP), processo nº AAAA/NNNNN-N — modalidade.]
- [Coordenação de Aperfeiçoamento de Pessoal de Nível Superior (CAPES), Código de Financiamento 001.]
- [Conselho Nacional de Desenvolvimento Científico e Tecnológico (CNPq), processo nº número.]

As opiniões, hipóteses, conclusões e recomendações expressas neste material são de responsabilidade dos autores e não necessariamente refletem a visão das agências de fomento.

## Estrutura do repositório

```text
.
├── data/           # Dados de entrada e metadados
├── scripts/        # Scripts e códigos utilizados
├── results/        # Resultados gerados pelas análises
├── figures/        # Figuras e visualizações
├── docs/           # Documentação complementar
└── environment/    # Arquivos de configuração do ambiente
```

<!-- Adapte a estrutura acima à organização real do projeto. Descreva brevemente a finalidade dos diretórios e mantenha a nomenclatura consistente. -->

## Dados de entrada

[Descreva os conjuntos de dados utilizados no projeto, sua origem e como acessá-los. Inclua identificadores de acesso, quando disponíveis.]

| Conjunto de dados | Descrição | Repositório | Origem / acesso |
| --- | --- | --- | --- |
| [Nome do conjunto] | [Descrição] | [BioProject, SRA, GenBank, Zenodo ou outros repositórios] | [Repositório, DOI ou identificador] |

Dados muito grandes (>50 MB) ou sensíveis (dados pessoais, coordenadas precisas de espécies ameaçadas, etc) não devem ser versionados diretamente no GitHub.

## Ambiente computacional

### Programas e dependências

[Informe os programas, linguagens, pacotes e respectivas versões necessários para executar o projeto.]

| Programa / pacote | Versão | Finalidade |
| --- | --- | --- |
| [Programa] | [Versão] | [Finalidade] |
| [Pacote] | [Versão] | [Finalidade] |

### Configuração do ambiente

[Descreva como instalar as dependências e configurar o ambiente necessário para executar os scripts.]

Sempre que possível, disponibilize arquivos de configuração que permitam reconstruir o ambiente computacional, como:

- `environment.yml` — Conda;
- `renv.lock` — R;
- `requirements.txt` — Python;
- `Dockerfile` — Docker.

## Fluxo de trabalho

[Apresente a sequência de execução dos scripts e procedimentos necessários para reproduzir as análises. Indique as dependências entre as etapas, os arquivos de entrada e os resultados gerados.]

| Ordem | Script / procedimento | Descrição | Entrada | Saída |
| --- | --- | --- | --- | --- |
| 01 | [script.R] | [Descrição] | [Arquivo] | [Arquivo] |
| 02 | [script.py] | [Descrição] | [Arquivo] | [Arquivo] |
| 03 | [script.sh] | [Descrição] | [Arquivo] | [Arquivo] |

## Publicações relacionadas

[Liste artigos, preprints, trabalhos acadêmicos ou outros produtos científicos relacionados ao projeto.]

- [Autor(es)] ([ano]). [Título]. [Periódico]. [DOI ou link].

<!-- Atualize esta seção conforme os resultados do projeto forem publicados. -->

## Como citar

As informações bibliográficas deste projeto estão disponíveis no arquivo `CITATION.cff` e no botão **"Cite this repository"** do GitHub.

Após a disponibilização de um *release* com DOI, inclua a referência correspondente:

> [Autores] ([ano]). [Título] (versão [x.y]). Zenodo. https://doi.org/[DOI]

## Histórico de versões

Consulte a seção *Releases* do GitHub para acessar as versões disponibilizadas deste projeto.

<!-- Registre alterações relevantes nos dados, scripts, parâmetros e procedimentos que possam afetar a reprodução dos resultados. -->

## Licença

- **Código e scripts:** MIT License (`LICENSE`).
- **Textos, protocolos, figuras e demais materiais não relacionados a código:** Creative Commons Atribuição 4.0 Internacional (CC BY 4.0) (`LICENSE-docs.md`).

Consulte os respectivos arquivos para conhecer as condições de uso, modificação e distribuição dos materiais.
