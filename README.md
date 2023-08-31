# landing-mountains

## Site address: https://incredible-gelato-12914a.netlify.app/

This site I made to practice data attributes, work with background and adaptive designe.
I used:

![](https://img.shields.io/badge/-HTML-7FFF00)
![](https://img.shields.io/badge/-CSS-7FFF00)
![](https://img.shields.io/badge/-Java%20Script-7FFF00)
![](https://img.shields.io/badge/-SVG-7FFF00)
![](https://img.shields.io/badge/-Adaptive%20designe-7FFF00)
![](https://img.shields.io/badge/-data%20attributes-7FFF00)
![](https://img.shields.io/badge/-Flexbox-7FFF00)
![](https://img.shields.io/badge/-positions-7FFF00)
![](https://img.shields.io/badge/-media%20queries-7FFF00)

![screenshot](/Screenshot_mountains.jpg)

## My code

```

window.addEventListener('click', function(){
    console.log('click on window');

    if (body.classList.contains('no-scroll')) {
        toggleMobileNav ();
    }
})

mobileNav.addEventListener('click', function(event){
    event.stopPropagation();
})

function toggleMobileNav () {
    mobileNav.classList.toggle('mobile-nav-active');
    navBtn.classList.toggle('nav-button-close');
    body.classList.toggle('no-scroll');
}

```

