<script lang="ts">
</script>

<div>
    <h1>Not Supported</h1>

    <slot name="message">
        <p>The Screen-Capture API is not supported by your device.</p>
        <p>Please visit this site on a desktop.</p>
    </slot>
</div>

<style>
    h1 {
        margin: 1rem 0;
    }

    div {
        width: 100%;
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
</style>
