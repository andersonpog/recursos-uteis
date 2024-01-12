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
v-bind:atributo ou : atributo

### Evento

v-on
