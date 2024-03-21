<script lang="ts">
    import { navigate } from 'svelte-routing';
    
    export let buttonText = 'Click me';
    export let buttonColor = 'blue';
    export let buttonTextColor = 'white';
    export let redirectPath = '/BeamMP-dashboard';
    
    function handleClick() {
        navigate(redirectPath);
    }
</script>

<button 
    on:click={handleClick} 
    style={`background-color: ${buttonColor}; color: ${buttonTextColor};`}
>
    {buttonText}
</button>
