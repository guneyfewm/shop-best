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
![image](https://user-images.githubusercontent.com/116850173/200363346-ca1b7a80-68b6-4c80-8b4d-66993f248414.png)

By clicking the buttons above the products section you change what gets rendered on the screen.
You can select to render either best selling, new or sunglasses state of our application.
In the product section we map our state and put it in a div (which is the products container. The yellow background one)
# Cart
![image](https://user-images.githubusercontent.com/116850173/200360135-cfbcbead-6aa3-46a4-b441-bd0a8ef8cff0.png)
In the cart page you can see that our total is calculated based on the amount property * price property of our objects in our cart state.
You can add and delete items from the cart, by adding the same item more than one time you stack it in a slot.
The image that gets rendered here is the "src" property of our object (product) and not "currentSrc" or "src2", "src3"

# Product Slider
![image](https://user-images.githubusercontent.com/116850173/200361261-e80a2736-91e3-42c6-ade5-476d180b4a2f.png)
![image](https://user-images.githubusercontent.com/116850173/200361468-e8567312-a15c-4b4c-ad18-5a6acfd16612.png)
![image](https://user-images.githubusercontent.com/116850173/200361597-3e225030-ad04-4569-b429-d5e7832b5818.png)

You can change the currentSrc property of a product object by dispatching a slider reducer (by clicking the buttons that are highlighted)
