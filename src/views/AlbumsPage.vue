<template>
    <div>
        <h3>Albums Page</h3>
    </div>
</template>

<script>
export default {
    async mounted() {
        this.$store.dispatch('albumInfo/getAlbumsData')
    },

    data: () => ({
        albumName: '',
        error: ''
    }),

    methods: {
        openAlbumDetail(album) {

        }
    }
}
</script>