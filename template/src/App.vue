<template lang="pug">
vm-layout(ref="layout" title="Vue Mapp Demo")
    router-view
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'

@Component({
    name: 'app'
})
export default class App extends Vue {

}
</script>

<style lang="postcss">

</style>
