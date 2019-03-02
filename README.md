## Simple Redux application for Redux concept

Run the aaplication using command:

```bash
npm start
```

## How to use:

Open the console of browser using F12 key.

- Now, to check current state type:

```bash
store.getState();
```
--------------

- If you want to change the state then call 'dispatch' method like:

```bash
store.dispatch(addArticle({id:1, title:'Redux Application'}));
```
-------------

- To listen the state change use the command:

```bash
store.subscribe(() => console.log('State Changed!'));
```
