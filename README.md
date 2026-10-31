# Ascent: an interactive parallax scrolling page

A scroll from a sunrise valley to Earth orbit, built for the Techfest CA Program "Interactive Parallax Scrolling Page" task.

## How the parallax works
- Five full scenes (Valley, Peaks, Clouds, Stratosphere, Orbit), each built from 3 to 5 layers.
- Every layer has its own speed (`data-s`). Far layers move slowly, near layers move faster than the scroll, and the text panels float at their own pace.
- Scroll is smoothed with an easing loop, and transforms use `translate3d` for GPU speed.
- Mouse movement adds a subtle sideways depth shift on desktop.
- A live altitude meter climbs from 0 m to about 400 km, and the sky colour changes seamlessly between scenes.
- Reduced-motion mode, keyboard navigation and a skip link are included.

## Run
Open `index.html` in a browser. No build step and no libraries.

## Live demo
https://smit20074.github.io/parallax-ascent/
