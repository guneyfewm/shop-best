# ShopBest An Ecommerce Glasses Shop
## Made with react, redux toolkit, bootstrap and react router dom

# Preview
![shopbest](https://user-images.githubusercontent.com/116850173/200358098-f10ee55f-fe7c-423e-a955-3c60bd87e062.gif)

# Home Page
![image](https://user-images.githubusercontent.com/116850173/200357588-742fd54d-8819-4b07-ab78-f9040d9ab356.png)
You can add items to cart or change the currentSrc property of our appslice by clicking on the slider buttons.
Every item you add into your cart is stored in local storage.
By clicking on the add to cart button you dispatch a reducer function and update the state of the application.
By clicking on the slider buttons you dispatch a new reducer and change the currentSrc property to either currentSrc1, currentSrc2 or currentSrc3
Each item has their own id's that way we can make them stack into each other in our cart state (which is displayed in the cart page).
# Catalog
![image](https://user-images.githubusercontent.com/116850173/200359286-c525e2ef-bec1-4af7-b289-7ff31460545d.png)
By clicking the buttons above the products section you change what gets rendered on the screen.
You can select to render either best selling, new or sunglasses state of our application.
In the product section we map our state and put it in a div (which is the products container. The yellow background one)
