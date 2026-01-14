User Story

As a Product Manager
I need to create and manage products in the catalog
So that customers can view and purchase available products

Details and Assumptions

Each product has a name, price, description, and stock quantity

Products are stored in a backend product catalog service

The catalog is accessible via REST APIs

Acceptance Criteria
Given the product catalog service is running
And a product with name "Laptop" and price 50000 does not exist
When the product manager submits a request to create a product with name "Laptop" and price 50000
Then the system stores the product in the catalog
And the system returns a success response with a unique product ID
