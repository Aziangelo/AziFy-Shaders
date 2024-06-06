+++
title = "AziFy Shaders"
template = "index.html"

[extra]
hero_title = "AziFy Shaders <i class='hero__title-hat fa-solid fa-wand-magic-sparkles'></i>"
hero_caption = "Enhance your Minecraft Experience."
hero_btns = [
    { name = "<i class='fa fa-download'></i> Download", url = "download" }
]
+++

<div style="width: 100%; display: flex; flex-wrap: wrap; gap: 10px;">

{{ explorecard(
    title = "AziFy Truly Default"
    description = "New Update v3.0!"
    image = "https://raw.githubusercontent.com/Aziangelo/AF-TrulyDefault/main/azifyss/ss1.jpg"
    url = "download"
    size = 2
) }}

{{ explorecard(
    title = "AziFy Revive"
    description = "Test"
    image = ""
    
    size = 1
) }}

</div>


<div style="text-align: center;">

# #aesthetic #realistic 

**AziFy Shader** Description!

</div>

<style>

.hero__title {
  background: linear-gradient(80deg, hsl(10, 100%, 60%) 0%, hsl(220, 100%, 60%) 100%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  position: relative;
  display: inline-block;
}

.hero__title::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 200%;
  height: 100%;
  background: linear-gradient(120deg, transparent, rgba(255, 255, 255, 0.4), transparent);
  animation: shine 3s infinite;
  background-clip: text;
  -webkit-background-clip: text;
  color: transparent;
}

@keyframes shine {
  0% { left: -100%; }
  50% { left: 100%; }
  100% { left: 100%; }
}

.hero__title-hat {
  font-size: 56px;
  animation-name: rotating;
  animation-duration: 10s;
  animation-iteration-count: infinite;
  animation-timing-function: ease-in-out;
}

@keyframes rotating {
  0% { transform: rotate(0deg); opacity: 1.0; }
  92% { transform: rotate(0deg); opacity: 0.5; }
  100% { transform: rotate(360deg); opacity: 1.0; }
}

</style>

