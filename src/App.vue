<template>
    <AxInput value="Hello, world!" placeholder="Your Message" />
    <br /><br />
    <AxButton>Hello, Button!</AxButton>
    <br /><br />
    <AxRange />
    <br /><br />
    <AxCheckBox />
</template>

<script>
    import AxInput from "@/components/AxeriDev/AxInput";
    import AxButton from "@/components/AxeriDev/AxButton";
    import AxRange from "@/components/AxeriDev/AxRange";
    import AxCheckBox from "@/components/AxeriDev/AxCheckBox";
    
    export default {
        components: {
            AxCheckBox,
            AxRange,
            AxButton,
            AxInput
        }
    }
</script>

<style lang="less">
    * {
        outline: none;
        box-sizing: border-box;
    }
    body {
        background: #191919;
    }
</style>