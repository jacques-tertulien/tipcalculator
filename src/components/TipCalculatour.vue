<template>
  <div>
    <p>{{ title }}</p>
    <OutputMessage />
    <InputBill />
    <InputGuest />
    <p>Or</p>
    <ButtonTips />
  </div>
</template>

<script>
import ButtonTips from '@/components/ButtonTips.vue';
import InputBill from '@/components/InputBill.vue';
import InputGuest from '@/components/InputGuest.vue';
import OutputMessage from '@/components/OutputMessage.vue';

export default {
  name: 'TipCalculatour',
  components: {
    ButtonTips,
    InputBill,
    InputGuest,
    OutputMessage,
  },
  props: ['okay-service'],

  data() {
    return {
      title: 'Split',
      okayService: '15%',
      goodservice: '20%',
      greatservice: '25%',
      inputbill: '',
      inputguest: '',
    };
  },
};
</script>

<style lang="scss">
*,
*::before,
*::after {
  margin: 0;
  padding: 0;
}
</style>
