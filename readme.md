

# My Maker Projects

3) [Chamrousse Mountains](#3---chamrousse-mountain)
![alt text](<03 - Chamrousse Mountains/Blender Mountain Model.png>)
2) [Caterpie with Chain](#2---caterpie-chain)
![alt text](<02 - Caterpie/Painted Caterpie.jpg>)
3) [NULSCC Keychain](#1---nulscc-keyring)
![alt text](<01 - NULSCC/NULSCC Keychain.png>)

## 3 - Chamrousse Mountain

![Chamrousse Blender Model](<03 - Chamrousse Mountains/Blender Mountain Model.png>)

LIDAR data coverage of the France is extremely good, with 10 points per meter. However, directly downloading the data for the Chamrousse area would have been over 10GB, and I couldn't find any DSM data to directly get a 3D model. 

I thus went to online premade tools, and found [TerraPrinter](https://terraprinter.com/) very good to use.

However, I then had to deal with manipulating a highly detailed model, which I don't have experience with in Blender. This made even cutting the region down for print times difficult, as boolean subtract failed me, and bisect cuts lead to gaping open faces.

![Blender - Gaps](<03 - Chamrousse Mountains/Blender - Gaps.png>)

With the lab nearing close time, all I could do in the end was cut it down to size.

![Cura - Gyroid fill](<03 - Chamrousse Mountains/Cura - Gyroid.png>)

I also used gyroid fill for the first time, which should help reduce warping, increase strength, and reduce material. 

Once I get my head around manipulating detailed models, I'd love to turn this into a portable travel map.

## 2 - Caterpie Chain

To test out the chain join, most prominently used in 3D dragons, I made a lil' caterpie (or "Chenipan" in french)

![Caterpie - Blender](<02 - Caterpie/Caterpie - Blender.png>)

The chains can be seen here. For a first attempt, I didn't try to hide the chains at all. They all printed fine, except the second-to-last smallest chain. The printing resolution caused the chains to merge, and the chain completely broke when I tried crimping the support off.

![Caterpie Blender Chains](<02 - Caterpie/Caterpie - Blender - Chains.png>)

I also used tree supports for the first time! 

![Caterpie in Cura with supports](<02 - Caterpie/Caterpie - Cura.png>)

![Unpainted Caterpie](<02 - Caterpie/Unpainted Caterpie.jpg>)

![Painted Caterpie](<02 - Caterpie/Painted Caterpie.jpg>)

Not a bad final result!

The chains move, but not as freely as I like. If I were to make a second attempt, I'd improve the body shape to cover over the chain, and also leave more space inside the chains. Mixing blocky chains and torus chains may also lead to better results.

# 1 - NULSCC Keyring

My first ever 3D print! I'm not skilled enough in Blender yet to make any organic shape, like the speed climbing holds, so I instead made the shape 2D with bézier curves.

Attempts were made concurrently with two different printing resolutions. The larger nozzel unfortunately didn't work well, with the model becoming damaged once the supports were taken off. The gray printed well, except for the user-error of taking it off the plate too early, where you can see it melted slightly.

![NULSCC keyring in blender](<01 - NULSCC/NULSCC - Blender.png>)

![Printed Keychain](<01 - NULSCC/NULSCC Keychain.png>)
