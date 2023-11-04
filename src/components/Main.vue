<template >
    <div>
        {{ name }}
    </div>
</template>

<script>

    
    export default {
      data() {
        return {
          name: 'Main Component',
        };
      },
      methods: {
        doIt() {
          console.log(`Hello ${this.name}`);
        },
      },
      mounted() {
        this.doIt();
      },
    };
    </script>
    
    <style scoped>
    </style>
