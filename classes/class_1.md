# **Menu (class)**

## _**Attributes**_

### dish_name (string)
### meal_type (string)
### cook_time (integer)
### ingredients_list (array)
### nutrition_info (hash)
### price (float)
### vegan_status (boolean)
### added_to_menu (datetime)

## _**Methods**_

### get_ingredients_nutrition_vegan (gets ingredients_list + nutrition_info + vegan_status)
### take_order (assign order_number = {dish_name: price})
### est_wait (gets all dish_name from take_order & sums cook_time for each item)
### check_out (gets take_order{Hash} & sums all the prices + tax & sends order number to open_orders array)
### complete_order (closes check_out + adds gratuity)
### refresh_menu (gets all menu items that have been on the menu for longer than 1 yr using added_to_menu)
