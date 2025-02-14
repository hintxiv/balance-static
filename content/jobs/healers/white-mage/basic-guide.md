---
title: White Mage Basic Guide
card_header_image: /img/jobs/whm/basic.png
authors:
  - Balance-WHM-Staff
patch: "5.58"
lastmod: 2021-10-29T03:52:28.260Z
changelog:
  - date: 2021-10-29T03:52:37.749Z
    message: Created page
---
Hi there, I’m pyre and this is my long overdue guide to White Mage in Shadowbringers, one month before Endwalker release… Luckily, based on current information from the Endwalker Media Tour, most of this information will carry into Endwalker, though I will update it shortly after release. This will be a fairly short and straightforward guide that addresses the basics of WHM mechanics and play, and will be expanded upon in Endwalker.

## On healers in FFXIV…

Healing in FFXIV is quite a bit different from healing in most other MMOs, and can be a bit of a shock when picking up the role for the first time.  Healers in FFXIV spend most of their time dealing damage, and in optimized environments are capable of dealing 60% or more of the damage of a DPS.  Healing spells and abilities are extremely powerful, but often expensive or on long cooldowns, and incoming damage is often infrequent, allowing healers to deal damage while healing the party with the most efficient spells possible.

White Mage is a traditional regen-based healer with a straightforward healing kit centered around powerful direct heals that allows it to excel in reactionary environments. White Mage possesses some of the strongest burst healing options in Benediction and Cure III, and has the highest personal damage of any healer, relying entirely on its own damage instead of party buffs. Good White Mages can utilize the Lily gauge to heal the party while refunding some of the lost damage in Afflatus Misery, one of the single hardest hitting abilities in the game.

## Acronyms

**CD:** cooldown

**GCD:** Global cooldown

**oGCD:** Off-Global Cooldown Ability

**AoE:** Area of Effect

Spell and ability acronyms are included in the next section.

- - -

## Healing Spell Overview

While healers in FFXIV are far more damage oriented than you might expect, they are still healers and their primary goal is keeping the party alive.  WHM fills the “pure” healer role in FFXIV, meaning it has no spammable shields and little mitigation, instead focusing on healing raw HP via regeneration effects (Asylum, Medica II) or direct heals (Assize, Afflatus: Rapture).  A progression group will typically have one pure and one shield healer, with SCH and Nocturnal AST for the shield healer option, and WHM or Diurnal AST as the pure healer.

The biggest categories healing spells fall into are GCD and oGCD heals. You can find an overview on how GCDs and oGCDs actually function (here).

### Cure

The first heal you get and by far the least used at 80.  Cure is a small, fast heal for a low MP cost, making it only useful in situations where the speed or MP will save someone. In most cases, Cure II is strictly better as it is a larger heal and only slightly slower, albeit at a steeper MP cost.  Cure can proc Freecure, making the next Cure II free to cast, but this aspect should mostly be ignored in any content past level 30.  If you find yourself using the spell a lot past level 30, you are most likely making inefficient use of your other heals.

### Cure II

A larger, less MP efficient heal than Cure, Cure II is your standard single target GCD healing option used mostly in cases where a single person needs HP immediately, or they will die, and you have no lillies or oGCD options available. This spell mostly sees use in non-level cap dungeons where tanks will frequently exhaust your other healing options on large pulls, but is generally reserved for emergency healing at 80.

### Medica

The first AoE heal you have access to, and much like Cure, one of the least-used spells at 80.  Medica is a moderate direct GCD heal that is typically only used in cases where the party already has Medica II ticking, needs healing, isn’t stacked enough for Cure III, and you have no Lilies.  It has a larger up-front heal than Medica II (300 vs 200 potency), but that healing is made up for in a single tick of Medica II’s regen, making Medica rarely used outside emergencies.

### Medica II

Medica II is WHM’s go-to AoE GCD heal, it has a small 200 potency up-front heal and applies a regen that heals for 500 potency over 15s, for 700 total potency.  If you have party healing that cannot be covered by oGCD’s or Lilies, then Medica II is next in line.  This spell tends to be used fairly heavily on progression where the goal is to keep as many people alive as long as possible in order to see more mechanics, but as you optimize it tends to get worked out of the rotation in favor of more efficient healing and mitigation plans that allow for more Glares.

### Cure III (C3)

A large, direct, AoE heal with a small radius, Cure III excels at raidwide spam effects where the party remains stacked, however is still less healing and more MP overall than Medica II. Cure III is mostly used if the party needs to be topped immediately and Medica II is already ticking or won’t heal enough by the time damage goes out. This spell comes at a hefty 1500 MP cost, and tends to be used sparingly.

### Tetragrammaton (Tetra, Tet)

A standard oGCD direct heal, Tetra is typically used in open weave slots if someone (usually a tank) will benefit from the extra healing.

### Divine Benison (DB, Beni)

DB is our tank-upkeep tool and only true shield, and its low 30s cooldown means it is often weaved with Dia, which also needs to be refreshed every 30s. Benison is one of the lowest-priority spells, since it has the lowest potency of our oGCD’s and is often dropped in favor of larger, higher priority heals or utility spells. That said, given the relative lack of oGCDs we have, DB is still used frequently and rarely a bad option.

### Benediction (Bene)

One of the hallmark features of WHM healing, Benediction is an oGCD ability that heals for 100% of a target's max HP. Bene is often saved for Living Dead when paired with a DRK, but can be used for any immediate single target healing in most other comps. It isn’t typically necessary to use Benediction for Superbollide or Holmgang, though it can still be a good use if Benediction is available and easily weaved.

### Asylum

Asylum is a ground-targeted regen effect, and at level 78 gains a 10% healing recovery increase that affects all healing spells and abilities to anyone inside its radius, including its own healing.  Asylum is our go-to AoE oGCD healing ability and should be used as frequently as possible so long as the party needs healing and can remain in its radius for most of the duration. Ground-targeted abilities can often be tricky to weave, so Asylum is one of the few cases where a macro can be used to assist with targeting.

### Plenary Indulgence (PI, Confession)

Plenary is a bit of an odd oGCD that adds 200 direct potency to our AoE GCD heals for ten seconds (note that Medica II only gets the 200 potency on the initial heal and not every tick). PI is most powerful when it can be used in soft-enrage spam where you will get multiple GCD heals in its duration for added healing potency, but typically is used to add some healing potency to an Afflatus: Rapture cast shortly after a Dia. The need to weave it and relatively small extra heal means this ability will sit on cooldown a lot in optimized play.

### Temperance (Temp)

Temperance is for looking pretty, as well as our healing steroid and mitigation tool. Temperance has a massive 30y range, 22s+ duration, decreases damage taken by 10%, and increases GCD healing by 20%. This spell is mostly used for the mitigation, although the GCD healing boost is pretty big and should also be considered if a mechanic does require GCD healing.

### Afflatus: Solace

Lilies and their associated spells will be expanded on further on in this guide, but Solace is the first Lily heal you have access to and is essentially a free, instant Cure II, allowing for movement and weaving if needed while also refunding some of the lost damage.  This spell sees a lot of use in dungeon pulls since the tank is typically the only player taking significant damage, but is rarely used outside emergencies in Savage and Ultimate since it shares the Lily charges with Rapture.

### Afflatus: Rapture

The other Lily heal and a fundamental component of WHM healing at 80; Rapture is a free, instant, and larger radius Medica that allows for moving and weaving while also refunding some damage via the Lily system. Ideal use of Rapture is to cover movement, weave oGCDs, and heal the party a bit, or to blow it in downtime for free Misery casts. Once again, the Lily system will be expanded on farther below.

- - -

## Damage Spell overview

Healers in FFXIV spend most of their time dealing damage, not healing, even in some of the most healing intensive phases in the game, and an optimized healer duo can contribute 20% or more of the total damage in an optimized party. Healer damage rotations are extremely simple, consisting mostly of a single DoT, a single filler, and a couple damaging oGCDs to weave.  

### Glare / Stone

Our basic filler nuke spell, you cast this whenever there are one or two enemies, and you have nothing better to cast. At 300 potency, Glare is the strongest healer filler spell and most of any raid fight will be spent casting Glare. Most of WHM's optimization will boil down to casting more Glares. There’s a reason we are sometimes referred to as Glare Mages.

### Holy

The AoE nuke spell; used in place of Glare when there are three or more enemies. Holy has a four second stun that makes it godlike for large dungeon pulls, but it rarely sees significant use in raid fights, since unlike other healers, Holy is not worth casting in a two target phase (Note: not the case at lower levels since Stone I-IV has lower potency than Glare). The spell does see some use in fights with downtime since Holy has a cast time and does not require a target, meaning that with good timing you can get some free extra damage if your cast ends just as the boss reappears. Like all stuns in game, Holy’s stun is subject to diminishing returns (first is 4s, 2nd 2s, 3rd 1s), but is capable of chain stunning mobs for up to 7s which can essentially act as a free invuln for the tank in a large pull, allowing them to delay mitigation for later parts of the pull.

### Dia / Aero

Our basic DoT spell that should be kept up at almost all times in raid fights.  Dia is instant cast, lasts 30s, deals 120 potency damage on cast, and applies a damage-over time effect that deals 60 potency every three seconds, for a total potency of 720 (120 + 10 x 60).  As one of our few instant-cast spells, we typically plan most of our oGCD use around the Dia refresh timer. The up-front damage does make it a bit of a movement tool, but it’s basically the last resort for movement since it will throw off your Assize and PoM alignment.

### Assize

Assize is an AoE oGCD damage and healing spell that also restores MP. Assize is cast on cooldown in almost every scenario, though could be delayed if it doesn’t cost you a use. While it does decent healing, we mainly use it for damage and MP restoration, and it is almost never held specifically for healing, although you can and should move other oGCD heals around if they can instead be covered by an Assize you were going to use anyways. The 45s cooldown unfortunately only aligns with the Dia refresh on every other use, so it is sometimes hard-clipped after a Glare if it doesn’t align with a Lily use.

### Presence of Mind (PoM)

This is our burst cooldown, it increases GCD speed and cast time by 20% for its duration (it does not affect Dia or regens), allowing you to get a couple extra Glares off per fight. It is typically used close to on CD, although is often delayed to better align with buffs or potions since its wacky 2:30 cooldown means it rarely naturally aligns with buff windows.

### Afflatus: Misery

A gigantic 900 potency nuke that can be used after using three Afflatus (Lily) heals. The Lily system will be explained in more detail further in this guide, but Afflatus: Misery specifically is typically used either to cover movement that cannot be handled by Swiftcast or Dia, for some extra damage in buff windows (e.g. Chain Stratagem, Trick Attack, etc.), or for some extra weave space.

- - -

## Utility Spells and Abilities

### Swiftcast (swift)

Swiftcast makes the next spell instant, useful in prog on Raise and in optimization for maintaining casting uptime by using it on Glare. This ability is not a damage gain if you are not moving, unless you can gain a Glare before the boss phases or dies, as Glare and Holy both use an entire GCD regardless of whether they are swift-casted or not.

### Lucid Dreaming (LD)

Standard healer MP restoration button. This spell restores 500 extra MP per MP tick for 21s, for a total of 3500 extra MP per use. This is typically used pretty close to on cooldown for optimization, although can be delayed if you happen to have excess Piety/MP or higher priority spells.

### Thin Air (TA)

This ability removes the MP cost for all spells for 12s, including GCD heals and Raise. For most levels of play, Thin Air can be saved for MP-intensive moments, usually Raises or GCD heals, but as you drop Piety while working towards speedkill oriented sets, it is more frequently used on Glares as an MP saving tool.

### Raise

Raise is our resurrection tool, it has a very long eight second cast time and costs almost 1/4th of your MP. Resurrected targets spawn with low HP and MP and are invulnerable to damage for five seconds, or until they use a spell, ability, or weaponskill. Raise is used frequently for recovery in all content.

### Surecast

Surecast is the caster and healer anti-knockback tool, and it comes with the small added bonus of preventing spell interruption for its duration, although the latter effect is very rarely utilized in PvE content. Knockback mechanics are a staple of Savage and Ultimate raiding, and as a caster, WHM can use Surecast to maintain uptime during some (but not all) of these mechanics.

### Rescue

Rescue moves another player to your position after a brief delay. This ability can be used to rescue your party member from avoidable damage if your reaction time is good enough, but is sometimes also used for uptime in very specific mechanics.

### Esuna

Esuna cleanses a single debuff from your target and Esuna-able debuffs have a white line above them. Esuna sees sporadic use in Savage and Ultimates, but low level dungeons have a lot of Esuna-able debuffs including diseases, slows, and bleeds.

### Repose

Puts an enemy to sleep for 30s, not really used outside deep dungeons.

### Fluid Aura

Binds your target, also not really used outside deep dungeons (and being removed in 6.0).

- - -

## Lilies

The Lily system has functioned in a few different ways since its implementation but in Shadowbringers it functions as a means to cast free, instant GCD heals while refunding some of the lost Glare damage in Afflatus Misery, a gigantic, pretty 900 potency nuke.

### Lily Gauge

Every 30s in combat the WHM generates a blue (or black) Lily that can be used on either Afflatus: Solace or Afflatus: Rapture.  These spells were touched on briefly above, but they are instant GCD heals that do moderate healing while allowing the WHM to move or weave. In general for raiding, Afflatus: Rapture is almost always preferred, since 300p on eight party members is simply a lot more potency than 700p on one, and tank healing can typically be covered almost entirely by oGCD heals. When Rapture or Solace are used, they add one red Lily to the gauge, and after three red Lilies are accumulated, Afflatus Misery can be used. This means that every three blue Lilies that are used, you get one Misery, or four total GCDs for 900 potency vs 1200 potency for four Glares, which is a damage loss.

The fact that Lilies are a damage loss is unintuitive and can be hard to adjust to since the gauge is right there (hopefully) in front of your face, begging to be used. That said, it does still allow for some nuanced gameplay, as they aren’t a total damage loss and a number of movement mechanics still force Lily use as we simply don’t have enough other instant-cast options to cover movement and/or healing.

### Lily Sets

When considering using a Lily, it’s important to keep in mind that Lily damage is only refunded if you can complete a Misery. Any unspent red Lilies at the end of a fight were completely wasted casts that could have been either Glares, or more GCD efficient GCD heals. As a result, it helps to think of Lilies in “sets” of three Raptures and one Misery for four GCDs and 900 potency total. As you optimize fights, you will work Afflatus spells out of the healing plan in favor of Glares, but you still want a whole number of Lily sets per fight.

Red Lilies | Lilies needed to complete misery | Glare Potency | Misery potency - Glare Potency

0 | 3 | 1200 | -300

1 | 2 | 900 | 0

2 | 1 | 600 | +300

### Downtime Lilies

Unlike Lilies used in uptime, Lilies used in downtime are a strict damage potency gain since they still give red Lilies and don’t have the typical cost of one Glare. Any Lilies you can afford to spend in downtime should be spent in downtime unless absolutely needed to cover movement or healing in the next uptime phase.

- - -

## Opener and Rotation

Opener: Potion, Prepull Glare, Dia, Assize, PoM, Glare...

The WHM opener is extremely simple and straightforward as we have only two oGCD damage abilities and two free weave slots. Assize is used first, because you want PoM to cover as many GCDs as possible. There are some opener variations with Swiftcast that allow for one more total weave slot in the event Temperance or Asylum is needed shortly after the pull, but these use cases are quite niche and can usually be resolved in ways that don’t lock us out of Swiftcast for the first minute of a fight.

### Rotation

Glare, Glare, Glare, Glare, Glare, Glare…

Jokes aside, the vast majority of your rotation is in fact just pressing Glare until you need to refresh Dia as long as there is no healing to be done.  While this seems simple… Well, yeah -- it’s simple.  Ideal Dia refresh is immediately as the previous Dia falls off, but PoM and hard-clip Assizes tend to throw off any GCD alignment we have, so Dia can be refreshed anywhere under three seconds remaining depending on your GCD.

WHM has two major DPS oGCDs: Assize and Presence of Mind. Assize is almost always used on cooldown in uptime since it has a fairly short 45s cooldown and delaying it will often cause you to lose a use in a fight unless you have a very specific kill time in mind.  The 45s CD is a bit awkward since it will only line up with a Dia refresh on every other use, or every 90s. You’ll generally want to use a Lily to weave the Assize uses that don’t align with Dia refreshes, but in the event you’re saving Lilies for movement, it’s worth it to just hard-clip Assize instead since at 400 potency easily outweighs the ~100p loss from clipping Glare (1/3rd of a 300p cast).

PoM also has an awkward cooldown of 150s, meaning it won’t naturally align with two minute or three minute buffs outside the opener if used on cooldown. PoM is typically used close to on cooldown to maximize uses, but PoM uses are often delayed until buff or potions windows since it’s typically fairly easy to determine if you’ll lose a use overall in an encounter. More uses almost always beats better uses as long as you don’t have dropped casts etc while it’s running. PoM should always be used in the second weave slot to maximize the amount of GCDs covered by the haste effect.

WHM has the most limited weave space of any healer, so any time there’s a free weave space you should be looking to use something. Typical candidates are Divine Benison, Tetragramaton, and Lucid Dreaming, as they have fairly short cooldowns and are almost always useful, but higher priority abilities always take precedence.

### Movement

Movement on White Mage is by far the hardest thing to optimize, since it is arguably the most rooted job in the game with the least access to instant cast spells like SCH’s Ruin II or movement abilities like BLM’s Aetherial Manipulation. The instant cast spells in your arsenal are limited to Dia and the three Afflatus Spells: Solace, Rapture, and Misery, plus whatever you can Swiftcast. As a result, WHM is heavily reliant on proper slidecasting to maximize casting uptime. Slidecasting refers to the ability to move in the last 0.5s of any cast bar without interrupting the cast, and is an important aspect of the game for all casters.

In general, you should prioritize movement as follows:

1. Pre-position with slidecasts, or natural Dia refreshes (100% lossless when executed properly)
2. Swiftcast Glare
3. Rapture that does useful healing, Misery
4. Regen that does necessary healing (rare in Savage and below)
5. Overheal Lilies
6. Dia outside natural refresh
7. Casting nothing (do not do this)

Ideally, most of your movement is covered in ways that cost nothing; only slidecasts and natural Dia refreshes fall into this category since you are casting Glare and Dia regardless. Everything else has some sort of associated cost to move. Swiftcast costs a use of Swiftcast, Lily spells have lower average potency than Glare, overheal Lilies cost Lily gauge and could be better utilized as either healing or downtime Lilies, and Regen is strictly a lost GCD unless actually needed for healing. As a result, most of WHM optimization in endgame content comes down to prepositioning and minimizing movement as much as possible.

Extended movement mechanics will typically involve most of your instant-cast arsenal.

- - -

## Healing Spell Priority

*oGCDs > Lilies > GCD Heals*

- - -

## Party/AoE Healing

While WHM lacks the weave space and oGCD healing arsenal of SCH and AST, we still prefer to use oGCD heals to cover as much of the healing possible before resorting to Lilies or standard GCD heals. While Assize is a healing ability, it is almost always used on cooldown for damage and MP regardless of the health of the party. That said, you should still plan other healing tools around Assize use if the Assize can cover some healing in its normal usage to maximize efficient use of healing abilities.

Asylum is our primary AoE oGCD heal that should be planned given its rather long 90s cooldown. Typically, Asylum is used as a slow ticking heal between mechanics when players can easily stay inside the effect for the majority of the duration.  Party movement must be taken into account when using Asylum since it’s a ground targeted ability and the regen will not continue ticking on players that leave its radius, making it a poor choice for mechanics that will force players out of the effect, although it can still be an efficient healing choice even if you can’t stay inside the entire duration.

Afflatus Rapture is generally your next priority for any party healing that can’t be covered by oGCDs but as mentioned above, you’re still ideally using it for movement and weaving in addition to healing. It’s tempting to spam Rapture for all healing as soon as it’s needed but it’s highly recommended to wait before using it until you’re sure it’s necessary since holding off can lead to more efficient uses overall. Don’t feel obligated to use Rapture just because you’re at three Lilies and are overcapping; it’s still a damage loss to use vs. Glare if it isn’t needed to cover movement or healing.

Medica II is your highest potency AoE GCD heal, and should be your first choice when you need healing beyond what the above options can provide. All GCD heals minus Rapture and Solace have MP costs, and Medica II’s comes in at a hefty 1300MP, so overuse will put serious strain on your MP bar. GCD heals in general are excellent progression tools, as they have no cooldown and can be used to quickly top the party between mechanics and allow you to see farther into the fight, but are typically worked out of the rotation fairly quickly during optimization in favor of more GCD efficient healing tools like Lilies and oGCDs.

Cure III has higher up front healing potency than Medica II, but less total healing and a higher MP cost. Cure III is mostly an emergency button for when the party is tightly stacked and needs immediate large healing, such as during an enrage spam or for triage when the other healer has died.

- - -

## Single Target Healing

Single target healing largely follows the same priority as party healing except we have a couple additional tools at our disposal, and in most raid encounters tank damage isn’t that high.

WHM has three single target oGCD heals: Divine Benison, Tetragrammaton, and Benediction. Use of these abilities depends on how much health the potential target is missing and how much damage they are taking; the more health they are missing, the better value you get out of Benediction and Tetragrammaton compared to Divine Bension. DB is also a poor choice if the target won’t actually take damage after it’s applied. It’s tempting to weave DB with every Dia application since both should be 30s, but given that DB is the smallest heal and has a short duration, it has the lowest priority to actually cast and plan. Benediction is often planned for tankbusters, especially with Living Dead, but can also be used as an emergency heal or for any significant tank healing if nothing else is available.

Single target GCD heals are rarely needed in most Savage and lower raid content, they are essentially limited to emergency tank healing tools and are almost never used in optimization. They see more use in Ultimates, and the most use in leveling dungeons where larger pulls can exhaust all other mitigation and healing options. While Solace is technically the first GCD heal you’d reach for, given its lack of MP cost and damage refund through the Lily system, in most content you’ll either spend Lilies on Rapture or in downtime between pulls, making Solace's use pretty niche and limited to tank upkeep in dungeon pulls that went on too long. Regen is typically your first single target GCD healing option with a massive 1200 potency over 18s, with Cure II filling in for the emergency healing gaps.

Cure is an extremely niche spell in max level content, and should only really be used if you either lack the MP for Cure II or the 0.5s difference in cast time from Cure II could be the difference between life and death. It’s more MP efficient per heal than Cure II (even without accounting for Freecure) but still takes an entire GCD for a small heal.

- - -

## Stats, Melds, and Gear

Stats and gearing in FFXIV is pretty straightforward, and gearing healers is no different. Much like the gameplay, we optimize our gear sets primarily around damage, although there are a couple considerations for healing when looking at prog sets, especially for Ultimates.

Magic Damage is exclusively on weapons and is by far the most important stat for both healing and damage. Magic damage directly increases all our damage and healing.

Mind and Vitality are on every piece of gear we get, and they are the most important stats next to weapon damage. Higher item level gear always has more mind and vit than lower item level gear from the same slot. Much like magic damage, Mind increases all our damage and healing, though to a much lesser degree. Vitality is a survival stat that increases our max HP which is extremely important considering that raidwides in Savage and Ultimate will often hit for over your max HP without mitigation.

Crit increases the frequency and damage of your critical strikes, both for healing and damage. Crit is the best damage substat by a decent margin, but is unreliable as a healing boost. All of our damage and healing including HoT and DoT ticks can crit save two healing abilities: Benediction and Divine Benison. We never rely on crit heals but they still make up a decent portion of our total healing.

Spell Speed reduces your GCD and cast times and directly increases the potency of damage and healing over time effects. WHM doesn’t favor any particular GCD tiers since PoM and hard clip Assizes tend to ruin any potential DoT/GCD alignment, but SpS is still a good damage stat on average and gets even better the more of it you have since SpS tiers are constant with the relative GCD gain increases the more you have. While SpS is good for damage, it’s important to note that it will increase your MP consumption which can cause issues when running low Piety sets with high SpS.

Direct Hit increases the chance for your spells to direct hit, which deals 25% more damage than a normal hit. Direct Hit isn’t actually present on any healer gear and can only be obtained through melds, and it has no effect whatsoever on healing. Direct Hit provides slightly more damage than Determination on average so is the preferred stat over DET for optimization after prog, though prog sets may favor higher Determination for some extra healing.

Determination increases all damage and healing, it’s a very boring stat, but nearly as strong as Direct Hit while also providing a small healing boost. The extra healing it provides over Direct Hit will rarely save you healing but can add a bit of comfort to prog sets and potentially save someone that would otherwise die to very minor overkill.

Piety is the healer-specific substat and it increases our MP regen. Since it provides no direct damage or healing boost it’s typically seen as the “worst” stat although it has its place in prog where GCD healing and Raises are more frequent. BiS sets tend to minimize Piety at all costs since it provides no damage, and in some cases it can even be worth dropping significant item level to avoid taking a Piety piece.  

### Stat Priority

Magic/Weapon Damage >> Mind >> Crit > SpS = Dhit >= Det >>>>> Piety*

This priority is purely focusing on damage. Substats in FFXIV all work on tiers and efficient tiering that minimizes stat losses will often trump the basic substat order. Piety is last on this priority as it provides no damage, but if you’re in a situation where you are frequently running out of MP then grabbing more Piety is an easy way to fix that issue (though typically this is better resolved through better play). Mind and Magic damage being so high on the list means that in the vast majority of cases a high item piece of gear will be better than a low item level piece regardless of substats.

- - -

## Final Remarks

Despite taking so long to put out, this guide was still pretty rushed and I plan to address that as much as possible in the coming weeks. If you find any glaring mistakes or have suggestions for this guide or future guides, please feel free to let me know and I will attempt to address them as quickly as possible. See you in Endwalker!