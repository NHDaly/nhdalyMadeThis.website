---
layout: page
title: "@nhdalyMadeThis, LLC"
order: 3
---


I make games under the game developer company _nhdalyMadeThis, LLC_.

<a name="Paddle-Battle"></a>
## Paddle Battle [![icon]({{ "assets/images/Paddle-Battle-Icon.png" }}){:width="50px"}](#Paddle-Battle)
My first product is a simple game written entirely in [Julia{% include icon-julia-logo-three-balls.html %}](https://github.com/JuliaLang/julia), intended as an example of creating and publishing a game from scratch with Julia. The code for the project is available here under the MIT license:<br>
[https://github.com/NHDaly/PaddleBattleJL](https://github.com/NHDaly/PaddleBattleJL)

I would love you to fork it and change it and sell what you create!

*Download the game here: <a id="paddleBattleDownload" href="https://github.com/NHDaly/PaddleBattleJL/releases/latest">Paddle-Battle.dmg</a>*

![clip from Paddle Battle]({{ "assets/images/Paddle-Battle-Clip.gif" }}){:width="300px"}

<script>
var ajaxRequest = new XMLHttpRequest();
ajaxRequest.onreadystatechange = function(){

  if(ajaxRequest.readyState == 4){
    releasesJson = JSON.parse(ajaxRequest.responseText);

    var asset = releasesJson.assets[0];
    document.getElementById("paddleBattleDownload").href = asset.browser_download_url;
  }
}
ajaxRequest.open('GET', 'https://api.github.com/repos/NHDaly/PaddleBattleJL/releases/latest');
ajaxRequest.send();
</script>


<a name="LiveIDE"></a>
## LiveIDE
I've been building a tool for live-debugging and editing julia code! It's
inspired by Bret Victor's 2012 [Inventing on
Principle](https://vimeo.com/36579366) talk. That talk also inspired similar
tools, like [Hydrogen](https://github.com/nteract/hydrogen), the jupyter
notebook integration for the [Atom](https://github.com/atom/atom) code editor.

I've been working on it for about a month. I'm currently calling it _LiveIDE_,
but the name is a work-in-progress.

LiveIDE is Copyright © 2018 nhdalyMadeThis, LLC
All rights reserved.
