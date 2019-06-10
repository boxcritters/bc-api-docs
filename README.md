# bc-api-docs
we document things can could be used to create mods

##helper function
```js
function getKeys(obj) {
  return Object.keys(obj)
  .map(k=>{
    if(this[k]){
      return k + ":<code>" + (obj[k].constructor.name||typeof obj[k]) + "</code>";
    }else{
      return k;
    }
  }).toString();
}
```
