Space Physics
=============

GRAVITY
-------

In space there is no gravity, unless you make it artificially by centrifugal force or thrust.

ARTIFICIAL GRAVITY
~~~~~~~~~~~~~~~~~~

There are two methods to generate artificial gravity: **Thrust** and **Centrifugal force**.

**Thrust** is the easiest one (but not the cheapest): It consists of maintaining a constant acceleration in a vessel, thus pushing “down” everything inside it. If the spacecraft is accelerating at 0.5G, everyone aboard would be experiencing a force pushing them down (or against the thrust vector) akin to 0.5 gravity. This is not a reliable source of artificial gravity for two reasons:

- **You can’t accelerate forever**; eventually you need to stop (ideally, when you reach your destination). The most common maneuver, the "Brachistochrone", is to constantly accelerate for half the trip, then rotate and fire your thrusters in the opposite direction, decelerating (or breaking) for the second half of the trip. This would generate constant artificial gravity for the entirety of the journey, but… most vessels do a partial burn and drift (in Zero-G) for a portion of the trip (to save fuel and propellant).
- **Fuel isn’t cheap**, and mass ratio must be taken into account. Some advanced fusion engines (with Deuterium-Helium3 fuel cycles) are extremely efficient and have seen incredible performance breakthroughs, but for most other commonly used engines, this option might be prohibitive (economically or physically).

**Centrifugal Force** is achieved by rotating the vessel or habitat around a central axis. This way, everything inside it would experience a force pushing it towards the outside boundaries (away from the center). This is the most commonly used method of artificial gravity in most space stations and even some vessels. The main drawback is the *Coriolis Effect* (a sideways motion created by the spin). The smaller the vessel (or the closer to the central axis), the more pronounced this effect is, and it can be powerful enough to cause dizziness or nausea (represented as a Condition like ``Coriolis vertigo (Mild, -1)``). This force can also cause unwanted physical side-effects, for example, throwing a ball spinward would make it fall faster, but throwing it anti-spinward would make it float for longer. Pouring water out of a kettle will cause the water to fall slightly anti-spinward, etc.

ZERO GRAVITY
~~~~~~~~~~~~

The human anatomy (specially if grown on Earth, Mars, or other gravity wells) is not made for microgravity, or Zero-G. The body slowly deteriorates and it can be fatal after 5 years if no measures are taken. This is represented mechanically by the character gaining an increasing number of stacking Conditions over time, specially after 1 year of exposure [#]_.

.. [#] Due to the amount of Conditions, the character becomes unplayable. Retire it and create a new one.

.. csv-table:: Extended effects of Zero-G in the human body
   :header: "Time in Zero-G","Effect / Condition"
   :widths: 20, 80

   "instant","Fluids pool in the chest and face, making you puffy and uncomfortable. 
   
   Gain ``Zero-G discomfort (Mild, -1)``"
   "1 week","Lower blood pressure and loss of potassium and liquids. 
   
   Gain ``Zero-G dehydration (Mild, -1)``"
   "1 month","Muscle atrophy and reduced body mass. 
   
   Gain ``Zero-G atrophy (Moderate, -3)``"
   "3 months","Bones begin to lose calcium, becoming weak and brittle. 
   
   Gain ``Spaceflight osteopenia (Severe, -5)``"
   "1 year","Bodily functions begin to collapse; You are probably blind, and are quasi-paralysed or prostrate without some sort of assistance."
   "5 years","Your body completely collapses. You will imminently die of cardiac arrest, circulatory system collapse, ischemic stroke or similar causes."


**LOW GRAVITY**: If exposed to gravity greater than 0 but lower than half your :hoverxref:`native gravity <nativegravity>`, the effects of Zero-G still apply, but take 4X the time to kick in.

.. figure:: /_static/images/0G-effects.png

These effects can be countered or postponed by doing one or more of the following:

.. csv-table:: 
   :header: "Preventive Action","Outcome"
   :widths: 20, 80

   "**Taking drugs**
   
   (calcium tabs, water retention aids, vasoconstrictors, etc)", "Delay most Zero-G health effects, for a maximum of 1 month (after that, effects start to apply as normal). Excessive use might lead to addiction or dependency."
   "**Physical Exercise**
   
   (treadmill, cycling, weight-pushing, muscle stress, etc)", "Ignore all Zero-G health effects.

   - At first, 1 hour/day is enough.
   - After 1 month, 2 hours/day are required.
   - After 3 months, 4 hours/day are required.
   - After 6 months, even constant exercise won’t be enough, and zero-g effects will start to occur as normal."
   "**Exposure to Gravity**

   (thrust, centrifugal force or a true gravity well)", "At least 1 hour of your native gravity for every 3 days in Zero-G is enough to “pause” Zero-G health deterioration completely.
   
   If under lower Gs, adjust the hours/days relation accordingly (i.e. at least 2hs of [½ native G] per 3 days in Zero-G)." 
   "**Tensile Strength Clothing**

   (G-suits, built-in elastic strap, “penguin suits”, etc)", "By forcing the body into positions which cause the muscles to exert extra force to counteract its resistance, these suits help delay the effects of Zero-G health deterioration by +50% (i.e. it would take one and a half weeks to suffer **dehydration**, one and a half months to suffer **atrophy**, etc)."
   "**Zero-G Experience**

   (Having lived most of your life in Zero-G environments, years of experience working in microgravity, etc)", "Ignore the basic effects of Zero-G **discomfort**. The puffiness still happens; you are just accustomed to it enough that it doesn’t affect you at all."

.. tip::

 The Condition ``Zero-G discomfort (Mild, -1)`` (which is automatically gained by anyone exposed to Zero-G for the first time) also represents the awkwardness of operating in free-fall: The need to accustom oneself to use anchor points, hand-holds, tethers or thrusters; the miscalculations of your body movements and misjudgements in applied strength; the inexperience in constantly being upside down or bumping into everything; etc. Thus, having **Zero-G Experience** cancels this Condition altogether.

