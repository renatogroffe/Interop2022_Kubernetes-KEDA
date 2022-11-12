# Interop2022_Kubernetes-KEDA
Objetos para Deployment de um Worker Service (apuração de votos de tecnologias + Feature Flags) no Kubernetes utilizando KEDA, Helm, Apache Kafka (a partir de uma instância do Azure Event Hubs) e .NET 7.

Worker para consumo dos eventos:
**https://github.com/renatogroffe/DotNet7-WorkerService-Kafka-FeatureFlags-AppInsights-SqlServer_VotacaoTecnologias**

Aplicação para geração dos eventos:
**https://github.com/renatogroffe/ASPNETCore7-MVC-AzureEventHubs-Kafka-AppInsightsConnString_SiteQuestao**