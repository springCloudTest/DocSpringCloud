# DocSpringCloud


* v1.02-服务注册+服务发现[角色：注册中心Eureka + 服务提供者Providers + 服务消费者Ribbon(http/tcp)/Feign(ws)]
EurekaService+ServiceProviders+EurekaRibbon+EurekaFeign(all v1.02)


* v1.03-服务注册+服务发现+断路器[服务降级-异常处理，后续可拓展服务路由能力支持灰度发布]
EurekaService+ServiceProviders+EurekaRibbon(Netflix Hystrix)


* v1.04-服务注册+服务发现+断路器+配置中心[拆分服务端-客户端，后续客户端集成进服务消费者]+服务网关zuul[支持token验证]
EurekaService+ServiceProviders+EurekaRibbon(Netflix Hystrix)+ConfigService+ZuulGateway


* v1.05-服务注册[euraka多实例实现高可用]+服务发现+断路器+配置中心[高可用，集成到euraka]+服务网关zuul
EurekaService+ServiceProviders+EurekaRibbon(Netflix Hystrix)+ConfigService+ZuulGateway



