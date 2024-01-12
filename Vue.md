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

<div :id="dynamicId"></div>
```

### Evento
```javascript
v-on:click
@click

<button @click="increment">{{ count }}</button>
```

### Two way
```javascript
<input :value="text" @input="onInput">
function onInput(e) {
  text.value = e.target.value
}

<input v-model="text">
```
