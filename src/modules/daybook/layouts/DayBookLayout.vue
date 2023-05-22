<template>
    <Navbar></Navbar>
    <div class="d-flex">
        <div class="col-4">
          <EntryList></EntryList>
        </div>
        <div class="col">
            <router-view></router-view>
        </div>
    </div>
</template>

<script >
import Navbar from '@/modules/daybook/components/Navbar.vue'
import EntryList from '@/modules/daybook/components/EntryList.vue'

export default {
    components: {
        Navbar, EntryList
    }
}


</script>


<style lang="scss" scoped>

</style>