# PGM21

JSON is the current base player list within PGM21 beta. This shows the format which should be followed for any custom rosters.

Basic player details
    "iden": "5A251D07-3C9D-4BD1-B511-FD20CA81227C",
    "forename": "Frank",
    "surname": "Jackson",
    "age": 23,
    "position": "DE",
    "teamID": "CHI",
    "draftSeason": 2019,
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
    "zoneCover": 0,
    "catching": 0,
    "mPassAcc": 0,
    "agility": 50,
    "discipline": 6,
    "throwOnRun": 0,
    "passBlock": 0,
    "rushBlock": 0,
    "releaseLine": 91,
    "injuryProne": 89, // 99 is highest likelihood
    "dPassAcc": 0,
    "stamina": 0,
    "intelligence": 89,
    "jumping": 70,
    "routeRun": 0,
    "loyalty": 93,
    "power": 72,
    "sPassAcc": 0,
    "ambition": 32,
    "ballSecurity": 0,
    "blockShedding": 94,
    "greed": 63,
    "draftNum": 34,
    "trucking": 0,
    "tackle": 50,
    "decisions": 20,
    "kickAccuracy": 0,
    "ballStrip": 74,
    "elusiveness": 0,
    "skillMove": 50,
    "manCover": 0,
    "burst": 53,
    "vision": 75,
    "speed": 54
