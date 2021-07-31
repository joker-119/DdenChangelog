# DDen Modded Changelog

## All numerical values, as well as spawn locations and potentially other things are all highly configurable, and subject to change/adjustment in the future. These are just the default values that are used if no other values are defined.

## Custom Items

- `[EM-119]` An EMP Grenade. This grenade acts similar to an Implosion grenade, however when it detonates, all of the doors in the room it is in are locked open, and the lights disabled for a few seconds. If SCP-079 is present in the room, it will send him back to his spawn camera. Also disabled all speakers in the facility temporarily. 
	- Default spawn is SCP-173 containment, room blackouts last for 20s

- `[IG-119]` An Implosion Grenade. This grenade will act similar to a normal Frag grenade, however it has an extremely short fuse, and does very low damage. Upon exploding, anyone within the explosion will be quickly drawn in towards the center of the explosion for a few seconds. 
	- 50% chance to be inside SCP-012's armory room. Otherwise will be in HCZ armory. Deals 5% normal frag grenade damage, suction will last for 2.25s

- `[GL-119]` A grenade launcher. This weapon shoots grenades that explode on impact with anything, instead of bullets. Capable of firing all types of grenades, including the above custom ones. 
	- 40% chance HCZ Armory, 50% chance 049 Armory. You must have at least 1 round of 7.62 ammo to attempt to reload the weapon this is a client-side limitation. Reloading actually consumes grenades from inventory, not normal ammo. Not guaranteed to spawn.

- `[LJ-119]` An injection of lethal chemicals that, when injected, immediately kills the user. If the user happens to be the target of a currently enraged SCP-096, the SCP-096 will immediately calm down, regardless of how many other targets they may or may not have. 	
	- Spawns in locked room behind 096 spawn

- `[LC-119]` This coin, when dropped while inside the Pocket Dimension, will immediately vanish. For the remainder of the round, whenever a player enters the Pocket Dimension, the coin will spawn in front of one of the correct entrances for a few seconds before vanishing again. This effect has a cooldown. 
	- 50% in locked room by 173 spawn, otherwise in locked room by SCP-012. Appears for 2s when triggered, 2min cooldown between apperances

- `[MG-119]` This gun is modified to fire self-injecting projectile darts. When fired at friendly targets, it will heal them. When fired at SCP-049-2, it will slowly begin to 'cure' them, repeated applications will eventually revert the SCP-049-2 to their human state. Has no effect on other hostile targets. 
	- 40% in GR-18, 50% in Gate A, 50% in Gate B. Not guaranteed to spawn. Heals for ~19 per shot. Zombies require 200 healing to be revived. Zombie healing degrades over time, but multiple people can use an MG-119 to heal zombies faster.

- `[SCP-127]` A gun that slowly regenerates it's clip over time, but trying to reload it normally has no effect. 
	- Inside locked room by 173 spawn. Clip size of 12, regenerates 2 ammo every 10s

- `[SG-119]` A shotgun. Fairly self-explanatory. 
	- 60% inside LCZ Armory. 1 shot per clip, 8 pellets per shot

- `[SR-119]` A sniper rifle. Also self-explanatory. 
	- 40% HCZ Armory, otherwise MicroHID room. 1 shot per clip, 750% normal E-11 damage Long Barrel, Sniper scope and no 3rd attachment. Attachments on this weapon cannot be changed.

- `[TG-119]` This gun is also modified to fire self-injecting projectile darts. When fired at a hostile target, it will tranquilize them, rendering them unconscious for several seconds. 
	- 50% GR-18, 80% Locked room by 173 spawn. Not guaranteed to spawn. 2 shots per clip. 0 damage. 5sec tranq duration. Causes victim to drop all items. SCPs have 40% chance to resist. SCP-173 immune. Humans who are repeatidly tranq'd in a short time have an exponentially higher chance to resist each time it succeeds.

- `[Rock]` This is a rock. Left-click to melee someone in the face with it. Left-click to toss it a short distance. 
	- Is a SCP-018. Spawns in a random locker. Melee hit: 10dmg Throw hit: 20dmg. Does not bounce when thrown. Hynx's favorite item.

- `[SCP-1499]` The gas mask that teleports you to another dimension, when you put it on. 
	- 10% inside MicroHID. You are returned to where you used the item when you try to drop it in the "dimension", or after 15sec.

- `[SCP-714]` A coin that, when held in your hand, makes you invulnerable to SCP-049 and SCP-049-2. However, as you hold the coin, your stamina will slowly drain. If you run out, your health will start to drain. 
	- 50% in 049 Armory.

- `[AM-119]` Pills that, when consumed, make you forget SCP-096's face if you have recently seen it. Removing you from being one of his targets, with some side effects. 
	- Spawns in locked room behind 096 spawn. Gives you "Amnesia" effect for 10s after use.

- `[SCP-2818]` A weapon that, when fired, will convert the entire biomass of it's shooter into the ammunition it fires. 
	- Uses the shooter as the projectile. Can be re-used by other players. Kills the shooter when fired. If you hit another player, that player is also killed instantly.

- `[C4-119]` A frag-grenade with a much longer than normal fuse, that will stick to the first solid surface it comes in contact with. It can be detonated using a console command. ".detonate" while holding a Radio in your hand. 
	- Detonation range of 100meters. Must have radio in your hand to use command. Recommend keybinding command with "cmdbind LETTER .det" where LETTER is a unused letter on your keyboard.

- `[939 Infused Serum]` A unique shot of adrenaline that will, when injected, allow the user to see sounds similar to how SCP-939 does for a short time, at the expense of diminished healing capabilities. 
	- Spawns in a random locker. Gives 50 AHP and 10 health. Gives full 939 vision for 30sec.

- `[SCP-035]` An item that takes many different forms. When picked up, the victim will start corroding quickly. If not dropped within a few seconds, the victim will become a bloodthirsty monster, hellbent on the destruction of humans. However the host is slowly damaged over time, until their body is no longer capable of functioning and they die. They will appear as a shorter, fatter SCP-049, with a very stylish hat. 
	- 15% spawn chance in a random locker. Victim has 3.5s to drop item before becoming 035. Host is damaged for 2.5/sec after transformation. 500 health. Host maintains control of their character, but are not considered an SCP. Host is able to use items and weapons. Hosts is unable to use the following items: MicroHID, SR-119


## Custom Roles

- `[SCP-575]` This keter-class SCP is a shapeless void that is very difficult to damage or contain. He drains the power from lightning systems in whatever room he is in, gets more powerful as he consumes biomatter, and is difficult to see. Shining a flashlight, or looking through a NV scope, directly at him will cause the void to condense, allowing people to damage him with small arms fire, though it is very ineffective. This SCP is, however, vulnerable to extremely bright light sources, like those emitted from flash-bang grenades. A single  flashbang can, if close enough, severely damage him, causing him to retreat to a safe place temporarily before returning to the facility. Due to the effects of this, he also loses much of the power he has gained from consuming biomatter when this occurs. Once SCP-575 has consumed enough biomatter, he is capable of causing a wide-spread blackout. During this time, some rooms in the facility will lose power. Any player caught in a blacked-out area without a light source flashlight will begin taking damage. Any humans who die to this effect, will cause SCP-575 to be healed slightly.
	- 50% chance to replace SCP-106 when a round begins with a SCP-106 spawned. 550 health. Flashbang at point blank deals 350 damage. Takes 40% damage from bullets and frag grenades.

- `[Chaos Phantom]` This specially trained and equipped Chaos soldier acts as a deep-cover infiltrator until the containment breach starts. Once the breach occurs, he sheds his disguise as a Facility Guard, and equips himself with a Sniper Rifle, SCP-127, EM-119, IG-119, a medkit, adrenaline shot, and his trusty hacking device. He is equipped with a special form of active camoflauge armor, which allows him to become virtually invisible for short periods of time. During this time he is able to use items and interact with doors and other objects without breaking his cloak, however taking damage or firing a weapon will cause the cloak to fail. There is a moderate cooldown period in which he cannot re-activate his cloak. Cloak is activated with the ".special" client console command.
	- 20% chance to replace a random guard when round starts. Does not respawn with chaos waves.

- `[NTF Medic]` A specially trained NTF Scientist that occasionally accompanies NTF units who attempt to re-take the facility. They are equipped with an MG-119, TG-119, EM-119, Medkit, Adrenaline Shot, Painkillers and an NTF Lt. Keycard. They also have a portable medical gel deployment system. Every 90sec, they are able to activate this device to heal any nearby allies for 6 health every sec. for 15sec. Any allies nearby when this 15sec period ends, will gain 45 AHP aswell. Neither the heal, nor the AHP can be applied to the medic who activated this ability, however they can be affected by other medics who are using theirs.
	- 40% chance to replace random respawned player during NTF waves.

- `[Dwarf]` Every round, there is a moderate chance a random human player will be choosen to be a Dwarf for the entire round. Dwarves are natural sprinters, as such, they do not consume stamina, though their shortness often becomes the target of mockery from others.
	- 35% chance to pick random human player when round starts. Role is maintained through respawns.

- `[Demolitionist]` A specially outfitted NTF Lt. trained in explosive ordinance. They are equipped with a GL-119, 2 C4 charges, and 5 Fragmentation Grenades.
	- 40% chance to replace random respawned player during NTF waves.

- `[Shotgunner]` A Chaos Insurgency soldier outfitted for close-quarters combat. They are equipped with an SG-119, IG-119, COM-15, Medkit, Painkillers, Adrenaline Shot and a Hacking device.
	- 40% chance to replace random respawned player during CI waves.

- `[Ballistic Zombie]` A mutated zombie that is otherwise normal, until their death, at which time their body will explode, dealing damage to anyone nearby.

- `[Pocket Dimension Zombie]` A mutated zombie that was subjected to SCP-106 too many times in their human life. They are resistant to ballistic damage, and have a small chance to teleport victims to the Pocket Dimension when they attack them.

- `[Plague Zombie]` A mutated zombie that moves slower than normal zombies, and deal less up-front damage with their attacks, however they have a large chance to infect their victims with SCP-008. Anyone who dies while infected with SCP-008 will immediately become a zombie upon death.

- `[Medic Zombie]` A former NTF Medic that, while slower, retained the ability to activate their healing ability, however now, it will heal other SCPs, instead of humans. They also do slightly less damage than normal zombies.

- `[Berzerk Zombie]` This zombie is extremely bloodthirsty. While they have less health than normal zombies, their attacks deal significantly more damage, and they gain a temporary speed boost each time they kill someone.

- `[Juggernaut Zombie]` The tank of zombies. This zombie moves more slowly than normal, however they are very difficult to kill, as they have double the health of a normal zombie.
	- All zombies have a 45% chance to be replaced with a mutation when they spawn as a zombie

## New Mechanics

- `[Chaos On Start]` There is 20% chance when a round begins that all Facility Guards will be replaced with Chaos Insurgency.
- 
- `[Spectate Void]` Spectators will see a "Void" spectate choice while dead. This will make them spectate an empty void, which allows them to hear spectator chat without having to hear proximity chat around whoever they are spectating.
- 
- `[Generator Overcharges]` When a generator completes it's activation cycle, for a few seconds the generator panel will emit sparks of electricity. Players standing too close to the generator while this occurs will be damaged for 5 damage every second and be afflicted with the "Burned" status effect for 10s. This effect causes the player affected to take increased damage from all sources.
- 
- `[Pets]` Pets are available to be given out to players. Who will have access is yet to be decided. Pets are small NPC SCPs that will follow their 'owner' around. Pets will 'run away' temporarily if the user holds their crouch button to avoid making noise or letting 939 see where hiding players are. 
	- Pets can be damaged and killed. If your pet is killed, it cannot be respawned for the rest of the round. 
	- Pets who are misbehaving can be killed by their owners with the ``.pet kill`` command in the client console.
	- Pets can be renamed by their owners with the ``.pet rename New Name Here`` command in the client console.
	- Pets roles can be changed by their owners with the ``.pet role NewRole`` command in the client console.
		- Valid roles are: Scp049, Scp0492, Scp096, Scp106, Scp173, Scp93953 and Scp93989.
	- Admins can kill misbehaving pets with the ``dden pet akill OwnerName`` command in the RA console.
	- Admins can temporarily assign players a pet for a single round with the ``dden pet assign OwnerName`` command in the RA console.

- `[Disguise]` Admins can change a player's apperance to that of another role with the ``dden disguise TargetPlayer RoleType`` command in the RA console.
	- The target will appear, to all other players, as the role the admin has entered.
	- This change is purely cosmetic.

- `[Dboi Rave]` If a round ends while there is still at least 1 Class-D personnel alive, a special victory dance song will play in honor of the Class-D. 
	- Class-D who escape will not count towards earning this special victory.

- `[Breach Announcement]` The C.A.S.S.I.E. system will sometimes make a special announcement when the round starts, indicating there has been a containment breach.
	- There are multiple announcements C.A.S.S.I.E. can make, they are chosen at random when the round begins.

- `[Zombie Prox Chat]` Zombies will now be able to use porximity chat.


## Bug Fixes

- `[Scp173 Anticheat]` The Anticheat should no longer kill SCP-173 when he attempts to move vertically while someone is looking at him.

- `[Last Teammember]` Players will now get the "You are the last teammember alive" message when they are the actual last member of their team Chaos, NTF or SCP, rather than when they are simply the last member of their role.

- `[Victory Screen]` The base-game logic for the end of round victory screen has been restored. The victory screen will no longer always display the last team standing as the victor. This means that if no Class-D escape, Chaos cannot win. If any Scientists die, NTF cannot win.

- `[SCP Swap]` SCP-049-2 will no longer be able to swap SCPs if they are created within the scpswap window.
- `[SCP Swap]` The SCP swap command now has a short delay of 10seconds.
