# Building Interfaces from the Future

The slides for my talk at [GUADEC 2017](https://2017.guadec.org/talks-and-events/#abstract-16-building_interfaces_from_the_future)

__Abstract:__

Animations are the future of interface design. They enable developers to make interfaces more understandable by offloading processes from the user’s brain to the screen. However, in many cases animations are simply added as transitions between independently designed screens. This can result in animations contradicting each other spatially. I co-wrote an [article](https://alistapart.com/article/motion-with-meaning-semantic-animation-in-interface-design) about why this is a problem and outlined a solution: Designing semantic components which change over time, and then using these to compose interfaces.

Even though the industry seems to largely agree that this is the way forward, there are very few interfaces implementing these ideas. I believe the main reason for this is that the current generation of layout technologies is built for static layouts with strict hierarchies. This makes it prohibitively difficult to build interfaces where components move fluidly between different states.

I will show some interface prototypes I built and explain why they were so difficult to implement with current technology. Finally, I will outline some ideas for a better layout API, to make building awesome, fluid interfaces from the future more feasible.
