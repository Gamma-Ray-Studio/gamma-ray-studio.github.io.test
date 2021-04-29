Template , Config
=====
`app : MarkAccount | template : system.template-config`

Contents
------
+ 个人帐本
+ 双人帐本
+ 多人帐本
+ 活动预算
+ 时程规划



个人帐本
------
`name : 个人帐本 | point : false | unit : 元`

### title
`type : date`

### subtitle
`type : subgroup`

+ 交通
+ 早餐
+ 中餐
+ 晚餐
+ 早午餐
+ 下午茶
+ 宵夜
+ 杂项
+ 超市
+ 固定开销

### item
+ 饮料
+ 点心
+ 地铁
+ 加油

### item
`group : 早餐`

+ 蛋饼
+ 汉堡
+ 奶茶
+ 咖啡

### item 
`group : 晚餐`

+ 排骨
+ 卤味
+ 炸鸡
+ 火锅
+ 牛排

### item
`group : 生活杂物`

+ 鸡蛋
+ 牛奶
+ 蔬菜
+ 泡面
+ 可乐
+ 凤梨酥
+ 玉米罐头

### item 
`group : 固定开销`

+ 房租
+ 管理费
+ 水费
+ 电费
+ 瓦斯费


双人帐本
------
`name : 双人帐本 | point : true | unit : 元`

### title
`type : date`

### subtitle
`type : member`

+ Richard
+ Joy

### item
+ 饮料
+ 点心
+ 早餐
+ 中餐
+ 晚餐
+ 早午餐
+ 下午茶

### item 
`group : 晚餐`

+ 排骨
+ 卤味
+ 炸鸡
+ 火锅
+ 牛排

### item
`group : 生活杂物`

+ 鸡蛋
+ 牛奶
+ 蔬菜
+ 泡面
+ 可乐
+ 凤梨酥
+ 玉米罐头

### item 
`group : 固定开销`

+ 房租
+ 管理费
+ 水费
+ 电费
+ 瓦斯费


多人帐本
------
`name : 多人帐本 | point : false | unit : 元`

### title
`type : date`

### subtitle
`type : member`

+ Richard
+ Joy
+ Gamma
+ Ray
+ Studio

### item
+ 葱油饼
+ 盐酥鸡
+ 饮料

### item
`group : 饮料`

+ 红茶
+ 绿茶
+ 奶茶
+ 乌龙茶
+ 鲜奶茶

### item
`group : 炸物`

+ 鸡排
+ 薯条
+ 盐酥鸡
+ 甜不辣
+ 洋葱圈

### item
`group : 冰品`

+ 巧克力
+ 香草
+ 草莓
+ 芒果
+ 凤梨


活动预算
------
`name : 活动预算 | point : false | unit : 元`

### title
`type : list`

+ 交通
+ 住宿
+ 第一天
+ 第二天
+ 第三天

### subtitle
`type : subgroup`

+ 机票
+ 计程车
+ 餐费
+ 伴手礼
+ 衣服

### item
`group : 机票`

+ 去程
+ 返程

### item
`group : 住宿`

+ 饭店
+ 民宿

### item
`group : 餐费`

+ 早餐
+ 中餐
+ 晚餐

### item
`group : 购物`

+ 伴手礼
+ 纪念品


时程规划
------
`name : 时程规划 | point : true | unit : 小时`

### title
`type : list`

+ Day 1
+ Day 2
+ Day 3
+ Day 4
+ Day 5

### subtitle
`type : subgroup`

+ 交通
+ 住宿
+ 休息
+ 用餐
+ 购物
+ 活动

### item
`group : 购物行程`

+ 东京车站
+ 银座
+ 唐吉轲德

### item
`group : 观光行程`

+ 浅草
+ 晴空塔
+ 明治神宫
+ 东京迪士尼
+ 东京铁塔

### item
`group : 用餐行程`

+ 抹茶
+ 章鱼烧
+ 大坂烧
+ 生鱼片
+ 一兰拉面

