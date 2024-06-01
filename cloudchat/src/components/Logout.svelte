<script>
    export let userName = "Name Surname";
</script>
<div class="user-info">
    <div style="display: flex; align-items: center">
        <img src="Avatar.png" alt="User">
        <div>{ userName }</div>
    </div>
    <div class="logout-button">
        <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" transform="rotate(180)">
            <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
            <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
            <g id="SVGRepo_iconCarrier">
                <path d="M14 4L18 4C19.1046 4 20 4.89543 20 6V18C20 19.1046 19.1046 20 18 20H14M3 12L15 12M3
                    12L7 8M3 12L7 16" stroke="#001A72" stroke-width="1.5" stroke-linecap="round"
                      stroke-linejoin="round"></path>
            </g>
        </svg>
    </div>
</div>

<style>
    .user-info {
        display: flex;
        align-items: center;
        justify-content: space-between;
        margin-top: auto;
        padding: 10px;
        font-weight: bold;
        border-radius: 30px;
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }
    .logout-button {
        display: flex;
        align-items: center;
        justify-content: center;
        width: 40px;
        height: 40px;
        border-radius: 50%;
        border: 1px solid #E0E5F2;
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }
    .logout-button svg {
        width: 70%;
        height: 70%;
    }
    .sidebar .user-info img {
        width: 40px;
        height: 40px;
        border-radius: 50%;
        margin-right: 10px;
    }
</style>

