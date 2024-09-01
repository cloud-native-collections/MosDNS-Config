# comment
自用MosDNS配置

- 支持ECS
- 支持GEOIP
- 支持GEOSITE
- 支持自定义灰名单及白名单
- 支持广告过滤
- 支持数据导入Grafana
- 本层级DNS处理无泄漏

根据 [Jasper-1024/mosdns_docker](https://github.com/Jasper-1024/mosdns_docker/tree/master/mosdns_v5)  进行二次修改，在此基础上增加GFW域名远程解析规则，修改并发请求DNS连接数
