<template>
    <div class="small-12 medium-6 columns">
        <ul class="accordion" data-accordion data-allow-all-closed="true">
            <li class="accordion-item" v-for="index in 5" data-accordion-item>
                <a href="#" class="accordion-title">Server #{{ index }}</a>
                <div class="accordion-content" data-tab-content>
                  This is server number {{ index }}
              </div>
            </li>
        </ul>
    </div>
</template>

<script>
</script>

<style scoped>
  a {
    color: red;
  }
</style>
