# Sales & Inventory Management Program

Fundamental of Software Development project with the following requirements:
The Stock Management program must store and manage products listed for sale. It must store each product with at least five attributes such as code, name, price, quantity, description, size and color of a product depending on your chosen product.
The program must store two attributes: code and quantity of each product along with other attributes. As code is the unique identifier, the program ensures that each product is stored with unique code value. The program will only accept quantity of a new product between 10 and 50 to make sure there are enough quantities available of a product for sale and also they are not overstock as well.

# The program must include the following functions
- add_product
- check_product
- search_product
- update_product
- buy_product


# Initial Project State
- This project intially uses multiple arrays that stores product code, type, price, materials, and quantity as minimum requirement for this project.
- Methods were originally implemented without any parameters.

# Improvement process
- I played around improving the functionality of the methods by implementing parameters
- I also transitioned from using multiple arrays to dictionaries, aiming to enhance performance.
- After successfully implementing functionality with dictionaries, I decided to enhance it further by integrating SQLite, ensuring that data is persisted.

# Future plan
- My upcoming plan involves integrating a graphical user interface (GUI) into the application.