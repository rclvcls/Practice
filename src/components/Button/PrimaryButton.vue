<template>
  <div>
    <button :class="data.textColor, data.border, data.borderColor" class="p-4 transition-all duration-300 ease-in-out hover:scale-125">Arcel</button>
  </div>
</template>

<script>
export default {
   props: ['data'],
}
</script>