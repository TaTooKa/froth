Space Travel
============

.. figure:: /_static/images/rpg-image-24.jpg

   art © `Maciej Rebisz <https://www.artstation.com/mac>`_


Traveling through space is costly, but in the 22nd century, humanity’s advancements in rocket science, nuclear fusion and material technology allow for extremely fast spacecraft and very efficient fuel. With diverse engines capable of thrust in the order of Kilo and Mega Newtons, vessels can get from planetary system to planetary system in a matter of days (instead of months or years), and/or sustain artificial gravity by maintaining constant thrust, provided the crew can afford the fuel costs.

Engine types range from *Nuclear Thermal*, which uses a nuclear reactor to heat a propellant like Liquid Hydrogen or Ammonia and ejects it through the exhaust nozzle to generate thrust, to *Fusion Drives* that use Deuterium, Tritium or Trilium (₃He) for Reaction and propellant.

To simplify matters and don’t bog gametime, the Ships detailed in the Spacecraft section (the most common models in the Solar System) have a listed value of MΔv (Max DeltaV), in Km/s or Mm/s. This represents the total budget for all the changes in velocity a ship would do, by taking into account the engine thrust capabilities, exhaust velocity, and wet and dry mass (ship’s mass with a full tank vs an empty tank). All of these variables are already pre-calculated into the Δv budgets listed in this chapter, for simplicity and expedience.

Fuel Consumption
----------------

Instead of counting fuel tons, it’s easier to calculate costs of Δv, in m/s (usually in the order of Km/s or Mm/s). When planning for a trip, consult in the Travel Time+Δv cost tables to see if you can afford the required Δv budget (must be less than your ship’s remaining Δv budget). After arriving at your destination, subtract the spent Δv from your ship’s total. When you refuel, the ship’s Δv returns to its max DeltaV (MΔv) value.

Refuelling
----------

The only thing you have to take into account is the type of fuel/propellant your engine type uses, because when refuelling, the prices will vary a lot depending on the rarity and availability. When you refuel, divide your MΔv by your remaining Δv to get the percentage of fuel left, then subtract that from your Fuel Tank Capacity and buy the remainder in fuel tons. Or to make things easier (and if saving money is not a concern), assume you spent all of your fuel and fill the tank from 0% to 100% by paying the total cost of required fuel tons.

Traveling through Space
-----------------------

Before the current advancements in engine types, spacecraft would use every trick in the book to travel through space: Hohmann Transfers (Orbital assists), Oberth Maneuvers (gravity-assisted slingshots), Bi-Elliptic Transfers, etc. These saved lots of Δv in a time where the current costs were prohibitive or outright impossible. It also meant transit times were extremely long (months or even years) because of all the (literal) hoops a ship would have to do around celestial objects and the fact that they would have to wait for specific launch windows or the correct/optimal position of planets in the system.

Luckily, in the 22nd century, all of that is no longer necessary. Any space-worthy vessel has the means to basically travel in a straight line from planetary system to system, either by accelerating+coasting+decelerating, or by constantly accelerating+decelerating to their destination. All of the techniques from the past are still used from time to time, but only by specific craft or missions that can afford longer times of arrival or that don’t have the economic means to pay for better engines or their fuel (these are mostly educational or science craft from developing nations or crafty enthusiasts).

Outside of those earlier techniques, nowadays most if not all spacecraft use what is called a **Full** or **Partial Brachistochrone**.

Full Brachistochrone Transit
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The vessel accelerates at a constant **g** until the midpoint, turns around and decelerates at the same constant g until its destination. Consult the tables on the following pages of this chapter for already calculated figures and Δv costs for common transit routes and Gs.

If you wish to calculate the Δv cost and transit times on your own, you can use these kinematic formulas:

.. math:: 

   \Delta v \ cost = 2\sqrt{distance * acceleration}

.. math:: 

   Transit \ Time = 2\sqrt{\frac{distance}{acceleration}}

**Δv cost** will be in m/s; **distance** is in m; **acceleration** is in m/s; **Transit time** is in s.

.. epigraph:: Full Brachistochrone Transit Example

*A character wants to get from the Earth system to Mars (0.52 AU) at a leisure 0.5g of acceleration. The player converts those values for the calculations into metric units and gets a distance of 7,779,089,2764m and an acceleration of 4.9 m/s². Plugging those values into the aforementioned equations solves for a Δv cost of 1,235,206 m/s (1.2M m/s) and a transit time of 251,912s (70 hours, or 2.9 days).*

The advantages of a Full Brachistochrone are many: The crew is under stable gravity because of constant thrust, that they can set to a comfortable one and avoid all of the problems of long exposure to zero-G; Transit time is reduced, which is not only convenient for those in a hurry, but also reduces time exposure to background radiation and potential Solar Storms or Flares.

The main disadvantage is one of cost (Propellants and Fusion fuel are expensive), and that even the most powerful of the available craft still have their limits, making some trips at high G prohibitive (Δv cost-wise) even at full burn (if the high-G exposure doesn’t kill the crew first!).