# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## [Unreleased]

## [AMAI3.10c 更新内容]

### 全局调整
- 重新调整动态策略系统，调整各单位的权重。
- 大规模调整各族战术，重做多个战术，完善大部分战术。
- 激活并完善各族反塔Rush战术。
- 为所有种族战术的二本阶段增加少量基础兵种，避免二本期间被Rush后不出兵的情况。
- 调整TP机制，现在即使队伍规模较小AI也会尝试TP回防。
- 提升各族重建分矿的优先级。
- 降低了AI英雄在家傻等恢复血量的时间。

### 种族调整
- 人族
  - 调整了AI生产农民的数量，现在AI在单矿时会用9个农民采木，确保在多个农民建造建筑时仍然有足够农民采木。
  - 调整人族多农民同时建造功能，现在AI只会在资源足够多的情况下双敲或多敲建筑。
  - 调整敲民兵开矿机制，因版本更新导致民兵时间缩短，因此等比例缩短允许AI使用民兵开矿的距离。
  - 调整AI后期建造塔的数量。
  - 完善小炮战术和飞机战术。
- 兽族
  - 调整各战术板砖车的数量。
  - 调整了剑圣的加点方式与骚扰模式，现在学习疾风步的剑圣可以正常骚扰对手农民了。
- 亡灵
  - 调整各战术前期蜘蛛数量，避免早期等着造坟场而不出兵。
  - 调整个别战术冰龙数量。
  - 为男巫海战术添加绞肉车，能提供更多尸体。
- 暗夜
  - 调整各战术前期女猎手数量，避免早期等着造猎手大厅而不出兵。
  - 恢复了暴雪自带AI的出兵战术，作为战术库备选之一。
  - 恢复了夜视的研究。
- 中立
  - 降低地精修补匠的出场率。
  - 调整了熊猫的技能加点。

## [AMAI3.10b 更新内容]

### 全局调整
- 修复了早期不出兵一直等科技建筑（铁匠铺等）的Bug。
- 调整了TP的使用：提高了购买TP的优先级；提升了对威胁的反应；缩短了使用TP的最小距离；降低了英雄使用TP最低生命值，使操作更加极限。
- 现在低血量英雄将会被移除出集火队伍。
- 调整了各族升级攻防的优先级：现在AI会在合适条件下优先升级高级兵的攻防；降低了一本升攻防的优先级，避免升级攻防影响升本。
- 现在AI会在经济充裕的情况下多造塔。
- 现在AI会在经济充裕的情况下在分矿多造一个商店。
- 重新调整了动态策略系统的参数，现在AI会更多地使用三本兵种来反制对手。
- 重新调整了各族战术，增加了三本兵的出场率和数量，确保战术后期的强度。
- 重新调整了各族战术，修复了升级兵种科技却不出兵的Bug。

### 种族调整
- 人族
  - 修复了AMAI文件中魔法岗哨和照明灯代码错误、错位的Bug，现在AI会正常升级魔法岗哨。
  - 调整了AI生产农民的数量，现在AI会用8个农民采木，确保前期不缺木。
  - 调整了哨塔和商店的优先级，现在AI会正常使用兵营开局。
  - 调整了一本时生产兵种的数量和比例，使前期兵足够用，造兵升本速度足够快。
  - 减少了二本步兵的数量。
  - 给部分战术三本添加了骑士和狮鹫。
  - 给纯法师战术添加了火枪和破法，使其更加万金油。
- 兽族
  - 调整了商店和磨坊的优先级，现在AI会正常使用兵营开局。
  - 调整了AI生产农民的数量，现在AI会用8个农民采木，确保前期不缺木。
  - 给部分战术二本添加了少量牛头人。
  - 给所有兽族战术三本添加大师级巫医，可以缓解兽族AI过多残血兵影响战斗力的问题。
- 亡灵
  - 解决了亡灵缺木的问题：确保每个战术所有阶段至少有三条狗；确保任何情况下AI至少会留下一只狗继续采木。
  - 修复了AI有时会先升本再出首发英雄的Bug
  - 移除了各个战术建造牺牲深渊。
  - 提高了三本购买腐球的优先级。
  - 修复了部分战术无法正确生产冰龙的Bug。
- 暗夜
  - 现在暗夜女英雄（白虎、守望者）不会在残血时使用夜间隐身来躲避对手。
  - 调整了各个战术女猎手的数量。
  - 调整了各个战术风德的数量。
  - 提高了三本购买毒球的优先级。
  - 重新调整了AI选择守望者的优先级。
  - 修改了守望者的撤离机制，降低了残血守望者闪烁逃离后继续回去战斗的概率。

## [AMAI3.10a 更新内容]

### 全局调整
- 战术
  - 恢复了被原作者删除的各族Normal战术（即暴雪原版AI下各族会使用的战术），这样使AI后期更有可能选择万金油战术，而不是纯法师或纯低级兵阵容。
  - 移除了战术编辑器中大部分战术的1 on 1 bonus，现在AI在1v1情况下不会再特别频繁的使用某些战术了。
  - 调整了AI升级攻防的优先级，现在AI在一本不太会升一攻一防，而是把资源省下来升本。
  - 提高了所有种族所有战术的三发英雄优先级，现在基本所有情况下，AI都会在80人口前召唤出三英雄。
  - 移除了各个战术的不合理骚扰。
- 动态策略系统
  - 恢复了动态策略清零函数，现在每次升本AI都会重置动态策略系统，重新计算用什么单位针对更好。（应该能部分修复AI各族总是暴法师应对的Bug）
  - 降低了动态策略系统对二本的影响，现在AI会更多的用三本部队来反制对手。
  - 调整了动态策略系统的计时器，现在更换针对战术后会等一段时间，而不是几十秒一换。
- 操作
  - 修改了英雄微操，现在AI英雄在拉单情况下残血也会使用TP撤退。
  - 降低了英雄使用TP的最大生命值，现在AI英雄会更极限地使用TP。
  - 部分修复了AI英雄卡在家不操作的Bug，这个Bug现在偶尔会有，但降低了卡顿时间。英雄会在血量比较健康时重新参战。
  - 向标准单位文件中添加了熊猫大招的三种形态，现在熊猫到达6级后应该能正常使用大招了。
  - 向标准单位文件中添加了火凤凰和复仇天神，现在血法师和守望者使用大招的概率会进一步提升。
  - 现在AI会在满足条件的情况下，在分矿建造另一个商店。
  - AI现在不会在资源过剩的情况下建造三个祭坛了。

### 种族调整
- 人族
  - 重新调整各类战术的一本建造和出兵逻辑。
  - 降低了购买慢补的优先级，现在AI不会抢先建造商店了。
  - 调整了一本兵的优先级，现在AI会比以前少出步兵了。
  - 重新调整骑士战术，AI不会前期造太多步兵，导致三本没有人口出骑士了。
  - 提高了采木人数，避免前期缺木。
  - 现在AM会在接近人口上限时同时建造农场。
  - 现在AI在一本就会研究采木技术。
  - 现在AI在一本就会研究破法的控制魔法。
- 兽族
  - 提高了采木人数，避免前期缺木。
  - 降低了第一个药膏的优先级，将第二个药膏优先级和受伤单位数量挂钩。这会降低AI先造商店后造祭坛的Bug发生概率。
- 亡灵
  - AI不再会在分矿建造坟场，现在AI会在分矿建造大墓地。
  - 现在所有战术下AI都会造3条以上的狗，避免后期木材不够。
  - 修复了男巫海战术下，AI会先升二本再造英雄的Bug。
- 暗夜
  - AI不再研究夜视。（AI本来就开全图的）
  - 自然祝福的研究将移动到三本，以避免二本缺木和升三本过晚。
  - 下调驱散优先级，现在AI会先造小鹿再研究驱散。
  - 减少1本可能建造弩车的数量。
  - 进一步降低WD二发和三发几率，降低DH三发概率。
  - AI不再使用猛禽德鲁伊来针对空军。（因为AI的鸟德不会变身）
  - AI不再研究猛禽之痕。（原因同上）
  - 降低了AI三本仍出大量一本兵的概率。
  - 提高了部分战术升三本的优先级。
  - 部分战术提高了角鹰、精灵龙和奇美拉的出场率。
- 中立
  - 略微回调了炼金术士的优先级。


## [AMAI 3.10 更新内容]
- 更新直到1.32.10的科技树和物品价格变化。
- 重做聊天系统，更换中文翻译，现在AI使用的聊天和嘲讽语句总算跟上时代了。
- 重做动态策略系统，现在AI会在合适的时间调整战术，战术也会更灵活，兵种更多样。
- 重做所有英雄技能加点顺序。（剑圣终于不会主修镜像了）
- 重做暗夜英雄选择优先级。现在KOG取代DH成为带头大哥，更频繁地出场。
- 降低了守望者二发、三发的概率。
- 提高了炼金术士的登场率。
- 重做所有暗夜精灵战术。
- 调整了所有种族购买物品的优先级。
- 修改维护费对AI的限制，取消过去只有开二矿后才能超过80人口，现在单矿情况下只要攒钱足够也会直接暴人口。（这个改动加强了疯狂AI在小地图上的表现）
- 修复拉扯问题，AI现在会更谨慎和有效地拉扯残血远程单位。
- 修复背水一战功能，现在暗夜AI在最后一搏时不会再拉上小精灵并且把树都站起来。
- 修复AI暗夜开局问题，现在AI不会直到出第7个小精灵才造祭坛，而是会正常开局，4采矿1祭坛，第6个造月井，第7个采矿。
- 扩展了前线距离，避免暗夜AI容易被堵死在家的恶性Bug。
- 修改伐木机对应农民数量，现在AI使用伐木机时会取代更多农民。
- 其他Bug修复。

## [AMAI 2.54b到3.01的更新内容]
- 2.61
  - 修复了对1.32之前版本的支持问题。如果你现在玩的还是老版本魔兽争霸3，可以用这个版本来给地图安装AMAI。
- 3.0
  - 全面支持1.32以上版本，全面支持重制版。3.0要求魔兽争霸 3 最低版本为 1.32。
  - 支持直至1.32.6的所有科技树更新。
  - AMAI 玩家现在默认显示电脑难度等级。例如疯狂AI会带有前缀[AMAI Insane]。
  - 加强AMAI集火操作。
  - 加强AMAI拉扯残血单位操作，地面远程攻击单位现在会尽量避免移速较慢的近战单位近身。
  - 改进了对 24 名玩家的支持。
  - 启用动态策略系统，并作为所有策略的备用计划。动态策略模式下AI会根据对手单位攻击和护甲更快的改变战术，选择最针对的单位反制对手。
  - 添加背水一战功能。现在当 AMAI 资源不足时，如果当前的局势已经低于该AI设定档案中的投降阈值，它会拉上包括农民在内的所有部队进行最后一搏。
  - 其他Bug修复。
- 3.01
  - 移除 AMAI.exe，给地图安装AMAI统一使用bat文件和pl文件。
  - 修复中文翻译/编码问题（感谢keamspring）。

## [3.0.1] - 2021-01-30

### Changed
- Moved the `AMAI.exe` to make it clearer which bat file to use to install the AI. This will avoid installing without the correct pre-requsites in place on the map.

### Fixed
- Fix the chinese language translation/encoding issues (Thanks keamspring)

## [3.0.0] - 2020-06-21

### Added
- Dynamic strategies are now enabled and act as a fallback for **all** strategies.
  - Hardcoded strategies still set the theme and initial build orders.
  - But AMAI will now have an element of countering what the enemies have built and what it has already built.
  - Dynamic strategies change more frequently than the chosen fixed strategy theme.
  - Dynamic strategies pick the attack type they are countering and a unit to focus on building until its next check.
- When AMAI is out of resources profiles with low surrender values, it will now do a last effort attack with all units including workers.
- New `InstallTFTToDir` perl script which can be used to install AMAI to an entire directory of maps e.g `InstallTFTtoDir.pl "C:\Documents\Warcraft III\Maps\AMAI"`

### Changed
- Now requires a minimum warcraft 3 version of 1.32.
- Computer skill level is now shown by default on AMAI players.
- Reduced impact of summons on total caster strength as they are temporary units.
- Moved template files to `Templates` folder.
- All war fronts are now taken into consideration for focus fire which should improve behaviour no matter where battles are happening.
- Halved front location distance from town center but now calculates an arc of locations to use. 
- Tweaked english gramatical errors for various strategy messages.
- Stock availability/regen times are no longer divided by 5 in `StandardUnits.txt`.

### Removed
- No longer a seperate AMAI vs AI installer batch script, installers now support both versions.

### Fixed
- Corrected tech tree to properly handle all changes since 1.24 to 1.32.6
- Improved support for 24 players. 
  - All 24 player colours are now supported by AMAI.
  - Various messaging and attack targeting will now work with more than 12 players.
  - Profiles can now be reused by AI players. This is useful for > 12 players in a game as there is not always enough profiles to set unique profiles.
- When the debug player is killed we will now switch to a new player to debug.
- The StrategyManager compile buttons now work again.
- Fixed warning message during script compilation.
- Ranged ground attackers will now try to avoid slower melee attackers that get too close.
- Focus fire micro will no longer accidentily wake sleeping creeps.
- Fixed an issue where AMAI would get stuck trying to attack its own base.
- Mechanical armies will not enter emergency healing state because the only non-mechnical unit/hero is damaged.
- Fixed some issues with the build logic where it would build the wrong priority units.

## [2.6.1] - 2021-01-13
- Fixed support for pre-1.32 versions.

## [2.6.0] - 2020-03-02

### Added
- Latest version of pjass.
- Missing licence text for sfmpq.
- Official Support for 1.30+.
- New `installToMap` scripts provided to install AMAI and VSAI editions to maps. 
  - MPQEditor by Ladislav Zezula is now included to support this.
  - These will increase the MPQ file limit on maps to 64 automatically as on official maps the limit is too low and prevents AMAI being installed.
- Alpha 3.0 dynamic strategy scripts have been harvested. Can be enabled by using the strategy manager to lock race strategies to the dynamic forms.

### Changed
- Reworked the changelog for keepachangelog format.
- Tweaked english ally chat messages so its more noticeable who the AI is attacking.

### Removed
- Removed grimoire and war3 exe hack support as it no longer works for versions post 1.24+. Only player edition "AMAI.exe" works.
- Removed MPQDraft executable as no longer useful post 1.30.
- Removed various files that are not of use.

## [Legacy Versions]
14/09/09
--------------------------------------------------------------------------------------------
The inbuilt grimoire provided with developer edition war3err updated for 1.24b support.

16/08/09
--------------------------------------------------------------------------------------------
Languages using wrong check on race. Race checks should be in capitals. Should fix messages appearing for the wrong race.
Debug traces improved and support for TraceI, TraceII and TraceIII

15/08/09
--------------------------------------------------------------------------------------------
Support for 1.24b appears to be complete.

19/10/08
--------------------------------------------------------------------------------------------
Fixed AMAI cancelling construction of townhalls.

17/10/08 (AMAI 2.54 released)
--------------------------------------------------------------------------------------------
Wrapped up a collection of updates/fixes to AMAI
Portuguese language updated
Bundled MPQDraft with the developer edition so people can make executables that work in the latest warcraft patch 1.22 from AMAI.mpq as grimoire will not work in this version of warcraft 
This builds core is going to be used as the basis for stability in a 2.54

16/06/08
--------------------------------------------------------------------------------------------
The militia_hall now has the capability to be rechosen if the original dies.
Focus fire job didn't appear to ignore dead units as focus targets.
Ghoul proirity setting was not being used.

11/06/08
--------------------------------------------------------------------------------------------
Turning off ver_heroes will ensure the hero heal army control is not used.

09/06/08
--------------------------------------------------------------------------------------------
BuildAdvUpgr2 now has an extra parameter that determines the priority upgrade is at if it does decide to build the upgrade.

08/06/08
--------------------------------------------------------------------------------------------
Added new columns to strength that is the strengths.txt that have advantages against a particular strength. 
Using the above, dynamic systems now take account what its allies are building.
Added support for mercs into the dynamic system but not been added to strategies themselves yet.

FIXED
Warning: RemoveLocation(null) fromm
GetSubtractionLoc_dd(0, 1143034)
DistanceBetweenPoints_dd(1143034, 0)
DistanceBetweenUnits(1058434, 1124720)
GetRangePenalty(1124720)
GetTargetStrength(1124720)
IsTargetGood(1124720, 10)

07/06/08
--------------------------------------------------------------------------------------------
Decreased percentage of army damage required for healing. 
Attacks on double expansions only occur if AMAI more likely to accomplish this task.
CaptainGoHome() re-enabled but both enabled or disabled flight and flee behavior can still occur.
Another buy item job bug.
Placed in sheeryiro's chinese as the default and Dr fans as optional replacement as fans may be useable for some.
Buy stutter fixes for neutral unit jobs implemented.


06/06/08
--------------------------------------------------------------------------------------------
Calculation error with the restriction of militia fixed
Added ability to add structures to the dynamic build sequences. Will only ensure building one of the particular structure.
Undead/human dynamic tiering systems implemented
Added the missing wyvern unit to the orc dynamic tree

03/06/08
--------------------------------------------------------------------------------------------
Extended resource blocks to allow placing a block on food as well as just gold and wood and used to check enough food is used before building a number of units.
Started implementing system to night elf/orc so that it dynamically decides when to tier up or not.
Ally Attack process is no longer running in games where there is no ally which caused AMAI to sometimes attack same target twice.
Fixed stutter behavior on the hero when buying item.
Fixed bug with a variable not set on the buying item job.
AMAI should restrict number of militia to build based on enemy strength in base.

27/05/08
--------------------------------------------------------------------------------------------
Turned off the CaptainGoHome() fnc in the racial attack code as when retreating from battle they resume attack to fast.
Turned off hardcoded unit micro controls too see how amai manages without.
Some improvements to buy item process so units not ordered multiple move orders every 0.01 of a second.

29-11/04/08
--------------------------------------------------------------------------------------------

AMAI 3.00
Fixed bugs in dynamic calculations causing bad unit ideas at start up and some units never being built at all.
Integrated dynamic strategy systems with profile uncertainties and strength prediction rules.
Size optimizations.
Fixed missing return statement on buy item causing the stutter behavior.
Implemented upgrade system to majority of upgrades.
Fixed a bug where militia stopped humans teching from the beginning of the game.
Ensured militia return home if for some reason the attack ends early.
Fixed bug where peasant would be stuck at the expansion if someone else built expansion before them.
Reduced the tower strength additions from towers.
First tier teching way to slow.
Added wood requirement to be below 550 as well as its other conditions to build a shredder.
Fixed a bug where AMAI picked up dead expansions in the double expansion detection.
Dynamic strategy selection now ignores some really really low strengths when countering.
Profile strat persistence now adds a bonus to highest probrability of countering.
Temporarily fixed issue of heros having loss of control from AMAI
Slight improvement to creeping to avoid going to creep then running away cause a unit got hit.
Fix for hero trying to use the unpathable fountain in map hail stone (i.e actually moving to point (0,0) on map).

FIXED
Divide by zero error in
BuildAntitowersStrength(100, 40)
DynamicBuildSequence(100, 40)
build_sequence_DynamoH()
build_sequence()
build_sequence_all()

FIXED
Divide by zero error in
GetTimeToReachUnit(1113004, 1051751)
BuyNeutral(292)
TQDoJob(20, 292, 0, 0)
TQHandleOnce()
TQLoop()

Memory Corruption:

FIXED
Warning: RemoveLocation(null) from
GetSubtractionLoc_dd(0, 1145177)
DistanceBetweenPoints_dd(1145177, 0)
DistanceBetweenUnits(1094523, 0)
HealthFountainJob(1094523, 80)
TQDoJob(15, 80, 1094523, 0)
TQHandleOnce()

FIXED
Warning: RemoveLocation(null) from
ZeppelinMoveJob(1, 1057835, 1146160)
TQDoJob(1, 1, 1057835, 1146160)
TQHandleOnce()
TQLoop()

FIXED
Warning: RemoveLocation(null) from
GetSubtractionLoc_dd(1113051, 0)
DistanceBetweenPoints_dd(0, 1113051)
DistanceBetweenUnits(0, 1076587)
GetRangePenalty(1076587)
GetTargetStrength(1076587)
IsTargetGood(1076587, 9)

FIXED
Warning: RemoveLocation(null) from
GetSubtractionLoc_dd(0, 1196004)
DistanceBetweenPoints_dd(1196004, 0)
DistanceBetweenUnits(1060202, 0)
GetRangePenalty(0)
GetTargetStrength(0)
IsTargetGood(0, 0)

FIXED (and safely)
Warning: RemoveLocation(null) from
GetSubtractionLoc_dd(0, 1186145)
DistanceBetweenPoints_dd(1186145, 0)
DistanceBetweenUnits(1181666, 1053583)
MilitiaCheckJob()
TQDoJob(27, 0, 0, 0)
TQHandleOnce()

FIXED
Warning: RemoveLocation(null) from
TeleportHome(1119449)
ExecuteSaveHero(2, 3, 0)
SaveHero(2)
MicroHeroJob(2)
TQDoJob(33, 2, 0, 0)
TQHandleOnce()


25/04/08 - AMAI 2.53b Released
----------------------------------------------------------------------------------------------
Fixed human and orc resource harvesting


18/04/08 - AMAI 2.53 Released
----------------------------------------------------------------------------------------------

17/04/08 - AMAI 2.53 Beta
----------------------------------------------------------------------------------------------
Fixed some bugs in the strategy calculations. All the racial bonuses where being ignored and profile strat persistance value was ignored.
Strat persistance is no longer in the global settings as its value is controlled by profile values.
race_min_ghouls, ghoul_prio,  and race_max_ghoul racial settings added
ver_optimal_gold, ver_flee_multiple1, ver_flee_multiple2, ver_flee_multiple3, ver_low_aggression, ver_high_aggression global settings added
Fixed a bug for custom amai's where the zeppelin job looked for a zeppelin so amai would error without that unit. Now correctly uses unit that uses the 'transporter' tag
Fixed a problem where amai would try and buy healing item for hero from a merchant when merchant is guarded.
Fix to the aggression checks so it uses amai's current aggression instead of its base aggression.
Fixed bug in apply table changes where it would fail to add decimal and negative valued settings correctly.
Apply table changes should now re-create the entire global settings file if you happen to delete entries(the values will just be default values so are not all up to date)
Fixed bug with peons and invisible units being detected by getlocationcreepstrength.
AI_COMP equivlence type added which is made to give a unit type multiple names, main purpose is for the standard ai compatability.
Fixed a bug with the CPU profile being picked in the ROC version
AMAI will supply its fighting army with reinforcements if battle still going for a long time.
Fixed bug where timing was using incorrect scale for buying neutral heros.
Fixed a nighttime timing bug for buying neutral units.
Bundled Swedish language updates by Thunder Ey


16/04/08
----------------------------------------------------------------------------------------------
AMAI 2.53
- Re-starting from 2.52 due to tech build failed
- Applied grimoire and pjass updates

AMAI 3.00
-Created function that determines which strength to counter to
-Investigation of jasshelper integration

14/04/08
----------------------------------------------------------------------------------------------
Updated grimoire to 1.5 beta for patch 1.21b support
Fixed a single memory leak in teleport home code

28/05/07
----------------------------------------------------------------------------------------------
Fixed some bugs in the strategy calculations. All the racial bonuses where being ignored and profile strat persistance value was ignored.
Strategy persistance is now a multiplicative amount bonus on the total priority of the strategy.
Strat persistance is no longer in the global settings as its value is controlled by profile values.
race_min_ghouls, ghoul_prio,  and race_max_ghoul racial settings added
ver_optimal_gold, ver_flee_multiple1, ver_flee_multiple2, ver_flee_multiple3, ver_low_aggression, ver_high_aggression global settings added
Fixed a bug for custom amai's where the zeppelin job looked for a zeppelin so amai would error without that unit. Now correctly uses unit that uses the 'transporter' tag
Fixed a problem where amai would try and buy healing item for hero from a merchant when merchant is guarded.
Fix to the aggression checks so it uses amai's current aggression instead of its base aggression.
Fixed bug in apply table changes where it would fail to add decimal and negative valued settings correctly.
Apply table changes should now re-create the entire global settings file if you happen to delete entries(the values will just be default values so are not all up to date)
Fixed bug with peons and invisible units being detected by getlocationcreepstrength.
AI_COMP equivlence type added which is made to give a unit type multiple names, main purpose is for the standard ai compatability.
Fixed a bug with the CPU profile being picked in the ROC version
AMAI will supply its fighting army with reinforcements if battle still going for a long time.
Fixed bug where timing was using incorrect scale for buying neutral heros.
Fixed a nighttime timing bug for buying neutral units.

IDEA: Check army has retreated all the way home before allowing it to continue back to attacking
NOTE: Time in amai is all /5 but the timing system for jobs uses the real time without any measurement changes
NOTE: AMAI not supporting change of day scale if thats possible for custom maps.

23/05/07 - 26/05/07  - AMAI2.52b-c released
----------------------------------------------------------------------------------------------
Added another streamlining to the militia expansion control to prevent amai reforming its troops and so militia end up getting beaten up.
Fixed a bug where if building at a mineloc failed amai wouldn't just build the unit normally.
Fixed bug where amai thinks it should retreat from units that are not detected by amai.
Heros get added back to the assault group if they succesfully buy an item now.

19/05/07
----------------------------------------------------------------------------------------------
Moon well control changes to the send home controls when all moon wells are empty so hero will buy items from shop.
Improvements to the tower rush code to improve reliability and integration, in otherwords no longer as bity as before and also amai builds towers towards enemies base instead of randomly all over the place.
Fixed a bug where heros wouldn't use healing salve on itself properly for healing.

17/05/07
----------------------------------------------------------------------------------------------
Tried to implement zals micro idea but dosn't seem to currently make any effect.
Jungle around with micro hero rules to hopefully and also improve likelyhood it teleports in case its surrounded.
Need to test to see if give item to hero when its in another hero works autmatically.
Implemented a hero surround detection that is an extra tp check even if its on another healing path.

14/05/07
----------------------------------------------------------------------------------------------
Implemented Blink micro control to be able to save the warden.
Increase creep camp strengths of orange and red camps to negate the strength of the hero and prevent some occasionaly wild choices.
Finally been able to re-enable aiandys healer controls (i.e. statues staying at distance from battle to heal) after some heavy messing around. (had been disabled due to the job crashes they were causing previously)

13/05/07
----------------------------------------------------------------------------------------------
Setbuildreact now builds units of different types simultanously instead of building the highest amount unit first
Setbuildreact will always build the units starting at the proity of building all of the unit type that has the lowest food
First farm is always built at main base even if you have build farms at front option on
Increased number of millitia used in base defense
Micro unit control is now always on
Fixed a bug where a hero with full inventory couldn't start to buy an item they had to already be buying
Fixed a boolean bug on getmajorhero that caused an occasional error of fleeing on maps with creeps at map center
AMAI should now no longer go to buy items when its on the attacks as its supposed to (used to go on trek to buy items in the gap)
Added missing human upgrade to increase lumber harvesting

IDEA: Hero should look for the healing item on another hero if that hero is close by and get it off him(This will also subsequently fix issue of wrong hero selected at shop)
TO DO: BLink functionality usage for warden
TO DO: Zals micro system idea and improve healer usage so they stay behind the army instead of always staying right in the action

12/05/07
----------------------------------------------------------------------------------------------
Fixed issue with vs ai edition where there was a chance in ROC for a hero not to be chosen
Fixed issue where if you have a custom AMAI with custom races AMAI still required the original race folders to compile

Human v human matches - Always 6 foots, 6 priests, then spell breakers

11/05/07 - AMAI 2.52 
----------------------------------------------------------------------------------------------
Fixed some issues of racial healing items not being able to be brought due to heroes out of range.
Fixed issue where buying and emergency item did not ignore if heroes have no free space.

10/05/07
----------------------------------------------------------------------------------------------
Fixed issue of the correct number of ghouls not aiding hero in the attack
Fixed an issue where on certain maps some creeps were regarded as expansion creeps due to how close they are to the expansion.

ERROR: Town spam still present (affects undead more often)
ERROR: Check droping item when inventory full control.
ERROR: Heroes not buying any items from shop see orcslow replay.

IDEA: If player attacks an amai in ffa give amai more aggression against that player and maybe even base its counter units on what that player is building to solely attack that player.
9/05/07
----------------------------------------------------------------------------------------------
Single melee attack ally attack system improvements
If you have more types of dragons they are succesfully added to the assault group if brought.
Some fixes so that the wave indicator increases correctly and to improve ghoul attack routines
Increased frequency of unit micro checks.
Fixed some bugs where army would just give up for no apparent reason
Unit selection as a hero system if hero dies now implemented into amai.
AMAI will now automatically build a required number of ghouls to harvest.
The expansions will now rebuild with the priority specified in racial settings if destroyed but still owned.

ERROR: When army retreats (i.e heros killed) some units dont retreat properly and stay at enemy
this results in the entire army getting sent to save the one unit. This causes AMAI to lose all
its units and become defeated when it could of saved itself. Need to force all units back home
when its retreating would seem safest option.
ERROR: Went to get item, army went to attack creeps so after hero got item it attacked the creeps
guarding the item shop. 
ERROR: Need to teleport away when surrounded and can't path away.
ERROR: Still undead ghouls not aiding hero in attack. Seems 2 reforms needed to kick start.

5/05/07
----------------------------------------------------------------------------------------------
Fixed issue where teleporting home would set break_attack variable when attack wasn't running causing a lock up of waiting for amai to retreat
Fixed issue where teleporting away when enemies close by only occurs when AMAI is in an attack
fixed a double free of group
Fixed a bug with ver_heroes off making AMAI never attack properly
Fixed some bugs that could occur with AMAI trying to buy units from merchants that it failed to path too.

ERROR: For some reason War2 always displays needs healing at beginning of game even though this shouldn't happen

4/05/07 - Amai 2.51 release
----------------------------------------------------------------------------------------------
Fixed issue with custom named ai's for pitting against amai


2/05/07
----------------------------------------------------------------------------------------------
Player pink of last replay has test of the new blademaster thing in (DIDINT work)
little bug fix to the teleporting when retreating where it would teleport home when they never even got to the enemy

IDEA: blademaster when going into windwalk should stay without guard position till either the invisibility has worn off. Should also keep moving with the army if no enemies around.

CHECK: call FlushGameCache(InitGameCache("GC"))
set udg_GC=InitGameCache("GC")

should be flushed when inited to make sure they are clear

1/05/07
----------------------------------------------------------------------------------------------
Fixed one location leak (normalizes to 40 permanent locations per AMAI player)
Fixed five major group leaks (reduced from 1300 leaked groups to 300 leaked groups with 2 AMAI players)

29/04/07
----------------------------------------------------------------------------------------------
Some attack system speed improvements
Attack reform length decreased from 20 to 7 due to bug fix showed error in this value
Improved the reform until target dead system to keep choosing new units to attack if in area
Added check to harass so if harassing player can see him so not to just wait around.
Now AMAI will always go for the enemies expansion first as its always the weakest point of an enemy.

IDEA: Use buff ability code to check if blademaster is invisible. 


27/04/07
----------------------------------------------------------------------------------------------
Fixed issue with blizzard orc ai used ENDURANE_AURA instead of ENDURANCE_AURA (syntax fix)
Pjass will now check the standard ai's have no compatability problems with the AMAI's compiled common.ai file
Harass can no longer be given to units currently doing something else like buying a merc or item
Fixed issue of zepplin not droping units it picked up.
Implemented idea: If army is outnumbered and hero with portal is present, they should town portal away instead of running
For blademaster harass there is only a 30% chance it occurs if blademaster is picked as first hero.
Massive strategy upgrade checkover and other misc strategy improvements.

IDEA: Aggression should increase the less gold mine gold AMAI has available so they might take an expansion.

NOTE: Do not beleive still entire food usage is used in all strategies(needs looking into)

24/04/07
----------------------------------------------------------------------------------------------
Delay for windwalking harass attacks now works.
Blademaster periodic harrass increased from 60 to 150 time units. Effectively another 7 mins before doing the harrass again.
Blademaster no longer does his harass if nearest enemy is undead.
Hopefully fixed finally the focus fire blademaster harass.

IDEA: Improvement to harass so it wont harrass if target is at the undead main base instead of just getting the nearest enemy.

23/04/07
----------------------------------------------------------------------------------------------
Fixed a bug so AMAI will change target if it can't attack its target, was using local variable so would never change.
Added a delay before windwalking harasser attacks the next target.
Hopefully fixed the bugs in the focus fire controls.

ERROR: Two windwalking stuff implemented never worked

22/04/07
----------------------------------------------------------------------------------------------
Hero drops of items only occurs when it wants to buy a healing item and will drop an item which is not deemed a healing item or a town portal.

ERROR: Windwalk usage in focus fire on player, need to realise when its windwalking but doesn't focus fire if it missed the first check
ERROR: Be nice to have a delay before AMAI blademaster does its next harrass attack on its victim. 

19/04/07
----------------------------------------------------------------------------------------------
German translation by Sagen completed
Added global setting to turn off the give up mechanisms of the ai
Modified code slightly in DefendTownsCond in hope to fix the spamming tower bug

Fix so hero drops items to buy new ones works correctly


ERROR: Some rare bug has been confirmed that causes amai to spam building towers+graveyards 
       everywhere- Need to check replay AMAI glitch (major build code bug)

13/03/07
----------------------------------------------------------------------------------------------
Fixed an issue where firelord could not learn incinerate ability
Fixed an issue where blademaster focus fire windwalking was used on buildings and creeps, turned this off so blademaster dosn't waste mana on them.
Improved focus fire systems with invisible units so they can focus on units further away as are able to move around battle without notice.

Hardcoded Error: Peons that are building get targeted by harass but the harraser can't attack unit so it wanders. (most noticeable problem with windwalkers)

9/03/07
----------------------------------------------------------------------------------------------
Fixed an issue where focus fire would not turn off windwalk once the units guard position was recycled
Fixed issue with strategy manager not correctly activating a bug if fix for new versions of perl

7/03/07
----------------------------------------------------------------------------------------------
Fixed issue where units were still not correctly removed from the harass group.
Units in harrass will immediatly join up with army instead of waiting until the army returns when they have returned home.
Implemented a mana potion usage system into the SEND_HOME controls.

ERROR: Windwalkers need to turn off there invsibility when they recycle guard position from focus fire controls
ERROR: Noticed that the reform until base dead can keep the units stuck because not all buildings destroyed and so never finish the attack cycle. Annoying blizzard bug with the attack captains it seems.

6/03/07
----------------------------------------------------------------------------------------------
Fixed aload of issues that were probrably causing location and group stack corruption amongst AMAI
Fixed issue with focus fire and windwalking so the units regain control at the correct time
Fixed issue where a unit in the healing group would try and buy a merchant item. (The send home controls deals with that so its a uneeded conflict)
Added a third hero bonus option to the strategy editor due to development demand.
Improved macro with night elf so it should be able to get hero out a little faster.

ERROR: Harrass units if meet a major army should then rejoin the assult group once home. (best way as doing immediatly harasser will become occupied at the harrass location and be killed by bad ass army)
ERROR: Need to get AMAI to change harass target if target is not attackable.

5/03/07 - Tech update
----------------------------------------------------------------------------------------------
Fixed wind walk focus fire control to now work correctly.

ERROR: Focus fire with windwalkers, they have issue of if they went invisible but no longer in range to focus fire and there guard position is not recycled back until they visible again.
ERROR: Need to have an emergency mana buying for heroes harassing. Current method is unreliable.

4/03/07 - Tech update
----------------------------------------------------------------------------------------------
There is an invalid racial setting as changing farm_food is done by the profile and not the setting.
Tweaks to farm building system and fixed an issue where if ur over the food limit amai builds 3 farms.
Some hero prority tweaks based on deutschepharmas work and updated bases with the latest battle.net stats.

3/03/07 - Tech update
----------------------------------------------------------------------------------------------
Focus fire and retreat control systems now do there checks around the main army and not just the major hero himself. This fixes some bugs of focus fire stopping working cause major hero went off to heal etc.

NOTE: Focus fire control usage of windwalk just can't implement nicely to give control back to the blademaster. It was ending up sending home the blademaster mid way in combat.

1/03/07 - Tech update
----------------------------------------------------------------------------------------------
Fixed a bug where units used for harassing where not removed from the harass group when harass has finished.
Fixed issue with healing salve not able to be used to heal hero in the send home control
Fixed issue where send home control was trying to use healing salve mid battle.

NOTE:Idea: The above healing salve changes need to be addressed for all regenerative healing items and all require target items for custom game support.
ERROR: Still hero wont have his guard position recycled. Very strange.

28/02/07 - Tech update
----------------------------------------------------------------------------------------------
Windwalk is now used in the focus fire systems.
Fixed a bug where units that can hide at night didn't hide if were going straight to the shop.

ERROR: If hero has a healing pot etc it will sometimes not send hero home and instead try to use that item.
ERROR: Harrass blademaster hero will not recycle guard position correctly once its removed during focus fire.
ERROR: Get focus fire to run off the correct hero. Currently occurs from a hero who harassing when it should be in the assault group.

27/02/07 - Tech update
----------------------------------------------------------------------------------------------
Fixed an issue where if hero does harass he should stop harass if town is threatened unlike other harasses.
Fixed an issue where army would stop creeping when the only hero required healing.
Windwalk capabilities implemented into the focus fire controls.
Fixed an issue where harassing units would be used for buying items.
Provided a temporary fix to zepplin storing units it shouldn't be by unloading if zepplin following hero.
NOTE:Blademaster temporariliy at high proirity. Its default is normally 21
Chinese Language translation implemented by Dr Fan

ERROR: Town not threatened properly with small amount of units and can cause blademaster to be stuck in his harass.
ERROR: Add windwalk usage into the focus fire controls so on a new unit blademaster uses windwalk.

26/02/07 - Tech update
----------------------------------------------------------------------------------------------
Fixed an issue where harmed harrassing units where not added to the unit_healing group.
Hero harasses tested and do work fine with the current harass system (albeit few small changes)
Wind walk can now be used more effectivly for retreating and harassing (not just for a blademaster)
Fixed a bug where unit wouldn't go to heal due to a conflict between the harrass and healing system.

ERROR: Strange issue of zepplin deciding to pick up a unit and not dropping. Seems to be related to it picking up harmed unit but then unit heals and somehow gets repicked up and gets stuck.

23/02/07 - Tech update
----------------------------------------------------------------------------------------------
Fixed a bug where the item system would clear units from there use in other scripts.
Fixed some bugs where a unit was picked to do multiple buying scripts so became stuck.

22/02/07 - Tech update
----------------------------------------------------------------------------------------------
Fixed issues where units being used for other things could be sent to buy a merc or hero
Set up group for when units are buying but is not currently used.

ERROR: There is no group for units buying items or mercs or taverns individually. Needs to be set up to prevent the issue where a unit can become stuck as tries to do multiple things at once.

21/02/07 - Tech update
----------------------------------------------------------------------------------------------
Fixed some issues with using shop when no item space to buy an item.

20/02/07 - Tech update
----------------------------------------------------------------------------------------------
Aggression bonus is higher if food usage above 99.
Night elf more likely to build ancient protector if is undead enemy.
Fixed issue where moon well control wouldn't send units home properly if no moon wells available.
Generally increased all racial aggression bonuses.
Fixed issue where if harrass killed target it could possibly not retreat correctly.
Harrass controls no longer take over the harrass units if the harrass job wont work anyway.

15/02/07 - Tech update
----------------------------------------------------------------------------------------------
Implemented ideas for night elf strategies researched by shadowstrike.
Re-enabled other unit harrassments now that the system is working correctly again.

14/02/07 - Tech update
----------------------------------------------------------------------------------------------
Fixed issue where units would think they had a healing item because it was null.
Improved effeciency of the ancient expansion attacks.

ERROR: Tavern not usable and unknown hero error

12/02/07 - Tech update
----------------------------------------------------------------------------------------------
Fixed issues with harrass code and detection of towers.
Fixed issue where peons inside buildings where being targeted by the harrass code.
Fixed major bugs in the strength calculations in the harrass code.
Harrasses are now much more responsive and better in retreating if harrass fails.
Fixed an issue where cannibalizing healing ghouls would stop cannibalizing before fully healing themselves from the current corpse.
Fixed an issue where amai would try to buy emergency items that had a delay before being available.

ERROR: Ancient expansion can be a bit slow when gathering hero around tree. It sometimes takes a while before they all go to attack.
ERROR: Hero:use healing item appearing on units. When undead hasn't build the shop thing.

11/02/07 - 2.50c Release
----------------------------------------------------------------------------------------------
Fixed issue with night elf macro due to it thinks it has enough wisps from the pathing wisps.
Fixed issue with invulnerable wisps in mines.
Fixed issue with night elf doing ancient expansions all game which is a waste at late game.
Fixed issue with focus fire targetting hidden and invisible units.

ERROR: SENDHOME control dosn't take into account healing items at merchant have a delay before ready

10/02/07 - 2.50 FINAL FEEDBACK - 2.50b
----------------------------------------------------------------------------------------------
May need to on the large maps put delay to pathing so people can give initial orders.
Replay with issue of neutral pathing failing, CreateUnitAtLoc fails to work- replace with createUnit and it now works hmmm

Fixed issue where unit to buy from shop or tavern would be a dead unit.
Fixed issue where buying unit would move back and forth taking longer to reach the shop.
Fixed memory leak in moon well control.
Fixed memory leak from hero flee rules.
Fixed memory leak from elf mine controls.
Fixed memory leak from ancient expansion.
Fixed a major issue with Getexpansiondistance destroying the home_location variable.
Fixed an issue where compute front points used knights for pathing, this caused some extra lag as knights are not preloaded units unlike wisps.
Reduced start lag by making the rest of pathing thread start 3 seconds after towers are computed.

ERROR: replay of nerubian towers spam. This seems similar to an issue that once occured with loads of night elven towers being built at expansion. Needs looking into.
ERROR: Invulnerable wisp issue keeps occuring on destruction of night elven ancients.

08/02/07 - 2.50 Release
----------------------------------------------------------------------------------------------
Found bug in focus fire control so is now working properly again.
Increased melee focus fire distance from 200 to 250.
Tried to set tower rush to more likely occur at night time.

Idea: There is alot of improvements to focus fire controls that can be made. Also need to tell
arcane towers to focus on magic units only instead of wasting on some grunt or something.

07/02/07
----------------------------------------------------------------------------------------------
Massive work fix to the languages checking whats missing and fixing bugs in the ROC language transitions

ERROR - Focus fire control is not working. focus fire group keeps being checked as empty

29/01/07
----------------------------------------------------------------------------------------------
Fixed a major bug that resulted in world editor and standard blizzard ai's building multiple town halls, not expanding correctly and doing conversions improperly and most likely other wierd issues.  

ERROR - Hardcoded bug where forces cannot attack creeps when they sleeping and one of the creeps is invisible
IDEA - Add a system to night elf ai to realise when its got trapped and target a farm to get its forces out.

28/1/07 - Tech update
----------------------------------------------------------------------------------------------
Fixed a grammatical error in english commander.

ERROR - GetAMAIId not working for ai properly, not working at all. Is always blank.

26/1/07 - Tech update
----------------------------------------------------------------------------------------------
Fixed a major locations memory leak for start locations.
Implementation of grimore 1.1 and error detection systems.
Fixed a bug in the teleport to nearest allied town feature.
Fixed major leaks in micro hero script.
Fixed major leak in getexpansiondistance function.
Fixed a bug in militia expansion where once amai had enough units it would suicide creeps with constant militia if it lost its army.

17/1/07 - Tech update
----------------------------------------------------------------------------------------------
Languages are now versionised to fix issues with incompatabilities with ROC version.

16/1/07 - Tech update
----------------------------------------------------------------------------------------------
Massive increase to calculation speed of pathing for gold mines - will cause 1 second lag on the large player 10 - 12 maps
Massive increase to calculation speed of front points
Massive increase to calculation speed of pathing for neutral buildings
These increases fix issues on larger maps where certain neutrals would be detected as pathable when they are not. This would last for a very long time till the calculations caught up.
Fixed an issue where night elfs wouldn't give up sending a wisp to a mine in an ancient expansion (state 5)
Updated instructions of AMAI vs AI
Fixed an issue where invisible units are detected by AMAI defense systems and can be used as an exploit to force AMAI into defending its town.

ERROR- Maps not using Melee(latest patch data set) will not work properly and never upgrade there town centers.
ERROR- Ancient expansion state 1 needs to have re-calculation in step to see if it should skip to 5 if its current build expansion gets destroyed off 

15/1/07
----------------------------------------------------------------------------------------------
ERROR- Healing fountain on friends map was used
ERROR- Sending peons to build but current location has building enemy town center so build order should be canceled (INSANE ONLY)
IDEA- Simulataneous calculation of pathing for neutrals to speed up the calculation processing so it is much faster.

13/1/07
----------------------------------------------------------------------------------------------
Fixed an issue where strength calculations for attacking players in function IsTargetGood was incorrect which caused less hero rushes than should of been

ERROR- Hero tries teleporting to a town where town hall not yet finished construction.

11/1/07
----------------------------------------------------------------------------------------------
NOT PROBLEM - Adding new heroes error was a false alarm

09/1/07 - RC2 Feedback
----------------------------------------------------------------------------------------------
ERROR- When adding new heroes as they cannot be detected correctly.
ERROR- Stealthed units in enemy base will prevent enemy from doing anything due to the army control.
ERROR- Certain maps cause the no tavern debug message issue (Might be ok to turn off now)
ERROR- Reports of Zepplins not able to drop there units - Dessert Strife map
	(Not a bug as map not suited for AMAI play)   
ERROR- Need to update instructions of AMAI vs AI as odd teams are AMAI, even teams are AI
IDEA- AI creeping to much instead of attacking player
IDEA- More Hero rushes?

20/12/06 - RC2 Released
----------------------------------------------------------------------------------------------

14/12/06 - Tech update
----------------------------------------------------------------------------------------------
Norwegian language option enabled.
Romanian now has the correct language encoding.
Chinese language option enabled but unknown if it is working.
Fixed missing strategys in the english language - Need translaters to update the other languages.

NOTES: May now need to version the languages and make independent blizzard.j's as different strategies means we required different translations.

08/12/06 - Tech update
----------------------------------------------------------------------------------------------
Fixed an issue where melee ai's created in the world editor failed to work due to the BuildExpansion multiply defined.

30/11/06 - Tech update
----------------------------------------------------------------------------------------------
Fixed an issue where amai would sacrifice its first peon into the enemies base when tower rushing.

22/11/06 - Tech update
----------------------------------------------------------------------------------------------
Tweaked minimum attack strengths of profiles.
Fixed an issue where militia expansion attacks amai didn't have enough rescources to build hall afterwards.

ERROR - Can't detect where amai is getting two zepplins from when all strategies only say one.
ERROR - Tower Rush one peon always goes straight into heart of enemy base to its death.

21/11/06 - Tech update
----------------------------------------------------------------------------------------------
Town threatened level system to be implemented
Improved town threatened calculations which greatly reduces false positives.
Fixed issue where creep camp choice was still using old strength system introduced in rc1 so would rarely attack strong creep camps.

NOTE: Variable currently checks threat against teleport_low_threat in the improved town threatened calculations

18/11/06 - Tech update
-----------------------------------------------------------------------------------------------
Fixed same issue that affected the gold mine system in the neutral building system. (This is just currently using both old and new checks so should still fix the bugs the aim of the new system was to fix)

17/11/06 - Error List
-----------------------------------------------------------------------------------------------
ERROR - Militia sometimes not saving cash in the mil expansion so peasant becomes stranded at mine waiting for the rescources.
ERROR - Got confirmation same error with gold mines affected the neutral buildings themselves.

15/11/06 - Tech update
-----------------------------------------------------------------------------------------------
Fixed an issue where computer beleives mine is not guarded. Fix required combining new code check with old code.
Removed the bat files so it just uses the executable files.
Fixed an issue where amai hero would teleport home when hurt even though they are winning the battle.

Note: Similar issues could occur with neutral shops as what happened with the gold mines so shall keep on a lookout.

Idea: Right idea for town threatened system is as follows:
1) Low threat most threatened town - Just set defense position to that town  (1500 distance start)
2) Medium threat most threatened town - Send attack captain here only NOT FORCED (Blizzards town threat alarm not gone off but high threat) 
3) High threat most threatened town - Teleport and send attack FORCED ATTACK MOVE(Blizzards town threat alarm goes off plus high threat)

09/11/06 - Tech update
-----------------------------------------------------------------------------------------------
Fixed a crash that could occur as getexpfoe current_expansion_creeps variable was not set and had potential to be referred to before it had been set anything.
Fixed an issue where creeps guarding a mine could cause the checkexpansiontaken to return true. 

ERROR - ok so no idea whats causing the error where computer beleives mine is not guarded and tries to build mine.

08/11/06 - Tech update (RC1)
-----------------------------------------------------------------------------------------------
Updated all strengths of units to use the new system

ERROR: Replay "attack crash"  occurs right at end of game with humans not mopping up the orcs.
ERROR: Manual pics will need updating for the tutorial.

04/11/06 - Tech update
------------------------------------------------------------------------------------------------
Fixed a long time standing issue where amai would finish its attack even though some enemy structures are left in the area.
Fixed issue where amai would go back to attacking creeps when town was threated.
Removed an invalid global setting in ROC version and the setting comments are now next to the correct settings.

ERROR: Note get tower strength only adds 1 instead of getting the tower strength amount. Needs to be investigated.
	(Investigated and system here is correct)

03/11/06 - Tech update
------------------------------------------------------------------------------------------------
Fixed a rare bug in the attack sequence that could cause amai to never end attack due to loss of the original targets location.

02/11/06 - Tech update
------------------------------------------------------------------------------------------------
The amai and ai implementation broke the neutral hero system. Issue has now been reactified. (Need to update manual on amai vs ai)
Fixed some calculation errors in the peon builder system. In some cases not enough wood lumberers where being built.

IDEA: Even more accurate strength measurement would be the average of the level and food usage.
ERROR: Undead got stuck in an attack loop under "reforming until target dead" and failed to ever attack.

01/11/06 - Tech update
------------------------------------------------------------------------------------------------
Fixed an issue where heroes where having loads of item jobs all running on the one hero that each caused conflicts with each other and in some cases made it fail to get items.
Reduced teleport threat distances global settings to 4000,2500 from 5000,3000
The micro hero rule that checks enough strength now uses the army strength around hero instead of the players entire army.
Orange strength bonus increased to 2 up from 0

27/10/06 - Tech update
------------------------------------------------------------------------------------------------
Reduced town threatened no threat radius to 1500 from 3000.
Gimoire 0.6 implemented.

ERROR: Failed to build neutral hero on certain map.
ERROR: Failure to get emergency items.

23/10/06 - Tech update
------------------------------------------------------------------------------------------------
Fixed crash bug in ROC version of amai

ERROR: Town threatened system is definatly an issue with it incorrectly determining a town is threatened. Needs improving.
ERROR: AMAI will not properly retreat from creeps to counter a town threatened issue unless they town portal. They instead end up re-attacking creeps when they should put attention on base.

22/10/06 - Tech update
------------------------------------------------------------------------------------------------
Alot of Script clean up
Neutral buildings now uses similar creep detection used by the gold mines.

21/10/06 - Tech update
------------------------------------------------------------------------------------------------
Fixed crash in build loop caused by expansion_creeps group not set up for the fast expansion mine
Fixed an issue where racial shops are not built in certain strategies so races cannot heal.
Fixed an issue where whole computer stopped attacking when only 3 units harmed. Instead will do heal check once then attack. Only if the overall army condition is below a certain threshold will computer no longer attack till its healed.
Distraction attacks now occur only when the harass is 1/3 or less of the strength of the entire army.
Fixed an issue where tree of life would uproot when enemies are close by. It should only do so if area is clear
Tried to fix an issue where tree of life would not entangle mine and instead joined army. This occured because the reset timer ran out.
Calculation of strength now degrades the heroes strength if he is hurt.
Tweaks to hero bonus strength bonuses generally reducing them.
Fixed a missing Undead:S in certain language profiles.

20/10/06 - Tech update
------------------------------------------------------------------------------------------------
Fixed the issue where AMAI would build at mine before creeps had been dealt with (Finished)
Fixed an issue with the usage of scroll of healing as hero dosn't wait until army is near him
Modification to way advanced upgrades work so it now has a max prority it could be and should help prevent lengthening of time to next tier

ERROR: Heros can try to buy multiple items at same time. Not a problem if items are all at same shop but not when different as hero gets stuck moving between the two shops
ERROR/IDEA: If hero has no item space to heal army the ai is basically doing nothing which is a problem. If it has enough units shouldn't he really be creeping?
ERROR: Loads of errors replay saved. Orc built lounge late. Didn't try to build items. Other races the build code completly froze and stopped building anything.

19/10/06 - Tech update
------------------------------------------------------------------------------------------------
Finished system so all blizzard entertainment and other ai scripts for the original ai scripts are all compatible without requiring any changes what so ever
Fixed issue where canabilizing ghouls would keep switching between cannablizing and harvesting nearby wood when trying to heal
Fixed issues where AMAI would build at mine even when creeps where present at mine ( not finished as always a delay from when you first get current_expansion calculated)

18/10/06 - Original ai compatability update
------------------------------------------------------------------------------------------------
Code changes to the way units are set so that original ai code no longer needs any changes what so ever to work with AMAI

17/10/06 - MPQ system update
------------------------------------------------------------------------------------------------
Trying out a whole new mpq method using a tool called grimore that uses dll injection to load the ai files. This should fix those ROC using TFT stat issue and also allow people to use parameters to load game in window or use opengl etc. (loadmpq.config)

ERROR: ROC isn't working. The ai scripts keeps crashing before even racial scripts turn on ?????
ERROR: Might be an issue with upgrades where the advanced upgrade system is actually lengthening time to go to next tier because upgrade priority is higher.

16/10/06 - Ideas
------------------------------------------------------------------------------------------------
Have idea to solve last compatability issues between amai and normal ai so that no change at all is required.
same functions in both amai and ai are going to have a condition in function which determines whether to do amai or ai style of the function

14/10/06 - Tech update
------------------------------------------------------------------------------------------------
Human,orc and undead strategy optimizations so the anti strengths are more accurate to the game percentages.

ERROR: AMAI will try teleported to towns when the racial hall is not yet finished.

13/10/06 - Tech update
------------------------------------------------------------------------------------------------
Fixed the crash bugs in the pathing system.
Fixed the canpathtoloc function and system is much faster at its calculations.
Fixed an issue where exp_time_count was set after adding to build list instead of when expansion begins building.

IDEA/ERROR: Code change so that if tavern is actually impassible it can change the hero choices instead of just not building any hero. Problem is the skill set up is in the racial scripts.
IDEA: Might be a good idea to introduce the getamaiexpansionpeon in the respective racial strategies that use them. e.g. ancient expansions 

12/10/06 - Tech update
------------------------------------------------------------------------------------------------
Fixed a developer bug that when turning debug mode on could crash amai
Fixed issue where the GetExpansionpeon might not return a peon. Therefore added amai's own system to get a peon when that fails. This prevents lag in the build code in waiting for a peon.
Fixed a bug where the invisible unit used for pathing had a large collision size that could make amai believe mine was not pathable.
Fixed a bug where the amai would send a peon up to build expansion before creeps had been killed

ERROR: Seems the expansionbuilder code resets exp_time_count so if expansion not built on first pass you have to wait the same amount of time as set in strategy before it starts building.
IDEA: Then if no mine and no gold would need to do emergency harvesting. A Job script should be able to handle this.
ERROR: Canpathtoloc function is not developer friendly as uses integer ids that might not be available in a mod.
ERROR: canpathtoloc function new method cannot fail so whole system crashes waiting for the peon to reach a destination that will never come
ERROR: There seems to be a crash in pathing thread as makeexpansionlist never finishes

11/10/06 - Tech update
------------------------------------------------------------------------------------------------
Fixed the build loop crash bug

ERROR: Found error for orcs not building. Seems getexpansionpeon can fail which is interesting.
ERROR: AMAI crashing on start so fails to become active on race. Occured with both human and nightelf. Replay saved

09/10/06 - Tech update
------------------------------------------------------------------------------------------------
Fixed issue where sometimes amai would still not build at the mine location due to a variable not being set to 0
Small improvement to focus fire code

ERROR: Again orc failed to build farms at back of mine... WHAT IS GOING ON!!!!!
ERROR: The build crash also occured with nightelfs and orcs. Very odd seems they still build heroes and such but end up not building anything else. And sit there piling on resources but still attack and defend fine. Seems linked to the building of an expansion.
ERROR: Stuck on racial attack: assigning peons for undead but showed above behaviour of error. Acolytes didn't even go to harvest new mine. Replay saved.

08/10/06 - Tech update
------------------------------------------------------------------------------------------------
Fixed an issue where ziggurat selling job control wasn't working due to the same hash set system issue.
Strategy change only occurs after a certain threshold is reached so strategy is much better than current one and not similar. This is to prevent that constant strategy switching when its perfectly fine to stay put and computer dosn't have enough time to utilize strategy perfectly.
Reduced number of farms built at mine for orc player to 2 as this is the best against preventing peons getting stuck
Fixed an issue where farms built at mine could include an extra one due to use of towncountdone instead of just towncount
Undead,orc,human Strategy tweaks adding some spellcaster upgrades.
Fixed missing key strategy for the undead strategies using spellcasters.

ERROR: Apply table changes may not be working correctly. Fault of issue unknown
ERROR: The build at mine function failed to work for 1 player but worked for the others... Strange
ERROR: On test map 2 players never build at mine. This is most likely caused by initial estimate picking up the unpathable mine and system does not fix itself.
ERROR: Big build crash with humans. Peasant seemed to be frozen. Replay saved AMAI Human build crash

07/10/06 - Tech update
------------------------------------------------------------------------------------------------
Fixed an issue with the buildatmine function. It wasn't working due to unknown problems with the hash set system. New system all gold mines are refered too in the standardunits.txt instead of the global setting
Orcs now build the first 5 farms at rear of there base - WARNING can get peons stuck on some maps

ERROR: Emergency gold systems really need implementation as they show there idoitic selves.
ERROR: The ziggurat selling is also affected by the hash set system issue

IDEA: Strategy system needs to realise it only needs to change its strategy is at a big disadvantage. This is to prevent switching between two strategies because they have equal prorities.

06/10/06 - Tech update
------------------------------------------------------------------------------------------------
New Job added that aims to prevent errors in ancient expansion control and millitia where it beleives mine is not guarded because the creeps are temporarily chasing someone else.
Fixed an issue where natures blessing was never researched
Fixed an issue where lumber mills were not built next to lumber but in the middle of the base (affects main base only)
Some harasses have been disabled due to they were not effective. Still looking into how to improve harass to be much more effective. This does not affect distraction attacks which are purely to cause enemies main army to go elsewhere.

ERROR: Whole set3 system which records id's of the gold mines is broken

IDEA: Fast expanding should be occuring for tier 1 strategies while late expanding should be the tier rush

05/10/06 - Tech update
------------------------------------------------------------------------------------------------
Reduced front radius to 900 down from 1100
More elf strategy tweaks

IDEA: Use an invisible peon to determine where the most effecient place for a lumber mill would be

04/10/06 - Tech Update
------------------------------------------------------------------------------------------------
Changed Goblin Tinker abilities to choose rockets instead of pocket factory as pocket factory usage not too effective.
Tweak to elf strategies to reduce chance of dryads being picked against peircing units.
Commander text website links updated

IDEA: Upgrades chosen for strategy prorities get a bonus to there proirity in the advanced upgrade system

03/10/06 - Tech Update
------------------------------------------------------------------------------------------------
Fixed some missing needs for hippo riders and rocket tanks
Fixed an issue where only 3 peons would mine gold on the starting mine instead of 5

IDEA: Implement creep camp system to determine when creep camp truly is dead and the creeps are not off chasing someone

18/09/06 - Bug Forum Collection
------------------------------------------------------------------------------------------------
INFO: Tower rushes should be within first 5 mins of game or on moment of reaching tier 2. Use only guard towers and maybe 1 or 2 arcane if alot of magic/summons. Reccomend 4 or 5 peons,replaced with 2 or 3 wood peons. Use of human hero to but mini towers. Initially have peons build 3 towers. Build 3 more with hero.
IDEA: Improvements to the build code to try and remove the lock of waiting for a certain building to be built before building next etc. This can potentially be crippling.
ERROR:Team game issues. I guess if a team player has no target other player will not have a target either. so make idea:Introduce a way to get the armies to meet then go on to attack enemy.
ERROR:Necros following DK when it is hurt (likely hard coded - flight and fight type behaviour)
ERROR/IDEA: burrows shouldn't be at front of base. 
ERROR: everytime peon returns gold he stops to change resource. (1 out of 5 peons)
ERROR: Mass woodcutters and 5 workers on gold mine after early tech is lowest income

25/07/06 - Techincal Build Update
------------------------------------------------------------------------------------------------
Fast expansion check is now moved above the new calculation but after the old calculation as the new system takes a while to finish and by then it wont be much of a fast expansion.
Ancient expansion should now only coordinate with tree of life if army is weaker than the creeps.
Balance adjustments to upgrades so they are more likely to be researched for certain upgrades.
Fixed a hippo rider bug where it didn't know the requirements to build a hippo rider.
In ffa reduced liklyhood of tower rush, although its still possible for amai to do the rush.

ERROR:AMAI town portalling when ally is being tower rush, instead should just walk hero home.
Idea: Usage of wisps to dispel summons of summon heros.
Idea: NE could use ancient protectors to walk close to trees and attack at a range, with wisp repairing.

24/07/06 - Beta 9 Feedback Collection
------------------------------------------------------------------------------------------------
Fixed the warcraft lag and crash bug. Reuploaded files.

ERROR:Turn off or reduce tower rush in ffa
ERROR:Strategy upgrades just not having the prority e.g. bears dont build any upgrades till alot of bears are made.
ERROR:Ancient expansion army should only coordinate with tree of life if there army is weaker than the creeps.
ERROR:Retreat control needs to include ally towns but only goes if his own town isn't threatened
ERROR:Fast expansion system check is after the choose expansion system so wont calculate it all pathing is done. By then its not longer a fast expansion.
ERROR:Turtle rock has innefective night elf expansion
ERROR:Rock Quarry(8) has reported issue of gold mine empty then attack issue
ERROR: Militia expansion on avalanche seems to end up with computer multi-tasking

21/07/06
------------------------------------------------------------------------------------------------
Fixed issue where night elfs sometimes wouldn't fill up mines when they all harvesting lumber.
Small fixes to militia to make sure gold_buffer active so amai is saving resources to build the town hall once they go to clear it out.
Fixed issue where extra peasants where not going to fast build the town hall.
Fixed an issue where getexpansionstrength was using incorrect calculation.
Fixed issue with militia expansion not working on maps with bigger maps where center of map is far from the starting point.
The mine calculated quickly for fast expansions will have a 25% chance of choosing a second mine if there is one available which is also as close and is orange creeps.

Idea: when calculating front for towers, why not use calculation from the enemy. As they may take a different route to your base if bases have multiple exits.
Note: Remember to keep thinking about future team game improvements.

Manual: Need to add requirement of latest perl

20/07/06
------------------------------------------------------------------------------------------------
Fixed issue where racial_expansion was used in non undead scripts. Now its valid for all races.
Removed the requirement of only 2 certain heros can tower rush or ancient expand. Its now down to the added bonus setting in the standard units.txt. Removed some obsolete variables from global settings.txt
When hero is hurt and goes to buy healing potion. If he cannot he can now buy other items as well which are set in the healingitems.txt file. Removed racial_healing_item variable from racial settings.txt
Removed the code for ancient expansion that uses waits so could mess up the job system. Now is all tightly integrated into the gold mine expansion list system.
Tweaked hero choice of priestess of the moon to have a 25 prority down from 34 for first hero.
NightElf Ancient Expansion priority has been set to 43% due to much smarter behaviour.
More bug fixes to night elf ancient expansion. Compared to the old betas, the random bugs that used to occur have been squished. Now only time i have seen this fail is because wisp got stuck due to cramped base :P

Idea: Heroes with non-ultimate summons should maybe have summon strength added to there bonus, instead of the summons themselves having them. Might be risky though.
Continuing Note: Make it so militia expansion and/or ancient expansion have a chance to occur for each gold mine instead of a one time check and then basically doing it only once.

19/07/06
------------------------------------------------------------------------------------------------
Fixed issue where after town portal the captain is still at the last attack location.
Did some balancing to the global harasses.
Fixed an issue where distraction attacks were calculating strength of player without detecting of healing units. So would do distraction even if army was in a critcal state to be able to do such.
Loads of improvements to nightelf ancient expansion technique, also now a 45% chance to occur up from 33%.

NOTE: racial_expansion is a undead variable yet is used in many non undead related places.
NOTE: Going to be complicated to get tree of life to eat trees when in racial expansion attack.
NOTE: Need to get rid of the racial settings that check you have certain heroes to do the expansion. Instead should use the rush bonus from the standardunits.txt as can then work with certain neutral heros too.
NOTE: Make it so militia expansion and/or ancient expansion have a chance to occur for each gold mine instead of a one time check and then basically doing it only once.
NOTE: ancient expansion chance currently on 100%. Need to remember to set back to 45%.

18/07/06
------------------------------------------------------------------------------------------------
Ghoul cannabalize issue now finished without using graveyard fix.
Buying of healing items now bypasses the usual build queue to try and build when possible.
Commented out captianflee variable as is useless and not used.
Militia Expansion attack code uses the new attack creep code variation.
Fixed the issue where amai will stop attack then go back on attack when it enters attack state.
Fixed an issue where if there is no pathable goblin merchant it will never buy its own shop items.
Modified DefendTownsCond to include a max_dist
Implementation of DefendTownsCond for undead in for construction of graveyards or necropolis at mines if conditions are satisfied. This hopefully prevent issues where ghouls have nothing to harvest and provide places to town portal too for bases further away.
Fixed a generic bug in healing code when using single healing items.
Undead now buy healing scrolls from a merchant if it is not tier 3.
Increased percentages slightly for tower rush so its now 25% for close choice, 16% choice further away, and 7% for furthest allowed distance.
Fixed an issue where AMAI wont build the requirement to be able to tower rush.
Now playing around with captain positions for threatened towns as well as tower rush to improve play effectiveness.
Tower rush now ends if the player being rushed is killed.

Note: Blizzards sick joke of human peasants mass repairing something when its under construction and no ones building it is starting to annoy me !!!!! 
Note: Seems to be an issue present that after for example a town portal the units go back to attack there fighting location. Its rare but happens. Just need to make sure attack captain is back at home.
Note: Somewhere can be seen in lost temple, one of the recovery systems likely fountain if units go home the send home system stopped working.


17/07/06
------------------------------------------------------------------------------------------------
Continuing implementation of the tag unit debug information.
Fixed an issue where ghouls where trying to cannabalize moment research was done even when no corpses around.
Fixed an issue where ghouls cannabalize to heal but do not move to the graveyard.
Fixed an issue where battle radius when creeping was using the normal battle radius.
Fixed an issue where player would do distraction attacks when creeping.
Fixed an issue where if AMAI was creeping he would never flee and give up correctly.
Fixed an issue that could occur causing AMAI to flee prematurely.
Fix more issues with the defend town code such as players strength not being updated during loop.

NOTE: Captain flee seems to be an old unused variable only present in militia code. May be removable.
NOTE: Ghouls cannabalize still not fixed. Lets add check for the graveyard itself.
NOTE: Orc healing in emergency the buying of healing items need to be seperated so it can buy them no matter what build order.

16/07/06
------------------------------------------------------------------------------------------------
Blizzard.j file was using older patch version data which could of caused some issues. Now the latest 1.20 data as it should be.
New Debug information method where info is added as a tag to the unit. The tags are color coded
to have a better idea which player the tag came from. Also hero tags will display hero in name.

04/07/06
------------------------------------------------------------------------------------------------
Finished implementation of fix to the undead ghouls failing to aid attack
Fixed an issue where militia if fails first time it will not work again.
Militia may just randomly decide to return home and is possible due to note above. Hopefully added a detterant to prevent that for now.
Fixed an issue where the town_threatened control to return home was not looping due to return command in inaccurate place.

Idea: Implement idea so if all heroes not available then will use a unit replacement until hero ready again. This is for functionality of certain jobs that at moment requires a hero to work. e.g. focus fire.
Idea: The Army Detection systems could be improved to just change defense captain when low threat then force units there in high threat. This should hopefully prevent issues where units become stuck in loop when its marginally still quite low threat.
Note: issue above is a direct result of Harvest command which is what tried to overide militia expansion behaviour
Note/Idea: break_attack made attack systems exit but also allows regrouping to occur. I want to take out this entire repetition and implement all this in the current attack loop instead of running the function call again that makes tracking whats happening difficult.
Error Noted: Team players are just not realising enemies in ally towns as a threat which can result in teams defeat by each player being outnumbered.

02/07/06
------------------------------------------------------------------------------------------------
Hopefully fixed some undead behaviour where ghouls couldn't attack as were re-routed back to harvest
Fixed issue where night elfs still were failing to use the moonstone effectivly.
More core attack segment improvements - Debug messages added
Note: break_attack might be a factor in ending attacks artificially early - Needs checking

01/07/06
------------------------------------------------------------------------------------------------
Modified some rush bonus strength settings for a few neutral heroes.
Tweaked strategy settings to improve millitia expansion builds further.
Modification of an extremly old core attack segment to keep AMAI from exiting battle systems early once it killed the single target it was after.
Another modification so that the core attack segment ends when the army truly is fleeing using the new setting that was added.

30/07/06
------------------------------------------------------------------------------------------------
Fixed some commander text that still was pointing to wc3campaigns  

Fixed zepplin issue that could occur causing zepplins to constantly pick up and drop unit its supposed to be unloading. 
Heroes now have bonus strengths depending on there harassing abilties and relative strength. So with those heroes and an agressive profile they should once again do single hero harasses or go straight to creeping instead of sitting back waiting.
Fixed some pathing determination issues on large maps.. 
Fixed some grave errors in profile strength calculations where some unit types where calculated twice making computers appear stronger and profile choice would be further biased. 
The new retreat system has been improved to take account of the profiles aggression. The higher the aggression the more enemy units needed to make the computer retreat. 
Fixed an issue related to ghoul harvesting when wood rescource was low the attacking ghouls would be set to only 4 no matter what. This meant the ai's strength would also be incorrectly calculated as low. Now it is changed to be max 4 harvesting. The ghouls will still all harvest when no attack is running. 
Fixed two amai script crashes when buying neutral units or items.
Missed a defend town code that didn/t have the knew let it die detection features in
Militia Expansion systems have been further improved and optimized. The militia sent will stay up there a build the hall. This dosn't include fast building it. That has yet to be optimized. 
Town hall human fast building has been modulised into a job in preparation of making it work for any building you wish. (This is to allow humans to be extremly effective at quickly building up base hopefully in the future)
Fixed an issue where illusions where being healed and treated as real units. This should prevent AMAI trying to save illusion units. 
Militia expansion chance increased to 60% from 40% due to much smarter behaviour. 
Fixed an issue with the functionality for using the moonstone.
Fixed an issue where player wont retreat to save his threatened town. (currently working on) 
