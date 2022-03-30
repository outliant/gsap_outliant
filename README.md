# gsap_outliant
GSAP animations for Oultiant website

## There are four/five main animations:
Loader
Menu
Blocks 1
Blocks 2
(There are others to implement on scroll)

## Steps
- Research: See some examples and implementation
- Prepare the assets (svg needs customizing)
- Prepare GSAP animations
- Integration into React project
- Integration into React Outliant project

## Workflow
- Edit the svg adding different paths
- Give styles
- Animate with GSAP
- Integration into React

## Research
This site was built using [GitHub Pages](https://pages.github.com/).
- [Animating React Components With GreenSock](https://www.smashingmagazine.com/2020/09/animating-react-components-greensock/)
- [React-gsap docs](https://bitworking.github.io/react-gsap/)
- [GSAP + React, First Steps & Handy Techniques](https://greensock.com/react/)
- [Hook a Lottie animation up to ScrollTrigger](https://greensock.com/docs/v3/HelperFunctions#lottie)
- [How to use the GSAP ScrollTrigger plugin in React](https://blog.logrocket.com/how-to-use-the-gsap-scrolltrigger-plugin-in-react/)
- [GSAP Cheetsheet](https://greensock.com/cheatsheet/)

## Loader
For the loader, to do it perfect I would need special plugins from GSAP. The video animation uses special animations features such as svg Drawing and Morphing, for this, GSAP has what they call The Club Greenshock where you can access these plugins. I think commercial license is 90$ per year (see https://greensock.com/licensing/ )

By now I would do two versions, with/without plugin

## Animations on Codesandbox
- Block1 (index.php) - https://codesandbox.io/s/block1-jxbigs 
- Block2 (performance) - https://codesandbox.io/s/block2-g8xcmy 
- Loader (without plugin) - https://codesandbox.io/s/loader-noplugin-i5bvrx 
- Loader (with plugin) - https://codesandbox.io/s/loader-withplugins-sq8o01 

## Update on React GSAP Animations (Round 2!)
These are the four animations shown yesterday:
- Let´s Collab - https://codesandbox.io/s/scrolltrigger-lets-collab-toggleactions-h80in8
- Our work - desktop - https://codesandbox.io/s/our-work-on-scroll-mb4o00
- Our work - mobile - https://codesandbox.io/s/mobile-onscroll-1e9wxk
- Limitless creation - https://codesandbox.io/s/limitless-creation-onscroll-kb5jsz

## Image optimization:
For “Our Desktop” animations I resized the media files as follows:
- Desktop 576x1070px
- Tablet 371x831px
- Mobile 340x2103px

I have made several trials with anyconv, optimage.app and tinypng.com
I upload a screenshot of images sizes (original, compressed to webp and what we are using now). For “Our work” animation, I did not include the texts (Real Estate  - Swift - Beauty Agency), I can add them if needed.

I am masking this images using: clip-path inset
You can see at the css files.

For mobile I have to use a .png as it has some transparency

In the demo files I am using scrollTrigger to trigger the animations once the user sees them on scroll view (we don´t want them to play out of viewport). Also if a user scrolls up and goes down again, the animation will begin again.
Animations are now looping, timing and sequencing can be easily changed.

## Next steps, working on:
- Menu Radial Scroll Bar Interaction
- 404

