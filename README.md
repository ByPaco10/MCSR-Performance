# MCSR Performance
A comprehensive guide (software and hardware) to get absolute maximum performance out of your PC for Minecraft Speedrunning (2025 rev 1.0)

# Summary
- [Summary](#Summary)
- [Best Price-Performance PC Config](#Best-Price-Performance-PC-Config)
  - [600USDS](#600USDS)
     - [AMD](#AMD-Config)
     - [Intel](#Intel-Config)
  - [1000USDS](#1000USDS)
     - [AMD](#AMD-Config-2)
     - [Intel](#Intel-Config-2)
  - [Microcenter Bundles](#Microcenter-Combos-and-Deals)
 
# Best Price-Performance PC Config

When you want the best performance out of your money usually we look at two CPU platforms, Ryzen 5000 and Intel 12th gen. This is because the motherboards and CPUs are really cheap and Intel 13th and 14th gen have some hard stability concerns. We are targeting both a 1000USD budget and a 600USD budget, in the budget we do not include any peripherals.

We have no fear of recommending second-hand parts using platforms like ebay or jawa or even AliExpress, if you do not live in the United States adjust your platform of choice (For LATAM you can use Mercadolibre and for Spain, Wallapop). Do be wary of sketchy sellers, (Really new accounts, no ratings, bad ratings, too good of a deal...).

When talking about Minecraft Speedrunning hardware configuration we are looking at a few important details on how to configure the build (and some are Linux-specific):
 - Powerful Gen4 m.2 SSD +3500MB/s recommended.
 - Powerful CPU 6 core minimum, 8 recommended. This is the core of the build and will determine the overall performance on resetting.
 - GPU VRAM and performance does **not** matter. We only care about video encoding for streaming.
 - AMD GPU on Linux is recommended if you do not care about good encoding support for streaming and a [bad F3 pie chart](https://youtu.be/cbaUJWzXh18?si=Skky-MPVjeDGD_01). AMD did promise to address encoder problems on RX 9000 series gpus. I'll keep this updated but I would not bet on it.
 - Peripherals **DO** matter do not skimp on them! (High-end is way too much for MCSR, but do not buy a very cheap mouse+keyboard kit, membrane-keyboard, etc).
 - Motherboard usually does not matter. We will not recommend very bad motherboards (H-xxx for intel and A-xxx for AMD) because of the VRM's (Power delivery to the CPU). That can cause catastrophic damage with a high-end CPU.
 - RAM is extremely important for performance on high-core count CPU's. This is even more important while using a chiplet design CPU (like all ryzen 9 CPU's and Intel core Ultra line) If you have a little money to spare you can buy a better RAM kit and it will improve performance a few percentage points.
 - AMD Ryzen line CPU's preffer lower latency over higher RAM speed. While Intel prefers higher RAM speed over lower latency (except core Ultra's). (Latency DOES NOT MEAN CL Rating. Latency is calculated via this formula: CL x 2000/RamSpeed (MHz or MT's) (more on that on [Overclocking](#Overclock).

## 600USDS
### AMD Config:

CPU:
- AMD Ryzen 5 5500.
- AMD Ryzen 7 5700x/5800x (or non-x).
- AMD Ryzen 9 5900x (or non-x).
- AMD Ryzen 9 5950x (If you actually manage to get in budget...).

Depends on your budget. Ryzen 9 is preferred, Ryzen 7 if you can is recommended.

Motherboard: 
- MSI B550M PRO-VDH WiFi (budget, do not pair with ryzen 9). 
- MSI B550 Gaming Plus.
- MSI B550-A PRO.

Any motherboard that does well on [Hardware Unboxed Testing](https://www.youtube.com/watch?v=JxczZChFaZI) (<80C on Ryzen 9 3950x OC) is recommended.

If you get a motherboard that is not a 500 series chipset be wary of the compatibility of your CPU, you can check it [here](https://cpulist.com/am4-cpu-list-all-processors/) and on the motherboard manufacturer site.

Disk:
- Teamgroup MP44 1TB/2TB 7400MB/s (High-end)
- WD Blue SN580 1TB/2TB 4150MB/s (Mid-end).
- WD Blue SN570 1TB/2TB 3500MB/s (Low-end).
- Kingston NV3 1TB/2TB 6000MB/s (High-end).
- Crucial P3 Plus 1TB/2TB 5000MB/s (Mid-end).
- Crucial P3 1TB/2TB 3500MB/s (Low-end).
- Sabrent Rocket 1TB/2TB (Extreme budget).
- WD Green SN350 1TB/2TB (Extreme budget).

While SSD Speed doesn't benefit the performance, it puts a hard-ceiling on it. I recommend a minimum of 3500mb/s. On Ryzen 9 Try to get a Mid-end SSD.

Faxiang and Adata drives are NOT recommended (Quality control issues). As well as samsung 980/990 lineup (You need to update the firmware on these drives).

RAM: 

Any kit will suffice. 16GB DDR4 (2x8GB) absolute minimum only go if you have a really low budget. 32GB DDR4 (2x16GB 3200MHz CL16 DDR4) recommended. Here is a few kits:

- Crucial Pro 3200MHz CL22 2x16gb CP2K16G4DFRA32A (Low-end).
- Corsair Vengeance LPX 3200MHz CL16 2x16 CMK32GX4M2E3200C16 (Mid-end).
- TeamGroup T-FORCE VULCAN Z 3200MHz CL16 2x8 TLZGD416G3200H (Low-end) (Warning: only 16GB).
- G.Skill Ripjaws V DDR4-3200 CL16 2x16 F4-3200C16D-32G (Mid-end).
- TeamGroup T-FORCE Delta RGB DDR4-3200 CL16 2x16 TF4D432G3200HC1 (Mid-end).
- G.Skill Trident Z RGB DDR4-3200 CL16 2x16 F4-3200C16D-32GTZR (Mid-end).
- G.Skill Trident Z Neo Series RGB DDR4-3600 CL16 2x16 F4-3600C16D-32GTZNC (High-end).

Adata kits are not recommended because of their low reliability, that also goes for any offbrand aliexpress kit.

GPU: 
- Nvidia GTX 1650.
- Nvidia GTX 1650 Super.
- Nvidia GTX 1660.
- Nvidia GTX 1660 Super.
- AMD Radeon RX 5600XT.
- Nvidia RTX 2060.
- AMD Radeon RX 5700XT.
- Intel Arc B580.
- Nvidia RTX 3060 12GB.
- AMD Radeon RX 6600XT.
- Nvidia RTX 3060Ti.
- AMD Radeon RX 6700XT.

AMD GPU's have extremely weak encoding support and a [bad F3 pie chart](https://youtu.be/cbaUJWzXh18?si=Skky-MPVjeDGD_01) that make them hard to recommend. Only buy them if you don't mind low-streaming quality and the bad F3 pie chart.

Depends on budget, cards ordered by rasterization performance (Where last is the best) based on [Techpowerup relative performance chart](https://www.techpowerup.com/gpu-specs/geforce-rtx-4090.c3889) and [Hardware Unboxed B580 Overhead Testing](https://youtu.be/00GmwHIJuJY?si=LPrTZA8G5Suzo9vH), if you also want to game on your machine go for higher tiers.

PSU: 
- Tier A:

1st player: NDGP series

Adata: XPG Core Reactor & Cybercore & Fusion series

Aerocool: Project 7

Antec: HCG series

Asrock: Phantom gaming & Taichi series

Asus: (All, except TUF and ROG Strix Platinum 1200w)

be quiet!: Dark Power (all) & Dark Power Pro (all) & Straight Power (all) & Pure Power 11FM/12FM

Bitfenix: BFG Gold ATX 3.0 & Formula Gold & Whisper M

Chieftec: PowerPlay (all) & Atmos

Cooler Master: V-series Vanguard (all Except Gold v1) & X-Silent & XG

Corsair: RM-x 2015-2024 (and shift) series & Corsair RM-i series & SF & TX-m & HX or HX-i & AX or AX-i

Cougar: Polar & GX-F

Deepcool: PQ-M & PX

Enermax: MaxTytan & PlatiGemini & Revolution ATX 3.0 / D.F.

EVGA: Supernova G2 & G2L & G3 & G6 & G7 & P2 & P6 & T2

Fractal Design: ION, FSP Hydro G(T) Pro (all) & Hydro PTM (all) & Hydro Ti Pro

Galax: Hall of Fame

Gamdias: Helios P1, Lian Li Edge (all)

Montech: Titan (all)

MSI: MEG & MPG (all)

NZXT: (All except C series Bronze)

Phanteks: AMP (except GH) & Revolt (all)

Razer: Katana Chroma

Seasonic: Focus (except SFX models, SFX-L is fine) & Prime (all) & Syncro Connect & Vertex (all)

Silverstone: HELA & Nightjar

Superflower: Leadex (all except silver, Super Bronze Pro and Gold Up ATX 3.1GE 1000/1300w)

Thermaltake: Toughpower iRGB Plus & GF & GF1 & GF2 & GF3 (except 1650w and GF3 A3) & PF1 (except Premium <=850w) & PF3, Vertroo GV (G5)

- Tier B:

1st player: Armour (AR Gold) & SFX (all) & Steampunk (SP)

Abko: Tenergy (TN) Gold

Adata: XPG Kyber (all)

Aerocool: Integrator Gold

Andyson: N & PX & R (all) & TX

Antec: GSK ATX 3.1 & Neo Eco Gold (all except modular atx 3.0, that is tier A) 

AsRock: Steel Legend

Asus: TUF (all) & ROG Strix Platinum 1200w

AZZA: PSAZ Platinum ATX 3.1 & Gold ATX 3.1

be quiet!: Power Zone 2 & Pure Power 11 (NOT 300/350W MODEL) / 11CM / 11FM up to 750w & SFX-L Power & System Power 10 Gold

Bitfenix: BFG (all except =>1000w that is tier A)

Chieftec: Polaris (all) & PowerUp (all) & Vega (PPG-S)

Cooler Master: G (all) & GX (all except CM Storm) & MWE Gold / Gold Modular & MWE V2 White (NOT 230V) / Bronze (NOT 230V) / all "golds" & MWE V3 (all except 230V Bronze) & Vanguard (V series) Gold V1 (all) / Platinum SFX ATX 3.0

Corsair: RM (all) & RM-e (all) & CX-F RGB

Cougar: GEX (all) & LLC

DarkFlash: UpMost (UPT)

DeepCool: Gamer Storm (all) & PM-D & PN-D & PN-M (all)

Enermax: Revolution D.F. 2 & D.F. X (all)

EVGA: G series (all except GD 2019 R1/V1) & SuperNOVA FTW / G+ (or) G1+ (all) / GA / GQ (>=850w) / GM / GT / P+ / P5 / PQ

FSP: Vita (all)

G.Skill: MB Gold

Gamdias: Cyclops & Helios P1A (all) / P2 (all except 1300w that is tier A) 

Gigabyte: Aorus AP-GM & Ultra Durable UD-GM 750w/850w

Huntkey: MVP Gold (all)

High Power: Performance (all) & Super GD+ (all)

InWin: PF Gold & P Gold (650w/750w/850w)

Kolink: Continuum V1 850w & Enclave

Lian Li: SP 750w & PE 750w

Montech: Century 550w/650w / G5 ATX 3.0 750w/850w

MSI: MAG A-GL (all, including PCIe5)

Phanteks: Revolt SFX (all) & AMP GH

Raidmax: Monster 

Redragon: PSU 013 / 015 & Master RGPS ATX 3.1 

Rosewill: Quark & SMG (all) & Tokamak

SAMA: Black Diamond (all) & Forza Titanium & XM

Seasonic: Core (all) & Focus (SFX Models, SFX-L Tier A)

Segotep: PM ATX 3.1

Sharkoon: Rebel (all) & SilentStorm SFX Gold / Cool Zero

SilverStone: Decathlon (all except DA Gold 750w/850w) & SFX SX Gold (new) / SX-LG / SX-G (NOT 600w model) / SX-PT & SFX-L SX-LTI & Strider ST-PT (all) / ST-PTS 1200w / SF-TI 600w/700w/800w & Viva Gold

SuperFlower: Combat (all) & Legion GX Pro & Leadex III Super Bronze Pro

Thermaltake: Toughpower Gold / Grand RGB (all) / GF A3 (all) / PF1 Premium 650w/750w/850w / SFX Platinum ATX 3.1 750w/850w

Thermalright: TR TG FX 550w/650w

Xigmatek: Fury GD & Harrier & Titan PT & Vector P

Zalman: Acrux & Teramax II SE 750w/850w

- Tier C: ADATA XPG Pylon, MSI MAG A-BN, Corsair CX-M 2021 – CV 650/750W.

Depends on budget, ordered by Tier on the [PSU tier-list](https://docs.google.com/spreadsheets/d/1akCHL7Vhzk_EhrpIGkz8zTEvYfLDcaSpZRB6Xt6JWkc/edit?gid=1973454078#gid=1973454078). Do NOT use a power supply of tier D or lower.

Case: 
- Phanteks XT Pro Ultra (and XT Pro).
- Lian Li Lancool 207.
- Corsair 4000D Airflow.
- Phanteks P400A.
- Phanteks G400A.

Get the cheaper one at the time (Or the one that you like the most).

Thermal Paste: 
- Thermalright TF9.
- Artic Mx-(any).
- Honeywell PTM7950 (only for high-end builds, difficult to find online as of now)

Cooler: Stock Cooler (Ryzen 5) Thermalright Peerless Assassin 120 (Ryzen 7 or 9). If you want a liquid cooler for overclock I would go no higher than a Thermalright Frozen Prism 360mm due to the budget constraints.

Feel free to open PR about new parts and issues about problematic old ones!

### Intel Config:

CPU:
- Intel i5 12600k.
- Intel i7 12700k.
- Intel i9 12900k.
- Intel i7 13700k/14700k.

  K suffix refers to overclockable chips
  KF suffix refers to overclockable chips without graphics
  F suffix refers to chips that are not overclockable and don't have graphics. These chips are usually slightly cheaper but are slightly slower than their K/KF counterparts
  no suffix refers to chips that are not overclockable but closer to performance than the F suffix chip

  All of these chips are good for the purposes of mcsr. Stores like Microcenter offer higher tier 12900k chips for 140 usd, 12700k chips for 108 usd,and more. These are through microcenter part bundles that include motherboard and ram.

## 1000USDS (or more)
### AMD Config 2:

CPU:
- AMD Ryzen 7 7700x (or non-x).
- AMD Ryzen 9 7900x (or non-x).
- AMD Ryzen 9 7950x (If you somehow fit it into budget).
- AMD Ryzen 7 9700x.
- AMD Ryzen 9 9900x.
- AMD Ryzen 9 9950x (If you somehow fit it into budget).

Depends on your budget. Ryzen 9 is preferred.

Motherboard: 

**Be wary that 600 series motherboards only support ryzen 9000 with a BIOS update. If you buy one for a ryzen 9000 be sure your motherboard supports BIOS flashback. All motherboards in the list support BIOS flashback**

If you want to overclock use a X670(E) for ryzen 7000 (except Asrock B650M-HDV/m.2) or 870(E) for 9000.

- Asrock B650M-HDV/m.2 (Mid-end, high overclock potential).
- Asus TUF Gaming B650-Plus WiFi (Mid-end, medium overclock potential).
- MSI MPG B650 Carbon WiFi (Mid-end, medium overclock potential).
- Gigabyte X670 Aorus Elite AX (High-end, high overclock potential).
- Asrock X670E PG Lightning (High-end, high overclock potential) **Use this for maximum performance. Not cheap**.
- Gigabyte X870 AORUS Elite WIFI7 Ice (High-end, high overclock potential) **Use this for maximum performance. Not cheap**.
- MSI MAG X870 Tomahawk WiFi (Very High-end, very high overclock potential) **Use this for maximum performance. Not cheap**.
- Asrock X870E Taichi Lite (Very High-end, very high overclock potential) **Use this for maximum performance. Not cheap**.

Disk:

Gen4 drives

- WD Blue SN580 1TB/2TB 4150MB/s (Low-end).
- Kingston NV3 1TB/2TB 6000MB/s (Mid-end).
- Crucial P3 Plus 1TB/2TB 5000MB/s (Mid-end).
- Teamgroup MP44 1TB/2TB 7400MB/s (High-end).
- WD Black SN850X 1TB/2TB 7300MB/s (High-end).
- SK Hynix Platinum P41 1TB/2TB 7000MB/s (High-end).

Gen5 drives
(No idea as of now)


Faxiang and Adata drives are NOT recommended (Quality control issues). As well as samsung 980/990 lineup (You need to update the firmware on these drives).

RAM: 

SK Hynix A-die and SK Hynix M-die are the best memory dies for DDR5 kits.

32GB DDR5 (2x16GB 6000MHz CL30) or 48GB DDR5 (2x24GB 6000MHz CL32) recommended. Preferably GSkill or Teamgroup. Here is a few kits:

32GB:
- Teamgroup T-Force Delta RGB 6400MHz CL32 2x16GB (SK Hynix A-die) (High overclock potential).
- G.Skill Trident Z5 RGB 6400MHz CL32 2x16GB (SK Hynix A-die) (High overclock potential).
- G.Skill Ripjaws S5 6000MHz CL30 2x16GB (SK Hynix A-die) (High overclock potential).
- Teamgroup T-Force Xtreme 6400MHz CL28 2x16GB (SK Hynix A-die) (Extreme overclock potential).
- G.Skill Trident Z5 RGB 6600MHz CL28 2x16GB (SK Hynix A-die) (Extreme overclock potential).
- G.Skill Ripjaws S5 6400MHz CL26 2x16GB (SK Hynix A-die) (Maximum overclock potential).
- G.Skill Trident Z5 Neo RGB 7200MHz CL26 2x16GB (SK Hynix A-die) (Maximum overclock potential).

This is list is ordered by kit quality, first one being the worst.

48GB:
- Team Group T-Force Delta RGB 6400MHz CL32 2x24GB (SK Hynix M-die) (Very High overclock potential).
- G.Skill Trident Z5 RGB 6400MHz CL32 2x24GB (SK Hynix M-die) (Very High overclock potential).
- G.Skill Trident Z5 Neo RGB 6400MHz CL28 2x24GB (SK Hynix M-die) (Extreme overclock potential).
- Teamgroup T-Force Delta RGB 6400MHz CL28 2x24GB (SK Hynix M-die) (Extreme overclock potential).
- G.Skill Trident Z5 RGB 6600MHz CL26 2x24GB (SK Hynix A-die) (Maximum overclock potential).
- G.Skill Ripjaws S5 6400MHz CL26 2x24GB (SK Hynix A-die) (Maximum overclock potential).

This is list is ordered by kit quality, first one being the worst.

GPU: 
- Nvidia GTX 1650.
- Nvidia GTX 1650 Super.
- Nvidia GTX 1660.
- Nvidia GTX 1660 Super.
- AMD Radeon RX 5600XT.
- Nvidia RTX 2060.
- AMD Radeon RX 5700XT.
- Intel Arc B580.
- Nvidia RTX 3060 12GB.
- AMD Radeon RX 6600XT.
- Nvidia RTX 3060Ti.
- AMD Radeon RX 6700XT.

AMD GPU's have extremely weak encoding support and a [bad F3 pie chart](https://youtu.be/cbaUJWzXh18?si=Skky-MPVjeDGD_01) that make them hard to recommend. Only buy them if you don't mind low-streaming quality and the bad F3 pie chart.

Depends on budget, cards ordered by rasterization performance (Where last is the best) based on [Techpowerup relative performance chart](https://www.techpowerup.com/gpu-specs/geforce-rtx-4090.c3889) and [Hardware Unboxed B580 Overhead Testing](https://youtu.be/00GmwHIJuJY?si=LPrTZA8G5Suzo9vH), if you also want to game on your machine go for higher tiers.

PSU: 
- Tier A: Adata XPG Core Reactor (I and II), MSI MPG-A GF, Corsair RM 2019-2021 series.
- Tier B: Cooler Master MWE Gold V2, Corsair CX-F RGB.

Depends on budget, ordered by Tier on the [PSU tier-list](https://docs.google.com/spreadsheets/d/1akCHL7Vhzk_EhrpIGkz8zTEvYfLDcaSpZRB6Xt6JWkc/edit?gid=1973454078#gid=1973454078). Do NOT use a power supply of tier C or lower.

Case: 
- Phanteks XT Pro Ultra (and XT Pro) (Low-end).
- Corsair 4000D Airflow (Low-end).
- Phanteks P400A (Low-end).
- Phanteks G400A (High-end **and cheap!**).
- Fractal Design North (High-end).
- Lian Li Lancool 207 (High-end).
- Antec Flux Pro (High-end)
- Antec C8 ARGB (High-end).

Use a case that can sustain the CPU that you used in the build, for that you can check reviews of the cases online. The low-ends will only cool up to a 9900x or 7950x.

Thermal Paste: 
- Thermalright TF9. (High-end)
- Honeywell PTM7950 (Best performance, difficult to find online as of now. Use it if you can).

Cooler: Thermalright Frozen Prism 360mm or Artic Liquid Freezer III 360mm/420mm.

Feel free to open PR about new parts and issues about problematic old ones!

### Intel Config 2:

## Microcenter Combos and Deals

Microcenter (US Only) usually has some really good value combos and deals on their website and in person locations. If you are low on budget or you want the maximum value for your dollar try to get one of these:

[Microcenter AMD Bundles](https://www.microcenter.com/site/content/bundle-and-save.aspx)

[Microcenter Intel Bundles](https://www.microcenter.com/site/content/intel-bundle-and-save.aspx)

Then you can continue the build process just ignoring the things you already bought in the bundle.

# Best Price-Performance Laptop Config

I have no idea.

# Peripherals

# Hardware Tuning

# Overclock

# Graal Flags Tricks

# Azul Prime

# Best Windows Config

# Best Linux Config (X-org)

# Best Linux Config (Wayland)

# Resources and Sources

### Information:

[DDR5 OC Guide](https://www.overclockers.com/ddr5-overclocking-guide/)

[DDR4 OC Guide](https://github.com/integralfx/MemTestHelper)

[Bullzoid Youtube Channel](https://www.youtube.com/@ActuallyHardcoreOverclocking)

[Gamers Nexus Youtube Channel](https://www.youtube.com/@GamersNexus)

[SkatterBencher Youtube Channel](https://www.youtube.com/@SkatterBencher)

[Hardware Unboxed Youtube Channel](https://www.youtube.com/@Hardwareunboxed)

[techless Youtube Channel](https://www.youtube.com/@techlessYT)

[Optimum Tech Youtube Channel](https://www.youtube.com/@optimumtech)

[Ultimate Guide for everything](https://youtu.be/Ir8_vgbsTsM)

[PSU tier-list](https://docs.google.com/spreadsheets/d/1akCHL7Vhzk_EhrpIGkz8zTEvYfLDcaSpZRB6Xt6JWkc/edit?gid=1973454078#gid=1973454078)

[Techpowerup relative performance gpu chart](https://www.techpowerup.com/gpu-specs/geforce-rtx-5090.c4216)

### Resouces (apps):

#### Windows
[Memtest86+](https://memtest.org/)

[AIDA64 Extreme](https://www.aida64.com/downloads)

[OCCT](https://www.ocbase.com/)

[ZenTimings](https://zentimings.com/)

[Hardware Monitoring](https://www.cpuid.com/softwares/hwmonitor.html)

[PYPrime](https://github.com/monabuntur/PYPrime-2.x)

[MaxMEM2](https://www.softpedia.com/get/System/Benchmarks/MaxxMEM2.shtml)

[Cinebench 2024](https://www.maxon.net/en/downloads/cinebench-2024-downloads)

[CPU-Z](https://www.cpuid.com/softwares/cpu-z.html)

#### Linux
[Waywall](https://github.com/tesselslate/waywall)

[Resetti](https://github.com/tesselslate/resetti)

#### Both
[PrismLauncher](https://prismlauncher.org/download/)

[OBS Studio](https://obsproject.com/download)
