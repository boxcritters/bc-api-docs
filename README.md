# bc-api-docs
we document things can could be used to create mods

##helper function
```js
function getKeys(obj) {
  return Object.keys(obj)
  .map(k=>{
    if(this[k]){
      return k + ":" + obj[k].constructor.name||typeof obj[k]
    }else{
      return k;
    }
  }).toString();
}
```
