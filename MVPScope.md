Given requirement has a minimum requirement scope

In MVP, we are scoping out the numerous attributes which could be part of the entity

In further sprints, we could add them iteratively

SpringBoot ()
    API
DB

React 8
    - bootstrap

## User 
Priority 1
    - view all items
    - Search items - will do filtering on existing things
    - Add items to cart
    - Create order
    - login/signup

Priority 2
    - Make payment integration
    - Edit / update items in cart
    
Not in Scope for first delivery plan
    - Pagination for viewing items
    - Out of stock scenario
    - Store selection / letting user know from which store, it is being delivered

## Data maintainer
Priority 1
    - Import Items to db
    - Import Stores to db

Not in scope
    - Shop login

Not all stores will have all items

Shop
    List<Items>

Order 
    List<ItemOrder>

ItemOrder
    item
    quantity


Not in scope
    - Items could be available with different MRP


Serve orders
    - Collect Order
    - For each item, find the nearby store, group by shop
    - Create shop order 
    


