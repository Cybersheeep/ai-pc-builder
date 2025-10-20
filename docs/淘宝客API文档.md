#淘宝客API文档

##API接口总览

-`taobao.tbk.item.convert` (24516) - 淘宝客-推广者-商品链接转换
-`taobao.tbk.item.share.convert` (24519) - 淘宝客-推广者-商品三方分成链接转换
-`taobao.tbk.shop.get` (24521) - 淘宝客-推广者-店铺搜索
-`taobao.tbk.shop.share.convert` (24524) - 淘宝客-推广者-店铺三方分成链接转换
-`taobao.tbk.itemid.coupon.get` (28111) - 淘宝客-推广者-根据宝贝id批量查询优惠券
-`taobao.tbk.coupon.convert` (29289) - 淘宝客-推广者-单品券高效转链
-`taobao.tbk.adzone.create` (31372) - 淘宝客-推广者-创建推广位
-`taobao.tbk.tpwd.share.convert` (32931) - 淘宝客-推广者-淘口令解析&三方分成转链
-`taobao.tbk.tpwd.convert` (32932) - 淘宝客-推广者-淘口令解析&转链
-`taobao.tbk.dg.newuser.order.get` (33892) - 淘宝客-推广者-新用户订单明细查询
-`taobao.tbk.dg.optimus.material` (33947) - 淘宝客-推广者-物料精选
-`taobao.tbk.dg.newuser.order.sum` (36836) - 淘宝客-推广者-拉新活动对应数据查询
-`taobao.tbk.relation.refund` (40121) - 淘宝客-推广者-售后退款订单查询
-`taobao.tbk.dg.vegas.tlj.create` (40173) - 淘宝客-推广者-淘礼金创建
-`taobao.tbk.dg.punish.order.get` (42050) - 淘宝客-推广者-处罚订单查询
-`taobao.tbk.content.recommend.material.get` (42937) - 淘宝客-推广者-图文智能识别消费者端推荐物料查询
-`taobao.tbk.content.daren.material.upload` (42939) - 淘宝客-推广者-图文智能识别达人端物料上传
-`taobao.tbk.order.details.get` (43328) - 淘宝客-推广者-所有订单查询
-`taobao.tbk.dg.reports.newquery` (43906) - 淘宝客-推广者-媒体数据报表交换
-`taobao.tbk.jzf.convert` (43914) - 淘宝客-推广者-官办找福利页
-`taobao.tbk.dg.reports.query.stat` (45095) - 淘宝客-推广者-媒体数据报表交换-汇总数据
-`taobao.tbk.dg.reports.query.click` (45096) - 淘宝客-推广者-媒体数据交换报表点击维度
-`taobao.tbk.dg.vegas.send.report` (47593) - 淘宝客-推广者-查询红包发放个数
-`taobao.tbk.activity.info.get` (48340) - 淘宝客-推广者-官方活动转链
-`taobao.tbk.dg.optimus.promotion` (52700) - 淘宝客-推广者-权益物料精选
-`taobao.tbk.dg.vegas.send.status` (52958) - 淘宝客-推广者-红包领取状态查询
-`taobao.tbk.dg.pailitao.widget.convert` (53760) - 淘宝客-推广者-拍立淘插件转链
-`taobao.tbk.thor.task.select` (55385) - 淘宝客-推广者-互动任务投放
-`taobao.tbk.rta.consumer.match` (55891) - 淘宝客-推广者-定向活动目标发布
-`taobao.tbk.dg.cpa.activity.detail` (56312) - 淘宝客-推广者-CPA活动执行明细
-`taobao.tbk.dg.tpwd.report.get` (56693) - 淘宝客-推广者-淘口令回流数据查询
-`taobao.tbk.private.tpwd.create` (57813) - 淘宝客-推广者-加密淘口令生成
-`taobao.tbk.dg.cpa.activity.report` (58111) - 淘宝客-推广者-任务奖励效果报表
-`taobao.tbk.dg.vegas.tlj.stop` (58713) - 淘宝客-推广者-淘礼金暂停发放
-`taobao.tbk.dg.vegas.tlj.report` (58736) - 淘宝客-推广者-淘礼金效果数据
-`taobao.tbk.dg.tpwd.risk.report` (59692) - 淘宝客-推广者-淘口令预警及拦截查询
-`taobao.tbk.dg.vegas.tlj.share.convert` (60552) - 淘宝客-推广者-淘礼金三方链接转换
-`taobao.tbk.seed.report.get` (61677) - 淘宝客-推广者-种草指标报表
-`taobao.tbk.dg.material.recommend` (62201) - 淘宝客-推广者-物料精选升级版
-`taobao.tbk.seed.wb.crowd.get` (62423) - 淘宝客-推广者-内容种草人群包数据查询
-`taobao.tbk.content.order.get` (62658) - 淘宝客-推广者-内容ID订单汇总
-`taobao.tbk.dg.material.optional.upgrade` (64759) - 淘宝客-推广者-物料搜索升级版
-`taobao.tbk.order.refund.get` (65180) - 淘宝客-推广者-全量售后退款订单查询
-`taobao.tbk.dg.general.link.convert` (65409) - 淘宝客-推广者-万能转链
-`taobao.tbk.feed.opt.upload` (66773) - 淘宝客-推广者-内容种草投流明细数据上传
-`taobao.tbk.dg.item.group.merge` (66793) - 淘宝客-推广者-多品凑单上传
-`taobao.tbk.feed.relation.upload` (66796) - 淘宝客-推广者-内容投流关系写入
-`taobao.tbk.feed.indicator.upload` (66816) - 淘宝客-推广者-内容种草投流前链路数据上传
-`taobao.tbk.feed.indicator.exchange` (66818) - 淘宝客-推广者-内容种草投流数据交换
-`taobao.tbk.feed.event.get` (67866) - 淘宝客-推广者-投流任务信息下行
-`taobao.tbk.uvid.encrypt` (68029) - 淘宝客-推广者-加密用户标识生成
-`taobao.tbk.seed.event.fee.update` (68039) - 淘宝客-推广者-种草商单子任务改价申请
-`taobao.tbk.seed.event.fee.update.result.get` (68040) - 淘宝客-推广者-种草商单子任务改价结果查询
-`taobao.tbk.rta.uvid.get` (68848) - 淘宝客-推广者-厂商版加密用户标识获取
-`taobao.tbk.feed.order.check` (69046) - 淘宝客-推广者-内容种草投流对账单
-`taobao.tbk.interest.items.get` (69446) - 淘宝客-推广者-厂商版-个性化推荐商品获取
-`taobao.tbk.content.general.link.convert` (69454) - 淘宝客-推广者-内容三方万能转链
-`taobao.tbk.dg.interest.items.get` (70231) - 淘宝客_推广者_个性化商品获取
-`taobao.tbk.dg.uvid.behavior.report` (70485) - 淘宝客-推广者-商品行为上报
-`taobao.tbk.dg.general.link.parse` (70532) - 淘宝客-推广者-万能解析
-`taobao.tbk.dg.uvid.bind.status.get` (70587) - 淘宝-淘宝客-推广者-用户绑定状态查询
-`taobao.tbk.dg.rta.uvid.match` (71718) - 淘宝客-推广者-UVID人群挑量
-`taobao.tbk.dsp.rta.consumer.match` (72399) - 淘宝客-推广者-目标用户批量匹配
-`taobao.tbk.dg.vc.landing.link.convert` (72751) - 淘宝客-推广者-拉新承接页转链
-`taobao.tbk.sc.vc.landing.link.convert` (72752) - 淘宝客-推广者-拉新承接页转链
-`taobao.tbk.dg.eshare.link.convert` (72949) - 淘宝客-推广者-KA私域专享转链
-`taobao.tbk.dg.image.ecognition.list.query` (73442) - 淘宝客【推广者】识图找优惠商品List
-`taobao.tbk.dg.image.ecognition.page.query` (73468) - 淘宝客【推广者】识图找优惠h5
-`taobao.tbk.shop.recommend.get` (24522) - 淘宝客-公用-店铺关联推荐
-`taobao.tbk.spread.get` (27832) - 淘宝客-公用-长链转短链
-`taobao.tbk.item.click.extract` (28156) - 淘宝客-公用-链接解析出商品id
-`taobao.tbk.coupon.get` (31106) - 淘宝客-公用-阿里妈妈推广券详情查询
-`taobao.tbk.tpwd.create` (31127) - 淘宝客-公用-淘口令生成
-`taobao.tbk.tpwd.mix.create` (31728) - 淘宝客-公用-文本淘口令
-`taobao.tbk.sc.publisher.info.save` (37988) - 淘宝客-公用-私域用户备案
-`taobao.tbk.sc.publisher.info.get` (37989) - 淘宝客-公用-私域用户备案信息查询
-`taobao.tbk.sc.invitecode.get` (38046) - 淘宝客-公用-私域用户邀请码生成
-`taobao.tbk.tbkinfo.get` (39869) - 淘宝客-公用-pid校验
-`taobao.tbk.tpwd.parse` (42646) - 淘宝客-公用-淘口令解析出原链接
-`taobao.tbk.item.details.upgrade.get` (64757) - 淘宝客-公用-淘宝客商品详情查询升级版（详细版）
-`taobao.tbk.item.info.upgrade.get` (64763) - 淘宝客-公用-淘宝客商品详情查询升级版（简易版）
-`taobao.tbk.itemid.ineffective.transform` (65372) - 淘宝客-公用-失效商品id转化


##公共参数
所有淘宝客API都需要包含以下公共参数：

| 参数名称 | 类型 | 是否必须 | 描述 |
|---------|------|---------|------|
| method | String | 必须 | API接口名称 |
| app_key | String | 必须 | TOP分配给应用的AppKey |
| session | String | 可选 | 用户授权令牌 |
| timestamp | String | 必须 | 时间戳，格式为yyyy-mm-dd hh:mm:ss |
| format | String | 可选 | 响应格式，默认为xml |
| v | String | 必须 | API协议版本号，可选值：2.0 |
| sign_method | String | 必须 | 签名的加密算法，可选值：md5，hmac |
| sign | String | 必须 | API输入参数签名结果 |


---
##taobao.tbk.item.convert（淘宝客-推广者-商品链接转换）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| adzone_id | Number | 必须 | 123 |  | 广告位ID，区分效果位置 |
| fields | String | 必须 | num_iid,click_url |  | 需返回的字段列表 |
| num_iids | String | 必须 | 123,456 |  | 商品ID串，用','分割，从taobao.tbk.item.get接口获取num_iid字段，最大40个 |
| platform | Number | 可选 | 123 | 默认值：1 | 链接形式：1：PC，2：无线，默认：１ |
| unid | String | 可选 | demo |  | 自定义输入串，英文和数字组成，长度不能大于12个字符，区分不同的推广渠道 |
| dx | String | 可选 | 1 |  | 1表示商品转通用计划链接，其他值或不传表示转营销计划链接 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| results | NTbkItem [] |  | 淘宝客商品 |
| └ click_url | String | http://s.click.taobao.com/e=xxx | 淘客地址 |
| └ num_iid | String | 123 | 商品ID |
| └ input_num_iid | String | 1 | 原始输入的商品ID |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.item.convert', {
	'adzone_id':'123',
	'fields':'num_iid,click_url',
	'num_iids':'123,456',
	'platform':'123',
	'unid':'demo',
	'dx':'1'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_item_convert_response":{
        "results":{
            "n_tbk_item":[
                {
                    "click_url":"http:\/\/s.click.taobao.com\/e=xxx",
                    "num_iid":"123",
                    "input_num_iid":"1"
                }
            ]
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isv.invalid-parameter:adzone_id | adzone_id不正确 | 请填写与member_id和site_id匹配的adzone_id |
| isv.invalid-parameter:platform | platform不正确 | 请填写正确的platform |
| isv.invalid-parameter:unid | unid不正确 | 请填写正确的union id |
| isp.tbkapi-service-unavailable | 内部服务不可用 | 稍后重试 |

---
##taobao.tbk.item.share.convert（淘宝客-推广者-商品三方分成链接转换）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| adzone_id | Number | 必须 | 123 |  | 广告位ID，区分效果位置 |
| fields | String | 必须 | num_iid,click_url |  | 需返回的字段列表 |
| num_iids | String | 必须 | 123,456 |  | 商品ID串，用','分割，从taobao.tbk.item.get接口获取num_iid字段 |
| platform | Number | 可选 | 1 | 默认值：1 | 链接形式：1：PC，2：无线，默认：１ |
| sub_pid | String | 必须 | mm_123_123_123 |  | 三方pid，满足mm_xxx_xxx_xxx格式 |
| unid | String | 可选 | demo |  | 该字段不使用。 |
| dx | String | 可选 | 1 |  | 1表示商品转通用计划链接，其他值或不传表示优先转营销计划链接 |
| coupon_id | String | 可选 | 1 |  | 券id，券仅支持关联唯一一个商品，输入券id，请确保商品id也是唯一的 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| results | NTbkItem [] |  | 淘宝客商品 |
| └ click_url | String | http://s.click.taobao.com/e=xxx | 单品的淘客地址或有优惠券商品的淘客地址 |
| └ num_iid | String | 123 | 商品ID |
| └ commission_rate | String | 3.60 | 当前转链计划的商品佣金率（%） |
| └ coupon_amount | String | 10.00 | 优惠券面额，宝贝没有优惠券时，为空 |
| └ coupon_click_url | String | https://uland.taobao.com/coupon/edetail?e=xxx | 优惠券地址，不论宝贝是否有优惠券，本地址均非空。调用者可参考coupon_amount的值以判断使用coupon_click_url或click_url。 |
| └ added_time | Number | 1585929600000 | 定时上架商品的上架时间。格式为时间戳，单位为毫秒。对于已上架商品，该字段为空，无意义。 |
| └ item_status | Number | 1 | 商品的商家状态。0表示已上架；1表示定时上架商品。 |
| └ input_num_iid | String | 1 | 原始输入的商品id |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.item.share.convert', {
	'adzone_id':'123',
	'fields':'num_iid,click_url',
	'num_iids':'123,456',
	'platform':'1',
	'sub_pid':'mm_123_123_123',
	'unid':'demo',
	'dx':'1',
	'coupon_id':'1'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_item_share_convert_response":{
        "results":{
            "n_tbk_item":[
                {
                    "click_url":"http:\/\/s.click.taobao.com\/e=xxx",
                    "num_iid":"123",
                    "commission_rate":"3.60",
                    "coupon_amount":"10.00",
                    "coupon_click_url":"https:\/\/uland.taobao.com\/coupon\/edetail?e=xxx",
                    "added_time":1585929600000,
                    "item_status":1,
                    "input_num_iid":"1"
                }
            ]
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isv.invalid-parameter:adzone_id | adzone_id不正确 | 请填写与member_id和site_id匹配的adzone_id |
| isv.invalid-parameter:sub_pid | sub_pid不正确 | 请填写正确的三方pid，满足mm_xxx_xxx_xxx格式 |
| isp.tbkapi-service-unavailable | 内部服务不可用 | 稍后重试 |

---
##taobao.tbk.shop.get（淘宝客-推广者-店铺搜索）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| end_auction_count | Number | 可选 | 200 |  | 累计推广商品上限 |
| end_commission_rate | Number | 可选 | 123 |  | 淘客佣金比率上限，1~10000 |
| end_credit | Number | 可选 | 20 |  | 信用等级上限，1~20 |
| end_total_action | Number | 可选 | 100 |  | 店铺商品总数上限 |
| fields | String | 必须 | user_id,shop_title,shop_type,seller_nick,pict_url,shop_url |  | 需返回的字段列表 |
| is_tmall | Boolean | 可选 | false |  | 是否商城的店铺，设置为true表示该是属于淘宝商城的店铺，设置为false或不设置表示不判断这个属性 |
| page_no | Number | 可选 | 1 | 默认值：1 | 第几页，默认1，1~100 |
| page_size | Number | 可选 | 20 | 默认值：20 | 页大小，默认20，1~100 |
| platform | Number | 可选 | 1 | 默认值：1 | 链接形式：1：PC，2：无线，默认：１ |
| q | String | 必须 | 女装 |  | 查询词 |
| sort | String | 可选 | commission_rate_des |  | 排序_des（降序），排序_asc（升序），佣金比率（commission_rate）， 商品数量（auction_count），销售总数量（total_auction） |
| start_auction_count | Number | 可选 | 123 |  | 累计推广商品下限 |
| start_commission_rate | Number | 可选 | 2000 |  | 淘客佣金比率下限，1~10000 |
| start_credit | Number | 可选 | 1 |  | 信用等级下限，1~20 |
| start_total_action | Number | 可选 | 1 |  | 店铺商品总数下限 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| results | NTbkShop [] |  | 淘宝客店铺 |
| └ shop_url | String | http://store.taobao.com/shop/xxx | 店铺地址 |
| └ seller_nick | String | demo | 卖家昵称 |
| └ shop_type | String | B | 店铺类型，B：天猫，C：淘宝 |
| └ shop_title | String | 女装店铺 | 店铺名称 |
| └ user_id | Number | 123 | 卖家ID |
| └ pict_url | String | http://img01.taobaocdn.com/bao/uploaded/i1/xxx.jpg | 店标图片 |
| total_results | Number | 100 | 搜索到符合条件的结果总数 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.shop.get', {
	'end_auction_count':'200',
	'end_commission_rate':'123',
	'end_credit':'20',
	'end_total_action':'100',
	'fields':'user_id,shop_title,shop_type,seller_nick,pict_url,shop_url',
	'is_tmall':'false',
	'page_no':'1',
	'page_size':'20',
	'platform':'1',
	'q':'女装',
	'sort':'commission_rate_des',
	'start_auction_count':'123',
	'start_commission_rate':'2000',
	'start_credit':'1',
	'start_total_action':'1'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_shop_get_response":{
        "results":{
            "n_tbk_shop":[
                {
                    "shop_url":"http:\/\/store.taobao.com\/shop\/xxx",
                    "seller_nick":"demo",
                    "shop_type":"B",
                    "shop_title":"女装店铺",
                    "user_id":123,
                    "pict_url":"http:\/\/img01.taobaocdn.com\/bao\/uploaded\/i1\/xxx.jpg"
                }
            ]
        },
        "total_results":100
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isp.tbkapi-service-unavailable | 内部服务不可用 | 稍后重试 |

---
##taobao.tbk.shop.share.convert（淘宝客-推广者-店铺三方分成链接转换）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| fields | String | 必须 | user_id,click_url |  | 需返回的字段列表 |
| user_ids | String | 必须 | 123,456 |  | 卖家ID串，用','分割，从taobao.tbk.shop.get接口获取user_id字段 |
| platform | Number | 可选 | 1 |  | 链接形式：1：PC，2：无线，默认：１ |
| adzone_id | Number | 必须 | 123 |  | 广告位ID，区分效果位置 |
| sub_pid | String | 必须 | demo |  | 三方pid，满足mm_xxx_xxx_xxx格式 |
| unid | String | 可选 | demo |  | 自定义输入串，英文和数字组成，长度不能大于12个字符，区分不同的推广渠道 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| results | NTbkShop [] |  | 淘宝客店铺 |
| └ user_id | Number | 123 | 卖家ID |
| └ click_url | String | http://s.click.taobao.com/e=xxx | 淘客地址 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.shop.share.convert', {
	'fields':'user_id,click_url',
	'user_ids':'123,456',
	'platform':'1',
	'adzone_id':'123',
	'sub_pid':'demo',
	'unid':'demo'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_shop_share_convert_response":{
        "results":{
            "n_tbk_shop":[
                {
                    "user_id":123,
                    "click_url":"http:\/\/s.click.taobao.com\/e=xxx"
                }
            ]
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isv.invalid-parameter:adzone_id | adzone_id不正确 | 请填写与member_id和site_id匹配的adzone_id |

---
##taobao.tbk.itemid.coupon.get（淘宝客-推广者-根据宝贝id批量查询优惠券）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| platform | Number | 可选 | 1 | 默认值：1 | 1：PC，2：无线，默认：1 |
| pid | String | 必须 | mm_123_123_123 |  | 三方pid，满足mm_xxx_xxx_xxx格式 |
| num_iids | String | 可选 | 123,456 |  | 商品ID串，用逗号分割，从taobao.tbk.item.coupon.get接口获取num_iid字段，最大40个。（如果传入了没有优惠券的宝贝num_iid，则优惠券相关的字段返回为空，请做好容错） |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| results | TbkCoupon [] |  | data |
| └ small_images | String

                                 [] | http://img4.tbcdn.cn/tfscom/i3/TB1vPdxHXXXXXbtXpXXXXXXXXXX_!!2-item_pic.png | 商品小图列表 |
| └ coupon_total_count | Number | 5000 | 优惠券总量 |
| └ commission_rate | String | 1.80 | 佣金比率(%) |
| └ user_type | Number | 1 | 卖家类型，0表示集市，1表示商城 |
| └ title | String | 奥克斯理发器电推剪电推子充电式成人儿童剪发器电动剃头刀家用 | 商品标题 |
| └ coupon_info | String | 满188元减5元 | 优惠券面额 |
| └ shop_title | String | 奥克斯品胜专卖店 | 店铺名称 |
| └ category | Number | 1 | 后台一级类目 |
| └ num_iid | String | 1 | itemId |
| └ coupon_remain_count | Number | 3395 | 优惠券剩余量 |
| └ zk_final_price | String | 269.00 | 折扣价 |
| └ coupon_start_time | String | 2016-09-05 | 优惠券开始时间 |
| └ nick | String | 奥克斯品胜专卖店 | 卖家昵称 |
| └ seller_id | Number | 2884767143 | 卖家id |
| └ volume | Number | 76927 | 30天销量 |
| └ coupon_end_time | String | 2016-10-01 | 优惠券结束时间 |
| └ coupon_click_url | String | https://uland.taobao.com/coupon/edetail?e=8Iirp0qvW4t9%2BIHBh%2BrOiioPr%2BRaKTNCdUZfqAaohJnOVyPi0MUz8w13gui0W49o5PdvjO4eOnOie%2FpBy9wBFg%3D%3D&pid=mm_0_0_0&af=1&itemId=531940770655 | 商品优惠券推广链接 |
| └ pict_url | String | http://img03.daily.taobao.net/tfscom/i1/TB1XTOqKXXXXXaSXVXXXXXXXXXX_!!0-item_pic.jpg | 商品主图 |
| └ item_url | String | http://h5.m.taobao.com/awp/core/detail.htm?id=531940770655 | 商品详情页链接地址 |
| └ input_num_iid | String | 1 | 原始入参商品id |
| └ annual_vol | String | 1万+ | 年销量 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.itemid.coupon.get', {
	'platform':'1',
	'pid':'mm_123_123_123',
	'num_iids':'123,456'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_itemid_coupon_get_response":{
        "results":{
            "tbk_coupon":[
                {
                    "small_images":{
                        "string":[
                            "http:\/\/img4.tbcdn.cn\/tfscom\/i3\/TB1vPdxHXXXXXbtXpXXXXXXXXXX_!!2-item_pic.png"
                        ]
                    },
                    "coupon_total_count":5000,
                    "commission_rate":"1.80",
                    "user_type":1,
                    "title":"奥克斯理发器电推剪电推子充电式成人儿童剪发器电动剃头刀家用",
                    "coupon_info":"满188元减5元",
                    "shop_title":"奥克斯品胜专卖店",
                    "category":1,
                    "num_iid":"1",
                    "coupon_remain_count":3395,
                    "zk_final_price":"269.00",
                    "coupon_start_time":"2016-09-05",
                    "nick":"奥克斯品胜专卖店",
                    "seller_id":2884767143,
                    "volume":76927,
                    "coupon_end_time":"2016-10-01",
                    "coupon_click_url":"https:\/\/uland.taobao.com\/coupon\/edetail?e=8Iirp0qvW4t9%2BIHBh%2BrOiioPr%2BRaKTNCdUZfqAaohJnOVyPi0MUz8w13gui0W49o5PdvjO4eOnOie%2FpBy9wBFg%3D%3D&pid=mm_0_0_0&af=1&itemId=531940770655",
                    "pict_url":"http:\/\/img03.daily.taobao.net\/tfscom\/i1\/TB1XTOqKXXXXXaSXVXXXXXXXXXX_!!0-item_pic.jpg",
                    "item_url":"http:\/\/h5.m.taobao.com\/awp\/core\/detail.htm?id=531940770655",
                    "input_num_iid":"1",
                    "annual_vol":"1万+"
                }
            ]
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isp.tbkapi-service-unavailable | 淘宝客API服务不可用 | 请稍后重试 |
| isv.invalid-parameter:start_price | 参数填写不正确 | 参数填写不正确 |
| isv.invalid-parameter:end_price | 参数填写不正确 | 参数填写不正确 |
| isv.invalid-parameter:end_tk_rate | 参数填写不正确 | 参数填写不正确 |
| 35 | 您输入的商品ID不合法，请使用升级后的新商品ID，如有疑问请加入【淘宝联盟】线上合规升级咨询群（钉钉群：44965410）进行咨询 | 您输入的商品ID不合法，请使用升级后的新商品ID，如有疑问请加入【淘宝联盟】线上合规升级咨询群（钉钉群：44965410）进行咨询 |
| 37 | ID处理异常 | ID处理异常 |
| 4 | 查询不到宝贝 | 查询不到宝贝 |

---
##taobao.tbk.coupon.convert（淘宝客-推广者-单品券高效转链）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| adzone_id | Number | 必须 | 123 |  | 推广位id，mm_xx_xx_xx pid三段式中的第三段 |
| item_id | String | 可选 | 123 |  | 淘客商品id |
| platform | Number | 可选 | 1 | 默认值：1 | 1：PC，2：无线，默认：１ |
| relation_id | String | 可选 | 12345 |  | 渠道管理ID（如是主站选品推广场景，必须入参该字段，且bizSceneId字段需入参2-消费者比价场景，否则二次转链失败） |
| special_id | String | 可选 | 12345 |  | 会员运营ID |
| external_id | String | 可选 | 12345 |  | 淘宝客外部用户标记，如自身系统账户ID；微信ID等 |
| xid | String | 可选 | abcdefg |  | 团长与下游渠道合作的特殊标识，用于统计渠道推广效果 |
| ucrowd_id | Number | 可选 | 1 |  | 会员人群ID，用于统计人群推广效果 |
| get_topn_rate | Number | 可选 | 0 | 默认值：0 | 是否获取前N件佣金	,0-否，1-是,其他值-否 |
| mini_program_link | Number | 可选 | 0 | 默认值：0 | 是否需要获取小程序链接，需要设置1。(暂未对外开放) |
| biz_scene_id | String | 可选 | 1 |  | 1-动态ID转链场景，2-消费者比价场景，3-商品库导购场景（不填默认为1） |
| promotion_type | String | 可选 | 2 |  | 1-自购省，2-推广赚（代理模式专属ID，代理模式必填，其它模式不用填写本字段） |
| manage_item_pub_id | Number | 可选 | 1 |  | 商品库服务账户(场景id3权限对应的memberid） |
| sku_id | Number | 可选 | 1234567 |  | 入参商品id下的skuid，传入时会透传至转链结果url中 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result | RpcResult | 1 | result |
| └ results | MaterialDto | 1 | data |
| └ coupon_remain_count | Number | 6859 | 优惠券剩余量 |
| └ coupon_total_count | Number | 8000 | 优惠券总量 |
| └ coupon_info | String | 满16元减10元 | 优惠券面额 |
| └ coupon_end_time | String | 2016-09-26 | 优惠券结束时间 |
| └ coupon_start_time | String | 2016-09-25 | 优惠券开始时间 |
| └ coupon_click_url | String | https://uland.taobao.com/coupon/edetail?e=nqUNB1NOF3Bt3vqbdXnGloankzPYmeEFkgNrw6YHQf9pZTj41Orn8MwBAs06HAOzqQomYNedOiHDYPmqkFXqLR0HgBdG%2FDDL%2F1M%2FBw7Sf%2FesGXLf%2BqX4cbeC%2F2cR0p0NlWH0%2BknxpnCJJP%2FQkZSsyo1HvKjXo4uz&pid=mm_26381042_12970066_52864659&af=1 | 商品优惠券推广链接 |
| └ category_id | Number | 1 | 后台一级类目 |
| └ max_commission_rate | String | 20.3 | 当不入参special_id、relation_id、external_id时，展示常规佣金率(%) |
| └ item_id | String | 524136796550 | 商品id |
| └ item_url | String | https://s.click.taobao.com/t?spm=a2e2e.10720394/c.90202110.1.4399704cUUhhH0&e=m%3D2%26s%3D0NJS731SUEdw4vFB6t2Z2ueEDrYVVa64LKpWJ%2Bin0XLjf2vlNIV67uIA4kDYDopEpOjgxi0uT208hw4H8GMUew7uoRPWrIBwR7CIpaNCoiKr9WTFywb%2BCtGNFs53xi4QGSKqJrqeJvt5ArodCWjzv9fsai3uVirbXH%2BQH9e66Y4%3D | 商品淘客链接 |
| └ ysyl_click_url | String | https://uland.taobao.com/coupon/edetail?e=nqUNB1NOF3Bt3vqbdXnGloankzPYmeEFkgNrw6YHQf9pZTj41Orn8MwBAs06HAOzqQomYNedOiHDYPmqkFXqLR0HgBdG%2FDDL%2F1M%2FBw7Sf%2FesGXLf%2BqX4cbeC%2F2cR0p0NlWH0%2BknxpnCJJP%2FQkZSsyo1HvKjXo4uz&pid=mm_26381042_12970066_52864659&af=1 | 预售有礼-推广链接 |
| └ ysyl_tlj_face | String | 0.6 | 预售有礼-预估淘礼金（元） |
| └ ysyl_tlj_send_time | String | 2019-11-10  21:59:59 | 预售有礼-淘礼金发放时间 |
| └ ysyl_tlj_use_start_time | String | 2019-11-10  21:59:59 | 预售有礼-淘礼金使用开始时间 |
| └ ysyl_commission_rate | String | 20.3 | 预售有礼-佣金比例（%）（ 预售有礼活动享受的推广佣金比例，注：推广该活动有特殊分成规则，请详见：https://tbk.bbs.taobao.com/detail.html?appId=45301&postId=9334376 ） |
| └ ysyl_tlj_use_end_time | String | 2019-11-10  21:59:59 | 预售有礼-淘礼金使用结束时间 |
| └ min_commission_rate | String | 20.3 | 当入参special_id、relation_id、external_id时，该字段展示预估最低佣金率(%) |
| └ reward_info | Number | 1 | 比价场景专用，当系统检测到入参消费者ID购买当前商品会获得《天天开彩蛋》玩法的彩蛋时，该字段显示1，否则为0 |
| └ campaign_type | Number | 2 | 计划类型，0代表通用计划，1代表定向计划，2代表鹊桥计划，3代表营销计划 |
| └ coupon_type | Number | 1 | 优惠券(商品优惠券推广链接中的券)类型，1 公开券，2 私有券，3 妈妈券 |
| └ topn_info | StepRateDto |  | 前N件佣金信息-当入参get_topn_rate=1，前N件佣金生效且最高，透出该组字段 |
| └ topn_start_time | Number | 1937297392332 | 前N件佣金开始时间，当前N件佣金失效，本字段置空 |
| └ topn_end_time | Number | 1937297392332 | 前N件佣金结束时间，当前N件佣金  失效，本字段置空 |
| └ topn_total_count | Number | 3000 | 前N件初始总库存，当前N件佣金失效，本字段置空（失效：任务完成、时间结束、商品下架） |
| └ topn_quantity | Number | 3000 | 前N件剩余库存，当前N件佣金失效，本字段置空 |
| └ mini_program | MiniProgramDto |  | 小程序链接(暂未对外开放) |
| └ mini_program_appid | String | 1 | 小程序APPID |
| └ mini_program_path | String | 见具体值 | 小程序路径 |
| └ mini_program_qrcode_url | String | 见具体值 | 小程序码url地址 |
| └ extra_info | String | skuid已失效，未参与转链 | 转链成功的场景下，需要补充说明的信息 |
| └ result_code | Number | 1 | 见错误码描述 |
| └ result_msg | String | 1 | 见错误描述 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.coupon.convert', {
	'adzone_id':'123',
	'item_id':'123',
	'platform':'1',
	'relation_id':'12345',
	'special_id':'12345',
	'external_id':'12345',
	'xid':'abcdefg',
	'ucrowd_id':'1',
	'get_topn_rate':'0',
	'mini_program_link':'0',
	'biz_scene_id':'1',
	'promotion_type':'2',
	'manage_item_pub_id':'1',
	'sku_id':'1234567'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_coupon_convert_response":{
        "result":{
            "results":{
                "coupon_remain_count":6859,
                "coupon_total_count":8000,
                "coupon_info":"满16元减10元",
                "coupon_end_time":"2016-09-26",
                "coupon_start_time":"2016-09-25",
                "coupon_click_url":"https:\/\/uland.taobao.com\/coupon\/edetail?e=nqUNB1NOF3Bt3vqbdXnGloankzPYmeEFkgNrw6YHQf9pZTj41Orn8MwBAs06HAOzqQomYNedOiHDYPmqkFXqLR0HgBdG%2FDDL%2F1M%2FBw7Sf%2FesGXLf%2BqX4cbeC%2F2cR0p0NlWH0%2BknxpnCJJP%2FQkZSsyo1HvKjXo4uz&pid=mm_26381042_12970066_52864659&af=1",
                "category_id":1,
                "max_commission_rate":"20.3",
                "item_id":"524136796550",
                "item_url":"https:\/\/s.click.taobao.com\/t?spm=a2e2e.10720394\/c.90202110.1.4399704cUUhhH0&e=m%3D2%26s%3D0NJS731SUEdw4vFB6t2Z2ueEDrYVVa64LKpWJ%2Bin0XLjf2vlNIV67uIA4kDYDopEpOjgxi0uT208hw4H8GMUew7uoRPWrIBwR7CIpaNCoiKr9WTFywb%2BCtGNFs53xi4QGSKqJrqeJvt5ArodCWjzv9fsai3uVirbXH%2BQH9e66Y4%3D",
                "ysyl_click_url":"https:\/\/uland.taobao.com\/coupon\/edetail?e=nqUNB1NOF3Bt3vqbdXnGloankzPYmeEFkgNrw6YHQf9pZTj41Orn8MwBAs06HAOzqQomYNedOiHDYPmqkFXqLR0HgBdG%2FDDL%2F1M%2FBw7Sf%2FesGXLf%2BqX4cbeC%2F2cR0p0NlWH0%2BknxpnCJJP%2FQkZSsyo1HvKjXo4uz&pid=mm_26381042_12970066_52864659&af=1",
                "ysyl_tlj_face":"0.6",
                "ysyl_tlj_send_time":"2019-11-10  21:59:59",
                "ysyl_tlj_use_start_time":"2019-11-10  21:59:59",
                "ysyl_commission_rate":"20.3",
                "ysyl_tlj_use_end_time":"2019-11-10  21:59:59",
                "min_commission_rate":"20.3",
                "reward_info":1,
                "campaign_type":2,
                "coupon_type":1,
                "topn_info":{
                    "topn_start_time":1937297392332,
                    "topn_end_time":1937297392332,
                    "topn_total_count":3000,
                    "topn_quantity":3000
                },
                "mini_program":{
                    "mini_program_appid":"1",
                    "mini_program_path":"见具体值",
                    "mini_program_qrcode_url":"见具体值"
                },
                "extra_info":"skuid已失效，未参与转链"
            },
            "result_code":1,
            "result_msg":"1"
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isp.special-campaign-error | 定向计划服务异常 | 建议加入重试机制 |
| isv.item-not-exist | 宝贝已下架或非淘客宝贝 | 使用有效的item_id |
| isv.pid-not-correct | site_id或adzone_id与登录账号不匹配 | 使用登录账号下的site_id与adzone_id |
| isv.invalid-parameter:adzone_id | 入参adzone_id非法 | 检查adzone_id相关入参 |
| isp.tbkapi-service-unavailable | 内部服务不可用 | 稍后重试 |
| isv.me_param_not_correct | me参数不合法 | 参考文档 |
| isp.url_xid_not_match | 输入推广url验证失败 | 检查url参数 |
| isv.coupon_not_exist | 优惠券不存在 | 修改优惠券参数 |
| 11 | 优惠券已领完 | 更换优惠券参数 |
| isp.url_item_get_error | 输入url的解析商品id失败，请检查 | 输入url的解析商品id失败，请检查 |
| isp.rebate-id-not-match | relationId, specialId, externalId不匹配 | relationId, specialId, externalId三者若传入，那么对应绑定的用户必须是一致的 |
| isp.relation-id-not-corrent | relationId不正确 | 检查relationId是否正确 |
| isp.special-id-not-corrent | specialId不正确 | 检查specialId是否正确 |
| isp.isp.mrc-service-unavailable | 服务异常 | 检查itemId等入参是否正常，然后重试 |
| isp.top-mapping-parse-error | 服务异常 | 检查itemId等入参是否正常，然后重试 |
| 35 | 您输入的商品ID不合法，请使用升级后的新商品ID，如有疑问请加入【淘宝联盟】线上合规升级咨询群（钉钉群：44965410）进行咨询 | 您输入的商品ID不合法，请使用升级后的新商品ID，如有疑问请加入【淘宝联盟】线上合规升级咨询群（钉钉群：44965410）进行咨询 |
| 33 | 不支持该商品id | 不支持该商品id |
| 36 | ID识别异常 | 入参itemId无效，更换itemId |
| 25 | 内部服务异常 | 请重试 |

---
##taobao.tbk.adzone.create（淘宝客-推广者-创建推广位）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| site_id | Number | 必须 | 123456 |  | 网站ID |
| adzone_name | String | 必须 | 广告位 | 最大长度：64 | 广告位名称，最大长度64字符 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | MapData | MapData | MapData |
| └ model | String | mm_1_1_1 | 完整的pid |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.adzone.create', {
	'site_id':'123456',
	'adzone_name':'广告位'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_adzone_create_response":{
        "data":{
            "model":"mm_1_1_1"
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.tpwd.share.convert（淘宝客-推广者-淘口令解析&三方分成转链）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| password_content | String | 必须 | ￥2kt123e08DjviP￥ |  | 需要解析的淘口令 |
| adzone_id | Number | 必须 | 1231212 |  | 广告位ID |
| sub_pid | String | 必须 | mm_11_11_11 |  | 三方pid |
| dx | String | 可选 | 1 |  | 1表示商品转通用计划链接，其他值或不传表示优先转营销计划链接 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | MapData |  | data |
| └ num_iid | String | 562120815059 | 商品id |
| └ click_url | String | https://s.click.taobao.com/t?e=xxx | 商品淘客转链 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.tpwd.share.convert', {
	'password_content':'￥2kt123e08DjviP￥',
	'adzone_id':'1231212',
	'sub_pid':'mm_11_11_11',
	'dx':'1'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_tpwd_share_convert_response":{
        "data":{
            "num_iid":"562120815059",
            "click_url":"https:\/\/s.click.taobao.com\/t?e=xxx"
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isp.param-error | 参数错误 | 仔细检查参数 |
| isp.sys-error | 服务系统异常 | 请稍后再试 |
| 1 | 服务系统异常 | 服务系统异常 |
| 10000 | 该item_id对应宝贝已下架或非淘客宝贝 | 表示对应的商品可能已下架，或者不属于淘客商品，针对这种场景，无法提供媒体商品url，及商品id，需要媒体特别关注，并自行确定解决方案。 |
| 20010 | 淘口令解析失败 | 检查输入 |
| 20011 | 淘口令解析结果为空 | -- |
| 20012 | 淘口令解析输入口令为空 | 检查输入 |
| 20013 | 淘口令解析输入subPid格式错误 | 检查输入 |
| 20015 | 淘口令转链结果为空 | -- |
| 20016 | 淘口令转链处理异常 | -- |
| 4 | 查询不到对应的adzoneId，请检查adzoneId是否正确 | 检查输入 |
| isv.parse-result-invalid | 淘口令解析结果无效，当前淘口令无效 | 更换淘口令或稍后重试 |

---
##taobao.tbk.tpwd.convert（淘宝客-推广者-淘口令解析&转链）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| password_content | String | 必须 | ￥2k12308DjviP￥ |  | 需要解析的淘口令 |
| adzone_id | Number | 必须 | 12312312 |  | 广告位ID |
| dx | String | 可选 | 1 |  | 1表示商品转通用计划链接，其他值或不传表示优先转营销计划链接 |
| ucrowd_id | Number | 可选 | 1 |  | 会员人群ID，转链后会自动带上，可用于统计人群推广效果 |
| relation_id | String | 可选 | 123 |  | 渠道id |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | MapData | map | data |
| └ num_iid | String | 12312 | 商品Id |
| └ click_url | String | https://s.click.taobao.com/t?e=xxx | 商品淘客转链 |
| └ seller_id | String | 12121 | 店铺卖家ID |
| └ origin_url | String | https://s.click.taobao.com/t?e=xxx | 入参淘口令对应原始链接 |
| └ origin_pid | String | mm_1_1_1 | 入参淘口令推广链接中的pid，如果不属于当前调用的推广者则展示“0” |
| └ biz_scene_id | String | 1 | 1-动态ID转链场景，2-消费者比价场景，3-商品库导购场景 |
| └ model | String | ￥VWRr2yvEvsz￥ | 短口令 |
| └ password | String | 37￥ CZ3457 h6s32DqCJML￥ https://m.tb.cn/h.UX2rIfT  路路手撕肉干香辣味麻辣原味混合熟食真空小包装鸭肉风干肉条零食【立即领券】 | 长口令 |
| └ url_type | String | 1 | 链接类型。1-单品，2-店铺，3-活动，0-其它 |
| └ short_url | String | https://s.click.taobao.com/vpIZmSu | 短链接 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.tpwd.convert', {
	'password_content':'￥2k12308DjviP￥',
	'adzone_id':'12312312',
	'dx':'1',
	'ucrowd_id':'1',
	'relation_id':'123'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_tpwd_convert_response":{
        "data":{
            "num_iid":"12312",
            "click_url":"https:\/\/s.click.taobao.com\/t?e=xxx",
            "seller_id":"12121",
            "origin_url":"https:\/\/s.click.taobao.com\/t?e=xxx",
            "origin_pid":"mm_1_1_1",
            "biz_scene_id":"1",
            "model":"￥VWRr2yvEvsz￥",
            "password":"37￥ CZ3457 h6s32DqCJML￥ https:\/\/m.tb.cn\/h.UX2rIfT  路路手撕肉干香辣味麻辣原味混合熟食真空小包装鸭肉风干肉条零食【立即领券】",
            "url_type":"1",
            "short_url":"https:\/\/s.click.taobao.com\/vpIZmSu"
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| 20010 | 淘口令解析失败 | 检查输入 |
| 20011 | 淘口令解析结果为空 | 更换淘口令或稍后重试 |
| 20012 | 淘口令解析输入口令为空 | 检查输入 |
| 20013 | 淘口令解析输入subPid格式错误 | 检查输入 |
| 20015 | 淘口令转链结果为空 | 更换淘口令或稍后重试 |
| 4 | 查询不到对应的adzoneId，请检查adzoneId是否正确 | 检查输入 |
| isp.param-error | 参数错误 | 仔细检查参数 |
| isp.sys-error | 服务系统异常 | 请稍后再试 |
| 1 | 服务系统异常 | 服务系统异常 |
| 10000 | 该item_id对应宝贝已下架或非淘客宝贝 | 表示对应的商品可能已下架，或者不属于淘客商品，针对这种场景，无法提供媒体商品url，及商品id，需要媒体特别关注，并自行确定解决方案。 |
| 20016 | 淘口令转链处理异常 | -- |
| 2 | pid不正确 | 检查输入 |
| 20014 | 淘口令转链入参不合法 | 检查淘口令入参 |
| isv.parse-result-invalid | 淘口令解析结果无效，当前淘口令无效 | 更换淘口令或稍后重试 |
| 20008 | 淘口令解析结果无效，当前淘口令无效 | 更换淘口令或稍后重试 |
| 0 | 内部服务不可用 | 稍后重试 |

---
##taobao.tbk.dg.newuser.order.get（淘宝客-推广者-新用户订单明细查询）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| page_size | Number | 可选 | 20 | 默认值：20 | 页大小，默认20，1~100 |
| page_no | Number | 可选 | 1 | 默认值：1 | 页码，默认1 |
| adzone_id | Number | 可选 | 123 |  | mm_xxx_xxx_xxx的第三位 |
| start_time | Date | 可选 | 2018-01-24 00:34:05 |  | 开始时间，当活动为淘宝活动，表示最早注册时间；当活动为支付宝活动，表示最早绑定时间；当活动为天猫活动，表示最早领取红包时间 |
| end_time | Date | 可选 | 2018-01-24 00:34:05 |  | 结束时间，当活动为淘宝活动，表示最晚结束时间；当活动为支付宝活动，表示最晚绑定时间；当活动为天猫活动，表示最晚领取红包的时间 |
| activity_id | String | 必须 | 119013_2 |  | 活动id， 活动名称与活动ID列表（该字段已废弃） |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| results | Results | data | data |
| └ data | Data |  | data |
| └ results | MapData

                                 [] |  | resultList |
| └ register_time | Date | 2018-01-24 00:34:05 | 新注册时间，仅淘宝拉新适用 |
| └ bind_time | Date | 2018-01-24 00:34:05 | 当前活动为淘宝拉新活动时，bind_time为新激活时间； 当前活动为支付宝拉新活动时，bind_time为绑定时间。 |
| └ buy_time | Date | 2018-01-24 00:34:05 | 首购时间，仅淘宝，天猫拉新适用 |
| └ status | Number | 2 | 新人状态， 当前活动为淘宝拉新活动时，1: 新注册，2:激活，3:首购，4:确认收货； 当前活动为支付宝实名活动时，1：已绑定，2：拉新成功，3：无效用户；当前活动为支付宝新登活动时，3：手淘首购，4：手淘确认收货；当前活动为天猫拉新活动时，2:已领取，3:已首购，4:已收货 |
| └ mobile | String | 137****9999 | 新人手机号 |
| └ order_tk_type | Number | 1 | 订单淘客类型:1.淘客订单；2.非淘客订单，仅淘宝，天猫拉新适用 |
| └ union_id | String | 222222 | 分享用户(unionid)，仅淘宝，天猫拉新适用 |
| └ member_id | Number | 11 | 来源媒体ID(pid中mm_1_2_3)中第1位 |
| └ member_nick | String | 联盟官方账号 | 来源媒体名称 |
| └ site_id | Number | 11 | 来源站点ID(pid中mm_1_2_3)中第2位 |
| └ site_name | String | 联盟官方站点 | 来源站点名称 |
| └ adzone_id | Number | 3434 | 来源广告位ID(pid中mm_1_2_3)中第3位 |
| └ adzone_name | String | 联盟官方推广位 | 来源广告位名称 |
| └ tb_trade_parent_id | Number | 1112333 | 淘宝订单id，仅淘宝，天猫拉新适用 |
| └ accept_time | Date | 2018-01-24 00:34:05 | 确认收货时间，仅天猫拉新适用 |
| └ receive_time | Date | 2018-01-24 00:34:05 | 领取红包时间，仅天猫拉新适用 |
| └ success_time | Date | 2018-01-24 00:34:05 | 拉新成功时间，仅支付宝拉新适用 |
| └ activity_type | String | taobao | 活动类型，taobao-淘宝 alipay-支付宝 tmall-天猫 |
| └ activity_id | String | 119013_2 | 活动id |
| └ biz_date | String | 20180202 | 日期，格式为"20180202" |
| └ orders | OrderData

                                 [] |  | 复购订单，仅适用于手淘拉新 |
| └ commission | String | 9.15 | 预估佣金 |
| └ confirm_receive_time | String | 20180204 | 收货时间 |
| └ pay_time | String | 20180203 | 支付时间 |
| └ order_no | String | 1589541350997963 | 订单号 |
| └ bind_card_time | Date | 2018-01-24 00:34:05 | 绑卡日期，仅适用于手淘拉新 |
| └ login_time | Date | 2018-01-24 00:34:05 | loginTime |
| └ is_card_save | Number | 1 | 银行卡是否是绑定状态：1-绑定，0-未绑定 |
| └ use_rights_time | Date | 2018-01-24 00:34:05 | 使用权益时间 |
| └ get_rights_time | Date | 2018-01-24 00:34:05 | 领取权益时间 |
| └ relation_id | String | 232342 | 渠道关系id |
| └ page_no | Number | 1 | 页码 |
| └ page_size | Number | 20 | 每页大小 |
| └ has_next | Boolean | true | 是否有下一页 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.newuser.order.get', {
	'page_size':'20',
	'page_no':'1',
	'adzone_id':'123',
	'start_time':'2018-01-24 00:34:05',
	'end_time':'2018-01-24 00:34:05',
	'activity_id':'119013_2'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_newuser_order_get_response":{
        "results":{
            "data":{
                "results":{
                    "map_data":[
                        {
                            "register_time":"2018-01-24 00:34:05",
                            "bind_time":"2018-01-24 00:34:05",
                            "buy_time":"2018-01-24 00:34:05",
                            "status":2,
                            "mobile":"137****9999",
                            "order_tk_type":1,
                            "union_id":"222222",
                            "member_id":11,
                            "member_nick":"联盟官方账号",
                            "site_id":11,
                            "site_name":"联盟官方站点",
                            "adzone_id":3434,
                            "adzone_name":"联盟官方推广位",
                            "tb_trade_parent_id":1112333,
                            "accept_time":"2018-01-24 00:34:05",
                            "receive_time":"2018-01-24 00:34:05",
                            "success_time":"2018-01-24 00:34:05",
                            "activity_type":"taobao",
                            "activity_id":"119013_2",
                            "biz_date":"20180202",
                            "orders":{
                                "order_data":[
                                    {
                                        "commission":"9.15",
                                        "confirm_receive_time":"20180204",
                                        "pay_time":"20180203",
                                        "order_no":"1589541350997963"
                                    }
                                ]
                            },
                            "bind_card_time":"2018-01-24 00:34:05",
                            "login_time":"2018-01-24 00:34:05",
                            "is_card_save":1,
                            "use_rights_time":"2018-01-24 00:34:05",
                            "get_rights_time":"2018-01-24 00:34:05",
                            "relation_id":"232342"
                        }
                    ]
                },
                "page_no":1,
                "page_size":20,
                "has_next":true
            }
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isp.tbkapi-service-unavailable | 淘宝客API服务不可用 | 请稍后重试 |
| isv.invalid-parameter:start_price | 参数填写不正确 | 参数填写不正确 |
| isv.invalid-parameter:end_price | 参数填写不正确 | 参数填写不正确 |
| isv.invalid-parameter:end_tk_rate | 参数填写不正确 | 参数填写不正确 |
| 4 | 查询不到对应的adzoneId | 请检查adzoneId是否正确 |
| 2 | pid不正确 | 请检查是否输入了正确的adzoneId和siteId |

---
##taobao.tbk.dg.optimus.material（淘宝客-推广者-物料精选）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| page_size | Number | 可选 | 20 | 默认值：20 | 页大小，默认20，1~100 |
| page_no | Number | 可选 | 1 | 默认值：1 | 第几页，默认：1 |
| adzone_id | Number | 必须 | 123 |  | mm_xxx_xxx_xxx的第三位 |
| material_id | Number | 必须 | 123 |  | 官方的物料Id(详细物料id见：https://market.m.taobao.com/app/qn/toutiao-new/index-pc.html#/detail/10628875?_k=gpov9a) |
| device_value | String | 可选 | xxx |  | 智能匹配-设备号加密后的值（MD5加密需32位小写），类型为OAID时传原始OAID值 |
| device_encrypt | String | 可选 | MD5 |  | 智能匹配-设备号加密类型：MD5，类型为OAID时不传 |
| device_type | String | 可选 | IMEI |  | 智能匹配-设备号类型：IMEI，或者IDFA，或者UTDID（UTDID不支持MD5加密），或者OAID |
| content_id | Number | 可选 | 323 |  | 内容专用-内容详情ID |
| content_source | String | 可选 | xxx |  | 内容专用-内容渠道信息 |
| item_id | String | 可选 | 33243 |  | 商品ID，用于相似商品推荐 |
| favorites_id | String | 可选 | 123445 |  | 选品库投放id |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result_list | MapData [] |  | resultList |
| └ coupon_amount | Number | 40 | 优惠券（元） 若属于预售商品，该优惠券付尾款可用，付定金不可用 |
| └ small_images | String

                                 [] |  | 商品信息-商品小图列表 |
| └ shop_title | String | 魔黛娅内衣旗舰店 | 店铺信息-店铺名称 |
| └ category_id | Number | 162201 | 商品信息-叶子类目id |
| └ coupon_start_fee | String | 69 | 优惠券信息-优惠券起用门槛，满X元可用。如：满299元减20元 |
| └ item_id | String | 556633720749 | 商品信息-宝贝id |
| └ coupon_total_count | Number | 30000 | 优惠券信息-优惠券总量 |
| └ user_type | Number | 1 | 店铺信息-卖家类型，0表示淘宝，1表示天猫，3表示特价版 |
| └ zk_final_price | String | 79.9 | 折扣价（元） 若属于预售商品，付定金时间内，折扣价=预售价 |
| └ coupon_remain_count | Number | 1936 | 优惠券信息-优惠券剩余量 |
| └ commission_rate | String | 5.50 | 商品信息-佣金比率(%) |
| └ coupon_start_time | String | 2017-10-29 | 优惠券信息-优惠券开始时间 |
| └ title | String | 毛呢阔腿裤港味复古女裤子秋冬九分裤萝卜裤显瘦高腰韩版2017新款 | 商品信息-商品标题 |
| └ item_description | String | 裤子 | 商品信息-宝贝描述（推荐理由,不一定有） |
| └ seller_id | Number | 745957850 | 店铺信息-卖家id |
| └ volume | Number | 3837 | 商品信息-30天销量 |
| └ coupon_end_time | String | 2017-11-02 | 优惠券信息-优惠券结束时间 |
| └ coupon_click_url | String | //uland.taobao.com/coupon/edetail?e=pR6YtnFKK%2B8GQASttHIRqcEWOmlidB03Pf45HLyCqA8dRAklSM5tEQ36hBQToU3M3MmLjFwLsqgZxcV7BPtHQDd2Naqom0e0&mt=1&app_pvid=0ab0fac715095507006577956e&ptl=app_pvid:0ab0fac715095507006577956e;tpp_pvid:41362290-fa0b-4252-b172-6afc9c00e2c8 | 链接-宝贝+券二合一页面链接(该字段废弃，请勿再用) |
| └ pict_url | String | //img.alicdn.com/bao/uploaded/i4/745957850/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg | 商品信息-商品主图 |
| └ click_url | String | //item.taobao.com/item.htm?id=556633720749&scm=1007.16190.92234.0&pvid=41362290-fa0b-4252-b172-6afc9c00e2c8&app_pvid=0ab0fac715095507006577956e | 链接-宝贝推广链接 |
| └ stock | Number | 123 | 拼团专用-拼团剩余库存 |
| └ sell_num | Number | 123 | 拼团专用-拼团已售数量 |
| └ total_stock | Number | 123 | 拼团专用-拼团库存数量 |
| └ oetime | String | 1640317400000 | 拼团专用-拼团结束时间 |
| └ ostime | String | 1640317400000 | 拼团专用-拼团开始时间 |
| └ jdd_num | Number | 1 | 拼团专用-拼团几人团 |
| └ jdd_price | String | 12 | 拼团专用-拼团拼成价，单位元 |
| └ orig_price | String | 12 | 拼团专用-拼团一人价（原价)，单位元 |
| └ level_one_category_name | String | 美妆 | 商品信息-一级类目名称 |
| └ level_one_category_id | Number | 1 | 商品信息-一级类目ID |
| └ category_name | String | 牛仔裤 | 商品信息-叶子类目名称 |
| └ white_image | String | https://img.alicdn.com/bao/uploaded/i4/745957850/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg | 商品信息-商品白底图 |
| └ short_title | String | sss | 商品信息-商品短标题 |
| └ word_list | WordMapData

                                 [] |  | 商品信息-商品关联词 |
| └ url | String | https://uland.taobao.com/semm/tbxxxx | 链接-商品相关关联词落地页地址 |
| └ word | String | 孕妇装 | 商品相关的关联词 |
| └ tmall_play_activity_info | String | 前n件x折 | 营销-天猫营销玩法 |
| └ uv_sum_pre_sale | Number | 21 | 商品信息-预售数量 |
| └ x_id | String | uESS0mv8JvfJRMKlIgCD5At9VuHVBXoqBRihfQlo4ybLiKygRlqiN4eoxoZDfe38uSogWy6GB971jD2N8tLuuc | 物料块id(测试中请勿使用) |
| └ new_user_price | String | 1.99 | 商品信息-新人价 |
| └ coupon_info | String | 满299减30元 | 优惠券信息-优惠券满减信息 |
| └ coupon_share_url | String | //uland.taobao.com/coupon/edetail?e=pR6YtnFKK%2B8GQASttHIRqcEWOmlidB03Pf45HLyCqA8dRAklSM5tEQ36hBQToU3M3MmLjFwLsqgZxcV7BPtHQDd2Naqom0e0&mt=1&app_pvid=0ab0fac715095507006577956e&ptl=app_pvid:0ab0fac715095507006577956e;tpp_pvid:41362290-fa0b-4252-b172-6afc9c00e2c8 | 链接-宝贝+券二合一页面链接 |
| └ nick | String | 秉迪数码专营店 | 店铺信息-卖家昵称 |
| └ reserve_price | String | 2.99 | 商品信息-一口价 |
| └ ju_online_end_time | String | 1559750399000 | 聚划算信息-聚淘结束时间 |
| └ ju_online_start_time | String | 1559232000000 | 聚划算信息-聚淘开始时间 |
| └ maochao_play_end_time | String | 1559750399000 | 猫超玩法信息-活动结束时间，精确到毫秒 |
| └ maochao_play_start_time | String | 1559232000000 | 猫超玩法信息-活动开始时间，精确到毫秒 |
| └ maochao_play_conditions | String | 2,3 | 猫超玩法信息-折扣条件，价格百分数存储，件数按数量存储。可以有多个折扣条件，与折扣字段对应，','分割 |
| └ maochao_play_discounts | String | 500,450 | 猫超玩法信息-折扣，折扣按照百分数存储，其余按照单位分存储。可以有多个折扣，','分割 |
| └ maochao_play_discount_type | String | 2 | 猫超玩法信息-玩法类型，2:折扣(满n件折扣),5:减钱(满n元减m元) |
| └ maochao_play_free_post_fee | String | 1 | 猫超玩法信息-当前是否包邮，1:是，0:否 |
| └ multi_coupon_zk_rate | String | 0.41234 | 多件券优惠比例 |
| └ price_after_multi_coupon | String | 9.9 | 多件券件单价 |
| └ multi_coupon_item_count | String | 3 | 多件券单品件数 |
| └ lock_rate | String | 110 | 锁住的佣金率 |
| └ lock_rate_end_time | Number | 1567440000000 | 锁佣结束时间 |
| └ lock_rate_start_time | Number | 1567440000000 | 锁佣开始时间 |
| └ promotion_type | String | 1 | 满减满折的类型（1. 满减 2. 满折） |
| └ promotion_info | String | 满2件打5折；满300减20 | 满减满折信息 |
| └ promotion_discount | String | 300 | 满减满折门槛（满2件打5折中值为2；满300减20中值为300） |
| └ promotion_condition | String | 5 | 满减满折优惠（满2件打5折中值为5；满300减20中值为20） |
| └ presale_discount_fee_text | String | 付定金立减5元 | 预售商品-优惠信息 |
| └ presale_tail_end_time | Number | 1567440000000 | 预售商品-付尾款结束时间（毫秒） |
| └ presale_tail_start_time | Number | 1567440000000 | 预售商品-付尾款开始时间（毫秒） |
| └ presale_end_time | Number | 1567440000000 | 预售商品-付定金结束时间（毫秒） |
| └ presale_start_time | Number | 1567440000000 | 预售商品-付定金开始时间（毫秒） |
| └ presale_deposit | String | 100 | 预售商品-定金（元） |
| └ ysyl_tlj_use_start_time | String | 2019-11-10 21:59:59 | 预售有礼-淘礼金使用开始时间 |
| └ ysyl_commission_rate | String | 2030（表示20.3%） | 预售有礼-佣金比例（ 预售有礼活动享受的推广佣金比例，注：推广该活动有特殊分成规则，请详见：https://tbk.bbs.taobao.com/detail.html?appId=45301&postId=9334376 ） |
| └ ysyl_tlj_send_time | String | 2019-11-10 21:59:59 | 预售有礼-淘礼金发放时间 |
| └ ysyl_tlj_face | String | 0.6 | 预售有礼-预估淘礼金（元） |
| └ ysyl_click_url | String | https://uland.taobao.com/coupon/edetail?e=nqUNB1NOF3Bt3vqbdXnGloankzPYmeEFkgNrw6YHQf9pZTj41Orn8MwBAs06HAOzqQomYNedOiHDYPmqkFXqLR0HgBdG%2FDDL%2F1M%2FBw7Sf%2FesGXLf%2BqX4cbeC%2F2cR0p0NlWH0%2BknxpnCJJP%2FQkZSsyo1HvKjXo4uz&pid=mm_26381042_12970066_52864659&af=1 | 预售有礼-推广链接 |
| └ ysyl_tlj_use_end_time | String | 2019-11-10 21:59:59 | 预售有礼-淘礼金使用结束时间 |
| └ ju_play_end_time | Number | 1567440000000 | 聚划算满减  -结束时间（毫秒） |
| └ ju_play_start_time | Number | 1567440000000 | 聚划算满减  -开始时间（毫秒） |
| └ play_info | String | 玩法 | 1聚划算满减：满N件减X元，满N件X折，满N件X元）  2天猫限时抢：前N分钟每件X元，前N分钟满N件每件X元，前N件每件X元） |
| └ tmall_play_activity_end_time | Number | 1567440000000 | 天猫限时抢可售  -结束时间（毫秒） |
| └ tmall_play_activity_start_time | Number | 1567440000000 | 天猫限时抢可售  -开始时间（毫秒） |
| └ ju_pre_show_end_time | String | 1581868800000 | 聚划算信息-商品预热开始时间（毫秒） |
| └ ju_pre_show_start_time | String | 1582300799000 | 聚划算信息-商品预热结束时间（毫秒） |
| └ favorites_info | FavoritesInfo |  | 选品库信息 |
| └ total_count | Number | 100 | 选品库总数量 |
| └ favorites_list | FavoritesDetail

                                 [] |  | 选品库详细信息 |
| └ favorites_id | Number | 12334 | 选品库id |
| └ favorites_title | String | 测试选品库 | 选品库标题 |
| └ sale_price | String | 168 | 活动价 |
| └ kuadian_promotion_info | String | ["每100减20","每200减50"] | 跨店满减信息 |
| └ sub_title | String | 吉品鲍鱼 关西参 | 商品子标题 |
| └ jhs_price_usp_list | String | 满200减10 | 聚划算商品价格卖点描述 |
| └ tqg_online_end_time | String | 1581868800000 | 淘抢购商品专用-结束时间 |
| └ tqg_online_start_time | String | 1581868800000 | 淘抢购商品专用-开团时间 |
| └ tqg_sold_count | Number | 20 | 淘抢购商品专用-已抢购数量 |
| └ tqg_total_count | Number | 50 | 淘抢购商品专用-总库存 |
| └ superior_brand | String | 1 | 是否品牌精选，0不是，1是 |
| └ is_brand_flash_sale | String | 1 | 是否品牌快抢，0不是，1是 |
| └ hot_flag | String | 1 | 是否是热门商品，0不是，1是 |
| └ topn_info | TopNInfoDTO |  | 前N件佣金信息-前N件佣金生效或预热时透出以下字段 |
| └ topn_quantity | Number | 3000 | 前N件剩余库存 |
| └ topn_total_count | Number | 3000 | 前N件初始总库存 |
| └ topn_end_time | String | 1937297392332 | 前N件佣金结束时间 |
| └ topn_start_time | String | 1937297392332 | 前N件佣金开始时间 |
| └ topn_rate | String | 30 | 前N件佣金率 |
| └ bybt_info | BybtInfoDTO |  | 百亿补贴信息 |
| └ bybt_brand_logo | String | //img.alicdn.com/bao/uploaded/i4/745957850/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg | 百亿补贴品牌logo |
| └ bybt_pic_url | String | //img.alicdn.com/bao/uploaded/i4/745957850/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg | 百亿补贴白底图 |
| └ bybt_item_tags | String

                                 [] | ["https://gw.alicdn.com/tfs/TB1CvN50KH2gK0jSZJnXXaT1FXa-167-42.png?getAvatar=avatar","https://gw.alicdn.com/tfs/TB10rZqkCR26e4jSZFEXXbwuXXa-132-42.png?getAvatar=avatar"] | 百亿补贴商品特征标签，eg.今日发货、晚发补偿、限购一件等 |
| └ bybt_coupon_amount | String | 10.00 | 百亿补贴专属券面额，仅限百亿补贴场景透出 |
| └ bybt_show_price | String | 100.00 | 百亿补贴页面实时价 |
| └ bybt_lowest_price | String | 200.00 | 全网对比参考价格 |
| └ bybt_end_time | String | 1559750399000 | 商品的百亿补贴开始时间 |
| └ bybt_start_time | String | 1559750399000 | 商品的百亿补贴结束时间 |
| └ tt_sold_count | String | 200+ | 商品入驻淘特后产生的所有销量量级，不特指某段具体时间 |
| └ maifan_promotion | MaifanPromotionDTO |  | 猫超买返卡信息 |
| └ maifan_promotion_end_time | String | 1559750399000 | 猫超买返卡活动结束时间 |
| └ maifan_promotion_start_time | String | 1559750399000 | 猫超买返卡活动开始时间 |
| └ maifan_promotion_discount | String | 200 | 猫超买返卡面额 |
| └ maifan_promotion_condition | String | 100 | 猫超买返卡总数，-1代表不限量，其他大于等于0的值为总数 |
| └ cpa_reward_type | String | 0 1 2 | 额外奖励活动类型，如果一个商品有多个奖励类型，返回结果使用空格分割，0=单单奖励(已失效)，1=超级单单奖励(已失效)，2=年货节单单奖励 |
| └ cpa_reward_amount | String | 1.11 2.22 3.21 | 额外奖励活动金额，活动奖励金额的类型与cpa_reward_type字段对应，如果一个商品有多个奖励类型，返回结果使用空格分割 |
| └ activity_id | String | 188 | 合作伙伴单单补ID，用作“年货节超级单单补”活动合作伙伴奖励统计依据 |
| └ sp_campaign_list | SpCampaign

                                 [] |  | 定向计划集合 |
| └ sp_cid | String | 123 | 定向计划活动ID |
| └ sp_name | String | 定向计划活动1 | 定向计划名称 |
| └ sp_rate | String | 1550表示15.5% | 定向佣金率 |
| └ sp_lock_status | String | 0 | 定向是否锁佣，0=不锁佣 1=锁佣 |
| └ sp_apply_link | String | http://pub.alimama.com/portal/promo/shop/campaign/detail.htm?mode=info&campaignId=1000492470&creatorId=98836808&breadcrumb=false | 定向计划申请链接 |
| └ sp_status | String | 1 | 定向计划是否可用 1-可用 0-不可用 |
| is_default | String | false | 推荐信息-是否抄底 |
| total_count | Number | 100 | 商品总数-目前只有全品库商品查询有该字段 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.optimus.material', {
	'page_size':'20',
	'page_no':'1',
	'adzone_id':'123',
	'material_id':'123',
	'device_value':'xxx',
	'device_encrypt':'MD5',
	'device_type':'IMEI',
	'content_id':'323',
	'content_source':'xxx',
	'item_id':'33243',
	'favorites_id':'123445'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_optimus_material_response":{
        "result_list":{
            "map_data":[
                {
                    "coupon_amount":40,
                    "small_images":{
                        "string":[
                            ""
                        ]
                    },
                    "shop_title":"魔黛娅内衣旗舰店",
                    "category_id":162201,
                    "coupon_start_fee":"69",
                    "item_id":"556633720749",
                    "coupon_total_count":30000,
                    "user_type":1,
                    "zk_final_price":"79.9",
                    "coupon_remain_count":1936,
                    "commission_rate":"5.50",
                    "coupon_start_time":"2017-10-29",
                    "title":"毛呢阔腿裤港味复古女裤子秋冬九分裤萝卜裤显瘦高腰韩版2017新款",
                    "item_description":"裤子",
                    "seller_id":745957850,
                    "volume":3837,
                    "coupon_end_time":"2017-11-02",
                    "coupon_click_url":"\/\/uland.taobao.com\/coupon\/edetail?e=pR6YtnFKK%2B8GQASttHIRqcEWOmlidB03Pf45HLyCqA8dRAklSM5tEQ36hBQToU3M3MmLjFwLsqgZxcV7BPtHQDd2Naqom0e0&mt=1&app_pvid=0ab0fac715095507006577956e&ptl=app_pvid:0ab0fac715095507006577956e;tpp_pvid:41362290-fa0b-4252-b172-6afc9c00e2c8",
                    "pict_url":"\/\/img.alicdn.com\/bao\/uploaded\/i4\/745957850\/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg",
                    "click_url":"\/\/item.taobao.com\/item.htm?id=556633720749&scm=1007.16190.92234.0&pvid=41362290-fa0b-4252-b172-6afc9c00e2c8&app_pvid=0ab0fac715095507006577956e",
                    "stock":123,
                    "sell_num":123,
                    "total_stock":123,
                    "oetime":"1640317400000",
                    "ostime":"1640317400000",
                    "jdd_num":1,
                    "jdd_price":"12",
                    "orig_price":"12",
                    "level_one_category_name":"美妆",
                    "level_one_category_id":1,
                    "category_name":"牛仔裤",
                    "white_image":"https:\/\/img.alicdn.com\/bao\/uploaded\/i4\/745957850\/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg",
                    "short_title":"sss",
                    "word_list":{
                        "word_map_data":[
                            {
                                "url":"https:\/\/uland.taobao.com\/semm\/tbxxxx",
                                "word":"孕妇装"
                            }
                        ]
                    },
                    "tmall_play_activity_info":"前n件x折",
                    "uv_sum_pre_sale":21,
                    "x_id":"uESS0mv8JvfJRMKlIgCD5At9VuHVBXoqBRihfQlo4ybLiKygRlqiN4eoxoZDfe38uSogWy6GB971jD2N8tLuuc",
                    "new_user_price":"1.99",
                    "coupon_info":"满299减30元",
                    "coupon_share_url":"\/\/uland.taobao.com\/coupon\/edetail?e=pR6YtnFKK%2B8GQASttHIRqcEWOmlidB03Pf45HLyCqA8dRAklSM5tEQ36hBQToU3M3MmLjFwLsqgZxcV7BPtHQDd2Naqom0e0&mt=1&app_pvid=0ab0fac715095507006577956e&ptl=app_pvid:0ab0fac715095507006577956e;tpp_pvid:41362290-fa0b-4252-b172-6afc9c00e2c8",
                    "nick":"秉迪数码专营店",
                    "reserve_price":"2.99",
                    "ju_online_end_time":"1559750399000",
                    "ju_online_start_time":"1559232000000",
                    "maochao_play_end_time":"1559750399000",
                    "maochao_play_start_time":"1559232000000",
                    "maochao_play_conditions":"2,3",
                    "maochao_play_discounts":"500,450",
                    "maochao_play_discount_type":"2",
                    "maochao_play_free_post_fee":"1",
                    "multi_coupon_zk_rate":"0.41234",
                    "price_after_multi_coupon":"9.9",
                    "multi_coupon_item_count":"3",
                    "lock_rate":"110",
                    "lock_rate_end_time":1567440000000,
                    "lock_rate_start_time":1567440000000,
                    "promotion_type":"1",
                    "promotion_info":"满2件打5折；满300减20",
                    "promotion_discount":"300",
                    "promotion_condition":"5",
                    "presale_discount_fee_text":"付定金立减5元",
                    "presale_tail_end_time":1567440000000,
                    "presale_tail_start_time":1567440000000,
                    "presale_end_time":1567440000000,
                    "presale_start_time":1567440000000,
                    "presale_deposit":"100",
                    "ysyl_tlj_use_start_time":"2019-11-10 21:59:59",
                    "ysyl_commission_rate":"2030（表示20.3%）",
                    "ysyl_tlj_send_time":"2019-11-10 21:59:59",
                    "ysyl_tlj_face":"0.6",
                    "ysyl_click_url":"https:\/\/uland.taobao.com\/coupon\/edetail?e=nqUNB1NOF3Bt3vqbdXnGloankzPYmeEFkgNrw6YHQf9pZTj41Orn8MwBAs06HAOzqQomYNedOiHDYPmqkFXqLR0HgBdG%2FDDL%2F1M%2FBw7Sf%2FesGXLf%2BqX4cbeC%2F2cR0p0NlWH0%2BknxpnCJJP%2FQkZSsyo1HvKjXo4uz&pid=mm_26381042_12970066_52864659&af=1",
                    "ysyl_tlj_use_end_time":"2019-11-10 21:59:59",
                    "ju_play_end_time":1567440000000,
                    "ju_play_start_time":1567440000000,
                    "play_info":"玩法",
                    "tmall_play_activity_end_time":1567440000000,
                    "tmall_play_activity_start_time":1567440000000,
                    "ju_pre_show_end_time":"1581868800000",
                    "ju_pre_show_start_time":"1582300799000",
                    "favorites_info":{
                        "total_count":100,
                        "favorites_list":{
                            "favorites_detail":[
                                {
                                    "favorites_id":12334,
                                    "favorites_title":"测试选品库"
                                }
                            ]
                        }
                    },
                    "sale_price":"168",
                    "kuadian_promotion_info":"[\"每100减20\",\"每200减50\"]",
                    "sub_title":"吉品鲍鱼 关西参",
                    "jhs_price_usp_list":"满200减10",
                    "tqg_online_end_time":"1581868800000",
                    "tqg_online_start_time":"1581868800000",
                    "tqg_sold_count":20,
                    "tqg_total_count":50,
                    "superior_brand":"1",
                    "is_brand_flash_sale":"1",
                    "hot_flag":"1",
                    "topn_info":{
                        "topn_quantity":3000,
                        "topn_total_count":3000,
                        "topn_end_time":"1937297392332",
                        "topn_start_time":"1937297392332",
                        "topn_rate":"30"
                    },
                    "bybt_info":{
                        "bybt_brand_logo":"\/\/img.alicdn.com\/bao\/uploaded\/i4\/745957850\/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg",
                        "bybt_pic_url":"\/\/img.alicdn.com\/bao\/uploaded\/i4\/745957850\/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg",
                        "bybt_item_tags":{
                            "string":[
                                "[\"https:\/\/gw.alicdn.com\/tfs\/TB1CvN50KH2gK0jSZJnXXaT1FXa-167-42.png?getAvatar=avatar\"",
                                "\"https:\/\/gw.alicdn.com\/tfs\/TB10rZqkCR26e4jSZFEXXbwuXXa-132-42.png?getAvatar=avatar\"]"
                            ]
                        },
                        "bybt_coupon_amount":"10.00",
                        "bybt_show_price":"100.00",
                        "bybt_lowest_price":"200.00",
                        "bybt_end_time":"1559750399000",
                        "bybt_start_time":"1559750399000"
                    },
                    "tt_sold_count":"200+",
                    "maifan_promotion":{
                        "maifan_promotion_end_time":"1559750399000",
                        "maifan_promotion_start_time":"1559750399000",
                        "maifan_promotion_discount":"200",
                        "maifan_promotion_condition":"100"
                    },
                    "cpa_reward_type":"0 1 2",
                    "cpa_reward_amount":"1.11 2.22 3.21",
                    "activity_id":"188",
                    "sp_campaign_list":{
                        "sp_campaign":[
                            {
                                "sp_cid":"123",
                                "sp_name":"定向计划活动1",
                                "sp_rate":"1550表示15.5%",
                                "sp_lock_status":"0",
                                "sp_apply_link":"http:\/\/pub.alimama.com\/portal\/promo\/shop\/campaign\/detail.htm?mode=info&campaignId=1000492470&creatorId=98836808&breadcrumb=false",
                                "sp_status":"1"
                            }
                        ]
                    }
                }
            ]
        },
        "is_default":"false",
        "total_count":100
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isp.tbkapi-service-unavailable | 淘宝客API服务不可用 | 请稍后重试 |
| isv.invalid-parameter:start_price | 参数填写不正确 | 参数填写不正确 |
| isv.invalid-parameter:end_price | 参数填写不正确 | 参数填写不正确 |
| isv.invalid-parameter:end_tk_rate | 参数填写不正确 | 参数填写不正确 |
| 4 | 查询不到对应的adzoneId | 请检查adzoneId是否正确 |
| 2 | pid不正确 | 请检查是否输入了正确的adzoneId和siteId |
| 50001 | 无结果 | 宝贝数据为空，请重新查询 |
| isp.sys-error | 服务异常 | 请稍后重试 |
| 30001 | 无效物料ID | 请传入有效的物料ID |
| 40001 | 调用失败 | 请重新调用 |
| 50002 | 调用频率过高 | 请稍后再试 |
| 41 | pageSize不合法 | 参考文档或设置为1~7之间 |
| isp.entry-sys-error | 内部服务出错 | 稍后重试 |
| 1103 | 活动物料id无效 | 检查调用参数 |
| 1201 | 口令类型无效 | 检查调用参数 |


---
##taobao.tbk.dg.newuser.order.sum（淘宝客-推广者-拉新活动对应数据查询）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| page_size | Number | 必须 | 20 | 最小值：1 最大值：100 | 页大小，默认20，1~100 |
| adzone_id | Number | 可选 | 123 |  | mm_xxx_xxx_xxx的第三位 |
| page_no | Number | 必须 | 1 |  | 页码，默认1 |
| site_id | Number | 可选 | 123 |  | mm_xxx_xxx_xxx的第二位 |
| activity_id | String | 必须 | sxxx |  | 活动id， 活动名称与活动ID列表，请参见https://tbk.bbs.taobao.com/detail.html?appId=45301&postId=8599277 |
| settle_month | String | 可选 | 201807 |  | 结算月份 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| results | Data | data | data |
| └ data | Data | data | data |
| └ page_no | Number | 1 | 页码 |
| └ page_size | Number | 20 | 每页大小 |
| └ has_next | Boolean | true | 是否有下一页 |
| └ results | Data

                                 [] |  | resultList |
| └ activity_id | String | dddxx | 活动ID |
| └ biz_date | String | 20180321 | 日期 |
| └ reg_user_cnt | Number | 100 | 新注册用户数 |
| └ login_user_cnt | Number | 99 | 新激活用户数 |
| └ alipay_user_cnt | Number | 88 | 首购用户数 |
| └ rcv_valid_user_cnt | Number | 66 | 结算有效用户数 |
| └ rcv_user_cnt | Number | 77 | 确认收货用户数 |
| └ alipay_user_cpa_pre_amt | String | 44.33 | 结算CPA 奖励金额：仅支持member 维度的统计 |
| └ bind_buy_user_cpa_pre_amt | String | 33.22 | 当日激活且首购结算的CPA 金额：仅适用于八天乐，仅支持member维度的统计 |
| └ bind_buy_valid_user_cnt | Number | 55 | 当日激活且首购的有效用户数：仅适用于八天乐，支持member，adzone维度的统计 |
| └ bind_card_valid_user_cnt | Number |  | bindCardValidUserCnt |
| └ re_buy_valid_user_cnt | Number |  | reBuyValidUserCnt |
| └ valid_num | Number |  | validNum |
| └ relation_id | String | 2323423 | 渠道关系id |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.newuser.order.sum', {
	'page_size':'20',
	'adzone_id':'123',
	'page_no':'1',
	'site_id':'123',
	'activity_id':'sxxx',
	'settle_month':'201807'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_newuser_order_sum_response":{
        "results":{
            "data":{
                "page_no":1,
                "page_size":20,
                "has_next":true,
                "results":{
                    "data":[
                        {
                            "activity_id":"dddxx",
                            "biz_date":"20180321",
                            "reg_user_cnt":100,
                            "login_user_cnt":99,
                            "alipay_user_cnt":88,
                            "rcv_valid_user_cnt":66,
                            "rcv_user_cnt":77,
                            "alipay_user_cpa_pre_amt":"44.33",
                            "bind_buy_user_cpa_pre_amt":"33.22",
                            "bind_buy_valid_user_cnt":55,
                            "bind_card_valid_user_cnt":,
                            "re_buy_valid_user_cnt":,
                            "valid_num":,
                            "relation_id":"2323423"
                        }
                    ]
                }
            }
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isp.tbkapi-service-unavailable | 淘宝客API服务不可用 | 请稍后重试 |
| isv.invalid-parameter:start_price | 参数填写不正确 | 参数填写不正确 |
| isv.invalid-parameter:end_price | 参数填写不正确 | 参数填写不正确 |
| isv.invalid-parameter:end_tk_rate | 参数填写不正确 | 参数填写不正确 |
| 4 | 查询不到对应的adzoneId | 请检查adzoneId是否正确 |
| 2 | pid不正确 | 请检查是否输入了正确的adzoneId和siteId |

---
##taobao.tbk.relation.refund（淘宝客-推广者-售后退款订单查询）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| search_option | TopApiRefundRptOption | 必须 |  |  | 参数option |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result | RpcResult |  | 返回结果封装对象 |
| └ result_msg | String |  | 返回信息 |
| └ data | PageResult |  | 真正的业务数据结构 |
| └ page_no | String |  | pageNo |
| └ page_size | String |  | pageSize |
| └ total_count | String |  | 总值 |
| └ results | Result

                                 [] |  | 订单列表 |
| └ tb_trade_parent_id | Number |  | 淘宝订单编号 |
| └ special_id | Number |  | 会员关系id |
| └ relation_id | Number |  | 渠道关系id |
| └ tk3rd_pub_id | Number |  | 第三方推广者memberid |
| └ tk_pub_id | Number |  | 推广者memberid |
| └ tk_subsidy_fee_refund3rd_pub | String |  | 第三方应该返还的补贴 |
| └ tk_commission_fee_refund3rd_pub | String |  | 第三方应该返还的佣金 |
| └ tk_subsidy_fee_refund_pub | String |  | 第二方应该返还的补贴(不包括技术服务费) |
| └ tk_commission_fee_refund_pub | String |  | 第二方应该返还的佣金(不包括技术服务费) |
| └ tk_refund_suit_time | Date |  | 维权完成时间 |
| └ tk_refund_time | Date |  | 维权创建时间 |
| └ earning_time | Date |  | 订单结算时间 |
| └ tb_trade_create_time | Date |  | 订单创建时间 |
| └ refund_status | Number |  | 维权创建(淘客结算回执) 4,维权成功(淘客结算回执) 2,维权失败(淘客结算回执) 3,发生多次维权，待处理      11,从淘客处补扣（钱已结给淘客） 等待扣款 12,从淘客处补扣（钱已结给淘客） 扣款成功 13,从卖家处补扣（钱已结给卖家） 等待扣款 14,从卖家处补扣（钱已结给卖家） 扣款成功 15 |
| └ tb_auction_title | String |  | 宝贝标题 |
| └ tb_trade_id | Number |  | 淘宝子订单编号 |
| └ refund_fee | String |  | 维权金额 |
| └ tb_trade_finish_price | String |  | 结算金额 |
| └ tk_pub_show_return_fee | String |  | 应返商家金额(二方) |
| └ tk3rd_pub_show_return_fee | String |  | 应返商家金额(三方) |
| └ refund_type | Number |  | 1 表示2方，2表示3方 |
| └ alsc_pid | String |  | （口碑订单）口碑父订单号 |
| └ alsc_id | String |  | （口碑订单）口碑子订单号 |
| └ modified_time | Date |  | 更新时间 |
| └ result_code | Number |  | 接口返回值信息，跟rpc架构保持一致 |
| └ biz_error_desc | String |  | 业务错误信息 |
| └ biz_error_code | Number |  | 业务错误码 101, 102,103 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.relation.refund', {
	'search_option':'数据结构JSON示例'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_relation_refund_response":{
        "result":{
            "result_msg":"",
            "data":{
                "page_no":"",
                "page_size":"",
                "total_count":"",
                "results":{
                    "result":[
                        {
                            "tb_trade_parent_id":,
                            "special_id":,
                            "relation_id":,
                            "tk3rd_pub_id":,
                            "tk_pub_id":,
                            "tk_subsidy_fee_refund3rd_pub":"",
                            "tk_commission_fee_refund3rd_pub":"",
                            "tk_subsidy_fee_refund_pub":"",
                            "tk_commission_fee_refund_pub":"",
                            "tk_refund_suit_time":"",
                            "tk_refund_time":"",
                            "earning_time":"",
                            "tb_trade_create_time":"",
                            "refund_status":,
                            "tb_auction_title":"",
                            "tb_trade_id":,
                            "refund_fee":"",
                            "tb_trade_finish_price":"",
                            "tk_pub_show_return_fee":"",
                            "tk3rd_pub_show_return_fee":"",
                            "refund_type":,
                            "alsc_pid":"",
                            "alsc_id":"",
                            "modified_time":""
                        }
                    ]
                }
            },
            "result_code":,
            "biz_error_desc":"",
            "biz_error_code":
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.vegas.tlj.create（淘宝客-推广者-淘礼金创建）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| security_level | Number | 可选 | 0 |  | 必须传入0 |
| use_start_time | String | 可选 | 2019-01-29 |  | 使用开始日期。相对时间，无需填写，以用户领取时间作为使用开始时间。绝对时间，格式 yyyy-MM-dd，例如，2019-01-29，表示从2019-01-29 00:00:00 开始,格式 yyyy-MM-dd HH:mm:ss，例如，2019-01-29 20:00:10，表示从2019-01-2920:00:10 开始 |
| use_end_time_mode | Number | 可选 | 1 |  | 结束日期的模式,1:相对时间，2:绝对时间 |
| use_end_time | String | 可选 | 5 |  | 使用结束日期。如果是结束时间模式为相对时间，时间格式为1-7直接的整数, 例如，1（相对领取时间1天）； 如果是绝对时间，格式为yyyy-MM-dd，例如，2019-01-29，表示到2019-01-29 23:59:59结束,格式 yyyy-MM-dd HH:mm:ss，例如，2019-01-29 20:00:10，表示从2019-01-29 20:00:10 开始 |
| send_end_time | Date | 可选 | 2018-09-01 00:00:00 |  | 发放截止时间 |
| send_start_time | Date | 必须 | 2018-09-01 00:00:00 |  | 发放开始时间 |
| per_face | String | 必须 | 10 |  | 单个淘礼金面额，支持两位小数，单位元 |
| security_switch | Boolean | 必须 | true |  | 必须设置为true，默认开启安全 |
| user_total_win_num_limit | Number | 必须 | 1 |  | 单用户累计中奖次数上限 |
| name | String | 必须 | 淘礼金来啦 |  | 淘礼金名称，最大10个字符 |
| total_num | Number | 必须 | 10 |  | 淘礼金总个数 |
| item_id | String | 必须 | 12323 |  | 宝贝ID或营销ID |
| campaign_type | String | 可选 | MKT |  | 已下线，后续不需要填写 |
| use_threshold | String | 可选 | 2 |  | 淘礼金使用门槛，实付款大于等于门槛面额时才可使用此淘礼金；门槛值不能小于淘礼金面额 |
| award_img_template_id | String | 可选 | 1 |  | 淘礼金皮肤模版ID，1、日常模板（长期可用） 2、弹窗模板（长期可用） 3、近期大促活动模版 |
| adzone_id | Number | 必须 | 1234567 |  | 妈妈广告位Id |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result | Result |  | result |
| └ model | RightsInstanceCreateResult | 134523^4351232 | model |
| └ rights_id | String | asfasdfasd | 淘礼金Id |
| └ send_url | String | https://www.taobao.com | 淘礼金领取Url |
| └ vegas_code | String | asfasdfasd | 投放code【百川商品详情页业务专用】 |
| └ available_fee | String | 20.23 | 创建完成后资金账户可用资金，单位元，保留2位小数 |
| └ item_today_num_left | Number | 10 | 媒体针对此商品今日剩余可领取淘礼金数量 |
| └ msg_code | String | 1 | msgCode |
| └ msg_info | String | 1 | msgInfo |
| └ success | Boolean | false | success |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.vegas.tlj.create', {
	'security_level':'0',
	'use_start_time':'2019-01-29',
	'use_end_time_mode':'1',
	'use_end_time':'5',
	'send_end_time':'2018-09-01 00:00:00',
	'send_start_time':'2018-09-01 00:00:00',
	'per_face':'10',
	'security_switch':'true',
	'user_total_win_num_limit':'1',
	'name':'淘礼金来啦',
	'total_num':'10',
	'item_id':'12323',
	'campaign_type':'MKT',
	'use_threshold':'2',
	'award_img_template_id':'1',
	'adzone_id':'1234567'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_vegas_tlj_create_response":{
        "result":{
            "model":{
                "rights_id":"asfasdfasd",
                "send_url":"https:\/\/www.taobao.com",
                "vegas_code":"asfasdfasd",
                "available_fee":"20.23",
                "item_today_num_left":10
            },
            "msg_code":"1",
            "msg_info":"1",
            "success":false
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isp.vegas-server-unavailable | 服务不可用 | 请重新调用接口创建 |
| isp.call-limited | 调用限流 | 请重新调用接口进行创建 |
| isv.FAIL_BIZ_HAS_NO_PRIVILEGE | 暂无淘礼金创建权限 | 暂无淘礼金创建权限，请先申请，详见：https://mo.re.taobao.com/page_201905042138222 |
| isv.FAIL_BIZ_VIOLATION_POINT_EXCEED | 您的账号因权限异常已被停用，请联系客服申诉 | 您的账号因权限异常已被停用，请联系客服申诉 |
| isv.FAIL_BIZ_ITEM_FORBIDDEN | 该商品不支持创建淘礼金红包，了解详细规则：https://mo.re.taobao.com/page_201905042138222 | 该商品不支持创建淘礼金红包，了解详细规则：https://mo.re.taobao.com/page_201905042138222 |
| isv.FAIL_BIZ_NOT_TK_ITEM | 该商品为非淘客宝贝，不支持创建淘礼金红包 | 该商品为非淘客宝贝，不支持创建淘礼金红包 |
| isv.FAIL_CHECK_DAILY_SEND_AMOUNT_EXCEED | 超过每日发放限额 | 超过每日发放限额，请去淘宝联盟APP玩法钱包自助调整 |
| isv.FAIL_CHECK_MEMBER_DAILY_SEND_ITEM_ABOVE_LIMIT_ERROR | 今日商品创建数已超上限，请您明日再试 | 今日商品创建数已超上限，请您明日再试 |
| isv.FAIL_CHECK_MEMBER_ITEM_DAILY_SEND_TLJ_ABOVE_LIMIT_ERROR | 今日淘礼金红包创建数已超上限，请您明日再试 | 今日淘礼金红包创建数已超上限，请您明日再试 |
| isv.FAIL_CHECK_SELLER_CREATE_ITEM_NUM_RULE_ERROR | 您对该商家商品的淘礼金创建数已超上限，请选择其他商品创建 | 您对该商家商品的淘礼金创建数已超上限，请选择其他商品创建 |
| isv.FAIL_CHECK_MEMBER_CREATE_ITEM_NUM_CHECK_ERROR | 该商品淘礼金创建数已超上限，请选择其他商品创建 | 该商品淘礼金创建数已超上限，请选择其他商品创建 |
| isv.FAIL_CHECK_SELLER_DAILY_CREATE_NUM_ABOVE_LIMIT_ERROR | 今日该商家商品淘礼金创建数已超上限，请您明日再试 | 今日该商家商品淘礼金创建数已超上限，请您明日再试 |
| isv.FAIL_CHECK_TLJ_MIN_FACE_ERROR | 单个红包面额必须大于等于1元 | 单个红包面额必须大于等于1元 |
| isv.FAIL_BIZ_ASSET_ACCOUNT_NOT_EXISTS | 您的淘礼金账户暂未创建，请前往资金管理页面充值 | 您的淘礼金账户暂未创建，请前往资金管理页面充值 |
| isv.FAIL_BIZ_ACCOUNT_UN_PAID | 您的淘礼金账户暂未创建，请前往资金管理页面充值 | 您的淘礼金账户暂未创建，请前往资金管理页面充值 |
| isv.ASSET_ACCOUNT_BALANCE_NOT_ENOUGH | 账户预算不足，请充值后重新创建 | 账户预算不足，请充值后重新创建 |
| isv.FAIL_BIZ_PARAMS_ERROR | 参数错误，请确认配置信息正确性 | 参数错误，请确认配置信息正确性 |
| isv.FAIL_BIZ_CREATE_FORBIDDEN | 暂未开放淘礼金创建接口 | 暂未开放淘礼金创建接口 |
| isv.FAIL_BIZ_EXTERNAL_SERVICE_EXCEPTION | 创建淘礼金红包失败，请重新调用接口进行创建 | 创建淘礼金红包失败，请重新调用接口进行创建 |
| isv.FAIL_BIZ_SYSTEM_ERROR | 创建淘礼金红包失败，请重新调用接口进行创建 | 创建淘礼金红包失败，请重新调用接口进行创建 |
| isp.ACK_FREEZE_ASSET_ACCOUNT_ERROR | 创建淘礼金红包失败，请重新调用接口进行创建 | 创建淘礼金红包失败，请重新调用接口进行创建 |
| isv.FAIL_CHECK_ITEM_DAILY_SEND_NUM_CHECK_ERROR | 今日该商品淘礼金创建数已超上限，请您明日再试 | 今日该商品淘礼金创建数已超上限，请您明日再试 |
| isv.PARAM_IS_EMPTY | PARAM_IS_EMPTY | 参数不能为空 |
| isv.FAIL_BIZ_SERVICE_TIMEOUT | FAIL_BIZ_SERVICE_TIMEOUT | 系统异常，请稍后重试 |
| isv.MEMBER_DAILY_DRAW_ITEM_ABOVE_LIMIT | MEMBER_DAILY_DRAW_ITEM_ABOVE_LIMIT | 该商品单账号领取已达上限，请明日进行创建 |
| isv.SELLER_DAILY_DRAW_ITEM_ABOVE_LIMIT | SELLER_DAILY_DRAW_ITEM_ABOVE_LIMIT | 该商品所属商家今日领取已达上限，请明日进行创建 |
| isv.DAILY_DRAW_ITEM_ABOVE_LIMIT | DAILY_DRAW_ITEM_ABOVE_LIMIT | 该商品今日已达上限，请更换商品创建 |
| isv.CREATE_INSTANCE_ERROR | CREATE_INSTANCE_ERROR | 创建错误, 请稍后重试 |
| isv.ACK_FREEZE_FAIL | ACK_FREEZE_FAIL | 确认冻结失败 |
| isv.NAME_LENGTH_EXCEED | NAME_LENGTH_EXCEED | 红包名称长度必须小于等于10个字符 |
| isv.SEND_DATE_TIME_LIMIT | SEND_DATE_TIME_LIMIT | 发放有效期大于30天，请重新设置 |
| isv.TOTAL_NUM_BELOW_LIMIT | TOTAL_NUM_BELOW_LIMIT | 红包总个数必须大于等于1 |
| isv.USER_TOTAL_WIN_NUM_LIMIT | USER_TOTAL_WIN_NUM_LIMIT | 单用户领取上限最低为1，请重新设置 |
| isv.USER_TOTAL_WIN_NUM_LIMIT_BELOW_TOTAL_NUM | USER_TOTAL_WIN_NUM_LIMIT_BELOW_TOTAL_NUM | 单用户领取上限大于淘礼金个数，请重新设置 |
| isv.ACCOUNT_STATUS_INVALID | ACCOUNT_STATUS_INVALID | 玩法钱包账户状态异常 |
| isv.invalid-argument | invalid-argument | 参数错误，请修改后重新创建 |
| isv.SHIELD_ACCESS_RELATION_ERROR | 您的关联账号存在严重违规行为，无法开通淘礼金权限 | 您的关联账号存在严重违规行为，无法开通淘礼金权限 |
| isv.SHIELD_ACCESS_SELF_ERROR | 您的账号累计扣分大于等于18分，无法开通淘礼金权限，请您核实账号处罚信息后再次申请 | 您的账号累计扣分大于等于18分，无法开通淘礼金权限，请您核实账号处罚信息后再次申请 |
| -4003 | 您输入的商品ID不合法，请使用升级后的新商品ID，如有疑问请加入【淘宝联盟】线上合规升级咨询群（钉钉群：44965410）进行咨询 | 您输入的商品ID不合法，请使用升级后的新商品ID，如有疑问请加入【淘宝联盟】线上合规升级咨询群（钉钉群：44965410）进行咨询 |

---
##taobao.tbk.dg.punish.order.get（淘宝客-推广者-处罚订单查询）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| af_order_option | TopApiAfOrderOption | 可选 |  |  | 入参的对象 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result | RpcResult |  | 查询的对象 |
| └ data | PageResult |  | 结果 |
| └ results | Result

                                 [] |  | 处罚订单列表 |
| └ union_id | String |  | 淘宝联盟unionid（该字段不再支持） |
| └ special_id | Number |  | 会员运营id（该字段不再支持） |
| └ relation_id | Number | 122344 | 渠道关系id |
| └ settle_month | Number | 201812 | 结算月份 |
| └ punish_status | String | 0 | 处罚状态。0 冻结，1 解冻 |
| └ violation_type | String | 店铺淘宝客 | 处罚类型，目前包括 1.店铺淘宝客 2.订单虚假交易 |
| └ tk_trade_create_time | String | 2018-11-11 00:01:01 | 淘客订单创建时间 |
| └ tb_trade_id | Number | 581552321112183166 | 子订单号 |
| └ tb_trade_parent_id | Number |  | 父订单号（该字段不再支持） |
| └ tk_adzone_id | Number | 1212 | pid里的adzoneid |
| └ tk_site_id | Number | 1212 | pid里的siteid |
| └ tk_pub_id | String | 114469792 | pid里的pubid |
| └ page_no | Number | 1 | 翻页的pageno |
| └ page_size | Number | 10 | 翻页的pagesie |
| └ total_count | Number | 100 | 一共能查询出来的结果总数 |
| └ biz_error_desc | String | 没有获取到memberid | 业务出错的描述 |
| └ biz_error_code | Number | 103 | 业务出错的状态码 |
| └ result_msg | String | ok | 执行结果 |
| └ result_code | Number | 200 | 执行结果状态码 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.punish.order.get', {
	'af_order_option':'数据结构JSON示例'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_punish_order_get_response":{
        "result":{
            "data":{
                "results":{
                    "result":[
                        {
                            "union_id":"",
                            "special_id":,
                            "relation_id":122344,
                            "settle_month":201812,
                            "punish_status":"0",
                            "violation_type":"店铺淘宝客",
                            "tk_trade_create_time":"2018-11-11 00:01:01",
                            "tb_trade_id":581552321112183166,
                            "tb_trade_parent_id":,
                            "tk_adzone_id":1212,
                            "tk_site_id":1212,
                            "tk_pub_id":"114469792"
                        }
                    ]
                },
                "page_no":1,
                "page_size":10,
                "total_count":100
            },
            "biz_error_desc":"没有获取到memberid",
            "biz_error_code":103,
            "result_msg":"ok",
            "result_code":200
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.content.recommend.material.get（淘宝客-推广者-图文智能识别消费者端推荐物料查询）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| page_size | Number | 可选 | 20 | 默认值：20 | 页大小，默认20，1~100 |
| page_num | Number | 可选 | 1 | 默认值：1 | 第几页，默认：1 |
| adzone_id | Number | 必须 | 123 |  | mm_xxx_xxx_xxx的第三位 |
| content_id | String | 必须 | uc_xxxxx |  | 媒体内容id |
| sub_pid | String | 必须 | mm_123_456_789 |  | 达人subPid |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result_list | MapData [] |  | resultList |
| └ coupon_amount | Number | 40 | 优惠券信息-优惠券面额。如：满299元减20元 |
| └ shop_title | String | 魔黛娅内衣旗舰店 | 店铺信息-店铺名称 |
| └ coupon_start_fee | String | 69 | 优惠券信息-优惠券起用门槛，满X元可用。如：满299元减20元 |
| └ coupon_total_count | Number | 30000 | 优惠券信息-优惠券总量 |
| └ user_type | Number | 1 | 店铺信息-卖家类型，0表示集市，1表示商城 |
| └ zk_final_price | String | 79.9 | 商品信息-商品折扣价格 |
| └ coupon_start_time | String | 2017-10-29 | 优惠券信息-优惠券开始时间 |
| └ title | String | 毛呢阔腿裤港味复古女裤子秋冬九分裤萝卜裤显瘦高腰韩版2017新款 | 商品信息-商品标题 |
| └ volume | Number | 3837 | 商品信息-30天销量 |
| └ coupon_end_time | String | 2017-11-02 | 优惠券信息-优惠券结束时间 |
| └ coupon_share_url | String | //uland.taobao.com/coupon/edetail?e=pR6YtnFKK%2B8GQASttHIRqcEWOmlidB03Pf45HLyCqA8dRAklSM5tEQ36hBQToU3M3MmLjFwLsqgZxcV7BPtHQDd2Naqom0e0 | 券二合一链接 |
| └ pict_url | String | //img.alicdn.com/bao/uploaded/i4/745957850/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg | 商品信息-商品主图 |
| └ click_url | String | //s.click.taobao.com/t?e=m%3D2%26s%3DuHk3LsWO7NRw4vFB6t2Z2ueEDrYVVa64LKpWJ%2Bin0XLjf2vlNIV67hKx4R7cy6GL2Y%2Bdtp35Zpq%2Fr1EKiEQwcsUNmoA4ubwK0p%2BZKPXjvjsNBTdchAjpbDIrMad9IKIuzw0S7DwV9C24%2FApvI96NZlS1tdX9DLjzjHH9b9takmD%2BC6IBjof6lq%2BA9WMYINZ7YXh4NEyNHJkPWp8sFi3N5j7lCjCC8ck8 | 链接-宝贝推广链接 |
| └ orig_price | String | 20 | 原价 |
| └ nick | String | 秉迪数码专营店 | 店铺信息-卖家昵称 |
| └ source_from | String | http://XXX | 商品推荐图片来源 |
| └ encrypt_item_id | String | xxxx | 加密后的itemId |
| total_results | Number | 30 | 通过审核的推荐商品总数 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.content.recommend.material.get', {
	'page_size':'20',
	'page_num':'1',
	'adzone_id':'123',
	'content_id':'uc_xxxxx',
	'sub_pid':'mm_123_456_789'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_content_recommend_material_get_response":{
        "result_list":{
            "map_data":[
                {
                    "coupon_amount":40,
                    "shop_title":"魔黛娅内衣旗舰店",
                    "coupon_start_fee":"69",
                    "coupon_total_count":30000,
                    "user_type":1,
                    "zk_final_price":"79.9",
                    "coupon_start_time":"2017-10-29",
                    "title":"毛呢阔腿裤港味复古女裤子秋冬九分裤萝卜裤显瘦高腰韩版2017新款",
                    "volume":3837,
                    "coupon_end_time":"2017-11-02",
                    "coupon_share_url":"\/\/uland.taobao.com\/coupon\/edetail?e=pR6YtnFKK%2B8GQASttHIRqcEWOmlidB03Pf45HLyCqA8dRAklSM5tEQ36hBQToU3M3MmLjFwLsqgZxcV7BPtHQDd2Naqom0e0",
                    "pict_url":"\/\/img.alicdn.com\/bao\/uploaded\/i4\/745957850\/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg",
                    "click_url":"\/\/s.click.taobao.com\/t?e=m%3D2%26s%3DuHk3LsWO7NRw4vFB6t2Z2ueEDrYVVa64LKpWJ%2Bin0XLjf2vlNIV67hKx4R7cy6GL2Y%2Bdtp35Zpq%2Fr1EKiEQwcsUNmoA4ubwK0p%2BZKPXjvjsNBTdchAjpbDIrMad9IKIuzw0S7DwV9C24%2FApvI96NZlS1tdX9DLjzjHH9b9takmD%2BC6IBjof6lq%2BA9WMYINZ7YXh4NEyNHJkPWp8sFi3N5j7lCjCC8ck8",
                    "orig_price":"20",
                    "nick":"秉迪数码专营店",
                    "source_from":"http:\/\/XXX",
                    "encrypt_item_id":"xxxx"
                }
            ]
        },
        "total_results":30
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.content.daren.material.upload（淘宝客-推广者-图文智能识别达人端物料上传）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| adzone_id | Number | 必须 | 789 |  | adzoneId，mm_123_456_789的第三段 |
| keywords | String | 可选 | 女装,连衣裙 |  | 内容关键词，多个英文逗号分隔，最多支持8个，中文统一用utf-8编码方式 |
| keywords_weight | String | 可选 | 0.2,0.4 |  | 关键词对应的权重，英文逗号分隔 |
| content_label | String | 可选 | 科技 |  | 内容标签，多个用英文逗号分隔，中文统一用utf-8编码方式 |
| content_detail | String | 可选 | xxxx |  | 文章内容详情，统一用utf-8编码方式 |
| content_link | String | 必须 | http://XXXx |  | 文章链接 |
| content_id | String | 必须 | uc_xxxxx |  | 内容id |
| sub_pid | String | 必须 | mm_123_0_0 |  | 达人pid |
| picture_url | String

        						[] | 必须 | ["123", "456"] | 最大列表长度：20 | 图片url列表，最多支持取前6张图片。图片建议：大小在150KB以内，分辨率在600*600以内，格式限制 jpg,png,bmp,gif。 |
| picture_label | String

        						[] | 可选 | ["科技", "数码"] | 最大列表长度：20 | 图片url对应的标签，必须统一用utf-8编码 |
| content_title | String | 可选 | 文章标题 |  | 文章标题，统一用utf-8编码 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result_list | MapData [] |  | resultList，只取第一个元素 |
| └ ret_code | Number | 1000 | 物料上传状态码，1000物料上传成功，其他错误码参考说明 |
| └ ret_desc | String | 内容物料上传成功,异步处理中 | 返回状态码说明 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.content.daren.material.upload', {
	'adzone_id':'789',
	'keywords':'女装,连衣裙',
	'keywords_weight':'0.2,0.4',
	'content_label':'科技',
	'content_detail':'xxxx',
	'content_link':'http://XXXx',
	'content_id':'uc_xxxxx',
	'sub_pid':'mm_123_0_0',
	'picture_url':'"123", "456"',
	'picture_label':'"科技", "数码"',
	'content_title':'文章标题'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_content_daren_material_upload_response":{
        "result_list":{
            "map_data":[
                {
                    "ret_code":1000,
                    "ret_desc":"内容物料上传成功,异步处理中"
                }
            ]
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.order.details.get（淘宝客-推广者-所有订单查询）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| query_type | Number | 可选 | 1 | 默认值：1 | 查询时间类型，1：按照订单淘客创建时间查询，2:按照订单淘客付款时间查询，3:按照订单淘客结算时间查询，4:按照订单更新时间； |
| position_index | String | 可选 | 2222_334666 |  | 位点，除第一页之外，都需要传递；前端原样返回。 |
| page_size | Number | 可选 | 20 | 默认值：20 | 页大小，默认20，1~100 |
| member_type | Number | 可选 | 2 |  | 推广者角色类型,2:二方，3:三方，不传，表示所有角色 |
| tk_status | Number | 可选 | 12 |  | 淘客订单状态，11-拍下未付款，12-付款，13-关闭，14-确认收货，3-结算成功;不传，表示所有状态 |
| end_time | String | 必须 | 2019-04-23 12:28:22 |  | 订单查询结束时间，订单开始时间至订单结束时间，中间时间段日常要求不超过3个小时，但如618、双11、年货节等大促期间预估时间段不可超过20分钟，超过会提示错误，调用时请务必注意时间段的选择，以保证亲能正常调用！ |
| start_time | String | 必须 | 2019-04-05 12:18:22 |  | 订单查询开始时间 |
| jump_type | Number | 可选 | 1 | 默认值：1 | 跳转类型，当向前或者向后翻页必须提供,-1: 向前翻页,1：向后翻页 |
| page_no | Number | 可选 | 1 | 默认值：1 | 第几页，默认1，1~100 |
| order_scene | Number | 可选 | 1 | 默认值：1 | 筛选订单类型，1:所有订单，2:渠道订单，3:会员运营订单，默认为1 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | OrderPage | OrderPage | PublisherOrderDto |
| └ results | PublisherOrderDto

                                 [] | PublisherOrderDto | PublisherOrderDto |
| └ tb_paid_time | String | 2019-04-22 15:15:05 | 淘宝付款时间。解释：订单在淘宝付款的时间 |
| └ tk_paid_time | String | 2019-04-22 15:15:05 | 付款时间。解释：订单付款的时间，该时间同步淘宝，可能会略晚于买家在淘宝的订单付款时间  （预售订单完尾款支付后，付款时间会自动更新为尾款支付的时间） |
| └ pay_price | String | 9.11 | 结算金额。解释：买家确认收货的付款金额（不包含运费金额） |
| └ pub_share_fee | String | 0 | 结算预估收入。解释：结算预付收入=结算预估佣金收入+结算预估补贴收入 |
| └ trade_id | String | 294159887445064307 | 子订单号。解释：买家通过购物车购买的每个商品对应的订单编号，此订单编号并未在淘宝买家后台透出，若平台类型为淘宝、口碑、饿了么等，则订单编号即为淘宝子订单编号、口碑订单编号、饿了么订单编号，以此类推 |
| └ tk_order_role | Number | 2 | 推广者身份。解释：二方：佣金收益的第一归属者；三方：从其他淘宝客佣金中进行分成的推广者 |
| └ tk_earning_time | String | 2019-04-22 15:15:05 | 结算时间。解释：订单确认收货后且商家完成佣金支付的时间 |
| └ adzone_id | Number | 111112234455 | 推广位ID。解释：“推广管理-推广位管理”中的pid中的最后一段数字，如pid=mm_1_2_3中的“3”这段数字 |
| └ pub_share_rate | String | 100 | 佣金分成比率。解释：从佣金中分得的收益比率（含平台技术服务费比率） |
| └ unid | String | 11 | unid（不对外开放） |
| └ refund_tag | Number | 0 | 维权标签。解释：若该订单产生了维权退款，则会打上“维权单”的提示。0 含义为非维权、1 含义为维权订单 |
| └ subsidy_rate | String | 0 | 补贴比率。解释：指该笔订单上各类型补贴的补贴比率总和。补贴比率=a补贴比率+b补贴比率+…。举例：天猫补贴1%、飞猪补贴1%等，则该数值显示为2% |
| └ tk_total_rate | String | 9.99 | 佣金提成。解释：佣金提成=佣金比率*佣金分成比率。指实际获得的佣金收益比率（含平台技术服务费） |
| └ item_category_name | String | 服装 | 类目名称。解释：商品所属的一级类目名称 |
| └ seller_nick | String | -- | 掌柜旺旺 |
| └ pub_id | Number | 98836808 | 推广者的账号id |
| └ alimama_rate | String | 0 | 平台技术服务费比率。解释：指该笔订单推广者在需支付给淘宝联盟的所有技术服务费比率总和。平台技术服务费比率=技术服务费比率a+技术服务费比率b+…。（特别说明：补贴从2023-03-10之后都不再收取补贴技术服务费了，故本字段公式中不再提及补贴相关) |
| └ subsidy_type | String | -- | 补贴类型。解释：各补贴类型的类型名称、补贴比率、补贴金额、单笔补贴上限、补贴分成比率的详细说明，如有多个补贴会一并告知，举例：淘宝特价版（补贴比率：1%，补贴金额1.00元，单笔补贴上限金额1000.00元，补贴分成比率：100.00%）、飞猪补贴（补贴比率：1%，补贴金额1.00元，单笔补贴上限金额1000.00元，补贴分成比率：100.00%） |
| └ item_img | String | //img.alicdn.com/bao/uploaded/i1/2200782262419/O1CN01b5qlop1TjwarUo8fo_!!2200782262419.jpg | 商品图片 |
| └ pub_share_pre_fee | String | 0 | 付款预估收入。解释：付款预付收入=付款预估佣金收入+付款预估补贴收入 |
| └ alipay_total_price | String | 11.22 | 付款金额。解释：买家拍下并付款金额（含预售订单定金金额，但不包含运费金额）；当预售订单完成尾款支付后，付款金额会自动更新为订单总金额 |
| └ item_title | String | tsh_rj_测试请不要拍_阶佣11.1 | 商品标题 |
| └ site_name | String | 合伙人 | 媒体名称。解释：“推广管理-媒体备案管理”中的媒体名称 |
| └ item_num | Number | 2 | 商品数量 |
| └ subsidy_fee | String | 0 | 补贴金额。解释：指该笔订单上各类补贴的补贴金额总和。补贴金额=a补贴金额+b补贴金额+…=结算金额*a补贴比率+结算金额*b补贴比率+…。若（结算金额*a补贴比率）＞补贴类型a单笔补贴上限，则a补贴金额=补贴类型a单笔补贴上限，b补贴金额等其他补贴金额同理 |
| └ alimama_share_fee | String | 0 | 平台技术服务费。解释：指该笔订单推广者在需支付给淘宝联盟的所有技术服务费费用总和。目前包含以下两类： 1、技术服务费说明：通过淘宝联盟平台推广所需支付的基础技术服务费；2、渠道专项服务费说明：开通渠道管理权限的推广者进行推广需要支付给淘宝联盟的专项技术服务费用。           平台技术服务费=付款金额*佣金比率*平台技术服务费比率。注意：若订单已结算则会按结算金额计算。（特别说明：补贴从2023-03-10之后都不再收取补贴技术服务费了，故本字段公式中不再提及补贴相关) |
| └ trade_parent_id | String | 294159887445064307 | 订单编号。解释：买家在购买后台显示的订单编号，若平台类型为淘宝、饿了么等，则订单编号即为淘宝订单编号、饿了么订单编号，以此类推 |
| └ order_type | String | 如意淘 | 平台类型。解释：订单所属平台类型，包括天猫、淘宝、聚划算、口碑等 |
| └ tk_create_time | String | 2019-04-22 15:15:05 | 创建时间。解释：订单创建的时间，该时间同步淘宝，可能会略晚于买家在淘宝的订单创建时间 |
| └ flow_source | String | -- | 产品类型。解释：若订单属于特定的产品类型，会进行说明，举例：该订单属于“联盟超级活动”、“品牌精选推广”、“自主推广”等，若无说明仅为“--”则为普通类型订单 |
| └ terminal_type | String | 无线 | 成交平台。解释：成交来自于PC或无线 |
| └ click_time | String | 2019-04-22 15:14:55 | 点击时间。解释：通过推广链接达到商品、店铺详情页的点击时间 |
| └ tk_status | Number | 13 | 订单状态。状态类型：已付款（指订单已付款，但还未确认收货）、已收货（指订单已确认收货，但商家佣金未支付）、已结算（指订单已确认收货，且商家佣金已支付成功）、已失效（指订单关闭/订单佣金小于0.01元，订单关闭主要有：①买家超时未付款；②买家付款前，买家/商家取消了订单；③订单付款后发起售中退款成功；④仅支付定金，到期未支付尾款的预售订单）。注意：当订单商家有实收货款（含交易成功和交易关闭订单），联盟以商家实收货款进行佣金结算(满返/买返订单等特殊订单除外)。出参数字代表：3:订单结算，12:订单付款，13:订单失效，14:订单成功 |
| └ item_price | String | 2.1 | 商品单价 |
| └ item_id | String | 590141576510 | 商品id |
| └ adzone_name | String | 推广位名 | 推广位名称。解释：“推广管理-推广位管理”中的推广位名称 |
| └ total_commission_rate | String | 9.99 | 佣金比率。解释：商品的佣金比率（含平台技术服务费比率，但不包含平台专项服务费比率）（特别说明：若想知道属于您名下的整体佣金比率，则整体佣金比率=佣金比率+平台专项服务费比率，为了简化展示报表，不再增加整体佣金收入字段，有需要的淘宝客可自行加和，举例：若整体佣金比率为10%，平台专项服务费比率为3%，则此处商品佣金比率显示为7%，即10%-3%=7%） |
| └ item_link | String | https://www.taobao.com | 商品链接 |
| └ site_id | Number | 45598009 | 媒体ID。解释：“推广管理-媒体备案管理”中的媒体ID，也是pid中的第二段数字，如pid=mm_1_2_3中的“2”这段数字 |
| └ seller_shop_title | String | -- | 店铺名称 |
| └ income_rate | String | 9.99 | 收入比率。解释：收入比率=佣金比率+补贴比率 |
| └ total_commission_fee | String | 0 | 佣金金额。解释：如果该订单还未结算，则佣金金额=付款金额*佣金比率；如果该订单已经结算，则佣金金额=结算金额*佣金比率 |
| └ special_id | Number | 21321 | 会员运营ID。解释：会员运营管理功能中的会员运营ID，若该订单来自于会员的购买，则会展示对应会员运营ID |
| └ relation_id | Number | 123123 | 渠道关系id。解释：渠道管理功能中的渠道关系ID，若该订单来自于渠道方的推广，则会展示对应渠道关系ID |
| └ deposit_price | String | 22.32 | 定金付款金额。解释：预售时期，预售订单支付的定金金额 |
| └ tb_deposit_time | String | 2019-09-09 12:01:01 | 定金淘宝付款时间。解释：预售时期，预售订单在淘宝支付定金的付款时间 |
| └ tk_deposit_time | String | 2019-09-09 12:01:01 | 定金付款时间。解释：预售时期，预售订单支付定金的付款时间，该时间同步淘宝，可能会略晚于买家在淘宝的订单创建时间 |
| └ tp_order_id | String | 3434 | 非电商淘系子订单号 |
| └ service_fee_dto_list | ServiceFeeDTO

                                 [] | ServiceFeeDto | 服务费信息（字段已废弃） |
| └ tk_share_role_type | Number | 122 | 专项服务费来源，122-渠道（字段已废弃） |
| └ share_relative_rate | String | 0.10 | 专项服务费率（字段已废弃） |
| └ share_fee | String | 11.11 | 结算专项服务费（字段已废弃） |
| └ share_pre_fee | String | 11.11 | 预估专项服务费（字段已废弃） |
| └ item_category_level2_name | String | 类目名 | 类目名称。解释：商品所属的二级类目名称 |
| └ marketing_type | String | 营销类型 | 营销类型。解释：该字段中视订单情况有单个或多个类型告知。 举例：联盟超级活动-优品、特价版客户端锁粉、特价版客户端推广等 |
| └ modified_time | String | 2019-09-09 12:01:01 | 订单更新时间 |
| └ talent_pid | String | mm_123_234_424 | 专用（不对外开放） |
| └ tb_gmv_total_price | String | 22.32 | 买家拍下金额（不包含运费金额） |
| └ extra_mkt_id | String | 123ucbewri | 管理member新商品ID后段 |
| └ untts | String | 1111TTTTTOOOO | 流量通untts（默认无，限定开放） |
| └ pub_share_pre_fee_for_commission | BigDecimal | 0 | 付款预估佣金收入。解释：付款预估佣金收入=付款金额*佣金提成。以买家付款金额为基数，预估您可能获得的付款佣金收入，包含平台技术服务费金额（最终发钱时会减去平台技术服务费）。注意：因买家退款等原因，可能与结算预估佣金收入不一致。（特别说明：若想知道属于您名下的整体佣金收入，则整体付款佣金收入=付款预估佣金收入+平台专项服务费，为了简化展示报表，不再增加整体佣金收入字段，有需要的淘宝客可自行加和） |
| └ pub_share_fee_for_commission | BigDecimal | 0 | 结算预估佣金收入。解释：结算预估佣金收入=付款金额*佣金提成。以买家确认收货的付款金额为基数，预估您可能获得的结算佣金收入，包含技术服务费金额（最终发钱时会减去平台技术服务费）。注意：因买家退款、您违规推广等原因，可能与您最终收入不一致，最终收入以月结后您实际收到的为准。（特别说明：若想知道属于您名下的整体佣金收入，则整体结算佣金收入=结算预估佣金收入+平台专项服务费，为了简化展示报表，不再增加整体佣金收入字段，有需要的淘宝客可自行加和） |
| └ subsidy_info_dto_list | SubsidyDetailDTO

                                 [] | subsidyDetailDTOList | 补贴金额明细节点。解释：各补贴类型的类型名称、补贴比率、补贴金额、单笔补贴上限、补贴分成比率的详细说明 |
| └ subsidy_type | String | 妈妈补贴 | 该笔订单包含的补贴类型 |
| └ subsidy_rate | BigDecimal | 0 | 补贴比率 |
| └ subsidy_fee | BigDecimal | 0 | 对应补贴类型的补贴金额 |
| └ subsidy_upper_limit | BigDecimal | 0 | 单笔订单补贴上限。对应补贴类型的单笔订单补贴上限 |
| └ subsidy_share_rate | BigDecimal | 0 | 补贴分成比率 |
| └ pub_share_rate_for_sdy | BigDecimal | 0 | 补贴分成比率。解释：从补贴中分得的收益比率 |
| └ tk_total_rate_for_sdy | BigDecimal | 0 | 补贴提成。解释：补贴提成=补贴比率*补贴分成比率。指实际获得的补贴收益比率 |
| └ pub_share_pre_fee_for_sdy | BigDecimal | 0 | 付款预估补贴收入。解释：指以买家付款金额为基数，预估您可能获得的补贴收入。付款预估补贴收入=（付款金额*a补贴比率+付款金额*b补贴比率+……）*补贴分成比率。如果付款金额*a补贴比率＞补贴类型a单笔订单补贴上限，则付款金额*a补贴比率的值取补贴类型a单笔订单补贴上限，b补贴金额等其他类型补贴金额同理。注意：因买家退款等原因，可能与结算预估补贴收入不一致 |
| └ pub_share_fee_for_sdy | BigDecimal | 0 | 结算预估补贴收入。解释：以买家确认收货的付款金额为基数，预估您可能获得的结算补贴收入。结算预估补贴收入=（结算金额*a补贴比率+结算金额*b补贴比率+……）*补贴分成比率。如果结算金额*a补贴比率＞补贴类型a单笔订单补贴上限，则结算金额*a补贴比率的值取补贴类型a单笔订单补贴上限，b补贴金额等其他类型补贴金额同理。注意：因买家退款、您违规推广等原因，可能与您最终收入不一致，最终收入以月结后您实际收到的为准 |
| └ alimm_share_info_dto | AlimmShareInfoDTO |  | 平台技术服务费明细节点。解释：各项平台技术服务费类型的类型名称、扣费比率、扣费金额的详细说明 |
| └ alimm_tech_service_rate | BigDecimal | 0 | 技术服务费比率 |
| └ alimm_tech_service_pre_fee | BigDecimal | 0 | 预估技术服务费 |
| └ alimm_tech_service_fee | BigDecimal | 0 | 结算技术服务费 |
| └ alimm_agent_service_rate | BigDecimal | 0 | 渠道专项服务费比率 |
| └ alimm_agent_service_pre_fee | BigDecimal | 0 | 预估渠道专项服务费 |
| └ alimm_agent_service_fee | BigDecimal | 0 | 结算渠道专项服务费 |
| └ platform_special_service_rate | BigDecimal | 0 | 平台专项服务费比率。解释：指该笔订单推广者在各种特殊场景下需支付给淘宝联盟的所有专项服务费比率总和。平台专项服务费比率=专项服务费比率a+专项服务费比率b+… |
| └ platform_special_service_fee | BigDecimal | 0 | 平台专项服务费。解释：指该笔订单推广者在各种特殊场景下需支付给淘宝联盟的所有专项服务费用总和。目前包含以下两类：1、内容专项服务费说明：内容场景专项技术服务费，内容推广者在内容场景进行推广需要支付给淘宝联盟的专项技术服务费用；2、流量专项服务费说明：流量通产品合作场景专项技术服务费，推广者在流量通产品能力下，进行流量投放推广需要支付给淘宝联盟的专项技术服务费用。           平台专项服务费=付款金额*平台专项服务费比率。注意：若订单已结算则会按结算金额计算 |
| └ platform_special_share_info_dto | PlatformSpecialShareInfoDTO |  | 平台专项服务费明细节点。解释：各项平台专项服务费类型的类型名称、扣费比率、扣费金额的详细说明 |
| └ content_tech_service_rate | BigDecimal | 0 | 内容专项服务费比率 |
| └ content_tech_service_pre_fee | BigDecimal | 0 | 预估内容专项服务费 |
| └ content_tech_service_fee | BigDecimal | 0 | 结算内容专项服务费 |
| └ traffic_tech_service_rate | BigDecimal | 0 | 流量专项服务费比率（默认无，限定开放） |
| └ traffic_tech_service_pre_fee | BigDecimal | 0 | 预估流量专项服务费（默认无，限定开放） |
| └ traffic_tech_service_fee | BigDecimal | 0 | 结算流量专项服务费（默认无，限定开放） |
| └ uvid | String | 0 | 加密标识（默认不开放） |
| └ has_pre | Boolean | false | 是否还有上一页 |
| └ position_index | String | 1555904214_lGltNdNvSX2|1555917305_lJfPMeFmdt2 | 位点字段，由调用方原样传递 |
| └ has_next | Boolean | true | 是否还有下一页 |
| └ page_no | Number | 1 | 页码 |
| └ page_size | Number | 11 | 页大小 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.order.details.get', {
	'query_type':'1',
	'position_index':'2222_334666',
	'page_size':'20',
	'member_type':'2',
	'tk_status':'12',
	'end_time':'2019-04-23 12:28:22',
	'start_time':'2019-04-05 12:18:22',
	'jump_type':'1',
	'page_no':'1',
	'order_scene':'1'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_order_details_get_response":{
        "data":{
            "results":{
                "publisher_order_dto":[
                    {
                        "tb_paid_time":"2019-04-22 15:15:05",
                        "tk_paid_time":"2019-04-22 15:15:05",
                        "pay_price":"9.11",
                        "pub_share_fee":"0",
                        "trade_id":"294159887445064307",
                        "tk_order_role":2,
                        "tk_earning_time":"2019-04-22 15:15:05",
                        "adzone_id":111112234455,
                        "pub_share_rate":"100",
                        "unid":"11",
                        "refund_tag":0,
                        "subsidy_rate":"0",
                        "tk_total_rate":"9.99",
                        "item_category_name":"服装",
                        "seller_nick":"--",
                        "pub_id":98836808,
                        "alimama_rate":"0",
                        "subsidy_type":"--",
                        "item_img":"\/\/img.alicdn.com\/bao\/uploaded\/i1\/2200782262419\/O1CN01b5qlop1TjwarUo8fo_!!2200782262419.jpg",
                        "pub_share_pre_fee":"0",
                        "alipay_total_price":"11.22",
                        "item_title":"tsh_rj_测试请不要拍_阶佣11.1",
                        "site_name":"合伙人",
                        "item_num":2,
                        "subsidy_fee":"0",
                        "alimama_share_fee":"0",
                        "trade_parent_id":"294159887445064307",
                        "order_type":"如意淘",
                        "tk_create_time":"2019-04-22 15:15:05",
                        "flow_source":"--",
                        "terminal_type":"无线",
                        "click_time":"2019-04-22 15:14:55",
                        "tk_status":13,
                        "item_price":"2.1",
                        "item_id":"590141576510",
                        "adzone_name":"推广位名",
                        "total_commission_rate":"9.99",
                        "item_link":"https:\/\/www.taobao.com",
                        "site_id":45598009,
                        "seller_shop_title":"--",
                        "income_rate":"9.99",
                        "total_commission_fee":"0",
                        "special_id":21321,
                        "relation_id":123123,
                        "deposit_price":"22.32",
                        "tb_deposit_time":"2019-09-09 12:01:01",
                        "tk_deposit_time":"2019-09-09 12:01:01",
                        "tp_order_id":"3434",
                        "service_fee_dto_list":{
                            "service_fee_d_t_o":[
                                {
                                    "tk_share_role_type":122,
                                    "share_relative_rate":"0.10",
                                    "share_fee":"11.11",
                                    "share_pre_fee":"11.11"
                                }
                            ]
                        },
                        "marketing_type":"营销类型",
                        "modified_time":"2019-09-09 12:01:01",
                        "talent_pid":"mm_123_234_424",
                        "tb_gmv_total_price":"22.32",
                        "extra_mkt_id":"123ucbewri",
                        "untts":"1111TTTTTOOOO",
                        "pub_share_pre_fee_for_commission":"0",
                        "pub_share_fee_for_commission":"0",
                        "subsidy_info_dto_list":{
                            "subsidy_detail_d_t_o":[
                                {
                                    "subsidy_type":"妈妈补贴",
                                    "subsidy_rate":"0",
                                    "subsidy_fee":"0",
                                    "subsidy_upper_limit":"0",
                                    "subsidy_share_rate":"0"
                                }
                            ]
                        },
                        "pub_share_rate_for_sdy":"0",
                        "tk_total_rate_for_sdy":"0",
                        "pub_share_pre_fee_for_sdy":"0",
                        "pub_share_fee_for_sdy":"0",
                        "alimm_share_info_dto":{
                            "alimm_tech_service_rate":"0",
                            "alimm_tech_service_pre_fee":"0",
                            "alimm_tech_service_fee":"0",
                            "alimm_agent_service_rate":"0",
                            "alimm_agent_service_pre_fee":"0",
                            "alimm_agent_service_fee":"0"
                        },
                        "platform_special_service_rate":"0",
                        "platform_special_service_fee":"0",
                        "platform_special_share_info_dto":{
                            "content_tech_service_rate":"0",
                            "content_tech_service_pre_fee":"0",
                            "content_tech_service_fee":"0",
                            "traffic_tech_service_rate":"0",
                            "traffic_tech_service_pre_fee":"0",
                            "traffic_tech_service_fee":"0"
                        },
                        "uvid":"0"
                    }
                ]
            },
            "has_pre":false,
            "position_index":"1555904214_lGltNdNvSX2|1555917305_lJfPMeFmdt2",
            "has_next":true,
            "page_no":1,
            "page_size":11
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| 1008 | positionIndex非法 | positionIndex非法 |
| 3001 | 系统繁忙，请稍后重试！ | 系统繁忙，请稍后重试！ |
| 1006 | tkStatus非法 | 请检查tkStatus参数 |
| 1005 | jumpType非法 | 请检查jumpType参数 |
| 9100 | 您的账号因调用不符合要求，当前触发限流。为保障广大推广者正常使用系统，会有账号维度的限流机制：通过API、淘宝客PC后台、联盟APP或使用第三方工具获取数据，同账号会统一限流。同一个账号1秒总请求次数约200次，其中调用API约40次，超过或接近临界值，会触发限流 | 建议您逐一排查各个渠道的总调用量，降低调用频次。此外，在淘宝客PC后台_效果报表_推广者推广明细页面，注意事项第3条会有订单查询方式建议，违反建议也会触发限流。请按建议调整请求策略。 |
| 2004 | 请求参数非法 | 开始时间应该大于最近90天 |
| 2007 | 亲，订单查询时间段日常要求不超过3个小时，但如618、双11、年货节等大促期间预估时间段不可超过20分钟，超过会提示错误，调用时请务必注意时间段的选择，以保证亲能正常调用！ | 请用户缩短时间段，同时查看调用频次，若频次过高，可能会有爬虫风险 |
| 2000 | 开始时间或结束时间参数非法 | 请求参数非法，查看调用频次，若频次过高，可能会有爬虫风险 |
| 2001 | 开始时间应该小于结束时间 | 请求参数非法，查看调用频次，若频次过高，可能会有爬虫风险 |
| 1001 | 请求参数非法，rptOption为空 | 请求参数非法，查看调用频次，若频次过高，可能会有爬虫风险 |
| 2002 | 请求参数非法，开始时间应该小于当前时间 | 请求参数非法，查看调用频次，若频次过高，可能会有爬虫风险 |
| isp.pubrpt-service-unavailable | 服务不可用 | 请检查hsf服务是否正常 |
| 3000 | 您的账号因调用不符合要求，当前触发限流。建议您逐一排查各个渠道的总调用量，降低调用频次，次日后重新尝试，若仍然无法使用，可通过淘宝联盟网站/APP客服中心 联系客服咨询。 | 您的账号因调用不符合要求，当前触发限流。建议您逐一排查各个渠道的总调用量，降低调用频次，次日后重新尝试，若仍然无法使用，可通过淘宝联盟网站/APP客服中心 联系客服咨询。 |

---
##taobao.tbk.dg.reports.newquery（淘宝客-推广者-媒体数据报表交换）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| page_size | Number | 必须 | 100 |  | 每页大小 |
| page_no | Number | 必须 | 1 |  | 页码 |
| dimensions | String | 可选 | ds |  | 聚合条件 |
| filters | String | 必须 | ds=20191013;subpid=mm_123_132_321;pubId=1234;hasCount=false;position_index=123 |  | 查询条件 ds-日期;subpid-达人pid; pubId-媒体memberid; hasCount-是否返回总数，true表示返回，建议只请求一次数量，false不返回数量 可以提高接口效率；position_index位点信息，返回的数据中最小的id |
| return_fields | String | 可选 | id,pub_id,sub_pub_id,sub_site_id,sub_adzone_id,daren_id,content_id,tk_trade_create_time,click_timestamp,tb_auction_id,tb_auction_num,tb_auction_price,tb_trade_status,tk_trade_status,tb_trade_parent_id,tb_trade_id,tb_auction_category_level1,tb_auction_category,tb_auction_category_level1_name,tb_alipay_total_price,pre_3rd_pub_share_fee,tk_3rd_pub_share_fee,tk_commission_rate |  | 查询字段 |
| report_type_id | String | 必须 | union_media_newlink_subpid_order_detail |  | 订单明细传 union_media_newlink_subpid_order_detail |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data_list | MapData [] | map数组 | 结果列表 |
| └ click_id | String | 1234 | 点击id |
| └ tb_auction_category_level1_name | String | 女装 | 商品一级类目名称 |
| └ tb_trade_id | Number | 1234 | 子订单编号 |
| └ tb_trade_parent_id | Number | 1234 | 父订单编号 |
| └ tb_trade_status | Number | 1 | 订单状态(淘宝) |
| └ tb_auction_price | String | 1.0 | 商品单价 |
| └ tb_auction_num | Number | 10 | 商品数 |
| └ tb_auction_id | String | 1234 | 商品id |
| └ click_timestamp | String | 2019-01-01 00:00:00 | 订单点击时间 |
| └ tk_trade_create_time | String | 2019-01-01 00:00:00 | 订单创建时间 |
| └ click_uv | Number | 10 | 单篇内容UV_pub口径 |
| └ click_pv | Number | 10 | 单篇内容PV_pub口径 |
| └ tk_commission_rate | String | 0.5 | 预估佣金率 |
| └ pre_subsidy_fee | String | 1 | cps预估补贴 |
| └ pre_commission_fee | String | 1.5 | cps预估佣金 |
| └ cm_alipay_amt | String | 10 | cps成交金额 |
| └ cm_alipay_num | Number | 1 | cps成交笔数 |
| └ ds | String | 20190525 | 日期 |
| └ cm_3rd_pub_share_fee | String | 1.5 | 达人结算预估收入 |
| └ cm_pub_share_fee | String | 1.5 | 平台结算预估收入 |
| └ pre_3rd_pub_share_fee | String | 1.5 | 达人预估收入 |
| └ pre_pub_share_fee | String | 1.5 | 平台预估收入 |
| └ alipay_amt | String | 10 | 成交金额 |
| └ alipay_num | Number | 10 | 成交笔数 |
| └ zz_uv | Number | 100 | 主站口径uv |
| └ union_pv | Number | 100 | 联盟口径pv |
| └ biz_type | String | 1 | 业务类型 |
| └ sub_adzone_id | Number | 1234 | 达人adzoneid |
| └ sub_site_id | Number | 1234 | 达人siteid |
| └ sub_pub_id | Number | 1234 | 达人pubid |
| └ name | String | 1234 | 达人名称 |
| └ pub_id | Number | 1234 | 平台pud_id |
| └ tb_alipay_total_price | String | 10 | 订单支付金额 |
| └ tk_3rd_pub_share_fee | String | 1.5 | 达人结算预估收入 |
| report_type_id | String | union_channel_content_basic_v1 | 报表名称 |
| page_info | RptPageinfo | map | 分页信息 |
| └ total_cnt | Number | 20 | 总数 |
| └ page_no | Number | 1 | 页数 |
| └ page_size | Number | 100 | 每页大小 |
| position_index | String | 123 | 位点信息 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.reports.newquery', {
	'page_size':'100',
	'page_no':'1',
	'dimensions':'ds',
	'filters':'ds=20191013;subpid=mm_123_132_321;pubId=1234;hasCount=false;position_index=123',
	'return_fields':'id,pub_id,sub_pub_id,sub_site_id,sub_adzone_id,daren_id,content_id,tk_trade_create_time,click_timestamp,tb_auction_id,tb_auction_num,tb_auction_price,tb_trade_status,tk_trade_status,tb_trade_parent_id,tb_trade_id,tb_auction_category_level1,tb_auction_category,tb_auction_category_level1_name,tb_alipay_total_price,pre_3rd_pub_share_fee,tk_3rd_pub_share_fee,tk_commission_rate',
	'report_type_id':'union_media_newlink_subpid_order_detail'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_reports_newquery_response":{
        "data_list":{
            "map_data":[
                {
                    "click_id":"1234",
                    "tb_auction_category_level1_name":"女装",
                    "tb_trade_id":1234,
                    "tb_trade_parent_id":1234,
                    "tb_trade_status":1,
                    "tb_auction_price":"1.0",
                    "tb_auction_num":10,
                    "tb_auction_id":"1234",
                    "click_timestamp":"2019-01-01 00:00:00",
                    "tk_trade_create_time":"2019-01-01 00:00:00",
                    "click_uv":10,
                    "click_pv":10,
                    "tk_commission_rate":"0.5",
                    "pre_subsidy_fee":"1",
                    "pre_commission_fee":"1.5",
                    "cm_alipay_amt":"10",
                    "cm_alipay_num":1,
                    "ds":"20190525",
                    "cm_3rd_pub_share_fee":"1.5",
                    "cm_pub_share_fee":"1.5",
                    "pre_3rd_pub_share_fee":"1.5",
                    "pre_pub_share_fee":"1.5",
                    "alipay_amt":"10",
                    "alipay_num":10,
                    "zz_uv":100,
                    "union_pv":100,
                    "biz_type":"1",
                    "sub_adzone_id":1234,
                    "sub_site_id":1234,
                    "sub_pub_id":1234,
                    "name":"1234",
                    "pub_id":1234,
                    "tb_alipay_total_price":"10",
                    "tk_3rd_pub_share_fee":"1.5"
                }
            ]
        },
        "report_type_id":"union_channel_content_basic_v1",
        "page_info":{
            "total_cnt":20,
            "page_no":1,
            "page_size":100
        },
        "position_index":"123"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| 1001 | 非法的me参数值 | 传入正确的me参数值，含有券ID与商品ID信息 |
| 10000 | 该itemId对应的宝贝已下架或非淘客宝贝 | 更换新的itemId查询 |
| 4 | 查询不到对应的adzoneId，请检查adzoneId是否正确 | 查询不到对应的adzoneId，请检查adzoneId是否正确 |
| 30002 | 参数q与cat不能都为空 | 参数q与cat不能都为空 |
| 2 | pid不正确，请检查是否输入了正确的adzoneId和siteId | pid不正确，请检查是否输入了正确的adzoneId和siteId |
| 40001 | 内部调用失败 | 联系开发人员 |
| 50001 | 无结果 | 无结果 |
| 30001 | 非法的物料id | 非法的物料id |

---
##taobao.tbk.jzf.convert（淘宝客-推广者-官办找福利页）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| content | String | 必须 | 九月陌墨 2019春季新款女装复古长袖格子衬衫女 韩版宽松休闲衬衣 |  | 标题类型的字数需超过10个 |
| type | Number | 可选 | 1 | 默认值：1 | 1：标题，2：淘口令/链接,不传默认为1 |
| adzone_id | Number | 必须 | 1212 |  | 广告位id |
| relation_id | Number | 可选 | 11212 |  | 代理ID（暂未支持，无需传递） |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | MapData |  | data |
| └ url | String | https://uland.taobao.com/zfl/edetail?union_spk=KB45dpYg73oGQASttHIRqVRYJwp7yS6qMABzzGcTJXQZn7bmG82Lxym%2BcFFf%2FTa5yxTIFqojWrfFAIMAFBmQmQ%3D%3D&union_lens=lensId:0b0d6e6f_1047_16b8d3ba2ec_03eb | content的商品对应找福利页面链接 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.jzf.convert', {
	'content':'九月陌墨 2019春季新款女装复古长袖格子衬衫女 韩版宽松休闲衬衣',
	'type':'1',
	'adzone_id':'1212',
	'relation_id':'11212'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_jzf_convert_response":{
        "data":{
            "url":"https:\/\/uland.taobao.com\/zfl\/edetail?union_spk=KB45dpYg73oGQASttHIRqVRYJwp7yS6qMABzzGcTJXQZn7bmG82Lxym%2BcFFf%2FTa5yxTIFqojWrfFAIMAFBmQmQ%3D%3D&union_lens=lensId:0b0d6e6f_1047_16b8d3ba2ec_03eb"
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isv.invalid-param | 入参不合法 | 根据文档检查入参并按照规范修改 |
| isp.sys-error | 系统服务错误 | 稍后重试 |
| isv.param-content-empty | 入参content为空 | 根据文档修改入参 |
| isv.param-type-invalid | 入参type不合法 | 根据文档修改入参 |
| isv.item-not-found | 未找到对应商品 | 修改商品查询相关参数 |
| isv.invalid-adzone-id | 入参adzoneId不合法 | 根据文档修改入参 |
| isv.invalid-pid | pid不合法 | 根据规范修改正确pid相关参数 |

---
##taobao.tbk.dg.reports.query.stat（淘宝客-推广者-媒体数据报表交换-汇总数据）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| page_size | Number | 必须 | 100 |  | 每页大小 |
| page_no | Number | 必须 | 1 |  | 页码 |
| dimensions | String | 可选 | ds |  | 聚合条件 |
| filters | String | 必须 | ds=20191017;hasCount=true |  | 查询条件;ds为日期，hasCount表示是否获取数量，建议第一次获取，后续传入false以提高整个接口响应性能 |
| return_fields | String | 可选 | ds,cm_3rd_pub_share_fee,cm_pub_share_fee,pre_3rd_pub_share_fee,pre_pub_share_fee,alipay_amt,alipay_num,union_pv,sub_adzone_id,sub_site_id,sub_pub_id,name,pub_id,union_uv,red_envelope_gmt,red_envelope_num,activity_promotion_gmt |  | 查询结果返回的字段 |
| report_type_id | String | 必须 | union_channel_content_3rd_v1 |  | 报表名称 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data_list | MapData [] | map数组 | 结果列表 |
| └ ds | String | 20190525 | 日期 |
| └ cm_3rd_pub_share_fee | String | 1.5 | 达人结算预估收入 |
| └ cm_pub_share_fee | String | 1.5 | 平台结算预估收入 |
| └ pre_3rd_pub_share_fee | String | 1.5 | 达人预估收入 |
| └ pre_pub_share_fee | String | 1.5 | 平台预估收入 |
| └ alipay_amt | String | 10 | 成交金额 |
| └ alipay_num | Number | 10 | 成交笔数 |
| └ union_pv | Number | 100 | 联盟口径pv |
| └ sub_adzone_id | Number | 1234 | 达人adzoneid |
| └ sub_site_id | Number | 1234 | 达人siteid |
| └ sub_pub_id | Number | 1234 | 达人pubid |
| └ name | String | 1234 | 达人名称 |
| └ pub_id | Number | 1234 | 平台pud_id |
| └ union_uv | Number | 100 | 联盟口径uv |
| └ red_envelope_gmt | String | 10 | 优品推广-权益成交Alipay金额 |
| └ red_envelope_num | Number | 10 | 超级红包发放数量 |
| └ activity_promotion_gmt | String | 10 | 优品推广成交Alipay金额 |
| └ pre_red_envelope_media_share_fee | String | 10 | 超红媒体预估收益 |
| report_type_id | String | union_channel_content_3rd_v1 | 报表名称 |
| page_info | RptPageinfo | map | 分页信息 |
| └ total_cnt | Number | 1234 | 总数 |
| └ page_no | Number | 1 | 页数 |
| └ page_size | Number | 100 | 每页大小 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.reports.query.stat', {
	'page_size':'100',
	'page_no':'1',
	'dimensions':'ds',
	'filters':'ds=20191017;hasCount=true',
	'return_fields':'ds,cm_3rd_pub_share_fee,cm_pub_share_fee,pre_3rd_pub_share_fee,pre_pub_share_fee,alipay_amt,alipay_num,union_pv,sub_adzone_id,sub_site_id,sub_pub_id,name,pub_id,union_uv,red_envelope_gmt,red_envelope_num,activity_promotion_gmt',
	'report_type_id':'union_channel_content_3rd_v1'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_reports_query_stat_response":{
        "data_list":{
            "map_data":[
                {
                    "ds":"20190525",
                    "cm_3rd_pub_share_fee":"1.5",
                    "cm_pub_share_fee":"1.5",
                    "pre_3rd_pub_share_fee":"1.5",
                    "pre_pub_share_fee":"1.5",
                    "alipay_amt":"10",
                    "alipay_num":10,
                    "union_pv":100,
                    "sub_adzone_id":1234,
                    "sub_site_id":1234,
                    "sub_pub_id":1234,
                    "name":"1234",
                    "pub_id":1234,
                    "union_uv":100,
                    "red_envelope_gmt":"10",
                    "red_envelope_num":10,
                    "activity_promotion_gmt":"10",
                    "pre_red_envelope_media_share_fee":"10"
                }
            ]
        },
        "report_type_id":"union_channel_content_3rd_v1",
        "page_info":{
            "total_cnt":1234,
            "page_no":1,
            "page_size":100
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| 1001 | 非法的me参数值 | 传入正确的me参数值，含有券ID与商品ID信息 |
| 10000 | 该itemId对应的宝贝已下架或非淘客宝贝 | 更换新的itemId查询 |
| 4 | 查询不到对应的adzoneId，请检查adzoneId是否正确 | 查询不到对应的adzoneId，请检查adzoneId是否正确 |
| 30002 | 参数q与cat不能都为空 | 参数q与cat不能都为空 |
| 2 | pid不正确，请检查是否输入了正确的adzoneId和siteId | pid不正确，请检查是否输入了正确的adzoneId和siteId |
| 40001 | 内部调用失败 | 联系开发人员 |
| 50001 | 无结果 | 无结果 |
| 30001 | 非法的物料id | 非法的物料id |

---
##taobao.tbk.dg.reports.query.click（淘宝客-推广者-媒体数据交换报表点击维度）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| page_size | Number | 必须 | 20 |  | 每页大小 |
| page_no | Number | 必须 | 1 |  | 页码 |
| dimensions | String | 可选 | ds |  | 聚合条件 |
| filters | String | 必须 | ds=20190723 |  | 查询条件 |
| return_fields | String | 可选 | name |  | 查询字段 |
| report_type_id | String | 必须 | union_media_3rd_click |  | 报表名称 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data_list | MapData [] | map数组 | 结果列表 |
| └ click_id | String | 1234 | 点击id |
| report_type_id | String | union_media_3rd_click | 报表名称 |
| page_info | RptPageinfo | map | 分页信息 |
| └ total_cnt | Number | 20 | 总数 |
| └ page_no | Number | 1 | 页数 |
| └ page_size | Number | 100 | 每页大小 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.reports.query.click', {
	'page_size':'20',
	'page_no':'1',
	'dimensions':'ds',
	'filters':'ds=20190723',
	'return_fields':'name',
	'report_type_id':'union_media_3rd_click'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_reports_query_click_response":{
        "data_list":{
            "map_data":[
                {
                    "click_id":"1234"
                }
            ]
        },
        "report_type_id":"union_media_3rd_click",
        "page_info":{
            "total_cnt":20,
            "page_no":1,
            "page_size":100
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| 1001 | 非法的me参数值 | 传入正确的me参数值，含有券ID与商品ID信息 |
| 10000 | 该itemId对应的宝贝已下架或非淘客宝贝 | 更换新的itemId查询 |
| 4 | 查询不到对应的adzoneId，请检查adzoneId是否正确 | 查询不到对应的adzoneId，请检查adzoneId是否正确 |
| 30002 | 参数q与cat不能都为空 | 参数q与cat不能都为空 |
| 2 | pid不正确，请检查是否输入了正确的adzoneId和siteId | pid不正确，请检查是否输入了正确的adzoneId和siteId |
| 40001 | 内部调用失败 | 联系开发人员 |
| 50001 | 无结果 | 无结果 |
| 30001 | 非法的物料id | 非法的物料id |



---
##taobao.tbk.dg.vegas.send.report（淘宝客-推广者-查询红包发放个数）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| biz_date | String | 必须 | 20191201 |  | 统计日期 |
| relation_id | Number | 可选 | 111 |  | 渠道关系id |
| activity_id | Number | 可选 | 1 |  | 已下线，后续不需要填写 |
| page_no | Number | 可选 | 1 | 默认值：1 | 页码 |
| page_size | Number | 可选 | 10 | 默认值：10 | 每页大小 |
| pid | String | 可选 | mm_123_123_123 |  | 媒体推广pid |
| rpt_dim | String | 可选 | pid/relation |  | 查询维度，不填写默认是pid维度 |
| activity_category | Number | 可选 | 1 | 默认值：1 | 查询红包类型，1-超级红包，2-福利购，3-签到红包，4-福利直降，5-幸运赢免单，不传时默认查询超级红包数据 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result | Result |  | 返回结果 |
| └ success | Boolean | true | 是否成功 |
| └ model | RightsSendRptDTO |  | model |
| └ relation_rpt_list | RightsSendRelationRptDto

                                 [] |  | 渠道关系id的发放数据 |
| └ biz_date | String | 20191201 | 日期 |
| └ relation_id | Number | 111 | 渠道关系id |
| └ fund_num | Number | 100 | 红包发放数量 |
| └ pid | String | mm_123_123_123 | 渠道关系id关联的pid |
| └ use_num | Number | 88 | 红包使用次数 |
| └ pid_rpt_list | RightsSendRelationRptDto

                                 [] |  | pid的发放数据 |
| └ biz_date | String | 20191201 | 日期 |
| └ pid | String | mm_123_123_123 | pid |
| └ fund_num | Number | 100 | 红包发放数量 |
| └ use_num | Number | 78 | 红包使用次数 |
| └ msg_info | String | 1 | msgInfo |
| └ msg_code | String | 1 | msgCode |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.vegas.send.report', {
	'biz_date':'20191201',
	'relation_id':'111',
	'activity_id':'1',
	'page_no':'1',
	'page_size':'10',
	'pid':'mm_123_123_123',
	'rpt_dim':'pid/relation',
	'activity_category':'1'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_vegas_send_report_response":{
        "result":{
            "success":true,
            "model":{
                "relation_rpt_list":{
                    "rights_send_relation_rpt_dto":[
                        {
                            "biz_date":"20191201",
                            "relation_id":111,
                            "fund_num":100,
                            "pid":"mm_123_123_123",
                            "use_num":88
                        }
                    ]
                },
                "pid_rpt_list":{
                    "rights_send_relation_rpt_dto":[
                        {
                            "biz_date":"20191201",
                            "pid":"mm_123_123_123",
                            "fund_num":100,
                            "use_num":78
                        }
                    ]
                }
            },
            "msg_info":"1",
            "msg_code":"1"
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```





---
##taobao.tbk.activity.info.get（淘宝客-推广者-官方活动转链）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| activity_material_id | String | 必须 | 123 |  | 官方活动会场ID，从淘宝客后台“我要推广-活动推广”中获取 |
| adzone_id | Number | 必须 | 123 |  | mm_xxx_xxx_xxx的第三位 |
| sub_pid | String | 可选 | mm_1_2_3 |  | mm_xxx_xxx_xxx 仅三方分成场景使用 |
| relation_id | Number | 可选 | 123 |  | 渠道关系id |
| union_id | String | 可选 | demo |  | 自定义输入串，英文和数字组成，长度不能大于12个字符，区分不同的推广渠道 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | Data |  | 返回结果对象 |
| └ wx_qrcode_url | String | https://img.alicdn.com/xxx | 【本地化】微信推广二维码地址 |
| └ click_url | String | https://s.click.xx.xx/xxx?xx | 淘客推广长链 |
| └ short_click_url | String | https://s.click.xx.xx/xxx?xx | 淘客推广短链 |
| └ terminal_type | String | 1 | 投放平台, 1-PC 2-无线 |
| └ material_oss_url | String | http://xxx.xxx.xxx | 物料素材下载地址 |
| └ page_name | String | 活动会场A | 会场名称 |
| └ page_start_time | String | 2020-02-27 | 活动开始时间 |
| └ page_end_time | String | 2020-02-27 | 活动结束时间 |
| └ wx_miniprogram_path | String | pages/sharePid/web/index?scene=https://xxx | 【本地化】微信小程序路径 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.activity.info.get', {
	'activity_material_id':'123',
	'adzone_id':'123',
	'sub_pid':'mm_1_2_3',
	'relation_id':'123',
	'union_id':'demo'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_activity_info_get_response":{
        "data":{
            "wx_qrcode_url":"https:\/\/img.alicdn.com\/xxx",
            "click_url":"https:\/\/s.click.xx.xx\/xxx?xx",
            "short_click_url":"https:\/\/s.click.xx.xx\/xxx?xx",
            "terminal_type":"1",
            "material_oss_url":"http:\/\/xxx.xxx.xxx",
            "page_name":"活动会场A",
            "page_start_time":"2020-02-27",
            "page_end_time":"2020-02-27",
            "wx_miniprogram_path":"pages\/sharePid\/web\/index?scene=https:\/\/xxx"
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isp.invalid-parameter-adzone | 入参adzone_id错误 | 请检查adzone_id是否属于appkey拥有者 |
| 4 | 入参adzone_id不存在 | 查询不到对应的adzoneId，请检查adzoneId是否正确 |
| isp.invalid-parameter-materialId | 物料id无效 | 请检查物料id是否从官方渠道获取或物料本身是否已失效 |
| 1108 | 【本地化】饿了么微信小程序二维码生成失败 | 请稍后重试，多次重试无效后请联系官方人员 |
| 1107 | 【本地化】饿了么短链生成失败 | 请稍后重试，多次重试无效后请联系官方人员 |
| isp.isp.get-activityinfo-unavailable | 服务无法获取 | 稍后重试，多次重试无效后请联系官方人员 |
| isv.invalid-parameter-materialId | 入参物料id无效 | 请检查物料id是否从官方渠道获取或物料本身是否已失效 |
| isv.invalid-parameter-adzone | 入参adzone_id错误 | 请检查adzone_id是否属于appkey拥有者 |
| isv.empty-parameter-materialId | 入参物料ID不正确 | 请传入正确的物料ID |

---
##taobao.tbk.dg.optimus.promotion（淘宝客-推广者-权益物料精选）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| page_size | Number | 可选 | 10 | 默认值：10 | 页大小，一次请求请限制在10以内 |
| page_num | Number | 可选 | 1 | 默认值：1 | 第几页，默认：1 |
| adzone_id | Number | 必须 | 123 |  | mm_xxx_xxx_xxx的第3段数字 |
| promotion_id | Number | 必须 | 123 |  | 官方提供的权益物料Id。有价券-37104、大额店铺券-37116、天猫店铺券-62191、券券补-61809 更多权益物料id敬请期待！ |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result_list | MapData [] |  | resultList |
| └ promotion_type | String | 1 | 权益类型。1 有价券（需要购买的店铺券或单品券） 2 公开券（直接领取的店铺券或单品券） 3 妈妈券（妈妈渠道领取的店铺券或单品券） 4.品类券 （跨店可用券，可与1，2，3叠加） |
| └ condition_type | String | 1 | 优惠门槛类型： 1 满元 2 满件 |
| └ discount_type | String | 1 | 优惠类型： 1 减钱 2 打折 |
| └ total_count | Number | 50 | 权益信息-总量（权益初始库存量） |
| └ remain_count | Number | 20 | 权益信息-剩余库存（权益剩余库存量） |
| └ display_start_time | String | 1559232000000 | 权益信息展示开始时间，精确到毫秒时间戳 |
| └ display_end_time | String | 1559750399000 | 权益信息展示结束时间，精确到毫秒时间戳 |
| └ promotion_list | PromotionList

                                 [] |  | 权益信息 |
| └ entry_used_start_time | String | 1559232000000 | 权益开始时间，精确到毫秒时间戳 |
| └ entry_used_end_time | String | 1559750399000 | 权益结束时间，精确到毫秒时间戳 |
| └ entry_condition | String | 100 | 权益起用门槛，满X元可用，券场景为满元，精确到分，如满100元可用 |
| └ entry_discount | String | 30 | 权益面额，券场景为减钱，精确到分 |
| └ promotion_extend | PromotionExtend |  | 权益扩展信息 |
| └ recommend_item_list | RecommendItemList

                                 [] |  | 权益推荐商品 |
| └ item_id | Number | 123456 | 权益推荐商品id |
| └ url | String | //s.click.taobao.com/xxx | 商品链接 |
| └ youjia_coupon_info | Youjiacouponinfo |  | 有价券信息 |
| └ item_id | String | 123456 | 有价券商品id |
| └ url | String | //s.click.taobao.com/xxx | 商品链接 |
| └ promotion_url | String | https://uland.taobao.com/quan/xxx | 权益链接 |
| └ seller_id | String | 123 | 店铺信息-卖家ID |
| └ nick | String | XXX专营店 | 店铺信息-卖家昵称 |
| └ shop_title | String | XXX旗舰店 | 店铺信息-店铺名称 |
| └ shop_picture_url | String | http://xxx | 店铺信息-店铺logo |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.optimus.promotion', {
	'page_size':'10',
	'page_num':'1',
	'adzone_id':'123',
	'promotion_id':'123'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_optimus_promotion_response":{
        "result_list":{
            "map_data":[
                {
                    "promotion_type":"1",
                    "condition_type":"1",
                    "discount_type":"1",
                    "total_count":50,
                    "remain_count":20,
                    "display_start_time":"1559232000000",
                    "display_end_time":"1559750399000",
                    "promotion_list":{
                        "promotion_list":[
                            {
                                "entry_used_start_time":"1559232000000",
                                "entry_used_end_time":"1559750399000",
                                "entry_condition":"100",
                                "entry_discount":"30"
                            }
                        ]
                    },
                    "promotion_extend":{
                        "recommend_item_list":{
                            "recommend_item_list":[
                                {
                                    "item_id":123456,
                                    "url":"\/\/s.click.taobao.com\/xxx"
                                }
                            ]
                        },
                        "youjia_coupon_info":{
                            "item_id":"123456",
                            "url":"\/\/s.click.taobao.com\/xxx"
                        },
                        "promotion_url":"https:\/\/uland.taobao.com\/quan\/xxx"
                    },
                    "seller_id":"123",
                    "nick":"XXX专营店",
                    "shop_title":"XXX旗舰店",
                    "shop_picture_url":"http:\/\/xxx"
                }
            ]
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| 50001 | 投放无数据 | 请联系小二 |
| 40001 | 内部调用失败 | 请重试 |

---
##taobao.tbk.dg.vegas.send.status（淘宝客-推广者-红包领取状态查询）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| relation_id | String | 可选 | 12345 |  | 渠道管理id |
| special_id | String | 可选 | 12345 |  | 会员运营id |
| device_value | String | 可选 | xxx |  | 加密后的值，需用MD5加密，32位小写 |
| device_type | String | 可选 | IMEI |  | 入参类型(该模式下返回的结果为模糊匹配结果，和实际情况可能存在误差)： 1. IMEI 2. IDFA 3. OAID 4. MOBILE |
| thor_biz_code | String | 可选 | xxx |  | 已废弃，请勿传入 |
| pid | String | 可选 | mm_0_0_0 |  | 媒体pid |
| activity_category | Number | 可选 | 1 |  | 查询红包类型，1-超级红包，2-福利购，3-签到红包，4-福利直降，5-幸运赢免单，不传时默认查询超级红包数据 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result_msg | String | 成功 | 返回结果描述信息 |
| data | Data |  | 返回结果封装对象 |
| └ result_list | MapData

                                 [] |  | 返回结果封装对象 |
| └ is_new_user | String | 1 | 若该用户当前无待核销的红包，则返回1，若当前有待核销的红包，则返回0 |
| biz_error_desc | String | 说明 | 系统自动生成 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.vegas.send.status', {
	'relation_id':'12345',
	'special_id':'12345',
	'device_value':'xxx',
	'device_type':'IMEI',
	'thor_biz_code':'xxx',
	'pid':'mm_0_0_0',
	'activity_category':'1'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_vegas_send_status_response":{
        "result_msg":"成功",
        "data":{
            "result_list":{
                "map_data":[
                    {
                        "is_new_user":"1"
                    }
                ]
            }
        },
        "biz_error_desc":"说明"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.pailitao.widget.convert（淘宝客-推广者-拍立淘插件转链）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| adzone_id | Number | 必须 | 123 |  | mm_xxx_xxx_xxx的第三位 |
| relation_id | Number | 可选 | 123 |  | 渠道id |
| type | Number | 可选 | 0 | 默认值：0 | 0：代表转官方插件  1：代表转deeplink链接 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| url | String | https://xxx | 根据入参信息，转出开启官方拍立淘插件URL或deeplink链接 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.pailitao.widget.convert', {
	'adzone_id':'123',
	'relation_id':'123',
	'type':'0'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_pailitao_widget_convert_response":{
        "url":"https:\/\/xxx"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.thor.task.select（淘宝客-推广者-互动任务投放）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| req | TopSelectOption | 必须 |  |  | 入参 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | TaskInstance [] |  | 系统自动生成 |
| └ task_type | String | LOGIN | 互动任务类型 |
| └ task_cost | String | 0.05 | 互动任务cpa价格 |
| └ task_button | String | 去绑定 | 媒体投放任务点击按钮文案 |
| └ task_desc | String | 绑定淘宝账号，逛淘宝也能赚钱 | 媒体投放任务描述 |
| └ task_name | String | 绑定淘宝 | 媒体投放任务标题 |
| └ url | String | https://mos.m.taobao.com/union/media/activity/auth | 媒体投放任务链接 |
| └ task_id | Number | 124 | 媒体投放任务id |
| └ status | String | ACCEPTED | 媒体投放任务状态 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.thor.task.select', {
	'req':'数据结构JSON示例'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_thor_task_select_response":{
        "data":{
            "task_instance":[
                {
                    "task_type":"LOGIN",
                    "task_cost":"0.05",
                    "task_button":"去绑定",
                    "task_desc":"绑定淘宝账号，逛淘宝也能赚钱",
                    "task_name":"绑定淘宝",
                    "url":"https:\/\/mos.m.taobao.com\/union\/media\/activity\/auth",
                    "task_id":124,
                    "status":"ACCEPTED"
                }
            ]
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.rta.consumer.match（淘宝客-推广者-定向活动目标发布）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| adzone_id | Number | 必须 | 33 |  | mm_xxx_xxx_xxx的第3段数字 |
| offer_list | OfferList

        						[] | 可选 |  | 最大列表长度：100 | 活动列表 |
| special_id | String | 可选 | 1 |  | 消费者对应的会员ID（会员ID或设备信息同时填时，优先使用会员ID） |
| device_value | String | 可选 | ssss |  | 设备信息，加密后的值(IMEI,IDFA,OAID,MOBILE需要加密)，需用MD5加密，32位小写 |
| device_type | String | 可选 | OAID |  | 设备信息，入参类型(该模式下返回的结果为模糊匹配结果，和实际情况可能存在误差)：IMEI, 或者IDFA, 或者OAID, 或者MOBILE |
| strategy_id_list | String | 可选 | 123456 |  | 策略ID，与活动列表二选一传入 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | Data |  | 返回结果 |
| └ result_list | Resultlist

                                 [] |  | 返回结果列表 |
| └ offer_id | String | 123 | 活动id |
| └ status | String | 1 | 活动状态：1-符合活动要求，2-淘客无活动权限，3-用户不匹配活动，4-系统异常，5-活动不存在 |
| └ click_url | String | https://www.taobao.com | 推广链接 |
| └ wx_miniprogram_path | String | https://www.taobao.com | 微信小程序路径 |
| └ wx_qrcode_url | String | https://www.taobao.com | 微信小程序码 |
| └ strategy_result_list | StrategyResultList

                                 [] |  | 策略ID的匹配结果，仅在入参strategy_id_list字段非空时返回 |
| └ strategy_id | String | 123 | 策略ID |
| └ status | String | 1 | 状态：1-符合活动要求 ，3-用户不匹配活动，4-系统异常，6-策略ID不存在，7-策略ID无效 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.rta.consumer.match', {
	'adzone_id':'33',
	'offer_list':'数据结构JSON示例',
	'special_id':'1',
	'device_value':'ssss',
	'device_type':'OAID',
	'strategy_id_list':'123456'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_rta_consumer_match_response":{
        "data":{
            "result_list":{
                "resultlist":[
                    {
                        "offer_id":"123",
                        "status":"1",
                        "click_url":"https:\/\/www.taobao.com",
                        "wx_miniprogram_path":"https:\/\/www.taobao.com",
                        "wx_qrcode_url":"https:\/\/www.taobao.com"
                    }
                ]
            },
            "strategy_result_list":{
                "strategy_result_list":[
                    {
                        "strategy_id":"123",
                        "status":"1"
                    }
                ]
            }
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| 1601 | 错误的specialId | 确保specialId正确，且归属关系正确 |
| 1701 | 活动查询异常 | 建议稍后重试 |
| 1702 | 无效的offerId | 建议传入有效的offerId |
| 2 | adzoneId不正确 | 更换正确的adzoneId |
| 4 | adzoneId不存在 | 更换正确的adzoneId |
| 1803 | 错误的设备信息参数 | 修改设备相关参数 |
| 1802 | 错误的设备信息参数device_value | 更换请求参数 |

---
##taobao.tbk.dg.cpa.activity.detail（淘宝客-推广者-CPA活动执行明细）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| query_type | Number | 可选 | 1 | 默认值：1 | 明细类型，1：预估明细，2：结算明细 |
| page_size | Number | 可选 | 10 | 默认值：10 | 每页条数 |
| page_no | Number | 可选 | 1 | 默认值：1 | 页码 |
| event_id | Number | 必须 | 111 |  | CPA活动ID |
| indicator_alias | String | 可选 | abcd |  | CPA活动奖励的统计口径，相关说明见文档：https://www.yuque.com/docs/share/7ecf8cf1-7f99-4633-a2ed-f9b6f8116af5?# |
| start_id | Number | 可选 | 111 |  | 下一页开始查询的记录主键id |
| runtime | Date | 可选 | 2022-06-09 00:00:00 |  | 指定数据批次号(时间戳) |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result | Result |  | 接口返回model |
| └ biz_error_feature | String | demo | 错误代码 |
| └ data | PageResult | 1234 | 返回素材id |
| └ results | Results

                                 [] |  | 数据结果 |
| └ field_detail | String |  | 奖励明细数据，KV结构。字段释义见文档：https://www.yuque.com/docs/share/7ecf8cf1-7f99-4633-a2ed-f9b6f8116af5?# |
| └ calc_type | Number | 1 | 明细类型，1：预估明细，2：结算明细 |
| └ id | Number | 1 | 明细记录主键id |
| └ pre_page | Number | 1 | 上一页页码 |
| └ next_page | Number | 1 | 下一页页码 |
| └ page_no | Number | 1 | 当前页码 |
| └ total_pages | Number | 1 | 总共页数 |
| └ page_size | Number | 10 | 每页条数 |
| └ has_next | Boolean | false | 是否有下一页 |
| └ total_count | Number | 4 | 总条数 |
| └ has_pre | Boolean | false | 是否有下一页 |
| └ runtime | Date | 2022-06-09 00:00:00 | 数据批次号(时间戳) |
| └ success | Boolean | true | 是否成功 |
| └ result_code | Number | 200 | 结果码 |
| └ biz_error_desc | String | demo | 错误描述 |
| └ biz_error_code | Number | 0 | 错误代码 |
| └ result_msg | String | demo | 结果信息 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.cpa.activity.detail', {
	'query_type':'1',
	'page_size':'10',
	'page_no':'1',
	'event_id':'111',
	'indicator_alias':'abcd',
	'start_id':'111',
	'runtime':'2022-06-09 00:00:00'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_cpa_activity_detail_response":{
        "result":{
            "biz_error_feature":"demo",
            "data":{
                "results":{
                    "results":[
                        {
                            "field_detail":"",
                            "calc_type":1,
                            "id":1
                        }
                    ]
                },
                "pre_page":1,
                "next_page":1,
                "page_no":1,
                "total_pages":1,
                "page_size":10,
                "has_next":false,
                "total_count":4,
                "has_pre":false,
                "runtime":"2022-06-09 00:00:00"
            },
            "success":true,
            "result_code":200,
            "biz_error_desc":"demo",
            "biz_error_code":0,
            "result_msg":"demo"
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.tpwd.report.get（淘宝客-推广者-淘口令回流数据查询）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| tao_password | String | 必须 | 8緮置内容￥hxlgccEumBB￥达开?τao寶?或掂击炼接 https://m.tb.cn/h.VvkiWSm 至浏.览览.器【618超级红包】 |  | 待查询的口令 |
| adzone_id | String | 必须 | 33 |  | mm_xxx_xxx_xxx的第3段数字 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | MapData |  | 返回结果 |
| └ hour_pv | Number | 1 | 截止查询时刻近1小时回流pv |
| └ hour_uv | Number | 1 | 截止查询时刻近1小时回流uv |
| └ uv | Number | 1 | 今日截止查询时刻累计uv |
| └ pv | Number | 1 | 今日截止查询时刻累计pv |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.tpwd.report.get', {
	'tao_password':'8緮置内容￥hxlgccEumBB￥达开?τao寶?或掂击炼接 https://m.tb.cn/h.VvkiWSm 至浏.览览.器【618超级红包】',
	'adzone_id':'33'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_tpwd_report_get_response":{
        "data":{
            "hour_pv":1,
            "hour_uv":1,
            "uv":1,
            "pv":1
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.private.tpwd.create（淘宝客-推广者-加密淘口令生成）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| url | String | 必须 | https://s.click.taobao.com/YI3Uopu |  | 联盟官方渠道获取的淘客推广链接，请注意，不要随意篡改官方生成的链接，否则可能无法生成淘口令 |
| text | String | 可选 | noMeaningValue |  | 兼容旧版本api参数，无实际作用 |
| logo | String | 可选 | noMeaningValue |  | 兼容旧版本api参数，无实际作用 |
| ext | String | 可选 | noMeaningValue |  | 兼容旧版本api参数，无实际作用 |
| user_id | String | 可选 | noMeaningValue |  | 兼容旧版本api参数，无实际作用 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | MapData |  | 返回结果对象 |
| └ model | String | 8緮置内容￥hxlgccEumBB￥达开?τao寶?或掂击炼接 https://m.tb.cn/h.VvkiWSm 至浏.览览.器【618超级红包】 | 针对苹果ios14及以上版本的苹果设备，手淘将按照示例值信息格式读取淘口令(需包含：数字+羊角符+url，识别规则可能根据ios情况变更)。如需更改淘口令内文案、url等内容，请务必先验证更改后的淘口令在手淘可被识别打开！ |
| └ password_simple | String | ￥SIH6XbwRfyt￥ | 非苹果ios14以上版本的设备（即其他ios版本、Android系统等），可以用此淘口令正常在复制到手淘打开 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.private.tpwd.create', {
	'url':'https://s.click.taobao.com/YI3Uopu',
	'text':'noMeaningValue',
	'logo':'noMeaningValue',
	'ext':'noMeaningValue',
	'user_id':'noMeaningValue'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_private_tpwd_create_response":{
        "data":{
            "model":"8緮置内容￥hxlgccEumBB￥达开?τao寶?或掂击炼接 https:\/\/m.tb.cn\/h.VvkiWSm 至浏.览览.器【618超级红包】",
            "password_simple":"￥SIH6XbwRfyt￥"
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.cpa.activity.report（淘宝客-推广者-任务奖励效果报表）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| event_id | Number | 必须 | 1 |  | CPA活动ID，详见https://www.yuque.com/docs/share/16905f3f-3a22-4e7c-b8c3-4d23791d42f7?# |
| biz_date | String | 必须 | 20210818 |  | 日期(yyyyMMdd) |
| page_no | Number | 可选 | 1 |  | 分页页数，从1开始 |
| query_type | Number | 可选 | 1 | 默认值：1 | 数据类型：数据类型:1预估 2结算 （选择1可查询含当天实时预估统计的累计数据，选择2可查询最晚截止昨天结算的累计数据，具体逻辑以活动规则描述为准；） |
| page_size | Number | 可选 | 10 |  | 分页大小 |
| pid | String | 可选 | mm_123_123_123 |  | 媒体三段式id（如果传入pid则返回pid汇总数据，不传则返回member维度统计数据，pid和relationid不可同时传入） |
| relation_id | Number | 可选 | 100 |  | 代理id（如果传入rid则返回rid统计数据，不传则返回member维度统计数据） |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result | RpcResult | {} | 返回模型 |
| └ data | PageResult | {} | 分页模型 |
| └ results | VegasCpaReportDTO

                                 [] | [] | 数据列表 |
| └ union_30d_lx_uv | Number | 100 | 符合奖励要求的累计用户数；按入参是预估/结算，区分用户数为预估or可结算结果； |
| └ reward_amount | String | 123.45 | 奖励金额；按入参是预估/结算，区分获得金额为预估or可结算结果； |
| └ relation_id | Number | 123456 | rid，当查询数据为rid维度时返回该字段 |
| └ biz_date | String | 20210301 | 统计日期（统计活动期内，截止 统计日期 的数据） |
| └ pid | String | mm_123_123_123 | 媒体三段式id，当查询数据为pid维度时返回该字段 |
| └ query_type | Number | 1 | 数据类型:1预估 2结算 |
| └ ext_info | String | {"总奖励(累计)":102.1} | 活动相关数据信息 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.cpa.activity.report', {
	'event_id':'1',
	'biz_date':'20210818',
	'page_no':'1',
	'query_type':'1',
	'page_size':'10',
	'pid':'mm_123_123_123',
	'relation_id':'100'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_cpa_activity_report_response":{
        "result":{
            "data":{
                "results":{
                    "vegas_cpa_report_d_t_o":[
                        {
                            "union_30d_lx_uv":100,
                            "reward_amount":"123.45",
                            "relation_id":123456,
                            "biz_date":"20210301",
                            "pid":"mm_123_123_123",
                            "query_type":1,
                            "ext_info":"{\"总奖励(累计)\":102.1}"
                        }
                    ]
                }
            }
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.vegas.tlj.stop（淘宝客-推广者-淘礼金暂停发放）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| rights_id | String | 必须 | 34ffg34 |  | 创建淘礼金时返回的rightsId |
| adzone_id | Number | 必须 | 2343434 |  | adzoneId |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| model | UpdateStatusResult | test | model |
| └ update_success | Boolean | true | 暂停成功 |
| msg_info | String | 1 | msgInfo |
| msg_code | String | 1 | msgCode |
| result_success | Boolean | true | 调用接口是否成功 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.vegas.tlj.stop', {
	'rights_id':'34ffg34',
	'adzone_id':'2343434'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_vegas_tlj_stop_response":{
        "model":{
            "update_success":true
        },
        "msg_info":"1",
        "msg_code":"1",
        "result_success":true
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.vegas.tlj.report（淘宝客-推广者-淘礼金效果数据）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| rights_id | String | 必须 | rer2324er |  | 创建淘礼金时返回的rightsId |
| adzone_id | Number | 必须 | 232323 |  | adzoneId |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| model | InstanceDTO | model | 结果 |
| └ extra | Extra | extra | extra |
| └ get_rate | String | 50 | 领取率，领取淘礼金个数/创建淘礼金个数 |
| └ use_rate | String | 50 | 使用率，使用淘礼金个数/领取淘礼金个数 |
| └ alipay_num | Number | 1 | 引导付款笔数，同一个红包，若因消费者付款使用后取消订单或退货退款，产生二次红包使用行为，引导付款笔数也会记录两单 |
| └ alipay_amt | String | 19.0 | 引导付款金额，同一个红包，若因消费者付款使用后取消订单或退货退款，产生二次红包使用行为，引导付款笔数也会记录两单 |
| └ pre_pub_share_fee_for_disp | String | 20.23 | 付款佣金，下单付款，产生二次红包使用行为，会记录2次 |
| └ cm_settle_amt | String | 12.23 | 结算佣金，确认收货，产生二次红包使用行为，会记录2次 |
| └ win_pv | Number | 1 | 领取淘礼金个数 |
| └ win_sum_amt | String | 10 | 领取淘礼金金额 |
| └ remaining_num | Number | 2 | 未领取淘礼金个数，过了领取有效期或者暂停后没有被领取的红包个数 |
| └ remaining_amt | String | 20 | 未领取金额，过了领取有效期或者暂停后没有被领取的红包金额 |
| └ use_num | Number | 1 | 使用淘礼金个数，同一个红包，若因消费者付款使用后取消订单或退货退款，产生二次红包使用行为，使用淘礼金个数会重复计算 |
| └ use_sum_amt | String | 10 | 使用淘礼金金额，若红包被重复使用（1)淘礼金红包被拆分，并且产生部分退款，会保留部分退款的订单淘礼金金额；若全部退款，会保留订单全部淘礼金金额），因此，已使用金额可能大于消费者实际使用金额（使用红包后，若产生红包退回后再次使用，已使用金额会被二次计算，已使用数量不会） |
| └ refund_num | Number | 1 | 退款淘礼金个数，红包使用后，由于订单取消，退货退款等行为带来的淘礼金红包退回数量，退款红包数量会重复计算 |
| └ refund_sum_amt | String | 5.0 | 退款淘礼金金额，红包使用后，由于订单取消，退货退款等行为行为带来的淘礼金红包退回数量 （退款红包若产生多次使用，退款红包金额会被多次计算，退款红包数量单日内不重复计算，跨天重复计算） |
| msg_info | String | 1 | msgInfo |
| msg_code | String | 1 | msgCode |
| result_success | Boolean | true | 调用接口是否成功 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.vegas.tlj.report', {
	'rights_id':'rer2324er',
	'adzone_id':'232323'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_vegas_tlj_report_response":{
        "model":{
            "extra":{
                "get_rate":"50",
                "use_rate":"50",
                "alipay_num":1,
                "alipay_amt":"19.0",
                "pre_pub_share_fee_for_disp":"20.23",
                "cm_settle_amt":"12.23",
                "win_pv":1,
                "win_sum_amt":"10",
                "remaining_num":2,
                "remaining_amt":"20",
                "use_num":1,
                "use_sum_amt":"10",
                "refund_num":1,
                "refund_sum_amt":"5.0"
            }
        },
        "msg_info":"1",
        "msg_code":"1",
        "result_success":true
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.tpwd.risk.report（淘宝客-推广者-淘口令预警及拦截查询）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| pid | String | 可选 | mm_1111_0_0 |  | 如有pid，则查询pid下的relationid名单；如没有pid，则查询appkey关联userid下的pid名单 |
| offset | Number | 必须 | 0 |  | 分页参数 |
| limit | Number | 必须 | 1000 |  | 分页参数，一次最多不能超过1000 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result | Result | 无 | 无 |
| └ status_list | DataMap

                                 [] | x | x |
| └ pid | String | mm_1110_0_0 | 当入参不传pid的时候返回，表示账号关联的pid |
| └ rid | String | 222 | 当入参传入pid的时候返回，表示pid关联的relationId |
| └ status | String | 0 | 0表示预警，1表示拦截，如果名单中同一个淘客同时有拦截和预警信息，以拦截为准 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.tpwd.risk.report', {
	'pid':'mm_1111_0_0',
	'offset':'0',
	'limit':'1000'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_tpwd_risk_report_response":{
        "result":{
            "status_list":{
                "data_map":[
                    {
                        "pid":"mm_1110_0_0",
                        "rid":"222",
                        "status":"0"
                    }
                ]
            }
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.vegas.tlj.share.convert（淘宝客-推广者-淘礼金三方链接转换）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| adzone_id | Number | 必须 | 1234567 |  | 妈妈广告位Id |
| origin_url | String | 必须 | https://uland.taobao.com/?es=xxx |  | 原始二方分成url |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result | Result |  | result |
| └ success | Boolean | true | 是否成功 |
| └ model | TljShareConvertResult |  | model |
| └ send_url | String | https://www.taobao.com | 淘礼金三方分成链接 |
| └ msg_info | String | 1 | msg_info |
| └ msg_code | String | 1 | msg_code |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.vegas.tlj.share.convert', {
	'adzone_id':'1234567',
	'origin_url':'https://uland.taobao.com/?es=xxx'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_vegas_tlj_share_convert_response":{
        "result":{
            "success":true,
            "model":{
                "send_url":"https:\/\/www.taobao.com"
            },
            "msg_info":"1",
            "msg_code":"1"
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.seed.report.get（淘宝客-推广者-种草指标报表）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| page_no | Number | 必须 | 1 |  | 页码 |
| report_type_id | String | 必须 | wb-content-rpt |  | 报表名称(wb-content-rpt) |
| page_size | Number | 必须 | 50 |  | 页容 |
| filters | String | 必须 | ds=20220222 |  | 查询条件(本期只支持ds) |
| return_fields | String | 可选 | uv_num,new_visitor_uv_num,pay_buyer_uv |  | 查询字段(预留字段) |
| dimensions | String | 可选 | ds |  | 聚合条件(预留字段) |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | WbReportInfoDTO |  | 返回对象 |
| └ data_list | WbReportDataDTO

                                 [] |  | 数据列表 |
| └ uv_num | Number | 1 | 进店UV |
| └ new_visitor_uv_num | Number | 1 | 新访客UV |
| └ pay_buyer_uv | Number | 1 | 成交UV |
| └ clt_uv_num | Number | 1 | 收藏UV |
| └ obj_itm_se | Number | 1 | 手淘搜索进店UV |
| └ add_uv_num | Number | 1 | 加购UV |
| └ shop_follow_uv | Number | 1 | 店铺关注UV |
| └ dimensions | String | eventId=123456,contentId=654321,ds=20220224,day=15 | 维度(逗号分隔符连接) |
| └ search_pv | Number | 2 | 搜索PV |
| └ enter_shop_pv | Number | 2 | 进店PV |
| └ collect_pv | Number | 2 | 收藏PV |
| └ add_shopping_cart_pv | Number | 2 | 加购PV |
| └ deal_pv | Number | 2 | 成交PV |
| └ new_visitor_pv | Number | 2 | 新访客PV |
| └ follow_pv | Number | 2 | 关注PV |
| └ page_info | PageInfoDTO |  | 分页信息 |
| └ total | Number | 222 | 总数 |
| └ page_no | Number | 1 | 页码 |
| └ page_size | Number | 50 | 页容 |
| └ report_type_id | String | wb-content-rpt | 报表名称 |
| └ position_index | String | 111 | 位点(预留) |
| result_code | Number | 200 | 返回码 |
| biz_error_code | Number | 0 | 错误描述 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.seed.report.get', {
	'page_no':'1',
	'report_type_id':'wb-content-rpt',
	'page_size':'50',
	'filters':'ds=20220222',
	'return_fields':'uv_num,new_visitor_uv_num,pay_buyer_uv',
	'dimensions':'ds'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_seed_report_get_response":{
        "data":{
            "data_list":{
                "wb_report_data_d_t_o":[
                    {
                        "uv_num":1,
                        "new_visitor_uv_num":1,
                        "pay_buyer_uv":1,
                        "clt_uv_num":1,
                        "obj_itm_se":1,
                        "add_uv_num":1,
                        "shop_follow_uv":1,
                        "dimensions":"eventId=123456,contentId=654321,ds=20220224,day=15",
                        "search_pv":2,
                        "enter_shop_pv":2,
                        "collect_pv":2,
                        "add_shopping_cart_pv":2,
                        "deal_pv":2,
                        "new_visitor_pv":2,
                        "follow_pv":2
                    }
                ]
            },
            "page_info":{
                "total":222,
                "page_no":1,
                "page_size":50
            },
            "report_type_id":"wb-content-rpt",
            "position_index":"111"
        },
        "result_code":200,
        "biz_error_code":0
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.material.recommend（淘宝客-推广者-物料精选升级版）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| page_size | Number | 可选 | 20 | 默认值：20 | 页大小，默认20，1~100 |
| page_no | Number | 可选 | 1 | 默认值：1 | 第几页，默认：1 |
| material_id | Number | 必须 | 123 |  | 官方提供的物料Id；可以通过taobao.tbk.optimus.tou.material.ids.get接口获取公开的物料id列表或查看物料id汇总贴：https://market.m.taobao.com/app/qn/toutiao-new/index-pc.html#/detail/10628875?_k=gpov9a |
| adzone_id | Number | 必须 | 123 |  | 推广位id，mm_xxx_xxx_12345678三段式的最后一段数字（登录pub.alimama.com推广管理-推广位管理中查询） |
| relation_id | Number | 可选 | 123456 |  | 渠道关系ID，仅适用于渠道推广场景 |
| device_type | String | 可选 | IMEI |  | 智能匹配-设备号类型：IMEI，或者IDFA，或者UTDID（UTDID不支持MD5加密），或者OAID；使用智能推荐请先签署协议https://pub.alimama.com/fourth/protocol/common.htm?key=hangye_laxin |
| device_encrypt | String | 可选 | MD5 |  | 智能匹配-设备号加密类型：MD5；使用智能推荐请先签署协议https://pub.alimama.com/fourth/protocol/common.htm?key=hangye_laxin |
| device_value | String | 可选 | xxx |  | 智能匹配-设备号加密后的值（MD5加密需32位小写）；使用智能推荐请先签署协议https://pub.alimama.com/fourth/protocol/common.htm?key=hangye_laxin |
| favorites_id | String | 可选 | 123445 |  | 选品库收藏夹id，获取收藏夹id参考文档：https://mos.m.taobao.com/union/page_20230109_175050_176?spm=a219t._portal_v2_pages_promo_goods_index_htm.0.0.7c2a75a5H2ER3N |
| promotion_type | String | 可选 | 2 |  | 1-自购省，2-推广赚（代理模式专属ID，代理模式必填，非代理模式不用填写该字段） |
| special_id | String | 可选 | 2323 |  | 会员运营ID |
| item_id | String | 可选 | qeqscd1231-uqwenqe |  | 淘宝客新商品ID；用于相似商品推荐（注意：使用相似商品推荐material_id=13256必传，并请先签署协议https://pub.alimama.com/fourth/protocol/common.htm?key=hangye_laxin)；另关于《淘宝客新商品ID升级》参考白皮书：https://www.yuque.com/taobaolianmengguanfangxiaoer/zmig94/tfyt0pahmlpzu2ud |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result_list | MapData [] |  | resultList |
| └ item_id | String | qeqscd1231-uqwenqe | 商品信息-淘宝客新商品id；使用说明参考《淘宝客新商品ID升级》白皮书：https://www.yuque.com/taobaolianmengguanfangxiaoer/zmig94/tfyt0pahmlpzu2ud |
| └ item_basic_info | BasicMapData |  | 商品基础信息 |
| └ title | String | 复古女裤子秋冬九分裤萝卜裤显瘦高腰韩版2017新款 | 商品信息-商品标题 |
| └ short_title | String | 九分裤显瘦高腰韩版 | 商品信息-商品短标题 |
| └ pict_url | String | //img.alicdn.com/bao/uploaded/i4/745957850/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg | 商品信息-商品主图 |
| └ white_image | String | https://img.alicdn.com/bao/uploaded/i4/745957850/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg | 商品信息-商品白底图 |
| └ level_one_category_id | Number | 1 | 商品信息-一级类目ID |
| └ level_one_category_name | String | 美妆 | 商品信息-一级类目名称 |
| └ category_id | Number | 162201 | 商品信息-叶子类目id |
| └ category_name | String | 牛仔裤 | 商品信息-叶子类目名称 |
| └ seller_id | Number | 123 | 店铺信息-卖家id |
| └ user_type | Number | 1 | 店铺信息-卖家类型，0表示淘宝，1表示天猫，3表示特价版 |
| └ shop_title | String | 魔黛娅内衣旗舰店 | 店铺信息-店铺名称 |
| └ volume | Number | 30 | 商品信息-30天销量；数据统计截止昨日非实时更新 |
| └ sub_title | String | 吉品鲍鱼 关西参 | 商品信息-商品子标题 |
| └ brand_name | String | 淘宝心选 | 商品信息-品牌名称 |
| └ annual_vol | String | 1万+ | 年销量 |
| └ small_images | String

                                 [] |  | 商品信息-商品小图列表 |
| └ real_post_fee | String | 0.00 | 商品邮费 |
| └ price_promotion_info | PromotionInfoMapData |  | 价格促销信息 |
| └ reserve_price | String | 102.00 | 商品信息-一口价通常显示为划线价 |
| └ zk_final_price | String | 79.9 | 促销信息-销售价格，无促销时等于一口价，有促销时为促销价。若属于预售商品，付定金时间内，在线售卖价=预售价 |
| └ final_promotion_price | String | 69.9 | 促销信息-预估到手价(元)。若属于预售商品，付定金时间内，预估到手价价=定金+尾款的预估到手价 |
| └ final_promotion_path_list | FinalPromotionPathMapData

                                 [] |  | 到手价优惠路径列表 |
| └ promotion_title | String | 商品券 | 优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 满7999减1300 | 优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_fee | String | 1300.00 | 实际优惠金额（元） |
| └ promotion_start_time | String | 1661184000000 | 优惠开始时间 |
| └ promotion_end_time | String | 1661788799000 | 优惠结束时间 |
| └ promotion_id | String | xx | 优惠ID |
| └ future_activity_promotion_price | String | 99.5 | 预热预估到手价（元） |
| └ future_activity_promotion_path_list | FutureActivityPromotionPathMapData

                                 [] |  | 预热到手价优惠路径列表 |
| └ promotion_title | String | 商品券 | 预热优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 满7999减1300 | 预热优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_fee | String | 1300.00 | 预热实际优惠金额（元） |
| └ promotion_start_time | String | 1661184000000 | 优惠开始时间 |
| └ promotion_end_time | String | 1661788799000 | 优惠结束时间 |
| └ promotion_tag_list | PromotionTagMapData

                                 [] |  | 标签信息列表 |
| └ tag_name | String | 88VIP | 标签名称，如“88VIP”、“花呗免息”、“猫超买返”、“是否包邮” |
| └ predict_rounding_up_price | String | 56.1 | 促销信息-预估凑单价（元）。预估凑单叠加优惠后的商品单价 |
| └ predict_rounding_up_price_desc | String | 需买1件 | 促销信息-凑单价说明，描述凑单价的实现说明。如 “可凑单”或“需买X件” |
| └ more_promotion_list | MorePromotionMapData

                                 [] |  | 更多活动优惠 |
| └ promotion_title | String | 满件折 | 优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 2件9折 | 优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_start_time | String | 1661222400000 | 优惠开始时间 |
| └ promotion_end_time | String | 1662393600000 | 优惠结束时间 |
| └ promotion_id | String | xx | 优惠ID |
| └ promotion_total_count | Number | 1000 | 当天优惠总库存【指定优惠透出，不对外开放】 |
| └ promotion_url | String | https:// | 优惠使用路径【指定优惠透出，不对外开放】 |
| └ predict_rounding_up_path_list | PredictRoundingUpPathMapData

                                 [] |  | 预估凑单优惠路径 |
| └ promotion_title | String | 店铺优惠 | 优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 再买1件，可参与2件5折 | 优惠利益点文案，如“2件5折”、“每200减20”等 |
| └ gov_subsidy | GovSubsidyDTO |  | 国家补贴 |
| └ tag_name | String | 国家补贴 | 国家补贴 |
| └ state_subsidy_info | StateSubsidyInfo |  | 国补信息 |
| └ max_rebate | Number | 1 | 最高优惠比例（%），入参具体IP时，仅展示该IP最高优惠比例。 |
| └ min_rebate | Number | 1 | 最低优惠比例（%），入参具体IP时，仅展示该IP最低优惠比例。 |
| └ max_discount | String | 15.00 | 最高优惠金额（元，如15代表15 元），入参具体IP时，仅展示该IP最高优惠金额 |
| └ min_discount | String | 15.00 | 最低优惠金额（元，如15代表15 元），入参具体IP时，仅展示该IP最低优惠金额 |
| └ province_list | String

                                 [] |  | 国补生效区域（省份）。不入参IP时展示各可用省份；入参IP时，全国可用商品展示各可用省份，区域可用商品仅展示IP对应省份。 |
| └ publish_info | PublishInfo |  | 淘客推广信息 |
| └ income_rate | String | 5.50 | 商品信息-收入比率(%)；商品佣金比率+补贴比率 |
| └ click_url | String | //item.taobao.com/item.htm?id=556633720749&scm=1007.16190.92234.0&pvid=41362290-fa0b-4252-b172-6afc9c00e2c8&app_pvid=0ab0fac715095507006577956e | 链接-宝贝推广链接 |
| └ coupon_share_url | String | //uland.taobao.com/coupon/edetail?e=pR6YtnFKK%2B8GQASttHIRqcEWOmlidB03Pf45HLyCqA8dRAklSM5tEQ36hBQToU3M3MmLjFwLsqgZxcV7BPtHQDd2Naqom0e0&mt=1&app_pvid=0ab0fac715095507006577956e&ptl=app_pvid:0ab0fac715095507006577956e;tpp_pvid:41362290-fa0b-4252-b172-6afc9c00e2c8 | 链接-宝贝+券二合一页面链接 |
| └ sp_campaign_list | SpCampaign

                                 [] |  | 定向计划集合-仅支持联系商务或运营小二申请定向计划合集字段权限 |
| └ sp_cid | String | 123 | 定向计划活动ID |
| └ sp_name | String | 定向计划活动1 | 定向计划名称 |
| └ sp_rate | String | 1550表示15.5% | 定向佣金率 |
| └ sp_lock_status | String | 0 | 定向是否锁佣，0=不锁佣 1=锁佣 |
| └ sp_apply_link | String | http://pub.alimama.com/portal/promo/shop/campaign/detail.htm?mode=info&campaignId=1000492470&creatorId=98836808&breadcrumb=false | 定向计划申请链接 |
| └ sp_status | String | 1 | 定向计划是否可用 1-可用 0-不可用 |
| └ future_activity_commission_rate | String | 1550表示15.5% | 预热活动到手价对应的佣金比率 |
| └ future_activity_time | String | 1665504000000 | 预热价活动开始时间 |
| └ income_info | IncomeInfo |  | 商品佣金信息 |
| └ commission_rate | String | 55 | 商品佣金比率 |
| └ commission_amount | String | 12 | 商品佣金金额 |
| └ subsidy_rate | String | 11 | 补贴比率 |
| └ subsidy_amount | String | 4 | 补贴金额 |
| └ subsidy_upper_limit | String | 10 | 补贴上限；仅在单笔订单命中补贴上限时返回结果否则出参为空 |
| └ subsidy_type | String | 妈妈补贴 | 补贴类型 |
| └ cpa_reward_type | String | 0 1 2 | 额外奖励活动类型，如果一个商品有多个奖励类型，返回结果使用空格分割，0=预售单单奖励，1=618超级U选单单补 |
| └ cpa_reward_amount | String | 1.11 2.22 3.21 | 额外奖励活动金额，活动奖励金额的类型与cpa_reward_type字段对应，如果一个商品有多个奖励类型，返回结果使用空格分割 |
| └ include_dxjh | String | false | 商品是否包含定向计划 |
| └ two_hour_promotion_sales | Number | 24 | 两小时推广销量。 非实时，约半小时更新 |
| └ daily_promotion_sales | Number | 111 | 当天推广销量。 非实时，约1小时更新 |
| └ tmall_rank_info | TmallRankInfo |  | 天猫榜单信息 |
| └ tmall_rank_text | String | 白茶热销榜·第5名 | 榜单排行描述 |
| └ tmall_rank_url | String | https://pages.tmall.com/wow/a/act/tmall/dailygroup/16220/16661/wupr?wh_pid=daily-459438&disableNav=YES | 榜单url |
| └ presale_info | PresaleInfo |  | 预售信息 |
| └ presale_start_time | Number | 1567440000000 | 预售商品-付定金开始时间（毫秒） |
| └ presale_end_time | Number | 1567440000000 | 预售商品-付定金结束时间（毫秒） |
| └ presale_tail_start_time | Number | 1567440000000 | 预售商品-付尾款开始时间（毫秒） |
| └ presale_tail_end_time | Number | 1567440000000 | 预售商品-付尾款结束时间（毫秒） |
| └ presale_deposit | String | 100 | 预售商品-定金（元） |
| └ presale_discount_fee_text | String | 付定金立减5元 | 预售商品-优惠信息 |
| └ favorites_info | FavoritesInfo |  | 选品库信息 |
| └ total_count | Number | 100 | 选品库收藏夹总数量 |
| └ favorites_list | FavoritesDetail

                                 [] |  | 选品库收藏夹详细信息 |
| └ favorites_id | Number | 12334 | 选品库收藏夹id |
| └ favorites_title | String | 测试选品库 | 选品库收藏夹标题 |
| └ topn_info | TopNInfoDTO |  | 前N件佣金信息-前N件佣金生效或预热时透出以下字段 |
| └ topn_quantity | Number | 3000 | 前N件剩余库存 |
| └ topn_total_count | Number | 3000 | 前N件初始总库存 |
| └ topn_start_time | String | 1937297392332 | 前N件佣金开始时间 |
| └ topn_end_time | String | 1937297392332 | 前N件佣金结束时间 |
| └ topn_rate | String | 30 | 前N件佣金率 |
| └ scope_info | ScopeInfo |  | 商品库范围信息 |
| └ superior_brand | String | 1 | 是否品牌精选，0不是，1是 |
| is_default | String | false | 推荐信息-是否抄底 |
| total_count | Number | 100 | 商品总数-该选品库收藏夹id及官方物料id对应的商品数量 |
| uvid_msg | String | 123 | uvid结果信息，传入但未使用uvid时会返回原因 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.material.recommend', {
	'page_size':'20',
	'page_no':'1',
	'material_id':'123',
	'adzone_id':'123',
	'relation_id':'123456',
	'device_type':'IMEI',
	'device_encrypt':'MD5',
	'device_value':'xxx',
	'favorites_id':'123445',
	'promotion_type':'2',
	'special_id':'2323',
	'item_id':'qeqscd1231-uqwenqe'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_material_recommend_response":{
        "result_list":{
            "map_data":[
                {
                    "item_id":"qeqscd1231-uqwenqe",
                    "item_basic_info":{
                        "title":"复古女裤子秋冬九分裤萝卜裤显瘦高腰韩版2017新款",
                        "short_title":"九分裤显瘦高腰韩版",
                        "pict_url":"\/\/img.alicdn.com\/bao\/uploaded\/i4\/745957850\/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg",
                        "white_image":"https:\/\/img.alicdn.com\/bao\/uploaded\/i4\/745957850\/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg",
                        "level_one_category_id":1,
                        "level_one_category_name":"美妆",
                        "category_id":162201,
                        "category_name":"牛仔裤",
                        "seller_id":123,
                        "user_type":1,
                        "shop_title":"魔黛娅内衣旗舰店",
                        "volume":30,
                        "sub_title":"吉品鲍鱼 关西参",
                        "brand_name":"淘宝心选",
                        "annual_vol":"1万+",
                        "real_post_fee":"0.00"
                    },
                    "price_promotion_info":{
                        "reserve_price":"102.00",
                        "zk_final_price":"79.9",
                        "final_promotion_price":"69.9 ",
                        "final_promotion_path_list":{
                            "final_promotion_path_map_data":[
                                {
                                    "promotion_title":"商品券",
                                    "promotion_desc":"满7999减1300",
                                    "promotion_fee":"1300.00",
                                    "promotion_start_time":"1661184000000",
                                    "promotion_end_time":"1661788799000",
                                    "promotion_id":"xx"
                                }
                            ]
                        },
                        "future_activity_promotion_price":"99.5",
                        "future_activity_promotion_path_list":{
                            "future_activity_promotion_path_map_data":[
                                {
                                    "promotion_title":"商品券",
                                    "promotion_desc":"满7999减1300",
                                    "promotion_fee":"1300.00",
                                    "promotion_start_time":"1661184000000",
                                    "promotion_end_time":"1661788799000"
                                }
                            ]
                        },
                        "promotion_tag_list":{
                            "promotion_tag_map_data":[
                                {
                                    "tag_name":"88VIP"
                                }
                            ]
                        },
                        "predict_rounding_up_price":"56.1",
                        "predict_rounding_up_price_desc":"需买1件",
                        "more_promotion_list":{
                            "more_promotion_map_data":[
                                {
                                    "promotion_title":"满件折",
                                    "promotion_desc":"2件9折",
                                    "promotion_start_time":"1661222400000",
                                    "promotion_end_time":"1662393600000",
                                    "promotion_id":"xx",
                                    "promotion_total_count":1000,
                                    "promotion_url":"https:\/\/"
                                }
                            ]
                        },
                        "predict_rounding_up_path_list":{
                            "predict_rounding_up_path_map_data":[
                                {
                                    "promotion_title":"店铺优惠",
                                    "promotion_desc":"再买1件，可参与2件5折"
                                }
                            ]
                        },
                        "gov_subsidy":{
                            "tag_name":"国家补贴",
                            "state_subsidy_info":{
                                "max_rebate":1,
                                "min_rebate":1,
                                "max_discount":"15.00",
                                "min_discount":"15.00"
                            }
                        }
                    },
                    "publish_info":{
                        "income_rate":"5.50",
                        "click_url":"\/\/item.taobao.com\/item.htm?id=556633720749&scm=1007.16190.92234.0&pvid=41362290-fa0b-4252-b172-6afc9c00e2c8&app_pvid=0ab0fac715095507006577956e",
                        "coupon_share_url":"\/\/uland.taobao.com\/coupon\/edetail?e=pR6YtnFKK%2B8GQASttHIRqcEWOmlidB03Pf45HLyCqA8dRAklSM5tEQ36hBQToU3M3MmLjFwLsqgZxcV7BPtHQDd2Naqom0e0&mt=1&app_pvid=0ab0fac715095507006577956e&ptl=app_pvid:0ab0fac715095507006577956e;tpp_pvid:41362290-fa0b-4252-b172-6afc9c00e2c8",
                        "sp_campaign_list":{
                            "sp_campaign":[
                                {
                                    "sp_cid":"123",
                                    "sp_name":"定向计划活动1",
                                    "sp_rate":"1550表示15.5%",
                                    "sp_lock_status":"0",
                                    "sp_apply_link":"http:\/\/pub.alimama.com\/portal\/promo\/shop\/campaign\/detail.htm?mode=info&campaignId=1000492470&creatorId=98836808&breadcrumb=false",
                                    "sp_status":"1"
                                }
                            ]
                        },
                        "future_activity_commission_rate":"1550表示15.5%",
                        "future_activity_time":"1665504000000",
                        "income_info":{
                            "commission_rate":"55",
                            "commission_amount":"12",
                            "subsidy_rate":"11",
                            "subsidy_amount":"4",
                            "subsidy_upper_limit":"10",
                            "subsidy_type":"妈妈补贴"
                        },
                        "cpa_reward_type":"0 1 2",
                        "cpa_reward_amount":"1.11 2.22 3.21",
                        "include_dxjh":"false",
                        "two_hour_promotion_sales":24,
                        "daily_promotion_sales":111
                    },
                    "tmall_rank_info":{
                        "tmall_rank_text":"白茶热销榜·第5名",
                        "tmall_rank_url":"https:\/\/pages.tmall.com\/wow\/a\/act\/tmall\/dailygroup\/16220\/16661\/wupr?wh_pid=daily-459438&disableNav=YES"
                    },
                    "presale_info":{
                        "presale_start_time":1567440000000,
                        "presale_end_time":1567440000000,
                        "presale_tail_start_time":1567440000000,
                        "presale_tail_end_time":1567440000000,
                        "presale_deposit":"100",
                        "presale_discount_fee_text":"付定金立减5元"
                    },
                    "favorites_info":{
                        "total_count":100,
                        "favorites_list":{
                            "favorites_detail":[
                                {
                                    "favorites_id":12334,
                                    "favorites_title":"测试选品库"
                                }
                            ]
                        }
                    },
                    "topn_info":{
                        "topn_quantity":3000,
                        "topn_total_count":3000,
                        "topn_start_time":"1937297392332",
                        "topn_end_time":"1937297392332",
                        "topn_rate":"30"
                    },
                    "scope_info":{
                        "superior_brand":"1"
                    }
                }
            ]
        },
        "is_default":"false",
        "total_count":100,
        "uvid_msg":"123"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.seed.wb.crowd.get（淘宝客-推广者-内容种草人群包数据查询）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| page_no | Number | 必须 | 1 |  | 固定值=1 |
| page_size | Number | 必须 | 100 |  | 分页，大小可变 |
| filters | String | 必须 | bTaskId=12346,hasCount=false,positionIndex=123 |  | bTaskId(联盟任务id),hasCount(是否返回总数),positionIndex(位点信息) |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | WbCrowdInfoDTO |  | 返回对象 |
| └ event_info | CpaEventInfoDTO |  | 活动信息 |
| └ b_task_id | Number | 22546 | 联盟任务id |
| └ start_time | Date | 2022-04-24 15:06:09 | 任务开始时间 |
| └ end_time | Date | 2022-04-24 15:06:09 | 任务结束时间 |
| └ page_info | PageInfoDTO |  | 分页信息 |
| └ total | Number | 222 | 总数 |
| └ page_no | Number | 1 | 页码 |
| └ page_size | Number | 100 | 页容 |
| └ data_list | String

                                 [] |  | 人群列表 |
| └ position_index | String | 111 | 位点信息 |
| result_code | Number | 200 | 返回码 |
| biz_error_code | Number | 0 | 错误描述 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.seed.wb.crowd.get', {
	'page_no':'1',
	'page_size':'100',
	'filters':'bTaskId=12346,hasCount=false,positionIndex=123'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_seed_wb_crowd_get_response":{
        "data":{
            "event_info":{
                "b_task_id":22546,
                "start_time":"2022-04-24 15:06:09",
                "end_time":"2022-04-24 15:06:09"
            },
            "page_info":{
                "total":222,
                "page_no":1,
                "page_size":100
            },
            "position_index":"111"
        },
        "result_code":200,
        "biz_error_code":0
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.content.order.get（淘宝客-推广者-内容ID订单汇总）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| cont_id | String | 必须 | 123 |  | 内容id |
| q_time | String | 必须 | 2022-05-22 15:00:00 |  | 小时粒度，查询的订单截止时间 备注查询周期范围：在自然月开始第一天0点到当前入参的查询截止时间 |
| page_size | Number | 可选 | 20 | 默认值：20 | 页大小，默认20，1~20 |
| page_no | Number | 可选 | 1 | 默认值：1 | 页码，起始值为1 |
| adzone_id | String | 可选 | 1 |  | 媒体的adzone_id |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result | RpcResult |  | 接口返回值 |
| └ data | OrderPage |  | 接口返回数据 |
| └ has_next | Boolean | false | 是否还有下一页 |
| └ result | ContentOrderDTO |  | 内容订单数据 |
| └ cont_id | String | 123 | 内容ID |
| └ alipay_amt | String | 100 | 按内容ID，汇总每笔订单买家拍下付款的金额（不包含运费金额） |
| └ confirm_amt | String | 100 | 按内容ID，汇总每笔订单确认收货金额 |
| └ settle_amt | String | 100 | 按内容ID，汇总每笔订单确认结算金额 |
| └ click_uv | String | 80 | 查询周期内，按内容ID，联盟口径点击人数UV |
| └ payment_info | ContentPayment |  | 订单明细信息 |
| └ tb_paid_times | String | 2022-04-22 15:15:05 | 订单在淘宝拍下付款的时间，多个订单逗号分割 |
| └ item_leaf_category_names | String | 女装 | 订单商品叶子类目名称，多个订单逗号分割 |
| └ item_titles | String | 连衣裙 | 订单商品标题，多个订单逗号分割 |
| └ item_id | String | 12345 | 商品id，根据订单id决定是否生成营销id |
| └ item_first_category_names | String | 3C数码配件 | 商品一级类目 |
| └ item_second_category_names | String | MP3/MP4配件 | 商品二级类目 |
| └ alipay_uv | String | 2 | 汇总每笔订单成交uv |
| └ alipay_order_cnt | String | 2 | 拍下订单数 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.content.order.get', {
	'cont_id':'123',
	'q_time':'2022-05-22 15:00:00',
	'page_size':'20',
	'page_no':'1',
	'adzone_id':'1'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_content_order_get_response":{
        "result":{
            "data":{
                "has_next":false,
                "result":{
                    "cont_id":"123",
                    "alipay_amt":"100",
                    "confirm_amt":"100",
                    "settle_amt":"100",
                    "click_uv":"80",
                    "payment_info":{
                        "tb_paid_times":"2022-04-22 15:15:05",
                        "item_leaf_category_names":"女装",
                        "item_titles":"连衣裙",
                        "item_id":"12345",
                        "item_first_category_names":"3C数码配件",
                        "item_second_category_names":"MP3\/MP4配件"
                    },
                    "alipay_uv":"2",
                    "alipay_order_cnt":"2"
                }
            }
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.material.optional.upgrade（淘宝客-推广者-物料搜索升级版）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| start_dsr | Number | 可选 | 10 |  | 商品筛选-店铺dsr评分。筛选大于等于当前设置的店铺dsr评分的商品0-50000之间 |
| page_size | Number | 可选 | 20 | 默认值：20 | 页大小，默认20，1~100 |
| page_no | Number | 可选 | 1 | 默认值：1 | 第几页，默认：１ |
| end_tk_rate | Number | 可选 | 1234 |  | 商品筛选-淘客收入比率上限(商品佣金比率+补贴比率)。如：1234表示12.34% |
| start_tk_rate | Number | 可选 | 1234 |  | 商品筛选-淘客收入比率下限(商品佣金比率+补贴比率)。如：1234表示12.34% |
| end_price | Number | 可选 | 10 |  | 商品筛选-预估到手价范围上限。单位：元 |
| start_price | Number | 可选 | 10 |  | 商品筛选-预估到手价范围下限。单位：元 |
| is_overseas | Boolean | 可选 | false |  | 商品筛选-是否海外商品。true表示属于海外商品，false或不设置表示不限 |
| is_tmall | Boolean | 可选 | false |  | 商品筛选-是否天猫商品。true表示属于天猫商品，false或不设置表示不限 |
| sort | String | 可选 | tk_rate_des |  | 排序_des（降序），排序_asc（升序），销量（total_sales），淘客收入比率（tk_rate），营销计划佣金（tk_mkt_rate）， 累计推广量（tk_total_sales），总支出佣金（tk_total_commi），预估到价格（final_promotion_price），匹配分（match） |
| itemloc | String | 可选 | 杭州 |  | 商品筛选-所在地 |
| cat | String | 可选 | 16,18 |  | 商品筛选-后台类目ID。用,分割，最大10个 |
| q | String | 可选 | 女装 |  | 商品筛选-查询词；注意：① q参数不支持入参淘宝联盟链接；② 淘宝复制商品含数字ID的链接需消费者比价场景ID2权限；③ 使用标题搜索时，如搜索出来的商品仅有一个，则需要消费者比价场景ID2权限，否则不透出商品推广链接和商品id字段；如搜索出来的商品有多个，则不受权限影响正常出参。(场景id使用说明参考《淘宝客新商品ID升级》白皮书：https://www.yuque.com/taobaolianmengguanfangxiaoer/zmig94/tfyt0pahmlpzu2ud) |
| material_id | Number | 可选 | 80309 | 默认值：80309 | 物料id，不传时默认物料material_id=80309；如果直接对消费者投放，可使用官方个性化算法优化的搜索物料material_id=17004（注意：若物料id=17004没查询到结果则出系统默认物料id=80309的查询结果） |
| has_coupon | Boolean | 可选 | false |  | 优惠券筛选-是否有优惠券。true表示该商品有优惠券，false或不设置表示不限 |
| ip | String | 可选 | 13.2.33.4 |  | ip参数影响邮费获取，如果不传或者传入不准确，邮费无法精准提供 |
| adzone_id | Number | 必须 | 12345678 |  | 推广位id，mm_xxx_xxx_12345678三段式的最后一段数字（登录pub.alimama.com推广管理-推广位管理中查询） |
| need_free_shipment | Boolean | 可选 | true |  | 商品筛选-是否包邮。true表示包邮，false或不设置表示不限 |
| need_prepay | Boolean | 可选 | true |  | 商品筛选-是否加入消费者保障。true表示加入，false或不设置表示不限 |
| include_pay_rate_30 | Boolean | 可选 | true |  | 商品筛选-成交转化是否高于行业均值。True表示大于等于，false或不设置表示不限 |
| include_good_rate | Boolean | 可选 | true |  | 商品筛选-好评率是否高于行业均值。True表示大于等于，false或不设置表示不限 |
| include_rfd_rate | Boolean | 可选 | true |  | 商品筛选-退款率是否低于行业均值。True表示大于等于，false或不设置表示不限 |
| npx_level | Number | 可选 | 2 | 默认值：1 | 商品筛选-牛皮癣程度。取值：1不限，2无，3轻微 |
| device_encrypt | String | 可选 | MD5 |  | 智能匹配-设备号加密类型：MD5；使用智能推荐请先签署协议https://pub.alimama.com/fourth/protocol/common.htm?key=hangye_laxin |
| device_value | String | 可选 | xxx |  | 智能匹配-设备号加密后的值（MD5加密需32位小写）；使用智能推荐请先签署协议https://pub.alimama.com/fourth/protocol/common.htm?key=hangye_laxin |
| device_type | String | 可选 | IMEI |  | 智能匹配-设备号类型：IMEI，或者IDFA，或者UTDID（UTDID不支持MD5加密），或者OAID；使用智能推荐请先签署协议https://pub.alimama.com/fourth/protocol/common.htm?key=hangye_laxin |
| special_id | String | 可选 | 2323 |  | 会员运营ID |
| relation_id | String | 可选 | 3243 |  | 渠道关系ID，仅适用于渠道推广场景 |
| get_topn_rate | Number | 可选 | 0 |  | 是否获取前N件佣金信息	0否，1是，其他值否 |
| biz_scene_id | String | 可选 | 1 |  | 1-动态ID转链场景，2-消费者比价场景（不填默认为1）；场景id使用说明参考《淘宝客新商品ID升级》白皮书：https://www.yuque.com/taobaolianmengguanfangxiaoer/zmig94/tfyt0pahmlpzu2ud |
| promotion_type | String | 可选 | 2 |  | 1-自购省，2-推广赚（代理模式专属ID，代理模式必填，非代理模式不用填写该字段） |
| mgc_start_time | String | 可选 | 1695281620000 |  | 线报内容筛选—内容生产开始时间，13毫秒时间戳 |
| mgc_end_time | String | 可选 | 1695281620000 |  | 线报内容筛选—内容生产截止时间，13毫秒时间戳 |
| mgc_status | String | 可选 | 0 |  | 线报状态筛选，0-全部 1-过期 2-实时生效 3-未来生效 不传默认过滤有效 |
| ucrowd_id | Number | 可选 | 1 |  | 人群ID，仅适用于物料评估场景material_id=41377 |
| ucrowd_rank_items | Ucrowdrankitems | 可选 |  |  | 物料评估-商品列表 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| total_results | Number | 1212 | 搜索到符合条件的结果总数 |
| result_list | MapData [] |  | resultList |
| └ item_id | String | qeqscd1231-uqwenqe | 商品信息-淘宝客新商品id；使用说明参考《淘宝客新商品ID升级》白皮书：https://www.yuque.com/taobaolianmengguanfangxiaoer/zmig94/tfyt0pahmlpzu2ud |
| └ publish_info | PublishInfo |  | 淘客推广信息 |
| └ income_rate | String | 5.50 | 商品信息-收入比率(%)；商品佣金比率+补贴比率 |
| └ topn_info | TopNInfoDTO |  | 前N件佣金信息-前N件佣金生效或预热时透出以下字段 |
| └ topn_quantity | Number | 3000 | 前N件剩余库存 |
| └ topn_total_count | Number | 3000 | 前N件初始总库存 |
| └ topn_end_time | String | 1937297392332 | 前N件佣金结束时间 |
| └ topn_start_time | String | 1937297392332 | 前N件佣金开始时间 |
| └ topn_rate | String | 30 | 前N件佣金率 |
| └ click_url | String | //item.taobao.com/item.htm?id=556633720749&scm=1007.16190.92234.0&pvid=41362290-fa0b-4252-b172-6afc9c00e2c8&app_pvid=0ab0fac715095507006577956e | 链接-宝贝推广链接 |
| └ coupon_share_url | String | //uland.taobao.com/coupon/edetail?e=pR6YtnFKK%2B8GQASttHIRqcEWOmlidB03Pf45HLyCqA8dRAklSM5tEQ36hBQToU3M3MmLjFwLsqgZxcV7BPtHQDd2Naqom0e0&mt=1&app_pvid=0ab0fac715095507006577956e&ptl=app_pvid:0ab0fac715095507006577956e;tpp_pvid:41362290-fa0b-4252-b172-6afc9c00e2c8 | 链接-宝贝+券二合一页面链接 |
| └ future_activity_commission_rate | String | 1550表示15.5% | 预热活动到手价对应的佣金比率 |
| └ future_activity_time | String | 1665504000000 | 预热价活动开始时间 |
| └ sp_campaign_list | SpCampaign

                                 [] |  | 定向计划集合-仅支持联系商务或运营小二申请定向计划合集字段权限 |
| └ sp_cid | String | 123 | 定向计划活动ID |
| └ sp_name | String | 定向计划活动1 | 定向计划名称 |
| └ sp_rate | String | 1550表示15.5% | 定向佣金率 |
| └ sp_lock_status | String | 0 | 定向是否锁佣，0=不锁佣 1=锁佣 |
| └ sp_apply_link | String | http://pub.alimama.com/portal/promo/shop/campaign/detail.htm?mode=info&campaignId=1000492470&creatorId=98836808&breadcrumb=false | 定向计划申请链接 |
| └ sp_status | String | 1 | 定向计划是否可用 1-可用 0-不可用 |
| └ rank_page_url | String | s.click.xxx | 榜单url |
| └ commission_type | String | MKT表示营销计划，SP表示定向计划，COMMON表示通用计划 | 推广信息-商品信息-佣金类型。MKT表示营销计划，SP表示定向计划，COMMON表示通用计划，ZX表示自选计划 |
| └ income_info | FinalIncomeInfo |  | 商品佣金信息 |
| └ commission_rate | String | 55 | 商品佣金比率 |
| └ commission_amount | String | 12 | 商品佣金金额 |
| └ subsidy_rate | String | 11 | 补贴比率 |
| └ subsidy_amount | String | 4 | 补贴金额 |
| └ subsidy_upper_limit | String | 10 | 补贴上限；仅在单笔订单命中补贴上限时返回结果否则出参为空 |
| └ subsidy_type | String | 妈妈补贴 | 补贴类型 |
| └ cpa_reward_type | String | 0 1 2 | 额外奖励活动类型，如果一个商品有多个奖励类型，返回结果使用空格分割，0=预售单单奖励，1=618超级U选单单补 |
| └ cpa_reward_amount | String | 1.11 2.22 3.21 | 额外奖励活动金额，活动奖励金额的类型与cpa_reward_type字段对应，如果一个商品有多个奖励类型，返回结果使用空格分割 |
| └ include_dxjh | String | false | 商品是否包含定向计划 |
| └ two_hour_promotion_sales | Number | 24 | 两小时推广销量。 非实时，约半小时更新 |
| └ daily_promotion_sales | Number | 111 | 当天推广销量。 非实时，约1小时更新 |
| └ price_promotion_info | PromotionInfoMapData |  | 价格促销信息 |
| └ predict_rounding_up_price | String | 56.1 | 促销信息-预估凑单价（元）。预估凑单叠加优惠后的商品单价 |
| └ predict_rounding_up_price_desc | String | 需买1件 | 促销信息-凑单价说明，描述凑单价的实现说明。如 “可凑单”或“需买X件” |
| └ more_promotion_list | MorePromotionMapData

                                 [] |  | 更多活动优惠 |
| └ promotion_title | String | 满件折 | 优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 2件9折 | 优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_start_time | String | 1661222400000 | 优惠开始时间 |
| └ promotion_end_time | String | 1662393600000 | 优惠结束时间 |
| └ promotion_id | String | xx | 优惠ID |
| └ promotion_total_count | Number | 1000 | 当天优惠总库存【指定优惠透出，不对外开放】 |
| └ promotion_url | String | https:// | 优惠使用路径【指定优惠透出，不对外开放】 |
| └ reserve_price | String | 102.00 | 商品信息-一口价通常显示为划线价 |
| └ zk_final_price | String | 79.9 | 促销信息-销售价格，无促销时等于一口价，有促销时为促销价。若属于预售商品，付定金时间内，在线售卖价=预售价 |
| └ final_promotion_price | String | 69.9 | 促销信息-预估到手价(元)。若属于预售商品，付定金时间内，预估到手价价=定金+尾款的预估到手价 |
| └ final_promotion_path_list | FinalPromotionPathMapData

                                 [] |  | 到手价优惠路径列表 |
| └ promotion_title | String | 商品券 | 优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 满7999减1300 | 优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_fee | String | 1300.00 | 实际优惠金额（元） |
| └ promotion_start_time | String | 1661184000000 | 优惠开始时间 |
| └ promotion_end_time | String | 1661788799000 | 优惠结束时间 |
| └ promotion_id | String | xx | 优惠ID |
| └ future_activity_promotion_price | String | 99.5 | 预热预估到手价（元） |
| └ future_activity_promotion_path_list | FutureActivityPromotionPathMapData

                                 [] |  | 预热到手价优惠路径列表 |
| └ promotion_title | String | 商品券 | 优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 满7999减1300 | 预热优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_fee | String | 1300.00 | 预热实际优惠金额（元） |
| └ promotion_start_time | String | 1661184000000 | 优惠开始时间 |
| └ promotion_end_time | String | 1661788799000 | 优惠结束时间 |
| └ promotion_tag_list | PromotionTagMapData

                                 [] |  | 标签信息列表 |
| └ tag_name | String | 88VIP | 标签名称，如“88VIP”、“花呗免息”、“猫超买返”、“是否包邮” |
| └ gov_subsidy | GovSubsidyDTO |  | 国家补贴 |
| └ tag_name | String | 国家补贴 | 国家补贴 |
| └ state_subsidy_info | StateSubsidyInfo |  | 国补信息 |
| └ max_rebate | Number | 1 | 最高优惠比例（%），入参具体IP时，仅展示该IP最高优惠比例。 |
| └ min_rebate | Number | 1 | 最低优惠比例（%），入参具体IP时，仅展示该IP最低优惠比例。 |
| └ max_discount | String | 15.00 | 最高优惠金额（元，如15代表15 元），入参具体IP时，仅展示该IP最高优惠金额 |
| └ min_discount | String | 15.00 | 最低优惠金额（元，如15代表15 元），入参具体IP时，仅展示该IP最低优惠金额 |
| └ province_list | String

                                 [] |  | 国补生效区域（省份）。不入参IP时展示各可用省份；入参IP时，全国可用商品展示各可用省份，区域可用商品仅展示IP对应省份。 |
| └ item_basic_info | BasicMapData |  | 商品基础信息 |
| └ title | String | 复古女裤子秋冬九分裤萝卜裤显瘦高腰韩版2017新款 | 商品信息-商品标题 |
| └ short_title | String | 九分裤显瘦高腰韩版 | 商品信息-商品短标题 |
| └ pict_url | String | //img.alicdn.com/bao/uploaded/i4/745957850/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg | 商品信息-商品主图 |
| └ white_image | String | https://img.alicdn.com/bao/uploaded/i4/745957850/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg | 商品信息-商品白底图 |
| └ level_one_category_id | Number | 1 | 商品信息-一级类目ID |
| └ category_id | Number | 162201 | 商品信息-叶子类目id |
| └ category_name | String | 牛仔裤 | 商品信息-叶子类目名称 |
| └ seller_id | Number | 123 | 店铺信息-卖家id |
| └ user_type | Number | 1 | 店铺信息-卖家类型，0表示淘宝，1表示天猫，3表示特价版 |
| └ shop_title | String | 魔黛娅内衣旗舰店 | 店铺信息-店铺名称 |
| └ volume | Number | 30 | 商品信息-30天销量；数据统计截止昨日非实时更新 |
| └ sub_title | String | 吉品鲍鱼 关西参 | 商品信息-商品子标题 |
| └ brand_name | String | 淘宝心选 | 商品信息-品牌名称 |
| └ level_one_category_name | String | 美妆 | 商品信息-一级类目名称 |
| └ tk_total_sales | String | 11 | 商品信息-淘客30天推广量 |
| └ provcity | String | 浙江 杭州 | 商品信息-宝贝所在地 |
| └ small_images | String

                                 [] |  | 商品信息-商品小图列表 |
| └ annual_vol | String | 1万+ | 年销量 |
| └ real_post_fee | String | 0.00 | 商品邮费 |
| └ tmall_rank_info | TmallRankInfo |  | 天猫榜单信息 |
| └ tmall_rank_text | String | 白茶热销榜·第5名 | 榜单排行描述 |
| └ tmall_rank_url | String | https://pages.tmall.com/wow/a/act/tmall/dailygroup/16220/16661/wupr?wh_pid=daily-459438&disableNav=YES | 榜单url |
| └ presale_info | PresaleInfo |  | 预售信息 |
| └ presale_start_time | Number | 1567440000000 | 预售商品-付定金开始时间（毫秒） |
| └ presale_end_time | Number | 1567440000000 | 预售商品-付定金结束时间（毫秒） |
| └ presale_tail_start_time | Number | 1567440000000 | 预售商品-付尾款开始时间（毫秒） |
| └ presale_tail_end_time | Number | 1567440000000 | 预售商品-付尾款结束时间（毫秒） |
| └ presale_deposit | String | 100 | 预售商品-定金（元） |
| └ presale_discount_fee_text | String | 付定金立减5元 | 预售商品-优惠信息 |
| └ scope_info | ScopeInfo |  | 商品库范围信息 |
| └ superior_brand | String | 1 | 是否品牌精选，0不是，1是 |
| └ mgc_info | MgcInfo |  | 线报内容 |
| └ price | String | 0.66 | 价格 |
| └ price_desc | String | xxx | 价格描述 |
| └ promotion_summary | String | xxx | 文案 |
| └ publish_time | String | 1695265124771 | 发布时间，13位毫秒时间戳 |
| └ valid_time | String | 0 | 生效时间，实时线报为0，未来线报为13位毫秒时间戳 |
| └ match_score | String | 10.0 | 物料评估-匹配分 |
| └ commi_score | String | 20.0 | 物料评估-收益分 |
| uvid_msg | String | 123 | uvid结果信息，传入但未使用uvid时会返回原因 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.material.optional.upgrade', {
	'start_dsr':'10',
	'page_size':'20',
	'page_no':'1',
	'end_tk_rate':'1234',
	'start_tk_rate':'1234',
	'end_price':'10',
	'start_price':'10',
	'is_overseas':'false',
	'is_tmall':'false',
	'sort':'tk_rate_des',
	'itemloc':'杭州',
	'cat':'16,18',
	'q':'女装',
	'material_id':'80309',
	'has_coupon':'false',
	'ip':'13.2.33.4',
	'adzone_id':'12345678',
	'need_free_shipment':'true',
	'need_prepay':'true',
	'include_pay_rate_30':'true',
	'include_good_rate':'true',
	'include_rfd_rate':'true',
	'npx_level':'2',
	'device_encrypt':'MD5',
	'device_value':'xxx',
	'device_type':'IMEI',
	'special_id':'2323',
	'relation_id':'3243',
	'get_topn_rate':'0',
	'biz_scene_id':'1',
	'promotion_type':'2',
	'mgc_start_time':'1695281620000',
	'mgc_end_time':'1695281620000',
	'mgc_status':'0',
	'ucrowd_id':'1',
	'ucrowd_rank_items':'数据结构JSON示例'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_material_optional_upgrade_response":{
        "total_results":1212,
        "result_list":{
            "map_data":[
                {
                    "item_id":"qeqscd1231-uqwenqe",
                    "publish_info":{
                        "income_rate":"5.50",
                        "topn_info":{
                            "topn_quantity":3000,
                            "topn_total_count":3000,
                            "topn_end_time":"1937297392332",
                            "topn_start_time":"1937297392332",
                            "topn_rate":"30"
                        },
                        "click_url":"\/\/item.taobao.com\/item.htm?id=556633720749&scm=1007.16190.92234.0&pvid=41362290-fa0b-4252-b172-6afc9c00e2c8&app_pvid=0ab0fac715095507006577956e",
                        "coupon_share_url":"\/\/uland.taobao.com\/coupon\/edetail?e=pR6YtnFKK%2B8GQASttHIRqcEWOmlidB03Pf45HLyCqA8dRAklSM5tEQ36hBQToU3M3MmLjFwLsqgZxcV7BPtHQDd2Naqom0e0&mt=1&app_pvid=0ab0fac715095507006577956e&ptl=app_pvid:0ab0fac715095507006577956e;tpp_pvid:41362290-fa0b-4252-b172-6afc9c00e2c8",
                        "future_activity_commission_rate":"1550表示15.5%",
                        "future_activity_time":"1665504000000",
                        "sp_campaign_list":{
                            "sp_campaign":[
                                {
                                    "sp_cid":"123",
                                    "sp_name":"定向计划活动1",
                                    "sp_rate":"1550表示15.5%",
                                    "sp_lock_status":"0",
                                    "sp_apply_link":"http:\/\/pub.alimama.com\/portal\/promo\/shop\/campaign\/detail.htm?mode=info&campaignId=1000492470&creatorId=98836808&breadcrumb=false",
                                    "sp_status":"1"
                                }
                            ]
                        },
                        "rank_page_url":"s.click.xxx",
                        "commission_type":"MKT表示营销计划，SP表示定向计划，COMMON表示通用计划",
                        "income_info":{
                            "commission_rate":"55",
                            "commission_amount":"12",
                            "subsidy_rate":"11",
                            "subsidy_amount":"4",
                            "subsidy_upper_limit":"10",
                            "subsidy_type":"妈妈补贴"
                        },
                        "cpa_reward_type":"0 1 2",
                        "cpa_reward_amount":"1.11 2.22 3.21",
                        "include_dxjh":"false",
                        "two_hour_promotion_sales":24,
                        "daily_promotion_sales":111
                    },
                    "price_promotion_info":{
                        "predict_rounding_up_price":"56.1",
                        "predict_rounding_up_price_desc":"需买1件",
                        "more_promotion_list":{
                            "more_promotion_map_data":[
                                {
                                    "promotion_title":"满件折",
                                    "promotion_desc":"2件9折",
                                    "promotion_start_time":"1661222400000",
                                    "promotion_end_time":"1662393600000",
                                    "promotion_id":"xx",
                                    "promotion_total_count":1000,
                                    "promotion_url":"https:\/\/"
                                }
                            ]
                        },
                        "reserve_price":"102.00",
                        "zk_final_price":"79.9",
                        "final_promotion_price":"69.9",
                        "final_promotion_path_list":{
                            "final_promotion_path_map_data":[
                                {
                                    "promotion_title":"商品券 \t",
                                    "promotion_desc":"满7999减1300",
                                    "promotion_fee":"1300.00",
                                    "promotion_start_time":"1661184000000",
                                    "promotion_end_time":"1661788799000",
                                    "promotion_id":"xx"
                                }
                            ]
                        },
                        "future_activity_promotion_price":"99.5",
                        "future_activity_promotion_path_list":{
                            "future_activity_promotion_path_map_data":[
                                {
                                    "promotion_title":"商品券",
                                    "promotion_desc":"满7999减1300",
                                    "promotion_fee":"1300.00",
                                    "promotion_start_time":"1661184000000",
                                    "promotion_end_time":"1661788799000"
                                }
                            ]
                        },
                        "promotion_tag_list":{
                            "promotion_tag_map_data":[
                                {
                                    "tag_name":"88VIP"
                                }
                            ]
                        },
                        "gov_subsidy":{
                            "tag_name":"国家补贴",
                            "state_subsidy_info":{
                                "max_rebate":1,
                                "min_rebate":1,
                                "max_discount":"15.00",
                                "min_discount":"15.00"
                            }
                        }
                    },
                    "item_basic_info":{
                        "title":"复古女裤子秋冬九分裤萝卜裤显瘦高腰韩版2017新款",
                        "short_title":"九分裤显瘦高腰韩版",
                        "pict_url":"\/\/img.alicdn.com\/bao\/uploaded\/i4\/745957850\/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg",
                        "white_image":"https:\/\/img.alicdn.com\/bao\/uploaded\/i4\/745957850\/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg",
                        "level_one_category_id":1,
                        "category_id":162201,
                        "category_name":"牛仔裤",
                        "seller_id":123,
                        "user_type":1,
                        "shop_title":"魔黛娅内衣旗舰店",
                        "volume":30,
                        "sub_title":"吉品鲍鱼 关西参",
                        "brand_name":"淘宝心选",
                        "level_one_category_name":"美妆",
                        "tk_total_sales":"11",
                        "provcity":"浙江 杭州",
                        "annual_vol":"1万+",
                        "real_post_fee":"0.00"
                    },
                    "tmall_rank_info":{
                        "tmall_rank_text":"白茶热销榜·第5名",
                        "tmall_rank_url":"https:\/\/pages.tmall.com\/wow\/a\/act\/tmall\/dailygroup\/16220\/16661\/wupr?wh_pid=daily-459438&disableNav=YES"
                    },
                    "presale_info":{
                        "presale_start_time":1567440000000,
                        "presale_end_time":1567440000000,
                        "presale_tail_start_time":1567440000000,
                        "presale_tail_end_time":1567440000000,
                        "presale_deposit":"100",
                        "presale_discount_fee_text":"付定金立减5元"
                    },
                    "scope_info":{
                        "superior_brand":"1"
                    },
                    "mgc_info":{
                        "price":"0.66",
                        "price_desc":"xxx",
                        "promotion_summary":"xxx",
                        "publish_time":"1695265124771",
                        "valid_time":"0"
                    },
                    "match_score":" 10.0",
                    "commi_score":"20.0"
                }
            ]
        },
        "uvid_msg":"123"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| 1001 |  | 传入正确的me参数值，含有券ID与商品ID信息 |
| 10000 |  | 更换新的itemId查询 |
| 4 |  | 查询不到对应的adzoneId，请检查adzoneId是否正确 |
| 30002 |  | 参数q与cat不能都为空 |
| 2 |  | pid不正确，请检查是否输入了正确的adzoneId和siteId |
| 50001 |  | 更换查询条件 |
| 40001 |  | 请稍后重试 |
| 30001 |  | 请传入有效的物料ID |
| 5 |  | 检查pid相关参数，稍后重试 |
| isp.entry-sys-error |  | 稍后重试 |
| isp.pid-check-error |  | 检查pid相关参数，稍后重试 |
| isp.sys-error |  | 稍后重试 |
| 50002 |  | 调用频率高，请稍后再试 |
| 1201 |  | 请重试 |
| 719 |  | 请重试。另同步重要通知：您需将商品ID字段类型调整为同时兼容number和string类型，否则8月8日起调用将会出现异常，如已调整完成可忽略本次错误提示，点击https://mo.m.taobao.com/union/page_20220701_150002_297 查看公告详情，如有疑问可加入【淘宝联盟】线上合规升级咨询群（钉钉群：44748908）进行咨询。 |
| 1911 |  | 该appkey没有本sceneId权限，如有需要请联系对口商务/运营申请（钉钉咨询群号：44964951） |

---
##taobao.tbk.order.refund.get（淘宝客-推广者-全量售后退款订单查询）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| publisher_refund_order_query_option | PublisherRefundOrderQueryOption | 可选 |  |  | 全量维权订单查询入参 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | OrderPage |  | 返回数据 |
| └ result | PublisherRefundOrderDTO

                                 [] |  | 真正的业务数据结构 |
| └ refund_suit_id | String | 12345 | 维权编号，是当前订单发生维权退款的编号，非淘宝订单编号，如订单发生多次维权，则会产生多个维权编号 |
| └ tb_trade_parent_id | String | 1707359271433894971 | 淘宝父订单编号(买家在淘宝后台显示的订单编号) |
| └ tb_trade_id | String | 1707359271433894971 | 淘宝子订单编号 |
| └ tb_trade_create_time | String | 2022-10-19 14:33:06 | 订单创建时间 |
| └ earning_time | String | 2022-10-19 14:39:31 | 订单结算时间 |
| └ tk_refund_time | String | 2022-10-19 14:41:22 | 维权创建时间 |
| └ tk_refund_suit_time | String | 2022-10-19 14:42:29 | 维权完成时间 |
| └ modified_time | String | 2022-10-20 03:26:23 | 订单更新时间 |
| └ item_title | String | zf测试商品003商品，测试请不要拍 | 商品标题 |
| └ tk_order_role | String | 二方 | 推广者角色(二方、三方) |
| └ refund_status | Number | 2 | 维权创建(淘客结算回执) 4, 维权成功(淘客结算回执) 2, 维权失败(淘客结算回执) 3, 发生多次维权，待处理 11, 从淘客处补扣（钱已结给淘客） 等待扣款 12, 从淘客处补扣（钱已结给淘客） 扣款成功 13, 从卖家处补扣（钱已结给卖家） 等待扣款 14, 从卖家处补扣（钱已结给卖家） 扣款成功 15 |
| └ tb_trade_finish_price | String | 5.00 | 结算金额(订单确认收货后的成交金额） |
| └ refund_fee | String | 3.50 | 维权金额(买家申请维权退款的金额) |
| └ pub_share_fee | String | 1.10 | 结算预估收入=结算金额*提成。以订单确认收货后的成交金额为基数，预估您可能获得的收入。 |
| └ tk_commission_fee_refund | String | 0.71 | 应退还佣金(不含技术服务费和渠道专项服务费) |
| └ tk_subsidy_fee_refund | String | 0 | 应退还补贴(不含技术服务费和渠道专项服务费) |
| └ tk_commission_alimm_refund_fee | String | 0.06 | 应退还佣金对应的技术服务费 |
| └ tk_subsidy_alimm_refund_fee | String | 0 | 应退还补贴对应的技术服务费 |
| └ tk_commission_agent_refund_fee | String | 0 | 应退还佣金对应的渠道专项服务费 |
| └ tk_subsidy_agent_refund_fee | String | 0 | 应退还补贴对应的渠道专项服务费 |
| └ show_return_fee | String | 0.77 | 应退还预估收入：订单发生维权退款应退还的预估收入（佣金+补贴，含技术服务费和渠道专项服务费） |
| └ relation_id | Number | 1111111 | 渠道关系id |
| └ special_id | Number | 22222 | 会员关系id |
| └ pre_page | Number | 1 | 上一页 |
| └ next_page | Number | 1 | 下一页 |
| └ page_no | Number | 1 | 页码 |
| └ page_size | Number | 2 | 每页订单量 |
| └ has_next | Boolean | false | 是否有下一页 |
| └ position_index | String | 1661386106_3nXt8TjdqT | 位点 |
| └ has_pre | Boolean | false | 是否有上一页 |
| result_code | Number | 200 | 接口返回值信息，跟rpc架构保持一致 |
| biz_error_desc | String | 开始时间不能为空 | 业务错误信息 |
| biz_error_code | Number | 101 | 业务错误码 101, 102,103 |
| result_msg | String | result | 返回信息 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.order.refund.get', {
	'publisher_refund_order_query_option':'数据结构JSON示例'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_order_refund_get_response":{
        "data":{
            "result":{
                "publisher_refund_order_d_t_o":[
                    {
                        "refund_suit_id":"12345",
                        "tb_trade_parent_id":"1707359271433894971",
                        "tb_trade_id":"1707359271433894971",
                        "tb_trade_create_time":"2022-10-19 14:33:06",
                        "earning_time":"2022-10-19 14:39:31",
                        "tk_refund_time":"2022-10-19 14:41:22",
                        "tk_refund_suit_time":"2022-10-19 14:42:29",
                        "modified_time":"2022-10-20 03:26:23",
                        "item_title":"zf测试商品003商品，测试请不要拍",
                        "tk_order_role":"二方",
                        "refund_status":2,
                        "tb_trade_finish_price":"5.00",
                        "refund_fee":"3.50",
                        "pub_share_fee":"1.10",
                        "tk_commission_fee_refund":"0.71",
                        "tk_subsidy_fee_refund":"0",
                        "tk_commission_alimm_refund_fee":"0.06",
                        "tk_subsidy_alimm_refund_fee":"0",
                        "tk_commission_agent_refund_fee":"0",
                        "tk_subsidy_agent_refund_fee":"0",
                        "show_return_fee":"0.77",
                        "relation_id":1111111,
                        "special_id":22222
                    }
                ]
            },
            "pre_page":1,
            "next_page":1,
            "page_no":1,
            "page_size":2,
            "has_next":false,
            "position_index":"1661386106_3nXt8TjdqT",
            "has_pre":false
        },
        "result_code":200,
        "biz_error_desc":"开始时间不能为空",
        "biz_error_code":101,
        "result_msg":"result"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.general.link.convert（淘宝客-推广者-万能转链）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| biz_scene_id | String | 可选 | 1 |  | 1-动态ID转链场景，2-消费者比价场景，4- |
| promotion_type | String | 可选 | 2 |  | 1-自购省，2-推广赚（代理模式专属ID，代理模式必填，其它模式不用填写本字段） |
| material_list | String | 可选 | https://s.click.taobao.com/pQBDhNu,https://s.click.taobao.com/pQBDhNu |  | 物料列表，可以为url或淘口令,多个时使用英文逗号拼接传入（邀约制权限有申请门槛，权限分为①联盟推广链接转链；②天猫/淘宝复制链接转链；如有相关需求请在权限申请时同步说明） |
| relation_id | String | 可选 | 123456 |  | 渠道管理ID（如是主站选品推广场景，必须入参该字段，且bizSceneId字段需入参2-消费者比价场景，否则二次转链失败） |
| adzone_id | Number | 必须 | 123456 |  | 推广位id，mm_xx_xx_xx pid三段式中的第三段 |
| seller_id_list | String | 可选 | 123456 |  | 卖家ID列表,多个时使用英文逗号拼接传入 |
| item_id_list | String | 可选 | qYtxrMJOC8tmtM-Qq0Z65Sbbq5DqZ9 |  | 商品ID列表,多个时使用英文逗号拼接传入 |
| page_id_list | String | 可选 | 123456 |  | 会场ID列表,多个时使用英文逗号拼接传入 |
| target_item | TargetItemDTO | 可选 |  |  | 会场页面内定坑商品 |
| item_dto | LkItemDTO | 可选 |  |  | 商品转链 |
| page_dto | LkPageDTO | 可选 |  |  | 会场页面转链 |
| shop_dto | LkShopDTO | 可选 |  |  | 店铺转链 |
| material_dto | LkMaterialDTO | 可选 |  |  | 链接/口令转链 |
| special_id | String | 可选 | 123 |  | 会员运营id |
| uvid | String | 可选 | adjso7389rbnasd |  | 加密用户标识 |
| qmtid | String | 可选 | 123 |  | 启明系统任务ID |
| uvid_not_authorized | Number | 可选 | 1 |  | （返利）uvid展示授权弹窗1-不展示，0-展示 |
| required_link_type | String | 可选 | cps_short_tpwd,coupon_short_url |  | 用于指定link_info_dto字段出参。coupon_long_url, cps_long_url, cps_short_tpwd, coupon_short_tpwd, cps_short_url, coupon_short_url, coupon_full_tpwd, cps_full_tpwd, share_unit_url, tao_brick_url |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | TbkLinkDTO | TbkLinkDTO | TbkLinkDTO |
| └ material_url_list | MaterialUrlList

                                 [] |  | 转链结果 |
| └ msg | String | 无权限 | 物料对应错误描述 |
| └ code | Number | 1001 | 物料对应错误码 |
| └ promotion_info_dto | MaterialPromotionInfoDTO |  | 营销信息 |
| └ commission_rate | String | 6.00 | 商品收入比率(%)：商品佣金比率+补贴比率。同物料类接口income_rate |
| └ commission_type | String | MKT | 佣金类型。MKT表示营销计划，SP表示定向计划，COMMON表示通用计划，ZX表示自选计划 |
| └ multiple_items_prices_count | Number | 2 | 多件价需拍件数 |
| └ coupon_info_dto | CouponInfoDTO |  | 券信息 |
| └ coupon_end_time | String | 2022-12-20 23:59:59 | 优惠券结束时间 |
| └ activity_id | String | 19d114f1a6464c98a30b01b3cb17dad6 | 券ID |
| └ coupon_remain_count | Number | 99944 | 优惠券剩余数量 |
| └ coupon_amount | String | 80.00 | 券面额 |
| └ coupon_start_time | String | 2022-12-14 00:00:00 | 优惠券开始时间 |
| └ coupon_desc | String | 满129元减80元 | 优惠券信息，满XX元减XX元 |
| └ coupon_type | Number | 0 | 0-店铺 1-单品 |
| └ link_info_dto | LinkInfoDTO |  | 链接信息 |
| └ coupon_long_url | String | https://uland.taobao.com/coupon/edetail?e=HcDWJQP6d12lhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJDtOYUTZvUxMupZB35fyH%2Bj%2BFrYU%2BROQkienhT0Gv%2FXXPpGXqwTrgn%2FiLFm3yG1xo9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmghqozJdwyPlqXT8BNPyRO3CWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOghqozJdwyPlaVcuzWAzoR%2BEffiaBagqGwiV9Bh6z0Brrk5oEZwv0ZJMDQVG07AK7A%3D%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01 | 二合一长链接 |
| └ material_type | Number | 1 | 1—单品 2—店铺 3—会场 4-承接开放 5-优惠券 6-直播间 7-淘积木页 |
| └ cps_long_url | String | https://s.click.taobao.com/t?e=m%3D2%26s%3DKkbloP8JSAVw4vFB6t2Z2ueEDrYVVa64yK8Cckff7TVRAdhuF14FMU3VlJUC3DsQ79%2FTFaMDK6Qc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQEVUjoeWqzb%2BCGsxm48e9hkfF%2Bxu0N%2BwWs0Rgp8gMc9dY1tyQTTDSHqySbHmSI7wOtef%2FroYqRldzn0lFpzXFujTCQ%2BHTk5EfzW8%2BBPSvjFWUZSZEfZ0FH4Va78Lza%2BD%2Fuqo6mSuTG7PlEs8HjV3hrkr1j%2BhoHy6%2FQNdzcFFug%2BbPXd6fR%2Fgq%2FLkcuZKrbdCBTlriuf8gGMP3mPUmtHv0Nb2kE%2BTfvdp4q7CEA%2B11P8YwWLI0fvJc3aqk5eKOUwbKCMNd%2Byi53bExg5p7bh%2BFbQ%3D&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01 | CPS链接长链 |
| └ cps_short_tpwd | String | ￥zRmVdesjTCu￥ | CPS链接的短口令 |
| └ tk_biz_type | Number | 2 | 1-联盟口令，2-主站口令。入参物料不为淘口令时，此字段返回null |
| └ coupon_short_tpwd | String | ￥p7lYdesjTCG￥ | 二合一链接的短口令 |
| └ cps_short_url | String | https://s.click.taobao.com/CvHjOPu | CPS链接短链 |
| └ coupon_short_url | String | https://s.click.taobao.com/DvHjOPu | 二合一链接长链 |
| └ coupon_full_tpwd | String | 47￥ CZ3457 p7lYdesjTCG￥ https://m.tb.cn/h.UQ4ceEA  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装 | 二合一链接的长口令 |
| └ cps_full_tpwd | String | 39￥ CZ3457 zRmVdesjTCu￥ https://m.tb.cn/h.UQ4cewa  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装 | CPS链接的长口令 |
| └ share_unit_url | String | s.click.taobao.com | 种草页链接，定向开放 |
| └ tao_brick_url | String | s.click.taobao.com | 淘积木页面链接，定向开放 |
| └ coupon_channel_url | String | https://uland.taobao.com/coupon/edetail?e=HcDWJQP6d12lhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJDtOYUTZvUxMupZB35fyH%2Bj%2BFrYU%2BROQkienhT0Gv%2FXXPpGXqwTrgn%2FiLFm3yG1xo9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmghqozJdwyPlqXT8BNPyRO3CWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOghqozJdwyPlaVcuzWAzoR%2BEffiaBagqGwiV9Bh6z0Brrk5oEZwv0ZJMDQVG07AK7A%3D%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01 | 频道页二合一链接，必须在required_link_type字段入参才可出参 目前支持淘金币 |
| └ coupon_channel_tpwd | String | 47￥ CZ3457 p7lYdesjTCG￥ https://m.tb.cn/h.UQ4ceEA  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装 | 频道页二合一口令，必须在required_link_type字段入参才可出参 目前支持淘金币 |
| └ cps_channel_url | String | https://s.click.taobao.com/t?e=m%3D2%26s%3DKkbloP8JSAVw4vFB6t2Z2ueEDrYVVa64yK8Cckff7TVRAdhuF14FMU3VlJUC3DsQ79%2FTFaMDK6Qc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQEVUjoeWqzb%2BCGsxm48e9hkfF%2Bxu0N%2BwWs0Rgp8gMc9dY1tyQTTDSHqySbHmSI7wOtef%2FroYqRldzn0lFpzXFujTCQ%2BHTk5EfzW8%2BBPSvjFWUZSZEfZ0FH4Va78Lza%2BD%2Fuqo6mSuTG7PlEs8HjV3hrkr1j%2BhoHy6%2FQNdzcFFug%2BbPXd6fR%2Fgq%2FLkcuZKrbdCBTlriuf8gGMP3mPUmtHv0Nb2kE%2BTfvdp4q7CEA%2B11P8YwWLI0fvJc3aqk5eKOUwbKCMNd%2Byi53bExg5p7bh%2BFbQ%3D&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01 | 频道页CPS链接，必须在required_link_type字段入参才可出参 目前支持淘金币 |
| └ cps_channel_tpwd | String | 39￥ CZ3457 zRmVdesjTCu￥ https://m.tb.cn/h.UQ4cewa  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装 | 频道页CPS口令，必须在required_link_type字段入参才可出参 目前支持淘金币 |
| └ coupon_supered_long_url | String | https://uland.taobao.com/coupon/edetail?e=HcDWJQP6d12lhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJDtOYUTZvUxMupZB35fyH%2Bj%2BFrYU%2BROQkienhT0Gv%2FXXPpGXqwTrgn%2FiLFm3yG1xo9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmghqozJdwyPlqXT8BNPyRO3CWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOghqozJdwyPlaVcuzWAzoR%2BEffiaBagqGwiV9Bh6z0Brrk5oEZwv0ZJMDQVG07AK7A%3D%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01 | 超红二合一长链接，必须在required_link_type字段入参才可出参 |
| └ coupon_supered_short_url | String | https://s.click.taobao.com/CvHjOPu | 超红二合一短链接，必须在required_link_type字段入参才可出参 |
| └ coupon_supered_long_tpwd | String | 39￥ CZ3457 zRmVdesjTCu￥ https://m.tb.cn/h.UQ4cewa  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装 | 超红二合一长口令，必须在required_link_type字段入参才可出参 |
| └ coupon_supered_short_tpwd | String | ￥p7lYdesjTCG￥ | 超红二合一短口令，必须在required_link_type字段入参才可出参 |
| └ cps_supered_long_url | String | https://s.click.taobao.com/t?e=m%3D2%26s%3DKkbloP8JSAVw4vFB6t2Z2ueEDrYVVa64yK8Cckff7TVRAdhuF14FMU3VlJUC3DsQ79%2FTFaMDK6Qc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQEVUjoeWqzb%2BCGsxm48e9hkfF%2Bxu0N%2BwWs0Rgp8gMc9dY1tyQTTDSHqySbHmSI7wOtef%2FroYqRldzn0lFpzXFujTCQ%2BHTk5EfzW8%2BBPSvjFWUZSZEfZ0FH4Va78Lza%2BD%2Fuqo6mSuTG7PlEs8HjV3hrkr1j%2BhoHy6%2FQNdzcFFug%2BbPXd6fR%2Fgq%2FLkcuZKrbdCBTlriuf8gGMP3mPUmtHv0Nb2kE%2BTfvdp4q7CEA%2B11P8YwWLI0fvJc3aqk5eKOUwbKCMNd%2Byi53bExg5p7bh%2BFbQ%3D&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01 | 超红cps长链接，必须在required_link_type字段入参才可出参 |
| └ cps_supered_short_url | String | https://s.click.taobao.com/CvHjOPu | 超红cps短链接，必须在required_link_type字段入参才可出参 |
| └ cps_supered_long_tpwd | String | 39￥ CZ3457 zRmVdesjTCu￥ https://m.tb.cn/h.UQ4cewa  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装 | 超红cps长口令，必须在required_link_type字段入参才可出参 |
| └ cps_supered_short_tpwd | String | ￥p7lYdesjTCG￥ | 超红cps短口令，必须在required_link_type字段入参才可出参 |
| └ input_material_url | String | s.click.taobao.com | 入参物料链接 |
| └ extra_info | String | skuid已失效 | 转链成功的场景下，需要补充说明的信息 |
| └ multiple_items_coupon_info_list | MaterialMultiCouponPromotionInfoDTO

                                 [] |  | 多件价券信息 |
| └ coupon_title | String | 商品券 | 优惠名称 |
| └ coupon_desc | String | 满7999减1300 | 优惠券信息，满XX元减XX元，满x件减y元 |
| └ coupoon_fee | String | 1300.00 | 优惠金额（元） |
| └ coupon_start_time | String | 2022-12-14 00:00:00 | 优惠开始时间 |
| └ coupon_end_time | String | 2022-12-15 00:00:00 | 优惠结束时间 |
| └ activity_id | String | xx | 优惠ID |
| └ coupon_remain_count | Number | 99987 | 优惠剩余数量 |
| └ shop_url_list | ShopUrlList

                                 [] |  | 店铺转链结果 |
| └ msg | String | 无权限 | 物料对应错误描述 |
| └ code | Number | 1001 | 物料对应错误码 |
| └ link_info_dto | LinkInfoDTO |  | 链接信息 |
| └ material_type | Number | 2 | 1—单品 2—店铺 3—会场 |
| └ seller_id | String | 123456 | 卖家ID |
| └ cps_long_url | String | https://s.click.taobao.com/t?e=m%3D2%26s%3DYryVaqQlYtxw4vFB6t2Z2jAVflQIoZepyK8Cckff7TVRAdhuF14FMU3VlJUC3DsQMMgx22UI05Yc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQJFcOCF3%2FDbwRh53k%2Fssh4t44u6hki9mkh%2BLdPuJoV%2FRzl3tHIK2mthnPjZ5WWqolAEgO5kclpNKBjInADNbJYxEcfNLn7HIXszVe3Fb2x4s%2FJDmTntQaQzGDmntuH4VtA%3D%3D | 店铺CPS长链接 |
| └ cps_short_tpwd | String | ￥EAqldesjTCt￥ | 店铺CPS链接对应短口令 |
| └ cps_short_url | String | https://s.click.taobao.com/FvHjOPu | 店铺CPS短链 |
| └ cps_full_tpwd | String | 58￥ CZ3457 EAqldesjTCt￥ https://m.tb.cn/h.UQ4ceEB  韩都衣舍旗舰店 | 店铺CPS链接对应长口令 |
| └ input_shop_id | String | 123 | 入参的店铺ID |
| └ event_url_list | EventUrlList

                                 [] |  | 活动转链信息 |
| └ msg | String | 无权限 | 物料对应错误描述 |
| └ code | Number | 1001 | 物料对应错误码 |
| └ link_info_dto | LinkInfoDTO |  | 链接信息 |
| └ material_type | Number | 3 | 1—单品 2—店铺 3—会场 |
| └ page_id | String | 20150318020014311 | 会场ID |
| └ cps_long_url | String | https://s.click.taobao.com/t?union_lens=lensId%3AOPT%401671517838%402107457f_128d_1852e3a1e2c_03f5%4001%3BeventPageId%3A20150318020014311&e=m%3D2%26s%3DKQjjrM92%2F7Nw4vFB6t2Z2iperVdZeJviU%2F9%2F0taeK29yINtkUhsv0Dl8FS4ucHenj2w9k21YZ3qgpaE1qudUv106NgiXS75NWi4GdVwNf8BfXAlTvwP7PvyclHulJsGMQ%2BNeRhkrKyfCg%2Fx6BHtN2amAOqUjIVeCy0DxCSzwFgFd1le1%2FF%2FLHa44ut0dMc8VMSJUXveljqoq%2FKh6EC%2FmGEM6gfQ3Aokl5MRYl0%2FyOZHb9no%2FURc5w7o18kPD%2BYRAFveQ9Ld2jorKLJiYzWv6xmKche5LvsSo37%2FLmqNFMyVzwS6VTp1JIFY8eNWMEbfNhDTn1psj9iZsDvbh8Qt7h8A2xIPV%2FpBCPqKNE1%2B%2FpYNizQgXEDae2m%2FrHB9aiVckS6fqAUnbbCiWZ1rWjVK6iMgmy2CsK7djvdOCkVnjXedCpzLnRBhrs1VdGRk68r9XJprbVzmT5j1Xj8w0BzyaviGFCzYOOqAQ | 会场CPS长链接 |
| └ cps_short_tpwd | String | ￥PnIodeIlU9z￥ | 会场CPS链接的短口令 |
| └ cps_short_url | String | https://s.click.taobao.com/EvHjOPu | 会场CPS短链接 |
| └ cps_full_tpwd | String | 37￥ CZ3457 PnIodeIlU9z￥ https://m.tb.cn/h.UQ4ceEz  22年天猫双旦礼遇季-主会场 | 会场CPS链接的长口令 |
| └ input_page_id | String | 203567898765 | 入参的会场ID |
| └ item_url_list | ItemUrlList

                                 [] |  | 单品转链信息 |
| └ msg | String | 无权限 | 物料对应错误描述 |
| └ code | Number | 1001 | 物料对应错误码 |
| └ promotion_info_dto | ItemPromotionInfoDTO |  | 营销信息 |
| └ commission_rate | String | 2.40 | 商品收入比率(%)：商品佣金比率+补贴比率。同物料类接口income_rate |
| └ commission_type | String | MKT | 佣金类型。MKT表示营销计划，SP表示定向计划，COMMON表示通用计划，ZX表示自选计划 |
| └ promotion_price | Number | 1349 | 商品到手价。单位分 |
| └ multiple_items_prices_count | Number | 2 | 多件价需拍件数 |
| └ coupon_info_dto | CouponInfoDTO |  | 券信息 |
| └ coupon_end_time | String | 2022-12-25 23:59:59 | 优惠券结束时间 |
| └ activity_id | String | 642208f7db6b4fb9880a9d09832d6b8d | 券ID |
| └ coupon_remain_count | Number | 99987 | 优惠券剩余数量 |
| └ coupon_amount | String | 170.00 | 券面额 |
| └ coupon_start_time | String | 2022-12-20 00:00:00 | 优惠券开始时间 |
| └ coupon_desc | String | 满319元减170元 | 优惠券信息，满XX元减XX元 |
| └ link_info_dto | ItemLinkInfoDTO |  | 链接信息 |
| └ coupon_long_url | String | https://uland.taobao.com/coupon/edetail?e=G6GuYx3ILfalhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJtx9C1Z8GbV1vHgx4K91Wrd9oW7c0CRLBdz881e47Ft9oBDRNgYIxgFNRd9B4OBPr9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmrRMCeO3Mi1ouPODd%2FkGgeDCWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOrRMCeO3Mi1oDb9krsjLiJ069NSKr8HLD%2F5cBb8E%2Fg255M0kZg5qGOw%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01 | 二合一长链接 |
| └ material_type | Number | 1 | 1—单品 2—店铺 3—会场 |
| └ item_id | String | y387e49cRt262Ozub0TvtA-dAeOMBinqPdm6Wxu0 | 商品ID |
| └ cps_long_url | String | https://s.click.taobao.com/t?e=m%3D2%26s%3DvazOG0sd5LJw4vFB6t2Z2ueEDrYVVa64yK8Cckff7TVRAdhuF14FMU3VlJUC3DsQMMgx22UI05Yc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQEVUjoeWqzb%2BCGsxm48e9hkfF%2Bxu0N%2BwWrcZhRlC%2FudiDepej5CXPoiMHuv7RoNv0Q0jFsbsQ7KW1Te9msJWkXsmFF9fm0wobpd0%2BQldqeoBF76lcPm%2FucppnJfkRUzuToD2uOlbI2qURHUT0gmVRp7ZGL0GbiMMd6BniEC%2BBYvRVSjzVV%2FKpYdMm7k2GPZX7L96ZdZH32PNybxY5kax0%2FETNqkNLIJLJkR1E9IJlUaerji63R0xzxUxIlRe96WOqlr6NugmfTu3&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01 | CPS链接长链 |
| └ cps_short_tpwd | String | ￥XODHdeIlU9B￥ | CPS链接的短口令 |
| └ coupon_short_tpwd | String | ￥LOcqdeIlU9y￥ | 二合一链接的短口令 |
| └ cps_short_url | String | https://s.click.taobao.com/GvHjOPu | CPS链接短链 |
| └ coupon_short_url | String | https://s.click.taobao.com/HvHjOPu | 二合一链接长链 |
| └ coupon_full_tpwd | String | 48￥ CZ3457 LOcqdeIlU9y￥ https://m.tb.cn/h.UQ4ceEC  olayks煮茶器喷淋式黑茶白茶煮茶壶家用自动蒸汽养生壶办公室小型 | 二合一链接的长口令 |
| └ cps_full_tpwd | String | 47￥ CZ3457 XODHdeIlU9B￥ https://m.tb.cn/h.UQ4ceEy  olayks煮茶器喷淋式黑茶白茶煮茶壶家用自动蒸汽养生壶办公室小型 | CPS链接的长口令 |
| └ share_unit_url | String | s.click.taobao.com | 种草页链接，定向开放 |
| └ coupon_channel_url | String | https://uland.taobao.com/coupon/edetail?e=HcDWJQP6d12lhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJDtOYUTZvUxMupZB35fyH%2Bj%2BFrYU%2BROQkienhT0Gv%2FXXPpGXqwTrgn%2FiLFm3yG1xo9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmghqozJdwyPlqXT8BNPyRO3CWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOghqozJdwyPlaVcuzWAzoR%2BEffiaBagqGwiV9Bh6z0Brrk5oEZwv0ZJMDQVG07AK7A%3D%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01 | 频道页二合一链接，必须在required_link_type字段入参才可出参 目前支持淘金币 |
| └ coupon_channel_tpwd | String | 47￥ CZ3457 p7lYdesjTCG￥ https://m.tb.cn/h.UQ4ceEA  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装 | 频道页二合一口令，必须在required_link_type字段入参才可出参 目前支持淘金币 |
| └ cps_channel_url | String | https://s.click.taobao.com/t?e=m%3D2%26s%3DvazOG0sd5LJw4vFB6t2Z2ueEDrYVVa64yK8Cckff7TVRAdhuF14FMU3VlJUC3DsQMMgx22UI05Yc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQEVUjoeWqzb%2BCGsxm48e9hkfF%2Bxu0N%2BwWrcZhRlC%2FudiDepej5CXPoiMHuv7RoNv0Q0jFsbsQ7KW1Te9msJWkXsmFF9fm0wobpd0%2BQldqeoBF76lcPm%2FucppnJfkRUzuToD2uOlbI2qURHUT0gmVRp7ZGL0GbiMMd6BniEC%2BBYvRVSjzVV%2FKpYdMm7k2GPZX7L96ZdZH32PNybxY5kax0%2FETNqkNLIJLJkR1E9IJlUaerji63R0xzxUxIlRe96WOqlr6NugmfTu3&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01 | 频道页CPS链接，必须在required_link_type字段入参才可出参 目前支持淘金币 |
| └ cps_channel_tpwd | String | 47￥ CZ3457 XODHdeIlU9B￥ https://m.tb.cn/h.UQ4ceEy  olayks煮茶器喷淋式黑茶白茶煮茶壶家用自动蒸汽养生壶办公室小型 | 频道页CPS口令，必须在required_link_type字段入参才可出参 目前支持淘金币 |
| └ coupon_supered_long_url | String | https://uland.taobao.com/coupon/edetail?e=G6GuYx3ILfalhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJtx9C1Z8GbV1vHgx4K91Wrd9oW7c0CRLBdz881e47Ft9oBDRNgYIxgFNRd9B4OBPr9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmrRMCeO3Mi1ouPODd%2FkGgeDCWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOrRMCeO3Mi1oDb9krsjLiJ069NSKr8HLD%2F5cBb8E%2Fg255M0kZg5qGOw%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01 | 超红二合一长链接，必须在required_link_type字段入参才可出参 |
| └ coupon_supered_short_url | String | https://s.click.taobao.com/HvHjOPu | 超红二合一短链接，必须在required_link_type字段入参才可出参 |
| └ coupon_supered_long_tpwd | String | 47￥ CZ3457 p7lYdesjTCG￥ https://m.tb.cn/h.UQ4ceEA  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装 | 超红二合一长口令，必须在required_link_type字段入参才可出参 |
| └ coupon_supered_short_tpwd | String | ￥LOcqdeIlU9y￥ | 超红二合一短口令，必须在required_link_type字段入参才可出参 |
| └ cps_supered_long_url | String | https://s.click.taobao.com/t?e=m%3D2%26s%3DvazOG0sd5LJw4vFB6t2Z2ueEDrYVVa64yK8Cckff7TVRAdhuF14FMU3VlJUC3DsQMMgx22UI05Yc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQEVUjoeWqzb%2BCGsxm48e9hkfF%2Bxu0N%2BwWrcZhRlC%2FudiDepej5CXPoiMHuv7RoNv0Q0jFsbsQ7KW1Te9msJWkXsmFF9fm0wobpd0%2BQldqeoBF76lcPm%2FucppnJfkRUzuToD2uOlbI2qURHUT0gmVRp7ZGL0GbiMMd6BniEC%2BBYvRVSjzVV%2FKpYdMm7k2GPZX7L96ZdZH32PNybxY5kax0%2FETNqkNLIJLJkR1E9IJlUaerji63R0xzxUxIlRe96WOqlr6NugmfTu3&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01 | 超红cps长链接，必须在required_link_type字段入参才可出参 |
| └ cps_supered_short_url | String | https://s.click.taobao.com/HvHjOPu | 超红cps短链接，必须在required_link_type字段入参才可出参 |
| └ cps_supered_long_tpwd | String | 47￥ CZ3457 p7lYdesjTCG￥ https://m.tb.cn/h.UQ4ceEA  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装 | 超红cps长口令，必须在required_link_type字段入参才可出参 |
| └ cps_supered_short_tpwd | String | ￥LOcqdeIlU9y￥ | 超红cps短口令，必须在required_link_type字段入参才可出参 |
| └ input_item_id | String | i87a9ja90d8-09qrjcoa7qwl | 入参的商品ID |
| └ extra_info | String | skuid已失效 | 转链成功的场景下，需要补充说明的信息 |
| └ multiple_items_coupon_info_list | ItemMultiCouponPromotionInfoDTO

                                 [] |  | 多件价券信息 |
| └ coupon_title | String | 商品券 | 优惠名称 |
| └ coupon_desc | String | 满7999减1300 | 优惠券信息，满XX元减XX元，满x件减y元 |
| └ coupoon_fee | String | 1300.00 | 优惠金额。单位元 |
| └ coupon_start_time | String | 2022-12-14 00:00:00 | 优惠开始时间 |
| └ coupon_end_time | String | 2022-12-15 00:00:00 | 优惠结束时间 |
| └ activity_id | String | 19d114f1a6464c98a30b01b3cb17dad6 | 优惠ID |
| └ coupon_remain_count | Number | 99987 | 优惠剩余数量 |
| biz_error_desc | Number | 1 | 见错误码描述 |
| result_msg | String | 1 | 见错误码描述 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.general.link.convert', {
	'biz_scene_id':'1',
	'promotion_type':'2',
	'material_list':'https://s.click.taobao.com/pQBDhNu,https://s.click.taobao.com/pQBDhNu',
	'relation_id':'123456',
	'adzone_id':'123456',
	'seller_id_list':'123456',
	'item_id_list':'qYtxrMJOC8tmtM-Qq0Z65Sbbq5DqZ9',
	'page_id_list':'123456',
	'target_item':'数据结构JSON示例',
	'item_dto':'数据结构JSON示例',
	'page_dto':'数据结构JSON示例',
	'shop_dto':'数据结构JSON示例',
	'material_dto':'数据结构JSON示例',
	'special_id':'123',
	'uvid':'adjso7389rbnasd',
	'qmtid':'123',
	'uvid_not_authorized':'1',
	'required_link_type':'cps_short_tpwd,coupon_short_url'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_general_link_convert_response":{
        "data":{
            "material_url_list":{
                "material_url_list":[
                    {
                        "msg":"无权限",
                        "code":1001,
                        "promotion_info_dto":{
                            "commission_rate":"6.00",
                            "commission_type":"MKT",
                            "multiple_items_prices_count":2
                        },
                        "coupon_info_dto":{
                            "coupon_end_time":"2022-12-20 23:59:59",
                            "activity_id":"19d114f1a6464c98a30b01b3cb17dad6",
                            "coupon_remain_count":99944,
                            "coupon_amount":"80.00",
                            "coupon_start_time":"2022-12-14 00:00:00",
                            "coupon_desc":"满129元减80元",
                            "coupon_type":0
                        },
                        "link_info_dto":{
                            "coupon_long_url":"https:\/\/uland.taobao.com\/coupon\/edetail?e=HcDWJQP6d12lhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJDtOYUTZvUxMupZB35fyH%2Bj%2BFrYU%2BROQkienhT0Gv%2FXXPpGXqwTrgn%2FiLFm3yG1xo9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmghqozJdwyPlqXT8BNPyRO3CWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOghqozJdwyPlaVcuzWAzoR%2BEffiaBagqGwiV9Bh6z0Brrk5oEZwv0ZJMDQVG07AK7A%3D%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01",
                            "material_type":1,
                            "cps_long_url":"https:\/\/s.click.taobao.com\/t?e=m%3D2%26s%3DKkbloP8JSAVw4vFB6t2Z2ueEDrYVVa64yK8Cckff7TVRAdhuF14FMU3VlJUC3DsQ79%2FTFaMDK6Qc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQEVUjoeWqzb%2BCGsxm48e9hkfF%2Bxu0N%2BwWs0Rgp8gMc9dY1tyQTTDSHqySbHmSI7wOtef%2FroYqRldzn0lFpzXFujTCQ%2BHTk5EfzW8%2BBPSvjFWUZSZEfZ0FH4Va78Lza%2BD%2Fuqo6mSuTG7PlEs8HjV3hrkr1j%2BhoHy6%2FQNdzcFFug%2BbPXd6fR%2Fgq%2FLkcuZKrbdCBTlriuf8gGMP3mPUmtHv0Nb2kE%2BTfvdp4q7CEA%2B11P8YwWLI0fvJc3aqk5eKOUwbKCMNd%2Byi53bExg5p7bh%2BFbQ%3D&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01",
                            "cps_short_tpwd":"￥zRmVdesjTCu￥",
                            "tk_biz_type":2,
                            "coupon_short_tpwd":"￥p7lYdesjTCG￥",
                            "cps_short_url":"https:\/\/s.click.taobao.com\/CvHjOPu",
                            "coupon_short_url":"https:\/\/s.click.taobao.com\/DvHjOPu",
                            "coupon_full_tpwd":"47￥ CZ3457 p7lYdesjTCG￥ https:\/\/m.tb.cn\/h.UQ4ceEA  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装",
                            "cps_full_tpwd":"39￥ CZ3457 zRmVdesjTCu￥ https:\/\/m.tb.cn\/h.UQ4cewa  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装",
                            "share_unit_url":"s.click.taobao.com",
                            "tao_brick_url":"s.click.taobao.com",
                            "coupon_channel_url":"https:\/\/uland.taobao.com\/coupon\/edetail?e=HcDWJQP6d12lhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJDtOYUTZvUxMupZB35fyH%2Bj%2BFrYU%2BROQkienhT0Gv%2FXXPpGXqwTrgn%2FiLFm3yG1xo9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmghqozJdwyPlqXT8BNPyRO3CWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOghqozJdwyPlaVcuzWAzoR%2BEffiaBagqGwiV9Bh6z0Brrk5oEZwv0ZJMDQVG07AK7A%3D%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01",
                            "coupon_channel_tpwd":"47￥ CZ3457 p7lYdesjTCG￥ https:\/\/m.tb.cn\/h.UQ4ceEA  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装",
                            "cps_channel_url":"https:\/\/s.click.taobao.com\/t?e=m%3D2%26s%3DKkbloP8JSAVw4vFB6t2Z2ueEDrYVVa64yK8Cckff7TVRAdhuF14FMU3VlJUC3DsQ79%2FTFaMDK6Qc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQEVUjoeWqzb%2BCGsxm48e9hkfF%2Bxu0N%2BwWs0Rgp8gMc9dY1tyQTTDSHqySbHmSI7wOtef%2FroYqRldzn0lFpzXFujTCQ%2BHTk5EfzW8%2BBPSvjFWUZSZEfZ0FH4Va78Lza%2BD%2Fuqo6mSuTG7PlEs8HjV3hrkr1j%2BhoHy6%2FQNdzcFFug%2BbPXd6fR%2Fgq%2FLkcuZKrbdCBTlriuf8gGMP3mPUmtHv0Nb2kE%2BTfvdp4q7CEA%2B11P8YwWLI0fvJc3aqk5eKOUwbKCMNd%2Byi53bExg5p7bh%2BFbQ%3D&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01",
                            "cps_channel_tpwd":"39￥ CZ3457 zRmVdesjTCu￥ https:\/\/m.tb.cn\/h.UQ4cewa  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装",
                            "coupon_supered_long_url":"https:\/\/uland.taobao.com\/coupon\/edetail?e=HcDWJQP6d12lhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJDtOYUTZvUxMupZB35fyH%2Bj%2BFrYU%2BROQkienhT0Gv%2FXXPpGXqwTrgn%2FiLFm3yG1xo9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmghqozJdwyPlqXT8BNPyRO3CWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOghqozJdwyPlaVcuzWAzoR%2BEffiaBagqGwiV9Bh6z0Brrk5oEZwv0ZJMDQVG07AK7A%3D%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01",
                            "coupon_supered_short_url":"https:\/\/s.click.taobao.com\/CvHjOPu",
                            "coupon_supered_long_tpwd":"39￥ CZ3457 zRmVdesjTCu￥ https:\/\/m.tb.cn\/h.UQ4cewa  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装",
                            "coupon_supered_short_tpwd":"￥p7lYdesjTCG￥",
                            "cps_supered_long_url":"https:\/\/s.click.taobao.com\/t?e=m%3D2%26s%3DKkbloP8JSAVw4vFB6t2Z2ueEDrYVVa64yK8Cckff7TVRAdhuF14FMU3VlJUC3DsQ79%2FTFaMDK6Qc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQEVUjoeWqzb%2BCGsxm48e9hkfF%2Bxu0N%2BwWs0Rgp8gMc9dY1tyQTTDSHqySbHmSI7wOtef%2FroYqRldzn0lFpzXFujTCQ%2BHTk5EfzW8%2BBPSvjFWUZSZEfZ0FH4Va78Lza%2BD%2Fuqo6mSuTG7PlEs8HjV3hrkr1j%2BhoHy6%2FQNdzcFFug%2BbPXd6fR%2Fgq%2FLkcuZKrbdCBTlriuf8gGMP3mPUmtHv0Nb2kE%2BTfvdp4q7CEA%2B11P8YwWLI0fvJc3aqk5eKOUwbKCMNd%2Byi53bExg5p7bh%2BFbQ%3D&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01",
                            "cps_supered_short_url":"https:\/\/s.click.taobao.com\/CvHjOPu",
                            "cps_supered_long_tpwd":"39￥ CZ3457 zRmVdesjTCu￥ https:\/\/m.tb.cn\/h.UQ4cewa  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装",
                            "cps_supered_short_tpwd":"￥p7lYdesjTCG￥"
                        },
                        "input_material_url":"s.click.taobao.com",
                        "extra_info":"skuid已失效",
                        "multiple_items_coupon_info_list":{
                            "material_multi_coupon_promotion_info_d_t_o":[
                                {
                                    "coupon_title":"商品券",
                                    "coupon_desc":"满7999减1300",
                                    "coupoon_fee":"1300.00",
                                    "coupon_start_time":"2022-12-14 00:00:00",
                                    "coupon_end_time":"2022-12-15 00:00:00",
                                    "activity_id":"xx",
                                    "coupon_remain_count":99987
                                }
                            ]
                        }
                    }
                ]
            },
            "shop_url_list":{
                "shop_url_list":[
                    {
                        "msg":"无权限",
                        "code":1001,
                        "link_info_dto":{
                            "material_type":2,
                            "seller_id":"123456",
                            "cps_long_url":"https:\/\/s.click.taobao.com\/t?e=m%3D2%26s%3DYryVaqQlYtxw4vFB6t2Z2jAVflQIoZepyK8Cckff7TVRAdhuF14FMU3VlJUC3DsQMMgx22UI05Yc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQJFcOCF3%2FDbwRh53k%2Fssh4t44u6hki9mkh%2BLdPuJoV%2FRzl3tHIK2mthnPjZ5WWqolAEgO5kclpNKBjInADNbJYxEcfNLn7HIXszVe3Fb2x4s%2FJDmTntQaQzGDmntuH4VtA%3D%3D",
                            "cps_short_tpwd":"￥EAqldesjTCt￥",
                            "cps_short_url":"https:\/\/s.click.taobao.com\/FvHjOPu",
                            "cps_full_tpwd":"58￥ CZ3457 EAqldesjTCt￥ https:\/\/m.tb.cn\/h.UQ4ceEB  韩都衣舍旗舰店"
                        },
                        "input_shop_id":"123"
                    }
                ]
            },
            "event_url_list":{
                "event_url_list":[
                    {
                        "msg":"无权限",
                        "code":1001,
                        "link_info_dto":{
                            "material_type":3,
                            "page_id":"20150318020014311",
                            "cps_long_url":"https:\/\/s.click.taobao.com\/t?union_lens=lensId%3AOPT%401671517838%402107457f_128d_1852e3a1e2c_03f5%4001%3BeventPageId%3A20150318020014311&e=m%3D2%26s%3DKQjjrM92%2F7Nw4vFB6t2Z2iperVdZeJviU%2F9%2F0taeK29yINtkUhsv0Dl8FS4ucHenj2w9k21YZ3qgpaE1qudUv106NgiXS75NWi4GdVwNf8BfXAlTvwP7PvyclHulJsGMQ%2BNeRhkrKyfCg%2Fx6BHtN2amAOqUjIVeCy0DxCSzwFgFd1le1%2FF%2FLHa44ut0dMc8VMSJUXveljqoq%2FKh6EC%2FmGEM6gfQ3Aokl5MRYl0%2FyOZHb9no%2FURc5w7o18kPD%2BYRAFveQ9Ld2jorKLJiYzWv6xmKche5LvsSo37%2FLmqNFMyVzwS6VTp1JIFY8eNWMEbfNhDTn1psj9iZsDvbh8Qt7h8A2xIPV%2FpBCPqKNE1%2B%2FpYNizQgXEDae2m%2FrHB9aiVckS6fqAUnbbCiWZ1rWjVK6iMgmy2CsK7djvdOCkVnjXedCpzLnRBhrs1VdGRk68r9XJprbVzmT5j1Xj8w0BzyaviGFCzYOOqAQ",
                            "cps_short_tpwd":"￥PnIodeIlU9z￥",
                            "cps_short_url":"https:\/\/s.click.taobao.com\/EvHjOPu",
                            "cps_full_tpwd":"37￥ CZ3457 PnIodeIlU9z￥ https:\/\/m.tb.cn\/h.UQ4ceEz  22年天猫双旦礼遇季-主会场"
                        },
                        "input_page_id":"203567898765"
                    }
                ]
            },
            "item_url_list":{
                "item_url_list":[
                    {
                        "msg":"无权限",
                        "code":1001,
                        "promotion_info_dto":{
                            "commission_rate":"2.40",
                            "commission_type":"MKT",
                            "promotion_price":1349,
                            "multiple_items_prices_count":2
                        },
                        "coupon_info_dto":{
                            "coupon_end_time":"2022-12-25 23:59:59",
                            "activity_id":"642208f7db6b4fb9880a9d09832d6b8d",
                            "coupon_remain_count":99987,
                            "coupon_amount":"170.00",
                            "coupon_start_time":"2022-12-20 00:00:00",
                            "coupon_desc":"满319元减170元"
                        },
                        "link_info_dto":{
                            "coupon_long_url":"https:\/\/uland.taobao.com\/coupon\/edetail?e=G6GuYx3ILfalhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJtx9C1Z8GbV1vHgx4K91Wrd9oW7c0CRLBdz881e47Ft9oBDRNgYIxgFNRd9B4OBPr9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmrRMCeO3Mi1ouPODd%2FkGgeDCWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOrRMCeO3Mi1oDb9krsjLiJ069NSKr8HLD%2F5cBb8E%2Fg255M0kZg5qGOw%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01",
                            "material_type":1,
                            "item_id":"y387e49cRt262Ozub0TvtA-dAeOMBinqPdm6Wxu0",
                            "cps_long_url":"https:\/\/s.click.taobao.com\/t?e=m%3D2%26s%3DvazOG0sd5LJw4vFB6t2Z2ueEDrYVVa64yK8Cckff7TVRAdhuF14FMU3VlJUC3DsQMMgx22UI05Yc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQEVUjoeWqzb%2BCGsxm48e9hkfF%2Bxu0N%2BwWrcZhRlC%2FudiDepej5CXPoiMHuv7RoNv0Q0jFsbsQ7KW1Te9msJWkXsmFF9fm0wobpd0%2BQldqeoBF76lcPm%2FucppnJfkRUzuToD2uOlbI2qURHUT0gmVRp7ZGL0GbiMMd6BniEC%2BBYvRVSjzVV%2FKpYdMm7k2GPZX7L96ZdZH32PNybxY5kax0%2FETNqkNLIJLJkR1E9IJlUaerji63R0xzxUxIlRe96WOqlr6NugmfTu3&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01",
                            "cps_short_tpwd":"￥XODHdeIlU9B￥",
                            "coupon_short_tpwd":"￥LOcqdeIlU9y￥",
                            "cps_short_url":"https:\/\/s.click.taobao.com\/GvHjOPu",
                            "coupon_short_url":"https:\/\/s.click.taobao.com\/HvHjOPu",
                            "coupon_full_tpwd":"48￥ CZ3457 LOcqdeIlU9y￥ https:\/\/m.tb.cn\/h.UQ4ceEC  olayks煮茶器喷淋式黑茶白茶煮茶壶家用自动蒸汽养生壶办公室小型",
                            "cps_full_tpwd":"47￥ CZ3457 XODHdeIlU9B￥ https:\/\/m.tb.cn\/h.UQ4ceEy  olayks煮茶器喷淋式黑茶白茶煮茶壶家用自动蒸汽养生壶办公室小型",
                            "share_unit_url":"s.click.taobao.com",
                            "coupon_channel_url":"https:\/\/uland.taobao.com\/coupon\/edetail?e=HcDWJQP6d12lhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJDtOYUTZvUxMupZB35fyH%2Bj%2BFrYU%2BROQkienhT0Gv%2FXXPpGXqwTrgn%2FiLFm3yG1xo9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmghqozJdwyPlqXT8BNPyRO3CWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOghqozJdwyPlaVcuzWAzoR%2BEffiaBagqGwiV9Bh6z0Brrk5oEZwv0ZJMDQVG07AK7A%3D%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01",
                            "coupon_channel_tpwd":"47￥ CZ3457 p7lYdesjTCG￥ https:\/\/m.tb.cn\/h.UQ4ceEA  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装",
                            "cps_channel_url":"https:\/\/s.click.taobao.com\/t?e=m%3D2%26s%3DvazOG0sd5LJw4vFB6t2Z2ueEDrYVVa64yK8Cckff7TVRAdhuF14FMU3VlJUC3DsQMMgx22UI05Yc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQEVUjoeWqzb%2BCGsxm48e9hkfF%2Bxu0N%2BwWrcZhRlC%2FudiDepej5CXPoiMHuv7RoNv0Q0jFsbsQ7KW1Te9msJWkXsmFF9fm0wobpd0%2BQldqeoBF76lcPm%2FucppnJfkRUzuToD2uOlbI2qURHUT0gmVRp7ZGL0GbiMMd6BniEC%2BBYvRVSjzVV%2FKpYdMm7k2GPZX7L96ZdZH32PNybxY5kax0%2FETNqkNLIJLJkR1E9IJlUaerji63R0xzxUxIlRe96WOqlr6NugmfTu3&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01",
                            "cps_channel_tpwd":"47￥ CZ3457 XODHdeIlU9B￥ https:\/\/m.tb.cn\/h.UQ4ceEy  olayks煮茶器喷淋式黑茶白茶煮茶壶家用自动蒸汽养生壶办公室小型",
                            "coupon_supered_long_url":"https:\/\/uland.taobao.com\/coupon\/edetail?e=G6GuYx3ILfalhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJtx9C1Z8GbV1vHgx4K91Wrd9oW7c0CRLBdz881e47Ft9oBDRNgYIxgFNRd9B4OBPr9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmrRMCeO3Mi1ouPODd%2FkGgeDCWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOrRMCeO3Mi1oDb9krsjLiJ069NSKr8HLD%2F5cBb8E%2Fg255M0kZg5qGOw%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01",
                            "coupon_supered_short_url":"https:\/\/s.click.taobao.com\/HvHjOPu",
                            "coupon_supered_long_tpwd":"47￥ CZ3457 p7lYdesjTCG￥ https:\/\/m.tb.cn\/h.UQ4ceEA  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装",
                            "coupon_supered_short_tpwd":"￥LOcqdeIlU9y￥",
                            "cps_supered_long_url":"https:\/\/s.click.taobao.com\/t?e=m%3D2%26s%3DvazOG0sd5LJw4vFB6t2Z2ueEDrYVVa64yK8Cckff7TVRAdhuF14FMU3VlJUC3DsQMMgx22UI05Yc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQEVUjoeWqzb%2BCGsxm48e9hkfF%2Bxu0N%2BwWrcZhRlC%2FudiDepej5CXPoiMHuv7RoNv0Q0jFsbsQ7KW1Te9msJWkXsmFF9fm0wobpd0%2BQldqeoBF76lcPm%2FucppnJfkRUzuToD2uOlbI2qURHUT0gmVRp7ZGL0GbiMMd6BniEC%2BBYvRVSjzVV%2FKpYdMm7k2GPZX7L96ZdZH32PNybxY5kax0%2FETNqkNLIJLJkR1E9IJlUaerji63R0xzxUxIlRe96WOqlr6NugmfTu3&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01",
                            "cps_supered_short_url":"https:\/\/s.click.taobao.com\/HvHjOPu",
                            "cps_supered_long_tpwd":"47￥ CZ3457 p7lYdesjTCG￥ https:\/\/m.tb.cn\/h.UQ4ceEA  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装",
                            "cps_supered_short_tpwd":"￥LOcqdeIlU9y￥"
                        },
                        "input_item_id":"i87a9ja90d8-09qrjcoa7qwl",
                        "extra_info":"skuid已失效",
                        "multiple_items_coupon_info_list":{
                            "item_multi_coupon_promotion_info_d_t_o":[
                                {
                                    "coupon_title":"商品券",
                                    "coupon_desc":"满7999减1300",
                                    "coupoon_fee":"1300.00",
                                    "coupon_start_time":"2022-12-14 00:00:00",
                                    "coupon_end_time":"2022-12-15 00:00:00",
                                    "activity_id":"19d114f1a6464c98a30b01b3cb17dad6",
                                    "coupon_remain_count":99987
                                }
                            ]
                        }
                    }
                ]
            }
        },
        "biz_error_desc":1,
        "result_msg":"1"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.feed.opt.upload（淘宝客-推广者-内容种草投流明细数据上传）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| device_type | Number | 必须 | 12 |  | 设备类型；IMEI-8,IMEI_MD5-9，IDFA-10,IDFA_MD5-13，OAID-12,OAID_MD5-14，CAID-15，CAID_MD5-25 |
| event_id | Number | 必须 | 111 |  | 星任务id |
| campaign_id | String | 必须 | 111 |  | 广告campaign_id |
| content_id | String | 必须 | content_id |  | 媒体内容id |
| device_id | String | 必须 | 0df232dd4d757938 |  | 用户设备id |
| creative_id | String | 必须 | 111 |  | 广告creative_id |
| account_id | String | 必须 | 111 |  | 广告account_id |
| indicator_type | Number | 必须 | 1 |  | 用户行为指标类型；1-播放，2-曝光 |
| unit_id | String | 必须 | 111 |  | 广告unit_id |
| indicator_value | Number | 必须 | 1 |  | 用户行为指标数值 |
| behavior_time_stamp | Date | 必须 | 2023-02-10 23:59:59 |  | 用户行为时间戳，yyyy-MM-dd HH:mm:ss |
| request_id | String | 必须 | 0df232dd4d757938 |  | RTA唯一请求id |
| exp_id | String | 必须 | 123 |  | 外界媒体划分的实验id |
| rta_switch | Number | 必须 | 1 |  | rta开关状态，1-开启，0-关闭 |
| ad_consume | Number | 必须 | 123 |  | 广告pv消耗金额，单位毫分 |
| rta_extra_info | String | 必须 | xxxxx |  | rta自定义业务字段 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | Boolean | true | 成功标志 |
| result_code | Number | 200 | 返回码 |
| biz_error_desc | String | 系统异常 | 业务错误码 |
| result_msg | Number | 内部服务发生错误 | 错误信息 |
| biz_error_code | Number | 1001 | 业务错误信息 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.feed.opt.upload', {
	'device_type':'12',
	'event_id':'111',
	'campaign_id':'111',
	'content_id':'content_id',
	'device_id':'0df232dd4d757938',
	'creative_id':'111',
	'account_id':'111',
	'indicator_type':'1',
	'unit_id':'111',
	'indicator_value':'1',
	'behavior_time_stamp':'2023-02-10 23:59:59',
	'request_id':'0df232dd4d757938',
	'exp_id':'123',
	'rta_switch':'1',
	'ad_consume':'123',
	'rta_extra_info':'xxxxx'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_feed_opt_upload_response":{
        "data":true,
        "result_code":200,
        "biz_error_desc":"系统异常",
        "result_msg":内部服务发生错误,
        "biz_error_code":1001
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.item.group.merge（淘宝客-推广者-多品凑单上传）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| super_red_envelope | Number | 可选 | 1 |  | 是否展示超红小把手，1:是，0:否。不传或其它值均视为否。 |
| nubmbers | String | 必须 | 2,3 |  | 每个商品对应的消费者购买数量，和商品id一一对应，用英文逗号分隔 |
| coupons | String | 可选 | false	["https://uland.taobao.com/coupon/edetail?e=123","https://uland.taobao.com/quan/detail?sellerId=123&activityId=123"] |  | 券信息（json数组，最多15个，建议不超过3个，否则可能超时），支持couponid和uland链接，若为uland链接，会通过uland查券（uland支持二合一、三合一、店铺券） |
| item_ids | String | 必须 | wojDmGmsMCeXQRGSBdYhbtd-jowwbqCvwGPMGgGTw6,v6K3mGVu8Co7AyKtPpzu0te-rYbbjPH2GvxnP38c5 |  | 淘宝客商品id，最多10个，用英文逗号分隔 |
| adzone_id | String | 必须 | 123123 |  | 淘客adzoneid |
| relation_id | String | 可选 | 123123 |  | 淘客relationid |
| page_id | String | 可选 | 20150318020015276 |  | 联盟洞房会场的id |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| page_url | String | https://mo.m.taobao.com/union2/page_1671415704484?openPageId=ab904583f69aa1437e97160e4ea3110a | 多品凑单页面链接 |
| open_page_id | String | b904583f69aa1437e97160e4ea3110a | 多品凑单页面id |
| model | String | ￥SIH6XbwRfyt￥ | 多品凑单页面链接对应的短口令。非苹果ios14以上版本的设备（即其他ios版本、Android系统等），可以用此淘口令正常在复制到手淘打开 |
| password | String | 79￥ CZ3457 vSfz2BFHDnQ￥ https://m.tb.cn/h.UdrTGkb  上海梅林经典午餐肉罐头340g即食速食家庭储备应急食品 不含鸡肉 | 多品凑单页面链接对应的长口令。针对苹果ios14及以上版本的苹果设备，手淘将按照示例值信息格式读取淘口令。如需更改淘口令内文案、url等内容，请务必先验证更改后的淘口令在手淘可被识别打开！ |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.item.group.merge', {
	'super_red_envelope':'1',
	'nubmbers':'2,3',
	'coupons':'false	[\"https://uland.taobao.com/coupon/edetail?e=123\",\"https://uland.taobao.com/quan/detail?sellerId=123&activityId=123\"]',
	'item_ids':'wojDmGmsMCeXQRGSBdYhbtd-jowwbqCvwGPMGgGTw6,v6K3mGVu8Co7AyKtPpzu0te-rYbbjPH2GvxnP38c5',
	'adzone_id':'123123',
	'relation_id':'123123',
	'page_id':'20150318020015276'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_item_group_merge_response":{
        "page_url":"https:\/\/mo.m.taobao.com\/union2\/page_1671415704484?openPageId=ab904583f69aa1437e97160e4ea3110a",
        "open_page_id":"b904583f69aa1437e97160e4ea3110a",
        "model":"￥SIH6XbwRfyt￥",
        "password":"79￥ CZ3457 vSfz2BFHDnQ￥ https:\/\/m.tb.cn\/h.UdrTGkb  上海梅林经典午餐肉罐头340g即食速食家庭储备应急食品 不含鸡肉"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.feed.relation.upload（淘宝客-推广者-内容投流关系写入）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| event_id | Number | 必须 | 12340 |  | 星任务id |
| creative_name | String | 可选 | xxx |  | 创意名称 |
| unit_name | String | 可选 | xxx |  | 单元名称 |
| account_name | String | 可选 | xxx |  | 广告账户名称 |
| creative_url | String | 可选 | url |  | 创意url |
| campaign_id | String | 可选 | yyy |  | 计划id |
| content_id | String | 可选 | yyy |  | 稿件id |
| creative_id | String | 可选 | yyy |  | 创意id |
| account_id | String | 可选 | yyy |  | 广告账户id |
| seed_content | Boolean | 可选 | true |  | 是否商单稿件 |
| unit_id | String | 可选 | yyy |  | 单元id |
| campaign_name | String | 可选 | xxx |  | 计划名称 |
| order_id | String | 可选 | 123456 |  | 订单id |
| order_name | String | 可选 | xxx |  | 订单名称 |
| content_name | String | 可选 | xxx |  | 内容名称 |
| content_url | String | 可选 | xxx |  | 内容链接 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | Boolean | true | 写入成功结果 |
| result_code | Number | 200 | 返回码 |
| biz_error_desc | String | "error" | 错误码释义 |
| result_msg | String | "result" | 返回码释义 |
| biz_error_code | Number | 110 | 错误码 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.feed.relation.upload', {
	'event_id':'12340',
	'creative_name':'xxx',
	'unit_name':'xxx',
	'account_name':'xxx',
	'creative_url':'url',
	'campaign_id':'yyy',
	'content_id':'yyy',
	'creative_id':'yyy',
	'account_id':'yyy',
	'seed_content':'true',
	'unit_id':'yyy',
	'campaign_name':'xxx',
	'order_id':'123456',
	'order_name':'xxx',
	'content_name':'xxx',
	'content_url':'xxx'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_feed_relation_upload_response":{
        "data":true,
        "result_code":200,
        "biz_error_desc":"\"error\"",
        "result_msg":"\"result\"",
        "biz_error_code":110
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.feed.indicator.upload（淘宝客-推广者-内容种草投流前链路数据上传）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| event_id | Number | 必须 | 111 |  | 星任务id |
| evoke_pv | Number | 可选 | 11 |  | 唤起pv |
| rpt_start_time | Date | 必须 | 2023-02-10 23:59:59 |  | 数据汇总开始时间 |
| creative_name | String | 可选 | xxx |  | 创意名称 |
| click_pv | Number | 必须 | 1 |  | 点击pv |
| play_pv | Number | 必须 | 1 |  | 播放pv |
| unit_name | String | 可选 | xxx |  | 单元名称 |
| exposure_pv | Number | 必须 | 1 |  | 曝光pv |
| account_name | String | 可选 | xxx |  | 账户名称 |
| campaign_id | String | 可选 | 1 |  | 计划id |
| content_id | String | 必须 | xxx |  | 内容id |
| sclick_pv | Number | 必须 | 1 |  | 蓝链点击 |
| rpt_end_time | Date | 必须 | 2023-02-10 23:59:59 |  | 数据汇总结束时间 |
| creative_id | String | 可选 | 1 |  | 创意id |
| content_name | String | 必须 | xxx |  | 内容名称 |
| sclick_exposure_pv | Number | 必须 | 1 |  | 蓝链曝光 |
| account_id | String | 可选 | 1 |  | 账户id |
| unit_id | String | 可选 | 1 |  | 单元id |
| consume_amt | Number | 必须 | 1 |  | 消费金额，分 |
| campaign_name | String | 可选 | xxx |  | 计划名称 |
| play_uv | Number | 可选 | 123 |  | 阅读uv |
| order_id | String | 可选 | 123 |  | 订单id |
| order_name | String | 可选 | xxx |  | 订单名称 |
| cpm | Number | 可选 | 123 |  | 千次曝光成本，分 |
| cpc | Number | 可选 | 123 |  | 单次阅读成本，分 |
| cpa | Number | 可选 | 123 |  | 单次互动成本，分 |
| like_pv | Number | 可选 | 123 |  | 点赞pv |
| collect_pv | Number | 可选 | 123 |  | 收藏pv |
| comment_pv | Number | 可选 | 123 |  | 评论pv |
| read_rate | Number | 可选 | 123 |  | 阅读率，精确至小数点后两位，1234意味着12.34% |
| sclick_exposure_rate | Number | 可选 | 123 |  | 链接曝光率，精确至小数点后两位，1234意味着12.34% |
| sclick_click_rate | Number | 可选 | 123 |  | 链接点击率，精确至小数点后两位，1234意味着12.34% |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | Boolean | true | 成功标志 |
| result_code | Number | 200 | 返回码 |
| biz_error_desc | String | 系统异常 | 业务错误码 |
| result_msg | Number | 内部服务发生错误 | 错误信息 |
| biz_error_code | Number | 1001 | 业务错误信息 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.feed.indicator.upload', {
	'event_id':'111',
	'evoke_pv':'11',
	'rpt_start_time':'2023-02-10 23:59:59',
	'creative_name':'xxx',
	'click_pv':'1',
	'play_pv':'1',
	'unit_name':'xxx',
	'exposure_pv':'1',
	'account_name':'xxx',
	'campaign_id':'1',
	'content_id':'xxx',
	'sclick_pv':'1',
	'rpt_end_time':'2023-02-10 23:59:59',
	'creative_id':'1',
	'content_name':'xxx',
	'sclick_exposure_pv':'1',
	'account_id':'1',
	'unit_id':'1',
	'consume_amt':'1',
	'campaign_name':'xxx',
	'play_uv':'123',
	'order_id':'123',
	'order_name':'xxx',
	'cpm':'123',
	'cpc':'123',
	'cpa':'123',
	'like_pv':'123',
	'collect_pv':'123',
	'comment_pv':'123',
	'read_rate':'123',
	'sclick_exposure_rate':'123',
	'sclick_click_rate':'123'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_feed_indicator_upload_response":{
        "data":true,
        "result_code":200,
        "biz_error_desc":"系统异常",
        "result_msg":内部服务发生错误,
        "biz_error_code":1001
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.feed.indicator.exchange（淘宝客-推广者-内容种草投流数据交换）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| page_no | Number | 必须 | 1 |  | 页码从1开始 |
| page_size | Number | 必须 | 20 |  | 页容20 |
| filters | String | 必须 | ds=20231111 |  | ds=20231111 & 分隔，每个查询维度仅传一次，多个会覆盖 |
| dimensions | String | 必须 | ds |  | 数据聚合维度，目前仅支持ds |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | PageResult |  | 返回对象 |
| └ page_no | Number | 1 | 页码 |
| └ page_size | Number | 20 | 页容 |
| └ total_count | Number | 100 | 总数 |
| └ result | DataExchangeDTO

                                 [] |  | 数据列表 |
| └ ds | String | 20230519 | 日期分区 |
| └ event_id | Number | 1111 | 星任务id |
| └ campaign_id | String | 111 | 计划id |
| └ unit_id | String | 111 | 单元id |
| └ creative_id | String | 111 | 创意id |
| └ uv_num | Number | 111 | 进店UV |
| └ clt_uv_num | Number | 111 | 收藏UV |
| └ add_uv_num | Number | 111 | 加购UV |
| └ new_visitor_uv_num | Number | 111 | 新访客UV |
| └ pay_buyer_uv | Number | 111 | 成交UV |
| └ se_lead_conv | Number | 111 | 手淘搜索进店UV |
| └ order_id | String | 123 | 知乎订单 |
| result_code | Number | 200 | 返回码 |
| biz_error_desc | String | "error" | 错误码释义 |
| result_msg | Number | "result" | 返回码释义 |
| biz_error_code | Number | 0 | 业务错误 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.feed.indicator.exchange', {
	'page_no':'1',
	'page_size':'20',
	'filters':'ds=20231111',
	'dimensions':'ds'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_feed_indicator_exchange_response":{
        "data":{
            "page_no":1,
            "page_size":20,
            "total_count":100,
            "result":{
                "data_exchange_d_t_o":[
                    {
                        "ds":"20230519",
                        "event_id":1111,
                        "campaign_id":"111",
                        "unit_id":"111",
                        "creative_id":"111",
                        "uv_num":111,
                        "clt_uv_num":111,
                        "add_uv_num":111,
                        "new_visitor_uv_num":111,
                        "pay_buyer_uv":111,
                        "se_lead_conv":111,
                        "order_id":"123"
                    }
                ]
            }
        },
        "result_code":200,
        "biz_error_desc":"\"error\"",
        "result_msg":"result",
        "biz_error_code":0
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.feed.event.get（淘宝客-推广者-投流任务信息下行）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| page_no | Number | 可选 | 1 |  | 页码 |
| page_size | Number | 可选 | 20 |  | 页容 |
| event_id_list | Number | 可选 | 123,456 |  | 星任务id列表 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | PageResult |  | 返回对象 |
| └ page_no | Number | 1 | 页码 |
| └ page_size | Number | 20 | 页容 |
| └ total_count | Number | 100 | 总数 |
| └ result | CooperationFeedEventDTO

                                 [] |  | 数据列表 |
| └ event_id | Number | 123456789 | 星任务id |
| └ secret_key | String | abcd1234 | 接单密钥 |
| └ sponsor_role_type | String | agency | 发单角色 |
| └ coop_role_type | String | service_provider | 接单角色 |
| └ event_create_time | Date | 2023-09-08 00:00:00 | 星任务创建时间 |
| └ event_start_time | Date | 2023-09-09 00:00:00 | 星任务推广开始时间 |
| └ event_end_time | Date | 2999-12-31 23:59:59 | 星任务推广结束时间 |
| └ status_code | Number | 3 | 星任务状态 |
| └ shop_nick_name | String | xxx店 | 推广店铺名称 |
| └ sponsor_member_id | Number | 123 | 星任务发单方memberId |
| └ coop_member_id | Number | 123 | 星任务接单方memberId |
| └ sponsor_company_name | String | 测试公司 | 星任务发单方主体 |
| └ sponsor_sign_time | Date | 2023-09-09 00:00:00 | 星任务发单方签约时间 |
| └ coop_company_name | String | 测试公司 | 星任务接单方主体 |
| └ coop_sign_time | Date | 2023-09-09 00:00:00 | 星任务接单方签约时间 |
| └ total_freeze_fee | String | 100.23 | 父任务冻结金额(元) |
| └ event_fee_update_time | String | 2024-01-09 00:00:00 | 父任务金额更新时间，默认0 |
| result_code | Number | 200 | 返回码 |
| biz_error_desc | String | "error" | 错误码释义 |
| result_msg | Number | "result" | 返回码释义 |
| biz_error_code | Number | 0 | 业务错误 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.feed.event.get', {
	'page_no':'1',
	'page_size':'20',
	'event_id_list':'123,456'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_feed_event_get_response":{
        "data":{
            "page_no":1,
            "page_size":20,
            "total_count":100,
            "result":{
                "cooperation_feed_event_d_t_o":[
                    {
                        "event_id":123456789,
                        "secret_key":"abcd1234",
                        "sponsor_role_type":"agency",
                        "coop_role_type":"service_provider",
                        "event_create_time":"2023-09-08 00:00:00",
                        "event_start_time":"2023-09-09 00:00:00",
                        "event_end_time":"2999-12-31 23:59:59",
                        "status_code":3,
                        "shop_nick_name":"xxx店",
                        "sponsor_member_id":123,
                        "coop_member_id":123,
                        "sponsor_company_name":"测试公司",
                        "sponsor_sign_time":"2023-09-09 00:00:00",
                        "coop_company_name":"测试公司",
                        "coop_sign_time":"2023-09-09 00:00:00",
                        "total_freeze_fee":"100.23",
                        "event_fee_update_time":"2024-01-09 00:00:00"
                    }
                ]
            }
        },
        "result_code":200,
        "biz_error_desc":"\"error\"",
        "result_msg":"result",
        "biz_error_code":0
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.uvid.encrypt（淘宝客-推广者-加密用户标识生成）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| tk_domain | Number | 必须 | 1 |  | 淘客业务域，1-导购 2-流量 3-社群 4-代理 5-返利 |
| source_type | Number | 可选 | 1 |  | 媒体侧用户id，固定传1 |
| source_values | String | 可选 | 123,123 |  | 原始用户id值，传入多个时请使用英文逗号分隔，最多不超过10个 |
| main_accountid | Number | 可选 | 1231231 |  | 联盟账号组的主账号ID,传入时使用账号组维度创建 |
| device_type | String | 可选 | 1 |  | 设备号类型，1-OAID 不加密 2-IMEI md5加密 3-IDFA md5加密 4-CAID 5-CAID2  6-OAID md5加密 |
| device_value | String | 可选 | 123-231-2313cdsa |  | 设备值 |
| caid_version | String | 可选 | 20211113 |  | CAID版本号，使用CAID时必传 |
| group_type | Number | 可选 | 1 |  | 1-媒体账号组，2-自定义账号组。main_accountid不空其他值默认为媒体账号组 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result_list | UvIdGenerateRes [] |  | result_list |
| └ error_message | String | miss source_values | 错误描述 |
| └ encrypted_uvid | String | vnt22Qurt6YYmVhBmLnBrsNPL9Ra | 加密用户标识 |
| └ source_value | String | 123 | 入参的原始用户id |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.uvid.encrypt', {
	'tk_domain':'1',
	'source_type':'1',
	'source_values':'123,123',
	'main_accountid':'1231231',
	'device_type':'1',
	'device_value':'123-231-2313cdsa',
	'caid_version':'20211113',
	'group_type':'1'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_uvid_encrypt_response":{
        "result_list":{
            "uv_id_generate_res":[
                {
                    "error_message":"miss source_values",
                    "encrypted_uvid":"vnt22Qurt6YYmVhBmLnBrsNPL9Ra",
                    "source_value":"123"
                }
            ]
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.seed.event.fee.update（淘宝客-推广者-种草商单子任务改价申请）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| change_request_id | String | 必须 | 123 |  | 变更请求id |
| change_type | Number | 必须 | 1 |  | 变更类型，-1：减少预算，1：增加预算 |
| media_platform_fee | String | 可选 | 1.00 |  | 原平台服务费 |
| change_request_time | Date | 必须 | 2023-09-23 12:00:00 |  | 变更请求发起时间 |
| kox_commission_fee | String | 可选 | 1.00 |  | 原达人费用 |
| media_event_id | String | 必须 | 123 |  | 媒体订单id |
| advertising_campaign_id | Number | 必须 | 123 |  | 子任务id |
| change_kox_commission_fee | String | 可选 | 1.00 |  | 变更后达人费用 |
| media_total_fee | String | 必须 | 1.00 |  | 原子任务总金额 |
| change_media_total_fee | String | 必须 | 1.00 |  | 变更后子任务总金额 |
| change_media_platform_fee | String | 可选 | 1.00 |  | 变更后平台服务费 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | MediaEventInfoDTO |  | 确认写入信息 |
| └ media_event_id | String | 123 | 媒体订单id |
| result_code | Number | 200 | 返回码 |
| biz_error_desc | String | result | 错误码释义:子任务状态不受理、有进行中的子任务改价 |
| result_msg | String | result | 返回码 |
| biz_error_code | Number | 40132 | 40132,40133 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.seed.event.fee.update', {
	'change_request_id':'123',
	'change_type':'1',
	'media_platform_fee':'1.00',
	'change_request_time':'2023-09-23 12:00:00',
	'kox_commission_fee':'1.00',
	'media_event_id':'123',
	'advertising_campaign_id':'123',
	'change_kox_commission_fee':'1.00',
	'media_total_fee':'1.00',
	'change_media_total_fee':'1.00',
	'change_media_platform_fee':'1.00'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_seed_event_fee_update_response":{
        "data":{
            "media_event_id":"123"
        },
        "result_code":200,
        "biz_error_desc":"result",
        "result_msg":"result",
        "biz_error_code":40132
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.seed.event.fee.update.result.get（淘宝客-推广者-种草商单子任务改价结果查询）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| advertising_campaign_id_list | Number | 可选 | 1,2,3 |  | 子任务id列表 |
| page_no | Number | 可选 | 1 |  | 页码 |
| page_size | Number | 可选 | 20 |  | 页容 |
| request_status | Number | 可选 | 2 |  | 子任务变更状态 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | PageResult |  | 返回对象 |
| └ page_no | Number | 1 | 页码 |
| └ page_size | Number | 20 | 页容 |
| └ total_count | Number | 100 | 总数 |
| └ result | MediaEventUpdateInfoDTO

                                 [] |  | 数据列表 |
| └ change_request_id | String | 123 | 变更请求id |
| └ change_request_time | Date | 2023-09-23 12:00:00 | 变更请求发起时间 |
| └ change_type | Number | 0 | 变更类型 -1：减少预算 1：增加预算 |
| └ advertising_campaign_id | Number | 123 | 子任务id |
| └ media_event_id | String | 123 | 媒体订单id |
| └ media_total_fee | String | 1.00 | 原子任务总金额 |
| └ kox_commission_fee | String | 1.00 | 原达人费用 |
| └ media_platform_fee | String | 1.00 | 原平台服务费 |
| └ change_media_total_fee | String | 1.00 | 变更后子任务总金额 |
| └ change_kox_commission_fee | String | 1.00 | 变更后达人费用 |
| └ change_media_platform_fee | String | 1.00 | 变更后平台服务费 |
| └ change_response_time | Date | 2023-09-23 12:00:00 | 星任务受理时间 |
| └ client_operate_time | Date | 2023-09-23 12:00:00 | 客户操作时间 |
| └ change_result | Number | 3 | 变更结果 2：变更待审核 3：同意变更 4：拒绝变更 5：变更处理中 -1：变更失效 |
| └ refuse_type | Number | 1 | 拒绝类型 0：用户拒绝变更 1：订单被拒绝 2：子任务被取消 |
| result_code | Number | 200 | 返回码 |
| biz_error_desc | String | "result" | 错误码释义 |
| result_msg | String | "result" | 返回码释义 |
| biz_error_code | Number | 0 | 错误码 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.seed.event.fee.update.result.get', {
	'advertising_campaign_id_list':'1,2,3',
	'page_no':'1',
	'page_size':'20',
	'request_status':'2'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_seed_event_fee_update_result_get_response":{
        "data":{
            "page_no":1,
            "page_size":20,
            "total_count":100,
            "result":{
                "media_event_update_info_d_t_o":[
                    {
                        "change_request_id":"123",
                        "change_request_time":"2023-09-23 12:00:00",
                        "change_type":0,
                        "advertising_campaign_id":123,
                        "media_event_id":"123",
                        "media_total_fee":"1.00",
                        "kox_commission_fee":"1.00",
                        "media_platform_fee":"1.00",
                        "change_media_total_fee":"1.00",
                        "change_kox_commission_fee":"1.00",
                        "change_media_platform_fee":"1.00",
                        "change_response_time":"2023-09-23 12:00:00",
                        "client_operate_time":"2023-09-23 12:00:00",
                        "change_result":3,
                        "refuse_type":1
                    }
                ]
            }
        },
        "result_code":200,
        "biz_error_desc":"\"result\"",
        "result_msg":"\"result\"",
        "biz_error_code":0
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.rta.uvid.get（淘宝客-推广者-厂商版加密用户标识获取）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| rta_id | String | 必须 | xx |  | 同步设备时指定的rtaId |
| manufacturer | String | 必须 | huawei |  | huawei-华为，rongyao-荣耀，oppo-oppo，vivo-vivo，xiaomi-小米，rongyaoNetwork-荣耀网络消息 |
| cursor | String | 可选 | 11 |  | 位点游标 |
| page_size | Number | 必须 | 10 | 默认值：10 | 每页大小，最大10 |
| main_accountid | Number | 可选 | 123123 |  | 联盟账号组的主账号ID,传入时使用账号组维度创建 |
| rta_type | Number | 可选 | 1 |  | rta类型，0-厂商rta，1-联盟rta |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| has_more | Boolean | true | 是否有下一页，true-有，false-没有 |
| cursor | String | 11 | 位点游标，请求下一页数据时原样传入 |
| result_list | String [] | xx | uvid列表 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.rta.uvid.get', {
	'rta_id':'xx',
	'manufacturer':'huawei',
	'cursor':'11',
	'page_size':'10',
	'main_accountid':'123123',
	'rta_type':'1'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_rta_uvid_get_response":{
        "has_more":true,
        "cursor":"11",
        "result_list":{
            "string":[
                "xx"
            ]
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.feed.order.check（淘宝客-推广者-内容种草投流对账单）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| media_order_id | String | 必须 | 123 |  | 媒体订单id |
| page_no | Number | 可选 | 1 |  | 分页码，默认1 |
| page_size | Number | 可选 | 10 |  | 页大小，默认10 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | MediaOrderDTO |  | 结果数据 |
| └ media_order_id | String | 123 | 媒体账单id |
| └ cost_amount | Number | 10000 | 实际结算总金额 |
| └ result | OrderDetailDTO

                                 [] |  | 结果列表 |
| └ media_order_id | String | 123 | 媒体账单id |
| └ order_dimision_id | String | 123 | 订单维度id（例如：星任务id） |
| └ total_frozen_amount | Number | 10000 | 总冻结金额（分） |
| └ historical_settled_amount | Number | 10000 | 历史已打款金额（分 ） |
| └ this_time_cost_amount | Number | 10000 | 本次请求金额（分） |
| └ this_time_real_settled_amount | Number | 10000 | 本次结算金额（分） |
| └ status | Number | 1 | 账单状态 1.打款成功，2.打款失败 |
| └ page_no | Number | 1 | 页码，从1开始 |
| └ page_size | Number | 50 | 页大小 |
| result_code | Number | 200 | 结果码 |
| biz_error_desc | String | 系统异常 | 业务错描述 |
| result_msg | String | 内部服务发生错误 | 详细描述 |
| biz_error_code | Number | 1001 | 业务错误码 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.feed.order.check', {
	'media_order_id':'123',
	'page_no':'1',
	'page_size':'10'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_feed_order_check_response":{
        "data":{
            "media_order_id":"123",
            "cost_amount":10000,
            "result":{
                "order_detail_d_t_o":[
                    {
                        "media_order_id":"123",
                        "order_dimision_id":"123",
                        "total_frozen_amount":10000,
                        "historical_settled_amount":10000,
                        "this_time_cost_amount":10000,
                        "this_time_real_settled_amount":10000,
                        "status":1
                    }
                ]
            },
            "page_no":1,
            "page_size":50
        },
        "result_code":200,
        "biz_error_desc":"系统异常",
        "result_msg":"内部服务发生错误",
        "biz_error_code":1001
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.interest.items.get（淘宝客-推广者-厂商版-个性化推荐商品获取）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| page_size | Number | 可选 | 20 | 默认值：20 | 页大小，默认20，1~100 |
| page_no | Number | 可选 | 1 | 默认值：1 | 第几页，默认：1 |
| material_id | Number | 必须 | 123 |  | 官方提供的物料Id；可以通过taobao.tbk.optimus.tou.material.ids.get接口获取公开的物料id列表或查看物料id汇总贴：https://market.m.taobao.com/app/qn/toutiao-new/index-pc.html#/detail/10628875?_k=gpov9a |
| adzone_id | Number | 必须 | 123 |  | 推广位id，mm_xxx_xxx_12345678三段式的最后一段数字（登录pub.alimama.com推广管理-推广位管理中查询） |
| device_type | String | 可选 | IMEI |  | 智能匹配-设备号类型：IMEI，或者IDFA，或者UTDID（UTDID不支持MD5加密），或者OAID；使用智能推荐请先签署协议https://pub.alimama.com/fourth/protocol/common.htm?key=hangye_laxin |
| device_value | String | 可选 | xxx |  | 智能匹配-设备号加密后的值（MD5加密需32位小写）；使用智能推荐请先签署协议https://pub.alimama.com/fourth/protocol/common.htm?key=hangye_laxin |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result_list | MapData [] |  | resultList |
| └ item_id | String | qeqscd1231-uqwenqe | 商品信息-淘宝客新商品id；使用说明参考《淘宝客新商品ID升级》白皮书：https://www.yuque.com/taobaolianmengguanfangxiaoer/zmig94/tfyt0pahmlpzu2ud |
| └ item_basic_info | BasicMapData |  | 商品基础信息 |
| └ title | String | 复古女裤子秋冬九分裤萝卜裤显瘦高腰韩版2017新款 | 商品信息-商品标题 |
| └ short_title | String | 九分裤显瘦高腰韩版 | 商品信息-商品短标题 |
| └ pict_url | String | //img.alicdn.com/bao/uploaded/i4/745957850/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg | 商品信息-商品主图 |
| └ white_image | String | https://img.alicdn.com/bao/uploaded/i4/745957850/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg | 商品信息-商品白底图 |
| └ level_one_category_id | Number | 1 | 商品信息-一级类目ID |
| └ level_one_category_name | String | 美妆 | 商品信息-一级类目名称 |
| └ category_id | Number | 162201 | 商品信息-叶子类目id |
| └ category_name | String | 牛仔裤 | 商品信息-叶子类目名称 |
| └ seller_id | Number | 123 | 店铺信息-卖家id |
| └ user_type | Number | 1 | 店铺信息-卖家类型，0表示淘宝，1表示天猫，3表示特价版 |
| └ shop_title | String | 魔黛娅内衣旗舰店 | 店铺信息-店铺名称 |
| └ volume | Number | 30 | 商品信息-30天销量；数据统计截止昨日非实时更新 |
| └ sub_title | String | 吉品鲍鱼 关西参 | 商品信息-商品子标题 |
| └ brand_name | String | 淘宝心选 | 商品信息-品牌名称 |
| └ annual_vol | String | 1万+ | 年销量 |
| └ price_promotion_info | PromotionInfoMapData |  | 价格促销信息 |
| └ reserve_price | String | 102.00 | 商品信息-一口价通常显示为划线价 |
| └ zk_final_price | String | 79.9 | 促销信息-销售价格，无促销时等于一口价，有促销时为促销价。若属于预售商品，付定金时间内，在线售卖价=预售价 |
| └ final_promotion_price | String | 69.9 | 促销信息-预估到手价(元)。若属于预售商品，付定金时间内，预估到手价价=定金+尾款的预估到手价 |
| └ final_promotion_path_list | FinalPromotionPathMapData

                                 [] |  | 到手价优惠路径列表 |
| └ promotion_title | String | 商品券 | 优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 满7999减1300 | 优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_fee | String | 1300.00 | 实际优惠金额（元） |
| └ promotion_start_time | String | 1661184000000 | 优惠开始时间 |
| └ promotion_end_time | String | 1661788799000 | 优惠结束时间 |
| └ promotion_id | String | xx | 优惠ID |
| └ future_activity_promotion_price | String | 99.5 | 预热预估到手价（元） |
| └ future_activity_promotion_path_list | FutureActivityPromotionPathMapData

                                 [] |  | 预热到手价优惠路径列表 |
| └ promotion_title | String | 商品券 | 预热优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 满7999减1300 | 预热优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_fee | String | 1300.00 | 预热实际优惠金额（元） |
| └ promotion_start_time | String | 1661184000000 | 优惠开始时间 |
| └ promotion_end_time | String | 1661788799000 | 优惠结束时间 |
| └ promotion_tag_list | PromotionTagMapData

                                 [] |  | 标签信息列表 |
| └ tag_name | String | 88VIP | 标签名称，如“88VIP”、“花呗免息”、“猫超买返”、“是否包邮” |
| └ predict_rounding_up_price | String | 56.1 | 促销信息-预估凑单价（元）。预估凑单叠加优惠后的商品单价 |
| └ predict_rounding_up_price_desc | String | 需买1件 | 促销信息-凑单价说明，描述凑单价的实现说明。如 “可凑单”或“需买X件” |
| └ more_promotion_list | MorePromotionMapData

                                 [] |  | 更多活动优惠 |
| └ promotion_title | String | 满件折 | 预热优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 2件9折 | 预热优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_start_time | String | 1661222400000 | 优惠开始时间 |
| └ promotion_end_time | String | 1662393600000 | 优惠结束时间 |
| └ promotion_id | String | xx | 优惠ID |
| └ predict_rounding_up_path_list | PredictRoundingUpPathMapData

                                 [] |  | 预估凑单优惠路径 |
| └ promotion_title | String | 店铺优惠 | 优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 再买1件，可参与2件5折 | 优惠利益点文案，如“2件5折”、“每200减20”等 |
| └ publish_info | PublishInfo |  | 淘客推广信息 |
| └ income_rate | String | 5.50 | 商品信息-收入比率(%)；商品佣金比率+补贴比率 |
| └ click_url | String | //item.taobao.com/item.htm?id=556633720749&scm=1007.16190.92234.0&pvid=41362290-fa0b-4252-b172-6afc9c00e2c8&app_pvid=0ab0fac715095507006577956e | 链接-宝贝推广链接 |
| └ coupon_share_url | String | //uland.taobao.com/coupon/edetail?e=pR6YtnFKK%2B8GQASttHIRqcEWOmlidB03Pf45HLyCqA8dRAklSM5tEQ36hBQToU3M3MmLjFwLsqgZxcV7BPtHQDd2Naqom0e0&mt=1&app_pvid=0ab0fac715095507006577956e&ptl=app_pvid:0ab0fac715095507006577956e;tpp_pvid:41362290-fa0b-4252-b172-6afc9c00e2c8 | 链接-宝贝+券二合一页面链接 |
| └ sp_campaign_list | SpCampaign

                                 [] |  | 定向计划集合-仅支持联系商务或运营小二申请定向计划合集字段权限 |
| └ sp_cid | String | 123 | 定向计划活动ID |
| └ sp_name | String | 定向计划活动1 | 定向计划名称 |
| └ sp_rate | String | 1550表示15.5% | 定向佣金率 |
| └ sp_lock_status | String | 0 | 定向是否锁佣，0=不锁佣 1=锁佣 |
| └ sp_apply_link | String | http://pub.alimama.com/portal/promo/shop/campaign/detail.htm?mode=info&campaignId=1000492470&creatorId=98836808&breadcrumb=false | 定向计划申请链接 |
| └ sp_status | String | 1 | 定向计划是否可用 1-可用 0-不可用 |
| └ future_activity_commission_rate | String | 1550表示15.5% | 预热活动到手价对应的佣金比率 |
| └ future_activity_time | String | 1665504000000 | 预热价活动开始时间 |
| └ income_info | IncomeInfo |  | 商品佣金信息 |
| └ commission_rate | String | 55 | 商品佣金比率 |
| └ commission_amount | String | 12 | 商品佣金金额 |
| └ subsidy_rate | String | 11 | 补贴比率 |
| └ subsidy_amount | String | 4 | 补贴金额 |
| └ subsidy_upper_limit | String | 10 | 补贴上限；仅在单笔订单命中补贴上限时返回结果否则出参为空 |
| └ cpa_reward_type | String | 0 1 2 | 额外奖励活动类型，如果一个商品有多个奖励类型，返回结果使用空格分割，0=预售单单奖励，1=618超级U选单单补 |
| └ cpa_reward_amount | String | 1.11 2.22 3.21 | 额外奖励活动金额，活动奖励金额的类型与cpa_reward_type字段对应，如果一个商品有多个奖励类型，返回结果使用空格分割 |
| └ tmall_rank_info | TmallRankInfo |  | 天猫榜单信息 |
| └ tmall_rank_text | String | 白茶热销榜·第5名 | 榜单排行描述 |
| └ tmall_rank_url | String | https://pages.tmall.com/wow/a/act/tmall/dailygroup/16220/16661/wupr?wh_pid=daily-459438&disableNav=YES | 榜单url |
| └ presale_info | PresaleInfo |  | 预售信息 |
| └ presale_start_time | Number | 1567440000000 | 预售商品-付定金开始时间（毫秒） |
| └ presale_end_time | Number | 1567440000000 | 预售商品-付定金结束时间（毫秒） |
| └ presale_tail_start_time | Number | 1567440000000 | 预售商品-付尾款开始时间（毫秒） |
| └ presale_tail_end_time | Number | 1567440000000 | 预售商品-付尾款结束时间（毫秒） |
| └ presale_deposit | String | 100 | 预售商品-定金（元） |
| └ presale_discount_fee_text | String | 付定金立减5元 | 预售商品-优惠信息 |
| └ favorites_info | FavoritesInfo |  | 选品库信息 |
| └ total_count | Number | 100 | 选品库收藏夹总数量 |
| └ favorites_list | FavoritesDetail

                                 [] |  | 选品库收藏夹详细信息 |
| └ favorites_id | Number | 12334 | 选品库收藏夹id |
| └ favorites_title | String | 测试选品库 | 选品库收藏夹标题 |
| └ topn_info | TopNInfoDTO |  | 前N件佣金信息-前N件佣金生效或预热时透出以下字段 |
| └ topn_quantity | Number | 3000 | 前N件剩余库存 |
| └ topn_total_count | Number | 3000 | 前N件初始总库存 |
| └ topn_start_time | String | 1937297392332 | 前N件佣金开始时间 |
| └ topn_end_time | String | 1937297392332 | 前N件佣金结束时间 |
| └ topn_rate | String | 30 | 前N件佣金率 |
| └ scope_info | ScopeInfo |  | 商品库范围信息 |
| └ superior_brand | String | 1 | 是否品牌精选，0不是，1是 |
| is_default | String | false | 推荐信息-是否抄底 |
| total_count | Number | 100 | 商品总数-该选品库收藏夹id及官方物料id对应的商品数量 |
| uvid_msg | String | 123 | uvid结果信息，传入但未使用uvid时会返回原因 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.interest.items.get', {
	'page_size':'20',
	'page_no':'1',
	'material_id':'123',
	'adzone_id':'123',
	'device_type':'IMEI',
	'device_value':'xxx'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_interest_items_get_response":{
        "result_list":{
            "map_data":[
                {
                    "item_id":"qeqscd1231-uqwenqe",
                    "item_basic_info":{
                        "title":"复古女裤子秋冬九分裤萝卜裤显瘦高腰韩版2017新款",
                        "short_title":"九分裤显瘦高腰韩版",
                        "pict_url":"\/\/img.alicdn.com\/bao\/uploaded\/i4\/745957850\/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg",
                        "white_image":"https:\/\/img.alicdn.com\/bao\/uploaded\/i4\/745957850\/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg",
                        "level_one_category_id":1,
                        "level_one_category_name":"美妆",
                        "category_id":162201,
                        "category_name":"牛仔裤",
                        "seller_id":123,
                        "user_type":1,
                        "shop_title":"魔黛娅内衣旗舰店",
                        "volume":30,
                        "sub_title":"吉品鲍鱼 关西参",
                        "brand_name":"淘宝心选",
                        "annual_vol":"1万+"
                    },
                    "price_promotion_info":{
                        "reserve_price":"102.00",
                        "zk_final_price":"79.9",
                        "final_promotion_price":"69.9 ",
                        "final_promotion_path_list":{
                            "final_promotion_path_map_data":[
                                {
                                    "promotion_title":"商品券",
                                    "promotion_desc":"满7999减1300",
                                    "promotion_fee":"1300.00",
                                    "promotion_start_time":"1661184000000",
                                    "promotion_end_time":"1661788799000",
                                    "promotion_id":"xx"
                                }
                            ]
                        },
                        "future_activity_promotion_price":"99.5",
                        "future_activity_promotion_path_list":{
                            "future_activity_promotion_path_map_data":[
                                {
                                    "promotion_title":"商品券",
                                    "promotion_desc":"满7999减1300",
                                    "promotion_fee":"1300.00",
                                    "promotion_start_time":"1661184000000",
                                    "promotion_end_time":"1661788799000"
                                }
                            ]
                        },
                        "promotion_tag_list":{
                            "promotion_tag_map_data":[
                                {
                                    "tag_name":"88VIP"
                                }
                            ]
                        },
                        "predict_rounding_up_price":"56.1",
                        "predict_rounding_up_price_desc":"需买1件",
                        "more_promotion_list":{
                            "more_promotion_map_data":[
                                {
                                    "promotion_title":"满件折",
                                    "promotion_desc":"2件9折",
                                    "promotion_start_time":"1661222400000",
                                    "promotion_end_time":"1662393600000",
                                    "promotion_id":"xx"
                                }
                            ]
                        },
                        "predict_rounding_up_path_list":{
                            "predict_rounding_up_path_map_data":[
                                {
                                    "promotion_title":"店铺优惠",
                                    "promotion_desc":"再买1件，可参与2件5折"
                                }
                            ]
                        }
                    },
                    "publish_info":{
                        "income_rate":"5.50",
                        "click_url":"\/\/item.taobao.com\/item.htm?id=556633720749&scm=1007.16190.92234.0&pvid=41362290-fa0b-4252-b172-6afc9c00e2c8&app_pvid=0ab0fac715095507006577956e",
                        "coupon_share_url":"\/\/uland.taobao.com\/coupon\/edetail?e=pR6YtnFKK%2B8GQASttHIRqcEWOmlidB03Pf45HLyCqA8dRAklSM5tEQ36hBQToU3M3MmLjFwLsqgZxcV7BPtHQDd2Naqom0e0&mt=1&app_pvid=0ab0fac715095507006577956e&ptl=app_pvid:0ab0fac715095507006577956e;tpp_pvid:41362290-fa0b-4252-b172-6afc9c00e2c8",
                        "sp_campaign_list":{
                            "sp_campaign":[
                                {
                                    "sp_cid":"123",
                                    "sp_name":"定向计划活动1",
                                    "sp_rate":"1550表示15.5%",
                                    "sp_lock_status":"0",
                                    "sp_apply_link":"http:\/\/pub.alimama.com\/portal\/promo\/shop\/campaign\/detail.htm?mode=info&campaignId=1000492470&creatorId=98836808&breadcrumb=false",
                                    "sp_status":"1"
                                }
                            ]
                        },
                        "future_activity_commission_rate":"1550表示15.5%",
                        "future_activity_time":"1665504000000",
                        "income_info":{
                            "commission_rate":"55",
                            "commission_amount":"12",
                            "subsidy_rate":"11",
                            "subsidy_amount":"4",
                            "subsidy_upper_limit":"10"
                        },
                        "cpa_reward_type":"0 1 2",
                        "cpa_reward_amount":"1.11 2.22 3.21"
                    },
                    "tmall_rank_info":{
                        "tmall_rank_text":"白茶热销榜·第5名",
                        "tmall_rank_url":"https:\/\/pages.tmall.com\/wow\/a\/act\/tmall\/dailygroup\/16220\/16661\/wupr?wh_pid=daily-459438&disableNav=YES"
                    },
                    "presale_info":{
                        "presale_start_time":1567440000000,
                        "presale_end_time":1567440000000,
                        "presale_tail_start_time":1567440000000,
                        "presale_tail_end_time":1567440000000,
                        "presale_deposit":"100",
                        "presale_discount_fee_text":"付定金立减5元"
                    },
                    "favorites_info":{
                        "total_count":100,
                        "favorites_list":{
                            "favorites_detail":[
                                {
                                    "favorites_id":12334,
                                    "favorites_title":"测试选品库"
                                }
                            ]
                        }
                    },
                    "topn_info":{
                        "topn_quantity":3000,
                        "topn_total_count":3000,
                        "topn_start_time":"1937297392332",
                        "topn_end_time":"1937297392332",
                        "topn_rate":"30"
                    },
                    "scope_info":{
                        "superior_brand":"1"
                    }
                }
            ]
        },
        "is_default":"false",
        "total_count":100,
        "uvid_msg":"123"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.content.general.link.convert（淘宝客-推广者-内容三方万能转链）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| sub_pid | String | 必须 | mm_123_123_123 |  | 三方推广者pid |
| item_dto | LkItemDTO | 可选 |  |  | 商品三方转链 |
| page_dto | LkItemDTO | 可选 |  |  | 会场页面三方转链 |
| shop_dto | LkPageDTO | 可选 |  |  | 店铺三方转链 |
| material_dto | LkShopDTO | 可选 |  |  | 链接三方转链 |
| adzone_id | String | 必须 | 123 |  | 推广位ID |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | TbkLinkDTO |  | 转链结果 |
| └ material_url_list | MaterialUrlList

                                 [] |  | 链接/口令转链结果 |
| └ code | Number | 1001 | 物料对应错误码 |
| └ msg | String | 无权限 | 物料对应错误描述 |
| └ extra_info | String | skuid已失效 | 转链成功的场景下，需要补充说明的信息 |
| └ input_material_url | String | s.click.taobao.com | 入参物料链接 |
| └ link_info_dto | UrlLinkInfoDTO |  | 链接信息 |
| └ coupon_long_url | String | https://uland.taobao.com/coupon/edetail?e=HcDWJQP6d12lhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJDtOYUTZvUxMupZB35fyH%2Bj%2BFrYU%2BROQkienhT0Gv%2FXXPpGXqwTrgn%2FiLFm3yG1xo9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmghqozJdwyPlqXT8BNPyRO3CWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOghqozJdwyPlaVcuzWAzoR%2BEffiaBagqGwiV9Bh6z0Brrk5oEZwv0ZJMDQVG07AK7A%3D%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01 | 二合一长链接 |
| └ material_type | Number | 1 | 1—单品 2—店铺 3—会场 4-承接开放 5-优惠券 |
| └ cps_long_url | String | https://s.click.taobao.com/t?e=m%3D2%26s%3DKkbloP8JSAVw4vFB6t2Z2ueEDrYVVa64yK8Cckff7TVRAdhuF14FMU3VlJUC3DsQ79%2FTFaMDK6Qc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQEVUjoeWqzb%2BCGsxm48e9hkfF%2Bxu0N%2BwWs0Rgp8gMc9dY1tyQTTDSHqySbHmSI7wOtef%2FroYqRldzn0lFpzXFujTCQ%2BHTk5EfzW8%2BBPSvjFWUZSZEfZ0FH4Va78Lza%2BD%2Fuqo6mSuTG7PlEs8HjV3hrkr1j%2BhoHy6%2FQNdzcFFug%2BbPXd6fR%2Fgq%2FLkcuZKrbdCBTlriuf8gGMP3mPUmtHv0Nb2kE%2BTfvdp4q7CEA%2B11P8YwWLI0fvJc3aqk5eKOUwbKCMNd%2Byi53bExg5p7bh%2BFbQ%3D&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01 | CPS链接长链 |
| └ cps_short_tpwd | String | ￥zRmVdesjTCu￥ | CPS链接的短口令 |
| └ coupon_short_tpwd | String | ￥p7lYdesjTCG￥ | 二合一链接的短口令 |
| └ cps_short_url | String | https://s.click.taobao.com/CvHjOPu | CPS链接短链 |
| └ coupon_short_url | String | https://s.click.taobao.com/DvHjOPu | 二合一链接长链 |
| └ coupon_full_tpwd | String | 47￥ CZ3457 p7lYdesjTCG￥ https://m.tb.cn/h.UQ4ceEA  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装 | 二合一链接的长口令 |
| └ cps_full_tpwd | String | 39￥ CZ3457 zRmVdesjTCu￥ https://m.tb.cn/h.UQ4cewa  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装 | CPS链接的长口令 |
| └ tk_biz_type | Number | 2 | 1-联盟口令，2-主站口令。入参物料不为淘口令时，此字段返回null |
| └ coupon_info_dto | UrlCouponInfoDTO |  | 券信息 |
| └ coupon_end_time | String | 2022-12-20 23:59:59 | 优惠券结束时间 |
| └ activity_id | String | 19d114f1a6464c98a30b01b3cb17dad6 | 券ID |
| └ coupon_remain_count | Number | 99944 | 优惠券剩余数量 |
| └ coupon_amount | String | 80.00 | 券面额 |
| └ coupon_start_time | String | 2022-12-14 00:00:00 | 优惠券开始时间 |
| └ coupon_desc | String | 满129元减80元 | 优惠券信息，满XX元减XX元 |
| └ coupon_type | Number | 0 | 0-店铺 1-单品 |
| └ promotion_info_dto | UrlPromotionInfoDTO |  | 营销信息 |
| └ commission_rate | String | 6.00 | 商品收入比率(%)：商品佣金比率+补贴比率。同物料类接口income_rate |
| └ commission_type | String | MKT | 佣金类型。MKT表示营销计划，SP表示定向计划，COMMON表示通用计划，ZX表示自选计划 |
| └ shop_url_list | ShopUrlList

                                 [] |  | 店铺转链结果 |
| └ code | Number | 1001 | 物料对应错误码 |
| └ msg | String | 无权限 | 物料对应错误描述 |
| └ input_shop_id | String | 123456 | 卖家ID |
| └ link_info_dto | ShopLinkInfoDTO | link_info_dto | 链接信息 |
| └ seller_id | String | 123456 | 卖家ID |
| └ cps_long_url | String | https://s.click.taobao.com/t?e=m%3D2%26s%3DYryVaqQlYtxw4vFB6t2Z2jAVflQIoZepyK8Cckff7TVRAdhuF14FMU3VlJUC3DsQMMgx22UI05Yc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQJFcOCF3%2FDbwRh53k%2Fssh4t44u6hki9mkh%2BLdPuJoV%2FRzl3tHIK2mthnPjZ5WWqolAEgO5kclpNKBjInADNbJYxEcfNLn7HIXszVe3Fb2x4s%2FJDmTntQaQzGDmntuH4VtA%3D%3D | 店铺CPS长链接 |
| └ cps_short_url | String | https://s.click.taobao.com/FvHjOPu | 店铺CPS短链 |
| └ cps_full_tpwd | String | 58￥ CZ3457 EAqldesjTCt￥ https://m.tb.cn/h.UQ4ceEB  韩都衣舍旗舰店 | 店铺CPS链接对应长口令 |
| └ cps_short_tpwd | String | ￥EAqldesjTCt￥ | 店铺CPS链接对应短口令 |
| └ event_url_list | EventUrlList

                                 [] |  | 会场页面转链结果 |
| └ code | Number | 1001 | 物料对应错误码 |
| └ msg | String | 无权限 | 物料对应错误描述 |
| └ input_page_id | String | 203567898765 | 入参的会场ID |
| └ link_info_dto | EventLinkInfoDTO | link_info_dto | 链接信息 |
| └ page_id | String | 20150318020014311 | 会场ID |
| └ cps_long_url | String | https://s.click.taobao.com/t?union_lens=lensId%3AOPT%401671517838%402107457f_128d_1852e3a1e2c_03f5%4001%3BeventPageId%3A20150318020014311&e=m%3D2%26s%3DKQjjrM92%2F7Nw4vFB6t2Z2iperVdZeJviU%2F9%2F0taeK29yINtkUhsv0Dl8FS4ucHenj2w9k21YZ3qgpaE1qudUv106NgiXS75NWi4GdVwNf8BfXAlTvwP7PvyclHulJsGMQ%2BNeRhkrKyfCg%2Fx6BHtN2amAOqUjIVeCy0DxCSzwFgFd1le1%2FF%2FLHa44ut0dMc8VMSJUXveljqoq%2FKh6EC%2FmGEM6gfQ3Aokl5MRYl0%2FyOZHb9no%2FURc5w7o18kPD%2BYRAFveQ9Ld2jorKLJiYzWv6xmKche5LvsSo37%2FLmqNFMyVzwS6VTp1JIFY8eNWMEbfNhDTn1psj9iZsDvbh8Qt7h8A2xIPV%2FpBCPqKNE1%2B%2FpYNizQgXEDae2m%2FrHB9aiVckS6fqAUnbbCiWZ1rWjVK6iMgmy2CsK7djvdOCkVnjXedCpzLnRBhrs1VdGRk68r9XJprbVzmT5j1Xj8w0BzyaviGFCzYOOqAQ | 会场CPS长链接 |
| └ cps_short_tpwd | String | ￥PnIodeIlU9z￥ | 会场CPS链接的短口令 |
| └ cps_short_url | String | https://s.click.taobao.com/EvHjOPu | 会场CPS短链接 |
| └ cps_full_tpwd | String | 37￥ CZ3457 PnIodeIlU9z￥ https://m.tb.cn/h.UQ4ceEz  22年天猫双旦礼遇季-主会场 | 会场CPS链接的长口令 |
| └ item_url_list | ItemUrlList

                                 [] |  | 商品转链结果 |
| └ input_item_id | String | i87a9ja90d8-09qrjcoa7qwl | 入参的商品ID |
| └ extra_info | String | skuid已失效 | 转链成功的场景下，需要补充说明的信息 |
| └ promotion_info_dto | PromotionInfoDTO | PromotionInfoDTO | 营销信息 |
| └ commission_rate | String | 2.40 | 商品收入比率(%)：商品佣金比率+补贴比率。同物料类接口income_rate |
| └ commission_type | String | MKT | 佣金类型。MKT表示营销计划，SP表示定向计划，COMMON表示通用计划，ZX表示自选计划 |
| └ code | Number | 1001 | 物料对应错误码 |
| └ msg | String | 无权限 | 物料对应错误描述 |
| └ link_info_dto | ItemLinkInfoDTO | ItemLinkInfoDTO | 链接信息 |
| └ coupon_long_url | String | https://uland.taobao.com/coupon/edetail?e=G6GuYx3ILfalhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJtx9C1Z8GbV1vHgx4K91Wrd9oW7c0CRLBdz881e47Ft9oBDRNgYIxgFNRd9B4OBPr9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmrRMCeO3Mi1ouPODd%2FkGgeDCWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOrRMCeO3Mi1oDb9krsjLiJ069NSKr8HLD%2F5cBb8E%2Fg255M0kZg5qGOw%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01 | 二合一长链接 |
| └ material_type | Number | 1 | 1—单品 2—店铺 3—会场 |
| └ item_id | String | y387e49cRt262Ozub0TvtA-dAeOMBinqPdm6Wxu0 | 商品ID |
| └ cps_long_url | String | https://s.click.taobao.com/t?e=m%3D2%26s%3DvazOG0sd5LJw4vFB6t2Z2ueEDrYVVa64yK8Cckff7TVRAdhuF14FMU3VlJUC3DsQMMgx22UI05Yc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQEVUjoeWqzb%2BCGsxm48e9hkfF%2Bxu0N%2BwWrcZhRlC%2FudiDepej5CXPoiMHuv7RoNv0Q0jFsbsQ7KW1Te9msJWkXsmFF9fm0wobpd0%2BQldqeoBF76lcPm%2FucppnJfkRUzuToD2uOlbI2qURHUT0gmVRp7ZGL0GbiMMd6BniEC%2BBYvRVSjzVV%2FKpYdMm7k2GPZX7L96ZdZH32PNybxY5kax0%2FETNqkNLIJLJkR1E9IJlUaerji63R0xzxUxIlRe96WOqlr6NugmfTu3&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01 | CPS链接长链 |
| └ cps_short_tpwd | String | ￥XODHdeIlU9B￥ | CPS链接的短口令 |
| └ coupon_short_tpwd | String | ￥LOcqdeIlU9y￥ | 二合一链接的短口令 |
| └ cps_short_url | String | https://s.click.taobao.com/GvHjOPu | CPS链接短链 |
| └ coupon_short_url | String | https://s.click.taobao.com/HvHjOPu | 二合一链接长链 |
| └ coupon_full_tpwd | String | 48￥ CZ3457 LOcqdeIlU9y￥ https://m.tb.cn/h.UQ4ceEC  olayks煮茶器喷淋式黑茶白茶煮茶壶家用自动蒸汽养生壶办公室小型 | 二合一链接的长口令 |
| └ cps_full_tpwd | String | 47￥ CZ3457 XODHdeIlU9B￥ https://m.tb.cn/h.UQ4ceEy  olayks煮茶器喷淋式黑茶白茶煮茶壶家用自动蒸汽养生壶办公室小型 | CPS链接的长口令 |
| └ coupon_info_dto | ItemLinkInfoDTO |  | 券信息 |
| └ coupon_end_time | String | 2022-12-25 23:59:59 | 优惠券结束时间 |
| └ activity_id | String | 642208f7db6b4fb9880a9d09832d6b8d | 券ID |
| └ coupon_remain_count | Number | 99987 | 优惠券剩余数量 |
| └ coupon_amount | String | 170.00 | 券面额 |
| └ coupon_start_time | String | 2022-12-20 00:00:00 | 优惠券开始时间 |
| └ coupon_desc | String | 满319元减170元 | 优惠券信息，满XX元减XX元 |
| biz_error_desc | String | 1 | 见错误码描述 |
| result_msg | String | 1 | 见错误码描述 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.content.general.link.convert', {
	'sub_pid':'mm_123_123_123',
	'item_dto':'数据结构JSON示例',
	'page_dto':'数据结构JSON示例',
	'shop_dto':'数据结构JSON示例',
	'material_dto':'数据结构JSON示例',
	'adzone_id':'123'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_content_general_link_convert_response":{
        "data":{
            "material_url_list":{
                "material_url_list":[
                    {
                        "code":1001,
                        "msg":"无权限",
                        "extra_info":"skuid已失效",
                        "input_material_url":"s.click.taobao.com",
                        "link_info_dto":{
                            "coupon_long_url":"https:\/\/uland.taobao.com\/coupon\/edetail?e=HcDWJQP6d12lhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJDtOYUTZvUxMupZB35fyH%2Bj%2BFrYU%2BROQkienhT0Gv%2FXXPpGXqwTrgn%2FiLFm3yG1xo9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmghqozJdwyPlqXT8BNPyRO3CWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOghqozJdwyPlaVcuzWAzoR%2BEffiaBagqGwiV9Bh6z0Brrk5oEZwv0ZJMDQVG07AK7A%3D%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01",
                            "material_type":1,
                            "cps_long_url":"https:\/\/s.click.taobao.com\/t?e=m%3D2%26s%3DKkbloP8JSAVw4vFB6t2Z2ueEDrYVVa64yK8Cckff7TVRAdhuF14FMU3VlJUC3DsQ79%2FTFaMDK6Qc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQEVUjoeWqzb%2BCGsxm48e9hkfF%2Bxu0N%2BwWs0Rgp8gMc9dY1tyQTTDSHqySbHmSI7wOtef%2FroYqRldzn0lFpzXFujTCQ%2BHTk5EfzW8%2BBPSvjFWUZSZEfZ0FH4Va78Lza%2BD%2Fuqo6mSuTG7PlEs8HjV3hrkr1j%2BhoHy6%2FQNdzcFFug%2BbPXd6fR%2Fgq%2FLkcuZKrbdCBTlriuf8gGMP3mPUmtHv0Nb2kE%2BTfvdp4q7CEA%2B11P8YwWLI0fvJc3aqk5eKOUwbKCMNd%2Byi53bExg5p7bh%2BFbQ%3D&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01",
                            "cps_short_tpwd":"￥zRmVdesjTCu￥",
                            "coupon_short_tpwd":"￥p7lYdesjTCG￥",
                            "cps_short_url":"https:\/\/s.click.taobao.com\/CvHjOPu",
                            "coupon_short_url":"https:\/\/s.click.taobao.com\/DvHjOPu",
                            "coupon_full_tpwd":"47￥ CZ3457 p7lYdesjTCG￥ https:\/\/m.tb.cn\/h.UQ4ceEA  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装",
                            "cps_full_tpwd":"39￥ CZ3457 zRmVdesjTCu￥ https:\/\/m.tb.cn\/h.UQ4cewa  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装",
                            "tk_biz_type":2
                        },
                        "coupon_info_dto":{
                            "coupon_end_time":"2022-12-20 23:59:59",
                            "activity_id":"19d114f1a6464c98a30b01b3cb17dad6",
                            "coupon_remain_count":99944,
                            "coupon_amount":"80.00",
                            "coupon_start_time":"2022-12-14 00:00:00",
                            "coupon_desc":"满129元减80元",
                            "coupon_type":0
                        },
                        "promotion_info_dto":{
                            "commission_rate":"6.00",
                            "commission_type":"MKT"
                        }
                    }
                ]
            },
            "shop_url_list":{
                "shop_url_list":[
                    {
                        "code":1001,
                        "msg":"无权限",
                        "input_shop_id":"123456",
                        "link_info_dto":{
                            "seller_id":"123456",
                            "cps_long_url":"https:\/\/s.click.taobao.com\/t?e=m%3D2%26s%3DYryVaqQlYtxw4vFB6t2Z2jAVflQIoZepyK8Cckff7TVRAdhuF14FMU3VlJUC3DsQMMgx22UI05Yc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQJFcOCF3%2FDbwRh53k%2Fssh4t44u6hki9mkh%2BLdPuJoV%2FRzl3tHIK2mthnPjZ5WWqolAEgO5kclpNKBjInADNbJYxEcfNLn7HIXszVe3Fb2x4s%2FJDmTntQaQzGDmntuH4VtA%3D%3D",
                            "cps_short_url":"https:\/\/s.click.taobao.com\/FvHjOPu",
                            "cps_full_tpwd":"58￥ CZ3457 EAqldesjTCt￥ https:\/\/m.tb.cn\/h.UQ4ceEB  韩都衣舍旗舰店",
                            "cps_short_tpwd":"￥EAqldesjTCt￥"
                        }
                    }
                ]
            },
            "event_url_list":{
                "event_url_list":[
                    {
                        "code":1001,
                        "msg":"无权限",
                        "input_page_id":"203567898765",
                        "link_info_dto":{
                            "page_id":"20150318020014311",
                            "cps_long_url":"https:\/\/s.click.taobao.com\/t?union_lens=lensId%3AOPT%401671517838%402107457f_128d_1852e3a1e2c_03f5%4001%3BeventPageId%3A20150318020014311&e=m%3D2%26s%3DKQjjrM92%2F7Nw4vFB6t2Z2iperVdZeJviU%2F9%2F0taeK29yINtkUhsv0Dl8FS4ucHenj2w9k21YZ3qgpaE1qudUv106NgiXS75NWi4GdVwNf8BfXAlTvwP7PvyclHulJsGMQ%2BNeRhkrKyfCg%2Fx6BHtN2amAOqUjIVeCy0DxCSzwFgFd1le1%2FF%2FLHa44ut0dMc8VMSJUXveljqoq%2FKh6EC%2FmGEM6gfQ3Aokl5MRYl0%2FyOZHb9no%2FURc5w7o18kPD%2BYRAFveQ9Ld2jorKLJiYzWv6xmKche5LvsSo37%2FLmqNFMyVzwS6VTp1JIFY8eNWMEbfNhDTn1psj9iZsDvbh8Qt7h8A2xIPV%2FpBCPqKNE1%2B%2FpYNizQgXEDae2m%2FrHB9aiVckS6fqAUnbbCiWZ1rWjVK6iMgmy2CsK7djvdOCkVnjXedCpzLnRBhrs1VdGRk68r9XJprbVzmT5j1Xj8w0BzyaviGFCzYOOqAQ",
                            "cps_short_tpwd":"￥PnIodeIlU9z￥",
                            "cps_short_url":"https:\/\/s.click.taobao.com\/EvHjOPu",
                            "cps_full_tpwd":"37￥ CZ3457 PnIodeIlU9z￥ https:\/\/m.tb.cn\/h.UQ4ceEz  22年天猫双旦礼遇季-主会场"
                        }
                    }
                ]
            },
            "item_url_list":{
                "item_url_list":[
                    {
                        "input_item_id":"i87a9ja90d8-09qrjcoa7qwl",
                        "extra_info":"skuid已失效",
                        "promotion_info_dto":{
                            "commission_rate":"2.40",
                            "commission_type":"MKT"
                        },
                        "code":1001,
                        "msg":"无权限",
                        "link_info_dto":{
                            "coupon_long_url":"https:\/\/uland.taobao.com\/coupon\/edetail?e=G6GuYx3ILfalhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJtx9C1Z8GbV1vHgx4K91Wrd9oW7c0CRLBdz881e47Ft9oBDRNgYIxgFNRd9B4OBPr9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmrRMCeO3Mi1ouPODd%2FkGgeDCWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOrRMCeO3Mi1oDb9krsjLiJ069NSKr8HLD%2F5cBb8E%2Fg255M0kZg5qGOw%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01",
                            "material_type":1,
                            "item_id":"y387e49cRt262Ozub0TvtA-dAeOMBinqPdm6Wxu0",
                            "cps_long_url":"https:\/\/s.click.taobao.com\/t?e=m%3D2%26s%3DvazOG0sd5LJw4vFB6t2Z2ueEDrYVVa64yK8Cckff7TVRAdhuF14FMU3VlJUC3DsQMMgx22UI05Yc28yV8PhABoJJuMl5iAyh8VyU%2FTlgQj6ChAyn0B5LQEVUjoeWqzb%2BCGsxm48e9hkfF%2Bxu0N%2BwWrcZhRlC%2FudiDepej5CXPoiMHuv7RoNv0Q0jFsbsQ7KW1Te9msJWkXsmFF9fm0wobpd0%2BQldqeoBF76lcPm%2FucppnJfkRUzuToD2uOlbI2qURHUT0gmVRp7ZGL0GbiMMd6BniEC%2BBYvRVSjzVV%2FKpYdMm7k2GPZX7L96ZdZH32PNybxY5kax0%2FETNqkNLIJLJkR1E9IJlUaerji63R0xzxUxIlRe96WOqlr6NugmfTu3&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01",
                            "cps_short_tpwd":"￥XODHdeIlU9B￥",
                            "coupon_short_tpwd":"￥LOcqdeIlU9y￥",
                            "cps_short_url":"https:\/\/s.click.taobao.com\/GvHjOPu",
                            "coupon_short_url":"https:\/\/s.click.taobao.com\/HvHjOPu",
                            "coupon_full_tpwd":"48￥ CZ3457 LOcqdeIlU9y￥ https:\/\/m.tb.cn\/h.UQ4ceEC  olayks煮茶器喷淋式黑茶白茶煮茶壶家用自动蒸汽养生壶办公室小型",
                            "cps_full_tpwd":"47￥ CZ3457 XODHdeIlU9B￥ https:\/\/m.tb.cn\/h.UQ4ceEy  olayks煮茶器喷淋式黑茶白茶煮茶壶家用自动蒸汽养生壶办公室小型"
                        },
                        "coupon_info_dto":{
                            "coupon_end_time":"2022-12-25 23:59:59",
                            "activity_id":"642208f7db6b4fb9880a9d09832d6b8d",
                            "coupon_remain_count":99987,
                            "coupon_amount":"170.00",
                            "coupon_start_time":"2022-12-20 00:00:00",
                            "coupon_desc":"满319元减170元"
                        }
                    }
                ]
            }
        },
        "biz_error_desc":"1",
        "result_msg":"1"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.interest.items.get（淘宝客_推广者_个性化商品获取）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| material_id | Number | 可选 | 123 |  | 官方提供的物料Id |
| adzone_id | Number | 必须 | 123 |  | 推广位id，mm_xxx_xxx_12345678三段式的最后一段数字（登录pub.alimama.com推广管理-推广位管理中查询） |
| page_size | Number | 可选 | 20 | 默认值：20 | 页大小，默认20，1~100 |
| page_no | Number | 可选 | 1 | 默认值：1 | 第几页，默认：1 |
| device_type | String | 可选 | uvid |  | 智能匹配,支持uvid/scdId |
| device_value | String | 可选 | xxx |  | 智能匹配-uvid/scdId的值 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result_list | MapData [] |  | resultList |
| └ item_id | String | qeqscd1231-uqwenqe | 商品信息-淘宝客新商品id；使用说明参考《淘宝客新商品ID升级》白皮书：https://www.yuque.com/taobaolianmengguanfangxiaoer/zmig94/tfyt0pahmlpzu2ud |
| └ item_basic_info | BasicMapData |  | 商品基础信息 |
| └ title | String | 复古女裤子秋冬九分裤萝卜裤显瘦高腰韩版2017新款 | 商品信息-商品标题 |
| └ short_title | String | 九分裤显瘦高腰韩版 | 商品信息-商品短标题 |
| └ pict_url | String | //img.alicdn.com/bao/uploaded/i4/745957850/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg | 商品信息-商品主图 |
| └ white_image | String | https://img.alicdn.com/bao/uploaded/i4/745957850/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg | 商品信息-商品白底图 |
| └ level_one_category_id | Number | 1 | 商品信息-一级类目ID |
| └ level_one_category_name | String | 美妆 | 商品信息-一级类目名称 |
| └ category_id | Number | 162201 | 商品信息-叶子类目id |
| └ category_name | String | 牛仔裤 | 商品信息-叶子类目名称 |
| └ seller_id | Number | 123 | 店铺信息-卖家id |
| └ user_type | Number | 1 | 店铺信息-卖家类型，0表示淘宝，1表示天猫，3表示特价版 |
| └ shop_title | String | 魔黛娅内衣旗舰店 | 店铺信息-店铺名称 |
| └ volume | Number | 30 | 商品信息-30天销量；数据统计截止昨日非实时更新 |
| └ sub_title | String | 吉品鲍鱼 关西参 | 商品信息-商品子标题 |
| └ brand_name | String | 淘宝心选 | 商品信息-品牌名称 |
| └ annual_vol | String | 1万+ | 年销量 |
| └ price_promotion_info | MapPromotionInfoMapData |  | 价格促销信息 |
| └ reserve_price | String | 102.00 | 商品信息-一口价通常显示为划线价 |
| └ zk_final_price | String | 79.9 | 促销信息-销售价格，无促销时等于一口价，有促销时为促销价。若属于预售商品，付定金时间内，在线售卖价=预售价 |
| └ final_promotion_price | String | 69.9 | 促销信息-预估到手价(元)。若属于预售商品，付定金时间内，预估到手价价=定金+尾款的预估到手价 |
| └ final_promotion_path_list | FinalPromotionPathMapData

                                 [] |  | 到手价优惠路径列表 |
| └ promotion_title | String | 商品券 | 优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 满7999减1300 | 优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_fee | String | 1300.00 | 实际优惠金额（元） |
| └ promotion_start_time | String | 1661184000000 | 优惠开始时间 |
| └ promotion_end_time | String | 1661788799000 | 优惠结束时间 |
| └ promotion_id | String | xx | 优惠ID |
| └ future_activity_promotion_price | String | 99.5 | 预热预估到手价（元） |
| └ future_activity_promotion_path_list | FutureActivityPromotionPathMapData

                                 [] |  | 预热到手价优惠路径列表 |
| └ promotion_title | String | 商品券 | 预热优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 满7999减1300 | 预热优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_fee | String | 1300.00 | 预热实际优惠金额（元） |
| └ promotion_start_time | String | 1661184000000 | 优惠开始时间 |
| └ promotion_end_time | String | 1661788799000 | 优惠结束时间 |
| └ promotion_tag_list | PromotionTagMapData

                                 [] |  | 标签信息列表 |
| └ tag_name | String | 88VIP | 标签名称，如“88VIP”、“花呗免息”、“猫超买返”、“是否包邮” |
| └ predict_rounding_up_price | String | 56.1 | 促销信息-预估凑单价（元）。预估凑单叠加优惠后的商品单价 |
| └ predict_rounding_up_price_desc | String | 需买1件 | 促销信息-凑单价说明，描述凑单价的实现说明。如 “可凑单”或“需买X件” |
| └ more_promotion_list | MorePromotionMapData

                                 [] |  | 更多活动优惠 |
| └ promotion_title | String | 满件折 | 预热优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 2件9折 | 预热优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_start_time | String | 1661222400000 | 优惠开始时间 |
| └ promotion_end_time | String | 1662393600000 | 优惠结束时间 |
| └ promotion_id | String | xx | 优惠ID |
| └ predict_rounding_up_path_list | PredictRoundingUpPathMapData

                                 [] |  | 预估凑单优惠路径 |
| └ promotion_title | String | 店铺优惠 | 优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 再买1件，可参与2件5折 | 优惠利益点文案，如“2件5折”、“每200减20”等 |
| └ publish_info | PublishInfo |  | 淘客推广信息 |
| └ income_rate | String | 5.50 | 商品信息-收入比率(%)；商品佣金比率+补贴比率 |
| └ click_url | String | //item.taobao.com/item.htm?id=556633720749&scm=1007.16190.92234.0&pvid=41362290-fa0b-4252-b172-6afc9c00e2c8&app_pvid=0ab0fac715095507006577956e | 链接-宝贝推广链接 |
| └ coupon_share_url | String | //uland.taobao.com/coupon/edetail?e=pR6YtnFKK%2B8GQASttHIRqcEWOmlidB03Pf45HLyCqA8dRAklSM5tEQ36hBQToU3M3MmLjFwLsqgZxcV7BPtHQDd2Naqom0e0&mt=1&app_pvid=0ab0fac715095507006577956e&ptl=app_pvid:0ab0fac715095507006577956e;tpp_pvid:41362290-fa0b-4252-b172-6afc9c00e2c8 | 链接-宝贝+券二合一页面链接 |
| └ sp_campaign_list | SpCampaignDTO

                                 [] |  | 定向计划集合-仅支持联系商务或运营小二申请定向计划合集字段权限 |
| └ sp_cid | String | 123 | 定向计划活动ID |
| └ sp_name | String | 定向计划活动1 | 定向计划名称 |
| └ sp_rate | String | 1550表示15.5% | 定向佣金率 |
| └ sp_lock_status | String | 0 | 定向是否锁佣，0=不锁佣 1=锁佣 |
| └ sp_apply_link | String | http://pub.alimama.com/portal/promo/shop/campaign/detail.htm?mode=info&campaignId=1000492470&creatorId=98836808&breadcrumb=false | 定向计划申请链接 |
| └ sp_status | String | 1 | 定向计划是否可用 1-可用 0-不可用 |
| └ future_activity_commission_rate | String | 1550表示15.5% | 预热活动到手价对应的佣金比率 |
| └ future_activity_time | String | 1665504000000 | 预热价活动开始时间 |
| └ income_info | IncomeInfo |  | 商品佣金信息 |
| └ commission_rate | String | 55 | 商品佣金比率 |
| └ commission_amount | String | 12 | 商品佣金金额 |
| └ subsidy_rate | String | 11 | 补贴比率 |
| └ subsidy_amount | String | 4 | 补贴金额 |
| └ subsidy_upper_limit | String | 10 | 补贴上限；仅在单笔订单命中补贴上限时返回结果否则出参为空 |
| └ tmall_rank_info | TmallRankInfo |  | 天猫榜单信息 |
| └ tmall_rank_text | String | 白茶热销榜·第5名 | 榜单排行描述 |
| └ tmall_rank_url | String | https://pages.tmall.com/wow/a/act/tmall/dailygroup/16220/16661/wupr?wh_pid=daily-459438&disableNav=YES | 榜单url |
| └ presale_info | PresaleInfo |  | 榜单排行描述 |
| └ presale_start_time | Number | 1567440000000 | 预售商品-付定金开始时间（毫秒） |
| └ presale_end_time | Number | 1567440000000 | 预售商品-付定金结束时间（毫秒） |
| └ presale_tail_start_time | Number | 1567440000000 | 预售商品-付尾款开始时间（毫秒） |
| └ presale_tail_end_time | Number | 1567440000000 | 预售商品-付尾款结束时间（毫秒） |
| └ presale_deposit | String | 100 | 预售商品-定金（元） |
| └ presale_discount_fee_text | String | 付定金立减5元 | 预售商品-优惠信息 |
| └ topn_info | StepRateDTO |  | 前N件佣金信息-前N件佣金生效或预热时透出以下字段 |
| └ topn_quantity | Number | 3000 | 前N件剩余库存 |
| └ topn_total_count | Number | 3000 | 前N件初始总库存 |
| └ topn_start_time | String | 1937297392332 | 前N件佣金开始时间 |
| └ topn_end_time | String | 1937297392332 | 前N件佣金结束时间 |
| └ topn_rate | String | 30 | 前N件佣金率 |
| uvid_msg | String | 123 | uvid结果信息，传入但未使用uvid时会返回原因 |
| scd_id_msg | String | 123 | scd_id结果信息 |
| material_id_msg | String | 123 | 描述本次商品推荐使用的物料信息 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.interest.items.get', {
	'material_id':'123',
	'adzone_id':'123',
	'page_size':'20',
	'page_no':'1',
	'device_type':'uvid',
	'device_value':'xxx'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_interest_items_get_response":{
        "result_list":{
            "map_data":[
                {
                    "item_id":"qeqscd1231-uqwenqe",
                    "item_basic_info":{
                        "title":"复古女裤子秋冬九分裤萝卜裤显瘦高腰韩版2017新款",
                        "short_title":"九分裤显瘦高腰韩版",
                        "pict_url":"\/\/img.alicdn.com\/bao\/uploaded\/i4\/745957850\/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg",
                        "white_image":"https:\/\/img.alicdn.com\/bao\/uploaded\/i4\/745957850\/TB1WzSRmV9gSKJjSspbXXbeNXXa_!!0-item_pic.jpg",
                        "level_one_category_id":1,
                        "level_one_category_name":"美妆",
                        "category_id":162201,
                        "category_name":"牛仔裤",
                        "seller_id":123,
                        "user_type":1,
                        "shop_title":"魔黛娅内衣旗舰店",
                        "volume":30,
                        "sub_title":"吉品鲍鱼 关西参",
                        "brand_name":"淘宝心选",
                        "annual_vol":"1万+"
                    },
                    "price_promotion_info":{
                        "reserve_price":"102.00",
                        "zk_final_price":"79.9",
                        "final_promotion_price":"69.9 ",
                        "final_promotion_path_list":{
                            "final_promotion_path_map_data":[
                                {
                                    "promotion_title":"商品券",
                                    "promotion_desc":"满7999减1300",
                                    "promotion_fee":"1300.00",
                                    "promotion_start_time":"1661184000000",
                                    "promotion_end_time":"1661788799000",
                                    "promotion_id":"xx"
                                }
                            ]
                        },
                        "future_activity_promotion_price":"99.5",
                        "future_activity_promotion_path_list":{
                            "future_activity_promotion_path_map_data":[
                                {
                                    "promotion_title":"商品券",
                                    "promotion_desc":"满7999减1300",
                                    "promotion_fee":"1300.00",
                                    "promotion_start_time":"1661184000000",
                                    "promotion_end_time":"1661788799000"
                                }
                            ]
                        },
                        "promotion_tag_list":{
                            "promotion_tag_map_data":[
                                {
                                    "tag_name":"88VIP"
                                }
                            ]
                        },
                        "predict_rounding_up_price":"56.1",
                        "predict_rounding_up_price_desc":"需买1件",
                        "more_promotion_list":{
                            "more_promotion_map_data":[
                                {
                                    "promotion_title":"满件折",
                                    "promotion_desc":"2件9折",
                                    "promotion_start_time":"1661222400000",
                                    "promotion_end_time":"1662393600000",
                                    "promotion_id":"xx"
                                }
                            ]
                        },
                        "predict_rounding_up_path_list":{
                            "predict_rounding_up_path_map_data":[
                                {
                                    "promotion_title":"店铺优惠",
                                    "promotion_desc":"再买1件，可参与2件5折 "
                                }
                            ]
                        }
                    },
                    "publish_info":{
                        "income_rate":"5.50",
                        "click_url":"\/\/item.taobao.com\/item.htm?id=556633720749&scm=1007.16190.92234.0&pvid=41362290-fa0b-4252-b172-6afc9c00e2c8&app_pvid=0ab0fac715095507006577956e",
                        "coupon_share_url":"\/\/uland.taobao.com\/coupon\/edetail?e=pR6YtnFKK%2B8GQASttHIRqcEWOmlidB03Pf45HLyCqA8dRAklSM5tEQ36hBQToU3M3MmLjFwLsqgZxcV7BPtHQDd2Naqom0e0&mt=1&app_pvid=0ab0fac715095507006577956e&ptl=app_pvid:0ab0fac715095507006577956e;tpp_pvid:41362290-fa0b-4252-b172-6afc9c00e2c8",
                        "sp_campaign_list":{
                            "sp_campaign_d_t_o":[
                                {
                                    "sp_cid":"123",
                                    "sp_name":"定向计划活动1",
                                    "sp_rate":"1550表示15.5%",
                                    "sp_lock_status":"0",
                                    "sp_apply_link":"http:\/\/pub.alimama.com\/portal\/promo\/shop\/campaign\/detail.htm?mode=info&campaignId=1000492470&creatorId=98836808&breadcrumb=false",
                                    "sp_status":"1"
                                }
                            ]
                        },
                        "future_activity_commission_rate":"1550表示15.5%",
                        "future_activity_time":"1665504000000",
                        "income_info":{
                            "commission_rate":"55",
                            "commission_amount":"12",
                            "subsidy_rate":"11",
                            "subsidy_amount":"4",
                            "subsidy_upper_limit":"10"
                        }
                    },
                    "tmall_rank_info":{
                        "tmall_rank_text":"白茶热销榜·第5名",
                        "tmall_rank_url":"https:\/\/pages.tmall.com\/wow\/a\/act\/tmall\/dailygroup\/16220\/16661\/wupr?wh_pid=daily-459438&disableNav=YES"
                    },
                    "presale_info":{
                        "presale_start_time":1567440000000,
                        "presale_end_time":1567440000000,
                        "presale_tail_start_time":1567440000000,
                        "presale_tail_end_time":1567440000000,
                        "presale_deposit":"100",
                        "presale_discount_fee_text":"付定金立减5元"
                    },
                    "topn_info":{
                        "topn_quantity":3000,
                        "topn_total_count":3000,
                        "topn_start_time":"1937297392332",
                        "topn_end_time":"1937297392332",
                        "topn_rate":"30"
                    }
                }
            ]
        },
        "uvid_msg":"123",
        "scd_id_msg":"123",
        "material_id_msg":"123"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.uvid.behavior.report（淘宝客-推广者-商品行为上报）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| uvid | String | 可选 | csadcdcdsacds |  | 联盟加密用户标识 |
| item_id | String | 必须 | cadsc-cdcd |  | 商品id |
| scd_id | Number | 可选 | 1000001 |  | 社群id |
| action_time | Number | 必须 | 1724746568070 |  | 行为发生时间 毫秒时间戳 |
| action | Number | 必须 | 1 |  | 1- 广告曝光 2-广告点击 3-商品曝光 4-商品点击 5... 8-（RID专属）feed流商品曝光 9-（RID专属）feed流商品点击 10-（RID专属）商详曝光 11-（RID专属）商详点击立即分享 12-（RID专属）商详点击立即购买 |
| task_id | Number | 可选 | 11 |  | 联盟任务id |
| channel | String | 可选 | 1 |  | 联盟渠道ID |
| call_back_url | String | 可选 | http://ccc |  | 回调地址 |
| oaid | String | 可选 | oaid |  | 安卓通用设备id |
| oaid_md5 | String | 可选 | oaidmd5 |  | oaidmd5 |
| idfa | String | 可选 | idfa |  | iosidfa适用ios6 及以上 |
| idfa_md5 | String | 可选 | idfaMd5 |  | iosidfa取md5 |
| android_id | String | 可选 | androidId |  | 用户终端的 Androidid |
| android_id_md5 | String | 可选 | androidIdMd5 |  | Androididmd5 |
| caid | String | 可选 | caid |  | caid原值（小写） |
| caid_md5 | String | 可选 | caidMd5 |  | caid原值md5（小 写） |
| caid_version | String | 可选 | caidVersion |  | 版本号 |
| caid2 | String | 可选 | caid2 |  | caid原值（小 写） |
| caid2_md5 | String | 可选 | caid2Md5 |  | caid原值md5（小 写） |
| caid2_version | String | 可选 | caid2Version |  | 版本号 |
| adzone_id | Number | 可选 | 123 |  | 推广位id，mm_xxx_xxx_12345678三段式的最后一段数字（登录pub.alimama.com推广管理-推广位管理中查询） |
| relation_id | Number | 可选 | 123 |  | 渠道管理id |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| report_success | Boolean | true | 是否成功 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.uvid.behavior.report', {
	'uvid':'csadcdcdsacds',
	'item_id':'cadsc-cdcd',
	'scd_id':'1000001',
	'action_time':'1724746568070',
	'action':'1',
	'task_id':'11',
	'channel':'1',
	'call_back_url':'http://ccc',
	'oaid':'oaid',
	'oaid_md5':'oaidmd5',
	'idfa':'idfa',
	'idfa_md5':'idfaMd5',
	'android_id':'androidId',
	'android_id_md5':'androidIdMd5',
	'caid':'caid',
	'caid_md5':'caidMd5',
	'caid_version':'caidVersion',
	'caid2':'caid2',
	'caid2_md5':'caid2Md5',
	'caid2_version':'caid2Version',
	'adzone_id':'123',
	'relation_id':'123'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_uvid_behavior_report_response":{
        "report_success":true
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.general.link.parse（淘宝客-推广者-万能解析）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| relation_id | String | 可选 | 123456 |  | 渠道管理ID（如是主站选品推广场景，必须入参该字段，且bizSceneId字段需入参2-消费者比价场景，否则二次转链失败） |
| adzone_id | Number | 必须 | 123456 |  | 推广位id，mm_xx_xx_xx pid三段式中的第三段 |
| material_dto | LkMaterialDTO | 可选 |  |  | 链接/口令转链 |
| fields | String | 可选 | origin_pid |  | 有origin_pid使用场景需入参 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | TbkLinkDTO | TbkLinkDTO | TbkLinkDTO |
| └ material_url_list | MaterialUrlList

                                 [] |  | 解析结果 |
| └ msg | String | 无权限 | 物料对应错误描述 |
| └ code | Number | 1001 | 物料对应错误码 |
| └ link_info_dto | LinkInfoDTO |  | 链接信息 |
| └ material_type | Number | 1 | 1—商品 2—店铺 3—会场 4-承接开放 5-优惠券 6-直播间 |
| └ tpwd_origin_url | String | https://item.taobao.com/item.htm?ut_sk=1.XhmNDzLwwioDABH4T6RBuvTP_21380790_1671501684367.Copy.1&id=688401422805&sourceType=item&price=54.9-74.9&origin_price=99.9&suid=2E8B3B3D-EA1D-44E4-A8DA-AB3468C239D4&shareUniqueId=19373158797&un=5b73a79de2da8c8a6eabd07a58355624&share_crt_v=1&un_site=0&spm=a2159r.13376460.0.0&sp_abtk=gray_1_code_simpleios2&tbSocialPopKey=shareItem&sp_tk=RHozeWRlRk1TUk8%3D&bxsign=tcdmT6tdiAhdgQRocCDz2_2umO9B1ffOtxAo1He-EbLu6Z8E9uqjMKg6YM4XMDSmvrZ0JD_pREyShNr0YBO6s6oaUJCq7Vtcx-iOO7WBaqbUy4&bc_fl_src=share-522958211663-1-0 | 入参口令/链接对应的原链接 |
| └ material_id | String | 688401422805 | 物料ID，需根据material_type判断物料类型， 可能为商品ID、卖家ID、会场ID |
| └ tk_biz_type | Number | 2 | 1-联盟口令，2-主站口令。入参物料不为淘口令时，此字段返回null |
| └ origin_pid | String | mm_11_11_11 | 入参推广链接中的pid，需配合入参fields使用，如果不属于当前调用的推广者，则不返回 |
| └ input_material_url | String | s.click.taobao.com | 入参物料链接 |
| └ extra_info | String | skuid已失效 | 解析成功的场景下，需要补充说明的信息 |
| biz_error_desc | Number | 1 | 见错误码描述 |
| result_msg | String | 1 | 见错误码描述 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.general.link.parse', {
	'relation_id':'123456',
	'adzone_id':'123456',
	'material_dto':'数据结构JSON示例',
	'fields':'origin_pid'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_general_link_parse_response":{
        "data":{
            "material_url_list":{
                "material_url_list":[
                    {
                        "msg":"无权限",
                        "code":1001,
                        "link_info_dto":{
                            "material_type":1,
                            "tpwd_origin_url":"https:\/\/item.taobao.com\/item.htm?ut_sk=1.XhmNDzLwwioDABH4T6RBuvTP_21380790_1671501684367.Copy.1&id=688401422805&sourceType=item&price=54.9-74.9&origin_price=99.9&suid=2E8B3B3D-EA1D-44E4-A8DA-AB3468C239D4&shareUniqueId=19373158797&un=5b73a79de2da8c8a6eabd07a58355624&share_crt_v=1&un_site=0&spm=a2159r.13376460.0.0&sp_abtk=gray_1_code_simpleios2&tbSocialPopKey=shareItem&sp_tk=RHozeWRlRk1TUk8%3D&bxsign=tcdmT6tdiAhdgQRocCDz2_2umO9B1ffOtxAo1He-EbLu6Z8E9uqjMKg6YM4XMDSmvrZ0JD_pREyShNr0YBO6s6oaUJCq7Vtcx-iOO7WBaqbUy4&bc_fl_src=share-522958211663-1-0",
                            "material_id":"688401422805",
                            "tk_biz_type":2,
                            "origin_pid":"mm_11_11_11"
                        },
                        "input_material_url":"s.click.taobao.com",
                        "extra_info":"skuid已失效"
                    }
                ]
            }
        },
        "biz_error_desc":1,
        "result_msg":"1"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.uvid.bind.status.get（淘宝-淘宝客-推广者-用户绑定状态查询）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| uvid | String | 必须 | cvasdcadsvcd |  | UVID |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result_list | MapData [] |  | 结果列表 |
| └ matched_user | Boolean | false | 是否匹配上消费者 |
| └ uvid_domain | String | 社群 | uvid业务域 |
| └ user_permission | Boolean | true | (返利业务特有) 用户是否授权 |
| └ bind_time | String | 20240101 | (返利业务特有) 用户授权时间 |
| └ create_taoke_type | Number | 1 | 1-memebr维度，2-member组维度 |
| └ uvid | String | sda | uvid |
| └ msg | String | invalid | 信息 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.uvid.bind.status.get', {
	'uvid':'cvasdcadsvcd'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_uvid_bind_status_get_response":{
        "result_list":{
            "map_data":[
                {
                    "matched_user":false,
                    "uvid_domain":"社群",
                    "user_permission":true,
                    "bind_time":"20240101",
                    "create_taoke_type":1,
                    "uvid":"sda",
                    "msg":"invalid"
                }
            ]
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.rta.uvid.match（淘宝客-推广者-UVID人群挑量）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| uvid | String | 必须 | sdadsc,cadacad |  | uvid |
| qmt_id | String | 必须 | 123 |  | 任务id |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | UvIdRtaMatchResult [] |  | data |
| └ uvid | String | sadas | uvid |
| └ match_status | Number | 1 | 1-命中，0-不命中 |
| └ ext_info | String | uvid不存在 | 描述信息 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.rta.uvid.match', {
	'uvid':'sdadsc,cadacad',
	'qmt_id':'123'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_rta_uvid_match_response":{
        "data":{
            "uv_id_rta_match_result":[
                {
                    "uvid":"sadas",
                    "match_status":1,
                    "ext_info":"uvid不存在"
                }
            ]
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dsp.rta.consumer.match（淘宝客-推广者-目标用户批量匹配）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| qmt_id_list | String | 必须 | 11 |  | 任务id，最多5个任务 |
| device_d_t_o_list | DeviceDTO | 必须 |  |  | 设备信息，最多10个设备，IMEI,IDFA,OAID：需用MD5加密，32位小写 CAID：设备号原始值 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | DspRtaResult [] |  | data |
| └ device_type | String | 11 | 设备类型 |
| └ device_value | String | 11 | 设备值 |
| └ match_result | MatchRes

                                 [] | {"12": 1} | 任务匹配结果，key：任务id，value：1-命中该任务 |
| └ task_id | String | 11 | 任务id |
| └ status | Number | 1 | 0-不符合任务要求，1-符合任务要求，2-设备未识别，3-系统异常，可重试 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dsp.rta.consumer.match', {
	'qmt_id_list':'11',
	'device_d_t_o_list':'数据结构JSON示例'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dsp_rta_consumer_match_response":{
        "data":{
            "dsp_rta_result":[
                {
                    "device_type":"11",
                    "device_value":"11",
                    "match_result":{
                        "match_res":[
                            {
                                "task_id":"11",
                                "status":1
                            }
                        ]
                    }
                }
            ]
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.vc.landing.link.convert（淘宝客-推广者-拉新承接页转链）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| relation_id | String | 可选 | 123456 |  | 渠道管理ID（如是主站选品推广场景，必须入参该字段，且bizSceneId字段需入参2-消费者比价场景，否则二次转链失败） |
| adzone_id | Number | 必须 | 123456 |  | 推广位id，mm_xx_xx_xx pid三段式中的第三段 |
| link_type | Number | 必须 | 1 |  | 链接类型（1-企微中转页；2-企微客服临时回话页；3-加好友二维码；4-企微零元购页面链接） |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | LinkInfoDTO | TbkLinkDTO | LinkInfoDTO |
| └ url | String | xxx | 链接 |
| biz_error_desc | String | 1 | 见错误码描述 |
| result_msg | String | 1 | 见错误码描述 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.vc.landing.link.convert', {
	'relation_id':'123456',
	'adzone_id':'123456',
	'link_type':'1'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_vc_landing_link_convert_response":{
        "data":{
            "url":"xxx"
        },
        "biz_error_desc":"1",
        "result_msg":"1"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.sc.vc.landing.link.convert（淘宝客-推广者-拉新承接页转链）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| relation_id | String | 可选 | 123456 |  | 渠道管理ID（如是主站选品推广场景，必须入参该字段，且bizSceneId字段需入参2-消费者比价场景，否则二次转链失败） |
| adzone_id | Number | 必须 | 123456 |  | 推广位id，mm_xx_xx_xx pid三段式中的第三段 |
| link_type | Number | 必须 | 1 |  | 链接类型（1-企微中转页；2-企微客服临时回话页；3-加好友二维码；4-企微零元购页面链接） |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | LinkInfoDTO | TbkLinkDTO | LinkInfoDTO |
| └ url | String | xxx | 链接 |
| biz_error_desc | String | 1 | 见错误码描述 |
| result_msg | String | 1 | 见错误码描述 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.sc.vc.landing.link.convert', {
	'relation_id':'123456',
	'adzone_id':'123456',
	'link_type':'1'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_sc_vc_landing_link_convert_response":{
        "data":{
            "url":"xxx"
        },
        "biz_error_desc":"1",
        "result_msg":"1"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.eshare.link.convert（淘宝客-推广者-KA私域专享转链）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| adzone_id | Number | 可选 | 1234 |  | 推广位id，mm_xx_xx_xx pid三段式中的第三段 |
| relation_id | String | 可选 | 1234 |  | 渠道管理ID |
| item_dto | LkItemDTO | 可选 |  |  | 商品转链 |
| material_dto | LkMaterialDTO | 可选 |  |  | 链接/口令转链 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | TbkLinkDTO | TbkLinkDTO | TbkLinkDTO |
| └ material_url_list | MaterialUrlList

                                 [] |  | 转链结果 |
| └ msg | String | 无权限 | 物料对应错误描述 |
| └ code | Number | 1001 | 物料对应错误码 |
| └ link_info_dto | LinkInfoDTO |  | 链接信息 |
| └ coupon_long_url | String | https://uland.taobao.com/coupon/edetail?e=HcDWJQP6d12lhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJDtOYUTZvUxMupZB35fyH%2Bj%2BFrYU%2BROQkienhT0Gv%2FXXPpGXqwTrgn%2FiLFm3yG1xo9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmghqozJdwyPlqXT8BNPyRO3CWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOghqozJdwyPlaVcuzWAzoR%2BEffiaBagqGwiV9Bh6z0Brrk5oEZwv0ZJMDQVG07AK7A%3D%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01 | 二合一长链接 |
| └ coupon_short_url | String | https://s.click.taobao.com/DvHjOPu | 二合一短链 |
| └ coupon_short_tpwd | String | ￥p7lYdesjTCG￥ | 二合一链接的短口令 |
| └ coupon_full_tpwd | String | 47￥ CZ3457 p7lYdesjTCG￥ https://m.tb.cn/h.UQ4ceEA  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装 | 二合一链接的长口令 |
| └ material_type | Number | 1 | 1—单品 |
| └ tk_biz_type | Number | 2 | 1-联盟口令，2-主站口令。入参物料不为淘口令时，此字段返回null |
| └ input_material_url | String | s.click.taobao.com | 入参物料链接 |
| └ promotion_info_dto | MaterialPromotionInfoDTO |  | 营销信息 |
| └ commission_rate | String | 6.00 | 商品收入比率(%)：商品佣金比率+补贴比率。同物料类接口income_rate |
| └ commission_type | String | MKT | 佣金类型。MKT表示营销计划，SP表示定向计划，COMMON表示通用计划，ZX表示自选计划 |
| └ item_url_list | ItemUrlList

                                 [] |  | 单品转链信息 |
| └ msg | String | 无权限 | 单品转链信息 |
| └ code | Number | 1001 | 物料对应错误码 |
| └ link_info_dto | ItemLinkInfoDTO |  | 链接信息 |
| └ coupon_long_url | String | https://uland.taobao.com/coupon/edetail?e=G6GuYx3ILfalhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJtx9C1Z8GbV1vHgx4K91Wrd9oW7c0CRLBdz881e47Ft9oBDRNgYIxgFNRd9B4OBPr9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmrRMCeO3Mi1ouPODd%2FkGgeDCWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOrRMCeO3Mi1oDb9krsjLiJ069NSKr8HLD%2F5cBb8E%2Fg255M0kZg5qGOw%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01 | 二合一长链接 |
| └ item_id | String | https://uland.taobao.com/coupon/edetail?e=G6GuYx3ILfalhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJtx9C1Z8GbV1vHgx4K91Wrd9oW7c0CRLBdz881e47Ft9oBDRNgYIxgFNRd9B4OBPr9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmrRMCeO3Mi1ouPODd%2FkGgeDCWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOrRMCeO3Mi1oDb9krsjLiJ069NSKr8HLD%2F5cBb8E%2Fg255M0kZg5qGOw%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01 | 商品ID |
| └ material_type | Number | 1 | 1—单品 |
| └ coupon_short_url | String | https://s.click.taobao.com/HvHjOPu | 二合一短链 |
| └ coupon_short_tpwd | String | ￥LOcqdeIlU9y￥ | 二合一链接的短口令 |
| └ coupon_full_tpwd | String | 48￥ CZ3457 LOcqdeIlU9y￥ https://m.tb.cn/h.UQ4ceEC  olayks煮茶器喷淋式黑茶白茶煮茶壶家用自动蒸汽养生壶办公室小型 | 二合一链接的长口令 |
| └ input_item_id | String | i87a9ja90d8-09qrjcoa7qwl | 入参的商品ID |
| └ promotion_info_dto | ItemPromotionInfoDTO |  | 营销信息 |
| └ commission_rate | String | 2.40 | 商品收入比率(%)：商品佣金比率+补贴比率。同物料类接口income_rate |
| └ commission_type | String | MKT | 佣金类型。MKT表示营销计划，SP表示定向计划，COMMON表示通用计划，ZX表示自选计划 |
| biz_error_desc | String | 1 | 错误码描述 |
| result_msg | String | 1 | 错误码 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.eshare.link.convert', {
	'adzone_id':'1234',
	'relation_id':'1234',
	'item_dto':'数据结构JSON示例',
	'material_dto':'数据结构JSON示例'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_eshare_link_convert_response":{
        "data":{
            "material_url_list":{
                "material_url_list":[
                    {
                        "msg":"无权限",
                        "code":1001,
                        "link_info_dto":{
                            "coupon_long_url":"https:\/\/uland.taobao.com\/coupon\/edetail?e=HcDWJQP6d12lhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJDtOYUTZvUxMupZB35fyH%2Bj%2BFrYU%2BROQkienhT0Gv%2FXXPpGXqwTrgn%2FiLFm3yG1xo9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmghqozJdwyPlqXT8BNPyRO3CWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOghqozJdwyPlaVcuzWAzoR%2BEffiaBagqGwiV9Bh6z0Brrk5oEZwv0ZJMDQVG07AK7A%3D%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517839@21055fa7_0b7f_1852e3a1f30_0417@01",
                            "coupon_short_url":"https:\/\/s.click.taobao.com\/DvHjOPu",
                            "coupon_short_tpwd":"￥p7lYdesjTCG￥",
                            "coupon_full_tpwd":"47￥ CZ3457 p7lYdesjTCG￥ https:\/\/m.tb.cn\/h.UQ4ceEA  我的天呐麻酱爆肚粉香辣花甲粉重庆酸辣粉方便速食粉条六袋装",
                            "material_type":1,
                            "tk_biz_type":2
                        },
                        "input_material_url":"s.click.taobao.com",
                        "promotion_info_dto":{
                            "commission_rate":"6.00",
                            "commission_type":"MKT"
                        }
                    }
                ]
            },
            "item_url_list":{
                "item_url_list":[
                    {
                        "msg":"无权限",
                        "code":1001,
                        "link_info_dto":{
                            "coupon_long_url":"https:\/\/uland.taobao.com\/coupon\/edetail?e=G6GuYx3ILfalhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJtx9C1Z8GbV1vHgx4K91Wrd9oW7c0CRLBdz881e47Ft9oBDRNgYIxgFNRd9B4OBPr9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmrRMCeO3Mi1ouPODd%2FkGgeDCWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOrRMCeO3Mi1oDb9krsjLiJ069NSKr8HLD%2F5cBb8E%2Fg255M0kZg5qGOw%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01",
                            "item_id":"https:\/\/uland.taobao.com\/coupon\/edetail?e=G6GuYx3ILfalhHvvyUNXZfh8CuWt5YH5OVuOuRD5gLJMmdsrkidbOWBzzpT26idJtx9C1Z8GbV1vHgx4K91Wrd9oW7c0CRLBdz881e47Ft9oBDRNgYIxgFNRd9B4OBPr9E3CIsWU5pj75f%2FX7e6X6TX2Dcu6%2BWPof99KHcV2dz2Q%2BPTkUmCMR1R8iWumasxPjXTWFYYVpFI4%2Baud2Kv%2BmrRMCeO3Mi1ouPODd%2FkGgeDCWm71evwboq2ugOoDIQE5avhnuz9l3tbd8BHHMx2peL6n7tssF5spfgu%2BKM%2Fbf9sE%2BdAb1JoOOrRMCeO3Mi1oDb9krsjLiJ069NSKr8HLD%2F5cBb8E%2Fg255M0kZg5qGOw%3D&traceId=816a277916715178333831026bf6cf&relationId=123456&&union_lens=lensId:TAPI@1671517838@21055fa7_0b7f_1852e3a1bae_0416@01",
                            "material_type":1,
                            "coupon_short_url":"https:\/\/s.click.taobao.com\/HvHjOPu",
                            "coupon_short_tpwd":"￥LOcqdeIlU9y￥",
                            "coupon_full_tpwd":"48￥ CZ3457 LOcqdeIlU9y￥ https:\/\/m.tb.cn\/h.UQ4ceEC  olayks煮茶器喷淋式黑茶白茶煮茶壶家用自动蒸汽养生壶办公室小型"
                        },
                        "input_item_id":"i87a9ja90d8-09qrjcoa7qwl",
                        "promotion_info_dto":{
                            "commission_rate":"2.40",
                            "commission_type":"MKT"
                        }
                    }
                ]
            }
        },
        "biz_error_desc":"1",
        "result_msg":"1"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.image.ecognition.list.query（淘宝客【推广者】识图找优惠商品List）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| img | String | 必须 | base64xxxx |  | base64需要小于200K，超出会拒绝处理，如果原始图片尺寸较大，请进行压缩。注意仅支持jpg png等常见格式图片 |
| identifier_value | String | 必须 | cdcadscads |  | 用户标识的值 |
| adzone_id | Number | 必须 | 1123 |  | mm_xx_xx_xx pid三段式中的第三段 |
| identifier_type | String | 必须 | OAID_MD5 |  | 用户标识类型 IMEI_MD5、IDFA_MD5、OAID_MD5 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | PicSearchResult |  | 结果 |
| └ item_infos | ItemInfo

                                 [] |  | 商品列表 |
| └ item_id | String | xxx-qqq | 商品ID |
| └ img | String | http://img | 商品图片地址 |
| └ item_title | String | 测试商品 | 商品标题 |
| └ sale_price | String | 112 | 售价 |
| └ zk_final_price | String | 111 | 到手价 |
| └ cps_url | String | https:// | 跳转地址 |
| └ coupon_url | String | https:// | 领券地址 |
| └ shop_type | String | 天猫 | 店铺类型 |
| └ provcity | String | 地区 | 地区 |
| └ coupon | String | 5 | 优惠券信息 |
| └ icon_list | String

                                 [] |  | 营销标签 |
| result_msg | String | success | 结果描述 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.image.ecognition.list.query', {
	'img':'base64xxxx',
	'identifier_value':'cdcadscads',
	'adzone_id':'1123',
	'identifier_type':'OAID_MD5'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_image_ecognition_list_query_response":{
        "data":{
            "item_infos":{
                "item_info":[
                    {
                        "item_id":"xxx-qqq",
                        "img":"http:\/\/img",
                        "item_title":"测试商品",
                        "sale_price":"112",
                        "zk_final_price":"111",
                        "cps_url":"https:\/\/",
                        "coupon_url":"https:\/\/",
                        "shop_type":"天猫",
                        "provcity":"地区",
                        "coupon":"5"
                    }
                ]
            }
        },
        "result_msg":"success"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.dg.image.ecognition.page.query（淘宝客【推广者】识图找优惠h5）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| img | String | 必须 | base64xxxx |  | base64需要小于200K，超出会拒绝处理，如果原始图片尺寸较大，请进行压缩。注意仅支持jpg png等常见格式图片 |
| identifier_value | String | 必须 | cdcadscads |  | 用户标识的值 |
| adzone_id | Number | 必须 | 1123 |  | mm_xx_xx_xx pid三段式中的第三段 |
| identifier_type | String | 必须 | OAID_MD5 |  | 用户标识类型 IMEI_MD5、IDFA_MD5、OAID_MD5 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | PicSearchResult |  | 结果 |
| └ url | String | https://mo.m.taobao.com/union2/page_1758699496339 | 识图推荐跳转 h5 url |
| └ deeplink | String | tbopen://m.taobao.com/tbopen/index.html?&action=ali.open.nav&module=h5&bootImage=0&source=alimama&appkey=26074866&h5Url=https%3A%2F%2Finternal-mo.m.taobao.com%2Funion2%2Fpage_1758699496339%3Fpreview%3D1%26__env%3Dpre%26cdnEnv%3Ddaily%26systype%3Dwapa%26cdnEnv%3Ddaily%26pic%3Dhttps%253A%252F%252Fimg.alicdn.com%252Fimgextra%252Fi2%252FO1CN01U2r5Tz1cVbJ76WqRD_%2521%25214611686018427383318-2-union_topapi_pic.png%26box%3D706%C3%97900%26es%3DQvy4cKfQ0627QfSPPGeGaXnc1eQCXtRItNi0U9RVOcSfuPsPoRP7r2Nd5pMqavl3rItFaAapWrX1Ezu7qcTLDFwIMtZV3XS3%26manu%3DXIAOMI&bc_fl_src=tunion_vipmedia_dandelion#Intent;scheme=tbopen;launchFlags=0x4000000;end | 识图推荐跳转deeplink，可直接打开手淘 |
| result_msg | String | success | 结果描述 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.dg.image.ecognition.page.query', {
	'img':'base64xxxx',
	'identifier_value':'cdcadscads',
	'adzone_id':'1123',
	'identifier_type':'OAID_MD5'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_dg_image_ecognition_page_query_response":{
        "data":{
            "url":"https:\/\/mo.m.taobao.com\/union2\/page_1758699496339",
            "deeplink":"tbopen:\/\/m.taobao.com\/tbopen\/index.html?&action=ali.open.nav&module=h5&bootImage=0&source=alimama&appkey=26074866&h5Url=https%3A%2F%2Finternal-mo.m.taobao.com%2Funion2%2Fpage_1758699496339%3Fpreview%3D1%26__env%3Dpre%26cdnEnv%3Ddaily%26systype%3Dwapa%26cdnEnv%3Ddaily%26pic%3Dhttps%253A%252F%252Fimg.alicdn.com%252Fimgextra%252Fi2%252FO1CN01U2r5Tz1cVbJ76WqRD_%2521%25214611686018427383318-2-union_topapi_pic.png%26box%3D706%C3%97900%26es%3DQvy4cKfQ0627QfSPPGeGaXnc1eQCXtRItNi0U9RVOcSfuPsPoRP7r2Nd5pMqavl3rItFaAapWrX1Ezu7qcTLDFwIMtZV3XS3%26manu%3DXIAOMI&bc_fl_src=tunion_vipmedia_dandelion#Intent;scheme=tbopen;launchFlags=0x4000000;end"
        },
        "result_msg":"success"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```



---
##taobao.tbk.shop.recommend.get（淘宝客-公用-店铺关联推荐）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| count | Number | 可选 | 20 |  | 返回数量，默认20，最大值40 |
| fields | String | 必须 | user_id,shop_title,shop_type,seller_nick,pict_url,shop_url |  | 需返回的字段列表 |
| platform | Number | 可选 | 1 |  | 链接形式：1：PC，2：无线，默认：１ |
| user_id | Number | 必须 | 123 |  | 卖家Id |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| results | NTbkShop [] |  | 淘宝客店铺 |
| └ user_id | Number | 123 | 卖家ID |
| └ shop_title | String | 女装店铺 | 店铺名称 |
| └ seller_nick | String | demo | 卖家昵称 |
| └ shop_type | String | B | 店铺类型，B：天猫，C：淘宝 |
| └ shop_url | String | http://store.taobao.com/shop/xxx | 店铺地址 |
| └ pict_url | String | http://img01.taobaocdn.com/bao/uploaded/i1/xxx.jpg | 店标图片 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.shop.recommend.get', {
	'count':'20',
	'fields':'user_id,shop_title,shop_type,seller_nick,pict_url,shop_url',
	'platform':'1',
	'user_id':'123'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_shop_recommend_get_response":{
        "results":{
            "n_tbk_shop":[
                {
                    "user_id":123,
                    "shop_title":"女装店铺",
                    "seller_nick":"demo",
                    "shop_type":"B",
                    "shop_url":"http:\/\/store.taobao.com\/shop\/xxx",
                    "pict_url":"http:\/\/img01.taobaocdn.com\/bao\/uploaded\/i1\/xxx.jpg"
                }
            ]
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isp.tbkapi-service-unavailable | 内部服务不可用 | 稍后重试 |

---
##taobao.tbk.spread.get（淘宝客-公用-长链转短链）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| requests | TbkSpreadRequest

        						[] | 必须 |  | 最大列表长度：20 | 请求列表，内部包含多个url |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| results | TbkSpread [] |  | 传播形式对象列表 |
| └ content | String | http://s.click.taobao.com/H4zazPx | 传播形式, 目前只支持短链接 |
| └ err_msg | String | OK | 调用错误信息；由于是批量接口，请重点关注每条请求返回的结果，如果非OK，则说明该结果对应的content不正常，请酌情处理; |
| total_results | Number | 10 | totalResults |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.spread.get', {
	'requests':'数据结构JSON示例'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_spread_get_response":{
        "results":{
            "tbk_spread":[
                {
                    "content":"http:\/\/s.click.taobao.com\/H4zazPx",
                    "err_msg":"OK"
                }
            ]
        },
        "total_results":10
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isp.dependency-error | 依赖服务暂时不可用 | 稍后重试 |
| isp.tbkapi-service-unavailable | 内部服务不可用 | 稍后重试 |
| isv.not-support-param-type | 输入参数非法 | 参考文档 |

---
##taobao.tbk.item.click.extract（淘宝客-公用-链接解析出商品id）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| click_url | String | 必须 | https://s.click.taobao.com/*** |  | 长链接或短链接 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| item_id | String | 123 | 商品id |
| open_iid | String | xxxxx | 商品混淆id |
| biz_scene_id | String | 1 | 1-动态ID转链场景，2-消费者比价场景，3-商品库导购场景（不填默认为1） |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.item.click.extract', {
	'click_url':'https://s.click.taobao.com/***'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_item_click_extract_response":{
        "item_id":"123",
        "open_iid":"xxxxx",
        "biz_scene_id":"1"
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.coupon.get（淘宝客-公用-阿里妈妈推广券详情查询）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| me | String | 可选 | nfr%2BYTo2k1PX18gaNN%2BIPkIG2PadNYbBnwEsv6mRavWieOoOE3L9OdmbDSSyHbGxBAXjHpLKvZbL1320ML%2BCF5FRtW7N7yJ056Lgym4X01A%3D |  | 带券ID与商品ID的加密串 |
| item_id | String | 可选 | 123 |  | 商品ID |
| activity_id | String | 可选 | sdfwe3eefsdf |  | 券ID |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | MapData | data | data |
| └ coupon_start_fee | String | 29.00 | 优惠券门槛金额 |
| └ coupon_remain_count | Number | 26996 | 优惠券剩余量 |
| └ coupon_total_count | Number | 30000 | 优惠券总量 |
| └ coupon_end_time | String | 2017-08-17 | 优惠券结束时间 |
| └ coupon_start_time | String | 2017-08-15 | 优惠券开始时间 |
| └ coupon_amount | String | 10.00 | 优惠券金额 |
| └ coupon_src_scene | Number | 1 | 券类型，1 表示全网公开券，4 表示妈妈渠道券 |
| └ coupon_type | Number | 0 | 券属性，0表示店铺券，1表示单品券 |
| └ coupon_activity_id | String | xsdss | 券ID |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.coupon.get', {
	'me':'nfr%2BYTo2k1PX18gaNN%2BIPkIG2PadNYbBnwEsv6mRavWieOoOE3L9OdmbDSSyHbGxBAXjHpLKvZbL1320ML%2BCF5FRtW7N7yJ056Lgym4X01A%3D',
	'item_id':'123',
	'activity_id':'sdfwe3eefsdf'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_coupon_get_response":{
        "data":{
            "coupon_start_fee":"29.00",
            "coupon_remain_count":26996,
            "coupon_total_count":30000,
            "coupon_end_time":"2017-08-17",
            "coupon_start_time":"2017-08-15",
            "coupon_amount":"10.00",
            "coupon_src_scene":1,
            "coupon_type":0,
            "coupon_activity_id":"xsdss"
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| 1001 | 非法的me参数值 | 传入正确的me参数值，含有券ID与商品ID信息 |
| 10000 | 该itemId对应的宝贝已下架或非淘客宝贝 | 更换新的itemId查询 |
| 1002 | 入参为空 | 传入正确的参数值 |
| 10 | 优惠券不存在 | 优惠券不存在，请重新查询 |
| 11 | 优惠券已领完 | 优惠券已领完，请重新查询 |
| 13 | 该优惠券不适用该商品 | 该优惠券不适用该商品，请重新查询 |
| 14 | 优惠券类型错误 | 该优惠券类型错误，请重新查询 |
| 15 | 不支持的优惠券 | 该优惠券不支持使用，请重新查询 |
| 17 | 优惠券未到开始使用时间 | 该优惠券未到开始使用时间，请重新查询 |
| 1 | 内部服务错误 | 稍后重试 |
| 12 | 优惠券已过期 | 优惠券已过期，请重新查询 |
| 16 | 优惠券未到开始领取时间 | 优惠券未到开始领取时间，请重新查询 |
| 1912 | 您输入的商品ID不合法，请使用升级后的新商品ID，如有疑问请加入【淘宝联盟】线上合规升级咨询群（钉钉群：44965410）进行咨询 | 您输入的商品ID不合法，请使用升级后的新商品ID，如有疑问请加入【淘宝联盟】线上合规升级咨询群（钉钉群：44965410）进行咨询 |

---
##taobao.tbk.tpwd.create（淘宝客-公用-淘口令生成）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| url | String | 必须 | https://s.click.taobao.com/YI3Uopu |  | 联盟官方渠道获取的淘客推广链接，请注意，不要随意篡改官方生成的链接，否则可能无法生成淘口令 |
| text | String | 可选 | noMeaningValue |  | 兼容旧版本api参数，无实际作用 |
| logo | String | 可选 | noMeaningValue |  | 兼容旧版本api参数，无实际作用 |
| ext | String | 可选 | noMeaningValue |  | 兼容旧版本api参数，无实际作用 |
| user_id | String | 可选 | noMeaningValue |  | 兼容旧版本api参数，无实际作用 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | MapData |  | 返回结果对象 |
| └ password_simple | String | ￥SIH6XbwRfyt￥ | 非苹果ios14以上版本的设备（即其他ios版本、Android系统等），可以用此淘口令正常在复制到手淘打开 |
| └ model | String | 8緮置内容￥hxlgccEumBB￥达开?τao寶?或掂击炼接 https://m.tb.cn/h.VvkiWSm 至浏.览览.器【618超级红包】 | 针对苹果ios14及以上版本的苹果设备，手淘将按照示例值信息格式读取淘口令(需包含：数字+羊角符+url，识别规则可能根据ios情况变更)。如需更改淘口令内文案、url等内容，请务必先验证更改后的淘口令在手淘可被识别打开！ |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.tpwd.create', {
	'url':'https://s.click.taobao.com/YI3Uopu',
	'text':'noMeaningValue',
	'logo':'noMeaningValue',
	'ext':'noMeaningValue',
	'user_id':'noMeaningValue'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_tpwd_create_response":{
        "data":{
            "password_simple":"￥SIH6XbwRfyt￥",
            "model":"8緮置内容￥hxlgccEumBB￥达开?τao寶?或掂击炼接 https:\/\/m.tb.cn\/h.VvkiWSm 至浏.览览.器【618超级红包】"
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isp.param-error | 参数错误 | 仔细检查参数 |
| isp.sys-error | 服务系统异常 | 请稍后再试 |
| 20000 | 口令跳转url不支持口令转换 | 修改口令跳转url，且以https开头 |
| 20001 | 口令弹框内容不能少于5个字符 | 增加口令弹框内容至5个字符以上 |
| 1 | 服务系统异常 | 服务系统异常 |
| 20002 | 口令参数扩展字段不能为空 | 补充口令参数扩展字段 |
| 24 | 淘口令生成者淘宝帐号为空 | 请检查链接中的pid信息是否正确、合法 |
| 25 | 淘口令生成失败 | 请重试 |
| 23 | 淘口令链接对应的物料信息为空 | 请检查链接是否为官方下行的物料链接，请勿随意篡改官方链接 |
| 26 | 链接不属于联盟官方业务场景 | 请检查链接是否是官方渠道下行，是否被篡改过，是否带有违规参数。 |

---
##taobao.tbk.tpwd.mix.create（淘宝客-公用-文本淘口令）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| ext | String | 可选 | {} |  | 扩展字段JSON格式 |
| logo | String | 可选 | https://uland.taobao.com/ |  | 口令弹框logoURL |
| url | String | 必须 | https://uland.taobao.com/ |  | 口令跳转目标页 |
| text | String | 必须 | 长度大于5个字符 |  | 口令弹框内容 |
| user_id | String | 可选 | 123 |  | 生成口令的淘宝用户ID |
| password | String | 必须 | 自定义口令 |  | 口令文本 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | MapData |  | data |
| └ status | String | 1 | 1：成功 2：失败，重复 3：失败，文本不符合规范 |
| └ password | String | 自定义内容自定义口令 | 自定义内容+自定义口令 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.tpwd.mix.create', {
	'ext':'{}',
	'logo':'https://uland.taobao.com/',
	'url':'https://uland.taobao.com/',
	'text':'长度大于5个字符',
	'user_id':'123',
	'password':'自定义口令'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_tpwd_mix_create_response":{
        "data":{
            "status":"1",
            "password":"自定义内容自定义口令"
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.sc.publisher.info.save（淘宝客-公用-私域用户备案）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| relation_from | String | 可选 | 1 |  | 渠道备案 - 来源，取链接的来源 |
| offline_scene | String | 可选 | 1 |  | 渠道备案 - 线下场景信息，1 - 门店，2- 学校，3 - 工厂，4 - 其他 |
| online_scene | String | 可选 | 1 |  | 渠道备案 - 线上场景信息，1 - 微信群，2- QQ群，3 - 其他 |
| inviter_code | String | 必须 | xxx |  | 淘宝客邀请渠道或会员的邀请码 |
| info_type | Number | 必须 | 1 |  | 类型，必选 默认为1: |
| note | String | 可选 | 小蜜蜂 |  | 媒体侧渠道备注 |
| register_info | String | 可选 | {"phoneNumber":"18801088599","city":"江苏省","province":"南京市","location":"玄武区花园小区","detailAddress":"5号楼3单元101室","shopType":"社区店","shopName":"全家便利店","shopCertifyType":"营业执照","certifyNumber":"111100299001"} |  | 线下备案注册信息,字段包含: 电话号码(phoneNumber，必填),省(province,必填),市(city,必填),区县街道(location,必填),详细地址(detailAddress,必填),经营类型(career,线下个人必填),店铺类型(shopType,线下店铺必填),店铺名称(shopName,线下店铺必填),店铺证书类型(shopCertifyType,线下店铺选填),店铺证书编号(certifyNumber,线下店铺选填) |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | Data |  | data |
| └ relation_id | Number | 40232 | 渠道关系ID |
| └ account_name | String | xxx | 渠道昵称 |
| └ special_id | Number | 32304 | 会员运营ID |
| └ desc | String | 绑定成功 | 如果重复绑定会提示：”重复绑定渠道“或”重复绑定粉丝“ |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.sc.publisher.info.save', {
	'relation_from':'1',
	'offline_scene':'1',
	'online_scene':'1',
	'inviter_code':'xxx',
	'info_type':'1',
	'note':'小蜜蜂',
	'register_info':'{\"phoneNumber\":\"18801088599\",\"city\":\"江苏省\",\"province\":\"南京市\",\"location\":\"玄武区花园小区\",\"detailAddress\":\"5号楼3单元101室\",\"shopType\":\"社区店\",\"shopName\":\"全家便利店\",\"shopCertifyType\":\"营业执照\",\"certifyNumber\":\"111100299001\"}'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_sc_publisher_info_save_response":{
        "data":{
            "relation_id":40232,
            "account_name":"xxx",
            "special_id":32304,
            "desc":"绑定成功"
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isp.tbkapi-service-unavailable | 淘宝客API服务不可用 | 请稍后重试 |
| isv.invalid-parameter:start_price | 参数填写不正确 | 参数填写不正确 |
| isv.invalid-parameter:end_price | 参数填写不正确 | 参数填写不正确 |
| isv.invalid-parameter:end_tk_rate | 参数填写不正确 | 参数填写不正确 |
| 4 | 查询不到对应的adzoneId | 请检查adzoneId是否正确 |
| 2 | pid不正确 | 请检查是否输入了正确的adzoneId和siteId |
| 1 | 内部服务不可用 | 稍后重试 |
| 30501 | 输入参数info_type非法 | 参考文档 |
| isp.sys-error | 内部服务出错 | 稍后重试 |

---
##taobao.tbk.sc.publisher.info.get（淘宝客-公用-私域用户备案信息查询）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| relation_id | Number | 可选 | 2323 |  | 渠道独占 - 渠道关系ID |
| page_no | Number | 可选 | 0 | 默认值：1 | 第几页，下标从0开始 |
| page_size | Number | 可选 | 10 | 默认值：10 | 每页大小 |
| info_type | Number | 必须 | 1 |  | 类型，必选 1:渠道信息；2:会员信息 |
| relation_app | String | 必须 | common |  | 备案的场景：common（通用备案），etao（一淘备案），minietao（一淘小程序备案），offlineShop（线下门店备案），offlinePerson（线下个人备案）。如不填默认common。查询会员信息只需填写common即可 |
| special_id | String | 可选 | 1212 |  | 会员独占 - 会员运营ID |
| external_id | String | 可选 | 12345 |  | 淘宝客外部用户标记，如自身系统账户ID；微信ID等 |
| external_type | Number | 可选 | 0 | 默认值：0 | 1-微信、2-微博、3-抖音、4-快手、5-QQ，0-其他；默认为0 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | Data |  | data |
| └ total_count | Number | 40 | 共享字段 - 总记录数 |
| └ inviter_list | MapData

                                 [] | inviterList | 共享字段 - 渠道或会员列表 |
| └ relation_app | String | common | 共享字段 - 备案场景：common（通用备案），etao（一淘备案），minietao（一淘小程序备案），offlineShop（线下门店备案），offlinePerson（线下个人备案） |
| └ create_date | Date | 2018-06-01 11:12:23 | 共享字段 - 备案日期 |
| └ account_name | String | s**x | 渠道独有 - 渠道昵称 |
| └ real_name | String | xxx | 渠道独有 - 渠道名称 |
| └ relation_id | Number | 40232 | 渠道独有 - 渠道关系ID |
| └ offline_scene | String | 门店 | 渠道独有 - 线下场景信息，1 - 门店，2- 学校，3 - 工厂，4 - 其他 |
| └ online_scene | String | 微信群 | 渠道独有 - 线上场景信息，1 - 微信群，2- QQ群，3 - 其他 |
| └ note | String | 小蜜蜂 | 渠道独有 - 媒体侧渠道备注信息 |
| └ root_pid | String | mm_1_1_1 | 共享字段 - 渠道/会员专属pid |
| └ rtag | String | 123 | 共享字段 - 渠道/会员原始身份信息 |
| └ offline_info | RegisterInfoDto | 线下 | 线下备案专属信息 |
| └ shop_name | String | 日用百货店 | 渠道独有 -店铺名称 |
| └ shop_type | String | 生活服务类 电信营业厅 | 渠道独有 -店铺类型 |
| └ phone_number | String | 1590000000 | 渠道独有 - 信息 |
| └ detail_address | String | **街道**号楼 | 渠道独有 -信息 |
| └ location | String | 内蒙古自治区 呼和浩特市 | 渠道独有 -区 |
| └ shop_certify_type | String | 营业执照 | 渠道独有 -类型 |
| └ certify_number | String | 123445677 | 渠道独有 - 编号 |
| └ career | String | 个人 快递员 | 渠道独有 -经营类型 |
| └ special_id | Number | 12345 | 会员独有 - 会员运营ID |
| └ punish_status | String | 1 | 渠道独有 - 处罚状态 |
| └ external_id | String | 12345 | 淘宝客外部用户标记 |
| └ external_type | String | 1 | 1-微信、2-微博、3-抖音、4-快手、5-QQ，0-其他 |
| └ root_pid_channel_list | String

                                 [] | ["mm_1_1_1"] | 渠道专属pidList |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.sc.publisher.info.get', {
	'relation_id':'2323',
	'page_no':'0',
	'page_size':'10',
	'info_type':'1',
	'relation_app':'common',
	'special_id':'1212',
	'external_id':'12345',
	'external_type':'0'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_sc_publisher_info_get_response":{
        "data":{
            "total_count":40,
            "inviter_list":{
                "map_data":[
                    {
                        "relation_app":"common",
                        "create_date":"2018-06-01 11:12:23",
                        "account_name":"s**x",
                        "real_name":"xxx",
                        "relation_id":40232,
                        "offline_scene":"门店",
                        "online_scene":"微信群",
                        "note":"小蜜蜂",
                        "root_pid":"mm_1_1_1",
                        "rtag":"123",
                        "offline_info":{
                            "shop_name":"日用百货店",
                            "shop_type":"生活服务类 电信营业厅",
                            "phone_number":"1590000000",
                            "detail_address":"**街道**号楼",
                            "location":"内蒙古自治区 呼和浩特市",
                            "shop_certify_type":"营业执照",
                            "certify_number":"123445677",
                            "career":"个人 快递员"
                        },
                        "special_id":12345,
                        "punish_status":"1",
                        "external_id":"12345",
                        "external_type":"1"
                    }
                ]
            },
            "root_pid_channel_list":{
                "string":[
                    "[\"mm_1_1_1\"]"
                ]
            }
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isp.tbkapi-service-unavailable | 淘宝客API服务不可用 | 请稍后重试 |
| isv.invalid-parameter:start_price | 参数填写不正确 | 参数填写不正确 |
| isv.invalid-parameter:end_price | 参数填写不正确 | 参数填写不正确 |
| isv.invalid-parameter:end_tk_rate | 参数填写不正确 | 参数填写不正确 |
| 4 | 查询不到对应的adzoneId | 请检查adzoneId是否正确 |
| 2 | pid不正确 | 请检查是否输入了正确的adzoneId和siteId |
| 30501 | 输入参数info_type非法 | 参考文档 |
| isp.sys-error | 服务异常 | 稍后重试 |

---
##taobao.tbk.sc.invitecode.get（淘宝客-公用-私域用户邀请码生成）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| relation_id | Number | 可选 | 11 |  | 渠道关系ID |
| relation_app | String | 必须 | common |  | 渠道推广的物料类型 |
| code_type | Number | 必须 | 1 |  | 邀请码类型，1 - 渠道邀请，2 - 渠道裂变，3 -会员邀请 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | Data |  | data |
| └ inviter_code | String | xxxx | 邀请码 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.sc.invitecode.get', {
	'relation_id':'11',
	'relation_app':'common',
	'code_type':'1'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_sc_invitecode_get_response":{
        "data":{
            "inviter_code":"xxxx"
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isp.tbkapi-service-unavailable | 淘宝客API服务不可用 | 请稍后重试 |
| isv.invalid-parameter:start_price | 参数填写不正确 | 参数填写不正确 |
| isv.invalid-parameter:end_price | 参数填写不正确 | 参数填写不正确 |
| isv.invalid-parameter:end_tk_rate | 参数填写不正确 | 参数填写不正确 |
| 4 | 查询不到对应的adzoneId | 请检查adzoneId是否正确 |
| 2 | pid不正确 | 请检查是否输入了正确的adzoneId和siteId |

---
##taobao.tbk.tbkinfo.get（淘宝客-公用-pid校验）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| pid | String | 必须 | mm_1_1_1 |  | 需要校验的三段式pid |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| result | RpcResult | result | result |
| └ data | Boolean | true | true表示pid校验正确 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.tbkinfo.get', {
	'pid':'mm_1_1_1'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_tbkinfo_get_response":{
        "result":{
            "data":true
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```


---
##taobao.tbk.tpwd.parse（淘宝客-公用-淘口令解析出原链接）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| password_content | String | 必须 | ￥asaff￥ |  | 需要解析的淘口令 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| data | MapData |  | data |
| └ origin_url | String | https://uland.taobao.com/coupon/edetail?e=xxx | 淘口令对应的landing链接 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.tpwd.parse', {
	'password_content':'￥asaff￥'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_tpwd_parse_response":{
        "data":{
            "origin_url":"https:\/\/uland.taobao.com\/coupon\/edetail?e=xxx"
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| isp.param-error | 参数错误 | 仔细检查参数 |
| isp.sys-error | 服务系统异常 | 请稍后再试 |
| 1 | 服务系统异常 | 请稍后再试 |
| 20010 | 淘口令解析失败 | 检查输入 |
| 20011 | 淘口令解析结果为空 | -- |
| 20012 | 淘口令解析输入口令为空 | 检查输入 |
| 6 | 当前淘口令无效，无法解析 | 更换淘口令 |


---
##taobao.tbk.item.details.upgrade.get（淘宝客-公用-淘宝客商品详情查询升级版（详细版））

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| item_id | String | 必须 | 3232 |  | 商品ID。多个用","分割，一次最多查询20个 |
| ip | String | 可选 | 11.22.33.43 |  | ip地址，影响邮费获取，如果不传或者传入不准确，邮费无法精准提供 |
| get_topn_rate | Number | 可选 | 0 |  | 是否获取前N件佣金信息，0否，1是，其他值否 |
| biz_scene_id | String | 可选 | 1 |  | 1-动态ID转链场景，2-消费者比价场景，3-商品库导购场景（不填默认为1）；场景id使用说明参考《淘宝客新商品ID升级》白皮书：https://www.yuque.com/taobaolianmengguanfangxiaoer/zmig94/tfyt0pahmlpzu2ud |
| promotion_type | String | 可选 | 2 |  | 1-自购省，2-推广赚（代理模式专属ID，代理模式必填，非代理模式不用填写该字段） |
| relation_id | String | 可选 | 1 |  | 渠道关系ID，仅适用于渠道推广场景 |
| manage_item_pub_id | Number | 可选 | 1 |  | 商品库服务账户(场景id3权限对应的memberid） |
| get_tlj_info | Number | 可选 | 0 |  | 是否获取单品淘礼金剩余数量，0-否，1-是，默认否(仅开通淘礼金权限媒体可查) |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| results | TbkItemDetail [] |  | 仅淘宝客商品，字段值根据API赋权等级输出 |
| └ sku_list | TbkItemDetailSku

                                 [] |  | 商品sku信息 |
| └ property_list | TbkItemDetailSkuProp

                                 [] |  | sku属性 |
| └ value_text | String | 藏青色 | 属性值名称 |
| └ value_id | Number | 28866 | 属性值ID |
| └ property_text | String | 颜色分类 | 属性名称 |
| └ property_id | Number | 1627207 | 属性ID |
| └ value_alias_text | String | 藏青色 | 属性值别名 |
| └ quantity | String | 6 | sku库存 |
| └ sku_id | Number | 4112264076 | skuId |
| └ sku_price_promotion_info | SkuPricePromotionInfo | {} | SKU价格促销信息 |
| └ sku_zk_final_price | String | 88.00 | 促销信息-销售价格，无促销时等于一口价，有促销时为促销价。若属于预售商品，付定金时间内，在线售卖价=预售价 |
| └ sku_final_promotion_price | String | 69.9 | 促销信息-预估到手价(元)。若属于预售商品，付定金时间内，预估到手价价=定金+尾款的预估到手价 |
| └ sku_final_promotion_path_list | SkuFinalPromotionPathMapData

                                 [] |  | SKU到手价优惠路径列表 |
| └ promotion_title | String | 商品券 | 优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 满7999减1300 | 优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_fee | String | 1300.00 | 优惠金额（元） |
| └ promotion_start_time | String | 1661184000000 | 优惠开始时间 |
| └ promotion_end_time | String | 1661788799000 | 优惠结束时间 |
| └ promotion_id | String | xx | 优惠ID |
| └ item_id | String | 4112264076123 | 商品ID |
| └ publish_info | PublishInfo | 1937297392332 | 淘客推广信息 |
| └ income_rate | String | 15.5 | 商品信息-收入比率(商品佣金比率+补贴比率)。15.5表示15.5% |
| └ topn_info | TopNInfoDTO |  | 前N件佣金信息-前N件佣金生效或预热时透出以下字段 |
| └ topn_quantity | Number | 3000 | 前N件剩余库存 |
| └ topn_total_count | Number | 3000 | 前N件初始总库存 |
| └ topn_end_time | String | 1937297392332 | 前N件佣金结束时间 |
| └ topn_start_time | String | 1937297392332 | 前N件佣金开始时间 |
| └ topn_rate | String | 30 | 前N件佣金率 |
| └ tlj_remain_num | Number | 19000 | 单品淘礼金今日剩余可创建个数 |
| └ two_hour_promotion_sales | Number | 24 | 两小时推广销量。 非实时，约15分钟更新 |
| └ daily_promotion_sales | Number | 111 | 当天推广销量。 非实时，约1小时更新（销量小于5不更新） |
| └ price_promotion_info | PromotionInfoMapData | 玩法 | 价格促销信息 |
| └ real_post_fee | String | 10.00 | 商品邮费金额，单位元（根据入参IP计算邮费） |
| └ reserve_price | String | 102.00 | 商品一口价格 |
| └ zk_final_price | String | 88.00 | 折扣价（元） 若属于预售商品，付定金时间内，折扣价=预售价 |
| └ final_promotion_price | String | 69.9 | 促销信息-预估到手价(元)。若属于预售商品，付定金时间内，预估到手价=预售尾款预估到手价 |
| └ final_promotion_path_list | FinalPromotionPathMapData

                                 [] |  | 优惠促销列表 |
| └ promotion_title | String | 商品券 | 优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 满7999减1300 | 优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_fee | String | 1300.00 | 优惠金额（元） |
| └ promotion_start_time | String | 2019-11-10 21:59:59 | 优惠开始时间 |
| └ promotion_end_time | String | 2019-11-10 21:59:59 | 优惠结束时间 |
| └ promotion_id | String | XX | 优惠ID |
| └ promotion_tag_list | PromotionTagMapData

                                 [] |  | 标签信息列表 |
| └ tag_name | String | 88VIP | 标签名称，如“88VIP”、“花呗免息”、“猫超买返”、“是否包邮” |
| └ predict_rounding_up_price | String | 56.1 | 促销信息-预估凑单价（元）。预估凑单叠加优惠后的商品单价 |
| └ predict_rounding_up_price_desc | String | 需买1件 | 促销信息-凑单价说明，描述凑单价的实现说明。如 “可凑单”或“需买X件” |
| └ more_promotion_list | MorePromotionMapData

                                 [] |  | 更多活动优惠 |
| └ promotion_title | String | 满件折 | 预热优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 2件9折 | 预热优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_start_time | String | 1661222400000 | 优惠开始时间 |
| └ promotion_end_time | String | 1662393600000 | 优惠结束时间 |
| └ promotion_id | String | XX | 优惠ID |
| └ promotion_total_count | Number | 1000 | 当天优惠总库存【指定优惠透出，不对外开放指定优惠透出，不对外开放】 |
| └ promotion_url | String | https:// | 优惠使用路径【指定优惠透出，不对外开放】 |
| └ activity_tag_list | ActivityTagMapData

                                 [] |  | 货品展示标识列表 |
| └ tag_name | String | 淘宝好价节 | 货品展示标识，展示在商品标题前的商品活动标 |
| └ multiple_items_coupon_list | MultiItemPromotionMapData

                                 [] |  | 多件价券信息 |
| └ promotion_title | String | 商品券 | 优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 满7999减1300 | 优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_fee | String | 1300.00 | 优惠金额（元） |
| └ promotion_start_time | String | 2019-11-10 21:59:59 | 优惠开始时间 |
| └ promotion_end_time | String | 2019-11-10 21:59:59 | 优惠结束时间 |
| └ promotion_id | String | XX | 优惠ID |
| └ unit_price_for_multiple_items | String | 56.1 | 多件单价 |
| └ multiple_items_prices_count | Number | 2 | 多件价需拍件数 |
| └ gov_subsidy | GovSubsidyDTO |  | 国家补贴 |
| └ tag_name | String | 国家补贴 | 国家补贴 |
| └ state_subsidy_info | StateSubsidyInfo |  | 国补信息 |
| └ max_rebate | Number | 1 | 最高优惠比例（%），入参具体IP时，仅展示该IP最高优惠比例。 |
| └ min_rebate | Number | 1 | 最低优惠比例（%），入参具体IP时，仅展示该IP最低优惠比例。 |
| └ max_discount | Number | 1 | 最高优惠金额（分，如1500代表1500分 = 15 元），入参具体IP时，仅展示该IP最高优惠金额 |
| └ min_discount | Number | 1 | 最低优惠金额（分，如1500代表1500分 = 15 元），入参具体IP时，仅展示该IP最低优惠金额。 |
| └ province_list | String

                                 [] |  | 国补生效区域（省份）。不入参IP时展示各可用省份；入参IP时，全国可用商品展示各可用省份，区域可用商品仅展示IP对应省份。 |
| └ future_activity_promotion_path_list | PreheatPromotionMapData

                                 [] |  | 预热价格信息 |
| └ promotion_title | String | 商品券 | 优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 满7999减1300 | 优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_fee | String | 1300.00 | 优惠金额（元） |
| └ promotion_start_time | String | 2019-11-10 21:59:59 | 优惠开始时间 |
| └ promotion_end_time | String | 2019-11-10 21:59:59 | 优惠结束时间 |
| └ future_activity_promotion_price | String | 56.1 | 预热预估到手价（元） |
| └ input_item_iid | String | qeqscd1231-uqwenqe | 输入的（新）商品ID |
| └ item_basic_info | BasicMapData | {} | 商品基本信息 |
| └ title | String | 连衣裙 | 商品标题 |
| └ short_title | String | 巴布豆菠萝超薄干爽拉拉裤xl60+6 | 商品信息-商品短标题 |
| └ pict_url | String | http://gi4.md.alicdn.com/bao/uploaded/i4/xxx.jpg | 商品主图 |
| └ white_image | String | https://img.alicdn.com/bao/uploaded/TB1De0xk4n1gK0jSZKPXXXvUXXa.png | 商品信息-商品白底图 |
| └ small_images | String

                                 [] |  | 商品小图列表 |
| └ level_one_category_name | String | 女装 | 一级类目名称 |
| └ category_name | String | 情趣内衣 | 叶子类目名称 |
| └ brand_name | String | 淘宝心选 | 商品信息-品牌名称 |
| └ provcity | String | 杭州 | 商品所在地 |
| └ item_url | String | http://detail.m.tmall.com/item.htm?id=xxx | 商品链接 |
| └ user_type | Number | 1 | 卖家类型，0表示集市，1表示商城，3表示特价版 |
| └ seller_id | Number | 123 | 卖家id |
| └ ratesum | Number | 13 | 卖家等级(字段等级SA，仅支持联系商务或运营小二申请) |
| └ shop_dsr | Number | 23 | 店铺dsr 评分(字段等级SA，仅支持联系商务或运营小二申请) |
| └ i_rfd_rate | Boolean | true | 退款率是否低于行业均值(字段等级SA，仅支持联系商务或运营小二申请) |
| └ h_good_rate | Boolean | true | 好评率是否高于行业均值(字段等级SA，仅支持联系商务或运营小二申请) |
| └ h_pay_rate30 | Boolean | true | 成交转化是否高于行业均值(字段等级SA，仅支持联系商务或运营小二申请) |
| └ volume | Number | 1 | 30天销量；数据统计截止昨日非实时更新 |
| └ quantity | String | 10 | 库存信息-商品库存 |
| └ is_prepay | Boolean | true | 是否加入消费者保障 |
| └ superior_brand | String | 1 | 是否品牌精选，0不是，1是 |
| └ material_lib_type | String | 1 | 商品库类型，支持多库类型输出，以英文逗号分隔“,”分隔，1:营销商品主推库，2. 内容商品库，如果值为空则不属于1，2这两种商品类型 |
| └ property_image_list | TbkItemDetailPropImg

                                 [] |  | 商品属性图片信息 |
| └ image_url | String | https://img.alicdn.com/bao/uploaded/i4/33283/O1CN01JMY9uO1a7enNCmCEP_!!33283.jpg | 属性图片主图地址 |
| └ properties | String | 1627207:6733755172（颜色分类--棉柔巾100抽(绿)） | 属性ID串 |
| └ property_list | TbkItemDetailProp

                                 [] |  | 商品属性信息 |
| └ value_text | String | 36 | 属性值名称 |
| └ value_id | Number | 671 | 属性值ID |
| └ property_text | String | 尺码 | 属性名称 |
| └ property_id | Number | 20509 | 属性ID |
| └ tmall_desc_url | String | ttps://mdetail.tmall.com/templates/pages/desc?id=5323 | pc宝贝详情(字段等级S，仅支持联系商务或运营小二申请) |
| └ taobao_desc_url | String | https://h5.m.taobao.com/app/detail/desc.html?_isH5Des=true#!id=2332&type=0&f=sdsdsd | H5宝贝详情(字段等级S，仅支持联系商务或运营小二申请) |
| └ shop_title | String | xx旗舰店 | 商品信息-店铺名称 |
| └ free_shipment | Boolean | true | 商品信息-是否包邮 |
| └ annual_vol | String | 1万+ | 年销量 |
| └ presale_info | PresaleInfo | {} | 预售信息 |
| └ presale_start_time | Number | 1567440000000 | 预售商品-付定金开始时间（毫秒） |
| └ presale_end_time | Number | 1567440000000 | 预售商品-付定金结束时间（毫秒） |
| └ presale_tail_start_time | Number | 1567440000000 | 预售商品-付尾款开始时间（毫秒） |
| └ presale_tail_end_time | Number | 1567440000000 | 预售商品-付尾款结束时间（毫秒） |
| └ presale_deposit | String | 100 | 预售商品-定金（元） |
| └ presale_discount_fee_text | String | 付定金立减5元 | 预售商品-优惠信息 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.item.details.upgrade.get', {
	'item_id':'3232',
	'ip':'11.22.33.43',
	'get_topn_rate':'0',
	'biz_scene_id':'1',
	'promotion_type':'2',
	'relation_id':'1',
	'manage_item_pub_id':'1',
	'get_tlj_info':'0'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_item_details_upgrade_get_response":{
        "results":{
            "tbk_item_detail":[
                {
                    "sku_list":{
                        "tbk_item_detail_sku":[
                            {
                                "property_list":{
                                    "tbk_item_detail_sku_prop":[
                                        {
                                            "value_text":"藏青色",
                                            "value_id":28866,
                                            "property_text":"颜色分类",
                                            "property_id":1627207,
                                            "value_alias_text":"藏青色"
                                        }
                                    ]
                                },
                                "quantity":"6",
                                "sku_id":4112264076,
                                "sku_price_promotion_info":{
                                    "sku_zk_final_price":"88.00",
                                    "sku_final_promotion_price":"69.9",
                                    "sku_final_promotion_path_list":{
                                        "sku_final_promotion_path_map_data":[
                                            {
                                                "promotion_title":"商品券",
                                                "promotion_desc":"满7999减1300",
                                                "promotion_fee":"1300.00",
                                                "promotion_start_time":"1661184000000",
                                                "promotion_end_time":"1661788799000",
                                                "promotion_id":"xx"
                                            }
                                        ]
                                    }
                                }
                            }
                        ]
                    },
                    "item_id":"4112264076123",
                    "publish_info":{
                        "income_rate":"15.5",
                        "topn_info":{
                            "topn_quantity":3000,
                            "topn_total_count":3000,
                            "topn_end_time":"1937297392332",
                            "topn_start_time":"1937297392332",
                            "topn_rate":"30"
                        },
                        "tlj_remain_num":19000,
                        "two_hour_promotion_sales":24,
                        "daily_promotion_sales":111
                    },
                    "price_promotion_info":{
                        "real_post_fee":"10.00",
                        "reserve_price":"102.00",
                        "zk_final_price":"88.00",
                        "final_promotion_price":"69.9",
                        "final_promotion_path_list":{
                            "final_promotion_path_map_data":[
                                {
                                    "promotion_title":"商品券",
                                    "promotion_desc":"满7999减1300",
                                    "promotion_fee":"1300.00",
                                    "promotion_start_time":"2019-11-10 21:59:59",
                                    "promotion_end_time":"2019-11-10 21:59:59",
                                    "promotion_id":"XX"
                                }
                            ]
                        },
                        "promotion_tag_list":{
                            "promotion_tag_map_data":[
                                {
                                    "tag_name":"88VIP"
                                }
                            ]
                        },
                        "predict_rounding_up_price":"56.1",
                        "predict_rounding_up_price_desc":"需买1件",
                        "more_promotion_list":{
                            "more_promotion_map_data":[
                                {
                                    "promotion_title":"满件折",
                                    "promotion_desc":"2件9折",
                                    "promotion_start_time":"1661222400000",
                                    "promotion_end_time":"1662393600000",
                                    "promotion_id":"XX",
                                    "promotion_total_count":1000,
                                    "promotion_url":"https:\/\/"
                                }
                            ]
                        },
                        "activity_tag_list":{
                            "activity_tag_map_data":[
                                {
                                    "tag_name":"淘宝好价节"
                                }
                            ]
                        },
                        "multiple_items_coupon_list":{
                            "multi_item_promotion_map_data":[
                                {
                                    "promotion_title":"商品券",
                                    "promotion_desc":"满7999减1300",
                                    "promotion_fee":"1300.00",
                                    "promotion_start_time":"2019-11-10 21:59:59",
                                    "promotion_end_time":"2019-11-10 21:59:59",
                                    "promotion_id":"XX"
                                }
                            ]
                        },
                        "unit_price_for_multiple_items":"56.1",
                        "multiple_items_prices_count":2,
                        "gov_subsidy":{
                            "tag_name":"国家补贴",
                            "state_subsidy_info":{
                                "max_rebate":1,
                                "min_rebate":1,
                                "max_discount":1,
                                "min_discount":1
                            }
                        },
                        "future_activity_promotion_path_list":{
                            "preheat_promotion_map_data":[
                                {
                                    "promotion_title":"商品券",
                                    "promotion_desc":"满7999减1300",
                                    "promotion_fee":"1300.00",
                                    "promotion_start_time":"2019-11-10 21:59:59",
                                    "promotion_end_time":"2019-11-10 21:59:59"
                                }
                            ]
                        },
                        "future_activity_promotion_price":"56.1"
                    },
                    "input_item_iid":"qeqscd1231-uqwenqe",
                    "item_basic_info":{
                        "title":"连衣裙",
                        "short_title":"巴布豆菠萝超薄干爽拉拉裤xl60+6",
                        "pict_url":"http:\/\/gi4.md.alicdn.com\/bao\/uploaded\/i4\/xxx.jpg",
                        "white_image":"https:\/\/img.alicdn.com\/bao\/uploaded\/TB1De0xk4n1gK0jSZKPXXXvUXXa.png",
                        "level_one_category_name":"女装",
                        "category_name":"情趣内衣",
                        "brand_name":"淘宝心选",
                        "provcity":"杭州",
                        "item_url":"http:\/\/detail.m.tmall.com\/item.htm?id=xxx",
                        "user_type":1,
                        "seller_id":123,
                        "ratesum":13,
                        "shop_dsr":23,
                        "i_rfd_rate":true,
                        "h_good_rate":true,
                        "h_pay_rate30":true,
                        "volume":1,
                        "quantity":"10",
                        "is_prepay":true,
                        "superior_brand":"1",
                        "material_lib_type":"1",
                        "property_image_list":{
                            "tbk_item_detail_prop_img":[
                                {
                                    "image_url":"https:\/\/img.alicdn.com\/bao\/uploaded\/i4\/33283\/O1CN01JMY9uO1a7enNCmCEP_!!33283.jpg",
                                    "properties":"1627207:6733755172（颜色分类--棉柔巾100抽(绿)）"
                                }
                            ]
                        },
                        "property_list":{
                            "tbk_item_detail_prop":[
                                {
                                    "value_text":"36",
                                    "value_id":671,
                                    "property_text":"尺码",
                                    "property_id":20509
                                }
                            ]
                        },
                        "tmall_desc_url":"ttps:\/\/mdetail.tmall.com\/templates\/pages\/desc?id=5323",
                        "taobao_desc_url":"https:\/\/h5.m.taobao.com\/app\/detail\/desc.html?_isH5Des=true#!id=2332&type=0&f=sdsdsd",
                        "shop_title":"xx旗舰店",
                        "free_shipment":true,
                        "annual_vol":"1万+"
                    },
                    "presale_info":{
                        "presale_start_time":1567440000000,
                        "presale_end_time":1567440000000,
                        "presale_tail_start_time":1567440000000,
                        "presale_tail_end_time":1567440000000,
                        "presale_deposit":"100",
                        "presale_discount_fee_text":"付定金立减5元"
                    }
                }
            ]
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| 50001 |  | 更换商品查询 |
| 40001 |  | 稍后重试 |
| 50002 |  | 稍后重试 |
| 2 |  | 检查除pid之外的相关入参adzoneId和siteId |
| 4 |  | 检查入参adzoneId |
| 5 |  | 检查pid相关入参，稍后重试 |
| 8 |  | 检查入参 |
| isp.tbkapi-service-unavailable |  | 请重试 |

---
##taobao.tbk.item.info.upgrade.get（淘宝客-公用-淘宝客商品详情查询升级版（简易版））

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| item_id | String | 必须 | 3232 |  | 商品ID。多个用","分割，一次最多查询20个 |
| ip | String | 可选 | 11.22.33.43 |  | ip地址，影响邮费获取，如果不传或者传入不准确，邮费无法精准提供 |
| biz_scene_id | String | 可选 | 1 |  | 1-动态ID转链场景，2-消费者比价场景，3-商品库导购场景（不填默认为1）；场景id使用说明参考《淘宝客新商品ID升级》白皮书：https://www.yuque.com/taobaolianmengguanfangxiaoer/zmig94/tfyt0pahmlpzu2ud |
| promotion_type | String | 可选 | 2 |  | 1-自购省，2-推广赚（代理模式专属ID，代理模式必填，非代理模式不用填写该字段） |
| relation_id | String | 可选 | 1 |  | 渠道关系ID，仅适用于渠道推广场景 |
| manage_item_pub_id | Number | 可选 | 1 |  | 商品库服务账户(场景id3权限对应的memberid） |
| get_tlj_info | Number | 可选 | 0 |  | 是否获取单品淘礼金剩余数量，0-否，1-是，默认否(仅开通淘礼金权限媒体可查) |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| results | TbkItemDetail [] |  | 仅淘宝客商品，字段值根据API赋权等级输出 |
| └ item_id | String | 4112264076123 | 商品ID |
| └ publish_info | PublishInfo | 1937297392332 | 淘客推广信息 |
| └ income_rate | String | 15.5 | 商品信息-收入比率(商品佣金比率+补贴比率)。15.5表示15.5% |
| └ topn_info | TopNInfoDTO |  | 前N件佣金信息-前N件佣金生效或预热时透出以下字段 |
| └ topn_quantity | Number | 3000 | 前N件剩余库存 |
| └ topn_total_count | Number | 3000 | 前N件初始总库存 |
| └ topn_end_time | String | 1937297392332 | 前N件佣金结束时间 |
| └ topn_start_time | String | 1937297392332 | 前N件佣金开始时间 |
| └ topn_rate | String | 30 | 前N件佣金率 |
| └ tlj_remain_num | Number | 19000 | 单品淘礼金今日剩余可创建个数 |
| └ two_hour_promotion_sales | Number | 24 | 两小时推广销量。 非实时，约半小时更新 |
| └ daily_promotion_sales | Number | 111 | 当天推广销量。 非实时，约1小时更新 |
| └ cpa_reward_type | String | 0 1 2 | 额外奖励活动类型，如果一个商品有多个奖励类型，返回结果使用空格分割，0=预售单单奖励，1=618超级U选单单补 |
| └ cpa_reward_amount | String | 1.11 2.22 3.21 | 额外奖励活动金额，活动奖励金额的类型与cpa_reward_type字段对应，如果一个商品有多个奖励类型，返回结果使用空格分割 |
| └ income_info | FinalIncomeInfo |  | 商品佣金信息 |
| └ commission_rate | String | 55 | 商品佣金比率 |
| └ commission_amount | String | 12 | 商品佣金金额 |
| └ subsidy_rate | String | 11 | 补贴比率 |
| └ subsidy_amount | String | 4 | 补贴金额 |
| └ subsidy_upper_limit | String | 10 | 补贴上限；仅在单笔订单命中补贴上限时返回结果否则出参为空 |
| └ subsidy_type | String | 妈妈补贴 | 补贴类型 |
| └ future_activity_commission_rate | String | 1550表示15.5% | 预热活动到手价对应的佣金比率 |
| └ future_activity_time | String | 1665504000000 | 预热价活动开始时间 |
| └ price_promotion_info | PromotionInfoMapData | 玩法 | 价格促销信息 |
| └ reserve_price | String | 102.00 | 商品一口价格 |
| └ zk_final_price | String | 88.00 | 折扣价（元） 若属于预售商品，付定金时间内，折扣价=预售价 |
| └ final_promotion_price | String | 69.9 | 促销信息-预估到手价(元)。若属于预售商品，付定金时间内，预估到手价=预售尾款预估到手价 |
| └ final_promotion_path_list | FinalPromotionPathMapData

                                 [] |  | 优惠促销列表 |
| └ promotion_title | String | 商品券 | 优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 满7999减1300 | 优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_fee | String | 1300.00 | 优惠金额（元） |
| └ promotion_start_time | String | 2019-11-10 21:59:59 | 优惠开始时间 |
| └ promotion_end_time | String | 2019-11-10 21:59:59 | 优惠结束时间 |
| └ promotion_id | String | XX | 优惠ID |
| └ promotion_tag_list | PromotionTagMapData

                                 [] |  | 标签信息列表 |
| └ tag_name | String | 88VIP | 标签名称，如“88VIP”、“花呗免息”、“猫超买返”、“是否包邮” |
| └ predict_rounding_up_price | String | 56.1 | 促销信息-预估凑单价（元）。预估凑单叠加优惠后的商品单价 |
| └ predict_rounding_up_price_desc | String | 需买1件 | 促销信息-凑单价说明，描述凑单价的实现说明。如 “可凑单”或“需买X件” |
| └ more_promotion_list | MorePromotionMapData

                                 [] |  | 更多活动优惠 |
| └ promotion_title | String | 满件折 | 预热优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 2件9折 | 预热优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_start_time | String | 1661222400000 | 优惠开始时间 |
| └ promotion_end_time | String | 1662393600000 | 优惠结束时间 |
| └ promotion_id | String | XX | 优惠ID |
| └ promotion_total_count | Number | 1000 | 当天优惠总库存【指定优惠透出，不对外开放】 |
| └ promotion_url | String | https:// | 优惠使用路径【指定优惠透出，不对外开放】 |
| └ activity_tag_list | ActivityTagMapData

                                 [] |  | 货品展示标识列表 |
| └ tag_name | String | 淘宝好价节 | 货品展示标识，展示在商品标题前的商品活动标 |
| └ gov_subsidy | GovSubsidyDTO |  | 国家补贴 |
| └ tag_name | String | 国家补贴 | 国家补贴 |
| └ state_subsidy_info | StateSubsidyInfo |  | 国补信息 |
| └ max_rebate | Number | 1 | 最高优惠比例（%），入参具体IP时，仅展示该IP最高优惠比例。 |
| └ min_rebate | Number | 1 | 最低优惠比例（%），入参具体IP时，仅展示该IP最低优惠比例。 |
| └ max_discount | String | 15.00 | 最高优惠金额（元，如15代表15 元），入参具体IP时，仅展示该IP最高优惠金额 |
| └ min_discount | String | 15.00 | 最低优惠金额（元，如15代表15 元），入参具体IP时，仅展示该IP最低优惠金额 |
| └ province_list | String

                                 [] |  | 国补生效区域（省份）。不入参IP时展示各可用省份；入参IP时，全国可用商品展示各可用省份，区域可用商品仅展示IP对应省份。 |
| └ future_activity_promotion_price | String | 56.1 | 预热预估到手价（元） |
| └ future_activity_promotion_path_list | String

                                 [] |  | 预热预估到手价信息 |
| └ promotion_title | String | 商品券 | 优惠名称，如“商品券”、“跨店满减”、“单品直降”等 |
| └ promotion_desc | String | 满7999减1300 | 预热优惠利益点文案，如“1件7.92折”、“每200减20”等 |
| └ promotion_fee | String | 1300.00 | 预热实际优惠金额（元） |
| └ promotion_start_time | String | 1661184000000 | 优惠开始时间 |
| └ promotion_end_time | String | 1661788799000 | 优惠结束时间 |
| └ input_item_iid | String | qeqscd1231-uqwenqe | 输入的（新）商品ID |
| └ item_basic_info | BasicMapData |  | 商品基本信息 |
| └ title | String | 连衣裙 | 商品标题 |
| └ pict_url | String | http://gi4.md.alicdn.com/bao/uploaded/i4/xxx.jpg | 商品主图 |
| └ small_images | String

                                 [] |  | 商品小图列表 |
| └ level_one_category_name | String | 女装 | 一级类目名称 |
| └ category_name | String | 情趣内衣 | 叶子类目名称 |
| └ provcity | String | 杭州 | 商品所在地 |
| └ item_url | String | http://detail.m.tmall.com/item.htm?id=xxx | 商品链接 |
| └ user_type | Number | 1 | 卖家类型，0表示集市，1表示商城，3表示特价版 |
| └ ratesum | Number | 13 | 卖家等级(字段等级SA) |
| └ shop_dsr | Number | 23 | 店铺dsr 评分(字段等级SA) |
| └ i_rfd_rate | Boolean | true | 退款率是否低于行业均值(字段等级SA) |
| └ h_good_rate | Boolean | true | 好评率是否高于行业均值(字段等级SA) |
| └ h_pay_rate30 | Boolean | true | 成交转化是否高于行业均值(字段等级SA) |
| └ volume | Number | 1 | 30天销量；数据统计截止昨日非实时更新 |
| └ is_prepay | Boolean | true | 是否加入消费者保障 |
| └ superior_brand | String | 1 | 是否品牌精选，0不是，1是 |
| └ material_lib_type | String | 1 | 商品库类型，支持多库类型输出，以英文逗号分隔“,”分隔，1:营销商品主推库，2. 内容商品库，如果值为空则不属于1，2这两种商品类型 |
| └ tmall_desc_url | String | ttps://mdetail.tmall.com/templates/pages/desc?id=5323 | pc宝贝详情(字段等级S) |
| └ taobao_desc_url | String | https://h5.m.taobao.com/app/detail/desc.html?_isH5Des=true#!id=2332&type=0&f=sdsdsd | H5宝贝详情(字段等级S) |
| └ shop_title | String | xx旗舰店 | 商品信息-店铺名称 |
| └ free_shipment | Boolean | true | 商品信息-是否包邮 |
| └ brand_name | String | 淘宝心选 | 商品信息-品牌名称 |
| └ short_title | String | 巴布豆菠萝超薄干爽拉拉裤xl60+6 | 商品信息-商品短标题 |
| └ white_image | String | https://img.alicdn.com/bao/uploaded/TB1De0xk4n1gK0jSZKPXXXvUXXa.png | 商品信息-商品白底图 |
| └ seller_id | Number | 123 | 卖家id(字段等级C) |
| └ annual_vol | String | 1万+ | 年销量 |
| └ presale_info | PresaleInfo |  | 预售信息 |
| └ presale_tail_end_time | Number | 1567440000000 | 预售商品-付尾款结束时间（毫秒） |
| └ presale_tail_start_time | Number | 1567440000000 | 预售商品-付尾款开始时间（毫秒） |
| └ presale_end_time | Number | 1567440000000 | 预售商品-付定金结束时间（毫秒） |
| └ presale_start_time | Number | 1567440000000 | 预售商品-付定金开始时间（毫秒） |
| └ presale_deposit | String | 100 | 预售商品-定金（元） |
| └ presale_discount_fee_text | String | 付定金立减5元 | 预售商品-优惠信息 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.item.info.upgrade.get', {
	'item_id':'3232',
	'ip':'11.22.33.43',
	'biz_scene_id':'1',
	'promotion_type':'2',
	'relation_id':'1',
	'manage_item_pub_id':'1',
	'get_tlj_info':'0'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_item_info_upgrade_get_response":{
        "results":{
            "tbk_item_detail":[
                {
                    "item_id":"4112264076123",
                    "publish_info":{
                        "income_rate":"15.5",
                        "topn_info":{
                            "topn_quantity":3000,
                            "topn_total_count":3000,
                            "topn_end_time":"1937297392332",
                            "topn_start_time":"1937297392332",
                            "topn_rate":"30"
                        },
                        "tlj_remain_num":19000,
                        "two_hour_promotion_sales":24,
                        "daily_promotion_sales":111,
                        "cpa_reward_type":"0 1 2",
                        "cpa_reward_amount":"1.11 2.22 3.21",
                        "income_info":{
                            "commission_rate":"55",
                            "commission_amount":"12",
                            "subsidy_rate":"11",
                            "subsidy_amount":"4",
                            "subsidy_upper_limit":"10",
                            "subsidy_type":"妈妈补贴"
                        },
                        "future_activity_commission_rate":"1550表示15.5%",
                        "future_activity_time":"1665504000000"
                    },
                    "price_promotion_info":{
                        "reserve_price":"102.00",
                        "zk_final_price":"88.00",
                        "final_promotion_price":"69.9",
                        "final_promotion_path_list":{
                            "final_promotion_path_map_data":[
                                {
                                    "promotion_title":"商品券",
                                    "promotion_desc":"满7999减1300",
                                    "promotion_fee":"1300.00",
                                    "promotion_start_time":"2019-11-10 21:59:59",
                                    "promotion_end_time":"2019-11-10 21:59:59",
                                    "promotion_id":"XX"
                                }
                            ]
                        },
                        "promotion_tag_list":{
                            "promotion_tag_map_data":[
                                {
                                    "tag_name":"88VIP"
                                }
                            ]
                        },
                        "predict_rounding_up_price":"56.1",
                        "predict_rounding_up_price_desc":"需买1件",
                        "more_promotion_list":{
                            "more_promotion_map_data":[
                                {
                                    "promotion_title":"满件折",
                                    "promotion_desc":"2件9折",
                                    "promotion_start_time":"1661222400000",
                                    "promotion_end_time":"1662393600000",
                                    "promotion_id":"XX",
                                    "promotion_total_count":1000,
                                    "promotion_url":"https:\/\/ "
                                }
                            ]
                        },
                        "activity_tag_list":{
                            "activity_tag_map_data":[
                                {
                                    "tag_name":"淘宝好价节"
                                }
                            ]
                        },
                        "gov_subsidy":{
                            "tag_name":"国家补贴",
                            "state_subsidy_info":{
                                "max_rebate":1,
                                "min_rebate":1,
                                "max_discount":"15.00",
                                "min_discount":"15.00"
                            }
                        },
                        "future_activity_promotion_price":"56.1",
                        "future_activity_promotion_path_list":{
                            "string":[
                                {
                                    "promotion_title":"商品券",
                                    "promotion_desc":"满7999减1300",
                                    "promotion_fee":"1300.00",
                                    "promotion_start_time":"1661184000000",
                                    "promotion_end_time":"1661788799000"
                                }
                            ]
                        }
                    },
                    "input_item_iid":"qeqscd1231-uqwenqe",
                    "item_basic_info":{
                        "title":"连衣裙",
                        "pict_url":"http:\/\/gi4.md.alicdn.com\/bao\/uploaded\/i4\/xxx.jpg",
                        "level_one_category_name":"女装",
                        "category_name":"情趣内衣",
                        "provcity":"杭州",
                        "item_url":"http:\/\/detail.m.tmall.com\/item.htm?id=xxx",
                        "user_type":1,
                        "ratesum":13,
                        "shop_dsr":23,
                        "i_rfd_rate":true,
                        "h_good_rate":true,
                        "h_pay_rate30":true,
                        "volume":1,
                        "is_prepay":true,
                        "superior_brand":"1",
                        "material_lib_type":"1",
                        "tmall_desc_url":"ttps:\/\/mdetail.tmall.com\/templates\/pages\/desc?id=5323",
                        "taobao_desc_url":"https:\/\/h5.m.taobao.com\/app\/detail\/desc.html?_isH5Des=true#!id=2332&type=0&f=sdsdsd",
                        "shop_title":"xx旗舰店",
                        "free_shipment":true,
                        "brand_name":"淘宝心选",
                        "short_title":"巴布豆菠萝超薄干爽拉拉裤xl60+6",
                        "white_image":"https:\/\/img.alicdn.com\/bao\/uploaded\/TB1De0xk4n1gK0jSZKPXXXvUXXa.png",
                        "seller_id":123,
                        "annual_vol":"1万+"
                    },
                    "presale_info":{
                        "presale_tail_end_time":1567440000000,
                        "presale_tail_start_time":1567440000000,
                        "presale_end_time":1567440000000,
                        "presale_start_time":1567440000000,
                        "presale_deposit":"100",
                        "presale_discount_fee_text":"付定金立减5元"
                    }
                }
            ]
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```

### 错误码表

| 错误码 | 错误描述 | 解决方案 |
|--------|---------|---------|
| 1001 |  | 传入正确的me参数值，含有券ID与商品ID信息 |
| 10000 |  | 更换新的itemId查询 |
| 4 |  | 查询不到对应的adzoneId，请检查adzoneId是否正确 |
| 30002 |  | 参数q与cat不能都为空 |
| 2 |  | pid不正确，请检查是否输入了正确的adzoneId和siteId |
| 50001 |  | 更换查询条件 |
| 40001 |  | 请稍后重试 |
| 30001 |  | 请传入有效的物料ID |
| 5 |  | 检查pid相关参数，稍后重试 |
| isp.entry-sys-error |  | 稍后重试 |
| isp.pid-check-error |  | 检查pid相关参数，稍后重试 |
| isp.sys-error |  | 稍后重试 |
| 50002 |  | 调用频率高，请稍后再试 |
| 1201 |  | 请重试 |
| 719 |  | 请重试。另同步重要通知：您需将商品ID字段类型调整为同时兼容number和string类型，否则8月8日起调用将会出现异常，如已调整完成可忽略本次错误提示，点击https://mo.m.taobao.com/union/page_20220701_150002_297 查看公告详情，如有疑问可加入【淘宝联盟】线上合规升级咨询群（钉钉群：44748908）进行咨询。 |
| 1911 |  | 该appkey没有本sceneId权限，如有需要请联系对口商务/运营申请（钉钉咨询群号：44964951） |

---
##taobao.tbk.itemid.ineffective.transform（淘宝客-公用-失效商品id转化）

### 请求参数

| 参数名称 | 类型 | 是否必须 | 示例值 | 更多限制 | 描述 |
|---------|------|---------|--------|---------|------|
| item_ids | String | 必须 | 1,2,3 |  | 商品id列表，使用英文逗号拼接 |

### 响应参数

| 参数名称 | 类型 | 示例值 | 描述 |
|---------|------|--------|------|
| results | ItemIdTransformDTO [] |  | 结果列表 |
| └ original_item_id | String | 12 | 原商品id |
| └ item_id | String | cd1 | 升级后的商品id-b段 |

### NodeJS 调用示例

```javascript
TopClient = require('./topClient').TopClient;
var client = new TopClient({
	'appkey': 'appkey',
	'appsecret': 'secret',
	'REST_URL': 'http://gw.api.taobao.com/router/rest'
});

client.execute('taobao.tbk.itemid.ineffective.transform', {
	'item_ids':'1,2,3'
}, function(error, response) {
	if (!error) console.log(response);
	else console.log(error);
})
```

### JSON 响应示例

```json
{
    "tbk_itemid_ineffective_transform_response":{
        "results":{
            "item_id_transform_d_t_o":[
                {
                    "original_item_id":"12",
                    "item_id":"cd1"
                }
            ]
        }
    }
}
```

### 异常示例

```json
{
	"error_response":{
		"msg":"Remote service error",
		"code":50,
		"sub_msg":"非法参数",
		"sub_code":"isv.invalid-parameter"
	}
}
```
