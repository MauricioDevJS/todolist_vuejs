<template>
  <div id="app">
     <section class="hero is-primary is-bold is-fullheight">
      <!-- Hero head: will stick at the top -->
      <div class="hero-head">
        <nav class="navbar">
          <div class="container">
            <div class="navbar-brand">
              <a class="navbar-item">
                TodoList 1.0
              </a>
            </div>
          </div>
        </nav>
      </div>

      <!-- Hero content: will be in the middle -->
      <div class="hero-body">
        <div class="container has-text-centered">
          <div class="row">
            <div class="columns">
              <div class="column is-half is-offset-one-quarter">
                <todo-card></todo-card>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Hero footer: will stick at the bottom -->
      <div class="hero-foot">
        <div class="container">
          <div class="content has-text-centered">
            <p>
              <strong>VueJS TodoList</strong> by <a href="https://github.com/MauricioDevJS">Mauricio Cardoso Oliveira</a>.
            </p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import TodoCard from './components/TodoCard'
export default {
  name: 'app',
  components: {
    TodoCard
  },
  data () {
    return {
      msg: 'Hello, World!'
    }
  }
}
</script>

<style>

</style>