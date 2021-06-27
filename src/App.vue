<template>
    <div class="App">
        <AxWindowSidebar />
        <AxWindowButtons />
    </div>
</template>

<script>
    import AxInput from "@/components/AxeriDev/AxInput";
    import AxButton from "@/components/AxeriDev/AxButton";
    import AxRange from "@/components/AxeriDev/AxRange";
    import AxCheckBox from "@/components/AxeriDev/AxCheckBox";
    import AxWindowSidebar from "@/components/AxeriDev/AxWindowSidebar";
    import AxWindowButtons from "@/components/AxeriDev/AxWindowButtons";
    
    export default {
        components: {
            AxWindowButtons,
            AxWindowSidebar,
            AxCheckBox,
            AxRange,
            AxButton,
            AxInput
        }
    }
</script>

<style lang="less">
    .App {
        display: flex;
        flex-direction: row;
    }
    * {
        outline: none;
        box-sizing: border-box;
    }
    body {
        background: #191919;
        margin: 0px;
    }
</style>