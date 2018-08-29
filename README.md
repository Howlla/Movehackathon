
# ClearCargo

### LIVE links : BLOCKCHAIN https://pure-shelf-59122.herokuapp.com/
### MACHINE LEARNING PLATFORM https://cargoclear.herokuapp.com/

> A supply chain management platform with transparency & Efficiency in mind.

ClearCargo has
1) A decentralized application based on the Ethereum blockchain aiming to
let consumers see the data behind the products they ship & lets the authorities make
better decisions. It currently consumers to place orders on the app and admins can login
to access the admin dashboard that uses predictive analysis to tell the number of shipments
on any particular day.

2) A Machine Learning Implemented Platform which predicts the TRUCKLOAD capacity on each oday by
studying past data. This way the plant can predict the amount of truckload on the upcoming days.
This algorithm takes into account the weekdays, weekends, holidays for prediction.

Keep in mind that **this is a proof of concept**. It is *not* production ready by any means.

BlockchainSolution made using the Truffle toolkit, React.js, Redux, and Webpack.

## Live Demo

## BLOCKCHAIN
# REQUIRES METAMASK ON RINKEBY NETWORK
>https://pure-shelf-59122.herokuapp.com/

## Installing / Getting started

0. Clone the repo:

    ```shell
    git clone https://github.com/Howlla/Movehackathon.git
    cd Movehackathon
    cd BlockchainSolution
    ```
    
1. Install the Truffle toolkit globally and install project dependencies:

    ```shell
    npm install -g truffle && npm install
    ```

2. In a new shell, start the Truffle development console:

    ```shell
    truffle develop
    ```

3. In the Truffle console, compile and deploy the smart contracts:

    This will effectively reset your local blockchain, meaning that all existing transactions will be deleted.

    ```shell
    migrate --reset
    ```

4. Back in a regular shell, start the Webpack server:

    ```shell
    npm run start
    ```

    A browser window should then open automatically at `http://localhost:3000` (or whatever port you set manually). If you see the Trace home page, you're ready to go. Otherwise, if the page is stuck on "Waiting for Web3...", proceed to steps 5 and 6. 

5.  Install the [MetaMask browser extension](https://metamask.io/). Once installed, click on the MetaMask icon, then use the "Import Account" feature to create an account from a private key. Copy the first private key from the first few lines of output of `truffle develop` and paste it into the "Private Key" field in Metamask.

6.  Connect to your private network. Click the network chooser (it will likely say "Main Ethereum Network" at the top), and choose "Custom RPC". In there, enter the URL that matches the configuration in the `truffle.js` file (which should be `http://localhost:9545` by default), then click "Save".

7. Refresh the page in your browser, and you should be good to go!


## Features

* Add a product to the platform
* Create unique serialized QR code for each product
* Search for a particular product
* Access Admin Panel for predictive analysis
* Add certifications to products (e.g. "manifest", "bill of lading" etc.)
* Browse a product's version history
* See the product's previous positions on a map
* Combine products into one (STILL TESTING)
* Split a product into many (STILL TESTING)

## MACHINE LEARNING
Visit cargoclear.herokuapp.com for the live working model


TO RUN locally:


 USE pip freeze -r requirements.txt to install al dependencies
 USE python manage.py to runserver locally

