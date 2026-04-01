this is my custom 11 key macropad using a seeed xiao rp2040. i built it mostly because i wanted something actually useful on my desk instead of just buying one.

it’s got a rotary encoder for volume, a small oled screen, and a 3x4 matrix for the buttons. it’s mainly set up for daily stuff so i don’t have to keep tabbing around all the time.

right now it can:

open firefox, spotify, discord
control volume with the knob
mute/unmute my mic
toggle vpn
run a timer that shows how long i’ve been working
show status on the screen (mic, vpn, timer)
do a small animation when it’s idle

firmware is just circuitpython since it’s easy to change stuff quickly. might switch to qmk later but this works fine for now.

files are split into cad, pcb, firmware, and production so it’s not a mess. pcb is 2 layer and uses a 3x4 matrix with diodes.

future stuff i might add:

better screen ui (icons instead of text)
smoother animations
different modes depending on what i’m doing
proper linux integration instead of basic shortcuts
maybe rgb if i feel like it
