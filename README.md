# youtube-bg live https://jibon87.github.io/youtube-bg/

```
1.  js--link ---> jquery.min.js

1.  js--link ---> js/youtube-bg.min.js

2.  css--link ---> css/youtube-bg.min.css

3.  html 
    {
    !-- youtube bg -->
    <div id="P1" class="player P1" data-property="{videoURL:'https://youtu.be/TxbE79-1OSI',containment:'self',startAt:50,opacity:.7}">
        <div style="height: 100vh" class="yt-content">
            <h2>jibon</h2>
            <div style="height: 150px; width: 200px">
                <img style="height: 100%; width: 100%" src="img/slider-5.jpg"/>
            </div>
        </div>
    </div>
    }
    
4.  active js {

    // youtub player
     $(".P1").YTPlayer({
        showControls: false,
        mute: true,
        autoPlay: true,
        loop: true,
        ratio: "16/9",
    });
}
5.  note [ 
           
         ]
