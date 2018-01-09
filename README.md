# Metrics Project
Metrics monitoring solution based on Prometheus

### Architecture

![Architecture](https://github.com/cx580/Metrics_Project/blob/master/pic/architecture.png)

### User Stories

- 最为运维人员，无需再给开发提供手段登录到对应的机器捞取日志来统计业务指标。
- 最为运维人员，期望所有的应用的业务指标都会自动收集和分类存储到中央的系统中，以便开发和运维使用
- 最为运维人员，能及时通知业务人员业务发生的异常情况
- 最为运维人员，可以方便的新建不同纬度的业务指标
- 最为运维人员，可以实时追踪指标的变化
- 最为运维人员，能够自动捕获新加入的系统和组件的指标（Optional）
- 作为开发人员，可以通过统一的入口获取不同纬度(域／服务／实例（ip）)的业务指标
- 作为开发人员，可以及时获得业务指标异常的告警


### Domain Model

![Domain Model](https://github.com/cx580/Metrics_Project/blob/master/pic/domainmodel.png)

### Metrics and label naming spec

Refer to [Metric naming](https://prometheus.io/docs/practices/naming/)

### Common labels in each metrics

- Namespace / Domain name
- Service name
- Interface name
- Method name
- Channel name

![Common Labe](https://github.com/cx580/Metrics_Project/blob/master/pic/label.png)



