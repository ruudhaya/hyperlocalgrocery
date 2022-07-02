Customers
    id
    email
    password
    firstname
    lastname
    pincode
    longitude
    latitude

Item
    id
    name
    mrp
    weight
    unit: grams
    quanitity

shop_item
    shopid
    itemid
    discount:
    discountUnit: Percentage
    availableQuantity
    discountedSellingPrice

Shop
    id
    name
    area
    pincode
    latitude
    longitude

Order
    id
    createdOn
    userid
    status

ItemOrder
    orderid
    itemid
    count
