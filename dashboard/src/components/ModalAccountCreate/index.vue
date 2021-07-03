<template>
  <h1>Cadastrar novo usuário</h1>
  <p>{{ name }}</p>
</template>

<script>
export default {
  name: 'ModalAccountCreateIndex',
  props: {
    name: String
  },
  setup (props) {
    console.log(props)
  }
}
</script>
