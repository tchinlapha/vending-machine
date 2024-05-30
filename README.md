# Vending Machine

A simple vending machine application built with Pure PHP.
This is an demo of a vending machine project. It simulates the behavior of a real vending machine, allowing users to select products and make purchases.

## Features
- Display available products
- Accept virtual coins
- Dispense selected products
- Provide change

## How to Use
1. Visit the [online demo](http://www.vending-machine.great-site.net) to see the vending machine in action.
2. Select a product by clicking on it.
3. Insert virtual coins by clicking on the coin icons.
4. Click the "Purchase" button to buy the selected product.
5. The machine will dispense the product and provide change if necessary.

## Manual Installation
### Prerequisites

- [XAMPP](https://www.apachefriends.org/index.html) or any PHP web server.

### Steps

1. Clone the repository:
   ````sh
   git clone https://github.com/yourusername/vending-machine.git
   ````

2. If using XAMPP, move the project to the htdocs directory. For example
   ````sh
   mv vending-machine /path/to/xampp/htdocs
   ````

3. Start the Apache server in XAMPP.
4. Open your web browser and navigate to:
   ````sh
   http://localhost/vending-machine
    ````


Alternatively, if you're using a different PHP web server
1. Navigate to the project directory:
  ````sh
   cd vending-machine
   ````
2. You can start the PHP built-in server:
  ````sh
   php -S localhost:8000
   ````
3. Then open your web browser and navigate to:
  ````sh
  http://localhost/vending-machine
   ````

## Architecture Diagram
![Architecture](https://github.com/tchinlapha/vending-machine/blob/main/assets/img/architecture.png?raw=true)

