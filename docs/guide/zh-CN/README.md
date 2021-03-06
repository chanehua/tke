# TKEStack 产品手册

* [产品部署指南](installation)
  * [部署架构](installation/installation-architecture.md)
  * [部署环境要求](installation/installation-requirement.md)
  * [安装步骤](installation/installation-procedures.md)
  
* [产品快速入门](QuickStart)
  * [快速入门](QuickStart/快速入门.md)
  * [入门示例](QuickStart/examples)
    * [创建简单的 Nginx 服务](QuickStart/examples/创建简单nginx服务.md)
    * [编写 Hello World 程序](QuickStart/examples/编写Hello-World程序.md)
    * [如何构建 Docker 镜像](QuickStart/examples/如何构建Docker镜像.md)
  
* [产品使用指南](products)

  [切换控制台](products/controlpannel.md)

  * [平台侧](products/platform)
    * [概览](products/platform/overview.md)
    * [集群管理](products/platform/cluster.md)
    * [业务管理](products/platform/business.md)
    * [扩展组件](products/platform/extender.md)
    * [组织资源](products/platform/resource.md)
    * [访问管理](products/platform/access.md)
    * [监控&告警](products/platform/monitor&alert.md)
    * [运维中心](products/platform/operation.md)
  * [业务侧](products/business-control-pannel)
    * [应用管理](products/business-control-pannel/application)
      * [命名空间](products/business-control-pannel/application/namespace.md)
      * [工作负载](products/business-control-pannel/application/workload)
        * [Deployment ](products/business-control-pannel/application/workload/deployment.md)
        * [StatefulSet ](products/business-control-pannel/application/workload/stateful-set.md)
        * [DaemonSet ](products/business-control-pannel/application/workload/daemon-set.md)
        * [Job ](products/business-control-pannel/application/workload/job.md)
        * [CronJob ](products/business-control-pannel/application/workload/cron-job.md)
        * [TApp ](products/business-control-pannel/application/workload/tapp.md)
        * [设置工作负载的资源限制](products/business-control-pannel/application/workload/resource-limit.md)
      * [服务](products/business-control-pannel/application/services)
        * [Service ](products/business-control-pannel/application/services/service.md)
        * [Ingress ](products/business-control-pannel/application/services/ingress.md)
      * [配置管理](products/business-control-pannel/application/configurations)
        * [ConfigMap](products/business-control-pannel/application/configurations/ConfigMap.md)
        * [Secret](products/business-control-pannel/application/configurations/secret.md)
      * [存储](products/business-control-pannel/application/storage)
        * [PV 和 PVC ](products/business-control-pannel/application/storage/persistent-volume-claim.md)
        * [StorageClass](products/business-control-pannel/application/storage/storave-class.md)
      * [日志](products/business-control-pannel/application/log.md)
      * [事件](products/business-control-pannel/application/events.md)
    * [Helm 应用](products/business-control-pannel/helm/helm.md)
    * [业务管理](products/business-control-pannel/business-manage.md)
    * [组织资源](products/business-control-pannel/resource)
      * [仓库管理](products/business-control-pannel/resource/registry.md)
      * [访问凭证](products/business-control-pannel/resource/credentials.md)
    * [监控与告警](products/business-control-pannel/monitor-alert)
      * [设置告警](products/business-control-pannel/monitor-alert/alert.md)
      * [通知管理](products/business-control-pannel/monitor-alert/notifition.md)
    * [运维中心](products/business-control-pannel/operation)
      * [日志采集](products/business-control-pannel/operation/logcollect.md)

* [产品特色功能](features)
  * [Galaxy](features/galaxy.md)
  * [TAPP](features/tapp.md)
  * [GPUManager](features/gpumanager.md)
  * [CronHPA](features/cron-hpa.md)
  * [LBCF](features/lbcf.md)
  
* [FAQ](FAQ)
  
  * [部署类](FAQ/Installation)
    * [如何规划部署资源](FAQ/Installation/规划部署资源.md)
    * [如何使用存储](FAQ/Installation/如何使用存储.md)
    * [如何重新部署](FAQ/Installation/如何重新部署.md)
  * [功能类](FAQ/Feature)
    * [如何接入LDAP&OIDC](FAQ/Feature/如何接入LDAP&OIDC.md)
    * [如何实现自定义监控](FAQ/Feature/如何实现自定义监控.md)
    * [如何做日志分析](FAQ/Feature/如何做日志分析.md)
  * [授权类](FAQ/Authority)
    * [业务管理与平台管理的区别](FAQ/Authority/业务管理与平台管理的区别.md)
    * [如何设置自定义策略](FAQ/Authority/如何设置自定义策略.md)
    * [Docker-login权限错误](FAQ/Authority/Docker-login权限错误.md)
  * [事件类](FAQ/Events)
    * [常见错误事件](FAQ/Events/常见错误事件.md)
  * [平台类](FAQ/品台类)
    * [平台使用常见问题](FAQ/Platform/平台使用常见问题.md)