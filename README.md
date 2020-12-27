# wordpress_trace_plugin


## how to start youtube video in certien time using youtube API
```
function onYouTubeIframeAPIReady() {
    player = new YT.Player('player', {
        height: '720',
        width: '1280',

        videoId: 'i8IXMGHpGBk',
        playerVars: { 'start': 10}
        //playerVars: { 'autoplay': 1, 'controls': 1,'autohide':1,'wmode':'opaque' },
        events: {
            'onStateChange': function(e) {
                if (e.data == 0) {
                    //skrolla här
                }
            }
        }
    })
   
  ``` 
    
