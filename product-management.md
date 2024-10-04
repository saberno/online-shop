# Description
A product can have these properties:
- product id
- category
- price
- seller information
- capacity
- details
    - description
    - images
    - videos
- comments
    - good
    - bad
- rate or score

# Operations
- Add
- Update
- Delete

# Add Scenarios
- Scenario1: these properties can be added:
    - category(M)
    - price(M)
    - seller information(M)
    - capacity(M)
    - details(M)
        - description(M)
        - images(O)
        - videos(O)

# Update Scenarios
- Scenario1: these properties can be updated
    - category
    - price
    - capacity
    - details
        - description
        - images
        - videos

# Delete Scenarios
- Scenario1:
    - A produce can be deleted by id
- Scenario2:
    - Products can be deleted by category
- Scenario3:
    - A product details can be deleted (descrioption should be remained)