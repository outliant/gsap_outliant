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

