# Lifebox

## Project description

Lifebox is a virtual ecosystem. Inside the LifeBox you can find two species. Both species have a set of parameters that defines how they can evolve inside the virtual ecosystem. You can change each parameter of both species individually.

Both species need to gather energy from the green mana to grow, reproduce and survive. This mana also has a set of parameters that defines its behavior inside the LifeBox ecosystem.

The goal of the project is to discover the basic concepts of biology through the experimentation, viewing the consequences of your actions and trying to find the way to balance the ecosystem changing the parameters of the LifeBox species and mana.

## The green ‘mana’ parameters

**LIFE:** Life expectancy of species individuals. High values are better.

**REPRODUCTION:** Reproduction capability of species individuals. High values are better.

**GENERATION:** Energy generation of green species individuals. High values are better.

## The species parameters

**LIFE:** Life expectancy of species individuals. High values are better.

**REPRODUCTION:** Reproduction capability of species individuals. High values are better.

**EFFICIENCY:** Energy consumption of species individuals. Low values are better.

**GATHERING:** Energy gathering of species individuals from green species individuals. High values are better.

## Lifebox webapp

**/web/*:**

You can control the lifebox simulation in real time by the lifebox webapp.

## Lifebox scripts

**lifebox.py:**

Main lifebox script, reads data from 'controllerdata' file and runs the simulation.

**readanalog.py:**

Reads data from Arduino based lifebox controller and saves it to 'controllerdata'.

**readwebapp.py:**

Reads data from webapp and saves it to 'controllerdata'.

## Lifebox Android app

You can download the Lifebox Information App from Google Play.

https://play.google.com/store/apps/details?id=com.app.lifeboxinformation&gl=ES

You can also download the application source code from the LifeboxInformationApp folder from the repo.
 
