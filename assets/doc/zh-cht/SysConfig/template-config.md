Template , Config
=====
`app : MarkAccount | template : system.template-config`

Contents
------
+ 個人帳本
+ 雙人帳本
+ 多人帳本
+ 活動預算
+ 時程規劃



個人帳本
------
`name : 個人帳本 | point : false | unit : 元`

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
+ 雜項
+ 超市
+ 固定開銷

### item
+ 飲料
+ 點心
+ 捷運
+ 加油

### item
`group : 早餐`

+ 蛋餅
+ 漢堡
+ 奶茶
+ 咖啡

### item 
`group : 晚餐`

+ 排骨
+ 滷味
+ 炸雞
+ 火鍋
+ 牛排

### item
`group : 生活雜物`

+ 雞蛋
+ 牛奶
+ 蔬菜
+ 泡麵
+ 可樂
+ 鳳梨酥
+ 玉米罐頭

### item 
`group : 固定開銷`

+ 房租
+ 管理費
+ 水費
+ 電費
+ 瓦斯費


雙人帳本
------
`name : 雙人帳本 | point : true | unit : 元`

### title
`type : date`

### subtitle
`type : member`

+ Richard
+ Joy

### item
+ 飲料
+ 點心
+ 早餐
+ 中餐
+ 晚餐
+ 早午餐
+ 下午茶

### item 
`group : 晚餐`

+ 排骨
+ 滷味
+ 炸雞
+ 火鍋
+ 牛排

### item
`group : 生活雜物`

+ 雞蛋
+ 牛奶
+ 蔬菜
+ 泡麵
+ 可樂
+ 鳳梨酥
+ 玉米罐頭

### item 
`group : 固定開銷`

+ 房租
+ 管理費
+ 水費
+ 電費
+ 瓦斯費


多人帳本
------
`name : 多人帳本 | point : false | unit : 元`

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
+ 蔥油餅
+ 鹽酥雞
+ 飲料

### item
`group : 飲料`

+ 紅茶
+ 綠茶
+ 奶茶
+ 烏龍茶
+ 鮮奶茶

### item
`group : 炸物`

+ 雞排
+ 薯條
+ 鹽酥雞
+ 甜不辣
+ 洋蔥圈

### item
`group : 冰品`

+ 巧克力
+ 香草
+ 草莓
+ 芒果
+ 鳳梨


活動預算
------
`name : 活動預算 | point : false | unit : 元`

### title
`type : list`

+ 交通
+ 住宿
+ 第一天
+ 第二天
+ 第三天

### subtitle
`type : subgroup`

+ 機票
+ 計程車
+ 餐費
+ 伴手禮
+ 衣服

### item
`group : 機票`

+ 去程
+ 返程

### item
`group : 住宿`

+ 飯店
+ 民宿

### item
`group : 餐費`

+ 早餐
+ 中餐
+ 晚餐

### item
`group : 購物`

+ 伴手禮
+ 紀念品


時程規劃
------
`name : 時程規劃 | point : true | unit : 小時`

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
+ 購物
+ 活動

### item
`group : 購物行程`

+ 東京車站
+ 銀座
+ 唐吉軻德

### item
`group : 觀光行程`

+ 淺草
+ 晴空塔
+ 明治神宮
+ 東京迪士尼
+ 東京鐵塔

### item
`group : 用餐行程`

+ 抹茶
+ 章魚燒
+ 大阪燒
+ 生魚片
+ 一蘭拉麵

