{
    "name": "Rotom",
    "author": "RiceKirby",
    "summary": "Everyone starts as a Rotom and has to choose a form. And then wipe out the other forms. All players can Inspect 2 times during the game. [MOW: Daykill] - [WASH: +20 votes] - [HEAT: 2x Poison, Distract] - [FROST: Recruiter] - [FAN: Nightkill]",
    "minplayers": 3,
    "sides": [
        {
            "side": "village",
            "translation": "Rotom",
            "color": "#cc00cc",
            "winmsg": "*** O.O *** The Normal Rotoms won?!?! How the hell did ~Players~ do that?"
        },
        {
            "side": "grass",
            "translation": "Lawnmowers",
            "color": "#008000",
            "winmsg": "Suddenly, all Lawnmowers in the city started moving on its own! I bet this is ~Players~'s prank!:"
        },
        {
            "side": "water",
            "translation": "Washing Machines",
            "color": "#0000ff",
            "winmsg": "Suddenly, all Washing Machines in the city started moving on its own! I bet this is ~Players~'s prank!:"
        },
        {
            "side": "fire",
            "translation": "Microwave Ovens",
            "color": "#ff0000",
            "winmsg": "Suddenly, all Microwave Ovens in the city started moving on its own! I bet this is ~Players~'s prank!:"
        },
        {
            "side": "ice",
            "translation": "Refrigerators",
            "color": "#0099cc",
            "winmsg": "Suddenly, all Refrigerators in the city started moving on its own! I bet this is ~Players~'s prank!:"
        },
        {
            "side": "flying",
            "translation": "Electric Fans",
            "color": "#cc6600",
            "winmsg": "Suddenly, all Electric Fans in the city started moving on its own! I bet this is ~Players~'s prank!:"
        },
        {
            "side": "rice",
            "translation": "Rice Cookers",
            "winmsg": "~Players~'s and their Rice Cookers have dominated the other Rotoms! Rice for everyone!:"
        },
        {
            "side": "shiny",
            "translation": "Shiny Rotom",
            "winmsg": "Rare and unbeatable! ~Players~, the Shiny Rotom, has triumphed over everyone else!"
        },
        {
            "side": "pen",
            "translation": "Pen Rotom",
            "winmsg": "Mightier than the sword, ~Players~, the Pen Rotom, proved their worth!"
        }
    ],
    "tips": {
        "Inspecting": "Don't forget you can inspect, but use that information carefully.",
        "Revealing": "Revealing another player could get you an easy lynch, but also turn their partners against you.",
        "Fake Claiming": "Fake-claiming to an opponent in PM can be a good way to control another side and protect yourself from them.",
        "Advantages": "All forms have a form they are weak and a form they are strong against. The order is Wash beats Heat beats Frost beats Fan beats Mow beats Wash."
    },
    "variables": {
        "hiddenRoles": false,
        "MaxInspections": 2,
        "prio_rotom_change": 0,
        "prio_rice_change": 0,
        "prio_heat_distract": 1,
        "prio_wash_protect": 2,
        "prio_mow_kill2": 3,
        "prio_heat_poison": 4,
        "prio_frost_convert": 5,
        "prio_mow_kill": 6,
        "prio_shiny_demote": 6,
        "prio_shiny_kill": 7,
        "prio_shiny_poison": 8,
        "prio_rotom_shock": 9,
        "prio_rotom_inspect": 9,
        "PoisonDie": {
            "mode": "die",
            "msg": "Someone tried to heat you, but being full of ice made you melt instantly!",
            "targetmsg": "Your target (~Self~) melted instantly from your heat!"
        },
        "SilentIgnore": {
            "mode": "ignore",
            "silent": true
        },
        "CommonInspect": {
            "target": "AnyButSelf",
            "common": "Self",
            "priority": "variable:prio_rotom_inspect",
            "hide": true
        },
        "ConvertToMow": {
            "command": "convert",
            "target": "OnlySelf",
            "common": "Self",
            "priority": "variable:prio_rotom_change",
            "newRole": "grass",
            "cancel": [
                "heat",
                "wash",
                "frost",
                "fan",
                "random"
            ],
            "silent": true,
            "hide": true
        },
        "ConvertToWash": {
            "command": "convert",
            "target": "OnlySelf",
            "common": "Self",
            "priority": "variable:prio_rotom_change",
            "newRole": "water",
            "cancel": [
                "heat",
                "frost",
                "fan",
                "mow",
                "random"
            ],
            "silent": true,
            "hide": true
        },
        "ConvertToHeat": {
            "command": "convert",
            "target": "OnlySelf",
            "common": "Self",
            "priority": "variable:prio_rotom_change",
            "newRole": "fire",
            "cancel": [
                "wash",
                "frost",
                "fan",
                "mow",
                "random"
            ],
            "silent": true,
            "hide": true
        },
        "ConvertToFrost": {
            "command": "convert",
            "target": "OnlySelf",
            "common": "Self",
            "priority": "variable:prio_rotom_change",
            "newRole": "ice",
            "cancel": [
                "heat",
                "wash",
                "fan",
                "mow",
                "random"
            ],
            "silent": true,
            "hide": true
        },
        "ConvertToFan": {
            "command": "convert",
            "target": "OnlySelf",
            "common": "Self",
            "priority": "variable:prio_rotom_change",
            "newRole": "flying",
            "cancel": [
                "heat",
                "wash",
                "frost",
                "mow",
                "random"
            ],
            "silent": true,
            "hide": true
        },
        "ConvertToRandom": {
            "command": "convert",
            "target": "OnlySelf",
            "common": "Self",
            "priority": "variable:prio_rotom_change",
            "newRole": {
                "random": {
                    "grass": 0.2,
                    "fire": 0.2,
                    "ice": 0.2,
                    "water": 0.2,
                    "flying": 0.2,
                    "shiny2": 0.04,
                    "rice": 0.0133,
                    "rice2": 0.0133,
                    "rice3": 0.0133,
                    "pen": 0.02
                }
            },
            "cancel": [
                "heat",
                "wash",
                "frost",
                "fan",
                "mow"
            ],
            "silent": true,
            "hide": true
        },
        "evadeCharges": {
            "mode": {
                "evadeCharges": 1
            }
        },
        "shock": {
            "mode": "die",
            "msg": "You have been electrified!",
            "targetmsg": "Your target (~Self~) died electrified!"
        },
        "shockCommand": {
            "command": "dummy2",
            "target": "AnyButSelf",
            "common": "Self",
            "priority": "variable:prio_rotom_shock",
            "limit": 5,
            "initialrecharge": 5,
            "pierce": true
        },
        "dieToInspect": {
            "mode": "die",
            "msg": "You are so fragile that a mere inspect has killed you!!",
            "targetmsg": "Your target (~Self~) was too fragile and died when you inspected them!"
        }
    },
    "roles": [
        {
            "role": "rotom",
            "translation": "Rotom",
            "side": "village",
            "help": "You can possess a machine and get a new power! Type /mow, /wash, /heat, /frost, /fan or /random to change forms. Twice during the game (even after changing forms), you can type /inspect [name] at night to find someone's role (20% chance of working, 100% after converting). Until you change forms, you have a voteshield of +2 and you will die instantly if you are inspected, poisoned or distracted! ",
            "info": "Can transform itself into Mow, Wash, Heat, Frost or Fan Rotom. Can inspect 2 times during the game (20% chance of working, 100% after converting). Die instantly if inspected, poisoned or distracted. Sided with Rotom.",
            "actions": {
                "night": {
                    "mow": "variable:ConvertToMow",
                    "wash": "variable:ConvertToWash",
                    "heat": "variable:ConvertToHeat",
                    "frost": "variable:ConvertToFrost",
                    "fan": "variable:ConvertToFan",
                    "random": "variable:ConvertToRandom",
                    "inspect": {
                        "target": "AnyButSelf",
                        "common": "Self",
                        "priority": "variable:prio_rotom_inspect",
                        "charges": "variable:MaxInspections",
                        "Sight": {
                            "true": 0.2,
                            "false_inspect": 0.8
                        },
                        "hide": true
                    }
                },
                "distract": {
                    "mode": "die",
                    "msg": "You are so fragile that a mere distract has killed you!!",
                    "targetmsg": "Your target (~Self~) was too fragile and died when you distracted them!"
                },
                "poison": {
                    "mode": "die",
                    "msg": "You are so fragile that a mere poison has instantly killed you!!",
                    "targetmsg": "Your target (~Self~) was too fragile and died instantly when you poisoned them!"
                },
                "voteshield": 2,
                "dummy2": "variable:shock",
                "inspect": "variable:dieToInspect"
            }
        },
        {
            "role": "rotom2",
            "translation": "Rotom",
            "side": "village",
            "help": "You got demoted, but you can possess a machine again to get a new power! Type /mow, /wash, /heat, /frost, /fan or /random to change forms. ",
            "hide": true,
            "actions": {
                "night": {
                    "mow": "variable:ConvertToMow",
                    "wash": "variable:ConvertToWash",
                    "heat": "variable:ConvertToHeat",
                    "frost": "variable:ConvertToFrost",
                    "fan": "variable:ConvertToFan",
                    "random": "variable:ConvertToRandom",
                    "inspect": {
                        "target": "AnyButSelf",
                        "common": "Self",
                        "priority": "variable:prio_rotom_inspect",
                        "Sight": {
                            "true": 0.2,
                            "false_inspect": 0.8
                        },
                        "hide": true
                    }
                },
                
                "distract": {
                    "mode": "die",
                    "msg": "You are so fragile that a mere distract has killed you!!",
                    "targetmsg": "Your target (~Self~) was too fragile and died when you distracted them!"
                },
                "poison": {
                    "mode": "die",
                    "msg": "You are so fragile that a mere poison has instantly killed you!!",
                    "targetmsg": "Your target (~Self~) was too fragile and died instantly when you poisoned them!"
                },
                "voteshield": 2,
                "dummy2": "variable:shock",
                "inspect": "variable:dieToInspect"
            }
        },
        {
            "role": "grass",
            "translation": "Mow Rotom",
            "side": "grass",
            "help": "You possessed a Lawnmower! You can type /kill [name] during the day to defeat another Rotom without revealing yourself. You also survive 1 lynch per game!",
            "info": "Can kill one person during the standby. Survives 1 lynch. ~Sided~",
            "players": "Convert from Rotom",
            "actions": {
                "night": {
                    "inspect": "variable:CommonInspect"
                },
                "standby": {
                    "kill": {
                        "target": "AnyButSelf",
                        "msg": "You can kill now by using /kill [name]!",
                        "killmsg": "A lawnmower ran over ~Target~!",
                        "initialrecharge": 2
                    }
                },
                "lynch": {
                    "convertTo": "grass2",
                    "convertmsg": "A Mow Rotom escaped the votes and survived the lynch!"
                },
                "dummy2": "variable:shock"
            }
        },
        {
            "role": "grass2",
            "translation": "Mow Rotom",
            "side": "grass",
            "help": "You possessed a Lawnmower! You can type /kill [name] during the day to defeat another Rotom without revealing yourself. You already escaped a lynch, so the next one will be fatal!",
            "hide": true,
            "actions": {
                "night": {
                    "inspect": "variable:CommonInspect"
                },
                "standby": {
                    "kill": {
                        "target": "AnyButSelf",
                        "msg": "You can kill now by using /kill [name]!",
                        "killmsg": "A lawnmower ran over ~Target~!"
                    }
                },
                "dummy2": "variable:shock"
            }
        },
        {
            "role": "water",
            "translation": "Wash Rotom",
            "side": "water",
            "help": "You possessed a Washing Machine! Your vote counts as +20, and you can use /protect [name] once during the game to protect anyone (even yourself) from any night action (you must wait 1 turn before that though). You also evade poison once per game.",
            "info": "Vote counts as 20. Can protect + safeguard (including self) once per game. Evades poison once per game. ~Sided~",
            "players": "Convert from Rotom",
            "actions": {
                "night": {
                    "inspect": "variable:CommonInspect",
                    "protect": {
                        "command": ["safeguard", "protect"],
                        "target": "Any",
                        "common": "Self",
                        "priority": "variable:prio_wash_protect",
                        "charges": 1,
                        "initialrecharge": 2
                    }
                },
                "vote": 20,
                "poison": "variable:evadeCharges",
                "dummy2": "variable:shock"
            }
        },
        {
            "role": "fire",
            "translation": "Heat Rotom",
            "side": "fire",
            "help": "You possessed a Microwave Oven! You can type /poison [name] twice during the night to kill your targets during the next night. You can also type /distract [name] during the nights to prevent someone else from using their actions. You also evade conversion once per game, takes longer to die to poison and identify any other Heat that distracts you.",
            "info": "Can poison 2 persons during the night. Can distract one person during the night. Evades 1 convert per game. Takes 2 nights to die to poison. Identify distractors. ~Sided~ ",
            "players": "Convert from Rotom",
            "actions": {
                "night": {
                    "poison": {
                        "target": "AnyButSelf",
                        "common": "Self",
                        "priority": "variable:prio_heat_poison",
                        "count": 2,
                        "limit": 2,
                        "poisonDeadMessage": "You melted after being exposed to the microwaves for too long!"
                    },
                    "distract": {
                        "command": ["distract"],
                        "target": "AnyButSelf",
                        "common": "Self",
                        "priority": "variable:prio_heat_distract",
                        "distractmsg": "A Heat Rotom had put you on the Microwave Oven for 1 turn, so you had to wait patiently."
                    },
                    "inspect": "variable:CommonInspect"
                },
                "distract": {
                    "mode": "identify"
                },
                "convert": "variable:evadeCharges",
                "poison": {
                    "mode": "resistance",
                    "constant": 1
                },
                "dummy2": "variable:shock"
            }
        },
        {
            "role": "ice",
            "translation": "Frost Rotom",
            "side": "ice",
            "help": "You possessed a Refrigerator! You can type /convert [name] every night to transform another kind of Rotom into a Frost Rotom. You evade one nightkill per game, but you die instantly if poisoned.",
            "info": "Can convert one person to Frost Rotom during the night. Evades 1 nightkill per game. Instantly dies if poisoned. ~Sided~",
            "players": "Convert from Rotom",
            "actions": {
                "night": {
                    "convert": {
                        "target": "AnyButSelf",
                        "common": "Self",
                        "priority": "variable:prio_frost_convert",
                        "newRole": "ice",
                        "canConvert": [
                            "rotom",
                            "fire",
                            "water",
                            "grass",
                            "grass2",
                            "flying",
                            "shiny",
                            "shiny2",
                            "rice",
                            "rice2",
                            "rice3"
                        ],
                        "convertusermsg": "Your target (~Target~) is now a ~New~! You should PM them!",
                        "convertmsg": "A ~Old~ was cooled until it became a ~New~!"
                    },
                    "inspect": "variable:CommonInspect"
                },
                "convert": {
                    "mode": {
                        "ignore": ["ice"]
                    }
                },
                "poison": "variable:PoisonDie",
                "kill": "variable:evadeCharges",
                "dummy2": "variable:shock"
            }
        },
        {
            "role": "flying",
            "translation": "Fan Rotom",
            "side": "flying",
            "help": "You possessed an Electric Fan! Type /kill [name] during the night to defeat another Rotom. Every 2 nights, you can also use /kill2 [name] to defeat a 2nd target. You evade one daykill per game.",
            "info": "Can kill one person during the night. Can kill2 one person every 2 nights. Evades 1 daykill per game. ~Sided~",
            "players": "Convert from Rotom",
            "actions": {
                "night": {
                    "kill": {
                        "target": "AnyButSelf",
                        "common": "Self",
                        "priority": "variable:prio_mow_kill",
                        "msg": "A Fan Rotom's wind blew you away!"
                    },
                    "kill2": {
                        "command": "kill",
                        "target": "AnyButSelf",
                        "common": "Self",
                        "priority": "variable:prio_mow_kill2",
                        "msg": "A Fan Rotom's wind blew you away!",
                        "recharge": 2,
                        "initialrecharge": 2
                    },
                    "inspect": "variable:CommonInspect"
                },
                "daykill": "variable:evadeCharges",
                "dummy2": "variable:shock"
            }
        },
        
        {
            "role": "shiny",
            "translation": "Shiny Rotom",
            "side": "shiny",
            "help": "WAIT, YOU ARE SHINING! You can't change forms, but you can /kill [name] both during the night and day, /poison [name] and even /demote [name] every night to make another player become a normal Rotom again (You can not act during the 1st night)! You are also immune to distractions, and whoever inspects you will see you as their ally! You can't inspect though!",
            "info": "Can kill, poison and demote during the night. Can kill during the standby. Cannot be distracted. Inspected as the same role of the person that inspected it. Bypass any protection. Sided with Shiny Rotom. ",
            "hide": "variable:hiddenRoles",
            "actions": {
                "night": {
                    "kill": {
                        "target": "AnyButSelf",
                        "common": "Self",
                        "priority": "variable:prio_shiny_kill",
                        "msg": "The Shiny Rotom was too bright for your eyes!",
                        "initialrecharge": 2,
                        "pierce": true,
                        "hide": "variable:hiddenRoles"
                    },
                    "poison": {
                        "target": "AnyButSelf",
                        "common": "Self",
                        "priority": "variable:prio_shiny_poison",
                        "count": 2,
                        "poisonDeadMessage": "You couldn't stand the Shiny Rotom's poisonous attack, and thus died!",
                        "initialrecharge": 2,
                        "pierce": true,
                        "hide": "variable:hiddenRoles"
                    },
                    "demote": {
                        "command": "convert",
                        "target": "AnyButSelf",
                        "common": "Self",
                        "priority": "variable:prio_shiny_demote",
                        "newRole": "rotom2",
                        "canConvert": [
                            "fire",
                            "ice",
                            "flying",
                            "water",
                            "grass",
                            "grass2",
                            "rice",
                            "rice2",
                            "rice3"
                        ],
                        "convertmsg": "A ~Old~ was demoted and became a normal ~New~ again!",
                        "initialrecharge": 2,
                        "pierce": true,
                        "hide": "variable:hiddenRoles"
                    }
                },
                "standby": {
                    "kill": {
                        "target": "AnyButSelf",
                        "msg": "Time to shine! Type /kill [name] to defeat another Rotom!",
                        "killmsg": "Shiny Rotom used Thunderbolt! ~Target~ has fainted!",
                        "revealChance": 0,
                        "revealmsg": "~Self~ is shining!"
                    }
                },
                "distract": {
                    "mode": "ignore",
                    "msg": "The ~Distracter~ tried to distract you, but you ignored them!"
                },
                "inspect": {
                    "mode": "ignore",
                    "msg": "±Info: ~Self~ is the ~Role~!!"
                },
                "dummy2": "variable:shock"
            }
        },
        {
            "role": "shiny2",
            "translation": "Shiny Rotom",
            "side": "shiny",
            "help": "WAIT, YOU ARE SHINING! You can't change forms, but you can /kill [name] both during the night and day, /poison [name] and even /demote [name] every night to make another player become a normal Rotom again (You can not act during the 1st night)! You are also immune to distractions, and whoever inspects you will see you as their ally! You can't inspect though!",
            "hide": true,
            "actions": {
                "night": {
                    "kill": {
                        "target": "AnyButSelf",
                        "common": "Self",
                        "priority": "variable:prio_shiny_kill",
                        "msg": "The Shiny Rotom was too bright for your eyes!",
                        "pierce": true,
                        "hide": true
                    },
                    "poison": {
                        "target": "AnyButSelf",
                        "common": "Self",
                        "priority": "variable:prio_shiny_poison",
                        "count": 2,
                        "poisonDeadMessage": "You couldn't stand the Shiny Rotom's poisonous attack, and thus died!",
                        "pierce": true,
                        "hide": true
                    },
                    "demote": {
                        "command": "convert",
                        "target": "AnyButSelf",
                        "common": "Self",
                        "priority": "variable:prio_shiny_demote",
                        "newRole": "rotom2",
                        "canConvert": [
                            "fire",
                            "ice",
                            "flying",
                            "water",
                            "grass",
                            "grass2",
                            "rice",
                            "rice2",
                            "rice3"
                        ],
                        "convertmsg": "A ~Old~ was demoted and became a normal ~New~ again!",
                        "pierce": true,
                        "hide": true
                    }
                },
                "standby": {
                    "kill": {
                        "target": "AnyButSelf",
                        "msg": "Time to shine! Type /kill [name] to defeat another Rotom!",
                        "killmsg": "Shiny Rotom used Thunderbolt! ~Target~ has fainted!",
                        "revealChance": 0,
                        "revealmsg": "~Self~ is shining!"
                    }
                },
                "distract": {
                    "mode": "ignore",
                    "msg": "The ~Distracter~ tried to distract you, but you ignored them!"
                },
                "inspect": {
                    "mode": "ignore",
                    "msg": "±Info: ~Self~ is the ~Role~!!"
                },
                "dummy2": "variable:shock"
            }
        },
        
        
        {
            "role": "rice",
            "translation": "Rice Rotom",
            "side": "rice",
            "help": "RICE TIME! You have no offensive actions, but you can counter actions used against you! If anyone tries to Nightkill or Convert, you will survive and kills them instead! If you wish, you can change forms to counter different actions. Type /mode2 to counter Lynches and Poison, or /mode3 to counter Daykills and Inspections.",
            "help2": "You currently counter Nightkills and Conversions.",
            "info": "Can change into one of the 3 different modes every night. On Mode 1, counters Nightkills and Conversions. On Mode 2, counters Lynch and Poison. On Mode 3, counters Daykills and Inspections. Sided with Rice Cookers.",
            "hide": "variable:hiddenRoles",
            "actions": {
                "night": {
                    "mode3": {
                        "command": "convert",
                        "common": "Self",
                        "target": "OnlySelf",
                        "priority": "variable:prio_rice_change",
                        "newRole": "rice3",
                        "bypass": ["ChangeTarget"],
                        "silent": true,
                        "hide": "variable:hiddenRoles"
                    },
                    "mode2": {
                        "command": "convert",
                        "common": "Self",
                        "target": "OnlySelf",
                        "priority": "variable:prio_rice_change",
                        "newRole": "rice2",
                        "bypass": ["ChangeTarget"],
                        "silent": true,
                        "hide": "variable:hiddenRoles"
                    }
                },
                "kill": {
                    "mode": "ChangeTarget",
                    "targetmsg": "You tried to kill Rice Rotom, but your attack was bounced back at you!",
                    "msg": "Someone tried to kill you, but you bounced their attack back at them!"
                },
                "convert": {
                    "mode": "ChangeTarget",
                    "targetmsg": "You tried to convert Rice Rotom, but your attack was bounced back at you!",
                    "msg": "Someone tried to convert you, but you bounced their attack back at them!"
                },
                "dummy2": "variable:shock"
            }
        },
        {
            "role": "rice2",
            "translation": "Rice Rotom",
            "side": "rice",
            "help": "RICE TIME! You have no offensive actions, but you can counter actions used against you! If anyone tries to Poison or Lynch, you will survive and kills them instead! If you wish, you can change forms to counter different actions. Type /mode1 to counter Nightkills and Conversion, or /mode3 to counter Daykills and Inspections.",
            "help2": "You currently counter Poison and Lynches.",
            "hide": true,
            "actions": {
                "night": {
                    "mode1": {
                        "command": "convert",
                        "common": "Self",
                        "target": "OnlySelf",
                        "priority": "variable:prio_rice_change",
                        "newRole": "rice",
                        "bypass": ["ChangeTarget"],
                        "silent": true,
                        "hide": "variable:hiddenRoles"
                    },
                    "mode3": {
                        "command": "convert",
                        "common": "Self",
                        "target": "OnlySelf",
                        "priority": "variable:prio_rice_change",
                        "newRole": "rice3",
                        "bypass": ["ChangeTarget"],
                        "silent": true,
                        "hide": true
                    }
                },
                "poison": {
                    "mode": "ChangeTarget",
                    "targetmsg": "You tried to poison Rice Rotom, but your attack was bounced back at you!",
                    "msg": "Someone tried to poison you, but you bounced their attack back at them!"
                },
                "lynch": {
                    "killVoters": {
                        "first": 1,
                        "message": "~Target~ tried to lynch the Rice Rotom, but Rice Rotom bounced their vote back at them!"
                    },
                    "convertTo": "rice2",
                    "lynchmsg": "And Rice Rotom didn't even die!"
                },
                "dummy2": "variable:shock"
            }
        },
        {
            "role": "rice3",
            "translation": "Rice Rotom",
            "side": "rice",
            "help": "RICE TIME! You have no offensive actions, but you can counter actions used against you! If anyone tries to Daykill or Inspect you, you will survive and kills them instead! If you wish, you can change forms to counter different actions. Type /mode1 to counter Nightkills and Conversion, or /mode2 to counter Lynches and Poison",
            "help2": "You currently counter Daykills and Inspections.",
            "hide": true,
            "actions": {
                "night": {
                    "mode1": {
                        "command": "convert",
                        "common": "Self",
                        "target": "OnlySelf",
                        "priority": "variable:prio_rice_change",
                        "newRole": "rice",
                        "bypass": ["ChangeTarget"],
                        "silent": true,
                        "hide": true
                    },
                    "mode2": {
                        "command": "convert",
                        "common": "Self",
                        "target": "OnlySelf",
                        "priority": "variable:prio_rice_change",
                        "newRole": "rice2",
                        "bypass": ["ChangeTarget"],
                        "silent": true,
                        "hide": true
                    }
                },
                "inspect": {
                    "mode": "ChangeTarget",
                    "targetmsg": "You tried to inspect Rice Rotom, but your attack was bounced back at you!",
                    "msg": "Someone tried to inspect you, but you bounced their attack back at them!",
                    "revealAs": "rotom"
                },
                "daykill": "revenge",
                "daykillrevengemsg": "~Target~ tried to attack Rice Rotom, but Rice Rotom bounced their attack back at them!",
                "dummy2": "variable:shock"
            }
        },
        

        {
            "role": "pen",
            "translation": "Pen Rotom",
            "side": "pen",
            "help": "What, a Rotom in Pen form now? Really? Anyway, you can use /expose [name] during the day to reveal someone's role, or you can fake-expose them with /mow, /heat, /fan, /wash, /frost or /pen. You win with everyone as long as you survive.",
            "winningSides": "*",
            "info": "Can expose during the day. Alternatively, can fake-expose someone as Mow, Heat, Fan, Frost, Wash or Pen Rotom. Wins with anyone as long as it survives.",
            "hide": true,
            "actions": {
                "standby": {
                    "expose": {
                        "target": "Any",
                        "msg": "You can expose someone's side by typing /expose [name] (You won't be revealed!):",
                        "exposemsg": "The Pen Rotom, mightier than the Sword Rotom, writes a note stating that ~Target~ is the ~Role~!"
                    },
                    "mow": {
                        "command": "expose",
                        "target": "Any",
                        "msg": "You can instead expose that person as a fake side by using /mow, /heat, /fan, /wash, /frost or /pen:",
                        "exposemsg": "The Pen Rotom, mightier than the Sword Rotom, writes a note stating that ~Target~ is the Mow Rotom!"
                    },
                    "heat": {
                        "command": "expose",
                        "target": "Any",
                        "exposemsg": "The Pen Rotom, mightier than the Sword Rotom, writes a note stating that ~Target~ is the Heat Rotom!"
                    },
                    "fan": {
                        "command": "expose",
                        "target": "Any",
                        "exposemsg": "The Pen Rotom, mightier than the Sword Rotom, writes a note stating that ~Target~ is the Fan Rotom!"
                    },
                    "frost": {
                        "command": "expose",
                        "target": "Any",
                        "exposemsg": "The Pen Rotom, mightier than the Sword Rotom, writes a note stating that ~Target~ is the Frost Rotom!"
                    },
                    "wash": {
                        "command": "expose",
                        "target": "Any",
                        "exposemsg": "The Pen Rotom, mightier than the Sword Rotom, writes a note stating that ~Target~ is the Wash Rotom!"
                    },
                    "pen": {
                        "command": "expose",
                        "target": "Any",
                        "exposemsg": "The Pen Rotom, mightier than the Sword Rotom, writes a note stating that ~Target~ is the Pen Rotom!"
                    }
                },
                "dummy2": "variable:shock"
            }
        },
        
        
        
        
        
        {
            "role": "false_inspect",
            "translation": "...uh, it seems your inspection failed",
            "side": "village",
            "help": "Placeholder role for false /inspect. Also, why did the chicken cross the road?",
            "hide": true,
            "actions": {}
        },
        {
            "role": "prio",
            "translation": "Any Rotom",
            "side": "village",
            "help": "Placeholder role for /priority list. Also, why did the chicken cross the road?",
            "hide": true,
            "actions": {
                "night": {
                    "inspect": {
                        "target": "AnyButSelf",
                        "common": "Self",
                        "priority": "variable:prio_rotom_inspect"
                    }
                }
            }
        },
        {
            "role": "prio2",
            "translation": "Rotom",
            "side": "village",
            "help": "Placeholder role for /priority list. Also, why did the chicken cross the road?",
            "hide": true,
            "actions": {
                "night": {
                    "change form": {
                        "command": "dummy",
                        "target": "AnyButSelf",
                        "common": "Self",
                        "priority": "variable:prio_rotom_change"
                    }
                }
            }
        }
    ],
    
    "roles1": [
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom",
        "rotom"
    ],
    "villageCantLoseRoles": [],
    "votemsg": "~Player~ rotoms ~Target~!",
    "killmsg": "±Motor: ~Player~ (~Role~) disappeared!",
    "killusermsg": "*** You lost your ability of possessing machines and thus disappeared.",
    "lynchmsg": "±Motor: ~Player~ (~Role~) disappeared!",
    "drawmsg": "Rotoms, Rotoms everywh- I mean, nowhere...",
    "changelog": {
        "09.06.2015": "When converting into Rice Rotom with /random, players will now start in a random mode.",
        "22.05.2015": "When lynched for the first time, Mow Rotom no longer reveals the number of votes it received.",
        "12.05.2015": "Testing new version. Main changes listed below.",
        "12.05.2015b": "Mow is Daykiller and Fan is Nightkiller. Instead of having 50% chance of evading an action, all actions evade that action once per game (100% chance). Mow survives a lynch once per game instead of having a voteshield. No more Frost Jr. Wash must wait 1 turn before it's able to use Protect. Fan gets a kill2 every 2 nights. Heat identify distractors and take 2 nights to die to poison."
        
    },
    "changelog2": {
        "22.03.2014": "#FreeRotom. Normal Rotoms won't die anymore if not converting. Normal Rotom's inspect has now only 25% chance of working. Fixed bug where Shiny Rotom converted into Frost would have unlimited inspections. Fixed bug where Shiny Rotom would be unable to demote Frost Rotom.",
        "17.03.2014": "Fixed bug where demoted Rotom would be unable to convert again.",
        "11.03.2014": "Shiny Rotom appears as Shiny on Current Roles list (since it's pointless to hide them).",
        "10.03.2014": "Normal Rotoms now have a 50% chance of failing when inspecting (won't fail after converting). Normal Rotoms set to village so they auto-lose on 1 vs. 1 situations.",
        "08.03.2014": "Mow's voteshield reverted to -19. Mow's kill now has a 25% chance of piercing through protection.",
        "04.03.2014": "Theme is now a fully closed setup. meaning player will not know how many of each form are in the game. Players can now inspect 3 times per game. Shiny Rotom can now daykill D1. Players can now wait until N5 to convert.",
        "28.02.2014": "Made the theme a half-closed setup, which means all forms will show as regular 'Rotom' at the Current Roles list (still show normally at the Current Team).",
        "22.02.2014": "Mow's voteshield buffed to -39. Heat's Distract is now faster than Wash's Protect. Rotoms can now wait until N3 to convert (/shock is NOT coming back though). Added Shiny Rotom as a test (Shiny Rotom is alone and can't inspect, but can nightkill, daykill, poison and demote. Shiny also pierces BG, ignores Distract and inspects as normal Rotom).",
        "13.02.2014": "Added important note the the summary stating that joining only to die N1 will be considered trolling (authorized by Fuzzy). It hinders the game for people who actually want to play and messes the mafia stats/win data.",
        "23.01.2014": "Heat's distract is now just a regular distraction (AKA won't stop Fan Rotoms from daykilling). If you already typed a command to change forms as Normal Rotom, you can now type another one in case you changed your mind.",
        "19.01.2014": "Yet another big change: Heats now distract instead of Wash. Heat no longer resists poison for 2 turns. Wash get a self-protect once per game. Wash's vote changed to 20. Mow's voteshield changed to -19. Mow no longer evades distract. Mow's kill is now faster than Heat's poison again. This update is experimental and has a high chance of being reverted if things doesn't work, so don't freak about those changes.",
        "17.01.2014": "Continuing the balance process, Heats now can protect+safeguard another player twice during the game. ",
        "12.01.2014": "Starting a new balance patch. Heat's priority is now faster than Mow. Frost can convert every turn. Mow's voteshield reduced to -35. Fan becomes Frost instead of Frost Jr. when converted by Frost. Fan's Buff coming soon (please be patient :x).",
        "10.01.2014": "Rotoms must convert N1 or die. You all asked for this.",
        "29.12.2013": "Removed normal Rotom's /shock. Normal Rotoms now die if not converting after 3 nights. Maybe now people will try to actually play the theme.",
        "26.12.2013": "Another Test Period: Reverted Heats to 2 poisons. Wash can only distract every 2 nights. Heat takes 2 nights to die from poison. Players converted into Frost will be able to convert someone else right away, but with a 50% chance of failing.",
        "22.12.2013": "Test Period: Heats now can poison 3 targets.",
        "25.11.2013": "Experimental Balance Update (may be reverted if unsuccessful): Mows have a 50% chance for -60 Voteshield. Fans can be distracted by Wash (unable to daykill for a turn). Players converted into Frost have to wait 1 turn before being able to convert. Heat's poison instantly kills Frosts.",
        "20.11.2013": "Wash has no more recharge for /distract. Frost evades /convert (so Frosts can't connect by hitting another Frost anymore).",
        "19.11.2013": "Theme added."
    }
}
