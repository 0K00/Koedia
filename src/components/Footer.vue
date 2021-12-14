<template>
  <div class="footer">
    <div class="text" id="text">Text change on click</div>
    <div class="footer__bloc">
      <button @click="changeText('hello')" class="btn">
      </button>
      <button @click="changeText('hello2')" class="btn">
      </button>
      <button @click="changeText('hello3')" class="btn">
      </button>
    </div>
  </div>
</template>

<script>


export default {
  name: 'Footer',
  methods: {
    changeText: function(text) {
      let textValue = document.getElementById('text');
      textValue.value = text
      textValue.innerHTML = text
    }
  }
}
</script>
