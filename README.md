# Guidelines on how to use this process agnostic model as described in my PhD thesis - "SIMULATION SOLUTIONS FOR POWER GAN TECHNOLOGIES"
1. Process agnostic version of ASM-GaN model as defined and implemented in chapters 2, 3 and 4 of my thesis is present as the Verilog-A file - asmhemt_power.va.
2. You can use this file alongwith the nmos4.scs and stats_include.scs files in the Cadence ADE environment. In ADE window, please add only nmos4.scs in the Add -> Model Files  
3. Ensure while drawing the FET symbol for AlGaN/GaN HEMT using above files that you use the symbol named - nmos4.
4. You can play with the various model parameters to see how they affect I-V and C-V characteristics in the ICCAP file


