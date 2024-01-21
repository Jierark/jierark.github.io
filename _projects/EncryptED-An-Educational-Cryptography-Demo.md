---
layout: project
---

This was my final project in 6.111/6.2050 Digital Systems Laboratory. The premise was to find something to implement on an FPGA, and given my interests, I decided to go with something security related. This resulted in an attempt to implement RSA-128 on an FPGA, with the goal of being able to send messages back and forth between two FPGAs without a third party being able to read the contents. Sounded simple enough, but oh boy was it ever difficult...

[Link to github repository](https://github.com/Jierark/EncryptED)

I think with some more time, we would have met our bare bone goals of being able to encrypt and decrypt messages. It's just that there were SO many problems that we ran into, coupled with the fact that I got sick in the last three weeks of classes, which threw all our timing out of the window. Also, working in verilog was quite the task because there's so many things that we take for granted when using a regular programming language like python. 

The biggest problems for me were trying to minimize area and working out logic for different modules. We initially came into the project hoping to implement RSA-512, but due to our implementations, we couldn't even get a bitmap to synthesize in the first place; thus, we scaled everything down to RSA-128. Looking back, we really should have looked for hardware algorithms that focused on area over speed, but looking for implementations was very difficult.

Overall, while it wasn't exactly successful, I did learn a lot about the RSA cryptosystem and about working with hardware description languages. Pretty fun too.