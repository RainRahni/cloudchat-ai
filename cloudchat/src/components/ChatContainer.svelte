<script>
    import ChatHeader from "./ChatHeader.svelte";
    import ChatGPTVersions from "./ChatGPTVersions.svelte";
    import ChatFooter from "./ChatFooter.svelte";
</script>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chat UI</title>
    <link href="bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            background-color: #fff;
            width: 99%;
        }
        .chat-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            height: 73vh;
            margin-top: 30px;
            background: #fff;
        }
        .links {
            padding-right: 30px;
        }
    </style>
</head>
<body>
<div class="container mt-3">
   <ChatHeader/>
    <div class="chat-container mx-auto">
        <ChatGPTVersions/>
        <div type="button" class="btn btn-light dropdown-toggle" data-bs-toggle="dropdown" aria-expanded="false">
            No plugins enabled
        </div>
        <div class="d-flex justify-content-center">
            <img style="display: flex; justify-content: center; width: 275px;" src="backgroundImg.png">
        </div>
        <ChatFooter/>
        <p style="font-size: 10px">
            Free Research Preview. ChatGPT may produce inaccurate information about people, places, or facts.
            <strong>ChatGPT May 12 Version</strong>
        </p>
    </div>
    <div style="opacity: 0.5; display: flex; float: right">
        <h5 class="links">Homepage</h5>
        <h5 class="links">License</h5>
        <h5 class="links">Terms of use</h5>
        <h5 class="links">Privacy Policy</h5>
    </div>
</div>

</body>
</html>
