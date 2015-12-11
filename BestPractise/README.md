#Azure云应用设计与实现指南
===

###该指南的文章翻译自[Azure官方文档][AzureOriginDoc]
---

##本文档涉及云服务设计、开发、部署、运维的最佳实践，主要包含以下一些内容：
---
* **[API设计指南][APIDesignGuidance]**描述设计一个Web API时应该考虑的一些事情。

* **[API实现指南][APIImplementationGuidance]**主要关注实现与发布Web API为可用服务的最佳实践。

* **[自动伸缩指南][AutoscalingGuidance]**总结了利用云服务器弹性伸缩特性简化性能监控与资源动态伸缩的实践方法。

* **[后台作业指南][BackgroundJobsGuidance]**详述了实现与前台操作完全独立的后台任务实现的最佳实现。

* **[内容分发网络指南][CDNGuidance]**是一个综述性指南，告诉你如何使用[内容分发网络（CDN）][CDNWiki]最小化应用服务器负载，同时最大化应用可用性及性能。

* **[缓存指南][CacheGuidance]**总结了如何使用Azure的缓存来提高系统的可用性与扩展能力。

* **[数据分片指南][DataPartitionGuidance]**描述如何使用数据分片策略提升系统扩展能力、减少竞态以及优化系统性能。
  
* **[监控与诊断指南][MoniteringAndDiagnosticsGuidance]**提供了如何监控用户使用情况、资源使用情况、系统健康与性能监控的指南。
  
* **[重试简略指南][RetryGeneralGuidance]**提供了Azure应用中如何处理瞬时故障的简单指南。
  
* **[重试服务详细指南][RetryServiceSpecificGuidance]**总结了Azure服务中的重试机制的特性，以及用户如何为自己的服务使用、适配和扩展这些重试机制。

* **[扩展性清单][ScalabilityChecklist]**总结了设计与实现可扩展性服务与数据管理的最佳实践。

* **[可用性清单][AvailabilityChecklist]**列出了保证服务可用性的最佳实践。


[AzureOriginDoc]: https://github.com/dragon119/azure-guidance
[AvailabilityChecklist]: AvailabilityChecklist.md
