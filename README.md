# PRISHA FOODS Food Ordering Bot

Welcome to the PRISHA FOODS Food Ordering Bot repository! This bot is designed to facilitate food ordering via Telegram, allowing users to place orders and admins to manage and track these orders effectively.

For Source Code Msg Me - 
[![INSTAGRAM](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/piyush.mujmule) ![Kaggle Badge](https://img.shields.io/badge/Kaggle-yellow?logo=kaggle&logoColor=fff&style=for-the-badge)
---
## Features

### User Features
- **Start Command**: `/start` - Initializes the bot and displays the food menu.
- **Place Order**: Choose food items and specify quantities.
- **Provide Address**: Enter delivery address.
- **Check Order Status**: `/status [Order ID]` - Get the current status of an order.

### Admin Features
- **Confirm Order**: `/confirm [Order ID]` - Confirm an order.
- **Decline Order**: `/decline [Order ID]` - Decline an order.
- **Update Status**:
  - **Cooking**: `/cooking [Order ID]` - Mark order as "Cooking."
  - **Out for Delivery**: `/out_for_delivery [Order ID]` - Mark order as "Out for Delivery."
  - **Delivered**: `/delivered [Order ID]` - Mark order as "Delivered."
- **Check Order Status**: `/status [Order ID]` - Retrieve the status of an order.

## Usage

### User Commands

- **/start**: Start the interaction and view the menu.
- **Order Items**: Choose items and specify quantities.
- **Provide Address**: Enter the delivery address.
- **/status [Order ID]**: Check the order status.

### Admin Commands

- **/confirm [Order ID]**: Confirm an order.
- **/decline [Order ID]**: Decline an order.
- **/cooking [Order ID]**: Update status to "Cooking."
- **/out_for_delivery [Order ID]**: Update status to "Out for Delivery."
- **/delivered [Order ID]**: Update status to "Delivered."
- **/status [Order ID]**: Retrieve order status.

## Database Schema

- **Table: `orders`**
  - `id`: INTEGER PRIMARY KEY AUTOINCREMENT
  - `user_id`: INTEGER
  - `items`: TEXT
  - `address`: TEXT
  - `status`: TEXT

## Future Enhancements

- **User Authentication**: Implement authentication for a personalized experience.
- **Order History**: Add functionality for users to view their order history.
- **Payment Integration**: Integrate payment gateways for transactions.
- **Feedback System**: Include a mechanism for users to provide feedback on orders.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, please contact:


[![INSTAGRAM](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/piyush.mujmule) ![Kaggle Badge](https://img.shields.io/badge/Kaggle-yellow?logo=kaggle&logoColor=fff&style=for-the-badge)
---
