# advanced-python


-- update and delete 

-- for single column
update product set price =1000 where product_id = 5;

-- for multiple column 
update product set product_name = 'New Product' ,Categories="bedroom",price=2999
where product_id = 2;

-- for delete 
delete from product where product_id = 5;

-- fro multiple 
delete from product where product_id in(10,15,18);

-- updated all product price by less then 5000 which price is more than 5000 
update product set price = 4999 where price >= 5000;

-- checked for price 4999
select * from product where price = 4999;
-- count total records for price 4999
select count(*) from product where price = 4999;

select * from product;

-- Delete all product records which price is more than 5000 
delete from product where price >=5000;
