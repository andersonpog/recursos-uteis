## Reativo

```javascript
const counter = reactive({
  count: 0
})
const message = ref('Hello World!')
console.log(counter.count)
console.log(message.value)

{{counter.count  message}}
```
## Binds

### Atributo
```javascript
v-bind:atributo 
:atributo
```

### Evento
```javascript
v-on
```
