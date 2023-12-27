<template>
    <div>
        <button @click="toggleComponent">Toggle Component</button>
        <component :is="currentComponent"></component>
    </div>
</template>
  
<script>
import ComponentA from './components/ComponentA.vue';
import ComponentB from './components/ComponentB.vue';

export default {
    data() {
        return {
            currentComponent: 'ComponentA',
        };
    },
    methods: {
        toggleComponent() {
            this.currentComponent = this.currentComponent === 'ComponentA' ? 'ComponentB' : 'ComponentA';
        },
    },
    components: {
        ComponentA,
        ComponentB,
    },
};
</script>