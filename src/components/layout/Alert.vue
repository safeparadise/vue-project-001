<template>
    <div class="alert {{ color }} alert-dismissible fade show" role="alert">
        {{ message }}
        <button type="button" class="close" data-dismiss="alert" aria-label="Close">
            <span aria-hidden="true">&times;</span>
        </button>
    </div>
</template>
<script>

export default ({
   name: 'Alert',
   props: ['message','color']
});
</script>
