<template>
<div class="wrapper-content">
  <section>
    <div class="container">
      <section>
        <div class="new-note">
          <newNote />
        </div>
      </section>
      <section>
        <div>
          <search />
        </div>
      </section>
     <notes />
    </div>
  </section>
</div>
</template>
<script>

import notes from '@/components/Notes.vue'
import newNote from '@/components/NewNote.vue'
import search from '@/components/Search.vue'

export default {
  components: {
    notes,
    newNote,
    search
  },
};
</script>

<style lang="scss">
.navbar-link {
  &.router-link-exact-active {
    color:rgb(134, 117, 228)
  }
}
</style>
