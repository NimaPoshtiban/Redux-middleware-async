# Redux-middleware-async
pass promises to the action with no worries 
## How does it works?
So simple just apply that middleware in your project by importing {applyMiddleware} from redux

## Instalation
```
npm install asyncmiddlewareredux
```
then to enable Redux-middleware-async ,use <a>```applyMiddleware()```</a>:
```
import { createStore, applyMiddleware } from 'redux';
import AsyncRedux from 'asyncmiddlewareredux';
import rootReducer from './reducers/index';


const store = createStore(rootReducer, applyMiddleware(AsyncRedux));
```
![NimaPoshtiban's GitHub stats](https://github-readme-stats.vercel.app/api?username=nimaposhtiban&show_icons=true&theme=synthwave)
