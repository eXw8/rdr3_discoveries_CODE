## Some COMBAT ATTRIBUTES Flags

## Example

```lua
	Citizen.InvokeNative(0x9F7794730795E019,ped_id,116,true)  -- SET_PED_COMBAT_ATTRIBUTES Set CA_PREFER_DUAL_WIELD enabled;
```

<h2>Some known COMBAT ATTRIBUTES Flags.</h2>

FlagId | COMBAT ATTRIBUTE Action Result
----------- | --------------------------
0 | CA_USE_COVER
1 | CA_USE_VEHICLE
2 | CA_DO_DRIVEBYS
3 | CA_LEAVE_VEHICLES
4 | CA_STRAFE_BASED_ON_TARGET_PROXIMITY
5 | CA_ALWAYS_FIGHT
6 | CA_FLEE_WHILST_IN_VEHICLE
7 | CA_JUST_FOLLOW_VEHICLE
8 | CA_ALLOW_STRAFE_BREAKUP
9 | CA_WILL_SCAN_FOR_DEAD_PEDS
10 | 
11 | CA_JUST_SEEK_COVER
12 | CA_BLIND_FIRE_IN_COVER
13 | CA_COVER_SEARCH_IN_ARC_AWAY_FROM_TARGET
14 | CA_CAN_INVESTIGATE
15 | CA_CAN_USE_RADIO
16 | CA_STRAFE_DUE_TO_BULLET_EVENTS
17 | CA_ALWAYS_FLEE
18 | 
19 | 
20 | CA_CAN_TAUNT_IN_VEHICLE
21 | CA_CAN_CHASE_TARGET_ON_FOOT
22 | CA_WILL_DRAG_INJURED_PEDS_TO_SAFETY
23 | 
24 | CA_USE_PROXIMITY_FIRING_RATE
25 | CA_DISABLE_SECONDARY_TARGET
26 | CA_DISABLE_ENTRY_REACTIONS
27 | CA_PERFECT_ACCURACY
28 | CA_CAN_USE_FRUSTRATED_ADVANCE
29 | CA_MOVE_TO_LOCATION_BEFORE_COVER_SEARCH
30 | ped can shoot without los
31 | CA_MAINTAIN_MIN_DISTANCE_TO_TARGET
32 | 
33 | 
34 | CA_ALLOW_PROJECTILE_SWAPS_AFTER_REPEATED_THROWS
35 | CA_DISABLE_PINNED_DOWN
36 | CA_DISABLE_PIN_DOWN_OTHERS
37 | CA_OPEN_COMBAT_WHEN_DEFENSIVE_AREA_IS_REACHED
38 | CA_DISABLE_BULLET_REACTIONS
39 | CA_CAN_BUST
40 | CA_IGNORED_BY_OTHER_PEDS_WHEN_WANTED
41 | CA_CAN_COMMANDEER_VEHICLES
42 | CA_CAN_FLANK
43 | CA_SWITCH_TO_ADVANCE_IF_CANT_FIND_COVER
44 | CA_SWITCH_TO_DEFENSIVE_IF_IN_COVER
45 | CA_CLEAR_PRIMARY_DEFENSIVE_AREA_WHEN_REACHED
46 | CA_CAN_FIGHT_ARMED_PEDS_WHEN_NOT_ARMED
47 | CA_ENABLE_TACTICAL_POINTS_WHEN_DEFENSIVE
48 | CA_DISABLE_COVER_ARC_ADJUSTMENTS
49 | CA_USE_ENEMY_ACCURACY_SCALING
50 | CA_CAN_CHARGE
51 | CA_REMOVE_AREA_SET_WILL_ADVANCE_WHEN_DEFENSIVE_AREA_REACHED
52 | CA_USE_VEHICLE_ATTACK
53 | CA_USE_VEHICLE_ATTACK_IF_VEHICLE_HAS_MOUNTED_GUNS
54 | CA_ALWAYS_EQUIP_BEST_WEAPON
55 | CA_CAN_SEE_UNDERWATER_PEDS
56 | CA_DISABLE_AIM_AT_AI_TARGETS_IN_HELIS
57 | CA_DISABLE_SEEK_DUE_TO_LINE_OF_SIGHT
58 | CA_DISABLE_FLEE_FROM_COMBAT
59 | CA_DISABLE_TARGET_CHANGES_DURING_VEHICLE_PURSUIT
60 | CA_CAN_THROW_SMOKE_GRENADE
61 | 
62 | CA_CLEAR_AREA_SET_DEFENSIVE_IF_DEFENSIVE_CANNOT_BE_REACHED
63 | 
64 | CA_DISABLE_BLOCK_FROM_PURSUE_DURING_VEHICLE_CHASE
65 | CA_DISABLE_SPIN_OUT_DURING_VEHICLE_CHASE
66 | CA_DISABLE_CRUISE_IN_FRONT_DURING_BLOCK_DURING_VEHICLE_CHASE
67 | CA_CAN_IGNORE_BLOCKED_LOS_WEIGHTING
68 | CA_DISABLE_REACT_TO_BUDDY_SHOT
69 | CA_PREFER_NAVMESH_DURING_VEHICLE_CHASE
70 | CA_ALLOWED_TO_AVOID_OFFROAD_DURING_VEHICLE_CHASE
71 | CA_PERMIT_CHARGE_BEYOND_DEFENSIVE_AREA
72 | CA_USE_ROCKETS_AGAINST_VEHICLES_ONLY
73 | CA_DISABLE_TACTICAL_POINTS_WITHOUT_CLEAR_LOS
74 | CA_DISABLE_PULL_ALONGSIDE_DURING_VEHICLE_CHASE
75 | 
76 | 
77 | CA_DISABLE_RESPONDED_TO_THREAT_BROADCAST
78 | CA_DISABLE_ALL_RANDOMS_FLEE
79 | CA_WILL_GENERATE_DEAD_PED_SEEN_SCRIPT_EVENTS
80 | 
81 | CA_FORCE_STRAFE
82 | 
83 | 
84 | 
85 | 
86 | 
87 | 
88 | 
89 | 
90 | 
91 | CA_USE_RANGE_BASED_WEAPON_SELECTION
92 | 
93 | CA_PREFER_MELEE
94 | 
95 | 
96 | 
97 | 
98 | 
99 | 
100 | 
101 | CA_RESTRICT_IN_VEHICLE_AIMING_TO_CURRENT_SIDE
102 | 
103 | 
104 | 
105 | CA_CAN_CRUISE_AND_BLOCK_IN_VEHICLE
106 | CA_PREFER_AIR_COMBAT_WHEN_IN_AIRCRAFT
107 | CA_ALLOW_DOG_FIGHTING
108 | CA_PREFER_NON_AIRCRAFT_TARGETS
109 | CA_PREFER_KNOWN_TARGETS_WHEN_COMBAT_CLOSEST_TARGET
110 | 
111 | 
112 | 
113 | CA_USE_INFINITE_CLIPS
114 | CA_CAN_EXECUTE_TARGET
115 | CA_DISABLE_RETREAT_DUE_TO_TARGET_PROXIMITY
116 | CA_PREFER_DUAL_WIELD
117 | CA_WILL_CUT_FREE_HOGTIED_PEDS
118 | CA_TRY_TO_FORCE_SURRENDER
119 | 
120 | if false, ped will not holster their secondary weapon
121 | 
122 | 
123 | 
124 | 
125 | CA_QUIT_WHEN_TARGET_FLEES_INTERACTION_FIGHT
126 | 
127 | 
128 | 
129 | 
130 | 
131 | CA_PREVENT_UNSAFE_PROJECTILE_THROWS
132 | 
133 | CA_DISABLE_BLANK_SHOTS
134 | 
