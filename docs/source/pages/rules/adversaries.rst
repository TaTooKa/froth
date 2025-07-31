.. _adversaries:

Adversaries
-----------

Adversaries (monsters, obstacles), just like characters, also have a :hoverxref:`Level <level>`, and an amount of :hoverxref:`HP <heartpoints>` that varies with that level.

Adversaries can also have :hoverxref:`Bonuses or Maluses <bonusesmaluses>` that affect dice rolls or Difficulty as usual.

Adversaries can be sentient opponents, but they could also be obstacles of some sort. For example, a *locked door* could be represented by the GM by setting a Level (which defines its Difficulty to be unlocked). If the lock is of Level 3, then a character needs to roll over a Difficulty of 13, and reduce its HP of 13 to 0 in order to successfully unlock it (this might take several turns or different attempts, which is intended).

.. admonition:: Symmetrical rolls

   When a character attacks an adversary, the Difficulty is equal to the base of **10 + the adversary’s level** (+Bonuses/-Maluses that adversary might have). A :hoverxref:`Positive Effect <effect>` reduces the adversary’s HP. A :hoverxref:`Negative Effect <effect>` might mean that the adversary counterattacks and hurts the character’s HP by that amount.

   When a character is attacked, the adversary rolls (+Bonuses/-Maluses of that adversary) against a Difficulty of **10 + the character's Level** (+Bonuses/-Maluses of the character).  Again, the difference in Effect usually translates to HP lost by one of those sides of the conflict. **OR** the character can roll against a Difficulty set by **10 + the adversary's level** (+Bonuses/-Maluses that adversary might have).

   This means that rolls are symmetrical; The game can be "player-facing" (in which only the players roll for their characters, both to attack and defend), or it can be played as traditionally, with the GM also rolling for the Adversaries against a Difficulty set by the Character (and their level, and any other relevant mods).


Adversary Types
~~~~~~~~~~~~~~~

Adversaries come in one of three types: **Minion**, **regular** or **Nemesis**.

A **Minion** is an adversary or minor obstacle that is easier to defeat or overcome. They have max HP equal to their Level.  They are useful as disposable enemies like goons and "cannon-fodder", or as simple obstacles like a stuck door, a simple lock to pick, etc.

A **regular** Adversary or obstacle, just like a normal character, has max HP equal to **10 + Level**. This is the default for "involved challenges", as it forces characters to make several attempts against them, until all of their HP are depleted.

A **Nemesis** is an important adversary that is harder to take down, or a notorious obstacle that takes much more effort to bypass. They have double the usual HP. For instance, a Dragon Nemesis of Level 4 would have 28 HP (2 x 14, which would be the default value for regular adversaries of 4th Level).

.. _challenges:

.. tip::

   The GM can represent any type of **challenge** as an Adversary (a puzzle to solve, a chase, a social debate) by abstracting it with a Level and a type (minion/regular/nemesis) and using its HP as its duration.

Sample Adversaries
~~~~~~~~~~~~~~~~~~

.. list-table::
   :widths: 50, 50

   * - .. container:: adversary1

            | **Goblin**                  
            | Level 1 - HP 11             
            | ``Mundane chainmail armor (+1)``
            | ``Mundane short sword (+1)``    

            | **Goblin Minion**       
            | Level 1 - HP 1          
            | ``Mundane short sword (+1)``

     - .. container:: adversary2

            | **Ork**                    
            | Level 2 - HP 12            
            | ``Mundane leather armor (+1)`` 
            | ``Expert Melee Combatant (+3)``
            | ``Mundane Falchion (+1)``      

            | **Troll Nemesis**      
            | Level 1 - HP 22        
            | ``Mundane Big Club (+1)``  
            | ``Mundane Thick Skin (+1)``