<template>
  <section class="new-comment">
    <div class="container">
      <form class="contact-form" @submit.prevent>
        <label>Name: </label>
        <input type="text" v-model='comment.name'>
        <label>Text: </label>
        <textarea v-model="comment.text"></textarea>
        <div class="controls">
          <button class='btn btnPrimary'>Submit</button>
        </div>
      </form>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      comment: {
        name: '',
        text: ''
      }
    }
  },
  methods: {
    onSubmit() {
      console.log(this.comment)
    }
  }
}
</script>

<style lang="scss">
.new-comment {
  text-align: center;

  .controls {
    margin: 30px;
  }

  .contact-form {
    min-width: 600px;
    margin: 30px auto;
  }
}
</style>