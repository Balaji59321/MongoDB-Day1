# MongoDB-Day1

Assignment 1   

Pre-requesite queries:    
> use student     
switched to db student     
> db.getCollectionNames()     
[ "product" ]     
> db.product.insertMany([
...     {
...         "id": "1",
...         "product_name": "Intelligent Fresh Chips",
...         "product_price": 655.00,
...         "product_material": "Concrete",
...         "product_color": "mint green"
...     },
...     {
...         "id": "2",
...         "product_name": "Practical Fresh Sausages",
...         "product_price": 911.0,
...         "product_material": "Cotton",
...         "product_color": "indigo"
...     },
...     {
...         "id": "3",
...         "product_name": "Refined Steel Car",
...         "product_price": 690.00,
...         "product_material": "Rubber",
...         "product_color": "gold"
...     },
...     {
...         "id": "4",
...         "product_name": "Gorgeous Plastic Pants",
...         "product_price": 492.00,
...         "product_material": "Soft",
...         "product_color": "plum"
...     },
...     {
...         "id": "5",
...         "product_name": "Sleek Cotton Chair",
...         "product_price": 33.00,
...         "product_material": "Fresh",
...         "product_color": "black"
...     },
...     {
...         "id": "6",
...         "product_name": "Awesome Wooden Towels",
...         "product_price": 474.00,
...         "product_material": "Plastic",
...         "product_color": "orange"
...     },
...     {
...         "id": "7",
...         "product_name": "Practical Soft Shoes",
...         "product_price": 500.00,
...         "product_material": "Rubber",
...         "product_color": "pink"
...     },
...     {
...         "id": "8",
...         "product_name": "Incredible Steel Hat",
...         "product_price": 78.00,
...         "product_material": "Rubber",
...         "product_color": "violet"
...     },
...     {
...         "id": "9",
...         "product_name": "Awesome Wooden Ball",
...         "product_price": 28.00,
...         "product_material": "Soft",
...         "product_color": "azure"
...     },
...     {
...         "id": "10",
...         "product_name": "Generic Wooden Pizza",
...         "product_price": 84.00,
...         "product_material": "Frozen",
...         "product_color": "indigo"
...     },
...     {
...         "id": "11",
...         "product_name": "Unbranded Wooden Cheese",
...         "product_price":26.00,
...         "product_material": "Soft",
...         "product_color": "black"
...     },
...     {
...         "id": "12",
...         "product_name": "Unbranded Plastic Salad",
...         "product_price": 89.00,
...         "product_material": "Wooden",
...         "product_color": "pink"
...     },
...     {
...         "id": "13",
...         "product_name": "Gorgeous Cotton Keyboard",
...         "product_price": 37.00,
...         "product_material": "Concrete",
...         "product_color": "sky blue"
...     },
...     {
...         "id": "14",
...         "product_name": "Incredible Steel Shirt",
...         "product_price": 54.00,
...         "product_material": "Metal",
...         "product_color": "white"
...     },
...     {
...         "id": "15",
...         "product_name": "Ergonomic Cotton Hat",
...         "product_price": 43.00,
...         "product_material": "Rubber",
...         "product_color": "mint green"
...     },
...     {
...         "id": "16",
...         "product_name": "Small Soft Chair",
...         "product_price": 47.00,
...         "product_material": "Cotton",
...         "product_color": "teal"
...     },
...     {
...         "id": "17",
...         "product_name": "Incredible Metal Car",
...         "product_price":36.00,
...         "product_material": "Fresh",
...         "product_color": "indigo"
...     },
...     {
...         "id": "18",
...         "product_name": "Licensed Plastic Bacon",
...         "product_price":88.00,
...         "product_material": "Steel",
...         "product_color": "yellow"
...     },
...     {
...         "id": "19",
...         "product_name": "Intelligent Cotton Chips",
...         "product_price": 46.00,
...         "product_material": "Soft",
...         "product_color": "azure"
...     },
...     {
...         "id": "20",
...         "product_name": "Handcrafted Wooden Bacon",
...         "product_price": 36.00,
...         "product_material": "Concrete",
...         "product_color": "lime"
...     },
...     {
...         "id": "21",
...         "product_name": "Unbranded Granite Chicken",
...         "product_price": 90.00,
...         "product_material": "Metal",
...         "product_color": "gold"
...     },
...     {
...         "id": "22",
...         "product_name": "Ergonomic Soft Hat",
...         "product_price": 99.00,
...         "product_material": "Rubber",
...         "product_color": "black"
...     },
...     {
...         "id": "23",
...         "product_name": "Intelligent Steel Pizza",
...         "product_price": 95.00,
...         "product_material": "Cotton",
...         "product_color": "azure"
...     },
...     {
...         "id": "24",
...         "product_name": "Tasty Rubber Cheese",
...         "product_price":47.00,
...         "product_material": "Frozen",
...         "product_color": "orchid"
...     },
...     {
...         "id": "25",
...         "product_name": "Licensed Steel Car",
...         "product_price":20.00,
...         "product_material": "Cotton",
...         "product_color": "indigo"
...     }
... ])        
\{ 
	"acknowledged" : true,
	"insertedIds" : [
		ObjectId("626cae63ed9457cf1c61df7d"),
		ObjectId("626cae63ed9457cf1c61df7e"),
		ObjectId("626cae63ed9457cf1c61df7f"),
		ObjectId("626cae63ed9457cf1c61df80"),
		ObjectId("626cae63ed9457cf1c61df81"),
		ObjectId("626cae63ed9457cf1c61df82"),
		ObjectId("626cae63ed9457cf1c61df83"),
		ObjectId("626cae63ed9457cf1c61df84"),
		ObjectId("626cae63ed9457cf1c61df85"),
		ObjectId("626cae63ed9457cf1c61df86"),
		ObjectId("626cae63ed9457cf1c61df87"),
		ObjectId("626cae63ed9457cf1c61df88"),
		ObjectId("626cae63ed9457cf1c61df89"),
		ObjectId("626cae63ed9457cf1c61df8a"),
		ObjectId("626cae63ed9457cf1c61df8b"),
		ObjectId("626cae63ed9457cf1c61df8c"),
		ObjectId("626cae63ed9457cf1c61df8d"),
		ObjectId("626cae63ed9457cf1c61df8e"),
		ObjectId("626cae63ed9457cf1c61df8f"),
		ObjectId("626cae63ed9457cf1c61df90"),
		ObjectId("626cae63ed9457cf1c61df91"),
		ObjectId("626cae63ed9457cf1c61df92"),
		ObjectId("626cae63ed9457cf1c61df93"),
		ObjectId("626cae63ed9457cf1c61df94"),
		ObjectId("626cae63ed9457cf1c61df95")
	]
}      


Find all the information about each products          
<img width="1370" alt="Screen Shot 2022-04-30 at 9 08 20 AM" src="https://user-images.githubusercontent.com/26063120/166089128-6349f2d2-cfee-46bc-9392-7a4c0618bb67.png">      


Find the product price which are between 400 to 800            
<img width="1680" alt="Screen Shot 2022-04-30 at 9 18 53 AM" src="https://user-images.githubusercontent.com/26063120/166089452-f5853db0-3ae1-42c4-a6eb-327e6c9de64f.png">      

   
Find the product price which are not between 400 to 600      
db.product.find({$and : [{product_price :{$not :  {$gte : 400}}},{product_price : {$not : {$lte : 800}}}]})
<img width="1680" alt="Screen Shot 2022-04-30 at 4 21 05 PM" src="https://user-images.githubusercontent.com/26063120/166117258-c7c79616-539b-48ee-ab13-79bd7099f093.png">


List the four product which are grater than 500 in price     
<img width="1680" alt="Screen Shot 2022-04-30 at 9 29 54 AM" src="https://user-images.githubusercontent.com/26063120/166089757-0a3cb0b6-8c33-45c3-b832-06192e87c68d.png">


Find the product name and product material of each products      
<img width="400" alt="Screen Shot 2022-04-30 at 9 33 20 AM" src="https://user-images.githubusercontent.com/26063120/166089857-99ca2861-c209-4d5b-a77b-b50d8684e839.png">


Find the product with a row id of 10      
<img width="1680" alt="Screen Shot 2022-04-30 at 9 34 41 AM" src="https://user-images.githubusercontent.com/26063120/166089903-7a4c8968-a550-495e-9007-b35b1db7a6ef.png">


Find only the product name and product material   
<img width="400" alt="Screen Shot 2022-04-30 at 9 33 20 AM" src="https://user-images.githubusercontent.com/26063120/166089922-8ce31a04-dc3a-49d0-bcc5-724ba36d215d.png">

Find all products which contain the value of soft in product material     
<img width="1678" alt="Screen Shot 2022-04-30 at 9 36 41 AM" src="https://user-images.githubusercontent.com/26063120/166089944-2032538e-1ab9-4d45-a1cf-26313547ae7c.png">


Find products which contain product color indigo  and product price 492.00       
<img width="1680" alt="Screen Shot 2022-04-30 at 9 40 14 AM" src="https://user-images.githubusercontent.com/26063120/166090057-307a9bd0-48e1-42f5-9274-f3f51d54d5f0.png">


Delete the products which product price value are same    
<img width="1674" alt="Screen Shot 2022-05-06 at 4 32 16 PM" src="https://user-images.githubusercontent.com/26063120/167119726-14a09c3e-5b35-4634-923d-f75c170fd4aa.png">
db.product.aggregate([{ $group : { _id: "$product_price",count : {$sum : 1},"dups" :{"$push" : "$id"}}},{$match : {count : {$gt : 1}} }])
db.product.remove({id : {$in : ["24","20"]}})


