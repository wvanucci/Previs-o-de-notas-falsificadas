# Previsão-de-notas-falsificadas
Queremos prever qual nota é falsificada ou genuína usando os bancos de recursos Wavelete. Para fazer isso, vou usar o algoritmo k-means para agrupar as notas em grupos que compartilham características semelhantes. Então, de antemão, tenho dois objetivos durante a tarefa: 

* Como não sabemos como os dados são melhor agrupados, devemos realizar o processo de identificação do melhor número de cluster sem alguma natureza do problema. As métricas do elbow, Silhoutte e Davies Bouldin Index serão apresentadas.

* Estime um número de agrupamentos de grupos de dados de acordo com a natureza do problema. Como temos classes verdadeiras de genuíno e falso (verdade fundamental), seremos apresentados a uma métrica de precisão
