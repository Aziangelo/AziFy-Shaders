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
  <div class="explorecard" onclick="location.href='download'">
    <img src="https://raw.githubusercontent.com/Aziangelo/AF-TrulyDefault/main/azifyss/ss1.jpg" alt="AziFy Truly Default">
    <h2>AziFy Truly Default</h2>
    <p>New Update v3.0!</p>
  </div>

  <div class="explorecard" onclick="location.href='download'">
    <img src="path/to/image.jpg" alt="AziFy Revive">
    <h2>AziFy Revive</h2>
    <p>Test</p>
  </div>
</div>




<div style="text-align: center;">

# #aesthetic #realistic 

**AziFy Shader** Description!

</div>

<style>

.hero__title {
  background: linear-gradient(80deg, hsl(10,100%,60%) 0%, hsl(220,100%,60%) 100%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  position: relative;
  display: inline-block;
  overflow: hidden;
}

.hero__title::after {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 200%;
  height: 100%;
  background: linear-gradient(120deg, transparent, rgba(255, 255, 255, 0.6), transparent);
  animation: shine 3s infinite;
  mix-blend-mode: overlay;
}

@keyframes shine {
  0% { left: -210%; }
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

.explorecard {
  transition: transform 0.2s ease;
}

.explorecard:active {
  transform: translateY(-10px);
}

.explorecard {
  position: relative;
  display: inline-block;
  overflow: hidden;
  width: 100%;
  max-width: 400px;
  cursor: pointer;
}

.explorecard img {
  width: 100%;
  height: auto;
  display: block;
}

.explorecard h2, .explorecard p {
  position: absolute;
  left: 10px;
  color: white;
  margin: 0;
  padding: 5px;
  background-color: rgba(0, 0, 0, 0.3);
  width: calc(100% - 20px);
}

.explorecard h2 {
  bottom: 30px;
}

.explorecard p {
  bottom: 0px;
}


</style>
