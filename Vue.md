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
```vue
v-bind:id 
:id

<div :id="dynamicId"></div>
```

### Evento
```vue
v-on:click
@click

<button @click="increment">{{ count }}</button>
```

### Two way
```vue
<input :value="text" @input="onInput">
function onInput(e) {
  text.value = e.target.value
}

<input v-model="text">
```

### Condicional
```vue
<h1 v-if="awesome">Vue is awesome!</h1>
<h1 v-else>Oh no 😢</h1>
```

### Laços
```vue
<ul>
  <li v-for="todo in todos" :key="todo.id">
    {{ todo.text }}
  </li>
</ul>
```
