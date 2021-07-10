<script>
    import { initializeApp } from "firebase/app"
    import {onMount} from "svelte";

    onMount(() => {
        const firebaseConfig = {
            apiKey: "AIzaSyDOCAbC123dEf456GhI789jKl01-MnO",
            authDomain: "myapp-project-123.firebaseapp.com",
            databaseURL: "https://myapp-project-123.firebaseio.com",
            projectId: "myapp-project-123",
            storageBucket: "myapp-project-123.appspot.com",
            messagingSenderId: "65211879809",
            appId: "1:65211879909:web:3ae38ef1cdcb2e01fe5f0c",
            measurementId: "G-8GSGZQ44ST"
        }
        const firebaseApp = initializeApp(firebaseConfig);
    })
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>