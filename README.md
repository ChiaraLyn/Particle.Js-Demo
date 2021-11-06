## Particles.js

Today I had a little taste of the power of the canvas concept. I chose to use a really beautiful library: [Particle.Js](https://vincentgarreau.com/particles.js/)      
It was a very exciting experiment. My demo is really essential but I realized that it has an immense potential for projects in which you want to make the most of design as an art form to communicate and to create different... atmosphere.    

![My Demo](img/particle.gif)    

After all, the concept of canvas is nothing more than an explicit reference to a white canvas that can be filled with what we want...   
So, with Particle.Js it is really simple to have in your hands working code, stable, clean, customizable.

Simply edit your canvas from the tool that Vincent Garreau (Particle.Js author) made available and publish it on Codepen. From here you can use the Javascript, Css and HTML parts in your project.    
The rest is built within the div that hosts the canvas.   
You can set all the settings related to the number of items you want, the interactions on hover, on click and the ways in which our items must react to these events.

![Particle Guide](img/guide.png)  

The particles are perfectly customizable and even the base of our canvas can be used with simple CSS or a background image.
Particle types can be chosen from a dropdown that offers default particles, NASA, Bubble, Snow, Nyan Cat.   

Particle.Js has 24,899 stars at the moment (including mine!) and 282 issues and 4,400 forks and is licensed under MIT.

1) Include [CDN library](https://www.jsdelivr.com/package/npm/particles.js) in you HTML file and use the 

```HTML   
<div id="particles-js"></div>
```
to grab you HTML content 

2) Create you own custom particles canvas using the page tool at https://vincentgarreau.com/particles.js/ 

3) Publish it on Codepen using the Codepen button on the top right 

4) In you custom JavaScript file copy that Codepen result (same for CSS)

***

  *All the "stats" part has been deleted because i don't need to monitor particles in this demo*
  
  The only flaw that this library has is that it is no longer maintained :cry:, but wait! We have a wonderful **solution** :sunglasses: :heart: !!

## tsParticle.js
 
**[tsParticle.js](https://particles.js.org/)** is a library with an implementation really similar to Particle.js (so there is not much different or complex than the previous one, really!!), with new features and very well maintained, created by @matteobruni and released under MIT license and... it's also wonderful :white_check_mark:!

[![particle2.gif](https://i.postimg.cc/gcsfhnWy/particle2.gif)](https://postimg.cc/LhqCK4hh)

In order to understand how to implement it, we have a beautiful documentation on [Github](https://github.com/matteobruni/tsparticles).

Matteo writes in his [article](https://dev.to/matteobruni/5-reasons-to-use-tsparticles-and-not-particles-js-1gbe): 
>[...]I’ll show you some reasons to replace particles.js with the new tsParticles.

>1. *tsParticles are fully compatible with the particles.js configuration. Seriously, you just need to change the script source et-voilà you're ready.*

>2. *tsParticles have a frame per second (fps) limiter, so they don’t let the CPU client suffer more than necessary.*

>3. *tsParticles have a lot of new features.*

>4. *tsParticles development is active.* [...]


We can find some great **examples with tsParticles** also on [Codepen](https://codepen.io/collection/DPOage), just to give you an idea of the potential and you can implement it with Vue, React and even Angular. For Wordpress there is no plugin but you can use tsParticle through Premium Addons for Elementor (in the Premium Particles Add.on section).

I hope that you too can try to have fun with **tsParticle.Js**, and that you create beautiful patterns for your projects!:blush: :blush:
