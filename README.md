# The Internet of Energy

- [The Internet of Energy](#the-internet-of-energy)
   - [The idea](#the-idea)
      - [Applying the WWW knowledge to the energy internet](#applying-the-www-knowledge-to-the-energy-internet)
      - [What we need is energy prototyping devices](#what-we-need-is-energy-prototyping-devices)
   - [What problems could be solved?](#what-problems-could-be-solved)
   - [State of the Art](#state-of-the-art)
      - [Wireless electricity transfer](#wireless-electricity-transfer)
      - [Energy storage solutions](#energy-storage-solutions)
   - [The Internet of Things approach](#the-internet-of-things-approach)
   - [How can we start?](#how-can-we-start)
   - [Interesting links](#interesting-links)
   - [References](#references)

## The idea

For a couple of month the idea of Jeremy Rifkin, an American economic and social theorist, writer, public speaker, political advisor, and activist <sup>1</sup>, to implement an internet of energy, is stuck in the back of my head.

[![The Energy Internet Explained, with Jeremy Rifkin](http://img.youtube.com/vi/XtQoPcscFts/0.jpg)](http://www.youtube.com/watch?v=XtQoPcscFts) 

*["The Energy Internet Explained, with Jeremy Rifkin"](https://youtube.com/watch?v=XtQoPcscFts)* <sup>2</sup>

Rifkin speaks of generating energy ressources from every households roof by solar panels, wind generators and heat exchangers in the ground. Every household, and this system is currently beeing implemented in Denmark and Germany will provide its share of energy to a smart grid of energy storage and consumers. The energy need will be balanced in a smart fashion so that there is always enough energy at high demand hotspots.

But these developments and new innovations, which effect everyone of us, are mostly research driven by highly educated specialists and behind closed curtains in energy producing organisations and their research and development departements.

#### Applying the WWW knowledge to the energy internet

Rifkin adresses the similarities to the internet of communication, that we are used to for a couple of years now, the good old WWW. We have learned to scale software to be able to serve hundreds of thousands of requests per minute and we also learned to balance the load across available ressources and queue and store data as we need and can process them.

These developments have recently been pushed by open source contributions of a large community of intelligent and innovative people. It has so to say been crowdsourced. The WWW research and developments have been open and a lot of people are contributing. Most recently we are developing applications we classify as "The Internet of Things" and these developments are possible due to the easy access to prototyping tools, such as the [Arduino](https://www.arduino.cc/) microcontroller board, to name just one of these innovations.

We have cheap and easy prototyping tools to solve problems on the internet of communication and the WWW developers and thinkers have best practices in their pockets on how to solve large scale problems well.

*Can't we apply this knowledge to the internet of energy?*

#### What we need is energy prototyping devices

In order to apply this knowledge and the generous intelligence of a crowd of intelligent people we need prototyping tools such as the Arduino microcontroller, that everybody can hook up on their office desk, to play around with energy problems.

"We had no specialty in energy or mechanical engineering but with ideas, with efford, with commitment, perhaps together we can figure out how to sustainably power the world." - Danielle Fong <sup>2b</sup>

## What problems could be solved?

* The other day I was driving my car down a german motorway and saw on my right hand side a field of wind turbines, our push forwards into green energy production. On the other side I looked at lines and lines of electricity wires. For the internet of communication we have solved this wire problem by going wireless. **We need wireless energy transmission!**
* The dilemma with solarpanels is that they create the energy when the need and demand for it is lesser than it is, when they cannot provide their energy - at nighttime. In order to solve this problem, **we need energy storage solutions that can store the energy produced at any point and elastically provide the energy when needed**

*"In Germany, one Sunday last May when 75 percent of the energy coming through the power grid was solar and wind, we had negative prices all day. [The power plant pays the grid operator to accept power, so that it is not forced to shut down the power plant.] You have to put in storage in order to manage peak and base loads, else you get wild fluctuations in your price, and a potential disruption of the system."* <sup>2a</sup>

## State of the Art

### Wireless electricity transfer

We have been transmitting energy wirelessly for a really long time. Think of the way an electrical transformer works:

![](http://vlex.physik.uni-oldenburg.de/ewa_transformator_html_fd7c1e0.png)

*"Abb. 1: Transformator mit 2 Spulen gleicher Windungszahl"* <sup>3</sup>

Energy is beeing transferred from one coil to the other using an magnetic field. The distance between the coils are quite small, but researchers have found ways to enhance the distance. <sup>3a</sup>

The current record for wireless energy transmit in distance is 55m (around 180 ft) held by japanese scientists <sup>4</sup> that are aiming to create solar panels orbiting earth and sending back the highly efficient energy produced.

The idea behind these technologies is to use the resonance effect. The same way the opera singer can make a wineglass pop on the other side of the room, the magnetic field emmiting coils are beeing shaken at a high frequency in order to use the resonance effect and kind of shake the magnetic field through the room. But only coils that move with the same frequency can receive the magnetic field and retransform it into energy. 

With this innovation we could build a smart grid of energy emmiting devices on the roof of everybodies houses and transmit the energy to whereever we need it the most momentarily.

And this is where we, the software developers, internet specialists, IT thinkers come into place: How do we find out where to route the energy, how, why, what if a node fails, what if a distict fails to route or deliver of store. **We have already solved these problems! We have already solved these problems for the internet of communications. Let's apply our know how to the internet of energy!**

### Energy storage solutions

* Hydrongen Energy Storage <sup>5</sup>
* Flywheels
* Batteries

## The Internet of Things approach

Assuming that we already have an energy internet setup and that we know how to store the engery efficiently, a new internet of things approach can be used. We can look at our homes and find new ways of creating energy. Each of these smart energy emitting IoT devices can deliver their energy to the energy internet and send data to a data collection / routing hub.

To name just a few ideas of energy generating IoT ideas:

* Using the wastewater flow of every household to power small water turbines
* Use the by-produts of heat emitting devices like computers or televisions to generate small amounts of energy

Adding up all these small amounts of energy per household, multiplied by every household in a country, this can create severe amounts of energy.

## How can we start?

* Build little energy problem solving projects with Arduino!
* Think about ways to store electricity 
* Layout an energy grid that uses commodity electronics for cities
* Crowdsourcing ideas of sharing electricity

## Interesting links

* https://www.youtube.com/watch?v=9y39WNUdbkM, "Revolutionary designs for energy alternatives: Lonnie Johnson at TEDxAtlanta"
* https://www.youtube.com/watch?v=hZiaTV6uvFQ, "Energy storage under pressure | Danielle Fong | TEDxCERN"

## References

[1] https://en.wikipedia.org/wiki/Jeremy_Rifkin, visited 07/27/2015<br>
[2] https://youtube.com/watch?v=XtQoPcscFts, "The Energy Internet Explained, with Jeremy Rifkin"<br>
[2a] http://spectrum.ieee.org/tech-talk/telecom/internet/jeremy-rifkin-on-the-internet-of-things-and-the-next-industrial-revolution, visited 07/27/2015<br>
[2b] https://www.youtube.com/watch?v=hZiaTV6uvFQ, "Energy storage under pressure | Danielle Fong | TEDxCERN", visited 07/28/2015
[3] http://vlex.physik.uni-oldenburg.de/42370.html, Institut für Physik Universität Oldenburg, visited 07/27/2015<br>
[3a] http://www.ted.com/talks/eric_giler_demos_wireless_electricity, "Eric Giler:
A demo of wireless electricity", visited 07/27/2015<br>
[4] http://phys.org/news/2015-03-japan-space-scientists-wireless-energy.html, visited 07/27/2015<br>
[5] http://www.renewableenergyworld.com/articles/2014/07/hydrogen-energy-storage-a-new-solution-to-the-renewable-energy-intermittency-problem.html, "Hydrogen Energy Storage: A New Solution To the Renewable Energy Intermittency Problem", visited 27/7/2015<br>
