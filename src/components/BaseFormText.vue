<template>
  <BaseFormField :title="title" :error="error">
    <label></label>
    <input
      v-model="dataValue"
      class="form__input"
      type="text"
      :placeholder="placeholder"
    >
  </BaseFormField>
</template>
<script>
import formFieldMixin from '@/mixins/formFieldMixin';

export default {
  mixins: [formFieldMixin],
};
</script>
