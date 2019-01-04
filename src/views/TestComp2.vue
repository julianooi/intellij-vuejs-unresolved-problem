<template>
	<div>

	</div>
</template>

<script lang="ts">
    import {Component, Vue} from "vue-property-decorator";
    import Service from "@/services/my-service";
    // import Service from "../services/my-service"; // this works

    @Component
    export default class TestComp2 extends Vue {
        created() {
            Service.doSomething();
        }
    }
</script>

<style scoped lang="scss">

</style>