#React Shopping Cart

1)Tools and Technologies
-----------------------
Javascript---MDN Web Docs --documentation--PL used
React--A Javascript library for building user interfaces---react.org
Redux--A predictable State container for JS Apps--redux.js.org
node--12.16.3 LTS (download)--nodejs.org--backend end point technology for creating apis
mongodb--mongodb.com/download-center/community--->download it-->install it-->command prompt enter mongod
development tools--->visual studio code---code.visualstudio.com--download and intall
for visual studio code install some extensions
1)Javascript (ES6) Code Snippets--install all 5
2)ES7 React Extension
3)ESLint Extension
4)Node Debug
5)CSS Peek
Google chrome--install google chrome--google.com/chrome--download and install it
git--git-scm.com--download and install--git is a version control tool
github.com--create an account
postman--postman.com
heroku--(deployment)--to publish our work--heroku.com-signup --fill all your info--create an account
mongodb.com/cloud/atlas--give your info--sign up and sign in--lavanya12gani@gmail.com--lavanyaharish216


2)create-react-app
----------------
command prompt
project folder path>npx create-react-app react-shopping-cart21
                   >cd react-shopping-cart21
                   >code .
		   >npm install react-scripts@2.1.8
                   >npm start

3)Project Workflow
------------------
https://docs.google.com/spreadsheets/u/0/
click on -->blank

control+enter command
github
commit
master branch
other branch
synchronize the 2 master n other brancges

4)Products List Components
----------------------------

git remote add origin https://github.com/lavanya2121/react-shopping-cart.git--must give this in another command prmpt to synchronise your code with github

5)filter and sort
-----------------

6)Add items to cart
-------------------
add items to cart
remove items to cart
show total
show the number of items

-------------------
1)create a branch cart-component
2)product.js
3)Handle "Add to Cart" to this.props.addToCart(product)
4)App.js
5)Add cart items to state as []
6)Craete addToCart(product)
7)Slice,check product existence, add to cartitems
8)Cart.js
9)Define cartItems, order from this.props
10)check cartItems.length and show message
11)List cart items {cartItems.length>0 && }
12)index.css
13)style cart,cart header,cart-items(img,li),
14)use localStorage on app constructor to load cart items(JSON.Parse)
15)use localStorage on addCart to save cartItems(JSON.stringify)


7)Checkout Form
----------------
1)create a branch checkout-form
2)Cart.js
3)Make cartItems persistent
4)Use LocalStorage on App constructor to load cart items(JSON.parse)
5)use LocalStorage on addToCart to save cart Items (JSON.stringify)
6)handle click on Process
7)update showCheckout state to true on click
8)conditional rendering checkout form
9)Get Email,name ,address required input
10)Define HandleInput Function
11)Add checkout Button
12)Handle onSubmit form event by this.createOrder
13)Create order object and pass to parent to handle it
14)Publish changes
