# JTAG_Needle
# !!!WORK IN PROGRESS!!!
Needle connectors for flashing/debugging hardware via JTAG become more and more popular last years.
But not as much the needle connectors themsleves as the corresponding "zero connector" footprint.
The footprint used as a flashing/debugging connector is beloved by managers as it looks like some cost optimizing move, but also by engineers as you can have one component implemented in layout itself and it is tech fun. 
So many people like them, I use them too. What nobody likes, though, is the price of needle adapters. It is a bit reduced through the last few years and you can find it on Digikey or Mouser for about 80$ or so but it is still a lot. For companies it may be not much, still developers tend to lose small things and bring them home so from my observations there are never enough of those adapters. And when individuals bring that footprint to their own projects - the price becomes unreachable, often beating the total price of designed target device.
I heard from nearly anyone facing that problem (using those connectors) that someone has to design an open source needle adapter to make it affordable for wast majority of makers. I waited for a few years but that didn't appear (or I didn't see it at least). So, having a few spare hours I decided to try to solve that problem. 
This repo contains my attempt to make a low-cost open source needle adapter for JTAG.
