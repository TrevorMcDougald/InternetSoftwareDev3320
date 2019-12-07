# Shopping Cart Project
This was originally a project for CS 3320: Internet Software Development
It is a fork from
[This](https://github.com/georgeotj/InternetSoftwareDev3320) repository.

## Project Structure:      
        .
        ├── docs 
        │   ├── page_images 
        │   │   └──  // .png files of our project's pages for turning in 
        │   │ ...
        │   └── // Documentation files
        │
        ├── node_modules
        │   │   // If we use NodeJS for the server side instead of XAMPP, This folder will contain all         
        │   │      the NodeJS dependencies required. When you type 'npm install' into the Webstorm   
        │   │      terminal on WebStorm, the node dependencies will get installed here. Don't commit it ti  
        │   └──    The repo because they're generally heavy in terms of space.     
        │   
        ├── www   ( might rename? just one commonly used that I found )
        │   │
        │   ├── Assets
        │   │   │
        │   │   ├── Audio
        │   │   │   └ // app audio ( .mp4 files )
        │   │   ├── Fonts     
        │   │   │   └ // app fonts ( .ttf/ .woff files )
        │   │   └── Images
        │   │       └ // images used in app ( **reduced** .jpg/ .png files )
        │   │   
        │   ├── Data  
        │   │   └ // app information (.JSON Files) 
        │   │
        │   ├── JavaScript ( Might separate this directory into more sub directories ) 
        │   │   │ 
        │   │   └ // Scripts ( .js files )
        │   │   
        │   ├── Libs  ( A lot of examples show JS files in here )
        │   │   │
        │   │   └ // 3rd party Libraries and general purpose files
        │   │
        │   ├── StyleSheets ( .css/ .scss files )
        │   │   │   
        │   │   ├── Base  
        │   │   │   └ // .css files for resets, variables, mixin, and utility classes      
        │   │   ├── Layout
        │   │   │   └ // All CSS files that handle layout, such as container and grid system
        │   │   ├── Components  
        │   │   │   └ // .css for anything reusable, such as buttons, navbars, etc..  
        │   │   │        
        │   │   └── main.css        ( primary .css file, should import the CSS files above )
        │   │     
        │   └── Views       ( .html files )
        │       │
        │       ├── Pages       
        │       │   ├── checkout.html               ( checkout page )
        │       │   ├── shippinginfo.html           ( shipping information page )
        │       │   ├── userinfo.html               ( user information page )
        │       │   ├── shoppingcart.html           ( shopping cart page )
        │       │   ├── ...
        │       │   └── // Layout of website pages
        │       │   
        │       └── Templates 
        │           │
        │           └ // possible template layouts we find and use 
        │
        ├── src
        │   │
        │   └── // if we need directory for back-end files? ( will look into way later )
        │
        ├── .gitignore
        │
        ├── _config.yml  // Jekyll use 
        │
        ├── index.html   // website entry point                
        │
        ├── LICENSE 
        │
        ├── robots.txt    // talks to search engines and crawlers
        │
        └── README.md
         
## Page Images (9-13-2019)
#### Top of Home Page:
------
![User Information](https://github.com/georgeotj/InternetSoftwareDev3320/blob/master/docs/page_images/main-page-top.PNG) 
#### Bottom of Home Page:
------
![User Information](https://github.com/georgeotj/InternetSoftwareDev3320/blob/master/docs/page_images/main-page-bottom.PNG) 

#### Scroll User Information Page:
![UserInformation](https://github.com/georgeotj/InternetSoftwareDev3320/blob/master/docs/page_images/user_information_page.png)


#### Top of User Information Page:
------
![User Information](https://github.com/georgeotj/InternetSoftwareDev3320/blob/master/docs/page_images/user-information-top.PNG) 
#### Bottom of User Information Page:
------
![User Information](https://github.com/georgeotj/InternetSoftwareDev3320/blob/master/docs/page_images/user-information-bottom.PNG) 


#### Top of Shipping Information Page:
------
![Shipping Information](https://github.com/georgeotj/InternetSoftwareDev3320/blob/master/docs/page_images/shipping-information-top.PNG) 
#### Bottom of Shipping Information Page:
------
![Shipping Information](https://github.com/georgeotj/InternetSoftwareDev3320/blob/master/docs/page_images/shipping-information-bottom.PNG) 

#### Top of Shopping Cart Page:
------
![Shopping Cart](https://github.com/georgeotj/InternetSoftwareDev3320/blob/master/docs/page_images/shopping-cart-top.PNG) 

#### Bottom of Shopping Cart Page:
------
![Shopping Cart](https://github.com/georgeotj/InternetSoftwareDev3320/blob/master/docs/page_images/shopping-cart-bottom.PNG) 


#### Top of Checkout Page:
------
![Checkout](https://github.com/georgeotj/InternetSoftwareDev3320/blob/master/docs/page_images/checkout-top.PNG) 
#### Bottom of Checkout Page:
------
![Checkout](https://github.com/georgeotj/InternetSoftwareDev3320/blob/master/docs/page_images/checkout-bottom.PNG) 


