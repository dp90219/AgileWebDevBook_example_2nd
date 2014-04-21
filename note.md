#rails new depot -d mysql

## rails g scaffold product title:string description:text image_url:string price:decimal

- <body class='<%= controller.controller_name %>'> 
- <tr class="<%= cycle('list_line_odd', 'list_line_even') %>">

### test

- controllers
- models
- fixtures

## rails g controller store index

- numebr_to_currency
- test: assert_select
- <%= truncate(strip_tags(product.description), length: 80) %> 

## rails g scaffold cart

- concern

## rails g scaffold LineItem product:references cart:belongs_to

## rails g migration add_quantity_to_line_items quantity:integer

## rails g migration combine_items_in_cart

- @cart.line_items.build  vs.  LineItems.create

## rails g scaffold order name:string address:text email:string pay_type:string
rails g migration add_order_to_line_item order:references

## rails g scaffold user name:string password:digest

## rails g controller sessions new create destroy

## rails g controller admin index
