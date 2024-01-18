# Emmet 
1) Emmet is generate standart scalatane of our code

# What is React 
React is Javascript Library , Using that we have create declarative Reusable Ui components

# Library And Framework
Library is Some piece or chunk of code , so it require less time for load
Framework is full fledged thing that contain all the thing for creating an app , so it require more time for load

# Ways of adding content inside HTMl 
1) Using Html
2) Using Javascript
3) Using React Core

# React.createElement() , ReactDom.createRoot()
1) Using React.createElement("tag" , {it places give attribute to our tag called Props} , "content") --> using Core-React Creating React-Element
2) ReactDOM.createRoot() --> creating and Pointing to id --> root in index.html file 

At The End of the Day ReactElement is javascript Object and when you render the reactElement convert this React-Object to the html and replace the whole root content with this ReactComponent

# Ways To Add React In Project
1) Using CDN --> CDN is Not A Good Way to add React Inside --> Because As version chnages it not automatically change the CDN version so it work statically
2) Using NPM

# What is CDN (Content-Delivery Network) for many distrubuted network 
1) It Deliver A Content for the perticular Request . CDN Network is WorldWide distrubuted so it check the request and send request to nearBy Server for proceesing and Sending Respond to that Request.
2) It Also Stored The caching so it check this request Respond chache already exit so it send respond from the cache layer without forwarding request to the server , so it send faster respond.

# React
React Contain the core thing for structuring react project

# ReactDOM
ReactDOM its Like a bridge between react and browser Dom , all ,anipulation of virtualDom , Normal Dom it handle by ReactDOM

# What is react.development.js and react.production.js
so when we used react at the time of building or developing our app we used react.developement.js but at the time of production we have use react.production.js

# What is CORS (Cross-Origin-Resource-Sharing)
if you want something or send to the same origin browser allow to do this
but but but when you send or access thing from the different origin browser not allowed to access directly
so,
1) preflight Request has been send by domain A , this is not actual request this request contain lot of header but two more imoportant header is 
Access-control-Allow-Origin = domain A
Access-control-allow-method = Get



if domain B , accept the request so the demain B tic this header it allow the request send By Domain A So it sets,
Access-control-Allow-Origin = domain A for specific domain or * for all domain
Access-control-Allow-Origin = Get , Post or * for all method

if any one this request false from domain B it throught the error

after getting response in preflight request according to that it will throght error or send actual request for accessing all user detail 

if domain B not allow to this Origin Browser throught the Cors error
if domain B allow the access then actual request made and get all user detail.

# What is Async and Defer