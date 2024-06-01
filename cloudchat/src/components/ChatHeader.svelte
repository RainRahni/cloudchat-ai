<div class="chat-header">
    <h1 class="nav-link active" id="gpt-3.5-tab" data-bs-toggle="tab" href="#gpt-3.5" aria-controls="gpt-3.5"
        >Chat UI</h1>
    <div class="search">
        <div class="search-bar" style="display: flex; align-items: center">
            <input type="text" class="form-control" placeholder="Search">
            <img src="moon.png" alt="moon">
            <img src="Avatar.png" alt="User">
        </div>
    </div>
</div>

<style>
    .chat-header {
        display: flex;
        align-items: center;
        justify-content: space-between;
        flex-direction: row;
        margin-top: 25px;
        color: #1B2559;
        width: 85%;
        padding-left: 50px;
    }
    .search-bar {
        display: flex;
        align-items: center;
        border: 1px solid #ced4da;
        border-radius: 0.375rem;
        width: 150px;
    }
    .search-bar input {
        border: none;
        outline: none;
        box-shadow: none;
        flex-grow: 1;
    }
    .search-bar img {
        border-radius: 50%;
        width: 32px;
        height: 32px;
    }
</style>
