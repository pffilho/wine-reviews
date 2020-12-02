# wine-reviews
Base kaggle de vinhos pontuados. Ingestão utilizando formato parquet e análise dos dados

## Premissas
1. Ter o Jupiter notebook instalado. Para executar no Google Collab é necessário subir arquivo no drive e adaptar os apontamentos de pastas.
2. Baixa o notebook em uma pasta local.
3. Dentro da mesma pasta criar a pastar "parquet_files" - local onde o processo de ingestão irá armazenar os dados particionados
4. Dentro da mesma pasta baixar o dataset do Kaggle -  https://www.kaggle.com/zynicide/wine-reviews ou baixar o arquivo zipado disponível neste repositório

## Algumas Conclusões neste trabalho

* O formato parquet ocupa menos disco, o acesso aos dados é muito mais rápido (I/O), muito útil para recuperar dados e uso nas visualizações, e fácil de implementar.

* Maioria dos vinhos possuem boa pontuação
* Austrália, França, Itália, Portugal e US -> possuem os vinhos mais bem votados
* 397 vinhos possuem a pontuação miníma
* Os vinhos mais caros são franceses
* Existem vinhos baratos com boa pontuação
* Maioria dos vinhos brasileiros com pontuação baixa

## Próximos passos
* Aprofundar nas análises e buscar padões
* Futuramente implementar um modelo ML
