<template lang="pug">
button.button.button--help-anyone
  //- RouterLink(:to="{name: 'Donate'}") 
  RouterLink(:to="{name: 'Forum'}") 
    span Help Anyone 
    img(src="@/assets/images/icons/help-anyone.png")
</template>
<style lang="scss">
.button--help-anyone {
  background-color: var(--color-primary-green);
  color: var(--color-white);
  gap: 2.4rem;
  font-weight: 600;
  disl & img {
    /* disl & img { */  
    width: 3.6rem;
    transform: scale(1.75);
  }
}
</style>
