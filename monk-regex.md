Credits: https://www.youtube.com/@CrimsonCasts

Act-by-Act Regex Building Blocks
Idea: you can glue together these blocks for your build
Some of these, like Resistances, are universally desirable.
Some of these, like attack or caster mods, are more specific.
Some of these, like *projectile attack* mods, are *much* more specific.
 
ONLY COPY THE PARTS IN THE QUOTES, THE REST IS JUST NOTES
 
Attack Mods:
 
"give me any flat damage" -> "o att"
Act 1: "nish|ulde|hilled|zzi" <- This works at lvl 8+
Act 2: "wick|poli|smok|infu|ppi" <- Lvl 16
Act 3: "honed|burning|frigid|crackling|vicious|empowering" <- lvl 33
Act 4: "unleashed|gleaming|flaming|freezing|sparking|bloodthirsty" <- Lvl 46
 
Melee Skills:
"combat" <- Level 1
"dueling" <- Level 18
"conflict" <- Level 36
 
Movement Speed:
Act 1: "vem" <- Catches all ms%
Act 2:"nter's" <-Level 16 (15%)
Act 3: "llion's" <- Level 33 (20%)
Act 4: "zelle's" <- Level 46 (25%)
 
Life:
Act 1: "hale|healthy"
Act 2: "sanguine|stalwart"
Act 3: "stout|robust"
Act 4: "rotund"
 
Resistances: [YOU SHOULD INCLUDE LOWER TIERS HERE IF YOU WANT TO BE SURE OF GOOD RESISTANCES - e.g. add the act 2 ones to your act 3 regex!]
Act 1: Don't need resistances, just keep moving
Act 2: "rak|torm|rwh" <- These work at level 24+, they are 16-20% rolls
Act 3: "kiln|derhe|yeti|nishme" <- These work at level 36+, they are 21-15% rolls
Act 4: "evicti|tempe|walru|furnace" <- These work at level 48+, they are 26-30% rolls
 
 
Flat Defenses:
Armour:
Act 1: "lacquered|studded"
Act 2: "ibbe|tifi"
Act 3: "plated"
Act 4: "rapaced"
 
Energy Shield:
Act 1: "shining|glimmering"
Act 2: "glittering|glowing"
Act 3: "radiating"
Act 4: "pulsing"
 
Evasion:
Act 1: "agile|dancer's"
Act 2: "acrobat's|fleet"
Act 3: "blurred"
Act 4: "phased"
 
Armour/Evasion:
Act 1: "supple"
Act 2: "pliant"
Act 3: "flexible"
Act 4: "durable"
 
Evasion/Energy Shield:
Act 1: "o-wisp's"
Act 2: "nymph's"
Act 3: "sylph's
Act 4: "cherub's"
 
Armour/Energy Shield:
Act 1: "blessed"
Act 2: "anointed"
Act 3: "sanctified"
Act 4: "hallowed"

Act 1:
"!(uiv)" "o att|combat|vem|nish|ulde|hilled|zzi|lacquered|studded|blessed|hale|healthy"
Act 2:
"!(uiv)" "wick|poli|smok|infu|ppi|combat|dueling|vem|sanguine|stalwart|rak|torm|rwh|acrobat's|fleet|nymph's"
Act 3:
"!(uiv)" "honed|burning|frigid|crackling|vicious|empowering|dueling|conflict|llion's|stout|robust|rak|torm|rwh|kiln|derhe|yeti|nishme|sylph's"
Act 4:
"!(uiv)" "unleashed|gleaming|flaming|freezing|sparking|bloodthirsty|duelling|conflict|zelle's|rotund|rak|torm|rwh|kiln|derhe|yeti|nishme|evicti|tempe|walru|furnace|cherub's"

