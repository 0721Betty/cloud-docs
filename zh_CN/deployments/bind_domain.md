# 绑定域名

在 EMQ X Cloud 建立部署后，您会获得一个 MQTT 连接地址，该地址在专业版部署里以 IP 显示，在基础版中以 emqx.cloud 结尾的二级域名显示。

您或许已经拥有自己的域名，希望可以将部署地址绑定到自己拥有的域名，通过您的域名使用 MQTT 服务。

> 注意：在绑定域名后，基础版将无法使用 mqtts 和 wss 端口


## 操作步骤

这里假设您有顶级域名 www.abc.com，希望以 mqtt.abc.com 访问 mqtt 服务，您在 EMQ X Cloud 上的部署的连接地址为 123.123.123.123

那么只需要在您的域名提供商的操作面板上，将 mqtt.abc.com 的 A 记录指向 123.123.123.123 即可

> 注意：如果您使用的是基础版或者亚马逊中国，则需要将 mqtt.abc.com 的 CNAME 记录指向 123.123.123.123

等待 DNS 解析生效后，您便可通过 mqtt.abc.com 连接 mqtt 服务。
