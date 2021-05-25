<template lang="">
    <div>
        <ul>
            <li>
                <nuxt-link to="/settings">General</nuxt-link>
            </li>
            <li>
                <nuxt-link to="/settings/deck">Deck</nuxt-link>
            </li>
            <li>
                <nuxt-link to="/settings/schedule">Schedule</nuxt-link>
            </li>
        </ul>
        <nuxt-child/>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="">
    
</style>