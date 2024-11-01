# Customer
> A person or organization who can:
>   * Search
>   * Buy Product


# Actions
>   * Register
>   * Edit information
>   * Login
>   * Search with/without login
>   * Buy product (need to login)
>   * Chat with Support
>   * Track Order

# Customer information
>   * customer id
>   * name
>   * mobile
>   * email
>   * address
>   * type:
>     * real
>     * legal


# Register customer scenarios
- Scenario1:
    1. ask username
    2. ask password
    3. navigate to register page
- Scenario2:
    1. get customer mobile number
    2. sent otp to customer mobile number
    3. customer sholud enter otp code
    4. validate code and navigate to register page
- Scenario3:
    1. user can register using google account

# Edit infromation scenarios
Edit should be done after login
customer can change these informations
* mobile
* email
* address

# Login Scenarios
- Scenatio1:
    1. enter mobile number
    2. send otp to user mobile number
    3. user should enter otp
    4. validate otp and navigate to main page
- Scenario2: 
    1. enter username and password
    2. validate username and password
    3. navigate to main page
- Scenario3:
    1. navigate to main page using google account

# Search Scenarios
customer can search products with/without login.
please check [search-management](search-management.md) for more information

# Buy Scenarios
customer can buy a product only after login.
please check [financial-management](financial-management.md) for more information

# Chat Scenatios
customer can chat with support only after login
please check [support-management](support-management.md) for more information

# Track order Scenarios
customer can track order status after login and using endToEndId. please check [support-management](support-management.md) for more information