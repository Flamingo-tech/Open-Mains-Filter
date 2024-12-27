[![License: CERN-OHL-S v2.0](https://img.shields.io/badge/License-CERN--OHL--S-blue.svg)](https://ohwr.org/project/cernohl/wikis/Documents/CERN-OHL-version-2)

# Open Mains Filter PCBA

![Preview](https://github.com/Flamingo-tech/Open-Mains-Filter/blob/main/Images/Open_Mains_Filter_V1.1.0_IMG_1.png)

A few years ago, I found myself in a friendly disagreement with Wurth Elektronik. I’ve always been a big fan of their whitepapers and products, and their EMC department has some incredibly knowledgeable people. Naturally, when I needed to design a mains EMC filter, I turned to WE for guidance.

About three years ago, I purchased their design kit and successfully built my first working mains filters. However, when it came time to refill the PCBs in my kit, I hit a snag. WE wouldn’t provide free refills, nor would they allow me to share the Gerber or Altium files to order new boards myself.

That was unfortunate, but it sparked an idea.

I decided to create my own Mains Filter PCBA. This design is freely available, including the Gerber files, so you can order the PCBAs or build your own EMC mains filter at no cost (aside from the PCB itself). The design is specifically tailored for WE components—which, by the way, you can sample for free!

### Let's take a look at the components you can sample for free:

![Preview](https://github.com/Flamingo-tech/Open-Mains-Filter/blob/main/Images/Open_Mains_Filter_V1.1.0_Overview.png)

#### Connectors:  
**J1 & J2:** [691411510003](https://www.we-online.com/en/components/products/TBL_5_08_4115_SCREWLESS_HORIZONTAL_ENTRY_6914115100XX?sq=691411510003#691411510003)  
- Recommended part: 691411510003 from Wurth Electronics.  
- You can also use any 5.08mm spaced THT header/connector.

---

#### Fuse Holder:  
**XF1:** [696103201002](https://www.we-online.com/en/components/products/FSH_THR_PCB_CLIP_COVER_696103201002)  
Optional **Fuse Cover:** [696121101001](https://www.we-online.com/en/components/products/FSH_THT_PCB_CLIP_COVER_696121101001)  

---

#### Varistor:  
**RV:** [WE-VD Series](https://www.we-online.com/en/components/products/WE-VD#/articles/WE-VD_SIZE_5MM)  
- Compatible with all 5mm-width varistors.  
- Larger varistors can fit if you bend the legs.

---

#### Capacitors:  
**Cx:** [WCAP-FTX2 Series](https://www.we-online.com/en/components/products/WCAP-FTX2)  
- Compatible with capacitors in the 7.5mm to 15mm pitch range.  
- Footprints are overlapped to accommodate different sizes, but only one capacitor can be mounted at a time.

**Cy:** [WCAP-CSSA Y-Filter Capacitors](https://www.we-online.com/en/components/products/WCAP-CSSA_2#/articles/WCAP-CSSA-1812_2)  
- Compatible with 2220 and 1812 Y-capacitor sizes.  
- Other sizes may fit with creative soldering.

---

#### Resistor:  
**R:** 1 MΩ Bleeding Resistor  
- Used to discharge Cx when power is off.  
- Technically optional but highly recommended for safety (no "touchy touchy").

---

#### Common Mode Choke (CMC):  
**WE-CMB Series:** [View Options](https://www.we-online.com/en/components/products/WE-CMB?)  
- Compatible with sizes S, M, and L in this range.

---
<a href="https://www.tindie.com/stores/theflamingo/?ref=offsite_badges&utm_source=sellers_TheFlamingo&utm_medium=badges&utm_campaign=badge_large"><img src="https://d2ss6ovg47m0r5.cloudfront.net/badges/tindie-larges.png" alt="I sell on Tindie" width="200" height="104"></a>
---

## License
This project is licensed under the CERN Open Hardware License Strongly Reciprocal (CERN-OHL-S) v2.0.  
For more details, see the [LICENSE](./LICENSE) file or visit the [official CERN-OHL website](https://ohwr.org/cern_ohl).


