# Bakery-app Documentation

## General APIs

### Register (POST)
- **URL**: /register
- **Payload**: username, password, firstName, lastName, mail
- **Response**: Registration Successful

### Login (POST)
- **URL**: /login
- **Payload**: username, password
- **Response**: Login Successful

### Logout (GET)
- **URL**: /logout

## Admin APIs

### getIngredients (GET)
- **URL**: /inventory/getIngredients
- **Response**: List of ingredients

### getBakeryItems (GET)
- **URL**: /inventory/getBakeryItems
- **Response**: List of bakery items

### addIngredients (POST)
- **URL**: /inventory/addIngredients
- **Payload**: ingredients
- **Response**: Success message

### addBakeryItem (POST)
- **URL**: /inventory/addBakeryItem
- **Payload**: item details
- **Response**: Success message

### updateDiscount (PATCH)
- **URL**: /inventory/updateDiscount
- **Payload**: item name, discount
- **Response**: Success message

### discardIngredients (DELETE)
- **URL**: /inventory/discardIngredients
- **Payload**: ingredient names
- **Response**: Success message

## Customer APIs

### checkItems (GET)
- **URL**: /checkItems
- **Response**: List of available items

### TopSellingItems (GET)
- **URL**: /getTopSellingItems
- **Response**: List of top-selling items

### order (POST)
- **URL**: /order
- **Payload**: order details
- **Response**: Success message

### getOrderHistory (GET)
- **URL**: /getOrderHistory
- **Response**: Order history