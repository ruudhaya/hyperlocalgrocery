Customers
    id
    email
    password
    firstname
    lastname
    pincode
    longitude   // Could be fetched dynamically - no need to store
    latitude   // Could be fetched dynamically - no need to store

// --- Single Shop 
Item
    id
    name
    mrp
    weight
    weightUnit: grams
    quantity
    discount:
    discountUnit: Percentage
    availableQuantity
    discountedSellingPrice

// --- Multiple Shop - Begins
Item
    id
    name
    mrp
    weight
    unit: grams
    quantity

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

// -- Multiple Shop -- Ends

Order
    id
    createdOn
    userid
    status

ItemOrder
    orderid
    itemid
    count
