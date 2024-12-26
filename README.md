# Exercise

## Create a new project named Lab5_Ex1 with the following requirements

1. Create endpoints to view, add, delete, and update User, Product, and ShoppingCart objects in two ways:

    1.1 Using standard query writing.

        - Create a database that includes User, Product, and ShoppingCart with corresponding data types:

        - **User**: Contains the following information: UserId, Full Name, Address, Registration Date.

        - **Product**: Contains: ProductId, Product Name, Price, Manufacturing Date.

        - **ShoppingCart**: Identify the necessary attributes to store user and shopping cart information.

    1.2 Using ORM (Object-Relational Mapping).

        - Define the required objects and appropriate data types for the models.

        - Return the results in API format as follows:

        ```json
        {
            "action": "",
            "status": "",
            "User/Product/ShoppingCart": {}
        }
        ```

        - For actions such as adding, deleting, and updating: display information about the object just interacted with.

        - For actions such as viewing: display information about all objects.

2. Create an endpoint that accepts a user's email and sends an email with any content to
the provided email address.

3. Create an endpoint capable of receiving and storing images, and another endpoint to
display the stored images.

4. Create an endpoint that, when called, will fetch all information from the URL
[https://jsonplaceholder.typicode.com/users](https://jsonplaceholder.typicode.com/users), create appropriate classes to map the objects
from the URL to the classes, and save them to the database.
