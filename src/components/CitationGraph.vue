<template>
    <div 
    v-if="$store.state.searchResultsFound"
    class="ma-3">
        <span class="title">Citations</span>
    </div>
</template>

<script>
export default {
    name: 'CitationGraph'
}
</script>