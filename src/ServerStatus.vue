<template>
    <div>
        <div>server status: {{ status }}</div>
        <button @click="changeStatus">Change Status</button>
    </div>
</template>

<script>
    export default {
        data: function(){
            return {
                status: 'cretical'
            }
        },
        methods: {
            changeStatus() {
                this.status = 'Normal';
            }
        }
    }
</script>