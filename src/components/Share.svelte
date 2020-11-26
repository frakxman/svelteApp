<!-- Share.css -->
<style>
    .Share {
        border: 1px solid rgba(219, 219, 219, 1);
        border-radius: 4px;
        background-color: white;
        margin: 0 0 2em 0;
        width: 300px;
        height: auto;
        position: absolute;
        top: 300px;
        left: 30%;
        z-index: 9;
        padding: 1em;
    }

    .Share-head {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .Share-head h2 {
        font-size: 16px;
    }

    .Share-head i {
        cursor: pointer;
    }

    .Share-content a {
        display: flex;
        align-items: center;
        text-decoration: none;
        color: black;
        font-size: 14px;
        margin: 2em 0 0 0;
    }

    .Share-content i {
        color: #3b5998;
        margin: 0 0.5em 0 0;
        font-size: 20px;
    }

    .Share-whatsapp i {
        color: #1bd741;
    }

  </style>

<!-- Share.html -->
<div class="Share">
    <div class="Share-head">
        <h2>Share</h2>
        <i class="far fa-times-circle" on:click/>
    </div>
    <div class="Share-content">
        <a href="https://www.facebook.com/sharer/sharer.php?&u=https://pusgstagram.co" target="_blank">
            <i class="fab fa-facebook-square" />
            Share to facebook
        </a>
        <div class="Share-whatsapp">
            <a href="https://api.whatsapp.com/send?&text=Aprendiendo%20https://pusgstagram.co"
               target="_blank">
                <i class="fab fa-whatsapp-square" />
                Share to Whatsapp
            </a>
        </div> 
        <a href="https://twitter.com/intent/tweet?text=Aprendiendo&url=https://pusgstagram.co"
           target="_blank">
            <i class="fab fa-twitter-square" />
            Share to Twitter
        </a>
    </div>
</div>