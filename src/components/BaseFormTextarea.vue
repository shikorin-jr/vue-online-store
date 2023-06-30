<template>
  <BaseFormField :title="title" :error="error">
    <label></label>
    <textarea
      v-model="dataValue"
      class="form__input form__input--area"
      :placeholder="placeholder"
    ></textarea>
  </BaseFormField>
</template>
<script>
import formFieldMixin from '@/mixins/formFieldMixin';

export default {
  mixins: [formFieldMixin],
};
</script>
