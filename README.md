# product_mongo
day_38
PLEASE VIEW THE CODE BY CLICKING RAW ......

 >use product
>db.product.insertMany(
[
	    {
	        "id": "1",
	        "product_name": "Intelligent Fresh Chips",
	        "product_price": 655.00,
	        "product_material": "Concrete",
	        "product_color": "mint green"
	    },
	    {
	        "id": "2",
	        "product_name": "Practical Fresh Sausages",
	        "product_price": 911.0,
	        "product_material": "Cotton",
	        "product_color": "indigo"
	    },
	    {
	        "id": "3",
	        "product_name": "Refined Steel Car",
	        "product_price": 690.00,
	        "product_material": "Rubber",
	        "product_color": "gold"
	    },
	    {
	        "id": "4",
	        "product_name": "Gorgeous Plastic Pants",
	        "product_price": 492.00,
	        "product_material": "Soft",
	        "product_color": "plum"
	    },
	    {
	        "id": "5",
	        "product_name": "Sleek Cotton Chair",
	        "product_price": 33.00,
	        "product_material": "Fresh",
	        "product_color": "black"
	    },
	    {
	        "id": "6",
	        "product_name": "Awesome Wooden Towels",
	        "product_price": 474.00,
	        "product_material": "Plastic",
	        "product_color": "orange"
	    },
	    {
	        "id": "7",
	        "product_name": "Practical Soft Shoes",
	        "product_price": 500.00,
	        "product_material": "Rubber",
	        "product_color": "pink"
	    },
	    {
	        "id": "8",
	        "product_name": "Incredible Steel Hat",
	        "product_price": 78.00,
	        "product_material": "Rubber",
	        "product_color": "violet"
	    },
	    {
	        "id": "9",
	        "product_name": "Awesome Wooden Ball",
	        "product_price": 28.00,
	        "product_material": "Soft",
	        "product_color": "azure"
	    },
	    {
	        "id": "10",
	        "product_name": "Generic Wooden Pizza",
	        "product_price": 84.00,
	        "product_material": "Frozen",
	        "product_color": "indigo"
	    },
	    {
	        "id": "11",
	        "product_name": "Unbranded Wooden Cheese",
	        "product_price":26.00,
	        "product_material": "Soft",
	        "product_color": "black"
	    },
	    {
	        "id": "12",
	        "product_name": "Unbranded Plastic Salad",
	        "product_price": 89.00,
	        "product_material": "Wooden",
	        "product_color": "pink"
	    },
	    {
	        "id": "13",
	        "product_name": "Gorgeous Cotton Keyboard",
	        "product_price": 37.00,
	        "product_material": "Concrete",
	        "product_color": "sky blue"
	    },
	    {
	        "id": "14",
	        "product_name": "Incredible Steel Shirt",
	        "product_price": 54.00,
	        "product_material": "Metal",
	        "product_color": "white"
	    },
	    {
	        "id": "15",
	        "product_name": "Ergonomic Cotton Hat",
	        "product_price": 43.00,
	        "product_material": "Rubber",
	        "product_color": "mint green"
	    },
	    {
	        "id": "16",
	        "product_name": "Small Soft Chair",
	        "product_price": 47.00,
	        "product_material": "Cotton",
	        "product_color": "teal"
	    },
	    {
	        "id": "17",
	        "product_name": "Incredible Metal Car",
	        "product_price":36.00,
	        "product_material": "Fresh",
	        "product_color": "indigo"
	    },
	    {
	        "id": "18",
	        "product_name": "Licensed Plastic Bacon",
	        "product_price":88.00,
	        "product_material": "Steel",
	        "product_color": "yellow"
	    },
	    {
	        "id": "19",
	        "product_name": "Intelligent Cotton Chips",
	        "product_price": 46.00,
	        "product_material": "Soft",
	        "product_color": "azure"
	    },
	    {
	        "id": "20",
	        "product_name": "Handcrafted Wooden Bacon",
	        "product_price": 36.00,
	        "product_material": "Concrete",
	        "product_color": "lime"
	    },
	    {
	        "id": "21",
	        "product_name": "Unbranded Granite Chicken",
	        "product_price": 90.00,
	        "product_material": "Metal",
	        "product_color": "gold"
	    },
	    {
	        "id": "22",
	        "product_name": "Ergonomic Soft Hat",
	        "product_price": 99.00,
	        "product_material": "Rubber",
	        "product_color": "black"
	    },
	    {
	        "id": "23",
	        "product_name": "Intelligent Steel Pizza",
	        "product_price": 95.00,
	        "product_material": "Cotton",
	        "product_color": "azure"
	    },
	    {
	        "id": "24",
	        "product_name": "Tasty Rubber Cheese",
	        "product_price":47.00,
	        "product_material": "Frozen",
	        "product_color": "orchid"
	    },
	    {
	        "id": "25",
	        "product_name": "Licensed Steel Car",
	        "product_price":20.00,
	        "product_material": "Cotton",
	        "product_color": "indigo"
	    }
	]
) 
>db.product.find({}).pretty()
>  db.product.find({product_price:{$gt:400,$lt:800}}).pretty()
{
        "_id" : ObjectId("61b9bed2b485f6dc0026944d"),
        "id" : "1",
        "product_name" : "Intelligent Fresh Chips",
        "product_price" : 655,
        "product_material" : "Concrete",
        "product_color" : "mint green"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc0026944f"),
        "id" : "3",
        "product_name" : "Refined Steel Car",
        "product_price" : 690,
        "product_material" : "Rubber",
        "product_color" : "gold"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc00269450"),
        "id" : "4",
        "product_name" : "Gorgeous Plastic Pants",
        "product_price" : 492,
        "product_material" : "Soft",
        "product_color" : "plum"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc00269452"),
        "id" : "6",
        "product_name" : "Awesome Wooden Towels",
        "product_price" : 474,
        "product_material" : "Plastic",
        "product_color" : "orange"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc00269453"),
        "id" : "7",
        "product_name" : "Practical Soft Shoes",
        "product_price" : 500,
        "product_material" : "Rubber",
        "product_color" : "pink"
}


> db.product.find({product_price:{$ne:{$gt:400,$lt:600}}}).pretty()
{
        "_id" : ObjectId("61b9bed2b485f6dc0026944d"),
        "id" : "1",
        "product_name" : "Intelligent Fresh Chips",
        "product_price" : 655,
        "product_material" : "Concrete",
        "product_color" : "mint green"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc0026944e"),
        "id" : "2",
        "product_name" : "Practical Fresh Sausages",
        "product_price" : 911,
        "product_material" : "Cotton",
        "product_color" : "indigo"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc0026944f"),
        "id" : "3",
        "product_name" : "Refined Steel Car",
        "product_price" : 690,
        "product_material" : "Rubber",
        "product_color" : "gold"
}

{
        "_id" : ObjectId("61b9bed2b485f6dc00269451"),
        "id" : "5",
        "product_name" : "Sleek Cotton Chair",
        "product_price" : 33,
        "product_material" : "Fresh",
        "product_color" : "black"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc00269454"),
        "id" : "8",
        "product_name" : "Incredible Steel Hat",
        "product_price" : 78,
        "product_material" : "Rubber",
        "product_color" : "violet"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc00269455"),
        "id" : "9",
        "product_name" : "Awesome Wooden Ball",
        "product_price" : 28,
        "product_material" : "Soft",
        "product_color" : "azure"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc00269456"),
        "id" : "10",
        "product_name" : "Generic Wooden Pizza",
        "product_price" : 84,
        "product_material" : "Frozen",
        "product_color" : "indigo"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc00269457"),
        "id" : "11",
        "product_name" : "Unbranded Wooden Cheese",
        "product_price" : 26,
        "product_material" : "Soft",
        "product_color" : "black"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc00269458"),
        "id" : "12",
        "product_name" : "Unbranded Plastic Salad",
        "product_price" : 89,
        "product_material" : "Wooden",
        "product_color" : "pink"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc00269459"),
        "id" : "13",
        "product_name" : "Gorgeous Cotton Keyboard",
        "product_price" : 37,
        "product_material" : "Concrete",
        "product_color" : "sky blue"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc0026945a"),
        "id" : "14",
        "product_name" : "Incredible Steel Shirt",
        "product_price" : 54,
        "product_material" : "Metal",
        "product_color" : "white"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc0026945b"),
        "id" : "15",
        "product_name" : "Ergonomic Cotton Hat",
        "product_price" : 43,
        "product_material" : "Rubber",
        "product_color" : "mint green"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc0026945c"),
        "id" : "16",
        "product_name" : "Small Soft Chair",
        "product_price" : 47,
        "product_material" : "Cotton",
        "product_color" : "teal"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc0026945d"),
        "id" : "17",
        "product_name" : "Incredible Metal Car",
        "product_price" : 36,
        "product_material" : "Fresh",
        "product_color" : "indigo"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc0026945e"),
        "id" : "18",
        "product_name" : "Licensed Plastic Bacon",
        "product_price" : 88,
        "product_material" : "Steel",
        "product_color" : "yellow"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc0026945f"),
        "id" : "19",
        "product_name" : "Intelligent Cotton Chips",
        "product_price" : 46,
        "product_material" : "Soft",
        "product_color" : "azure"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc00269460"),
        "id" : "20",
        "product_name" : "Handcrafted Wooden Bacon",
        "product_price" : 36,
        "product_material" : "Concrete",
        "product_color" : "lime"
}
Type "it" for more
> it
{
        "_id" : ObjectId("61b9bed2b485f6dc00269461"),
        "id" : "21",
        "product_name" : "Unbranded Granite Chicken",
        "product_price" : 90,
        "product_material" : "Metal",
        "product_color" : "gold"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc00269462"),
        "id" : "22",
        "product_name" : "Ergonomic Soft Hat",
        "product_price" : 99,
        "product_material" : "Rubber",
        "product_color" : "black"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc00269463"),
        "id" : "23",
        "product_name" : "Intelligent Steel Pizza",
        "product_price" : 95,
        "product_material" : "Cotton",
        "product_color" : "azure"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc00269464"),
        "id" : "24",
        "product_name" : "Tasty Rubber Cheese",
        "product_price" : 47,
        "product_material" : "Frozen",
        "product_color" : "orchid"
}
{
        "_id" : ObjectId("61b9bed2b485f6dc00269465"),
        "id" : "25",
        "product_name" : "Licensed Steel Car",
        "product_price" : 20,
        "product_material" : "Cotton",
        "product_color" : "indigo"
}

> db.product.find({product_price:{$gte:500}}).pretty()
{
        "_id" : ObjectId("61bb0d7aa722f6075db2b36f"),
        "id" : "1",
        "product_name" : "Intelligent Fresh Chips",
        "product_price" : 655,
        "product_material" : "Concrete",
        "product_color" : "mint green"
}
{
        "_id" : ObjectId("61bb0d7aa722f6075db2b370"),
        "id" : "2",
        "product_name" : "Practical Fresh Sausages",
        "product_price" : 911,
        "product_material" : "Cotton",
        "product_color" : "indigo"
}
{
        "_id" : ObjectId("61bb0d7aa722f6075db2b371"),
        "id" : "3",
        "product_name" : "Refined Steel Car",
        "product_price" : 690,
        "product_material" : "Rubber",
        "product_color" : "gold"
}
{
        "_id" : ObjectId("61bb0d7aa722f6075db2b375"),
        "id" : "7",
        "product_name" : "Practical Soft Shoes",
        "product_price" : 500,
        "product_material" : "Rubber",
        "product_color" : "pink"
}

> db.product.find({},{product_name:1,product_material:1})
{ "_id" : ObjectId("61bb0d7aa722f6075db2b36f"), "product_name" : "Intelligent Fresh Chips", "product_material" : "Concrete" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b370"), "product_name" : "Practical Fresh Sausages", "product_material" : "Cotton" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b371"), "product_name" : "Refined Steel Car", "product_material" : "Rubber" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b372"), "product_name" : "Gorgeous Plastic Pants", "product_material" : "Soft" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b373"), "product_name" : "Sleek Cotton Chair", "product_material" : "Fresh" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b374"), "product_name" : "Awesome Wooden Towels", "product_material" : "Plastic" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b375"), "product_name" : "Practical Soft Shoes", "product_material" : "Rubber" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b376"), "product_name" : "Incredible Steel Hat", "product_material" : "Rubber" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b377"), "product_name" : "Awesome Wooden Ball", "product_material" : "Soft" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b378"), "product_name" : "Generic Wooden Pizza", "product_material" : "Frozen" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b379"), "product_name" : "Unbranded Wooden Cheese", "product_material" : "Soft" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b37a"), "product_name" : "Unbranded Plastic Salad", "product_material" : "Wooden" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b37b"), "product_name" : "Gorgeous Cotton Keyboard", "product_material" : "Concrete" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b37c"), "product_name" : "Incredible Steel Shirt", "product_material" : "Metal" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b37d"), "product_name" : "Ergonomic Cotton Hat", "product_material" : "Rubber" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b37e"), "product_name" : "Small Soft Chair", "product_material" : "Cotton" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b37f"), "product_name" : "Incredible Metal Car", "product_material" : "Fresh" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b380"), "product_name" : "Licensed Plastic Bacon", "product_material" : "Steel" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b381"), "product_name" : "Intelligent Cotton Chips", "product_material" : "Soft" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b382"), "product_name" : "Handcrafted Wooden Bacon", "product_material" : "Concrete" }
Type "it" for more
> it
{ "_id" : ObjectId("61bb0d7aa722f6075db2b383"), "product_name" : "Unbranded Granite Chicken", "product_material" : "Metal" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b384"), "product_name" : "Ergonomic Soft Hat", "product_material" : "Rubber" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b385"), "product_name" : "Intelligent Steel Pizza", "product_material" : "Cotton" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b386"), "product_name" : "Tasty Rubber Cheese", "product_material" : "Frozen" }
{ "_id" : ObjectId("61bb0d7aa722f6075db2b387"), "product_name" : "Licensed Steel Car", "product_material" : "Cotton" }

> db.product.find({id:"10"})
{ "_id" : ObjectId("61bb0d7aa722f6075db2b378"), "id" : "10", "product_name" : "Generic Wooden Pizza", "product_price" : 84, "product_material" : "Frozen", "product_color" : "indigo" }

> db.product.find({},{product_name:1,product_material:1,_id:0})
{ "product_name" : "Intelligent Fresh Chips", "product_material" : "Concrete" }
{ "product_name" : "Practical Fresh Sausages", "product_material" : "Cotton" }
{ "product_name" : "Refined Steel Car", "product_material" : "Rubber" }
{ "product_name" : "Gorgeous Plastic Pants", "product_material" : "Soft" }
{ "product_name" : "Sleek Cotton Chair", "product_material" : "Fresh" }
{ "product_name" : "Awesome Wooden Towels", "product_material" : "Plastic" }
{ "product_name" : "Practical Soft Shoes", "product_material" : "Rubber" }
{ "product_name" : "Incredible Steel Hat", "product_material" : "Rubber" }
{ "product_name" : "Awesome Wooden Ball", "product_material" : "Soft" }
{ "product_name" : "Generic Wooden Pizza", "product_material" : "Frozen" }
{ "product_name" : "Unbranded Wooden Cheese", "product_material" : "Soft" }
{ "product_name" : "Unbranded Plastic Salad", "product_material" : "Wooden" }
{ "product_name" : "Gorgeous Cotton Keyboard", "product_material" : "Concrete" }
{ "product_name" : "Incredible Steel Shirt", "product_material" : "Metal" }
{ "product_name" : "Ergonomic Cotton Hat", "product_material" : "Rubber" }
{ "product_name" : "Small Soft Chair", "product_material" : "Cotton" }
{ "product_name" : "Incredible Metal Car", "product_material" : "Fresh" }
{ "product_name" : "Licensed Plastic Bacon", "product_material" : "Steel" }
{ "product_name" : "Intelligent Cotton Chips", "product_material" : "Soft" }
{ "product_name" : "Handcrafted Wooden Bacon", "product_material" : "Concrete" }
Type "it" for more
> it
{ "product_name" : "Unbranded Granite Chicken", "product_material" : "Metal" }
{ "product_name" : "Ergonomic Soft Hat", "product_material" : "Rubber" }
{ "product_name" : "Intelligent Steel Pizza", "product_material" : "Cotton" }
{ "product_name" : "Tasty Rubber Cheese", "product_material" : "Frozen" }
{ "product_name" : "Licensed Steel Car", "product_material" : "Cotton" }


> db.product.find({product_material:"Soft"},{product_name:1,product_material:1,_id:0})
{ "product_name" : "Gorgeous Plastic Pants", "product_material" : "Soft" }
{ "product_name" : "Awesome Wooden Ball", "product_material" : "Soft" }
{ "product_name" : "Unbranded Wooden Cheese", "product_material" : "Soft" }
{ "product_name" : "Intelligent Cotton Chips", "product_material" : "Soft" }

> db.product.find({product_color:"indigo",product_price:492})
>     //as there are no products
> db.produt.remove({$match:product_price})
