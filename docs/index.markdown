---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
author_profile: true
spotifyId: "27rZYxE4l21wTaovX4WTnI"
# header:
#   video:
#     id: NZc__Hhi4L8
#     provider: youtube
---
{% include video id="NZc__Hhi4L8" provider="youtube" %}

<p>
<audio id="loop-limited" controls="controls" autoplay style="width: 6em;height:20px;">
<source src="/assets/audios/y2mate.com - Rex Orange County  Television  So Far So Good Official Audio.mp3" type="audio/ogg" />
<source src="/assets/audios/y2mate.com - Rex Orange County  Television  So Far So Good Official Audio.mp3" type="audio/mpeg" />
</audio>
<br />
<script>
var loopLimit = 5;
var loopCounter = 0;
document.getElementById('loop-limited').addEventListener('ended', function(){
    if (loopCounter < loopLimit){this.currentTime = 0;this.play();loopCounter++;}
}, false);
</script>
</p>

<!-- {% include spotify-RexOrangeCounty/sofarsogood.html id=page.spotifyId %}{: .align-center} -->
