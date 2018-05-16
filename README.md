Smarter layer
===============

## 上阶段调整：
* 资金添加账户总额统计。

## 直做户下单（pc+app）
流程与超市经理要一样。购买商品（单一商品雏鸡，饲料除外），进行分单，业务归属是否存在购买权限，根据当前商品，下单人员获取业务归属信息，区域会计，区域经理，余额账户，根据业务归属信息获取计划量，购买数量，生成订单，余额支付调取相应的账户信息。雏鸡和饲料流程区别，支付方式，增值服务不同。

## 超市经理管理中心（pc+app）

购买商品（单一商品雏鸡，饲料除外），进行分单，强制检测是否存在账户，业务归属是否存在购买权限，根据当前商品，下单人员获取业务归属信息，区域会计，区域经理，余额账户，根据业务归属信息获取计划量，购买数量，生成订单，业务归属（区域经理，区域会计），余额支付调取相应的账户信息。雏鸡和饲料流程区别，支付方式，增值服务不同

## 区域经理管理中心（pc+app）
超市管理：
* 我的管理超市；
* 我的业务超市
大客户管理：
* 我的大客户，新增订单，取消该按钮
* 我的业务大客户，新增订单，订单流程超市经理代下单流程，业务大客户个人中心，通过前台查看区域经理代下的订单。
## 订单管理：
* 管理订单维持原流程，去除操作按钮
* 业务订单，根据新字段查询关系调取订单，管理

## 区域会计管理中心（pc）

* 余额管理：按照不同的业务管理管理不同的用户余额；
* 余额管理：调单发货产生退款按照业务归属关系逆向增加账户余额；
* 提现管理：按照用户的不同的业务管理，进行提现管理；
* 汇款单管理：按照用户的不同业务管理，进行汇款单确认；
* 订单管理：发货，鸡的发货和饲料的发货不同；
* 调整发货：饲料不允许减少数量，雏鸡执行多不收钱，少了退款的流程；

更多细节参阅 [LICENSE.txt](LICENSE.txt)
