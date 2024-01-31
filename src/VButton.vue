<script>
import { defineComponent, h } from 'vue'

export default defineComponent({
  emits: ['update'],

  setup(_, ctx) {
    return () =>
      h(
        'button',
        {
          type: 'button',
          onClick: () => ctx.emit('update'),
        },
        'Click me!',
      )
  },
})
</script>
