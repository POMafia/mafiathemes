{
    "name": "RPS",
    "altname": "Rock-Paper-Scissors",
    "threadlink": "http://pokemon-online.eu/threads/nonpeak-rps-rock-paper-scissors.26937/#post-373586",
    "author": [
	"Joeypals",
	"Xtina",
	"Baby Jane",
	"obey to kyubey"],
    "minplayers": 3,
	"nonPeak": true,
	"checkNoVoters": true,
	"ticks": {
		"standby": 27
	},
    "summary": "One day, some children were arguing about who was the best at Rock-Paper-Scissors. After a massive uproar, a strange child said ''Hey, just go into teams. I'll be alone. Team that wins is the best'', and thus started the Super Mega Ultra Rock-Paper-Scissors Tournament! A/N This theme runs on an HP system based on effectiveness. Good hit means 2HP for the opponent lost, bad hit means none lost, hitting the same type will cause your opponent to lose 1HP. Now you can Team Talk with your Known Partners! If you have any comments, questions, concerns, or bugs, please contact either obey to kyubey or Joeypals/Baby Jane/Xtina.",
    "sides": [
        {
            "side": "warm",
            "translation": "Red Hands",
            "winmsg": "±Foot: With fiery determination, the Red Hands ~Players~ lasted past everyone else and won the tournament!"
        },
        {
            "side": "cold",
            "translation": "Blue Hands",
            "winmsg": "±Foot: Through icy determination, the Blue Hands ~Players~ lasted past everyone else and won the tournament!"
        },
        {
            "side": "oddball",
            "translation": "Yellow Hands",
            "winmsg": "±Foot: By being themselves and having fun, the Yellow Hands ~Players~ lasted past everyone else and won the tournament!"
        },
        {
            "side": "green",
            "translation": "Green Hands",
            "winmsg": "±Foot: With the power of democracy, the Green Hands ~Players~ lasted past everyone else and won the tournament!"
        },
        {
            "side": "violet",
            "translation": "Violet Hands",
            "winmsg": "±Foot: With the power of brute force, the Violet Hands ~Players~ lasted past everyone else and won the tournament!"
        },
        {
            "side": "voodoo",
            "translation": "Special Hands",
            "winmsg": "±Foot: The Grey Hands using their special powers of darkness and light, ~Players~ cheated their way to victory."
        }
    ],
    "lynchmsg": "±Foot: ~Player~ (~Role~) cheated and was disqualified!",
    "killmsg": "±Foot: ~Player~ (~Role~) was eliminated!",
    "killusermsg": "±Foot: You've been hit too many times. Sorry, but you're out!",
	"drawmsg": "±Foot: Sometimes life is a giant draw, just like this game. Sorry guys!",
	"variables": {
				"gun damage": { "violetpaper0": [ "violethand7", "violethand6", "violethand5", "violethand4", "violethand3", "violethand2", "violethand1", "violethand7x", "violethand6x", "violethand5x", "violethand4x", "violethand3x", "violethand2x", "violethand1x" ],
								"greenscissors0": [ "greenhand7", "greenhand6", "greenhand5", "greenhand4", "greenhand3", "greenhand2", "greenhand1", "greenhand7x", "greenhand6x", "greenhand5x", "greenhand4x", "greenhand3x", "greenhand2x", "greenhand1x" ],
								"emeraldrock0": [ "emeraldhand7", "emeraldhand6", "emeraldhand5", "emeraldhand4", "emeraldhand3", "emeraldhand2", "emeraldhand1", "emeraldhand7x", "emeraldhand6x", "emeraldhand5x", "emeraldhand4x", "emeraldhand3x", "emeraldhand2x", "emeraldhand1x" ],
								"rwpaper0": [ "rwhand7", "rwhand6", "rwhand5", "rwhand4", "rwhand3", "rwhand2", "rwhand1" ],
								"swpaper0": [ "swhand7", "swhand6", "swhand5", "swhand4", "swhand3", "swhand2", "swhand1" ],
								"owpaper0": [ "owhand7", "owhand6", "owhand5", "owhand4", "owhand3", "owhand2", "owhand1" ],
								"ywpaper0": [ "ywhand7", "ywhand6", "ywhand5", "ywhand4", "ywhand3", "ywhand2", "ywhand1" ],
								"bcpaper0": [ "bchand7", "bchand6", "bchand5", "bchand4", "bchand3", "bchand2", "bchand1" ],
								"gcpaper0": [ "gchand7", "gchand6", "gchand5", "gchand4", "gchand3", "gchand2", "gchand1" ],
								"pcpaper0": [ "pchand7", "pchand6", "pchand5", "pchand4", "pchand3", "pchand2", "pchand1" ],
								"mcpaper0": [ "mchand7", "mchand6", "mchand5", "mchand4", "mchand3", "mchand2", "mchand1" ],
								"copaper0": [ "cohand7", "cohand6", "cohand5", "cohand4", "cohand3", "cohand2", "cohand1" ],
								"bopaper0": [ "bohand7", "bohand6", "bohand5", "bohand4", "bohand3", "bohand2", "bohand1" ],
								"gopaper0": [ "gohand7", "gohand6", "gohand5", "gohand4", "gohand3", "gohand2", "gohand1" ],
								"sopaper0": [ "sohand7", "sohand6", "sohand5", "sohand4", "sohand3", "sohand2", "sohand1" ]
							  },
				"gun attack":{
                    "gun": {
					"hide": true, "command": [ "dummy7", "poison", "convert", "distract" ], "priority": -1,
						"distractmsg": "",
						"teammsg": "",
                        "common": "Self",
						"dummy7broadcastmsg": "A shot has been heard on ~Target~'s direction!",
						"poisonDeadMessage": "You have been shot and a bullet hit your heart!",
						"poisonmsg": "",
						"poisontarmsg": "",
                        "target": "AnyButTeam",
						"count": 1,
                        "silent": true,
                        "silentConvert": true,
						"convertfailmsg": "",
						"usermsg": "",
						"newRole": "variable:gun damage"
                    } },
				"paper attack":{
                    "paper": {
					"hide": true, "command": [ "convert", "dummy", "dummy2" ], "priority": 2,
                        "common": "Self",
                        "silent": true,
                        "silentConvert": true,
                    "usermsg": "",
                        "target": "AnyButSelf",
						"newRole": "variable:paper damage",
                        "dummytargetmsg": "Another piece of Paper attacked you! You received 1 point of damage. You still have ~TargetRole~ Health Points!",
                        "dummyusermsg": "Your target was Paper too! You dealt 1 point of damage to them.",
                        "dummy2targetmsg": "Paper wraps Rock! You received 2 points of damage. You still have ~TargetRole~ Health Points!",
                        "dummy2usermsg": "You wrapped a Rock! You dealt 2 points of damage to them.",
						"convertfailmsg": "Your attack was deflected, your target either used a pair of Scissors or a Gray Shield"
                    } },
				"paper damage": { "violetrock5": [ "violetrock7" ], "violetrock4": [ "violetrock6" ], "violetrock3": [ "violetrock5" ], "violetrock2": [ "violetrock4" ], "violetrock1": [ "violetrock3" ], "violetrock0": [ "violetrock2", "violetrock1", "violetrock0" ], "greenrock5": [ "greenrock7" ], "greenrock4": [ "greenrock6" ], "greenrock3": [ "greenrock5" ], "greenrock2": [ "greenrock4" ], "greenrock1": [ "greenrock3" ], "greenrock0": [ "greenrock2", "greenrock1", "greenrock0" ], "rwrock5": [ "rwrock7" ], "rwrock4": [ "rwrock6" ], "rwrock3": [ "rwrock5" ], "rwrock2": [ "rwrock4" ], "rwrock1": [ "rwrock3" ], "rwrock0": [ "rwrock2", "rwrock1", "rwrock0" ], "swrock5": [ "swrock7" ], "swrock4": [ "swrock6" ], "swrock3": [ "swrock5" ], "swrock2": [ "swrock4" ], "swrock1": [ "swrock3" ], "swrock0": [ "swrock2", "swrock1", "swrock0" ], "owrock5": [ "owrock7" ], "owrock4": [ "owrock6" ], "owrock3": [ "owrock5" ], "owrock2": [ "owrock4" ], "owrock1": [ "owrock3" ], "owrock0": [ "owrock2", "owrock1", "owrock0" ], "ywrock5": [ "ywrock7" ], "ywrock4": [ "ywrock6" ], "ywrock3": [ "ywrock5" ], "ywrock2": [ "ywrock4" ], "ywrock1": [ "ywrock3" ], "ywrock0": [ "ywrock2", "ywrock1", "ywrock0" ], "bcrock5": [ "bcrock7" ], "bcrock4": [ "bcrock6" ], "bcrock3": [ "bcrock5" ], "bcrock2": [ "bcrock4" ], "bcrock1": [ "bcrock3" ], "bcrock0": [ "bcrock2", "bcrock1", "bcrock0" ], "gcrock5": [ "gcrock7" ], "gcrock4": [ "gcrock6" ], "gcrock3": [ "gcrock5" ], "gcrock2": [ "gcrock4" ], "gcrock1": [ "gcrock3" ], "gcrock0": [ "gcrock2", "gcrock1", "gcrock0" ], "pcrock5": [ "pcrock7" ], "pcrock4": [ "pcrock6" ], "pcrock3": [ "pcrock5" ], "pcrock2": [ "pcrock4" ], "pcrock1": [ "pcrock3" ], "pcrock0": [ "pcrock2", "pcrock1", "pcrock0" ], "mcrock5": [ "mcrock7" ], "mcrock4": [ "mcrock6" ], "mcrock3": [ "mcrock5" ], "mcrock2": [ "mcrock4" ], "mcrock1": [ "mcrock3" ], "mcrock0": [ "mcrock2", "mcrock1", "mcrock0" ], "corock5": [ "corock7" ], "corock4": [ "corock6" ], "corock3": [ "corock5" ], "corock2": [ "corock4" ], "corock1": [ "corock3" ], "corock0": [ "corock2", "corock1", "corock0" ], "borock5": [ "borock7" ], "borock4": [ "borock6" ], "borock3": [ "borock5" ], "borock2": [ "borock4" ], "borock1": [ "borock3" ], "borock0": [ "borock2", "borock1", "borock0" ], "sorock5": [ "sorock7" ], "sorock4": [ "sorock6" ], "sorock3": [ "sorock5" ], "sorock2": [ "sorock4" ], "sorock1": [ "sorock3" ], "sorock0": [ "sorock2", "sorock1", "sorock0" ], "gorock5": [ "gorock7" ], "gorock4": [ "gorock6" ], "gorock3": [ "gorock5" ], "gorock2": [ "gorock4" ], "gorock1": [ "gorock3" ], "gorock0": [ "gorock2", "gorock1", "gorock0" ],
								  "vvgun5": [ "vvgun7" ], "vvgun4": [ "vvgun6" ], "vvgun3": [ "vvgun5" ], "vvgun2": [ "vvgun4" ], "vvgun1": [ "vvgun3" ], "vvgun0": [ "vvgun2", "vvgun1", "vvgun0" ],
								  "rwhand5": [ "rwhand7" ], "rwhand4": [ "rwhand6" ], "rwhand3": [ "rwhand5" ], "rwhand2": [ "rwhand4" ], "rwhand1": [ "rwhand3" ], "rwhand0": [ "rwhand2", "rwhand1", "rwhand0" ], "swhand5": [ "swhand7" ], "swhand4": [ "swhand6" ], "swhand3": [ "swhand5" ], "swhand2": [ "swhand4" ], "swhand1": [ "swhand3" ], "swhand0": [ "swhand2", "swhand1", "swhand0" ], "owhand5": [ "owhand7" ], "owhand4": [ "owhand6" ], "owhand3": [ "owhand5" ], "owhand2": [ "owhand4" ], "owhand1": [ "owhand3" ], "owhand0": [ "owhand2", "owhand1", "owhand0" ], "ywhand5": [ "ywhand7" ], "ywhand4": [ "ywhand6" ], "ywhand3": [ "ywhand5" ], "ywhand2": [ "ywhand4" ], "ywhand1": [ "ywhand3" ], "ywhand0": [ "ywhand2", "ywhand1", "ywhand0" ], "bchand5": [ "bchand7" ], "bchand4": [ "bchand6" ], "bchand3": [ "bchand5" ], "bchand2": [ "bchand4" ], "bchand1": [ "bchand3" ], "bchand0": [ "bchand2", "bchand1", "bchand0" ], "gchand5": [ "gchand7" ], "gchand4": [ "gchand6" ], "gchand3": [ "gchand5" ], "gchand2": [ "gchand4" ], "gchand1": [ "gchand3" ], "gchand0": [ "gchand2", "gchand1", "gchand0" ], "pchand5": [ "pchand7" ], "pchand4": [ "pchand6" ], "pchand3": [ "pchand5" ], "pchand2": [ "pchand4" ], "pchand1": [ "pchand3" ], "pchand0": [ "pchand2", "pchand1", "pchand0" ], "mchand5": [ "mchand7" ], "mchand4": [ "mchand6" ], "mchand3": [ "mchand5" ], "mchand2": [ "mchand4" ], "mchand1": [ "mchand3" ], "mchand0": [ "mchand2", "mchand1", "mchand0" ], "cohand5": [ "cohand7" ], "cohand4": [ "cohand6" ], "cohand3": [ "cohand5" ], "cohand2": [ "cohand4" ], "cohand1": [ "cohand3" ], "cohand0": [ "cohand2", "cohand1", "cohand0" ], "bohand5": [ "bohand7" ], "bohand4": [ "bohand6" ], "bohand3": [ "bohand5" ], "bohand2": [ "bohand4" ], "bohand1": [ "bohand3" ], "bohand0": [ "bohand2", "bohand1", "bohand0" ], "sohand5": [ "sohand7" ], "sohand4": [ "sohand6" ], "sohand3": [ "sohand5" ], "sohand2": [ "sohand4" ], "sohand1": [ "sohand3" ], "sohand0": [ "sohand2", "sohand1", "sohand0" ], "gohand5": [ "gohand7" ], "gohand4": [ "gohand6" ], "gohand3": [ "gohand5" ], "gohand2": [ "gohand4" ], "gohand1": [ "gohand3" ], "gohand0": [ "gohand2", "gohand1", "gohand0" ],
								  "vvhand5": [ "vvhand7", "vvhand7x" ], "vvhand4": [ "vvhand6", "vvhand6x" ], "vvhand3": [ "vvhand5", "vvhand5x" ], "vvhand2": [ "vvhand4", "vvhand4x"], "vvhand1": [ "vvhand3", "vvhand3x" ], "vvhand0": [ "vvhand2", "vvhand1", "vvhand0", "vvhand2x", "vvhand1x", "vvhand0x" ], "greenhand5": [ "greenhand7", "greenhand7x" ], "greenhand4": [ "greenhand6", "greenhand6x" ], "greenhand3": [ "greenhand5", "greenhand5x" ], "greenhand2": [ "greenhand4", "greenhand4x"], "greenhand1": [ "greenhand3", "greenhand3x" ], "greenhand0": [ "greenhand2", "greenhand1", "greenhand0", "greenhand2x", "greenhand1x"], "violethand5": [ "violethand7", "violethand7x" ], "violethand4": [ "violethand6", "violethand6x" ], "violethand3": [ "violethand5", "violethand5x" ], "violethand2": [ "violethand4", "violethand4x"], "violethand1": [ "violethand3", "violethand3x" ], "violethand0": [ "violethand2", "violethand1", "violethand0", "violethand2x", "violethand1x"],
								  "violetpaper6": [ "violetpaper7" ], "violetpaper5": [ "violetpaper6" ], "violetpaper4": [ "violetpaper5" ], "violetpaper3": [ "violetpaper4" ], "violetpaper2": [ "violetpaper3" ], "violetpaper1": [ "violetpaper2"], "violetpaper0": [ "violetpaper1", "violetpaper0" ], "greenpaper6": [ "greenpaper7" ], "greenpaper5": [ "greenpaper6" ], "greenpaper4": [ "greenpaper5" ], "greenpaper3": [ "greenpaper4" ], "greenpaper2": [ "greenpaper3" ], "greenpaper1": [ "greenpaper2"], "greenpaper0": [ "greenpaper1", "greenpaper0" ], "rwpaper6": [ "rwpaper7" ], "rwpaper5": [ "rwpaper6" ], "rwpaper4": [ "rwpaper5" ], "rwpaper3": [ "rwpaper4" ], "rwpaper2": [ "rwpaper3" ], "rwpaper1": [ "rwpaper2"], "rwpaper0": [ "rwpaper1", "rwpaper0" ], "swpaper6": [ "swpaper7" ], "swpaper5": [ "swpaper6" ], "swpaper4": [ "swpaper5" ], "swpaper3": [ "swpaper4" ], "swpaper2": [ "swpaper3" ], "swpaper1": [ "swpaper2"], "swpaper0": [ "swpaper1", "swpaper0" ], "owpaper6": [ "owpaper7" ], "owpaper5": [ "owpaper6" ], "owpaper4": [ "owpaper5" ], "owpaper3": [ "owpaper4" ], "owpaper2": [ "owpaper3" ], "owpaper1": [ "owpaper2"], "owpaper0": [ "owpaper1", "owpaper0" ], "ywpaper6": [ "ywpaper7" ], "ywpaper5": [ "ywpaper6" ], "ywpaper4": [ "ywpaper5" ], "ywpaper3": [ "ywpaper4" ], "ywpaper2": [ "ywpaper3" ], "ywpaper1": [ "ywpaper2"], "ywpaper0": [ "ywpaper1", "ywpaper0" ], "bcpaper6": [ "bcpaper7" ], "bcpaper5": [ "bcpaper6" ], "bcpaper4": [ "bcpaper5" ], "bcpaper3": [ "bcpaper4" ], "bcpaper2": [ "bcpaper3" ], "bcpaper1": [ "bcpaper2"], "bcpaper0": [ "bcpaper1", "bcpaper0" ], "gcpaper6": [ "gcpaper7" ], "gcpaper5": [ "gcpaper6" ], "gcpaper4": [ "gcpaper5" ], "gcpaper3": [ "gcpaper4" ], "gcpaper2": [ "gcpaper3" ], "gcpaper1": [ "gcpaper2"], "gcpaper0": [ "gcpaper1", "gcpaper0" ], "pcpaper6": [ "pcpaper7" ], "pcpaper5": [ "pcpaper6" ], "pcpaper4": [ "pcpaper5" ], "pcpaper3": [ "pcpaper4" ], "pcpaper2": [ "pcpaper3" ], "pcpaper1": [ "pcpaper2"], "pcpaper0": [ "pcpaper1", "pcpaper0" ], "mcpaper6": [ "mcpaper7" ], "mcpaper5": [ "mcpaper6" ], "mcpaper4": [ "mcpaper5" ], "mcpaper3": [ "mcpaper4" ], "mcpaper2": [ "mcpaper3" ], "mcpaper1": [ "mcpaper2"], "mcpaper0": [ "mcpaper1", "mcpaper0" ], "copaper6": [ "copaper7" ], "copaper5": [ "copaper6" ], "copaper4": [ "copaper5" ], "copaper3": [ "copaper4" ], "copaper2": [ "copaper3" ], "copaper1": [ "copaper2"], "copaper0": [ "copaper1", "copaper0" ], "bopaper6": [ "bopaper7" ], "bopaper5": [ "bopaper6" ], "bopaper4": [ "bopaper5" ], "bopaper3": [ "bopaper4" ], "bopaper2": [ "bopaper3" ], "bopaper1": [ "bopaper2"], "bopaper0": [ "bopaper1", "bopaper0" ], "sopaper6": [ "sopaper7" ], "sopaper5": [ "sopaper6" ], "sopaper4": [ "sopaper5" ], "sopaper3": [ "sopaper4" ], "sopaper2": [ "sopaper3" ], "sopaper1": [ "sopaper2"], "sopaper0": [ "sopaper1", "sopaper0" ], "gopaper6": [ "gopaper7" ], "gopaper5": [ "gopaper6" ], "gopaper4": [ "gopaper5" ], "gopaper3": [ "gopaper4" ], "gopaper2": [ "gopaper3" ], "gopaper1": [ "gopaper2"], "gopaper0": [ "gopaper1", "gopaper0" ],
								  "bluerock5": [ "bluerock7" ], "bluerock4": [ "bluerock6" ], "bluerock3": [ "bluerock5" ], "bluerock2": [ "bluerock4" ], "bluerock1": [ "bluerock3" ], "bluerock0": [ "bluerock2", "bluerock1", "bluerock0" ], "bluehand5": [ "bluehand7", "bluehand7x" ], "bluehand4": [ "bluehand6", "bluehand6x" ], "bluehand3": [ "bluehand5", "bluehand5" ], "bluehand2": [ "bluehand4", "bluehand4x"], "bluehand1": [ "bluehand3", "bluehand3" ], "bluehand0": [ "bluehand2", "bluehand1", "bluehand0", "bluehand2x", "bluehand1x"], "bluepaper6": [ "bluepaper7" ], "bluepaper5": [ "bluepaper6" ], "bluepaper4": [ "bluepaper5" ], "bluepaper3": [ "bluepaper4" ], "bluepaper2": [ "bluepaper3" ], "bluepaper1": [ "bluepaper2"], "bluepaper0": [ "bluepaper1", "bluepaper0" ],
								  "redrock5": [ "redrock7" ], "redrock4": [ "redrock6" ], "redrock3": [ "redrock5" ], "redrock2": [ "redrock4" ], "redrock1": [ "redrock3" ], "redrock0": [ "redrock2", "redrock1", "redrock0" ], "redhand5": [ "redhand7", "redhand7x" ], "redhand4": [ "redhand6", "redhand6x" ], "redhand3": [ "redhand5", "redhand5" ], "redhand2": [ "redhand4", "redhand4x"], "redhand1": [ "redhand3", "redhand3" ], "redhand0": [ "redhand2", "redhand1", "redhand0", "redhand2x", "redhand1x"], "redpaper6": [ "redpaper7" ], "redpaper5": [ "redpaper6" ], "redpaper4": [ "redpaper5" ], "redpaper3": [ "redpaper4" ], "redpaper2": [ "redpaper3" ], "redpaper1": [ "redpaper2"], "redpaper0": [ "redpaper1", "redpaper0" ],
								  "yellowrock5": [ "yellowrock7" ], "yellowrock4": [ "yellowrock6" ], "yellowrock3": [ "yellowrock5" ], "yellowrock2": [ "yellowrock4" ], "yellowrock1": [ "yellowrock3" ], "yellowrock0": [ "yellowrock2", "yellowrock1", "yellowrock0" ], "yellowhand5": [ "yellowhand7", "yellowhand7x" ], "yellowhand4": [ "yellowhand6", "yellowhand6x" ], "yellowhand3": [ "yellowhand5", "yellowhand5" ], "yellowhand2": [ "yellowhand4", "yellowhand4x"], "yellowhand1": [ "yellowhand3", "yellowhand3" ], "yellowhand0": [ "yellowhand2", "yellowhand1", "yellowhand0", "yellowhand2x", "yellowhand1x"], "yellowpaper6": [ "yellowpaper7" ], "yellowpaper5": [ "yellowpaper6" ], "yellowpaper4": [ "yellowpaper5" ], "yellowpaper3": [ "yellowpaper4" ], "yellowpaper2": [ "yellowpaper3" ], "yellowpaper1": [ "yellowpaper2"], "yellowpaper0": [ "yellowpaper1", "yellowpaper0" ],
								  "emeraldrock5": [ "emeraldrock7" ], "emeraldrock4": [ "emeraldrock6" ], "emeraldrock3": [ "emeraldrock5" ], "emeraldrock2": [ "emeraldrock4" ], "emeraldrock1": [ "emeraldrock3" ], "emeraldrock0": [ "emeraldrock2", "emeraldrock1", "emeraldrock0" ],
								  "emeraldhand5": [ "emeraldhand7", "emeraldhand7x" ], "emeraldhand4": [ "emeraldhand6", "emeraldhand6x" ], "emeraldhand3": [ "emeraldhand5", "emeraldhand5" ], "emeraldhand2": [ "emeraldhand4", "emeraldhand4x"], "emeraldhand1": [ "emeraldhand3", "emeraldhand3" ], "emeraldhand0": [ "emeraldhand2", "emeraldhand1", "emeraldhand0", "emeraldhand2x", "emeraldhand1x"],
								  "emeraldpaper6": [ "emeraldpaper7" ], "emeraldpaper5": [ "emeraldpaper6" ], "emeraldpaper4": [ "emeraldpaper5" ], "emeraldpaper3": [ "emeraldpaper4" ], "emeraldpaper2": [ "emeraldpaper3" ], "emeraldpaper1": [ "emeraldpaper2"], "emeraldpaper0": [ "emeraldpaper1", "emeraldpaper0" ]
								},
				"scissors attack":{
                    "scissors": {
					"hide": true, "command": [ "convert", "dummy3", "dummy4" ], "priority": 2,
                        "common": "Self",
                    "usermsg": "",
                        "silent": true,
                        "silentConvert": true,
                        "target": "AnyButSelf",
						"newRole": "variable:scissors damage",
                        "dummy3targetmsg": "Another pair of Scissors attacked you! You received 1 point of damage. You still have ~TargetRole~ Health Points!",
                        "dummy3usermsg": "Your target was Scissors too! You dealt 1 point of damage to them.",
                        "dummy4targetmsg": "Scissors cuts Paper! You received 2 points of damage. You still have ~TargetRole~ Health Points!",
                        "dummy4usermsg": "You cut a piece of Paper! You dealt 2 points of damage to them.",
						"convertfailmsg": "Your attack was deflected, your target either used a Rock or a Gray Shield"
                    } },
				"scissors damage": { "violetpaper5": [ "violetpaper7" ], "violetpaper4": [ "violetpaper6" ], "violetpaper3": [ "violetpaper5" ], "violetpaper2": [ "violetpaper4" ], "violetpaper1": [ "violetpaper3" ], "violetpaper0": [ "violetpaper2", "violetpaper1", "violetpaper0" ], "greenpaper5": [ "greenpaper7" ], "greenpaper4": [ "greenpaper6" ], "greenpaper3": [ "greenpaper5" ], "greenpaper2": [ "greenpaper4" ], "greenpaper1": [ "greenpaper3" ], "greenpaper0": [ "greenpaper2", "greenpaper1", "greenpaper0" ], "rwpaper5": [ "rwpaper7" ], "rwpaper4": [ "rwpaper6" ], "rwpaper3": [ "rwpaper5" ], "rwpaper2": [ "rwpaper4" ], "rwpaper1": [ "rwpaper3" ], "rwpaper0": [ "rwpaper2", "rwpaper1", "rwpaper0" ], "swpaper5": [ "swpaper7" ], "swpaper4": [ "swpaper6" ], "swpaper3": [ "swpaper5" ], "swpaper2": [ "swpaper4" ], "swpaper1": [ "swpaper3" ], "swpaper0": [ "swpaper2", "swpaper1", "swpaper0" ], "owpaper5": [ "owpaper7" ], "owpaper4": [ "owpaper6" ], "owpaper3": [ "owpaper5" ], "owpaper2": [ "owpaper4" ], "owpaper1": [ "owpaper3" ], "owpaper0": [ "owpaper2", "owpaper1", "owpaper0" ], "ywpaper5": [ "ywpaper7" ], "ywpaper4": [ "ywpaper6" ], "ywpaper3": [ "ywpaper5" ], "ywpaper2": [ "ywpaper4" ], "ywpaper1": [ "ywpaper3" ], "ywpaper0": [ "ywpaper2", "ywpaper1", "ywpaper0" ], "bcpaper5": [ "bcpaper7" ], "bcpaper4": [ "bcpaper6" ], "bcpaper3": [ "bcpaper5" ], "bcpaper2": [ "bcpaper4" ], "bcpaper1": [ "bcpaper3" ], "bcpaper0": [ "bcpaper2", "bcpaper1", "bcpaper0" ], "gcpaper5": [ "gcpaper7" ], "gcpaper4": [ "gcpaper6" ], "gcpaper3": [ "gcpaper5" ], "gcpaper2": [ "gcpaper4" ], "gcpaper1": [ "gcpaper3" ], "gcpaper0": [ "gcpaper2", "gcpaper1", "gcpaper0" ], "pcpaper5": [ "pcpaper7" ], "pcpaper4": [ "pcpaper6" ], "pcpaper3": [ "pcpaper5" ], "pcpaper2": [ "pcpaper4" ], "pcpaper1": [ "pcpaper3" ], "pcpaper0": [ "pcpaper2", "pcpaper1", "pcpaper0" ], "mcpaper5": [ "mcpaper7" ], "mcpaper4": [ "mcpaper6" ], "mcpaper3": [ "mcpaper5" ], "mcpaper2": [ "mcpaper4" ], "mcpaper1": [ "mcpaper3" ], "mcpaper0": [ "mcpaper2", "mcpaper1", "mcpaper0" ], "copaper5": [ "copaper7" ], "copaper4": [ "copaper6" ], "copaper3": [ "copaper5" ], "copaper2": [ "copaper4" ], "copaper1": [ "copaper3" ], "copaper0": [ "copaper2", "copaper1", "copaper0" ], "bopaper5": [ "bopaper7" ], "bopaper4": [ "bopaper6" ], "bopaper3": [ "bopaper5" ], "bopaper2": [ "bopaper4" ], "bopaper1": [ "bopaper3" ], "bopaper0": [ "bopaper2", "bopaper1", "bopaper0" ], "sopaper5": [ "sopaper7" ], "sopaper4": [ "sopaper6" ], "sopaper3": [ "sopaper5" ], "sopaper2": [ "sopaper4" ], "sopaper1": [ "sopaper3" ], "sopaper0": [ "sopaper2", "sopaper1", "sopaper0" ], "gopaper5": [ "gopaper7" ], "gopaper4": [ "gopaper6" ], "gopaper3": [ "gopaper5" ], "gopaper2": [ "gopaper4" ], "gopaper1": [ "gopaper3" ], "gopaper0": [ "gopaper2", "gopaper1", "gopaper0" ],
								  "vvgun5": [ "vvgun7" ], "vvgun4": [ "vvgun6" ], "vvgun3": [ "vvgun5" ], "vvgun2": [ "vvgun4" ], "vvgun1": [ "vvgun3" ], "vvgun0": [ "vvgun2", "vvgun1", "vvgun0" ],
								  "rwhand5": [ "rwhand7" ], "rwhand4": [ "rwhand6" ], "rwhand3": [ "rwhand5" ], "rwhand2": [ "rwhand4" ], "rwhand1": [ "rwhand3" ], "rwhand0": [ "rwhand2", "rwhand1", "rwhand0" ], "swhand5": [ "swhand7" ], "swhand4": [ "swhand6" ], "swhand3": [ "swhand5" ], "swhand2": [ "swhand4" ], "swhand1": [ "swhand3" ], "swhand0": [ "swhand2", "swhand1", "swhand0" ], "owhand5": [ "owhand7" ], "owhand4": [ "owhand6" ], "owhand3": [ "owhand5" ], "owhand2": [ "owhand4" ], "owhand1": [ "owhand3" ], "owhand0": [ "owhand2", "owhand1", "owhand0" ], "ywhand5": [ "ywhand7" ], "ywhand4": [ "ywhand6" ], "ywhand3": [ "ywhand5" ], "ywhand2": [ "ywhand4" ], "ywhand1": [ "ywhand3" ], "ywhand0": [ "ywhand2", "ywhand1", "ywhand0" ], "bchand5": [ "bchand7" ], "bchand4": [ "bchand6" ], "bchand3": [ "bchand5" ], "bchand2": [ "bchand4" ], "bchand1": [ "bchand3" ], "bchand0": [ "bchand2", "bchand1", "bchand0" ], "gchand5": [ "gchand7" ], "gchand4": [ "gchand6" ], "gchand3": [ "gchand5" ], "gchand2": [ "gchand4" ], "gchand1": [ "gchand3" ], "gchand0": [ "gchand2", "gchand1", "gchand0" ], "pchand5": [ "pchand7" ], "pchand4": [ "pchand6" ], "pchand3": [ "pchand5" ], "pchand2": [ "pchand4" ], "pchand1": [ "pchand3" ], "pchand0": [ "pchand2", "pchand1", "pchand0" ], "mchand5": [ "mchand7" ], "mchand4": [ "mchand6" ], "mchand3": [ "mchand5" ], "mchand2": [ "mchand4" ], "mchand1": [ "mchand3" ], "mchand0": [ "mchand2", "mchand1", "mchand0" ], "cohand5": [ "cohand7" ], "cohand4": [ "cohand6" ], "cohand3": [ "cohand5" ], "cohand2": [ "cohand4" ], "cohand1": [ "cohand3" ], "cohand0": [ "cohand2", "cohand1", "cohand0" ], "bohand5": [ "bohand7" ], "bohand4": [ "bohand6" ], "bohand3": [ "bohand5" ], "bohand2": [ "bohand4" ], "bohand1": [ "bohand3" ], "bohand0": [ "bohand2", "bohand1", "bohand0" ], "sohand5": [ "sohand7" ], "sohand4": [ "sohand6" ], "sohand3": [ "sohand5" ], "sohand2": [ "sohand4" ], "sohand1": [ "sohand3" ], "sohand0": [ "sohand2", "sohand1", "sohand0" ], "gohand5": [ "gohand7" ], "gohand4": [ "gohand6" ], "gohand3": [ "gohand5" ], "gohand2": [ "gohand4" ], "gohand1": [ "gohand3" ], "gohand0": [ "gohand2", "gohand1", "gohand0" ],
								  "vvhand5": [ "vvhand7", "vvhand7x" ], "vvhand4": [ "vvhand6", "vvhand6x" ], "vvhand3": [ "vvhand5", "vvhand5x" ], "vvhand2": [ "vvhand4", "vvhand4x"], "vvhand1": [ "vvhand3", "vvhand3x" ], "vvhand0": [ "vvhand2", "vvhand1", "vvhand0", "vvhand2x", "vvhand1x", "vvhand0x" ], "violethand5": [ "violethand7", "violethand7x" ], "violethand4": [ "violethand6", "violethand6x" ], "violethand3": [ "violethand5", "violethand5x" ], "violethand2": [ "violethand4", "violethand4x"], "violethand1": [ "violethand3", "violethand3x" ], "violethand0": [ "violethand2", "violethand1", "violethand0", "violethand2x", "violethand1x"], "greenhand5": [ "greenhand7", "greenhand7x" ], "greenhand4": [ "greenhand6", "greenhand6x" ], "greenhand3": [ "greenhand5", "greenhand5x" ], "greenhand2": [ "greenhand4", "greenhand4x"], "greenhand1": [ "greenhand3", "greenhand3x" ], "greenhand0": [ "greenhand2", "greenhand1", "greenhand0", "greenhand2x", "greenhand1x"],
								  "violetscissors6": [ "violetscissors7" ], "violetscissors5": [ "violetscissors6" ], "violetscissors4": [ "violetscissors5" ], "violetscissors3": [ "violetscissors4" ], "violetscissors2": [ "violetscissors3" ], "violetscissors1": [ "violetscissors2"], "violetscissors0": [ "violetscissors1", "violetscissors0" ], "greenscissors6": [ "greenscissors7" ], "greenscissors5": [ "greenscissors6" ], "greenscissors4": [ "greenscissors5" ], "greenscissors3": [ "greenscissors4" ], "greenscissors2": [ "greenscissors3" ], "greenscissors1": [ "greenscissors2"], "greenscissors0": [ "greenscissors1", "greenscissors0" ], "rwscissors6": [ "rwscissors7" ], "rwscissors5": [ "rwscissors6" ], "rwscissors4": [ "rwscissors5" ], "rwscissors3": [ "rwscissors4" ], "rwscissors2": [ "rwscissors3" ], "rwscissors1": [ "rwscissors2"], "rwscissors0": [ "rwscissors1", "rwscissors0" ], "swscissors6": [ "swscissors7" ], "swscissors5": [ "swscissors6" ], "swscissors4": [ "swscissors5" ], "swscissors3": [ "swscissors4" ], "swscissors2": [ "swscissors3" ], "swscissors1": [ "swscissors2"], "swscissors0": [ "swscissors1", "swscissors0" ], "owscissors6": [ "owscissors7" ], "owscissors5": [ "owscissors6" ], "owscissors4": [ "owscissors5" ], "owscissors3": [ "owscissors4" ], "owscissors2": [ "owscissors3" ], "owscissors1": [ "owscissors2"], "owscissors0": [ "owscissors1", "owscissors0" ], "ywscissors6": [ "ywscissors7" ], "ywscissors5": [ "ywscissors6" ], "ywscissors4": [ "ywscissors5" ], "ywscissors3": [ "ywscissors4" ], "ywscissors2": [ "ywscissors3" ], "ywscissors1": [ "ywscissors2"], "ywscissors0": [ "ywscissors1", "ywscissors0" ], "bcscissors6": [ "bcscissors7" ], "bcscissors5": [ "bcscissors6" ], "bcscissors4": [ "bcscissors5" ], "bcscissors3": [ "bcscissors4" ], "bcscissors2": [ "bcscissors3" ], "bcscissors1": [ "bcscissors2"], "bcscissors0": [ "bcscissors1", "bcscissors0" ], "gcscissors6": [ "gcscissors7" ], "gcscissors5": [ "gcscissors6" ], "gcscissors4": [ "gcscissors5" ], "gcscissors3": [ "gcscissors4" ], "gcscissors2": [ "gcscissors3" ], "gcscissors1": [ "gcscissors2"], "gcscissors0": [ "gcscissors1", "gcscissors0" ], "pcscissors6": [ "pcscissors7" ], "pcscissors5": [ "pcscissors6" ], "pcscissors4": [ "pcscissors5" ], "pcscissors3": [ "pcscissors4" ], "pcscissors2": [ "pcscissors3" ], "pcscissors1": [ "pcscissors2"], "pcscissors0": [ "pcscissors1", "pcscissors0" ], "mcscissors6": [ "mcscissors7" ], "mcscissors5": [ "mcscissors6" ], "mcscissors4": [ "mcscissors5" ], "mcscissors3": [ "mcscissors4" ], "mcscissors2": [ "mcscissors3" ], "mcscissors1": [ "mcscissors2"], "mcscissors0": [ "mcscissors1", "mcscissors0" ], "coscissors6": [ "coscissors7" ], "coscissors5": [ "coscissors6" ], "coscissors4": [ "coscissors5" ], "coscissors3": [ "coscissors4" ], "coscissors2": [ "coscissors3" ], "coscissors1": [ "coscissors2"], "coscissors0": [ "coscissors1", "coscissors0" ], "boscissors6": [ "boscissors7" ], "boscissors5": [ "boscissors6" ], "boscissors4": [ "boscissors5" ], "boscissors3": [ "boscissors4" ], "boscissors2": [ "boscissors3" ], "boscissors1": [ "boscissors2"], "boscissors0": [ "boscissors1", "boscissors0" ], "soscissors6": [ "soscissors7" ], "soscissors5": [ "soscissors6" ], "soscissors4": [ "soscissors5" ], "soscissors3": [ "soscissors4" ], "soscissors2": [ "soscissors3" ], "soscissors1": [ "soscissors2"], "soscissors0": [ "soscissors1", "soscissors0" ], "goscissors6": [ "goscissors7" ], "goscissors5": [ "goscissors6" ], "goscissors4": [ "goscissors5" ], "goscissors3": [ "goscissors4" ], "goscissors2": [ "goscissors3" ], "goscissors1": [ "goscissors2"], "goscissors0": [ "goscissors1", "goscissors0" ],
								  "bluepaper5": [ "bluepaper7" ], "bluepaper4": [ "bluepaper6" ], "bluepaper3": [ "bluepaper5" ], "bluepaper2": [ "bluepaper4" ], "bluepaper1": [ "bluepaper3" ], "bluepaper0": [ "bluepaper2", "bluepaper1", "bluepaper0" ], "bluehand5": [ "bluehand7", "bluehand7x" ], "bluehand4": [ "bluehand6", "bluehand6x" ], "bluehand3": [ "bluehand5", "bluehand5" ], "bluehand2": [ "bluehand4", "bluehand4x"], "bluehand1": [ "bluehand3", "bluehand3" ], "bluehand0": [ "bluehand2", "bluehand1", "bluehand0", "bluehand2x", "bluehand1x"], "bluescissors6": [ "bluescissors7" ], "bluescissors5": [ "bluescissors6" ], "bluescissors4": [ "bluescissors5" ], "bluescissors3": [ "bluescissors4" ], "bluescissors2": [ "bluescissors3" ], "bluescissors1": [ "bluescissors2"], "bluescissors0": [ "bluescissors1", "bluescissors0" ],
"redpaper5": [ "redpaper7" ], "redpaper4": [ "redpaper6" ], "redpaper3": [ "redpaper5" ], "redpaper2": [ "redpaper4" ], "redpaper1": [ "redpaper3" ], "redpaper0": [ "redpaper2", "redpaper1", "redpaper0" ], "redhand5": [ "redhand7", "redhand7x" ], "redhand4": [ "redhand6", "redhand6x" ], "redhand3": [ "redhand5", "redhand5" ], "redhand2": [ "redhand4", "redhand4x"], "redhand1": [ "redhand3", "redhand3" ], "redhand0": [ "redhand2", "redhand1", "redhand0", "redhand2x", "redhand1x"], "redscissors6": [ "redscissors7" ], "redscissors5": [ "redscissors6" ], "redscissors4": [ "redscissors5" ], "redscissors3": [ "redscissors4" ], "redscissors2": [ "redscissors3" ], "redscissors1": [ "redscissors2"], "redscissors0": [ "redscissors1", "redscissors0" ],
"yellowpaper5": [ "yellowpaper7" ], "yellowpaper4": [ "yellowpaper6" ], "yellowpaper3": [ "yellowpaper5" ], "yellowpaper2": [ "yellowpaper4" ], "yellowpaper1": [ "yellowpaper3" ], "yellowpaper0": [ "yellowpaper2", "yellowpaper1", "yellowpaper0" ], "yellowhand5": [ "yellowhand7", "yellowhand7x" ], "yellowhand4": [ "yellowhand6", "yellowhand6x" ], "yellowhand3": [ "yellowhand5", "yellowhand5" ], "yellowhand2": [ "yellowhand4", "yellowhand4x"], "yellowhand1": [ "yellowhand3", "yellowhand3" ], "yellowhand0": [ "yellowhand2", "yellowhand1", "yellowhand0", "yellowhand2x", "yellowhand1x"], "yellowscissors6": [ "yellowscissors7" ], "yellowscissors5": [ "yellowscissors6" ], "yellowscissors4": [ "yellowscissors5" ], "yellowscissors3": [ "yellowscissors4" ], "yellowscissors2": [ "yellowscissors3" ], "yellowscissors1": [ "yellowscissors2"], "yellowscissors0": [ "yellowscissors1", "yellowscissors0" ],
								  "emeraldpaper5": [ "emeraldpaper7" ], "emeraldpaper4": [ "emeraldpaper6" ], "emeraldpaper3": [ "emeraldpaper5" ], "emeraldpaper2": [ "emeraldpaper4" ], "emeraldpaper1": [ "emeraldpaper3" ], "emeraldpaper0": [ "emeraldpaper2", "emeraldpaper1", "emeraldpaper0" ],
								  "emeraldhand5": [ "emeraldhand7", "emeraldhand7x" ], "emeraldhand4": [ "emeraldhand6", "emeraldhand6x" ], "emeraldhand3": [ "emeraldhand5", "emeraldhand5" ], "emeraldhand2": [ "emeraldhand4", "emeraldhand4x"], "emeraldhand1": [ "emeraldhand3", "emeraldhand3" ], "emeraldhand0": [ "emeraldhand2", "emeraldhand1", "emeraldhand0", "emeraldhand2x", "emeraldhand1x"],
								  "emeraldscissors6": [ "emeraldscissors7" ], "emeraldscissors5": [ "emeraldscissors6" ], "emeraldscissors4": [ "emeraldscissors5" ], "emeraldscissors3": [ "emeraldscissors4" ], "emeraldscissors2": [ "emeraldscissors3" ], "emeraldscissors1": [ "emeraldscissors2"], "emeraldscissors0": [ "emeraldscissors1", "emeraldscissors0" ]
								},
				"rock attack":{
                    "rock": {
					"hide": true, "command": [ "convert", "dummy5", "dummy6" ], "priority": 2,
                        "common": "Self",
                        "silent": true,
                        "silentConvert": true,
                    "usermsg": "",
                        "target": "AnyButSelf",
						"newRole": "variable:rock damage",
                        "dummy5targetmsg": "Another Rock attacked you! You received 1 point of damage. You still have ~TargetRole~ Health Points!",
                        "dummy5usermsg": "Your target was a Rock too! You dealt 1 point of damage to them.",
                        "dummy6targetmsg": "Rock smashes Scissors! You received 2 points of damage. You still have ~TargetRole~ Health Points!",
                        "dummy6usermsg": "You smashed a pair of Scissors! You dealt 2 points of damage to them.",
						"convertfailmsg": "Your attack was deflected, your target either used a piece of Paper or a Gray Shield"
                    } },
				"rock damage": { "emeraldscissors5": [ "emeraldscissors7" ], "emeraldscissors4": [ "emeraldscissors6" ], "emeraldscissors3": [ "emeraldscissors5" ], "emeraldscissors2": [ "emeraldscissors4" ], "emeraldscissors1": [ "emeraldscissors3" ], "emeraldscissors0": [ "emeraldscissors2", "emeraldscissors1", "emeraldscissors0" ], "violetscissors5": [ "violetscissors7" ], "violetscissors4": [ "violetscissors6" ], "violetscissors3": [ "violetscissors5" ], "violetscissors2": [ "violetscissors4" ], "violetscissors1": [ "violetscissors3" ], "violetscissors0": [ "violetscissors2", "violetscissors1", "violetscissors0" ], "greenscissors5": [ "greenscissors7" ], "greenscissors4": [ "greenscissors6" ], "greenscissors3": [ "greenscissors5" ], "greenscissors2": [ "greenscissors4" ], "greenscissors1": [ "greenscissors3" ], "greenscissors0": [ "greenscissors2", "greenscissors1", "greenscissors0" ], "rwscissors5": [ "rwscissors7" ], "rwscissors4": [ "rwscissors6" ], "rwscissors3": [ "rwscissors5" ], "rwscissors2": [ "rwscissors4" ], "rwscissors1": [ "rwscissors3" ], "rwscissors0": [ "rwscissors2", "rwscissors1", "rwscissors0" ], "swscissors5": [ "swscissors7" ], "swscissors4": [ "swscissors6" ], "swscissors3": [ "swscissors5" ], "swscissors2": [ "swscissors4" ], "swscissors1": [ "swscissors3" ], "swscissors0": [ "swscissors2", "swscissors1", "swscissors0" ], "owscissors5": [ "owscissors7" ], "owscissors4": [ "owscissors6" ], "owscissors3": [ "owscissors5" ], "owscissors2": [ "owscissors4" ], "owscissors1": [ "owscissors3" ], "owscissors0": [ "owscissors2", "owscissors1", "owscissors0" ], "ywscissors5": [ "ywscissors7" ], "ywscissors4": [ "ywscissors6" ], "ywscissors3": [ "ywscissors5" ], "ywscissors2": [ "ywscissors4" ], "ywscissors1": [ "ywscissors3" ], "ywscissors0": [ "ywscissors2", "ywscissors1", "ywscissors0" ], "bcscissors5": [ "bcscissors7" ], "bcscissors4": [ "bcscissors6" ], "bcscissors3": [ "bcscissors5" ], "bcscissors2": [ "bcscissors4" ], "bcscissors1": [ "bcscissors3" ], "bcscissors0": [ "bcscissors2", "bcscissors1", "bcscissors0" ], "gcscissors5": [ "gcscissors7" ], "gcscissors4": [ "gcscissors6" ], "gcscissors3": [ "gcscissors5" ], "gcscissors2": [ "gcscissors4" ], "gcscissors1": [ "gcscissors3" ], "gcscissors0": [ "gcscissors2", "gcscissors1", "gcscissors0" ], "pcscissors5": [ "pcscissors7" ], "pcscissors4": [ "pcscissors6" ], "pcscissors3": [ "pcscissors5" ], "pcscissors2": [ "pcscissors4" ], "pcscissors1": [ "pcscissors3" ], "pcscissors0": [ "pcscissors2", "pcscissors1", "pcscissors0" ], "mcscissors5": [ "mcscissors7" ], "mcscissors4": [ "mcscissors6" ], "mcscissors3": [ "mcscissors5" ], "mcscissors2": [ "mcscissors4" ], "mcscissors1": [ "mcscissors3" ], "mcscissors0": [ "mcscissors2", "mcscissors1", "mcscissors0" ], "coscissors5": [ "coscissors7" ], "coscissors4": [ "coscissors6" ], "coscissors3": [ "coscissors5" ], "coscissors2": [ "coscissors4" ], "coscissors1": [ "coscissors3" ], "coscissors0": [ "coscissors2", "coscissors1", "coscissors0" ], "boscissors5": [ "boscissors7" ], "boscissors4": [ "boscissors6" ], "boscissors3": [ "boscissors5" ], "boscissors2": [ "boscissors4" ], "boscissors1": [ "boscissors3" ], "boscissors0": [ "boscissors2", "boscissors1", "boscissors0" ], "soscissors5": [ "soscissors7" ], "soscissors4": [ "soscissors6" ], "soscissors3": [ "soscissors5" ], "soscissors2": [ "soscissors4" ], "soscissors1": [ "soscissors3" ], "soscissors0": [ "soscissors2", "soscissors1", "soscissors0" ], "goscissors5": [ "goscissors7" ], "goscissors4": [ "goscissors6" ], "goscissors3": [ "goscissors5" ], "goscissors2": [ "goscissors4" ], "goscissors1": [ "goscissors3" ], "goscissors0": [ "goscissors2", "goscissors1", "goscissors0" ],
								  "vvgun5": [ "vvgun7" ], "vvgun4": [ "vvgun6" ], "vvgun3": [ "vvgun5" ], "vvgun2": [ "vvgun4" ], "vvgun1": [ "vvgun3" ], "vvgun0": [ "vvgun2", "vvgun1", "vvgun0" ],
								  "rwhand5": [ "rwhand7" ], "rwhand4": [ "rwhand6" ], "rwhand3": [ "rwhand5" ], "rwhand2": [ "rwhand4" ], "rwhand1": [ "rwhand3" ], "rwhand0": [ "rwhand2", "rwhand1", "rwhand0" ], "swhand5": [ "swhand7" ], "swhand4": [ "swhand6" ], "swhand3": [ "swhand5" ], "swhand2": [ "swhand4" ], "swhand1": [ "swhand3" ], "swhand0": [ "swhand2", "swhand1", "swhand0" ], "owhand5": [ "owhand7" ], "owhand4": [ "owhand6" ], "owhand3": [ "owhand5" ], "owhand2": [ "owhand4" ], "owhand1": [ "owhand3" ], "owhand0": [ "owhand2", "owhand1", "owhand0" ], "ywhand5": [ "ywhand7" ], "ywhand4": [ "ywhand6" ], "ywhand3": [ "ywhand5" ], "ywhand2": [ "ywhand4" ], "ywhand1": [ "ywhand3" ], "ywhand0": [ "ywhand2", "ywhand1", "ywhand0" ], "bchand5": [ "bchand7" ], "bchand4": [ "bchand6" ], "bchand3": [ "bchand5" ], "bchand2": [ "bchand4" ], "bchand1": [ "bchand3" ], "bchand0": [ "bchand2", "bchand1", "bchand0" ], "gchand5": [ "gchand7" ], "gchand4": [ "gchand6" ], "gchand3": [ "gchand5" ], "gchand2": [ "gchand4" ], "gchand1": [ "gchand3" ], "gchand0": [ "gchand2", "gchand1", "gchand0" ], "pchand5": [ "pchand7" ], "pchand4": [ "pchand6" ], "pchand3": [ "pchand5" ], "pchand2": [ "pchand4" ], "pchand1": [ "pchand3" ], "pchand0": [ "pchand2", "pchand1", "pchand0" ], "mchand5": [ "mchand7" ], "mchand4": [ "mchand6" ], "mchand3": [ "mchand5" ], "mchand2": [ "mchand4" ], "mchand1": [ "mchand3" ], "mchand0": [ "mchand2", "mchand1", "mchand0" ], "cohand5": [ "cohand7" ], "cohand4": [ "cohand6" ], "cohand3": [ "cohand5" ], "cohand2": [ "cohand4" ], "cohand1": [ "cohand3" ], "cohand0": [ "cohand2", "cohand1", "cohand0" ], "bohand5": [ "bohand7" ], "bohand4": [ "bohand6" ], "bohand3": [ "bohand5" ], "bohand2": [ "bohand4" ], "bohand1": [ "bohand3" ], "bohand0": [ "bohand2", "bohand1", "bohand0" ], "sohand5": [ "sohand7" ], "sohand4": [ "sohand6" ], "sohand3": [ "sohand5" ], "sohand2": [ "sohand4" ], "sohand1": [ "sohand3" ], "sohand0": [ "sohand2", "sohand1", "sohand0" ], "gohand5": [ "gohand7" ], "gohand4": [ "gohand6" ], "gohand3": [ "gohand5" ], "gohand2": [ "gohand4" ], "gohand1": [ "gohand3" ], "gohand0": [ "gohand2", "gohand1", "gohand0" ],
								  "vvhand5": [ "vvhand7", "vvhand7x" ], "vvhand4": [ "vvhand6", "vvhand6x" ], "vvhand3": [ "vvhand5", "vvhand5x" ], "vvhand2": [ "vvhand4", "vvhand4x"], "vvhand1": [ "vvhand3", "vvhand3x" ], "vvhand0": [ "vvhand2", "vvhand1", "vvhand0", "vvhand2x", "vvhand1x", "vvhand0x" ], "violethand5": [ "violethand7", "violethand7x" ], "violethand4": [ "violethand6", "violethand6x" ], "violethand3": [ "violethand5", "violethand5x" ], "violethand2": [ "violethand4", "violethand4x"], "violethand1": [ "violethand3", "violethand3x" ], "violethand0": [ "violethand2", "violethand1", "violethand0", "violethand2x", "violethand1x"], "greenhand5": [ "greenhand7", "greenhand7x" ], "greenhand4": [ "greenhand6", "greenhand6x" ], "greenhand3": [ "greenhand5", "greenhand5x" ], "greenhand2": [ "greenhand4", "greenhand4x"], "greenhand1": [ "greenhand3", "greenhand3x" ], "greenhand0": [ "greenhand2", "greenhand1", "greenhand0", "greenhand2x", "greenhand1x"], "emeraldhand5": [ "emeraldhand7", "emeraldhand7x" ], "emeraldhand4": [ "emeraldhand6", "emeraldhand6x" ], "emeraldhand3": [ "emeraldhand5", "emeraldhand5" ], "emeraldhand2": [ "emeraldhand4", "emeraldhand4x"], "emeraldhand1": [ "emeraldhand3", "emeraldhand3" ], "emeraldhand0": [ "emeraldhand2", "emeraldhand1", "emeraldhand0", "emeraldhand2x", "emeraldhand1x"],
								  "bluescissors5": [ "bluescissors7" ], "bluescissors4": [ "bluescissors6" ], "bluescissors3": [ "bluescissors5" ], "bluescissors2": [ "bluescissors4" ], "bluescissors1": [ "bluescissors3" ], "bluescissors0": [ "bluescissors2", "bluescissors1", "bluescissors0" ], "bluehand5": [ "bluehand7", "bluehand7x" ], "bluehand4": [ "bluehand6", "bluehand6x" ], "bluehand3": [ "bluehand5", "bluehand5" ], "bluehand2": [ "bluehand4", "bluehand4x"], "bluehand1": [ "bluehand3", "bluehand3" ], "bluehand0": [ "bluehand2", "bluehand1", "bluehand0", "bluehand2x", "bluehand1x"], "bluerock6": [ "bluerock7" ], "bluerock5": [ "bluerock6" ], "bluerock4": [ "bluerock5" ], "bluerock3": [ "bluerock4" ], "bluerock2": [ "bluerock3" ], "bluerock1": [ "bluerock2"], "bluerock0": [ "bluerock1", "bluerock0" ],
								  "redscissors5": [ "redscissors7" ], "redscissors4": [ "redscissors6" ], "redscissors3": [ "redscissors5" ], "redscissors2": [ "redscissors4" ], "redscissors1": [ "redscissors3" ], "redscissors0": [ "redscissors2", "redscissors1", "redscissors0" ], "redhand5": [ "redhand7", "redhand7x" ], "redhand4": [ "redhand6", "redhand6x" ], "redhand3": [ "redhand5", "redhand5" ], "redhand2": [ "redhand4", "redhand4x"], "redhand1": [ "redhand3", "redhand3" ], "redhand0": [ "redhand2", "redhand1", "redhand0", "redhand2x", "redhand1x"], "redrock6": [ "redrock7" ], "redrock5": [ "redrock6" ], "redrock4": [ "redrock5" ], "redrock3": [ "redrock4" ], "redrock2": [ "redrock3" ], "redrock1": [ "redrock2"], "redrock0": [ "redrock1", "redrock0" ],
								  "yellowscissors5": [ "yellowscissors7" ], "yellowscissors4": [ "yellowscissors6" ], "yellowscissors3": [ "yellowscissors5" ], "yellowscissors2": [ "yellowscissors4" ], "yellowscissors1": [ "yellowscissors3" ], "yellowscissors0": [ "yellowscissors2", "yellowscissors1", "yellowscissors0" ], "yellowhand5": [ "yellowhand7", "yellowhand7x" ], "yellowhand4": [ "yellowhand6", "yellowhand6x" ], "yellowhand3": [ "yellowhand5", "yellowhand5" ], "yellowhand2": [ "yellowhand4", "yellowhand4x"], "yellowhand1": [ "yellowhand3", "yellowhand3" ], "yellowhand0": [ "yellowhand2", "yellowhand1", "yellowhand0", "yellowhand2x", "yellowhand1x"], "yellowrock6": [ "yellowrock7" ], "yellowrock5": [ "yellowrock6" ], "yellowrock4": [ "yellowrock5" ], "yellowrock3": [ "yellowrock4" ], "yellowrock2": [ "yellowrock3" ], "yellowrock1": [ "yellowrock2"], "yellowrock0": [ "yellowrock1", "yellowrock0" ],
								  "emeraldrock6": [ "emeraldrock7" ], "emeraldrock5": [ "emeraldrock6" ], "emeraldrock4": [ "emeraldrock5" ], "emeraldrock3": [ "emeraldrock4" ], "emeraldrock2": [ "emeraldrock3" ], "emeraldrock1": [ "emeraldrock2"], "emeraldrock0": [ "emeraldrock1", "emeraldrock0" ], "violetrock6": [ "violetrock7" ], "violetrock5": [ "violetrock6" ], "violetrock4": [ "violetrock5" ], "violetrock3": [ "violetrock4" ], "violetrock2": [ "violetrock3" ], "violetrock1": [ "violetrock2"], "violetrock0": [ "violetrock1", "violetrock0" ], "greenrock6": [ "greenrock7" ], "greenrock5": [ "greenrock6" ], "greenrock4": [ "greenrock5" ], "greenrock3": [ "greenrock4" ], "greenrock2": [ "greenrock3" ], "greenrock1": [ "greenrock2"], "greenrock0": [ "greenrock1", "greenrock0" ], "rwrock6": [ "rwrock7" ], "rwrock5": [ "rwrock6" ], "rwrock4": [ "rwrock5" ], "rwrock3": [ "rwrock4" ], "rwrock2": [ "rwrock3" ], "rwrock1": [ "rwrock2"], "rwrock0": [ "rwrock1", "rwrock0" ], "swrock6": [ "swrock7" ], "swrock5": [ "swrock6" ], "swrock4": [ "swrock5" ], "swrock3": [ "swrock4" ], "swrock2": [ "swrock3" ], "swrock1": [ "swrock2"], "swrock0": [ "swrock1", "swrock0" ], "owrock6": [ "owrock7" ], "owrock5": [ "owrock6" ], "owrock4": [ "owrock5" ], "owrock3": [ "owrock4" ], "owrock2": [ "owrock3" ], "owrock1": [ "owrock2"], "owrock0": [ "owrock1", "owrock0" ], "ywrock6": [ "ywrock7" ], "ywrock5": [ "ywrock6" ], "ywrock4": [ "ywrock5" ], "ywrock3": [ "ywrock4" ], "ywrock2": [ "ywrock3" ], "ywrock1": [ "ywrock2"], "ywrock0": [ "ywrock1", "ywrock0" ], "bcrock6": [ "bcrock7" ], "bcrock5": [ "bcrock6" ], "bcrock4": [ "bcrock5" ], "bcrock3": [ "bcrock4" ], "bcrock2": [ "bcrock3" ], "bcrock1": [ "bcrock2"], "bcrock0": [ "bcrock1", "bcrock0" ], "gcrock6": [ "gcrock7" ], "gcrock5": [ "gcrock6" ], "gcrock4": [ "gcrock5" ], "gcrock3": [ "gcrock4" ], "gcrock2": [ "gcrock3" ], "gcrock1": [ "gcrock2"], "gcrock0": [ "gcrock1", "gcrock0" ], "pcrock6": [ "pcrock7" ], "pcrock5": [ "pcrock6" ], "pcrock4": [ "pcrock5" ], "pcrock3": [ "pcrock4" ], "pcrock2": [ "pcrock3" ], "pcrock1": [ "pcrock2"], "pcrock0": [ "pcrock1", "pcrock0" ], "mcrock6": [ "mcrock7" ], "mcrock5": [ "mcrock6" ], "mcrock4": [ "mcrock5" ], "mcrock3": [ "mcrock4" ], "mcrock2": [ "mcrock3" ], "mcrock1": [ "mcrock2"], "mcrock0": [ "mcrock1", "mcrock0" ], "corock6": [ "corock7" ], "corock5": [ "corock6" ], "corock4": [ "corock5" ], "corock3": [ "corock4" ], "corock2": [ "corock3" ], "corock1": [ "corock2"], "corock0": [ "corock1", "corock0" ], "borock6": [ "borock7" ], "borock5": [ "borock6" ], "borock4": [ "borock5" ], "borock3": [ "borock4" ], "borock2": [ "borock3" ], "borock1": [ "borock2"], "borock0": [ "borock1", "borock0" ], "sorock6": [ "sorock7" ], "sorock5": [ "sorock6" ], "sorock4": [ "sorock5" ], "sorock3": [ "sorock4" ], "sorock2": [ "sorock3" ], "sorock1": [ "sorock2"], "sorock0": [ "sorock1", "sorock0" ], "gorock6": [ "gorock7" ], "gorock5": [ "gorock6" ], "gorock4": [ "gorock5" ], "gorock3": [ "gorock4" ], "gorock2": [ "gorock3" ], "gorock1": [ "gorock2"], "gorock0": [ "gorock1", "gorock0" ]
								},
				"team rswarm": [
								"rwhand0", "rwhand1", "rwhand2", "rwhand3", "rwhand4", "rwhand5", "rwhand6", "rwhand7", "rwscissors0", "rwscissors1", "rwscissors2", "rwscissors3", "rwscissors4", "rwscissors5", "rwscissors6", "rwscissors7", "rwpaper0", "rwpaper1", "rwpaper2", "rwpaper3", "rwpaper4", "rwpaper5", "rwpaper6", "rwpaper7", "rwrock0", "rwrock1", "rwrock2", "rwrock3", "rwrock4", "rwrock5", "rwrock6", "rwrock7",
								"swhand0", "swhand1", "swhand2", "swhand3", "swhand4", "swhand5", "swhand6", "swhand7", "swscissors0", "swscissors1", "swscissors2", "swscissors3", "swscissors4", "swscissors5", "swscissors6", "swscissors7", "swpaper0", "swpaper1", "swpaper2", "swpaper3", "swpaper4", "swpaper5", "swpaper6", "swpaper7", "swrock0", "swrock1", "swrock2", "swrock3", "swrock4", "swrock5", "swrock6", "swrock7"
							   ],
				"team oywarm": [
								"owhand0", "owhand1", "owhand2", "owhand3", "owhand4", "owhand5", "owhand6", "owhand7", "owscissors0", "owscissors1", "owscissors2", "owscissors3", "owscissors4", "owscissors5", "owscissors6", "owscissors7", "owpaper0", "owpaper1", "owpaper2", "owpaper3", "owpaper4", "owpaper5", "owpaper6", "owpaper7", "owrock0", "owrock1", "owrock2", "owrock3", "owrock4", "owrock5", "owrock6", "owrock7",
								"ywhand0", "ywhand1", "ywhand2", "ywhand3", "ywhand4", "ywhand5", "ywhand6", "ywhand7", "ywscissors0", "ywscissors1", "ywscissors2", "ywscissors3", "ywscissors4", "ywscissors5", "ywscissors6", "ywscissors7", "ywpaper0", "ywpaper1", "ywpaper2", "ywpaper3", "ywpaper4", "ywpaper5", "ywpaper6", "ywpaper7", "ywrock0", "ywrock1", "ywrock2", "ywrock3", "ywrock4", "ywrock5", "ywrock6", "ywrock7"
							   ],
				"team bgcold": [
								"bchand0", "bchand1", "bchand2", "bchand3", "bchand4", "bchand5", "bchand6", "bchand7", "bcscissors0", "bcscissors1", "bcscissors2", "bcscissors3", "bcscissors4", "bcscissors5", "bcscissors6", "bcscissors7", "bcpaper0", "bcpaper1", "bcpaper2", "bcpaper3", "bcpaper4", "bcpaper5", "bcpaper6", "bcpaper7", "bcrock0", "bcrock1", "bcrock2", "bcrock3", "bcrock4", "bcrock5", "bcrock6", "bcrock7",
								"gchand0", "gchand1", "gchand2", "gchand3", "gchand4", "gchand5", "gchand6", "gchand7", "gcscissors0", "gcscissors1", "gcscissors2", "gcscissors3", "gcscissors4", "gcscissors5", "gcscissors6", "gcscissors7", "gcpaper0", "gcpaper1", "gcpaper2", "gcpaper3", "gcpaper4", "gcpaper5", "gcpaper6", "gcpaper7", "gcrock0", "gcrock1", "gcrock2", "gcrock3", "gcrock4", "gcrock5", "gcrock6", "gcrock7"
							   ],
				"team mpcold": [
								"mchand0", "mchand1", "mchand2", "mchand3", "mchand4", "mchand5", "mchand6", "mchand7", "mcscissors0", "mcscissors1", "mcscissors2", "mcscissors3", "mcscissors4", "mcscissors5", "mcscissors6", "mcscissors7", "mcpaper0", "mcpaper1", "mcpaper2", "mcpaper3", "mcpaper4", "mcpaper5", "mcpaper6", "mcpaper7", "mcrock0", "mcrock1", "mcrock2", "mcrock3", "mcrock4", "mcrock5", "mcrock6", "mcrock7",
								"pchand0", "pchand1", "pchand2", "pchand3", "pchand4", "pchand5", "pchand6", "pchand7", "pcscissors0", "pcscissors1", "pcscissors2", "pcscissors3", "pcscissors4", "pcscissors5", "pcscissors6", "pcscissors7", "pcpaper0", "pcpaper1", "pcpaper2", "pcpaper3", "pcpaper4", "pcpaper5", "pcpaper6", "pcpaper7", "pcrock0", "pcrock1", "pcrock2", "pcrock3", "pcrock4", "pcrock5", "pcrock6", "pcrock7"
							   ],
				"team bcoddball": [
								"bohand0", "bohand1", "bohand2", "bohand3", "bohand4", "bohand5", "bohand6", "bohand7", "boscissors0", "boscissors1", "boscissors2", "boscissors3", "boscissors4", "boscissors5", "boscissors6", "boscissors7", "bopaper0", "bopaper1", "bopaper2", "bopaper3", "bopaper4", "bopaper5", "bopaper6", "bopaper7", "borock0", "borock1", "borock2", "borock3", "borock4", "borock5", "borock6", "borock7",
								"cohand0", "cohand1", "cohand2", "cohand3", "cohand4", "cohand5", "cohand6", "cohand7", "coscissors0", "coscissors1", "coscissors2", "coscissors3", "coscissors4", "coscissors5", "coscissors6", "coscissors7", "copaper0", "copaper1", "copaper2", "copaper3", "copaper4", "copaper5", "copaper6", "copaper7", "corock0", "corock1", "corock2", "corock3", "corock4", "corock5", "corock6", "corock7"
							   ],
				"team gsoddball": [
								"gohand0", "gohand1", "gohand2", "gohand3", "gohand4", "gohand5", "gohand6", "gohand7", "goscissors0", "goscissors1", "goscissors2", "goscissors3", "goscissors4", "goscissors5", "goscissors6", "goscissors7", "gopaper0", "gopaper1", "gopaper2", "gopaper3", "gopaper4", "gopaper5", "gopaper6", "gopaper7", "gorock0", "gorock1", "gorock2", "gorock3", "gorock4", "gorock5", "gorock6", "gorock7",
								"sohand0", "sohand1", "sohand2", "sohand3", "sohand4", "sohand5", "sohand6", "sohand7", "soscissors0", "soscissors1", "soscissors2", "soscissors3", "soscissors4", "soscissors5", "soscissors6", "soscissors7", "sopaper0", "sopaper1", "sopaper2", "sopaper3", "sopaper4", "sopaper5", "sopaper6", "sopaper7", "sorock0", "sorock1", "sorock2", "sorock3", "sorock4", "sorock5", "sorock6", "sorock7"
							   ],
				"death msg": "You lost all your HP and died!",
				"generalhand help": "You may attack using /rock, /paper, or /scissors every night to choose your hand and challenge another player.",
				"violethand help": "Your team have more Health Points then the other teams but you are less numerous and know your teammates. You may attack using /rock, /paper, or /scissors every night to choose your hand and challenge another player (not shared with team). If you get a good hit, the target loses 2HP whereas if you make a bad hit, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you.",
				"emeraldhand help": "You have more Health Points then your team mates Green Hands, but your vote power is equal to 0. You may attack using /rock, /paper, or /scissors every night to choose your hand and challenge another player. If you get a good hit, the target loses 2HP whereas if you make a bad hit, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you. Every day you can /inspect how much HP your target has!",
				"greenhand help": "Your team have less Health Points then the other teams but you are more numerous. You may attack using /rock, /paper, or /scissors every night to choose your hand and challenge another player. If you get a good hit, the target loses 2HP whereas if you make a bad hit, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you.",
				"bluehand help": "Fight the enemy hands to become the Rock-Paper-Scissors champion! You may attack using /rock, /paper, or /scissors every night to choose your hand and challenge another player. If you get a good hit, the target loses 2HP whereas if you make a bad hit, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you. You cannot vote!",
				"redhand help": "variable:bluehand help",
				"yellowhand help": "variable:bluehand help",
				"rwhand help": "Fight the enemy hands to become the Rock-Paper-Scissors champion! Sometimes you will be able to know and Team Talk with one of the Red Left Hands. You may attack using /rock, /paper, or /scissors every night to choose your hand and challenge another player. If you get a good hit, the target loses 2HP whereas if you make a bad hit, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you.",
				"swhand help": "Fight the enemy hands to become the Rock-Paper-Scissors champion! Sometimes you will be able to know and Team Talk with one of the Red Right Hands. You may attack using /rock, /paper, or /scissors every night to choose your hand and challenge another player. If you get a good hit, the target loses 2HP whereas if you make a bad hit, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you.",
				"ywhand help": "Fight the enemy hands to become the Rock-Paper-Scissors champion! Sometimes you will be able to know and Team Talk with one of the Red Left Hands. You may attack using /rock, /paper, or /scissors every night to choose your hand and challenge another player. If you get a good hit, the target loses 2HP whereas if you make a bad hit, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you.",
				"owhand help": "Fight the enemy hands to become the Rock-Paper-Scissors champion! Sometimes you will be able to know and Team Talk with one of the Red Right Hands. You may attack using /rock, /paper, or /scissors every night to choose your hand and challenge another player. If you get a good hit, the target loses 2HP whereas if you make a bad hit, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you.",
				"bchand help": "Fight the enemy hands to become the Rock-Paper-Scissors champion! Sometimes you will be able to know and Team Talk with one of the Blue Left Hands. You may attack using /rock, /paper, or /scissors every night to choose your hand and challenge another player. If you get a good hit, the target loses 2HP whereas if you make a bad hit, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you.",
				"gchand help": "Fight the enemy hands to become the Rock-Paper-Scissors champion! Sometimes you will be able to know and Team Talk with one of the Blue Right Hands. You may attack using /rock, /paper, or /scissors every night to choose your hand and challenge another player. If you get a good hit, the target loses 2HP whereas if you make a bad hit, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you.",
				"pchand help": "Fight the enemy hands to become the Rock-Paper-Scissors champion! Sometimes you will be able to know and Team Talk with one of the Blue Left Hands. You may attack using /rock, /paper, or /scissors every night to choose your hand and challenge another player. If you get a good hit, the target loses 2HP whereas if you make a bad hit, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you.",
				"mchand help": "Fight the enemy hands to become the Rock-Paper-Scissors champion! Sometimes you will be able to know and Team Talk with one of the Blue Right Hands. You may attack using /rock, /paper, or /scissors every night to choose your hand and challenge another player. If you get a good hit, the target loses 2HP whereas if you make a bad hit, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you.",
				"cohand help": "Fight the enemy hands to become the Rock-Paper-Scissors champion! Sometimes you will be able to know and Team Talk with one of the Yellow Left Hands. You may attack using /rock, /paper, or /scissors every night to choose your hand and challenge another player. If you get a good hit, the target loses 2HP whereas if you make a bad hit, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you.",
				"bohand help": "Fight the enemy hands to become the Rock-Paper-Scissors champion! Sometimes you will be able to know and Team Talk with one of the Yellow Right Hands. You may attack using /rock, /paper, or /scissors every night to choose your hand and challenge another player. If you get a good hit, the target loses 2HP whereas if you make a bad hit, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you.",
				"sohand help": "Fight the enemy hands to become the Rock-Paper-Scissors champion! Sometimes you will be able to know and Team Talk with one of the Yellow Right Hands. You may attack using /rock, /paper, or /scissors every night to choose your hand and challenge another player. If you get a good hit, the target loses 2HP whereas if you make a bad hit, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you.",
				"gohand help": "Fight the enemy hands to become the Rock-Paper-Scissors champion! Sometimes you will be able to know and Team Talk with one of the Yellow Left Hands. You may attack using /rock, /paper, or /scissors every night to choose your hand and challenge another player. If you get a good hit, the target loses 2HP whereas if you make a bad hit, no one gets damaged, instead if you attack your same element like Scissors on Scissors, the target loses 1HP. This also applies to people that hit you.",
				"violethand info": "They know all their partners and have more health points then the other hands, but they are less numerous. Can transform into /Rock, /Paper or /Scissor during the night (not shared with team). Sided with Violet Hands.",
				"emeraldhand info": "They don't know any of their partners, but have more Health Points then their partners Green Hands. Can transform into /Rock, /Paper or /Scissor during the night. Every night they can inspect how much HP a player has. Their vote power is equal to 0. Sided with Green Hands.",
				"bluehand info": "They don't know any of their partners. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Blue Hands.",
				"redhand info": "They don't know any of their partners. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Red Hands.",
				"yellowhand info": "They don't know any of their partners. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Yellow Hands.",
				"greenhand info": "They don't know any of their partners and have less health points then the other hands, but they are more numerous. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Green Hands.",
				"rwhand info": "Knows one of the Red Left Hands. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Red Hands.",
				"swhand info": "Knows one of the Red Right Hands. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Red Hands.",
				"ywhand info": "Knows one of the Red Left Hands. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Red Hands.",
				"owhand info": "Knows one of the Red Right Hands. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Red Hands.",
				"bchand info": "Knows one of the Blue Left Hands. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Blue Hands.",
				"gchand info": "Knows one of the Blue Right Hands. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Blue Hands.",
				"pchand info": "Knows one of the Blue Left Hands. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Blue Hands.",
				"mchand info": "Knows one of the Blue Right Hands. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Blue Hands.",
				"cohand info": "Knows one of the Yellow Left Hands. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Yellow Hands.",
				"bohand info": "Knows one of the Yellow Right Hands. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Yellow Hands.",
				"sohand info": "Knows one of the Yellow Right Hands. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Yellow Hands.",
				"gohand info": "Knows one of the Yellow Left Hands. Can transform into /Rock, /Paper or /Scissor during the night. Sided with Yellow Hands.",
				"hand info": "Starts with 7HP. Hand can decides to be a /rock, a pair of /scissors or a piece of /paper until the end of the night and to deal 2 damages with their new role if their target is weak to them. If they don't transform during the night, they will be weak to any attack. Sided with their own colour.",
				"scissors help": "",
				"scissors info": "",
				"rock help": "",
				"rock info": "",
				"paper help": "",
				"paper info": "",
				"vvhand help": "Infused with everything dark and light, you are the Gray Hand! These silly hands keep arguing about who is best at Rock-Paper-Scissors when you've been the king for ages. During the night, you may use one of two actions. /gun will instantly kill the target whereas /shield every 2 days will make you evade any hits. The only downside to you is that you take 2 points of damage regardless of what hits you, so you need to be careful. Your vote power is 2. Remember that you can TeamTalk with your partners with /tt. ",
				"vvhand info": "Can use /Gun (instakill) or /Shield (protect himself like if they are resistent to that type of attack) during the night. /shield can be used only every 2 days. Receives 2 points of damage as if weak to every type. Their vote power is 2. Sided with Special Hands.",
				"gun help": "",
				"gun info": "",
				"shield help": "",
				"shield info": ""
			 },
    "roles": [
        {   "role": "rwhand0",
            "translation": "Red Right Hand",
			"help": "variable:rwhand help",
            "info": "variable:rwhand info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" }, "teamTalk": "variable:team rswarm", "preventTeamvote": "variable:team rswarm",
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "rwhand1",
            "translation": "Red Right Hand [1]",
			"help": "variable:rwhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" }, "teamTalk": "variable:team rswarm", "preventTeamvote": "variable:team rswarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "rwhand2",
            "translation": "Red Right Hand [2]",
			"help": "variable:rwhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" }, "teamTalk": "variable:team rswarm", "preventTeamvote": "variable:team rswarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "rwhand3",
            "translation": "Red Right Hand [3]",
			"help": "variable:rwhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" }, "teamTalk": "variable:team rswarm", "preventTeamvote": "variable:team rswarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "rwhand4",
            "translation": "Red Right Hand [4]",
			"help": "variable:rwhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" }, "teamTalk": "variable:team rswarm", "preventTeamvote": "variable:team rswarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "rwhand5",
            "translation": "Red Right Hand [5]",
			"help": "variable:rwhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" }, "teamTalk": "variable:team rswarm", "preventTeamvote": "variable:team rswarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "rwhand6",
            "translation": "Red Right Hand [6]",
			"help": "variable:rwhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" }, "teamTalk": "variable:team rswarm", "preventTeamvote": "variable:team rswarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "rwhand7",
            "translation": "Red Right Hand [7]",
			"hide": true,
			"help": "variable:rwhand help",
            "info": "variable:rwhand info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team rswarm" }, "teamTalk": "variable:team rswarm", "preventTeamvote": "variable:team rswarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "rwpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "rwpaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "rwpaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "rwpaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "rwpaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "rwpaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "rwpaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "rwpaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "rwpaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "rwscissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "rwscissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "rwscissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "rwscissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "rwscissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "rwscissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "rwscissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "rwscissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "rwrock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "rwrock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "rwrock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "rwrock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "rwrock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "rwrock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "rwrock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "rwrock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "rwhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "swhand0",
            "translation": "Red Left Hand",
			"help": "variable:swhand help",
            "info": "variable:swhand info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" }, "teamTalk": "variable:team rswarm", "preventTeamvote": "variable:team rswarm",
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "swhand1",
            "translation": "Red Left Hand [1]",
			"help": "variable:swhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" }, "teamTalk": "variable:team rswarm", "preventTeamvote": "variable:team rswarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "swhand2",
            "translation": "Red Left Hand [2]",
			"help": "variable:swhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" }, "teamTalk": "variable:team rswarm", "preventTeamvote": "variable:team rswarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "swhand3",
            "translation": "Red Left Hand [3]",
			"help": "variable:swhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" }, "teamTalk": "variable:team rswarm", "preventTeamvote": "variable:team rswarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "swhand4",
            "translation": "Red Left Hand [4]",
			"help": "variable:swhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" }, "teamTalk": "variable:team rswarm", "preventTeamvote": "variable:team rswarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "swhand5",
            "translation": "Red Left Hand [5]",
			"help": "variable:swhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" }, "teamTalk": "variable:team rswarm", "preventTeamvote": "variable:team rswarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "swhand6",
            "translation": "Red Left Hand [6]",
			"help": "variable:swhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team rswarm" }, "teamTalk": "variable:team rswarm", "preventTeamvote": "variable:team rswarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "swhand7",
            "translation": "Red Left Hand [7]",
			"help": "variable:swhand help",
			"hide": true,
            "info": "variable:swhand info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team rswarm" }, "teamTalk": "variable:team rswarm", "preventTeamvote": "variable:team rswarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team rswarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "swpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "swpaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "swpaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "swpaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "swpaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "swpaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "swpaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "swpaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "swpaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "swscissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "swscissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "swscissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "swscissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "swscissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "swscissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "swscissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "swscissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "swrock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "swrock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "swrock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "swrock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "swrock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "swrock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "swrock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "swrock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "swhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team rswarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team rswarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "ywhand0",
            "translation": "Red Right Hand",
            "hide": true,
			"help": "variable:ywhand help",
            "info": "variable:ywhand info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" }, "teamTalk": "variable:team oywarm", "preventTeamvote": "variable:team oywarm",
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "ywhand1",
            "translation": "Red Right Hand [1]",
			"help": "variable:ywhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" }, "teamTalk": "variable:team oywarm", "preventTeamvote": "variable:team oywarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "ywhand2",
            "translation": "Red Right Hand [2]",
			"help": "variable:ywhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" }, "teamTalk": "variable:team oywarm", "preventTeamvote": "variable:team oywarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "ywhand3",
            "translation": "Red Right Hand [3]",
			"help": "variable:ywhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" }, "teamTalk": "variable:team oywarm", "preventTeamvote": "variable:team oywarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "ywhand4",
            "translation": "Red Right Hand [4]",
			"help": "variable:ywhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" }, "teamTalk": "variable:team oywarm", "preventTeamvote": "variable:team oywarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "ywhand5",
            "translation": "Red Right Hand [5]",
			"help": "variable:ywhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" }, "teamTalk": "variable:team oywarm", "preventTeamvote": "variable:team oywarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "ywhand6",
            "translation": "Red Right Hand [6]",
			"help": "variable:ywhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" }, "teamTalk": "variable:team oywarm", "preventTeamvote": "variable:team oywarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "ywhand7",
            "translation": "Red Right Hand [7]",
			"help": "variable:ywhand help",
			"hide": true,
            "info": "variable:ywhand info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team oywarm" }, "teamTalk": "variable:team oywarm", "preventTeamvote": "variable:team oywarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "ywpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "ywpaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "ywpaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "ywpaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "ywpaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "ywpaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "ywpaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "ywpaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "ywpaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "ywscissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "ywscissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "ywscissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "ywscissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "ywscissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "ywscissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "ywscissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "ywscissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "ywrock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "ywrock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "ywrock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "ywrock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "ywrock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "ywrock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "ywrock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "ywrock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "ywhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "owhand0",
            "translation": "Red Left Hand",
            "hide": true,
			"help": "variable:owhand help",
            "info": "variable:owhand info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" }, "teamTalk": "variable:team oywarm", "preventTeamvote": "variable:team oywarm",
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "owhand1",
            "translation": "Red Left Hand [1]",
			"help": "variable:owhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" }, "teamTalk": "variable:team oywarm", "preventTeamvote": "variable:team oywarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "owhand2",
            "translation": "Red Left Hand [2]",
			"help": "variable:owhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" }, "teamTalk": "variable:team oywarm", "preventTeamvote": "variable:team oywarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "owhand3",
            "translation": "Red Left Hand [3]",
			"help": "variable:owhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" }, "teamTalk": "variable:team oywarm", "preventTeamvote": "variable:team oywarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "owhand4",
            "translation": "Red Left Hand [4]",
			"help": "variable:owhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" }, "teamTalk": "variable:team oywarm", "preventTeamvote": "variable:team oywarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "owhand5",
            "translation": "Red Left Hand [5]",
			"help": "variable:owhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" }, "teamTalk": "variable:team oywarm", "preventTeamvote": "variable:team oywarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "owhand6",
            "translation": "Red Left Hand [6]",
			"help": "variable:owhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team oywarm" }, "teamTalk": "variable:team oywarm", "preventTeamvote": "variable:team oywarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "owhand7",
            "translation": "Red Left Hand [7]",
			"help": "variable:owhand help",
			"hide": true,
            "info": "variable:owhand info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team oywarm" }, "teamTalk": "variable:team oywarm", "preventTeamvote": "variable:team oywarm",
						"convert": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team oywarm", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "owpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "owpaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "owpaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "owpaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "owpaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "owpaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "owpaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "owpaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "owpaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "owscissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "owscissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "owscissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "owscissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "owscissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "owscissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "owscissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "owscissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "owrock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "owrock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "owrock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "owrock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "owrock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "owrock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "owrock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "owrock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "owhand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team oywarm"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team oywarm"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "pchand0",
            "translation": "Blue Right Hand",
			"help": "variable:pchand help",
            "info": "variable:pchand info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" }, "teamTalk": "variable:team mpcold", "preventTeamvote": "variable:team mpcold",
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "pchand1",
            "translation": "Blue Right Hand [1]",
			"help": "variable:pchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" }, "teamTalk": "variable:team mpcold", "preventTeamvote": "variable:team mpcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "pchand2",
            "translation": "Blue Right Hand [2]",
			"help": "variable:pchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" }, "teamTalk": "variable:team mpcold", "preventTeamvote": "variable:team mpcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "pchand3",
            "translation": "Blue Right Hand [3]",
			"help": "variable:pchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" }, "teamTalk": "variable:team mpcold", "preventTeamvote": "variable:team mpcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "pchand4",
            "translation": "Blue Right Hand [4]",
			"help": "variable:pchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" }, "teamTalk": "variable:team mpcold", "preventTeamvote": "variable:team mpcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "pchand5",
            "translation": "Blue Right Hand [5]",
			"help": "variable:pchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" }, "teamTalk": "variable:team mpcold", "preventTeamvote": "variable:team mpcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "pchand6",
            "translation": "Blue Right Hand [6]",
			"help": "variable:pchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" }, "teamTalk": "variable:team mpcold", "preventTeamvote": "variable:team mpcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "pchand7",
            "translation": "Blue Right Hand [7]",
			"help": "variable:pchand help",
			"hide": true,
            "info": "variable:pchand info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team mpcold" }, "teamTalk": "variable:team mpcold", "preventTeamvote": "variable:team mpcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "pcpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "pcpaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "pcpaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "pcpaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "pcpaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "pcpaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "pcpaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "pcpaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "pcpaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "pcscissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "pcscissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "pcscissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "pcscissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "pcscissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "pcscissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "pcscissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "pcscissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "pcrock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "pcrock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "pcrock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "pcrock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "pcrock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "pcrock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "pcrock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "pcrock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "pchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "mchand0",
            "translation": "Blue Left Hand",
			"help": "variable:mchand help",
            "info": "variable:mchand info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" }, "teamTalk": "variable:team mpcold", "preventTeamvote": "variable:team mpcold",
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "mchand1",
            "translation": "Blue Left Hand [1]",
			"help": "variable:mchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" }, "teamTalk": "variable:team mpcold", "preventTeamvote": "variable:team mpcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "mchand2",
            "translation": "Blue Left Hand [2]",
			"help": "variable:mchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" }, "teamTalk": "variable:team mpcold", "preventTeamvote": "variable:team mpcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "mchand3",
            "translation": "Blue Left Hand [3]",
			"help": "variable:mchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" }, "teamTalk": "variable:team mpcold", "preventTeamvote": "variable:team mpcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "mchand4",
            "translation": "Blue Left Hand [4]",
			"help": "variable:mchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" }, "teamTalk": "variable:team mpcold", "preventTeamvote": "variable:team mpcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "mchand5",
            "translation": "Blue Left Hand [5]",
			"help": "variable:mchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" }, "teamTalk": "variable:team mpcold", "preventTeamvote": "variable:team mpcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "mchand6",
            "translation": "Blue Left Hand [6]",
			"help": "variable:mchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team mpcold" }, "teamTalk": "variable:team mpcold", "preventTeamvote": "variable:team mpcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "mchand7",
            "translation": "Blue Left Hand [7]",
			"help": "variable:mchand help",
			"hide": true,
            "info": "variable:mchand info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team mpcold" }, "teamTalk": "variable:team mpcold", "preventTeamvote": "variable:team mpcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team mpcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "mcpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "mcpaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "mcpaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "mcpaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "mcpaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "mcpaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "mcpaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "mcpaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "mcpaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "mcscissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "mcscissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "mcscissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "mcscissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "mcscissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "mcscissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "mcscissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "mcscissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "mcrock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "mcrock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "mcrock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "mcrock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "mcrock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "mcrock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "mcrock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "mcrock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "mchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team mpcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team mpcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bchand0",
            "translation": "Blue Right Hand",
            "hide": true,
			"help": "variable:bchand help",
            "info": "variable:bchand info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" }, "teamTalk": "variable:team bgcold", "preventTeamvote": "variable:team bgcold",
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bchand1",
            "translation": "Blue Right Hand [1]",
			"help": "variable:bchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" }, "teamTalk": "variable:team bgcold", "preventTeamvote": "variable:team bgcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bchand2",
            "translation": "Blue Right Hand [2]",
			"help": "variable:bchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" }, "teamTalk": "variable:team bgcold", "preventTeamvote": "variable:team bgcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bchand3",
            "translation": "Blue Right Hand [3]",
			"help": "variable:bchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" }, "teamTalk": "variable:team bgcold", "preventTeamvote": "variable:team bgcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bchand4",
            "translation": "Blue Right Hand [4]",
			"help": "variable:bchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" }, "teamTalk": "variable:team bgcold", "preventTeamvote": "variable:team bgcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bchand5",
            "translation": "Blue Right Hand [5]",
			"help": "variable:bchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" }, "teamTalk": "variable:team bgcold", "preventTeamvote": "variable:team bgcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bchand6",
            "translation": "Blue Right Hand [6]",
			"help": "variable:bchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" }, "teamTalk": "variable:team bgcold", "preventTeamvote": "variable:team bgcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bchand7",
            "translation": "Blue Right Hand [7]",
			"help": "variable:bchand help",
			"hide": true,
            "info": "variable:bchand info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team bgcold" }, "teamTalk": "variable:team bgcold", "preventTeamvote": "variable:team bgcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bcpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bcpaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bcpaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bcpaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bcpaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bcpaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bcpaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bcpaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bcpaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bcscissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bcscissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bcscissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bcscissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bcscissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bcscissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bcscissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bcscissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bcrock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bcrock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bcrock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bcrock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bcrock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bcrock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bcrock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bcrock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gchand0",
            "translation": "Blue Left Hand",
			"help": "variable:gchand help",
            "hide": true,
            "info": "variable:gchand info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" }, "teamTalk": "variable:team bgcold", "preventTeamvote": "variable:team bgcold",
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gchand1",
            "translation": "Blue Left Hand [1]",
			"help": "variable:gchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" }, "teamTalk": "variable:team bgcold", "preventTeamvote": "variable:team bgcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gchand2",
            "translation": "Blue Left Hand [2]",
			"help": "variable:gchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" }, "teamTalk": "variable:team bgcold", "preventTeamvote": "variable:team bgcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gchand3",
            "translation": "Blue Left Hand [3]",
			"help": "variable:gchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" }, "teamTalk": "variable:team bgcold", "preventTeamvote": "variable:team bgcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gchand4",
            "translation": "Blue Left Hand [4]",
			"help": "variable:gchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" }, "teamTalk": "variable:team bgcold", "preventTeamvote": "variable:team bgcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gchand5",
            "translation": "Blue Left Hand [5]",
			"help": "variable:gchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" }, "teamTalk": "variable:team bgcold", "preventTeamvote": "variable:team bgcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gchand6",
            "translation": "Blue Left Hand [6]",
			"help": "variable:gchand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bgcold" }, "teamTalk": "variable:team bgcold", "preventTeamvote": "variable:team bgcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gchand7",
            "translation": "Blue Left Hand [7]",
			"help": "variable:gchand help",
			"hide": true,
            "info": "variable:gchand info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team bgcold" }, "teamTalk": "variable:team bgcold", "preventTeamvote": "variable:team bgcold",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bgcold", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gcpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gcpaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gcpaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gcpaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gcpaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gcpaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gcpaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gcpaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gcpaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gcscissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gcscissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gcscissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gcscissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gcscissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gcscissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gcscissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gcscissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gcrock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gcrock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gcrock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gcrock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gcrock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gcrock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gcrock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gcrock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gchand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bgcold"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bgcold"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "cohand0",
            "translation": "Yellow Right Hand",
			"help": "variable:cohand help",
            "info": "variable:cohand info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" }, "teamTalk": "variable:team bcoddball", "preventTeamvote": "variable:team bcoddball",
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "coscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "corock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "copaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "cohand1",
            "translation": "Yellow Right Hand [1]",
			"help": "variable:cohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" }, "teamTalk": "variable:team bcoddball", "preventTeamvote": "variable:team bcoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "coscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "corock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "copaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "cohand2",
            "translation": "Yellow Right Hand [2]",
			"help": "variable:cohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" }, "teamTalk": "variable:team bcoddball", "preventTeamvote": "variable:team bcoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "coscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "corock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "copaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "cohand3",
            "translation": "Yellow Right Hand [3]",
			"help": "variable:cohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" }, "teamTalk": "variable:team bcoddball", "preventTeamvote": "variable:team bcoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "coscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "corock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "copaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "cohand4",
            "translation": "Yellow Right Hand [4]",
			"help": "variable:cohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" }, "teamTalk": "variable:team bcoddball", "preventTeamvote": "variable:team bcoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "coscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "corock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "copaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "cohand5",
            "translation": "Yellow Right Hand [5]",
			"help": "variable:cohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" }, "teamTalk": "variable:team bcoddball", "preventTeamvote": "variable:team bcoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "coscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "corock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "copaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "cohand6",
            "translation": "Yellow Right Hand [6]",
			"help": "variable:cohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" }, "teamTalk": "variable:team bcoddball", "preventTeamvote": "variable:team bcoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "coscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "corock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "copaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "cohand7",
            "translation": "Yellow Right Hand [7]",
			"help": "variable:cohand help",
			"hide": true,
            "info": "variable:cohand info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team bcoddball" }, "teamTalk": "variable:team bcoddball", "preventTeamvote": "variable:team bcoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "coscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "corock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "copaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "copaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "copaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "copaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "copaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "copaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "copaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "copaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "copaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "coscissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "coscissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "coscissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "coscissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "coscissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "coscissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "coscissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "coscissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "corock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "corock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "corock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "corock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "corock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "corock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "corock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "corock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "cohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bohand0",
            "translation": "Yellow Left Hand",
			"help": "variable:bohand help",
            "info": "variable:bohand info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" }, "teamTalk": "variable:team bcoddball", "preventTeamvote": "variable:team bcoddball",
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "boscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "borock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bopaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bohand1",
            "translation": "Yellow Left Hand [1]",
			"help": "variable:bohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" }, "teamTalk": "variable:team bcoddball", "preventTeamvote": "variable:team bcoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "boscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "borock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bopaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bohand2",
            "translation": "Yellow Left Hand [2]",
			"help": "variable:bohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" }, "teamTalk": "variable:team bcoddball", "preventTeamvote": "variable:team bcoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "boscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "borock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bopaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bohand3",
            "translation": "Yellow Left Hand [3]",
			"help": "variable:bohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" }, "teamTalk": "variable:team bcoddball", "preventTeamvote": "variable:team bcoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "boscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "borock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bopaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bohand4",
            "translation": "Yellow Left Hand [4]",
			"help": "variable:bohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" }, "teamTalk": "variable:team bcoddball", "preventTeamvote": "variable:team bcoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "boscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "borock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bopaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bohand5",
            "translation": "Yellow Left Hand [5]",
			"help": "variable:bohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" }, "teamTalk": "variable:team bcoddball", "preventTeamvote": "variable:team bcoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "boscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "borock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bopaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bohand6",
            "translation": "Yellow Left Hand [6]",
			"help": "variable:bohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team bcoddball" }, "teamTalk": "variable:team bcoddball", "preventTeamvote": "variable:team bcoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "boscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "borock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bopaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bohand7",
            "translation": "Yellow Left Hand [7]",
			"help": "variable:bohand help",
			"hide": true,
            "info": "variable:bohand info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team bcoddball" }, "teamTalk": "variable:team bcoddball", "preventTeamvote": "variable:team bcoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "boscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "borock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team bcoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bopaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bopaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bopaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bopaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bopaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bopaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bopaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bopaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bopaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "boscissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "boscissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "boscissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "boscissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "boscissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "boscissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "boscissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "boscissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "borock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "borock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "borock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "borock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "borock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "borock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "borock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "borock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team bcoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team bcoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "sohand0",
            "translation": "Yellow Left Hand",
			"help": "variable:sohand help",
            "hide": true,
            "info": "variable:sohand info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" }, "teamTalk": "variable:team gsoddball", "preventTeamvote": "variable:team gsoddball",
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "soscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sorock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sopaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "sohand1",
            "translation": "Yellow Left Hand [1]",
			"help": "variable:sohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" }, "teamTalk": "variable:team gsoddball", "preventTeamvote": "variable:team gsoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "soscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sorock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sopaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "sohand2",
            "translation": "Yellow Left Hand [2]",
			"help": "variable:sohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" }, "teamTalk": "variable:team gsoddball", "preventTeamvote": "variable:team gsoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "soscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sorock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sopaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "sohand3",
            "translation": "Yellow Left Hand [3]",
			"help": "variable:sohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" }, "teamTalk": "variable:team gsoddball", "preventTeamvote": "variable:team gsoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "soscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sorock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sopaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "sohand4",
            "translation": "Yellow Left Hand [4]",
			"help": "variable:sohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" }, "teamTalk": "variable:team gsoddball", "preventTeamvote": "variable:team gsoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "soscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sorock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sopaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "sohand5",
            "translation": "Yellow Left Hand [5]",
			"help": "variable:sohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" }, "teamTalk": "variable:team gsoddball", "preventTeamvote": "variable:team gsoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "soscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sorock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sopaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "sohand6",
            "translation": "Yellow Left Hand [6]",
			"help": "variable:sohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" }, "teamTalk": "variable:team gsoddball", "preventTeamvote": "variable:team gsoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "soscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sorock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sopaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "sohand7",
            "translation": "Yellow Left Hand [7]",
			"help": "variable:sohand help",
			"hide": true,
            "info": "variable:sohand info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team gsoddball" }, "teamTalk": "variable:team gsoddball", "preventTeamvote": "variable:team gsoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "soscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sorock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "sopaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "sopaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "sopaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "sopaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "sopaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "sopaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "sopaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "sopaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "sopaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "soscissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "soscissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "soscissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "soscissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "soscissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "soscissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "soscissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "soscissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "sorock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "sorock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "sorock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "sorock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "sorock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "sorock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "sorock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "sorock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "sohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gohand0",
            "translation": "Yellow Right Hand",
			"help": "variable:gohand help",
            "hide": true,
            "info": "variable:gohand info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" }, "teamTalk": "variable:team gsoddball", "preventTeamvote": "variable:team gsoddball",
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "goscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gorock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gopaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gohand1",
            "translation": "Yellow Right Hand [1]",
			"help": "variable:gohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" }, "teamTalk": "variable:team gsoddball", "preventTeamvote": "variable:team gsoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "goscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gorock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gopaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gohand2",
            "translation": "Yellow Right Hand [2]",
			"help": "variable:gohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" }, "teamTalk": "variable:team gsoddball", "preventTeamvote": "variable:team gsoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "goscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gorock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gopaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gohand3",
            "translation": "Yellow Right Hand [3]",
			"help": "variable:gohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" }, "teamTalk": "variable:team gsoddball", "preventTeamvote": "variable:team gsoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "goscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gorock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gopaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gohand4",
            "translation": "Yellow Right Hand [4]",
			"help": "variable:gohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" }, "teamTalk": "variable:team gsoddball", "preventTeamvote": "variable:team gsoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "goscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gorock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gopaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gohand5",
            "translation": "Yellow Right Hand [5]",
			"help": "variable:gohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" }, "teamTalk": "variable:team gsoddball", "preventTeamvote": "variable:team gsoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "goscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gorock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gopaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gohand6",
            "translation": "Yellow Right Hand [6]",
			"help": "variable:gohand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
				"startup": { "revealRole": "variable:team gsoddball" }, "teamTalk": "variable:team gsoddball", "preventTeamvote": "variable:team gsoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "goscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gorock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gopaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gohand7",
            "translation": "Yellow Right Hand [7]",
			"help": "variable:gohand help",
			"hide": true,
            "info": "variable:gohand info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
						"startup": { "revealRole": "variable:team gsoddball" }, "teamTalk": "variable:team gsoddball", "preventTeamvote": "variable:team gsoddball",
						"convert": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} } ,"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "goscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gorock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "broadcast": "variable:team gsoddball", "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "gopaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "gopaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gopaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gopaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gopaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gopaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gopaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gopaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "gopaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "goscissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "goscissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "goscissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "goscissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "goscissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "goscissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "goscissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "goscissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy3": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "gorock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand0",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gorock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand1",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gorock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand2",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gorock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand3",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gorock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand4",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gorock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand5",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gorock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand6",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "gorock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "gohand7",
                        "curseCount": 1
                    }
                },
						"convert": { "silent": true,"msg": "You cannot attack your partner","mode": {"ignore": "variable:team gsoddball"} },
						"dummy2": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": {"ignore": "variable:team gsoddball"} },
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "emeraldhand0",
            "translation": "Emerald Hand",
			"help": "variable:generalhand help",
            "info": "variable:emeraldhand info",
            "side": "green",
            "help2": "You have 0HP!",
            "actions": { "inspect": { "revealAs": [ "0" ] }, "vote": 0,

						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "standby": {
                    "inspect": {
						"msg": "Use /inspect to discover how much HP your target has!",
                        "command": "expose",
                        "target": "AnyButSelf", "exposedtargetmsg": "~Target~ has still ~Role~ HP!", "exposemsg": "±Foot: Emerald scanned someone with ~Role~ HP!"
                    }
                },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "emeraldhand1",
            "translation": "Emerald Hand [1]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 1HP!",
            "actions": { "inspect": { "revealAs": [ "1" ] }, "vote": 0,
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "standby": {
                    "inspect": {
						"msg": "Use /inspect to discover how much HP your target has!",
                        "command": "expose",
                        "target": "AnyButSelf", "exposedtargetmsg": "~Target~ has still ~Role~ HP!", "exposemsg": "±Foot: Emerald scanned someone with ~Role~ HP!"
                    }
                },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "emeraldhand2",
            "translation": "Emerald Hand [2]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 2HP!",
            "actions": { "inspect": { "revealAs": [ "2" ] }, "vote": 0,
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "standby": {
                    "inspect": {
						"msg": "Use /inspect to discover how much HP your target has!",
                        "command": "expose",
                        "target": "AnyButSelf", "exposedtargetmsg": "~Target~ has still ~Role~ HP!", "exposemsg": "±Foot: Emerald scanned someone with ~Role~ HP!"
                    }
                },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "emeraldhand3",
            "translation": "Emerald Hand [3]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 3HP!",
            "actions": { "inspect": { "revealAs": [ "3" ] }, "vote": 0,
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "standby": {
                    "inspect": {
						"msg": "Use /inspect to discover how much HP your target has!",
                        "command": "expose",
                        "target": "AnyButSelf", "exposedtargetmsg": "~Target~ has still ~Role~ HP!", "exposemsg": "±Foot: Emerald scanned someone with ~Role~ HP!"
                    }
                },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "emeraldhand4",
            "translation": "Emerald Hand [4]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 4HP!",
            "actions": { "inspect": { "revealAs": [ "4" ] }, "vote": 0,
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "standby": {
                    "inspect": {
						"msg": "Use /inspect to discover how much HP your target has!",
                        "command": "expose",
                        "target": "AnyButSelf", "exposedtargetmsg": "~Target~ has still ~Role~ HP!", "exposemsg": "±Foot: Emerald scanned someone with ~Role~ HP!"
                    }
                },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "emeraldhand5",
            "translation": "Emerald Hand [5]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 5HP!",
            "actions": { "inspect": { "revealAs": [ "5" ] }, "vote": 0,
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "standby": {
                    "inspect": {
						"msg": "Use /inspect to discover how much HP your target has!",
                        "command": "expose",
                        "target": "AnyButSelf", "exposedtargetmsg": "~Target~ has still ~Role~ HP!", "exposemsg": "±Foot: Emerald scanned someone with ~Role~ HP!"
                    }
                },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "emeraldhand6",
            "translation": "Emerald Hand [6]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 6HP!",
            "actions": { "inspect": { "revealAs": [ "6" ] }, "vote": 0,
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "standby": {
                    "inspect": {
						"msg": "Use /inspect to discover how much HP your target has!",
                        "command": "expose",
                        "target": "AnyButSelf", "exposedtargetmsg": "~Target~ has still ~Role~ HP!", "exposemsg": "±Foot: Emerald scanned someone with ~Role~ HP!"
                    }
                },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "emeraldhand7",
            "translation": "Emerald Hand [7]",
			"hide": true,
			"help": "variable:generalhand help",
            "info": "variable:emeraldhand info",
            "side": "green",
            "help2": "You have 7HP!",
            "actions": { "inspect": { "revealAs": [ "7" ] }, "vote": 0,
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "standby": {
                    "inspect": {
						"msg": "Use /inspect to discover how much HP your target has!",
                        "command": "expose",
                        "target": "AnyButSelf", "exposedtargetmsg": "~Target~ has still ~Role~ HP!", "exposemsg": "±Foot: Emerald scanned someone with ~Role~ HP!"
                    }
                },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "emeraldhand1x",
            "translation": "Emerald Hand [1]",
			"help": "variable:emeraldhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 1HP!",
            "actions": { "inspect": { "revealAs": [ "1" ] }, "vote": 0,
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "standby": {
                    "inspect": {
						"msg": "Use /inspect to discover how much HP your target has!",
						"initialrecharge": 1,
                        "command": "expose",
                        "target": "AnyButSelf", "exposedtargetmsg": "~Target~ has still ~Role~ HP!", "exposemsg": "±Foot: Emerald scanned someone with ~Role~ HP!"
                    }
                },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "emeraldhand2x",
            "translation": "Emerald Hand [2]",
			"help": "variable:emeraldhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 2HP!",
            "actions": { "inspect": { "revealAs": [ "2" ] }, "vote": 0,
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "standby": {
                    "inspect": {
						"msg": "Use /inspect to discover how much HP your target has!",
						"initialrecharge": 1,
                        "command": "expose",
                        "target": "AnyButSelf", "exposedtargetmsg": "~Target~ has still ~Role~ HP!", "exposemsg": "±Foot: Emerald scanned someone with ~Role~ HP!"
                    }
                },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "emeraldhand3x",
            "translation": "Emerald Hand [3]",
			"help": "variable:emeraldhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 3HP!",
            "actions": { "inspect": { "revealAs": [ "3" ] }, "vote": 0,
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "standby": {
                    "inspect": {
						"msg": "Use /inspect to discover how much HP your target has!",
						"initialrecharge": 1,
                        "command": "expose",
                        "target": "AnyButSelf", "exposedtargetmsg": "~Target~ has still ~Role~ HP!", "exposemsg": "±Foot: Emerald scanned someone with ~Role~ HP!"
                    }
                },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "emeraldhand4x",
            "translation": "Emerald Hand [4]",
			"help": "variable:emeraldhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 4HP!",
            "actions": { "inspect": { "revealAs": [ "4" ] }, "vote": 0,
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "standby": {
                    "inspect": {
						"msg": "Use /inspect to discover how much HP your target has!",
						"initialrecharge": 1,
                        "command": "expose",
                        "target": "AnyButSelf", "exposedtargetmsg": "~Target~ has still ~Role~ HP!", "exposemsg": "±Foot: Emerald scanned someone with ~Role~ HP!"
                    }
                },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "emeraldhand5x",
            "translation": "Emerald Hand [5]",
			"help": "variable:emeraldhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 5HP!",
            "actions": { "inspect": { "revealAs": [ "5" ] }, "vote": 0,
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "standby": {
                    "inspect": {
						"msg": "Use /inspect to discover how much HP your target has!",
						"initialrecharge": 1,
                        "command": "expose",
                        "target": "AnyButSelf", "exposedtargetmsg": "~Target~ has still ~Role~ HP!", "exposemsg": "±Foot: Emerald scanned someone with ~Role~ HP!"
                    }
                },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "emeraldhand6x",
            "translation": "Emerald Hand [6]",
			"help": "variable:emeraldhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 6HP!",
            "actions": { "inspect": { "revealAs": [ "6" ] }, "vote": 0,
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "standby": {
                    "inspect": {
						"msg": "Use /inspect to discover how much HP your target has!",
						"initialrecharge": 1,
                        "command": "expose",
                        "target": "AnyButSelf", "exposedtargetmsg": "~Target~ has still ~Role~ HP!", "exposemsg": "±Foot: Emerald scanned someone with ~Role~ HP!"
                    }
                },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "emeraldhand7x",
            "translation": "Emerald Hand [7]",
			"hide": true,
			"help": "variable:emeraldhand help",
            "info": "variable:emeraldhand info",
            "side": "green",
            "help2": "You have 7HP!",
            "actions": { "inspect": { "revealAs": [ "7" ] }, "vote": 0,
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "standby": {
                    "inspect": {
						"msg": "Use /inspect to discover how much HP your target has!",
						"initialrecharge": 1,
                        "command": "expose",
                        "target": "AnyButSelf", "exposedtargetmsg": "~Target~ has still ~Role~ HP!", "exposemsg": "±Foot: Emerald scanned someone with ~Role~ HP!"
                    }
                },
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "emeraldpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "emeraldpaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "green",
            "help2": "You have 0HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand0",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "emeraldpaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "green",
            "help2": "You have 1HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand1",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "emeraldpaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "green",
            "help2": "You have 2HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand2",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "emeraldpaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "green",
            "help2": "You have 3HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand3",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "emeraldpaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "green",
            "help2": "You have 4HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand4",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "emeraldpaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "green",
            "help2": "You have 5HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand5",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "emeraldpaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "green",
            "help2": "You have 6HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand6",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "emeraldpaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "green",
            "help2": "You have 7HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand7",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "emeraldscissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "green",
            "help2": "You have 0HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand0",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "emeraldscissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "green",
            "help2": "You have 1HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand1",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "emeraldscissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "green",
            "help2": "You have 2HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand2",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "emeraldscissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "green",
            "help2": "You have 3HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand3",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "emeraldscissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "green",
            "help2": "You have 4HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand4",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "emeraldscissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "green",
            "help2": "You have 5HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand5",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "emeraldscissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "green",
            "help2": "You have 6HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand6",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "emeraldscissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "green",
            "help2": "You have 7HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand7",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "emeraldrock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "green",
            "help2": "You have 0HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand0",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "emeraldrock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "green",
            "help2": "You have 1HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand1",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "emeraldrock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "green",
            "help2": "You have 2HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand2",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "emeraldrock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "green",
            "help2": "You have 3HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand3",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "emeraldrock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "green",
            "help2": "You have 4HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand4",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "emeraldrock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "green",
            "help2": "You have 5HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand5",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "emeraldrock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "green",
            "help2": "You have 6HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand6",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "emeraldrock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "green",
            "help2": "You have 7HP!",
            "actions": { "vote": 0,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "emeraldhand7",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "redhand0",
            "translation": "Red Hand",
			"hide": true,
			"help": "variable:generalhand help",
            "info": "variable:redhand info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "0" ] },

						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "redhand1",
            "translation": "Red Hand [1]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "1" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "redhand2",
            "translation": "Red Hand [2]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "2" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "redhand3",
            "translation": "Red Hand [3]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "3" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "redhand4",
            "translation": "Red Hand [4]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "4" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "redhand5",
            "translation": "Red Hand [5]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "5" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "redhand6",
            "translation": "Red Hand [6]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "6" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "redhand7",
            "translation": "Red Hand [7]",
			"hide": true,
			"help": "variable:generalhand help",
            "info": "variable:redhand info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "7" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "redhand1x",
            "translation": "Red Hand [1]",
			"help": "variable:redhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "1" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "redhand2x",
            "translation": "Red Hand [2]",
			"help": "variable:redhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "2" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "redhand3x",
            "translation": "Red Hand [3]",
			"help": "variable:redhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "3" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "redhand4x",
            "translation": "Red Hand [4]",
			"help": "variable:redhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "4" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "redhand5x",
            "translation": "Red Hand [5]",
			"help": "variable:redhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "5" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "redhand6x",
            "translation": "Red Hand [6]",
			"help": "variable:redhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "6" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "redhand7x",
            "translation": "Red Hand [7]",
			"hide": true,
			"help": "variable:redhand help",
            "info": "variable:redhand info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "7" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "redpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "redpaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand0",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "redpaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand1",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "redpaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand2",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "redpaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand3",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "redpaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand4",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "redpaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand5",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "redpaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand6",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "redpaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand7",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "redscissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand0",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "redscissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand1",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "redscissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand2",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "redscissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand3",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "redscissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand4",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "redscissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand5",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "redscissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand6",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "redscissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand7",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "redrock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 0HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand0",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "redrock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 1HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand1",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "redrock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 2HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand2",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "redrock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 3HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand3",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "redrock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 4HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand4",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "redrock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 5HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand5",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "redrock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 6HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand6",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "redrock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "warm",
            "help2": "You have 7HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "redhand7",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bluehand0",
            "translation": "Blue Hand",
			"hide": true,
			"help": "variable:generalhand help",
            "info": "variable:bluehand info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "0" ] },

						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluescissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluerock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluepaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bluehand1",
            "translation": "Blue Hand [1]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "1" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluescissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluerock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluepaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bluehand2",
            "translation": "Blue Hand [2]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "2" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluescissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluerock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluepaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bluehand3",
            "translation": "Blue Hand [3]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "3" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluescissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluerock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluepaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bluehand4",
            "translation": "Blue Hand [4]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "4" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluescissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluerock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluepaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bluehand5",
            "translation": "Blue Hand [5]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "5" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluescissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluerock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluepaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bluehand6",
            "translation": "Blue Hand [6]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "6" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluescissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluerock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluepaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bluehand7",
            "translation": "Blue Hand [7]",
			"hide": true,
			"help": "variable:generalhand help",
            "info": "variable:bluehand info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "7" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluescissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluerock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluepaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bluehand1x",
            "translation": "Blue Hand [1]",
			"help": "variable:bluehand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "1" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluescissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluerock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluepaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bluehand2x",
            "translation": "Blue Hand [2]",
			"help": "variable:bluehand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "2" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluescissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluerock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluepaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bluehand3x",
            "translation": "Blue Hand [3]",
			"help": "variable:bluehand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "3" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluescissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluerock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluepaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bluehand4x",
            "translation": "Blue Hand [4]",
			"help": "variable:bluehand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "4" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluescissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluerock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluepaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bluehand5x",
            "translation": "Blue Hand [5]",
			"help": "variable:bluehand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "5" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluescissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluerock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluepaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bluehand6x",
            "translation": "Blue Hand [6]",
			"help": "variable:bluehand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "6" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluescissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluerock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluepaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bluehand7x",
            "translation": "Blue Hand [7]",
			"hide": true,
			"help": "variable:bluehand help",
            "info": "variable:bluehand info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "7" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluescissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluerock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "bluepaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "bluepaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand0",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bluepaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand1",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bluepaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand2",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bluepaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand3",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bluepaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand4",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bluepaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand5",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bluepaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand6",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bluepaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand7",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "bluescissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand0",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bluescissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand1",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bluescissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand2",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bluescissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand3",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bluescissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand4",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bluescissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand5",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bluescissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand6",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bluescissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand7",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "bluerock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 0HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand0",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bluerock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 1HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand1",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bluerock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 2HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand2",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bluerock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 3HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand3",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bluerock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 4HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand4",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bluerock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 5HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand5",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bluerock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 6HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand6",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "bluerock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "cold",
            "help2": "You have 7HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "bluehand7",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "yellowhand0",
            "translation": "Yellow Hand",
			"hide": true,
			"help": "variable:generalhand help",
            "info": "variable:yellowhand info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "0" ] },

						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "yellowhand1",
            "translation": "Yellow Hand [1]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "1" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "yellowhand2",
            "translation": "Yellow Hand [2]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "2" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "yellowhand3",
            "translation": "Yellow Hand [3]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "3" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "yellowhand4",
            "translation": "Yellow Hand [4]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "4" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "yellowhand5",
            "translation": "Yellow Hand [5]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "5" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "yellowhand6",
            "translation": "Yellow Hand [6]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "6" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "yellowhand7",
            "translation": "Yellow Hand [7]",
			"hide": true,
			"help": "variable:generalhand help",
            "info": "variable:yellowhand info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "7" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "yellowhand1x",
            "translation": "Yellow Hand [1]",
			"help": "variable:yellowhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "1" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "yellowhand2x",
            "translation": "Yellow Hand [2]",
			"help": "variable:yellowhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "2" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "yellowhand3x",
            "translation": "Yellow Hand [3]",
			"help": "variable:yellowhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "3" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "yellowhand4x",
            "translation": "Yellow Hand [4]",
			"help": "variable:yellowhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "4" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "yellowhand5x",
            "translation": "Yellow Hand [5]",
			"help": "variable:yellowhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "5" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "yellowhand6x",
            "translation": "Yellow Hand [6]",
			"help": "variable:yellowhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "6" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "yellowhand7x",
            "translation": "Yellow Hand [7]",
			"hide": true,
			"help": "variable:yellowhand help",
            "info": "variable:yellowhand info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": { "noVote": true, "inspect": { "revealAs": [ "7" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "yellowpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "yellowpaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand0",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "yellowpaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand1",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "yellowpaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand2",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "yellowpaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand3",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "yellowpaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand4",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "yellowpaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand5",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "yellowpaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand6",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "yellowpaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand7",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "yellowscissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand0",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "yellowscissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand1",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "yellowscissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand2",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "yellowscissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand3",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "yellowscissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand4",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "yellowscissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand5",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "yellowscissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand6",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "yellowscissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand7",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "yellowrock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 0HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand0",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "yellowrock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 1HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand1",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "yellowrock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 2HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand2",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "yellowrock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 3HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand3",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "yellowrock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 4HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand4",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "yellowrock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 5HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand5",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "yellowrock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 6HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand6",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "yellowrock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "oddball",
            "help2": "You have 7HP!",
            "actions": { "noVote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "yellowhand7",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "greenhand0",
            "translation": "Green Hand",
			"help": "variable:generalhand help",
            "info": "variable:greenhand info",
            "side": "green",
            "help2": "You have 0HP!",
            "actions": { "inspect": { "revealAs": [ "0" ] },

						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "greenhand1",
            "translation": "Green Hand [1]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 1HP!",
            "actions": { "inspect": { "revealAs": [ "1" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "greenhand2",
            "translation": "Green Hand [2]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 2HP!",
            "actions": { "inspect": { "revealAs": [ "2" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "greenhand3",
            "translation": "Green Hand [3]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 3HP!",
            "actions": { "inspect": { "revealAs": [ "3" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "greenhand4",
            "translation": "Green Hand [4]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 4HP!",
            "actions": { "inspect": { "revealAs": [ "4" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "greenhand5",
            "translation": "Green Hand [5]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 5HP!",
            "actions": { "inspect": { "revealAs": [ "5" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "greenhand6",
            "translation": "Green Hand [6]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 6HP!",
            "actions": { "inspect": { "revealAs": [ "6" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "greenhand7",
            "translation": "Green Hand [7]",
			"hide": true,
			"help": "variable:generalhand help",
            "info": "variable:greenhand info",
            "side": "green",
            "help2": "You have 7HP!",
            "actions": { "inspect": { "revealAs": [ "7" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "greenhand1x",
            "translation": "Green Hand [1]",
			"help": "variable:greenhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 1HP!",
            "actions": { "inspect": { "revealAs": [ "1" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "greenhand2x",
            "translation": "Green Hand [2]",
			"help": "variable:greenhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 2HP!",
            "actions": { "inspect": { "revealAs": [ "2" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "greenhand3x",
            "translation": "Green Hand [3]",
			"help": "variable:greenhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 3HP!",
            "actions": { "inspect": { "revealAs": [ "3" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "greenhand4x",
            "translation": "Green Hand [4]",
			"help": "variable:greenhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 4HP!",
            "actions": { "inspect": { "revealAs": [ "4" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "greenhand5x",
            "translation": "Green Hand [5]",
			"help": "variable:greenhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 5HP!",
            "actions": { "inspect": { "revealAs": [ "5" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "greenhand6x",
            "translation": "Green Hand [6]",
			"help": "variable:greenhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "green",
            "help2": "You have 6HP!",
            "actions": { "inspect": { "revealAs": [ "6" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "greenhand7x",
            "translation": "Green Hand [7]",
			"hide": true,
			"help": "variable:greenhand help",
            "info": "variable:greenhand info",
            "side": "green",
            "help2": "You have 7HP!",
            "actions": { "inspect": { "revealAs": [ "7" ] },
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButSelf","canCopy": "*","copyfailmsg": "","copyAs": "greenpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "greenpaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "green",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand0",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "greenpaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "green",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand1",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "greenpaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "green",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand2",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "greenpaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "green",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand3",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "greenpaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "green",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand4",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "greenpaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "green",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand5",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "greenpaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "green",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand6",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "greenpaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "green",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand7",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "greenscissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "green",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand0",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "greenscissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "green",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand1",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "greenscissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "green",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand2",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "greenscissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "green",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand3",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "greenscissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "green",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand4",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "greenscissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "green",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand5",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "greenscissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "green",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand6",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "greenscissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "green",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand7",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "greenrock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "green",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand0",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "greenrock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "green",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand1",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "greenrock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "green",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand2",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "greenrock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "green",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand3",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "greenrock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "green",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand4",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "greenrock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "green",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand5",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "greenrock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "green",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand6",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "greenrock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "green",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "greenhand7",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "violethand0",
            "translation": "Violet Hand",
			"help": "variable:generalhand help",
            "info": "variable:violethand info",
            "side": "violet",
            "help2": "You have 0HP!",
            "actions": { "inspect": { "revealAs": [ "0" ] },
						"teamTalk": true, "preventTeamvote": true,
						"startup": "team-reveal-with-roles",
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetscissors0" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetrock0" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetpaper0" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "violethand1",
            "translation": "Violet Hand [1]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "violet",
            "help2": "You have 1HP!",
            "actions": { "inspect": { "revealAs": [ "1" ] },
						"teamTalk": true, "preventTeamvote": true,
						"startup": "team-reveal-with-roles",
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "violethand2",
            "translation": "Violet Hand [2]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "violet",
            "help2": "You have 2HP!",
            "actions": { "inspect": { "revealAs": [ "2" ] },
						"teamTalk": true, "preventTeamvote": true,
						"startup": "team-reveal-with-roles",
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "violethand3",
            "translation": "Violet Hand [3]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "violet",
            "help2": "You have 3HP!",
            "actions": { "inspect": { "revealAs": [ "3" ] },
						"teamTalk": true, "preventTeamvote": true,
						"startup": "team-reveal-with-roles",
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "violethand4",
            "translation": "Violet Hand [4]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "violet",
            "help2": "You have 4HP!",
            "actions": { "inspect": { "revealAs": [ "4" ] },
						"teamTalk": true, "preventTeamvote": true,
						"startup": "team-reveal-with-roles",
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "violethand5",
            "translation": "Violet Hand [5]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "violet",
            "help2": "You have 5HP!",
            "actions": { "inspect": { "revealAs": [ "5" ] },
						"teamTalk": true, "preventTeamvote": true,
						"startup": "team-reveal-with-roles",
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "violethand6",
            "translation": "Violet Hand [6]",
			"help": "variable:generalhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "violet",
            "help2": "You have 6HP!",
            "actions": { "inspect": { "revealAs": [ "6" ] },
						"teamTalk": true, "preventTeamvote": true,
						"startup": "team-reveal-with-roles",
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "violethand7",
            "translation": "Violet Hand [7]",
			"hide": true,
			"help": "variable:generalhand help",
            "info": "variable:violethand info",
            "side": "violet",
            "help2": "You have 7HP!",
            "actions": { "inspect": { "revealAs": [ "7" ] },
						"teamTalk": true, "preventTeamvote": true,
						"startup": "team-reveal-with-roles",
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "violethand1x",
            "translation": "Violet Hand [1]",
			"help": "variable:violethand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "violet",
            "help2": "You have 1HP!",
            "actions": { "inspect": { "revealAs": [ "1" ] },
						"teamTalk": true, "preventTeamvote": true,
						"startup": "team-reveal-with-roles",
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetscissors1" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetrock1" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetpaper1" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "violethand2x",
            "translation": "Violet Hand [2]",
			"help": "variable:violethand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "violet",
            "help2": "You have 2HP!",
            "actions": { "inspect": { "revealAs": [ "2" ] },
						"teamTalk": true, "preventTeamvote": true,
						"startup": "team-reveal-with-roles",
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetscissors2" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetrock2" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetpaper2" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "violethand3x",
            "translation": "Violet Hand [3]",
			"help": "variable:violethand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "violet",
            "help2": "You have 3HP!",
            "actions": { "inspect": { "revealAs": [ "3" ] },
						"teamTalk": true, "preventTeamvote": true,
						"startup": "team-reveal-with-roles",
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetscissors3" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetrock3" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetpaper3" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "violethand4x",
            "translation": "Violet Hand [4]",
			"help": "variable:violethand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "violet",
            "help2": "You have 4HP!",
            "actions": { "inspect": { "revealAs": [ "4" ] },
						"teamTalk": true, "preventTeamvote": true,
						"startup": "team-reveal-with-roles",
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetscissors4" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetrock4" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetpaper4" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "violethand5x",
            "translation": "Violet Hand [5]",
			"help": "variable:violethand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "violet",
            "help2": "You have 5HP!",
            "actions": { "inspect": { "revealAs": [ "5" ] },
						"teamTalk": true, "preventTeamvote": true,
						"startup": "team-reveal-with-roles",
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetscissors5" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetrock5" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetpaper5" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "violethand6x",
            "translation": "Violet Hand [6]",
			"help": "variable:violethand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "violet",
            "help2": "You have 6HP!",
            "actions": { "inspect": { "revealAs": [ "6" ] },
						"teamTalk": true, "preventTeamvote": true,
						"startup": "team-reveal-with-roles",
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetscissors6" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetrock6" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetpaper6" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "violethand7x",
            "translation": "Violet Hand [7]",
			"hide": true,
			"help": "variable:violethand help",
            "info": "variable:violethand info",
            "side": "violet",
            "help2": "You have 7HP!",
            "actions": { "inspect": { "revealAs": [ "7" ] },
						"teamTalk": true, "preventTeamvote": true,
						"startup": "team-reveal-with-roles",
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "scissors": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetscissors7" ,"cancel": [ "rock","paper" ]
                    },
                    "rock": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetrock7" ,"cancel": [ "scissors","paper" ]
                    },
                    "paper": {
					"hide": true,"command": [ "copy" ], "priority": 0,"common": "Self","silent": true, "silentCopy": true,
					"target": "AnyButTeam", "broadcast": "team", "canCopy": "*","copyfailmsg": "","copyAs": "violetpaper7" ,"cancel": [ "scissors","rock" ]
                    }
                }
            }
        },
        {   "role": "violetpaper0",
            "translation": "[0]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "violet",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand0",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "violetpaper1",
            "translation": "[1]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "violet",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand1",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "violetpaper2",
            "translation": "[2]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "violet",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand2",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "violetpaper3",
            "translation": "[3]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "violet",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand3",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "violetpaper4",
            "translation": "[4]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "violet",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand4",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "violetpaper5",
            "translation": "[5]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "violet",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand5",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "violetpaper6",
            "translation": "[6]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "violet",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand6",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "violetpaper7",
            "translation": "[7]",
			"help": "variable:paper help",
            "hide": true,
            "info": "variable:paper info",
            "side": "violet",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand7",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:paper attack"
            }
        },
        {   "role": "violetscissors0",
            "translation": "[0]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "violet",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand0",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "violetscissors1",
            "translation": "[1]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "violet",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand1",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "violetscissors2",
            "translation": "[2]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "violet",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand2",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "violetscissors3",
            "translation": "[3]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "violet",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand3",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "violetscissors4",
            "translation": "[4]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "violet",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand4",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "violetscissors5",
            "translation": "[5]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "violet",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand5",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "violetscissors6",
            "translation": "[6]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "violet",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand6",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "violetscissors7",
            "translation": "[7]",
			"help": "variable:scissors help",
            "hide": true,
            "info": "variable:scissors info",
            "side": "violet",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand7",
                        "curseCount": 1
                    }
                },
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy": { "silent": true,"mode": "ignore"},
                "night": "variable:scissors attack"
            }
        },
        {   "role": "violetrock0",
            "translation": "[0]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "violet",
            "help2": "You have 0HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand0",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "violetrock1",
            "translation": "[1]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "violet",
            "help2": "You have 1HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand1",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "violetrock2",
            "translation": "[2]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "violet",
            "help2": "You have 2HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand2",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "violetrock3",
            "translation": "[3]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "violet",
            "help2": "You have 3HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand3",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "violetrock4",
            "translation": "[4]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "violet",
            "help2": "You have 4HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand4",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "violetrock5",
            "translation": "[5]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "violet",
            "help2": "You have 5HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand5",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "violetrock6",
            "translation": "[6]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "violet",
            "help2": "You have 6HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand6",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "violetrock7",
            "translation": "[7]",
			"help": "variable:rock help",
            "hide": true,
            "info": "variable:rock info",
            "side": "violet",
            "help2": "You have 7HP!",
            "actions": {
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "violethand7",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"},
                "night": "variable:rock attack"
            }
        },
        {   "role": "vvhand0",
            "translation": "Gray Hand",
			"help": "variable:vvhand help",
            "info": "variable:vvhand info",
            "side": "voodoo",
            "help2": "You have 0HP!",
            "actions": { "inspect": { "revealAs": [ "0" ] }, "vote": 2,
				"startup": "team-reveal-with-roles", "teamTalk": true, "preventTeamvote": true,
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {"command": [ "copy" ], "priority": -2,"common": "Self","silent": true, "silentCopy": true,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun0","cancel": [ "shield" ]
                    },
                    "shield": {"command": [ "convert" ],"priority": -2,"common": "Self","silent": true, "silentConvert": true, "recharge": 2,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield0","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand0x",
            "translation": "Gray Hand",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 0HP!",
            "actions": { "inspect": { "revealAs": [ "0" ] }, "vote": 2,
				"startup": "team-reveal-with-roles", "teamTalk": true, "preventTeamvote": true,
						"initialCondition": { "poison": { "count": 1,"poisonDeadMessage": "variable:death msg"}},
						"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": -2,"common": "Self","silent": true, "silentCopy": true, "limit": 1,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun0","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": -2,"common": "Self","silent": true, "silentConvert": true, "limit": 1, "recharge": 2,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield0","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand1",
            "translation": "Gray Hand [1]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 1HP!",
            "actions": { "inspect": { "revealAs": [ "1" ] }, "vote": 2,
				"startup": "team-reveal-with-roles", "teamTalk": true, "preventTeamvote": true,
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": -2,"common": "Self","silent": true, "silentCopy": true,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun1","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": -2,"common": "Self","silent": true, "silentConvert": true, "recharge": 2,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield1","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand1x",
            "translation": "Gray Hand [1]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 1HP!",
            "actions": { "inspect": { "revealAs": [ "1" ] }, "vote": 2,
				"startup": "team-reveal-with-roles", "teamTalk": true, "preventTeamvote": true,
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": -2,"common": "Self","silent": true, "silentCopy": true, "limit": 1,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun1","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": -2,"common": "Self","silent": true, "silentConvert": true, "limit": 1, "recharge": 2,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield1","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand2",
            "translation": "Gray Hand [2]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 2HP!",
            "actions": { "inspect": { "revealAs": [ "2" ] }, "vote": 2,
				"startup": "team-reveal-with-roles", "teamTalk": true, "preventTeamvote": true,
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": -2,"common": "Self","silent": true, "silentCopy": true,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun2","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": -2,"common": "Self","silent": true, "silentConvert": true, "recharge": 2,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield2","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand2x",
            "translation": "Gray Hand [2]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 2HP!",
            "actions": { "inspect": { "revealAs": [ "2" ] }, "vote": 2,
				"startup": "team-reveal-with-roles", "teamTalk": true, "preventTeamvote": true,
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": -2,"common": "Self","silent": true, "silentCopy": true, "limit": 1,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun2","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": -2,"common": "Self","silent": true, "silentConvert": true, "limit": 1, "recharge": 2,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield2","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand3",
            "translation": "Gray Hand [3]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 3HP!",
            "actions": { "inspect": { "revealAs": [ "3" ] }, "vote": 2,
				"startup": "team-reveal-with-roles", "teamTalk": true, "preventTeamvote": true,
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": -2,"common": "Self","silent": true, "silentCopy": true,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun3","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": -2,"common": "Self","silent": true, "silentConvert": true, "recharge": 2,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield3","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand3x",
            "translation": "Gray Hand [3]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 3HP!",
            "actions": { "inspect": { "revealAs": [ "3" ] }, "vote": 2,
				"startup": "team-reveal-with-roles", "teamTalk": true, "preventTeamvote": true,
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": -2,"common": "Self","silent": true, "silentCopy": true, "limit": 1,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun3","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": -2,"common": "Self","silent": true, "silentConvert": true, "limit": 1, "recharge": 2,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield3","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand4",
            "translation": "Gray Hand [4]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 4HP!",
            "actions": { "inspect": { "revealAs": [ "4" ] }, "vote": 2,
				"startup": "team-reveal-with-roles", "teamTalk": true, "preventTeamvote": true,
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": -2,"common": "Self","silent": true, "silentCopy": true,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun4","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": -2,"common": "Self","silent": true, "silentConvert": true, "recharge": 2,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield4","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand4x",
            "translation": "Gray Hand [4]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 4HP!",
            "actions": { "inspect": { "revealAs": [ "4" ] }, "vote": 2,
				"startup": "team-reveal-with-roles", "teamTalk": true, "preventTeamvote": true,
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": -2,"common": "Self","silent": true, "silentCopy": true, "limit": 1,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun4","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": -2,"common": "Self","silent": true, "silentConvert": true, "limit": 1, "recharge": 2,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield4","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand5",
            "translation": "Gray Hand [5]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 5HP!",
            "actions": { "inspect": { "revealAs": [ "5" ] }, "vote": 2,
				"startup": "team-reveal-with-roles", "teamTalk": true, "preventTeamvote": true,
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": -2,"common": "Self","silent": true, "silentCopy": true,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun5","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": -2,"common": "Self","silent": true, "silentConvert": true, "recharge": 2,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield5","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand5x",
            "translation": "Gray Hand [5]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 5HP!",
            "actions": { "inspect": { "revealAs": [ "5" ] }, "vote": 2,
				"startup": "team-reveal-with-roles", "teamTalk": true, "preventTeamvote": true,
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": -2,"common": "Self","silent": true, "silentCopy": true, "limit": 1,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun5","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": -2,"common": "Self","silent": true, "silentConvert": true, "limit": 1, "recharge": 2,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield5","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand6",
            "translation": "Gray Hand [6]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 6HP!",
            "actions": { "inspect": { "revealAs": [ "6" ] }, "vote": 2,
				"startup": "team-reveal-with-roles", "teamTalk": true, "preventTeamvote": true,
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": -2,"common": "Self","silent": true, "silentCopy": true,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun6","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": -2,"common": "Self","silent": true, "silentConvert": true, "recharge": 2,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield6","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand6x",
            "translation": "Gray Hand [6]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 6HP!",
            "actions": { "inspect": { "revealAs": [ "6" ] }, "vote": 2,
				"startup": "team-reveal-with-roles", "teamTalk": true, "preventTeamvote": true,
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": -2,"common": "Self","silent": true, "silentCopy": true, "limit": 1,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun6","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": -2,"common": "Self","silent": true, "silentConvert": true, "limit": 1, "recharge": 2,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield6","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand7",
            "translation": "Gray Hand [7]",
			"help": "variable:vvhand help",
            "hide": true,
            "info": "variable:hand info",
            "side": "voodoo",
            "help2": "You have 7HP!",
            "actions": { "inspect": { "revealAs": [ "7" ] }, "vote": 2,
						"startup": "team-reveal-with-roles", "teamTalk": true, "preventTeamvote": true,
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {
					"hide": true,"command": [ "copy" ], "priority": -2,"common": "Self","silent": true, "silentCopy": true,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun7","cancel": [ "shield" ]
                    },
                    "shield": {
					"hide": true,"command": [ "convert" ],"priority": -2,"common": "Self","silent": true, "silentConvert": true, "recharge": 2,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield7","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvhand7x",
            "translation": "Gray Hand [7]",
			"help": "variable:vvhand help",
			"hide": true,
            "info": "variable:vvhand info",
            "side": "voodoo",
            "help2": "You have 7HP!",
            "actions": { "inspect": { "revealAs": [ "7" ] }, "vote": 2,
						"startup": "team-reveal-with-roles", "teamTalk": true, "preventTeamvote": true,
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": {
                    "gun": {"command": [ "copy" ], "hide": true, "priority": -2,"common": "Self","silent": true, "silentCopy": true, "limit": 1,
					"broadcast": "team","target": "AnyButTeam","canCopy": "*","copyfailmsg": "","copyAs": "vvgun7","cancel": [ "shield" ]
                    },
                    "shield": {"command": [ "convert" ], "hide": true, "priority": -2,"common": "Self","silent": true, "silentConvert": true, "limit": 1, "recharge": 2,
					"broadcast": "team","target": "OnlySelf","newRole": "vvshield7","cancel": [ "gun" ]
                    }
                }
            }
        },
        {   "role": "vvshield0",
            "translation": "Gray Shield",
			"help": "variable:shield help",
            "hide": true,
            "info": "variable:shield info",
            "side": "voodoo",
            "help2": "You have 0HP!",
            "actions": { "inspect": { "revealAs": [ "0" ] },
				"preventTeamvote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "vvhand0",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"}
            }
        },
        {   "role": "vvshield1",
            "translation": "Gray Shield",
			"help": "variable:shield help",
            "hide": true,
            "info": "variable:shield info",
            "side": "voodoo",
            "help2": "You have 1HP!",
            "actions": { "inspect": { "revealAs": [ "1" ] },
				"preventTeamvote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "vvhand1",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"}
            }
        },
        {   "role": "vvshield2",
            "translation": "Gray Shield",
			"help": "variable:shield help",
            "hide": true,
            "info": "variable:shield info",
            "side": "voodoo",
            "help2": "You have 2HP!",
            "actions": { "inspect": { "revealAs": [ "2" ] },
				"preventTeamvote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "vvhand2",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"}
            }
        },
        {   "role": "vvshield3",
            "translation": "Gray Shield",
			"help": "variable:shield help",
            "hide": true,
            "info": "variable:shield info",
            "side": "voodoo",
            "help2": "You have 3HP!",
            "actions": { "inspect": { "revealAs": [ "3" ] },
				"preventTeamvote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "vvhand3",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"}
            }
        },
        {   "role": "vvshield4",
            "translation": "Gray Shield",
			"help": "variable:shield help",
            "hide": true,
            "info": "variable:shield info",
            "side": "voodoo",
            "help2": "You have 4HP!",
            "actions": { "inspect": { "revealAs": [ "4" ] },
				"preventTeamvote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "vvhand4",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"}
            }
        },
        {   "role": "vvshield5",
            "translation": "Gray Shield",
			"help": "variable:shield help",
            "hide": true,
            "info": "variable:shield info",
            "side": "voodoo",
            "help2": "You have 5HP!",
            "actions": { "inspect": { "revealAs": [ "5" ] },
				"preventTeamvote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "vvhand5",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"}
            }
        },
        {   "role": "vvshield6",
            "translation": "Gray Shield",
			"help": "variable:shield help",
            "hide": true,
            "info": "variable:shield info",
            "side": "voodoo",
            "help2": "You have 6HP!",
            "actions": { "inspect": { "revealAs": [ "6" ] },
				"preventTeamvote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "vvhand6",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"}
            }
        },
        {   "role": "vvshield7",
            "translation": "Gray Shield",
			"help": "variable:shield help",
            "hide": true,
            "info": "variable:shield info",
            "side": "voodoo",
            "help2": "You have 7HP!",
            "actions": { "inspect": { "revealAs": [ "7" ] },
				"preventTeamvote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "vvhand7",
                        "curseCount": 1
                    }
                },
						"dummy": { "silent": true,"mode": "ignore"},
						"dummy2": { "silent": true,"mode": "ignore"},
						"dummy3": { "silent": true,"mode": "ignore"},
						"dummy4": { "silent": true,"mode": "ignore"},
						"dummy5": { "silent": true,"mode": "ignore"},
						"dummy6": { "silent": true,"mode": "ignore"}
            }
        },
        {   "role": "vvgun0",
            "translation": "[0]",
			"help": "variable:gun help",
            "hide": true,
            "info": "variable:gun info",
            "side": "voodoo",
            "help2": "You have 0HP!",
            "actions": { "inspect": { "revealAs": [ "0" ] },
				"preventTeamvote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "vvhand0",
                        "curseCount": 1
                    }
                },
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": "variable:gun attack"
            }
        },
        {   "role": "vvgun1",
            "translation": "[1]",
			"help": "variable:gun help",
            "hide": true,
            "info": "variable:gun info",
            "side": "voodoo",
            "help2": "You have 1HP!",
            "actions": { "inspect": { "revealAs": [ "1" ] },
				"preventTeamvote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "vvhand1",
                        "curseCount": 1
                    }
                },
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": "variable:gun attack"
            }
        },
        {   "role": "vvgun2",
            "translation": "[2]",
			"help": "variable:gun help",
            "hide": true,
            "info": "variable:gun info",
            "side": "voodoo",
            "help2": "You have 2HP!",
            "actions": { "inspect": { "revealAs": [ "2" ] },
				"preventTeamvote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "vvhand2",
                        "curseCount": 1
                    }
                },
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": "variable:gun attack"
            }
        },
        {   "role": "vvgun3",
            "translation": "[3]",
			"help": "variable:gun help",
            "hide": true,
            "info": "variable:gun info",
            "side": "voodoo",
            "help2": "You have 3HP!",
            "actions": { "inspect": { "revealAs": [ "3" ] },
				"preventTeamvote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "vvhand3",
                        "curseCount": 1
                    }
                },
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": "variable:gun attack"
            }
        },
        {   "role": "vvgun4",
            "translation": "[4]",
			"help": "variable:gun help",
            "hide": true,
            "info": "variable:gun info",
            "side": "voodoo",
            "help2": "You have 4HP!",
            "actions": { "inspect": { "revealAs": [ "4" ] },
				"preventTeamvote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "vvhand4",
                        "curseCount": 1
                    }
                },
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": "variable:gun attack"
            }
        },
        {   "role": "vvgun5",
            "translation": "[5]",
			"help": "variable:gun help",
            "hide": true,
            "info": "variable:gun info",
            "side": "voodoo",
            "help2": "You have 5HP!",
            "actions": { "inspect": { "revealAs": [ "5" ] },
				"preventTeamvote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "vvhand5",
                        "curseCount": 1
                    }
                },
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": "variable:gun attack"
            }
        },
        {   "role": "vvgun6",
            "translation": "[6]",
			"help": "variable:gun help",
            "hide": true,
            "info": "variable:gun info",
            "side": "voodoo",
            "help2": "You have 6HP!",
            "actions": { "inspect": { "revealAs": [ "6" ] },
				"preventTeamvote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "vvhand6",
                        "curseCount": 1
                    }
                },
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": "variable:gun attack"
            }
        },
        {   "role": "vvgun7",
            "translation": "[7]",
			"help": "variable:gun help",
            "hide": true,
            "info": "variable:gun info",
            "side": "voodoo",
            "help2": "You have 7HP!",
            "actions": { "inspect": { "revealAs": [ "7" ] },
				"preventTeamvote": true,
                "initialCondition": {
                    "curse": { "silentCurse": true,
                        "cursedRole": "vvhand7",
                        "curseCount": 1
                    }
                },
				"dummy": { "silent": true,"mode": "ignore"},"dummy3": { "silent": true,"mode": "ignore"},"dummy5": { "silent": true,"mode": "ignore"},
                "night": "variable:gun attack"
            }
        },
        {   "role": "0",
            "translation": "[0]",
			"help": "THIS IS ONLY A DUMMY ROLE, NOTHING TO LOOK HERE.",
            "hide": true,
            "info": "This is only a dummy role, nothing to look here",
            "side": "green",
            "actions": {}
		},
        {   "role": "1",
            "translation": "[1]",
			"help": "THIS IS ONLY A DUMMY ROLE, NOTHING TO LOOK HERE.",
            "hide": true,
            "info": "This is only a dummy role, nothing to look here",
            "side": "green",
            "actions": {}
		},
        {   "role": "2",
            "translation": "[2]",
			"help": "THIS IS ONLY A DUMMY ROLE, NOTHING TO LOOK HERE.",
            "hide": true,
            "info": "This is only a dummy role, nothing to look here",
            "side": "green",
            "actions": {}
		},
        {   "role": "3",
            "translation": "[3]",
			"help": "THIS IS ONLY A DUMMY ROLE, NOTHING TO LOOK HERE.",
            "hide": true,
            "info": "This is only a dummy role, nothing to look here",
            "side": "green",
            "actions": {}
		},
        {   "role": "4",
            "translation": "[4]",
			"help": "THIS IS ONLY A DUMMY ROLE, NOTHING TO LOOK HERE.",
            "hide": true,
            "info": "This is only a dummy role, nothing to look here",
            "side": "green",
            "actions": {}
		},
        {   "role": "5",
            "translation": "[5]",
			"help": "THIS IS ONLY A DUMMY ROLE, NOTHING TO LOOK HERE.",
            "hide": true,
            "info": "This is only a dummy role, nothing to look here",
            "side": "green",
            "actions": {}
		},
        {   "role": "6",
            "translation": "[6]",
			"help": "THIS IS ONLY A DUMMY ROLE, NOTHING TO LOOK HERE.",
            "hide": true,
            "info": "This is only a dummy role, nothing to look here",
            "side": "green",
            "actions": {}
		},
        {   "role": "7",
            "translation": "[7]",
			"help": "THIS IS ONLY A DUMMY ROLE, NOTHING TO LOOK HERE.",
            "hide": true,
            "info": "This is only a dummy role, nothing to look here",
            "side": "green",
            "actions": {}
		},
        {   "role": "hand",
            "translation": "Coloured Hand",
			"hide": true,
			"help": "variable:vvhand help",
            "info": "variable:vvhand info",
            "side": "voodoo",
            "actions": {
                "night": {
                    "Rock, Paper or Scissor": {"command": [ "dummy" ], "priority": 2,"common": "Self", "broadcast": "team","target": "AnyButTeam"
                    }
                }
            }
        }
    ],
    "roles1": [
        "redhand4x",
        "bluehand4x",
        "yellowhand4x"
    ],
    "roles2": [
        "redhand4x",
        "bluehand4x",
        "redhand4x",
        "bluehand4x"
    ],
    "roles3": [
        "greenhand4x",
		"greenhand4x",
        "greenhand4x",
        "violethand4x",
		"violethand4x"
    ],
    "roles4": [
        "greenhand4x",
		"greenhand4x",
        "emeraldhand5x",
        "violethand6x",
        "violethand6x",
		"greenhand4x",
		"vvhand5x"
    ],
    "roles5": [
        "emeraldhand6x",
		"greenhand4x",
        "greenhand4x",
		"greenhand4x",
        "violethand5x",
        "violethand5x",
		"vvhand5x",
		"greenhand4x"
    ],
    "roles6": [
        "emeraldhand7x",
		"greenhand4x",
        "greenhand4x",
		"greenhand4x",
		"greenhand4x",
        "violethand5x",
        "violethand5x",
		"violethand5x",
		"vvhand4x"
    ],
    "roles7": [
        "emeraldhand6x",
        "greenhand4x",
		"greenhand4x",
        "greenhand4x",
		"greenhand4x",
		"greenhand4x",
        "violethand5x",
        "violethand5x",
		"violethand5x",
		"vvhand7x"
    ],
    "roles8": [
        "emeraldhand7x",
        "greenhand4x",
		"greenhand4x",
        "greenhand4x",
		"greenhand4x",
		"greenhand4x",
        "violethand5x",
        "violethand5x",
		"violethand5x",
		"vvhand3x",
		"vvhand3x",
		"greenhand4x"
    ],
    "roles9": [
        "rwhand4",
		"swhand4",
		"owhand4",
		"ywhand4",
        "bchand4",
        "gchand4",
		"pchand4",
		"mchand4",
		"cohand4",
		"bohand4",
		"gohand4",
		"sohand4",
		"vvhand7x"
    ],
    "changelog": {
        "February 2014": "Theme created.",
		"May 2014": "Added village vs. mafia setup with Green and Violet Hands",
		"May 2014 part 2": "Added Emerald hand as Day inspector for Green Team",
		"May 2014 part 3": "Cut down the Curse texts to make the theme less full of messages"
    }
}

