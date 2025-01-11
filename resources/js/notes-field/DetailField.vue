<template>
  <h3>Hoer</h3>
  <NotesField
    :field="field"
    :resourceName="resourceName"
    :resourceId="resourceId"
    :extraClass="'-mx-6 -my-px border-t'"
  />
</template>

<script>
import NotesField from '../components/NotesField';

export default {
  components: { NotesField },
  props: ['field', 'resourceId', 'resourceName'],
};
</script>
