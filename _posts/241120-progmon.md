# PROGRAMMING MONSTER

One of the projects I've been working on recently is programming a video game using the Pico-8 console. The game is intended to be a Pokemon-like RPG which incorporates some ideas I've used in previous BASH games. The limitations of the Pico-8 console reduces the scope of what a monster training RPG can offer, but I've spun up a few ideas that can, hopefully, make extensive use of what little resources I have.

The first, most significant limitation is sprite count. I settled on a total of sixteen 16x16 sprites for the monsters, which is not a lot. To make the most of such a small pool of monsters, I've decided to depart from a the linear evolutionary lines seen in Pokemon, opting for a cyclical branching evolutionary path. A close comparison would be the evolutionary process for Digimon. However, instead of starting from a basic monster and progressively evolving up to a maximum power monster, the monster forms in my game are all of similar size and (lack of) complexity, and the monster never stops changing forms.

By making the monster evolution cyclical, I can re-use forms to allow players more time to become familiar with and attached to the each. Since monsters do not inherently power up when their form changes, each form change will instead offer a new utility to the monster, such as a new attack or ability. Each form will have mutliple phases of utility to add, meaning players can evolve to the same form multiple times and still earns something from it, while giving completionists something to chase.

As of now, none of that has been programmed. I'm a novice programmer, so I am learning how to implement a lot of these things as I go. So, consider those nothing more than plans, haha. For the moment, I'm refamiliarizing myself with the Lua language, and programming in general, by building out basic systems, menus and whatnot that I feel a prerequisites to beginning work on the battling and evolution systems.

I don't have much to show for my work at this point, but I have enough complete to at least show a screenshot of a basic idea of what my prototyping has led up to so far. I'm uploading [112024_prototype.png](https://github.com/mosevique/milomitir/blob/main/_media/241120_prototype.png) to capture where things are for the moment. 

![prototype screenshot](https://github.com/mosevique/milomitir/blob/main/_media/241120_prototype.png?raw=true)
