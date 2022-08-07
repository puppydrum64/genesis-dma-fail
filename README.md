# genesis-dma-fail
Test ROM for scanline color DMA, trying to debug
Essentially the only difference between the two is that the VDP registers are either written to by using commands read from ROM or RAM.
For some reason the DMA only takes place if the commands are read from RAM (or are immediate constants), and I don't understand why.
I want to see if that happens on real hardware as well.
