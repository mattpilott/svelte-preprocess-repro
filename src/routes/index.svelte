<style lang="scss">
	:global(.block) {
      color: red;

      &__element {
         color: purple;

         &--modifier {
            color: blue;
         }
      }
   }
</style>

<div class="block">
   Block <span class="block__element">Element</span> <span class="block__element--modifier">Modifier</span>
</div>