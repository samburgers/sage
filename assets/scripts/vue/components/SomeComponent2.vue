<template>
  <div>
    <h1>{{title}}</h1>
    <ul>
      <li v-for="todo in todos">
        {{ list.text }}
      </li>
    </ul>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        title: 'Some Component Title!!',
        list: [
          { text: 'List One' },
          { text: 'List Two' },
          { text: 'List Three' }
        ]
      }
    }
  }
</script>
