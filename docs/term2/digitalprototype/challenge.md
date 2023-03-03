---
hide:
    - toc
---

### MICRO CHALLENGE 1.0

I am always so excited when FabLab meets MDEF because there is **a clash of ideas that come to fruition in a matter of days**.

For context: I have always been reluctant when it comes to activism, as it felt too aggressive. It felt like it was an approach that would feed on my energy, hurting me more than anything else. At the same time, there is this expectation of activism being my daily positioning, a default setting, that I should be angry and frustrated all the time when in reality I just really want to keep adding good things all around me, elevate my community, and celebrate life. Recently I read Dr. Bayo Akomolafe, and he says the following:

*“Activism is increasingly instrumental, meaning it’s a form of power that is tied to the logic and algorithm of the status quo. This makes activism, even in the search for justice, a creature of the status quo, which renders hope and justice, as ironic as that sounds, a creature of the things we’re trying to leave behind.”*

I make his words my own, I feel seen in this excerpt. **My feelings towards activism are more complex than I thought** and also have a context that I did not take into account before - capitalist society.

Well… I have been talking with some colleagues for a while about how we could make a design intervention dedicated to the Weak Signals card: **“Non-Western-Centric Futures”**. I am very interested in decolonizing research. For me that circles back to storytelling, of who is telling the stories, myths, fantasies, and building these worlds and futures. More specifically, Natural Science Institutions that through ecological imperialism managed to take and gather knowledge, making it their own and neglecting and killing anything that did not fit into their imagined future - a Eurocentric future -. **A future that came to reality through the exploitation of life** - humans and other living things -. Behind this exploitation there are people like Columbus, Guell, and Joan Prim I Prats that were actively imposing borders, conquering lands, polarizing and formatting the world with their stories and fantasies resulting in the killing of millions and the destruction of the natural environment. Yet, they are still celebrated and highly viewed by many. Our History books are broken, as it is the system we currently live in, and that is reflected in our physical world.

So, when Marielle came to me with the idea of making a Machine that would uncover these hidden truths around the city of Barcelona, we could not help ourselves from jumping straight into it. Stella join us because she is also interested in the subtle signals/inputs/language a city can give to its citizens and how that shapes someone’s experience and beliefs. By the end of the morning of the first day, after brainstorming, reference searching, and sharing our values, we were set on the idea of making a Museum of Colonization. **The Museum of Colonization would be in the city of Barcelona.**

From defaced little colonizer statues, and making molds of city artifacts, to having a machine that would shoot colonization facts, we combined all of that and concluded that we would make a **Gumball machine**.

This was the **initial idea** and some of the questions we first had consisted of:

- Gumball Machine: figuring out the mechanism, designing our system, deciding whether we needed electrical components, designing the exterior of the machine, finding ways of combining the different machine parts (base, cover/top, front, back, mechanism, ball wholes), choosing materials (acrylic, paper, cardboard or wood),
- Balls: figuring out what kind of material was the best to work with (plastic or paper/cardboard), trying out different ball designs, defining the size of the ball, and trying different cutting technics to make the pattern (vinyl cutter or laser cutter).
- Gifts: ticket for the museum, stickers with a fact of the colonizer, a mini statue of the colonizer. Due to time constraints, we decided that we would only make the stickers.

Without knowing the size of the ball we could not have a mechanism. So, Stella started working on finding how we could make a ball. She is great at visualizing origami patterns and making them her own, so she proceeded with that task until we settled on a particular ball design. While Stella was doing the ball design and testing, I was trying to figure out how gumball machines work. I felt like I had to make a physical mechanical thing, feel, see, and build one to then move with a more spatial and materialistic awareness of what this machine does and consists of. I grabbed some cardboard and made a fast prototype of a mechanical gumball for kids. While I was doing that, Marielle was searching for a code to make our future disk dispenser work. We were working under schedule, and using our different skills to try to make this possible. I was nervous, as when I did the Tech Beyond the Myth the biggest struggle was to make the motor stop when and where we wanted… Yet, by the end of the day, we had a prototype of the mechanism (disk dispenser) made out of cardboard and decided on what kind of ball we would use - what we now call an armadillo ball. **This was just the first day!**

**On the second day**, Marielle and I started by brainstorming about the looks of the Machine. This was the combination of symbols, triggers, architecture, and calligraphy that is all around us. From China Town to Angolan traditional villages. Once we settled on a design Marielle moved it to Adobe Illustrator. While Marielle worked on adobe, I was focused on portraying the colonizer's defaced illustrations and their facts with a different tone. This group is not about feeling emotionally and energetically drained by focusing on colonization, but rather finding healthier and funnier ways to cope with harsh historical facts while still shining a light on the truths behind European cities like Barcelona. I learned so much from Marielle’s and Stella’s skills! We had to be fast and Marielle was super proficient with the software, and Stella could visualize the outcome of the origami balls and adapt them.

Before moving our designs into Rhino and laser cutting, we had some more cardboard experiments to do, in order to size the machine according to our ball size foresight. Once we got that out of our way, we moved on to figuring out the best measurements for the slots (places on the base of the machine where we would attach the different parts) according to the length of the component and thickness of the material. We intended to use acrylic and wood. But how could we make wood bend to meet our design choices? Because straight lines are not aligned with our “Non-Western-Centric” futures… That is when Marielle mentioned a type of cutting pattern that allows for materials like wood, to be more flexible in certain parts. So of course, we had to test it! However, due to time constraints, we chose to not proceed with wood to make our soft-cornered design. But this is what we learned from it:

1. the wood we used was not ideal for laser cutting as it burned very fast and did not cut through the design
2. ou of the designs in the picture of our testing the most flexible way

We could not use wood, but we could still use cardboard and attain a great texture and still very bendy. Marielle and Stella due to their backgrounds (Design & Arts) already knew we could have this as an alternative, but I saw it for the first time when I ripped the cardboard, and it looked fitting to our design and intentions. After that, I moved on to electronics as we had to replace Marielle’s Arduino, used for the initial prototype, for an ESP32 because we wanted to use the setup with a battery instead of connected to a PC. While shifting the setup I realized that the code used was done with a particular library I did not have installed, also the board and the setup were having the weirdest reactions, even Adai and Daphne were surprised. For Arduino, Marielle had found the servo.h library that would allow our motor to do a 180º turn each time, but it was a library incompatible with the ESP32. Daphne helped me find a library that was done with an ESP32 in mind. While I was doing the electronics with the ESP32, Marielle was at the laser cutter and Stella was trying to make the balls more resistant.

This is when I started to feel guilty. The first micro-challenge was coming to an end and even though I did help Marielle and Stella, and I was doing different tasks I did not have the chance to spend as much time as I wanted on the laser cut or doing the ball design. I understand now the guilt behind this was a personal construct: thought out school I was very used to being the one doing everything in group projects. In order to finish quite an ambitious project we organically divided our work without much discussion and played with our strengths, which is totally fine if not the best scenario but I am still attached to old habits that haunted me for the last few days… I later realized that there was no need to feel guilty. I am still learning how experiences, biases, and habits shaped me and that is ok.

**Day three** and we assembled the machine. The slots were the correct ones, and the sizes were in accordance with each piece and the ball size, we had engravings of a logo, the stickers, the balls, and the documentation but we still needed:

- attach every part of the machine together on the base slots
- because we were no longer working with wood (that would have slots to fit the acrylic parts) we had to glue the cardboard to the acrylics
- make a slide for the balls (from the top to the dispenser)
- pass our notion documentation to a GitHub Repository

As we passed through these obstacles we got to see our Museum of Colonization come to life!

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFbCUA-Hp8&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFbCUA-Hp8&#x2F;view?utm_content=DAFbCUA-Hp8&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">Why?</a> by Carolina Almeida

This was a more descriptive and personal view on the project but if you would like to know the step by step and what were our knowledge sources and code used, please click on the following links:

- GitHub: https://github.com/stella-dikmans/MOC/blob/main/README.md

- Notion: https://hickory-polonium-fd1.notion.site/Marielle-Stella-Carolina-MDEF-22-23-34fdfc848ec44d93bae61fdf263d6c88
