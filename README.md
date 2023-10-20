# webquick

快速生成web,依赖字节跳动的 hz.  支持redis,mysql,pulsar,naocs,elastic 等常用中间件

案例地址 [案例 洁骏汽车服务有限公司](http://www.ch123.com.cn/ "洁骏汽车服务有限公司")

go install github.com/cloudwego/hertz/cmd/hz@latest

hz new --mod=github.com/hertz/hello --proto_path=idl --idl=idl/hello.proto --customize_layout=layout/default.yaml --customize_package=layout/package.yaml

hz update --mod=github.com/hertz/hello --proto_path=idl --idl=idl/system/module.proto  --customize_package=layout/package.yaml

github.com/jhump/protoreflect v1.14.1 需要这个版本

github.com/apache/thrift v0.13.0 需要这个版本

github.com/cloudwego/netpoll v0.4.1 需要这个版本


设置proto默认路径的方法
![2RTTA3XF@STW6GVJJMQ) 3V](https://github.com/flyerxp/hertz_web/assets/52146821/d60a167a-6530-444c-af64-7ea36f742d94)
