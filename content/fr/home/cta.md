---
widget: slider
interval: 5000
height: 350px

headless: true
weight: 20

item:
  - title: Visitez notre page Youtube<br/>et abonnez-vous dès maintenant !
    content: '<br/>'
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    overlay_color: '#d7bfb6'  # An HTML color value.
    #overlay_img: bubbles.jpg  # Image path relative to your `assets/media/` folder
   # overlay_filter: 0.5  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Salis & Cats, editions.
    cta_url: 'https://www.youtube.com/channel/UCpskbazAPxxHwwZgHZM5YOA/featured'
    cta_icon_pack: fab
    cta_icon: youtube
  - title: Decouvrez notre boutique<br/>et précommandez le disque !
    content: '<br/>'
    align: center
    overlay_color: '#98bbcb'
    cta_label: Boutique
    cta_url: './boutique'
    cta_icon_pack: fas
    cta_icon: shopping-cart
  - title: Visitez notre Crowdfunding<br/>et soutenez le projet !
    content: '<br/>'
    align: center
    overlay_color: '#e6d090'
    cta_label: Platform
    cta_url: 'https://www.youtube.com/channel/UCpskbazAPxxHwwZgHZM5YOA/about'
    cta_icon_pack: fas
    cta_icon: money-bill-wave-alt

#{{% cta cta_link="https://www.youtube.com/channel/UCpskbazAPxxHwwZgHZM5YOA" cta_text="Visitez la page Youtube    →" %}}
#{{% cta cta_link="./boutique" cta_text="Decouvrez notre boutique →" %}}
#{{% cta cta_link="./boutique" cta_text="Lien vers notre Crowdfunding →" %}}
---
