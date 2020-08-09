# HWK2
cy公司打算建立一個訂便當的系統，流程可隨意安排
1. 建立一個資料庫 create database~~~~~ 新增資料
有哪些廠商，
2. 新增幾筆會員，幾個菜單，種類，可加入外鍵
3. 最後下一個簡單的select句子(select * from ~~~)



建立資料庫

建立資料表
Restaurant : RestaurantID, Address
Food : FoodID, FoodName, UnitPrice
Groups : GroupID, GroupName
Employee : EmployeeID, GroupID, Name, Address
OrderDetail : OrdersID, RestaurantID, FoodID, Quantity
Orders : OrderID, GroupID, OrderDate, RestaurantID

建立關聯
	- fk_emp_grp		→ 員工與組別之關聯
	- fk_odr_grp		→ 訂單與組別之關聯
	- fk_odr_rest		→ 訂單與餐廳之關聯
	- fk_odrdtl_odr		→ 訂單明細與訂單之關聯
	- fk_odrdtl_rest	→ 訂單明細與餐廳之關聯
	- fk_odrdtl_fd		→ 訂單明細與食物之關聯
	
加入餐廳
加入餐點
加入員工組別
加入員工
加入訂單
## 加入訂單明細