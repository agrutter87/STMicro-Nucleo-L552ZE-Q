# STMicro-Nucleo-L552ZE-Q
 
Day 1, 7/22/2019:
I received a board which was brought into work for a demo for a customer. 
After the demo was completed, I received the board to bring home or shelf.
I do a little bit with Renesas' and NXP's 32-bit Arm core-based processors already, so I decided to bring it home and take a look at it to see how ST's entire onboarding process compares.

I've learned that the first thing you do when you are looking at new hardware is to find and save away its documentation.
Sure enough, I was able to use the label on the board to find a product page through a quick Google search.
From here I learned that this board is still in the design stage by noticing the Preview note.
I was able to download a product Data Brief which told me some more information I need to find the real documentation.

Nucleo-L552ZE-Q Product Page:
https://www.st.com/content/st_com/en/products/evaluation-tools/product-evaluation-tools/mcu-mpu-eval-tools/stm32-mcu-mpu-eval-tools/stm32-nucleo-boards/nucleo-l552ze-q.html
Relevant Downloads:
Product Brief - nucleo-l552ze-q.pdf

I was able to find the page for the microcontroller by looking in the product Data Brief on the product page.
The medium sized datasheet is on this page, but I still want the much larger one. 
After some searching, I found it on the following page's "Resources" tab under "Reference Manuals".
There's a lot of other super-useful stuff here, but I'll wait and download it when necessary.

STM32L552ZE:
https://www.st.com/en/microcontrollers-microprocessors/stm32l552ze.html
Relevant Downloads:
Product Brief - stm32l552ze.pdf
Reference Manual - en.DM00346336.pdf

STM32CubeIDE:
After doing some digging in the multitude of IDEs that ST is involved with, it looks like the STM32CubeIDE is the latest IDE that STMicro is pushing for its STM32 line. 
I'll try this out first because it looks familiar to the Eclipse environment I'm used to with the Renesas Synergy platform.
I only worry that it isn't ready yet because all the documentation that I've peeked into doesn't mention the Cube IDE yet.
It will be easy enough to find out when I install it, though, so no big deal.
https://my.st.com/content/my_st_com/en/products/development-tools/software-development-tools/stm32-software-development-tools/stm32-ides/stm32cubeide.html

STM32CubeMX:
This looks like a standalone code generator. This may not be needed if I'm using the STM32CubeIDE. We'll see.
https://my.st.com/content/my_st_com/en/products/development-tools/software-development-tools/stm32-software-development-tools/stm32-configurators-and-code-generators/stm32cubemx.html