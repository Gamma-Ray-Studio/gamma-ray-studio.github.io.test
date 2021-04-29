Template , Config
=====
`app : MarkAccount | template : system.template-config`

Contents
------
+ Individual
+ Couple
+ People
+ Activity
+ Schedule



Individual
------
`name : Individual | point : true | unit : USD`

### title
`type : date`

### subtitle
`type : subgroup`

+ Transportation
+ Breakfast
+ Lunch
+ Dinner
+ Brunch
+ Afternoon Tea
+ Night Snack
+ Others
+ Supermarket
+ Routine Expenses

### item
+ Beverage
+ Dessert
+ Metro Fee
+ Gas Fee

### item
`group : Breakfast`

+ Toast
+ Hamburger
+ Milk Tea
+ Coffee

### item 
`group : Dinner`

+ Beef Noodle
+ Fried Chicken
+ Hotpot
+ Steak

### item
`group : Living Necessities`

+ Egg
+ Milk
+ Vegetables
+ Instant Noodle
+ Cola
+ Bacon

### item 
`group : Routine Expenses`

+ Rent Fee
+ Internet Fee
+ Water Fee
+ Electricity Fee
+ Gas Fee


Couple
------
`name : Couple | point : true | unit : USD`

### title
`type : date`

### subtitle
`type : member`

+ Richard
+ Joy

### item
+ Beverage
+ Dessert
+ Breakfast
+ Lunch
+ Dinner
+ Brunch
+ Afternoon Tea

### item 
`group : Dinner`

+ Beef Noodle
+ Fried Chicken
+ Hotpot
+ Steak

### item
`group : Living Necessities`

+ Egg
+ Milk
+ Vegetables
+ Instant Noodle
+ Cola
+ Bacon

### item 
`group : Routine Expenses`

+ Rent Fee
+ Internet Fee
+ Water Fee
+ Electricity Fee
+ Gas Fee


People
------
`name : People | point : true | unit : USD`

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
+ Cake
+ Donut
+ Beverage

### item
`group : Beverage`

+ Black Tea
+ Green Tea
+ Milk Tea
+ Oolong Tea

### item
`group : Fried Food`

+ Fried Chicken
+ French Fries
+ Tofu
+ Onion Ring

### item
`group : Ice Cream`

+ Chocolate
+ Vanilla
+ Strawberry
+ Mango
+ Pineapple


Activity
------
`name : Activity | point : true | unit : USD`

### title
`type : list`

+ Transportation
+ Accommodation
+ Day 1
+ Day 2
+ Day 3

### subtitle
`type : subgroup`

+ Air Ticket
+ Taxi
+ Food
+ Souvenirs
+ Clothes

### item
`group : Air Ticket`

+ Departure
+ Return

### item
`group : Accommodation`

+ Hotel
+ B&B

### item
`group : Food`

+ Breakfast
+ Lunch
+ Dinner

### item
`group : Shopping`

+ Clothes
+ Shoes
+ Souvenirs


Schedule
------
`name : Schedule | point : true | unit : Hrs`

### title
`type : list`

+ Day 1
+ Day 2
+ Day 3
+ Day 4
+ Day 5

### subtitle
`type : subgroup`

+ Transportation
+ Accommodation
+ Dining
+ Shopping
+ Activity

### item
`group : Shopping`

+ Tokyo Train Station
+ Ginza
+ Donki

### item
`group : Sightseeing`

+ Sensoji
+ Tokyo Skytree
+ Meiji Jingu
+ Tokyo Disneyland
+ Tokyo Tower

### item
`group : Dining`

+ Matcha
+ Takoyaki
+ Okonomiyaki
+ Sashimi
+ ICHIRAN Ramen


