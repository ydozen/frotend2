<template>
    <div>
        <sample-component></sample-component>
    </div>
</template>

<script>
import SampleComopnent from './sample'

export default {
    name: 'OtherComponent',
    cofmponents: {
        SampleComponent,
    },
}
</script>
