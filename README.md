# Redux-Practice
## Purpose
A simple blog project to acquire the core functionalities of Redux.js  

Two folders in the Redux-Practice directory are the same project but with different tools to achieve Frontend and Backend communication and upate Redux state.  

In the "Blog Project With Axios and Redux Thunk" folder, the combination of Axios library and Redux Thunk middleware are used to fetch/send data from/to APIs, and JSONPlaceholder is adopted as fake API.  
  
In the "Blog Project With RTK Query" folder, Redux Toolkit Query is used as data fetching and caching tool and to replace Axios and Redux Thunk, providing a more abstract but simpler option to achieve the same functionalities.

## Initiate Project  
### Blog Project With Axios and Redux Thunk
#### Enter the project directory
```
cd BlogProjectWithAxiosAndReduxThunk
```
#### Install dependency
```
npm install
```
#### Initiate project
```
npm start
```
### Blog Project with RTK Query
#### Enter the project directory
```
cd BlogProjectWithRTKQuery
```
#### Install dependency
```
npm install
```
#### initiate JSON Server
```
json-server --watch data/db.json --port 3500
```
#### Initiate project
open a new terminal and enter the following command
```
npm start
```