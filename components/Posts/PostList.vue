<template>
    <div class="post-list">
        <PostPreview 
            id="1"
            thumbnail="https://images.pexels.com/photos/373543/pexels-photo-373543.jpeg?cs=srgb&dl=abstract-art-blur-bright-373543.jpg"
            title="Hello there"
            previewText="This is my first preview Text" />
                
        <PostPreview 
            id="1"
            thumbnail="https://images.pexels.com/photos/373543/pexels-photo-373543.jpeg?cs=srgb&dl=abstract-art-blur-bright-373543.jpg"
            title="Hi there"
            previewText="This is my second preview Text" />

        <PostPreview 
            id="1"
            thumbnail="https://images.pexels.com/photos/373543/pexels-photo-373543.jpeg?cs=srgb&dl=abstract-art-blur-bright-373543.jpg"
            title="Namaste there"
            previewText="This is my third preview Text" />  
    </div>
</template>

<script>
import PostPreview from '@/components/Posts/PostPreview'

export default {
    name: "PostList",

    components: {
        PostPreview
    }
}
</script>

<style scoped>
    .post-list {
        display: flex;
        padding: 20px;
        box-sizing: border-box;
        flex-wrap: wrap;
        align-items: center;
        justify-content: center;
    }
</style>