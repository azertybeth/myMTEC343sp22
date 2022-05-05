solo set documentation



slow 4 $ n "1*4 ~  2 ~ 3 ~ 1" # s "flbass"

stack [
n "2 3 {2 8} ~ ~" # s "sid",
every 3 (rev) $ n "2 3 {2 8} ~ ~" # s "sid",
every 4 (fast 5) $ n "0 0" # s "sid"
]

slow 2 $ n "1*2 ~  7 [2*7 | 2*5| 2] 3 ~ 1" # s "bubble" # gain 2

n "0*30 2 0*77 4 9*20 2 2 2 4" # s "gab" # gain 0.7 # pan sine

n "0 2 0 4 9 4" # s "juno"

fast 20 $ n "5 8 5 {8 [7*5 | 7 7*2 7]}?" # s "jungle"

fast 2 $ s "[bd | bd sd | bd bd] [hh | hh hh | hh*2 hh] bd [hh | {sd ~} sd]" # gain 1.5

n "1*49 2*33 9 4*66" # s "jungbass" # gain 2

n "1 4 2 3" # s "future" # gain 2

slow 4 $ n "1 4 2 3" # s "led" # gain 1.25

n "1 2 4 6 2 5 3 4" # s "sid" # gain 1.5

n "5 5 5 5*16" # s "sid" # gain 2

n "5*16 5 5 [5 | 5 {5 5}]" # s "sid" # gain 2

n "9 8" # s "uxay" # gain 2

n "9 8" # s "ul" # gain 1

n "9 8 2 1 8 5 4 2" # s "sf" # gain 1.5

n "d d d a a" # s "bass3" # gain 1.6

stack [
n "a" # s "moog" # gain 1.6,
n "e e e" # s "juno" # gain 1.5
]

stack [
n (arp "updown" "<a'min7>") # s "juno" # pan sine # gain 0,
slow 2 $ n (arp "up" "<a'min7>") # s "juno" # pan 1 # gain 0,
fast 2 $ n (arp "down" "<a'min7>") # s "juno" # pan 0 # gain 0,
fast 2 $ n (arp "down" "<a'min>") # s "moog" # gain 0
]
