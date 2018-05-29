# redux-auto-save-session-after-dispatch

```bash
npm install --save redux-auto-save-session-after-dispatch
```

```javascript
import autoSaveSessionAfterDispatch from '';
const store = createStore(
    reducer,
    initStore,
    applyMiddleware(
        thunk,
        autoSaveSessionAfterDispatch({
            namespace: '__GLOBAL_STATE__',
            log: true,
        })
    )
)
```


Happy Code.