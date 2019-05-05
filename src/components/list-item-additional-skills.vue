<template>
    <ListItem>
        <p class="additional-skills" contenteditable="true" spellcheck="false">
            <b>Frameworks:</b> jQuery, Vue.js, Symfony <br>
            <b>CMS:</b> Wordpress, Prestashop, Opencart, OXID<br>
            <b>Templating:</b> Twig, Smarty<br>
            <b>Automation / build tools:</b> Node.js, Grunt, Gulp, Webpack<br>
            <b>Prototyping:</b> Adobe XD, Axure RP<br>
            <b>Miscellaneous:</b> Docker, GIT, Sass, Composer, Yarn, NPM, Adobe Photoshop, Redis, Elasticsearch, JIRA<br>
            <b>Languages:</b> Czech native, English B2<br>
            <b>Driver's license:</b> A, B
        </p>
    </ListItem>
</template>
<script>
    import ListItem from '@/components/list-item'
    export default {
        name: 'ListItemAdditionalSkills',
        components: {
            ListItem
        }
    }

</script>
<style>
    .additional-skills b {
        font-size: 18px;
        color: #2c3e50;
    }
</style>
