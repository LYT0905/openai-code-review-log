这段代码是一个名为`SkuRechargeEntity`的Java实体类，用于表示活动商品充值的信息。它包含了以下属性：

1. `userId`：用户ID，用于标识充值的用户。
2. `sku`：商品SKU，由活动编号和活动计数组成。
3. `outBusinessNo`：业务防重ID，用于确保幂等性，防止多次充值。

这个实体类使用了Lombok库来简化代码，包括自动生成getter、setter、构造函数、`toString`方法等。同时，它还使用了`@Builder`注解来支持构建器模式，使得创建实例更加方便。