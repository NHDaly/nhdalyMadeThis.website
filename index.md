---
layout: page
title: "@nhdalyMadeThis, LLC"
order: 3
---


I make games under the game developer company _nhdalyMadeThis, LLC_.

## Paddle Battle ![icon]({{ "assets/images/Paddle-Battle-Icon.png" }}){:width="50px"}
My first product is a simple game written entirely in [Julia{% include icon-julia-logo-three-balls.html %}](https://github.com/JuliaLang/julia), intended as an example of creating and publishing a game from scratch with Julia. The code for the project is available here under the MIT license:<br>
[https://github.com/NHDaly/PaddleBattleJL](https://github.com/NHDaly/PaddleBattleJL)

I would love you to fork it and change it and sell what you create!

*Download the game here: <a class="download" href="https://github.com/NHDaly/PaddleBattleJL/releases/latest">Paddle-Battle.dmg</a>*

![clip from Paddle Battle]({{ "assets/images/Paddle-Battle-Clip.gif" }}){:width="300px"}

<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<script>
function GetLatestReleaseInfo() {
  $.getJSON("https://api.github.com/repos/NHDaly/PaddleBattleJL/releases/latest").done(function(release) {
    var asset = release.assets[0];
    $(".download").attr("href", asset.browser_download_url);
  });
}

GetLatestReleaseInfo();
</script>
