Combat and Damage
-----------------

.. figure:: /_static/images/rpg-image-11.jpg

   art © `Aleksi Briclot <https://www.artstation.com/aleksi>`_

.. _base-damage:

Base Damage
===========

Weapons have a "base damage" listed as part of their description or stats. When you roll the die and succeed (result > Difficulty), this base damage is applied first to the :hoverxref:`Effect <effect>`, and then you count the reminder of the positive effect. 

For example, if a Weapon is listed as ``Mundane long sword (+1) - Base DMG 3``, and you roll against a Difficulty of 12 (let's say you've obtained a total of 15), your total Positive Effect would be: **3** (the weapons, Base DMG) **+ 3** (the Positive Effect) **= 6**.

Thus, weapons can have two "axes" of stats, the typical :hoverxref:`Item Bonus <items>`, and the **Base DMG**.

Sample Weapon DMGs
~~~~~~~~~~~~~~~~~~

+--------------------------------------------+----------+
| Weapon Type                                | Base DMG |
+============================================+==========+
| dagger, sap, staff, short-bow              |     1    |
+--------------------------------------------+----------+
| short-sword, mace, short-axe, bow          |     2    |
+--------------------------------------------+----------+
| long-sword, warhammer, great-axe, long-bow |     3    |
+--------------------------------------------+----------+
| zweihänder, daiklaive                      |     4    |
+--------------------------------------------+----------+

Uncertain Death
===============

When a character's :hoverxref:`HP <heartpoints>` are reduced to 0 or less (from a source of damage that could be deadly), they are defeated, taken out, fall unconcious, etc, but it is still **uncertain** if they are dead or alive.

Place a d20 inside an opaque cup, shake it and place it face down on the table, without revealing the result. Once another ally goes to the character and checks their vitals, then you uncover the die and announce the result, which is modified by their current negative HP [#]_.

.. [#] The lower into the negatives the character was, the more likely they are dead. If they had exactly 0 HP, then their chances are 50/50. But if they had, for example, -4 HP, then the die result must be modified by -4, which is a -20% probability, and ends in a 30% chance of surviving.

- **9 or less**: The character is dead.
- **10 or more**: The character is unconcious, but still alive.

.. tip::
   
   If a character is still alive, you can give them a :hoverxref:`Condition <conditions>` that the character got instead of dying, so that they don't get out of it unscathed. The severity of the Condition is left at GM's discretion depending on the amount of HP lost and contextual circumstances.

   Some GMs don't give Conditions to characters that survive the **Uncertain Death** check *on purpose*—this emphasises the gamble of it: You :hoverxref:`could've taken a Condition instead of losing HP <damageandconditions>` and risking death, but you chose to risk a roll, which is *all or nothing*.

.. _instinct-checks:

Instinct Checks
===============

.. figure:: /_static/images/rpg-image-15.jpg

   art © `Geoffroy Thoorens <https://www.artstation.com/djahal>`_

**Instinct Checks** are triggered in situations of extreme fear or pain, or life-threatening damage or danger. The result dictates if you can maintain your composure or are forced to act in a certain way. Roll and add any modifiers (skills/items/abilities/etc) that would help keeping your cool in the specific situation, vs a :hoverxref:`Difficulty Level <difficulty>` according to the gravity of the context [#]_:

.. [#] The GM defines the Difficulty Level based on the fictional context, without taking into account the affected character (they will use their own modifiers for the dice roll, that represent their tolerance or instinctual abilities). The GM can increase the Difficulty Level for subsequent Instinct Checks if they deem the situation being increasingly more dire.

.. csv-table:: Instinct Check Results
 :widths: 20, 80

   "**CRITICAL FAILURE**", "Gain a ``Stressed (Severe, -5)`` Condition AND the GM picks your character’s behavior from  ``Fight``, ``Flight``, ``Freeze`` or ``Fawn``."
   "**FAILURE**", "Gain a ``Troubled (Moderate, -3)`` Condition AND choose a behavior from ``Fight``, ``Flight``, ``Freeze`` or ``Fawn``."
   "**SUCCESS**", "You maintain your composure and are not adversely affected by the situation."
   "**CRITICAL SUCCESS**", "You maintain your composure, and gain +1 for further **Instinct Checks** during the scene."

- **Fight**: lash out violently; attack anyone (friend or foe)
- **Flight**: Escape ASAP; distance from / block the danger
- **Freeze**: Become immobilized; in shock; unable to act
- **Fawn**: Surrender; yield; submit to (or ally with) the enemy