<template>
    <div class="footer">
        <p>footer</p>

    </div>
</template>

<style lang="scss">
    .footer {
        height: 60px;
        background: $black;
    }

    @include mobile {
        .footer {
            height: 14vw;
        }
    }

</style>