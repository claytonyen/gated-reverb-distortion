# Gated Reverb Distortion
Mk.gee's electric guitar tone has gained popularity in recent years and I seek to emulate it. Many would say that Mk.gee's music generally falls under the "dream pop" genre, mixed with dark, liminal atmosphere. An integral part of his tone is the Rainger FX Reverb X pedal (which from now on I will refer to it as RRP), a gated reverb and distortion pedal that serves to create gigantic swells and ringing. 

## Gate
The gate of the RRP does not have much customization. While you can adjust the threshold that it opens, you can not alter the gate attack, release, or the sudden closing of the gate (although this built in feature is what gives the pedal its iconic sound). Since my intention is to make this pedal as customizable as possible, there will be potentiometers and a switch to change these settings.

The RRP has a gate toggle that can switch between before and after the distortion and reverb effects, which is something to keep in mind when implementing the gate. 

## Distortion


## Reverb
The RRP uses a Spin Semiconductor FV-1 IC for its reverb. However, I want to challenge myself and try to make a reverb with part I already have: the PT2399! This is the chip I used in my chorus pedal so I already have a few in my arsenal, which is why I'm going to try to make a reverb using them. A single PT2399 alone is not enough to get a good reverb sound, so I am using two chips with different delay times and feedback. 
