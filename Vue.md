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
v-bind:id 
:id
```

### Evento
```javascript
v-on:click
@click

<button @click="increment">{{ count }}</button>
```
