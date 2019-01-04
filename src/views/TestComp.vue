<template>
	<div>

	</div>
</template>

<script lang="ts">
    import {Component, Vue} from "vue-property-decorator";
    import Service from "@/services/my-service";
    // import Service from "../services/my-service";

    @Component
    export default class TestComp extends Vue {
        created() {
            Service.doSomething();
        }
    }
</script>

<style scoped lang="scss">

</style>