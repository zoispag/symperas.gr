<template>
  <div class="bg-pink-700 py-8 px-6 text-white flex justify-center">
    <div>
      <p class="text-3xl tracking-wide">Φροντίζουμε για <span v-html="careWord"></span> σας</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Credits',
  data() {
    return {
      interval: null,
      wordIndex: 0,
      words: [
        'το <strong>σπίτι</strong>',
        'το <strong>αυτοκίνητό</strong>',
        'τη <strong>σύνταξή</strong>',
        'την <strong>υγεία</strong>'
      ]
    }
  },
  computed: {
    careWord: function () {
      return this.words[this.wordIndex];
    }
  },
  methods: {
    rotateWords () {
      this.interval = setInterval(() => {
        this.wordIndex = this.wordIndex === this.words.length - 1 ? 0 : this.wordIndex + 1
      }, 1000)
    }
  },
  beforeDestroy () {
    clearInterval(this.interval)
  },
  created () {
    this.rotateWords()
  }
}
</script>
