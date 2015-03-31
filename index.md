---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
title: "Rich IT – Soluciones Integrales en tecnología."
header:
    image_fullwidth: "logo.png"
    title: ""

widget-1:
    title: "¿Quiénes somos?"
    url: '/quienes-somos/'
    text: 'Conócenos'
    image: mini-logo.png

widget-2:
    title: "Desarrollos"
    url: '/desarrollo/'
    text: '<em>Rich IT</em> tiene proyectos de desarrollo originales.'
    video: '<a href="#" data-reveal-id="videoModal"><img src="/images/video-omni.png" width="302" height="182" alt=""></a>'



widget-3:
    title: "Servicios"
    url: '/servicios/'
    text: 'Contamos co una gran variedad de servicios ofrecidos por profesionales certificados'
    image: cern.jpg


---


<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/sV_eaoFv2Ik" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>




<!-- Quite toda la carpeta de posts y la renombre a posts.bak, por si es necesario poner un blog posteriormente -->
