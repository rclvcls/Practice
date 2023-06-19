<template>
  <div>
    <PrimaryButton :data="design"/>
    <br/>
    <PrimaryButton :data="{textColor:'text-green-500',border:'border',borderColor:'border-green-900'}"/>
       <br/>
    <PrimaryButton :data="{textColor:'text-green-500',border:'border',borderColor:'border-green-900'}"/>
  </div>
</template>

<script>
import PrimaryButton from '@/components/Button/PrimaryButton.vue'
export default {
  data: () => ({
    design: {
      textColor:'text-red-500',
      border: 'border',
      borderColor: 'border-blue-900'
    }
  }),
  components: {
    PrimaryButton,
  },
}
</script>
