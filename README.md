
# E-Shop

It is full Responsive E-Commerce web-app for shopping .
It is based on Fake API.


## API Reference

#### Get all items

```http
  https://fakestoreapi.com/products
```



#### Get item

```http
  https://fakestoreapi.com/products/${id}
```



## Screenshots

### Products List
![Product List](https://user-images.githubusercontent.com/91049345/140634953-2e03a981-8ee1-4ca0-a14d-6c5dcfe03fdf.png)

### Product Details
![Product Details](https://user-images.githubusercontent.com/91049345/140634988-1c44bae5-c93f-421e-a21a-2814d7145c86.png)
## Installation

Install E-Shop with npm

```bash
  npm install
  
```


## Tech Stacks

### React Js

    React helps you create your web applications in a more maintainable way.
    React enables developer to reuse components. 
    I have used useEffect react hook in this application.By using this Hook, we tell React that our component needs to do something after render. React will remember the function we passed , and call it later after performing the DOM updates. 

### Redux

    In this web application redux library is used to store the states of a component.
    There are various components of redux are used in this web application like store , reducers, combine reducers, actions.
    The selector is approximately equivalent to the mapStateToProps argument to connect conceptually.
    useSelector() will also subscribe to the Redux store, and run your selector whenever an action is dispatched.


### Axios

    Axios is a library used in this project to make request to API ,return data form API , then do the things from that data.
    It has good defaults to work with JSON data. Unlike alternatives such as the Fetch API, you often don't need to set your headers. Or perform tedious tasks like converting your request body to a JSON string.
    Axios has function names that match any HTTP methods. To perform a GET request, you use the .get() method.

### React-Router
    I have used React-Router for Routing in this web application which  enables the navigation among views of various components in a React Application, allows changing the browser URL, and keeps the UI in sync with the URL.
    I have used useParams which is the hooks of React-router-dom.
    useParams() returns an object that consists of all the parameters in URL. 
#### Components used from react-router-dom
    1. BrowserRouter :- BrowserRouter is a router implementation that uses the HTML5 history API to keep your UI in sync with the URL. 
                        It is the parent component that is used to store all of the other components.

    2. Route :-         Route is the conditionally shown component that renders some UI when its path matches the current URL.  

    3. Switch :-         Switch component is used to render only the first route that matches the location rather than rendering all matching routes.

    4. Link :-           Link component is used to create links to different routes and implement navigation around the application. It works like HTML anchor tag.

#### Components used from react-redux 

    1. useDispatch :-   The useDispatch hook returns a reference to our dispatch functions from the Redux store. 
                        We can use it to directly access our dispatch actions without having to use mapDispatchToProps in our component.

    2. useSelector :-   The useSelector() is approximately equivalent to the mapStateToProps argument to connect conceptually.
                        The selector will be run whenever the function component renders
                        
## Author

- [@rushikesh-mahamuni](https://github.com/rushikesh-mahamuni)
