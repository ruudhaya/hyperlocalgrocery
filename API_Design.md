User Flow mapped through APIs

User Authentication <Username, Password>
    - Auth Service

Upon successful login
    - Get All items (Availability is between different stores, could be done next)
        - Filter the items (Could be done without API, locally on the browser)
    - Add items to cart
        Only one cart per user, needs persistence between login
    - Create order

