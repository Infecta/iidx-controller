# Building

Alright here's what you **need**

# Tools

| Tool Name | Notes |
|---|---|
| Laser Cutter | Own one or find a service(like me) |
| Drill | Nothing special a battery powered one will be good |
| Tapping Bits | **M3** Size; Either [this](https://github.com/Infecta/iidx-controller/blob/main/build-guide/resources/tapping-var1.jpg) or [this one](https://github.com/Infecta/iidx-controller/blob/main/build-guide/resources/tapping-var-2.jpg)
| Countersink Bits | A set of [these](https://github.com/Infecta/iidx-controller/blob/main/build-guide/resources/countersink.png) would do just fine<br>**NOTE**: Use your own judgement when using these.<br>aka. make sure it's the right size |
| A screwdriver | One with different bits will really help |
| [Strap clamp](https://www.amazon.com/Bessey-VAS-23-2K-Vario-Angle/dp/B00NO6XHZC/ref=zg_bs_553168_sccl_1/141-0972143-9302916?psc=1) | For holding the case pieces together while you glue
| Crimping tool | For the jumper wires |

# Case Parts List

| Part name | Quantity | Note |
|---|---|---|
|Acrylic laser cuts from this Repo| 1 set | From the CAD folder in this repo (in DXF)<br>Acrylic thickness is 5mm
| Acrylic Glue | - | Not sure about the specific amount<br>Be sure to have a brush to apply
| Hex standoffs | 4pc | This is for mounting the **Arduino Leo**<br>**Size:** M3<br>**Length:** 15mm
| **M6** Screws and Nut | 4pc | For mounting the TT Panels together |
| **M5** Screw and Nut | 4pc | For Mounting the Key panel |
| **M4** Screws | 4pc | For Mounting the TT itself
| **M3** screws | 8pc | For mounting the Arduino and Encoder |
| Feet | 4pc | Something with an **M6** shaft and won't slip |
| Vinyl wrap | - | **PURELY OPTIONAL** I listed it here because<br>My laser cutting services do not offer anything other<br>than clear acrylic |

It's okay to have extra :p

# Other Core Parts

| Part Name | Note |
| --- | --- |
| Arduino Leonardo | Clones work too; But this is going to revolve<br>around the original |
| Dupont Jumper wires and Crimps | You are required to know how to crimp wires<br> [Crimp sizes](https://i.imgur.com/QQwPejp.jpeg)|
| IIDX Rectangle Buttons | Refer to [rhythm-cons.wiki](https://rhythm-cons.wiki/w/Buttons#50x33_mm_Rectangle)
| Small Square Buttons | Refer to [rhythm-cons.wiki](https://rhythm-cons.wiki/w/Buttons#33x33_mm_Square)
| Rotary Encoder | Can be any variation of [this](https://www.amazon.com/Taiss-Incremental-Encoder-Voltage-Warranty%EF%BC%89600P/dp/B07MX1SYXB/ref=sr_1_3?crid=10MVORI8D55RN&keywords=encoder&qid=1668608560&sprefix=encoder+%2Caps%2C506&sr=8-3) because the CAD is designed around it|
| [USB Micro to USB-B Female panel adapter](https://www.amazon.com/CERRXIAN-Female-Extension-Charge-Screws/dp/B07G4XYJ5W/ref=sr_1_4?keywords=usb+micro+to+usb+b+female&qid=1668608795&sprefix=usb+micro+to+usb+b+fe%2Caps%2C417&sr=8-4) | Again; CAD is designed around it

# Actually Building

**NOTE: This only covers how to build and prep the case, please refer to other resources such as the [Cons&Stuff Discord](https://discord.com/invite/fknwz8s) for useful guides**

If you view my CADs you will notice the case itself has different size joints.

This is to ensure it only goes together in **one**, correct way
I've had many mistakes where I accidentally glued together different pieces the wrong way.

However It can also be inverted if you're a P2 gamer

## P1 Layout
Standard Layout

![](https://cdn.discordapp.com/attachments/832618563226304582/1043033475730657310/image.png)

## P2 Layout
Invert the pieces and you're good

![](https://cdn.discordapp.com/attachments/832618563226304582/1043030898410520676/image.png)

Now you've got your pieces all layed out, It's good practice to label them<br>(Label them which side is inside and outside; [Example](https://cdn.discordapp.com/attachments/832618563226304582/1043543022857633802/Labels.jpg))

## Countersinking

The goal of countersinking is to make the screw heads sit flush with the acrylic/wood pieces.

Technically you could get away with not countersinking the holes (except for the TT). But it won't look nice imo.

Here's the holes that should be countersunk(?) labeled green

![](https://cdn.discordapp.com/attachments/832618563226304582/1043545538026549278/Countersink.jpg)

**NOTES:**
- Make sure the top piece (Long Piece *Bottom-Left in the picture* with the USB port hole is countersunk from the outside)

## Tapping/ Making Threads

These (Labeled in blue) should be tapped.

![](https://cdn.discordapp.com/attachments/832618563226304582/1043547726035562576/image.png)

# Gluing

At this point, You should be able to figure out how it all goes together, Especially after being labeled.

I won't go too much into detail other than to tell you to utilize the strap/belt clamp to hold the pieces together and applying the acrylic glue.

Google is your best friend.

You should be able to assemble it without ease from this point on.

# Other Stuff

## Code

I recommend using [Gladuin's iidx-controller](https://github.com/Gladuin/iidx-controller) code because of the GUI configurator.

## Have fun and be a chad.