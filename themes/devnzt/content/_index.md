+++
description = "Devnzt se duis venenatis volutpat sollicitudin fermentum ante a risus zola efficitur porta."
[extra]
hero_title = "devnzt"
hero_caption = "Nulla sit amet semper mauris."

messagecard_socials = [
    { fa_icon = "fa-brands fa-github", alt="devnzt", url="https://github.com/devendrn/devnzt/" },
    { fa_icon = "fa-solid fa-hashtag", alt="Dapibus feugiat", url="" },
]

+++

<div style="display: flex; gap: 10px;">

{{ messagecard(
    title="Lorem Ipsum"
    description="Nunc consequat malesuada sem at aliquet. Ut at lectus nunc. Vivamus accumsan diam a magna tempor, vel tincidunt ipsum feugiat."
    socials_name="messagecard_socials"
    size = 2
) }}

<div class="card card--animated-cog" style="flex:1;"> 
  <i class="fa-solid fa-cog"></i>
</div>

</div>

# Fusce in justo

<div style="width: 100%; display: flex; flex-wrap: wrap; gap: 10px;">

{{ explorecard(
    title = "Vivamus accumsan"
    description = "Sed non lectus condimentum, dapibus lectus quis, tempus purus."
    image = "https://picsum.photos/600/300"
    url = "gallery"
    size = 2
) }}

{{ explorecard(
    title = "Quisque"
    description = "Fusce maximus dolor at mauris blandit iaculis."
    image = "https://picsum.photos/800/300"
    url = "page"
    size = 1
) }}

</div>

# Duis dictum

Phasellus non vestibulum tortor. Sed finibus, augue eu bibendum imperdiet, lacus ante blandit ipsum, porttitor gravida magna magna in nisi. In hac habitasse platea dictumst. Duis venenatis volutpat sollicitudin. Vestibulum fermentum ante a risus efficitur porta. 

<style>

.card--animated-cog > i {
  animation: m 20s infinite linear;
}

@keyframes m {
  100% { transform: rotate(-360deg); }
}

@media screen and (max-width: 560px) {
  .card--animated-cog {
    display: none;
  }
}

</style>

