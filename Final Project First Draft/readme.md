# Brief

This composition will consist of two systems: ***Compositional Roles***
and a ***Mood Diagram***; all of the former roles adhere to the
latter diagram.

# Compositional Roles
### are divided into six categories (in accordance with the number of performance fields in Estuary).
Each role may be shared by multiple players, however: **all roles
must be occupied by at least one player.**

For ease of intuitiveness, roles will be called by common
contemporary musical vernacular or will be relatively self-
explanatory.

Each role will have a designated choice of patches and samples to
play with.

The intensity/aggression of the patch will be marked in parenthesis next to the
patch name on a scale of 1 to 5.


## Lead

"pluck" (1)
"hoover" (5)
"newnotes" (1)


n "0 2 0 4 9 4" # s "newnotes"

stack [
n "2 3 {2 8} ~ ~" # s "pluck",
every 3 (rev) $ n "2 3 {2 8} ~ ~" # s "pluck",
every 4 (fast 5) $ n "0 0" # s "pluck"
]



## Support Layer A

"arpy" (2)
"jvbass" (1)


## Support Layer B

"blip" (2)
"notes" (1)
"flbass" (1)

n "1*4 ~  2 ~ 3 ~ 1" # s "flbass"

## Percussion Layer A

"peri" (2)
"reverbkick" (5)

## Percussion Layer B

"jazz" (1)
"glasstap" (1)
"bubble" (1)
"casio" (2)
"808bd" (3)
"808sd" (3)


n "1*2 ~  7 [2*7 | 2*5| 2] 3 ~ 1" # s "bubble" # gain 2

stack [
n "1*2 ~  7 [2*7 | 2*5| 2] 3 ~ 1" # s "bubble",
n "6 ~ ~ ~ 6 ~ ~ " # s "808bd",
n "~ ~ 4 ~ ~ 5 ~" # s "808sd",
n "~ 1 ~ 2 ~ ~ 2" # s "casio"
]

## Texture/Ambience

"yeah"
"tink"
"wind"
