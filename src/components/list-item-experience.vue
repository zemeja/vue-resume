<template>
    <ListItem class="list-item-experience">
        <div class="heading">
            <div class="company">
                <span contenteditable="true" spellcheck="false">{{ company }}</span>
            </div>
            <div class="job">
                <span contenteditable="true" spellcheck="false">{{ job }}</span>
            </div>
            <div class="date">
                <span contenteditable="true" spellcheck="false">{{ date }}</span>
            </div>
        </div>
        <p contenteditable="true" spellcheck="false">
            {{ description }}
        </p>
    </ListItem>
</template>
<script>
import ListItem from '@/components/list-item'
export default {
    name: 'ListItemExperience',
    components: {
        ListItem
    },
    props: {
        company: {
            type: String,
            default: 'oXy Online s.r.o.'
        },
        job: {
            type: String,
            default: 'Lead frontend developer'
        },
        date: {
            type: String,
            default: '2013.8 — now'
        },
        description: {
            type: String,
            default: 'Job description'
        }
    }
}

</script>
<style lang="less">
.list-item-experience {
    .heading {
        font-size: 18px;
        font-weight: bold;
        display: flex;
        justify-content: space-between;
        margin-bottom: 12px;

        .company {
            width: 40%
        }

        .job {
            width: 35%;
        }

        .date {
            width: 25%;
            text-align: right;
        }
    }
}

</style>
