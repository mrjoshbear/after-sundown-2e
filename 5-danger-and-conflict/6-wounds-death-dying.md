## Wounds
_"Okay, that hurt."_

When a character would take damage, they are usually allowed to soak that
damage. This involves rolling a Resistance Test (normally Strength), with the
hits subtracted from the incoming damage. If the damage is reduced to zero, the
character takes no perceptible harm, otherwise they suffer a wound. Some number
of boxes of the character's condition monitor will be filled up. All characters
and objects have 10 boxes on their condition monitor. When boxes are filled in,
they are marked depending on the type of damage that caused the wound:

| Damage Type | Box |
|:-|:-:|
| Normal | <tt>[/]</tt> |
| Lethal | <tt>[X]</tt> |
| Aggravated | <tt>[<s>X</s>]</tt> |

For ease of accounting, the game arranges all wound marks in the order of
Aggravated, then Lethal, then Normal. As new wound marks of any type accumulate
they push lesser marks to the right of the track. If a damage mark would be
pushed off of the track entirely simply discard it. The only exception to this
is if a character's track is already entirely filled with Normal marks when you
start adding a Normal wound: in that case you should convert existing Normal
marks into Lethal marks on a one-for-one basis.

When all 10 of a character's boxes fill up with any kind of damage they are
**Incapacitated**. They might or might not be conscious, but they cannot attempt
any action that requires a dice roll, and they can at best crawl around at a
Slow speed.

* If the character's rightmost box is filled in with a forward slash
  (<tt>[/]</tt>), they are in no immediate danger (at least not from their
  wounds, being incapacitated in a place where you just _took_ a wound implies a
  certain level of urgency in most cases).
* If the character's rightmost box is filled in with a back slash
  (<tt>[\\]</tt>), they gain the Dying condition with one hour to live (see the
  [Healing and Death](healing_and_death.md) section). This usually comes
  directly from Lethal or Aggravated wounds, but note that wound marks heal
  separately so it's possible to have just the back slash itself.

A character can also suffer a Terminal wound, which is much like an
Incapacitating wound (in that all of your condition boxes will be filled up with
a mark), but the character gains the Dying condition with only 5 minutes to
live. Even a Normal damage attack can cause a Terminal wound (eg: an unlucky
rubber bullet or boxer's punch), and then someone had better be on hand with CPR
or the curtain is coming down.

| Net Damage | Wound Type | Wound Boxes |
|:----------:|:-----------|:------------|
| 1 | **P**etty Wounds | 1 Box |
| 2 | **O**rdinary Wounds | 3 Boxes |
| 3 | **S**erious Wounds | 6 Boxes |
| 4 | **I**ncapacitating Wounds | All 10 Boxes |
| 5 | **T**erminal Wounds | All 10 Boxes\* |
| 6 | **T**erminal Wounds | All 10 Boxes\* |
| 7 | **T**erminal Wounds | All 10 Boxes\* |
| 8+ | **D**eath | NA |

\* Also, you are probably going to die.

* **Petty Wounds:** A scratch. Will stop bleeding in a minute, and heal
  completely in a day. May still get infected or transmit poison.
* **Ordinary Wounds:** These are painful and physically debilitating, but they
  generally heal up without much more than a discoloration at the spot, though
  they will take many days to do so.
* **Serious Wounds:** People who see a serious wound inflicted generally wince,
  and the agony and pure physical hampering it causes will generally strike
  mortal terror into the sane.
* **Incapacitating Wounds:** An incapacitating wound is called that because it
  incapacitates the victim. They may or may not lose consciousness, but they
  will be unable to stand even if they are able to keep their eyes open.
* **Terminal Wounds:** Your ass is dying. Not dead, but nothing short of a
  miracle and a pair of lightning paddles is going to save you now.
* **Death:** A character who receives 8 unsoaked damage from a single attack
  simply dies outright. Feel free to describe graphic injuries such as exploding
  heads and bodies torn in half.

### Damage Penalties

When a character has been _recently_ damaged, their ability to act is extremely
impaired. The character's actions take a penalty equal to the number of boxes on
their condition monitor that have a forward slash (<tt>[/]</tt>). This includes
any Normal (<tt>[/]</tt>), Lethal (<tt>[X]</tt>) or Aggravated
(<tt>[<s>X</s>]</tt>) wound boxes.

For every point that a character's Willpower exceeds 2, they can ignore one
point of wound penalty. For example, a character with a Willpower of 4 can
ignore the wound penalties imposed by 2 of their boxes.

A character with the Indomitably power ignores wound penalties completely.

## Healing and Death
_Good as new<br />
...or not..._

When characters are injured, there are two possibilities: they can either get better or not. Medically speaking, injured tissue can resolve into healed or regenerated tissue, it can resolve into a scar, or it can die. This is actually much farther in-depth than we care to go into.

When a character is given time to heal, they reduce the number of boxes that are filled in with a type of wound mark by 2. The character must also succeed on a Healing Test or the damage will fester: Normal or Lethal marked healed will add a mark of the next higher damage type, and Aggravated marks will heal only 1 mark instead of 2. Note that when a wound festers on a character who's already Incapacitated it can potentially send them into a Dying state, as normal for taking new damage marks. The time required for natural healing depends on the type of wound.

| Wounds | Symbol | Healing Time |
|:-------|:------:|:-------------|
| Normal | <tt>[/]</tt> | 20 minutes |
| Lethal | <tt>[\\]</tt> | 1 day |
| Aggravated | <tt>[<s> </s>]</tt> | 3 Days |

If a character is running around being the Action Man, they don't heal at all. Healing doesn't really happen until the character takes some time off from ninja flips and car chases. The exception is characters who have suffered Incapacitating or Terminal injuries, who start the cycle of healing and possible death right away.

If a character's entire track is filled, the character's healing timeframe is increased by one step until they have at least one box that has no wounds in it. Normal marks will take 1 hour to heal, Lethal marks will take 3 days to heal, and Aggravated marks will take an entire week to heal.

### Sample Healing

Assuming that a character were to _fail_ all of their Healing Tests during their
rest, their damage track would change as follows:

| Time Passed | Condition Track | Notes |
|:-|:-:|:-|
| Starting | <tt>[/][/][/][/][/][/][/][/][ ][ ]</tt> | Start with 8 <tt>[/]</tt>
| 20 minutes | <tt>[X][/][/][/][/][/][ ][ ][ ][ ]</tt> | Heal 2 <tt>[/]</tt>, add 1 <tt>[\\]</tt>
| 40 minutes | <tt>[X][X][/][/][ ][ ][ ][ ][ ][ ]</tt> | "
| 60 minutes | <tt>[X][X][\\][ ][ ][ ][ ][ ][ ][ ]</tt> | "
| 80 minutes | <tt>[\\][\\][\\][\\][ ][ ][ ][ ][ ][ ]</tt> | "
| 1 day | <tt>[<s>\\</s>][\\][ ][ ][ ][ ][ ][ ][ ][ ]</tt> | Heal 2 <tt>[\\]</tt>, add 1 <tt>[<s> </s>]</tt>
| 2 days | <tt>[<s> </s>][<s> </s>][ ][ ][ ][ ][ ][ ][ ][ ]</tt> | "
| 5 days | <tt>[<s> </s>][ ][ ][ ][ ][ ][ ][ ][ ][ ]</tt> | Heal only 1 <tt>[<s> </s>]</tt>
| 8 days | <tt>[ ][ ][ ][ ][ ][ ][ ][ ][ ][ ]</tt> | Finally fully healthy

### Dying and Stabilization

When a character is in a Dying state, the condition must be removed in time ("stabilizing" their condition) or they die.

 * The character can spend an Edge to automatically stabilize.
 * The character without Edge still gets to roll a Healing Test to stabilize.
 * Someone else can apply First Aid to stabilize the character.

When a Healing Test or First Aid is involved, a result of 1 or 2 hits increases the timer on the Dying condition by either 20 minutes or 1 hour respectively. This allows time for the character to potentially be moved to a place with a better shot at a final test before they die. A result of 3 hits or more causes the character to stabilize right away.

Characters with a Terminal Wound will normally die within 5 minutes. This is not normally enough time to allow for a Healing Test. However, Dying characters are always allowed to make at least one final Healing Test before their Dying timer runs out.

A character who is already Dying can also have their death hastened with further injury. Once the character's rightmost wound box is filled with a Lethal or Aggravated mark, additional wounds accumulate towards a threshold of outright killing the target.

 * Incapacitating or Terminal wounds add 2 towards a character's Death Threshold.
 * Any other wound adds 1.

A character's Death Threshold limit is equal to their Willpower, though this can be increased by knowing Lure of Destruction magic. Yes, this all means that once someone is already on death's door, it takes quite a few extra bullets to push them through it - it's not like they are going to go _into_ shock at that point.

### The Healing Test

When a character is Healing they will often need to make a Healing Test. This can be called for as either a part of natural healing to prevent wound marks from festering, or when trying to prevent the Dying condition from ending the character's life.

A Healing Test is Edge + Survival, modified by the local conditions. If another character is on hand to provide medical care their Logic + Medicine works as a Teamwork Test with the character's own roll (whoever has the smaller dice pool counts as the assistant).

| Conditions are... | Healing Modifier |
|:------------------|:----------------:|
| Dangerous | -2 |
| Distressing | +0 |
| Restful | +1 |
| Sanitary | +2 |
| Awesome | +4 |

### First Aid

When a character is trained in first aid, they can reduce the amount of damage on someone substantially. This is pretty much a one-time deal and has to be performed within the "golden hour" of the injury (an hour from when the patient was injured, not an hour from first medical contact). First aid is a Logic + Medicine test. 1 hit removes 2 forward slashes, 2 hits removes 2 back slashes, 3 hits remove 2 dashes, and any additional hits remove 1 mark of each type. So, a 5 hit First Aid test would remove 4 marks of each type.

If the victim is currently Dying you must first put a stop to that. This is a Threshold 3 test. Any Net Hits will also remove wound 1 wound mark of each type.

Perhaps the biggest advantage of First Aid is the _time_ it takes to make the first healing test during medical treatment: one time frame shorter than usual for the left-most injury type in the wound track. So it's only 1 minute to rouse someone from Normal Damage, 5 minutes to treat Lethal Damage, and 20 minutes to treat Aggravated damage.

### Being Dead
_"Okay, **now** we go through the pockets looking for loose change."_

Characters in horror die from time to time. Sometimes a character will end up dying several times, because After Sundown posits ghastly life after death and even has magical ways to restore life. When a character dies, all of their powers that cost Power Points to activate or which otherwise last for a scene end. In addition, anything they have going that could be dispelled is dispelled with their death. A character's Power Pool is also emptied at the moment the character actually dies. Very importantly, a character's power schedule (if any) does not change just because they are dead. A Strigoi can still be fed blood to regain Power Points and a Frankenstein can still be recharged while a corpse. This usually only matters if they have the Restoration Power, but there are other ways to raise the dead, and it might be important that they rise up with a power reserve on hand.

The dead may also come back as Ghosts, whether they are Luminaries or Extras. In After Sundown, no one becomes a Ghost until they've been dead for three settings of the sun. There are movies in which the spirit is left standing there as the body hits the floor, and there are movies in which the spirit wakes up having been dead and buried for a couple days. After Sundown's assumed setting is the latter.

Sometimes a player may want to continue their character as a Wraith rather than start a new character or have their character restored to life. This is a workable storyline, but it is fraught with peril because Wraiths are not normally considered playable (being constantly insubstantial while outside the Gloom). If the players agree, the character can be converted into a Wraith, with their powers traded out for the basic Wraith abilities, starting what is in essence a new Origin Story. Being a Wraith should not be a license to print superpowers, so the new powers that Wraiths get should replace some of the abilities they already had rather than piling on.
