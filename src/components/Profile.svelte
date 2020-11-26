<!-- Profile.js -->
<script>
    export let nickname;
    export let name;
</script>
<!-- Profile.css -->
<style>
    .Profile-content {
        align-items: center;
        display: flex;
    }

    .Profile-avatar img {
        width: 42px;
        height: 42px;
        border-radius: 50%;
    }

    .Profile-info {
        margin: 0 0 0 0.5em;
    }

    .Profile-info h2 {
        font-size: 14px;
        color: black;
        margin: 0;
        padding: 0;
    }

    .Profile-info span {
        font-size: 12px;
        font-weight: normal;
    }
</style>

<!-- Profile.html -->
<div class="Profile">
    <div class="Profile-content">
        <div class="Profile-avatar">
            <img src="https://media-exp1.licdn.com/dms/image/C4E03AQHoGMrTqpEQUw/profile-displayphoto-shrink_200_200/0?e=1611792000&v=beta&t=w-3XiIZwkwVuU-mHchSZbTG39oZ3zTwlOYgfG5aMuXQ" alt="">
        </div>
        <div class="Profile-info">
            <h2>{ nickname }</h2>
            <span>{ name }</span>
        </div>
    </div>
</div>