<script>
    import Logo from './Logo.svelte';
    import Logout from './Logout.svelte';
</script>
<style>
    .sidebar {
        height: 90vh;
        width: 300px;
        background-color: #ffffff;
        border-radius: 20px;
        border-right: 1px solid #e3e3e3;
        padding: 20px;
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        display: flex;
        flex-direction: column;
        font-family: 'Poppins';
        color: #1B2559;
    }
    .sidebar .nav-heading {
        display: flex;
        font-weight: bold;
        padding-bottom: 10px;
        margin: 10px 10px;
    }

    .heading-logo {
        margin-right: 10px
    }
    #admin-pages {
        font-weight: normal;
        opacity: 0.2;
        padding-bottom: 0;
    }
    .pro-features {
        opacity: 0.2;
    }
    .other-features {
        opacity: 0.7;
    }
    #other-pages {
        padding-bottom: 0;
    }
    .pro-badge {
        display: flex;
        justify-content: center;
        align-items: center;
        color:#603CFF;
        font-weight: bold;
        background-color:#F2EFFF;
        border-radius: 39px;
        width: 60px;
        height: 30px;
    }
    .pro-feature-header {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
</style>
<div class="sidebar">
    <Logo/>
    <nav class="nav flex-column">
        <div class="nav-heading">
            <img class="heading-logo" src="stars.png" alt="stars logo"> Chat UI
        </div>
        <div id="other-pages" class="nav-heading">
            <img class="heading-logo" src="pagesIcon.png" alt="icon of pages">
            Other Pages
        </div>
        <ul class="other-features">
            Prompt Page
        </ul>
        <ul class="other-features">
            Register
        </ul>
        <ul class="other-features">
            Sign In
        </ul>
        <div class="pro-feature-header">
            <div id="admin-pages" class="nav-heading">
                <img class="heading-logo" src="lockedIcon.png" alt="locked icon ">
                Admin Pages
            </div>
            <div class="pro-badge">
                PRO
            </div>
        </div>
        <ul class="pro-features">
            All Templates
        </ul>
        <ul class="pro-features">
            New Template
        </ul>
        <ul class="pro-features">
            Edit Template
        </ul>
        <ul class="pro-features">
            Users Overview
        </ul>
    </nav>
    <Logout />
</div>
