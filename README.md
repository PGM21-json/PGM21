# PGM21

JSON is the current base player list within PGM21 beta. This shows the format which should be followed for any custom rosters.

Basic player details

    "iden": "5A251D07-3C9D-4BD1-B511-FD20CA81227C", // You can ignore this. This is generated afresh on import.
    "forename": "Frank",
    "surname": "Jackson",
    "age": 23,
    "position": "DE",
    "teamID": "CHI",
    "draftSeason": 2019,
    "draftNum": 34, // 1-224 (1 = first pick)
    "appearance": [
      "Head4",
      "Eyes2",
      "Hair1Brown",
      "Beard1Brown"
    ],
    // Appearance should follow above format with options as...
    - colorOptions = ["Blonde","Ginger","Brown","Black","Grey","White"] (hair and beard color)
    - headOptions = [1,2,3,4,5,6] (ethnicity from 1 = white to 6 = black) 
    - eyeOptions = [1,2,3] (eye color - blue, green, brown)
    - hairOptions = [1,2,3,4,5,6] (1 = bald, 2,3 = medium, 4 = long, 5/6 = short) // order as per GM selection
    - beardOptions = [1,2,3,4] (1 = none, 2 = short beard, 3 = med beard, 4 = tash)
    
Player potential and development

    "potential": 22, // From 1-30. This represents the TOTAL development over a players career, not just the remaining!
    "growthType": 0, // Represents development distribution (0 = Very early dev (70% Yr1), 1= Mid Dev (45% Yr1), 2 = Late Dev (35% Yr1))
    "rating": 81, // This will be replaced, so you can ignore this
    
These are contracts and/or expectations

    "eLength": 2,
    "length": 2,
    "eSalary": 640860,
    "salary": 640860,
    "guarantee": 1301140,
    "eGuarantee": 1301140,

The following are rating stats (from 40 - 99)

    Physical - All players
    "speed": 54
    "burst": 53,
    "power": 72,
    "agility": 50,
    "jumping": 70,
    "stamina": 0,
    "injuryProne": 89, // 99 is highest likelihood
    
    Mental - All players
    "discipline": 6,
    "intelligence": 89,
    "loyalty": 93,
    "greed": 63,
    "ambition": 32,
    "decisions": 20,
    "vision": 75,
    
    Passing
    "sPassAcc": 0,
    "mPassAcc": 0,
    "dPassAcc": 0,
    "throwOnRun": 0,
    
    Off Skill
    "routeRun": 0,
    "catching": 0,
    "passBlock": 0,
    "rushBlock": 0,
    "ballSecurity": 0,
    "trucking": 0,
    "kickAccuracy": 0,
    
    Defence Skill
    "zoneCover": 0,
    "manCover": 0,
    "blockShedding": 94,
    "ballStrip": 74,
    "tackle": 50,
    
    Both
    "elusiveness": 0,
    "releaseLine": 91,
    "skillMove": 50,
