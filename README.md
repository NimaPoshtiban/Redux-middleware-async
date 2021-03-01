# Redux-middleware-async
pass promises to the action with no worries 
## How does it works?
So simple just apply that middleware in your project by importing {applyMiddleware} from redux

## Instalation
```
npm install asyncmiddlewareredux
```
then to enable Redux-middleware-async ,use ```applyMiddleware()```:
```
import { createStore, applyMiddleware } from 'redux';
import AsyncRedux from 'asyncmiddlewareredux';
import rootReducer from './reducers/index';

// Note: this API requires redux@>=3.1.0
const store = createStore(rootReducer, applyMiddleware(AsyncRedux));
```
