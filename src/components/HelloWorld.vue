<script>
let gifs = [
  "https://media.giphy.com/media/l4pSVziIbNt3WmJ8c/giphy.gif",
  "https://media.giphy.com/media/1zSz5MVw4zKg0/giphy.gif",
  "https://media.giphy.com/media/5xtDarC0XyqmUhD5eDK/giphy.gif",
  "https://media.giphy.com/media/12ETcAyWE6TjHy/giphy.gif",
  "https://media.giphy.com/media/T5QOxf0IRjzYQ/giphy.gif",
  "https://media.giphy.com/media/YWFmlljmSpo6k/giphy.gif",
  "https://media.giphy.com/media/tCYMesnacJ6cE/giphy.gif",
  "https://media.giphy.com/media/67T9Wfqpd9z6E8nvdx/giphy.gif",
  "https://media.giphy.com/media/12ETcAyWE6TjHy/giphy.gif",
  "https://media.giphy.com/media/oxFDq4E9CHb7W/giphy.gif",
  "https://media.giphy.com/media/5xtDarDQqitychRz27K/giphy.gif",
  "https://media.giphy.com/media/tpdG5dt17HaO4/giphy.gif",
  "https://media.giphy.com/media/10Jpr9KSaXLchW/giphy.gif",
  "https://media.giphy.com/media/PS7d4tm1Hq6Sk/giphy.gif",
  "https://media.giphy.com/media/I4hvxPEWSbq5q/giphy.gif",
  "https://media.giphy.com/media/wofftnAdDtx4s/giphy.gif"
]
export default {
  name: 'App',
  data () {
    return {
      gifs,
      activeGif: null
    }
  },
  methods: {
    sendQuestion(e){
      e.preventDefault();
      let index = Math.floor(Math.random() * 16) + 0;
      this.activeGif = this.gifs[index];
    }
  }
}
</script>
