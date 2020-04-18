<template>
  <div class="youtube">
        <div id="player"></div>
        <div id="player2"></div>
        <div id="player5"></div>
        <div id="player4"></div>
        <div id="player3"></div>

    <script>
        var tag =document.createElement('script');
        tag.src='https://www.youtube.com/iframe_api';
        var firstScriptTag = document.getElementsByTagName('script')[0];
        firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);
        var player;
        var player2;
        var player3;
        var player4;
        var player5;
        function onYouTubeIframeAPIReady() {
          player = new YT.Player('player', {
            height: '390',
            width: '640',
            videoId: 'IDZyZMYn3H0',
            events: {
              
            }
          });
           player2 = new YT.Player('player2', {
            height: '390',
            width: '640',
            videoId: '2GFeHRlJf1A',
            events: {
              
            }
          });
          player3 = new YT.Player('player3', {
            height: '390',
            width: '640',
            videoId: '_8Avz2FCyHI',
            events: {
              
            }
          });
          player4 = new YT.Player('player4', {
            height: '390',
            width: '640',
            videoId: '2pWu_rJUiJs',
            events: {
              
            }
          });
          player5 = new YT.Player('player5', {
            height: '390',
            width: '640',
            videoId: 'ZS_kXvOeQ5Y',
            events: {
              
            }
          });

        }

    </script>
  </div>
</template>

<script>
    

    
export default {
  name: 'YoutubeC1'
}
</script>