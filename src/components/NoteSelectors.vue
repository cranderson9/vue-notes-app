<template>
  <div class="note-selectors">
    <!-- note selector was here -->
    <note-selector />
    <note-selector />
    <note-selector />
    <note-selector />
    <note-selector />
  </div>
</template>

<script>
import NoteSelector from './NoteSelector';

export default {
  name: 'note-selectors',
  components: {
    NoteSelector
  }
}
</script> 