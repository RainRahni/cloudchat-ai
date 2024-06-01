<script>
    import Sidebar from '../components/Sidebar.svelte';
    import ChatContainer from "../components/ChatContainer.svelte";
</script>

<div id="app">
    <Sidebar />
    <ChatContainer/>
</div>

<style>
    #app {
        display: grid;
        grid-template-columns: auto 1fr;
    }
</style>