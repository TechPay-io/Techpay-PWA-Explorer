<template>
    <ul class="f-social-media-links no-markers">
        <li>
            <a href="https://discord.gg/FSa4ESEMAF" target="_blank" rel="nofollow" title="TechPay on Discord">
                <icon data="@/assets/svg/social-media/discord.svg" width="24" height="24"></icon>
            </a>
        </li>
        <li>
            <a href="https://twitter.com/TechPay_Chain" target="_blank" rel="nofollow" title="TechPay on Twitter">
                <icon data="@/assets/svg/social-media/twitter.svg" width="24" height="24"></icon>
            </a>
        </li>
        <li>
            <a href="https://t.me/TechPayAnn" target="_blank" rel="nofollow" title="TechPay on Telegram">
                <icon data="@/assets/svg/social-media/telegram.svg" width="24" height="24"></icon>
            </a>
        </li>
        <li>
            <a href="https://github.com/TechPay-io/" target="_blank" rel="nofollow" title="TechPay on Github">
                <icon data="@/assets/svg/social-media/github.svg" width="24" height="24"></icon>
            </a>
        </li>
        <li>
            <a href="https://medium.com/@techpay_io" target="_blank" rel="nofollow" title="TechPay on Medium">
                <icon data="@/assets/svg/social-media/medium.svg" width="24" height="24"></icon>
            </a>
        </li>
        <li>
            <a href="https://www.facebook.com/TechPayChain/" target="_blank" rel="nofollow" title="TechPay on Facebook">
                <icon data="@/assets/svg/social-media/facebook.svg" width="24" height="24"></icon>
            </a>
        </li>
    </ul>
</template>

<script>
    export default {
    }
</script>

<style lang="scss">
    .f-social-media-links {
        --f-social-media-links-color: #{$secondary-color-lighter};

        color: var(--f-social-media-links-color);

        li {
            display: inline-block;
            vertical-align: middle;

            &:not(:last-child) {
                padding-inline-end: 24px;
            }

            @include links() {
                color: inherit;
                transition: color $transition-length ease;
            }

            a:not(.btn):hover {
                color: #fff;
            }
        }

        .linkedin {
            position: relative;
            top: -3px;
        }
    }
</style>
