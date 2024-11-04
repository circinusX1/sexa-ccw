# 6 Coils Guitar Pickup
## EXI-CCW, Six Continous Coils Winding guitar pickup

EXI -  SIX in Greek.
CCW -  Continous Coils Winding, 

The coils / diffferential input of the OP amp have no soldering between the coils (less noise). 


![ccw-show](https://github.com/user-attachments/assets/264fc695-38b5-48cc-875b-a993a79dcdc8)See Guitar maxim frequencies chart here: 


### LESS HUM, BETTER PICK ATTACK, STRING SEPARATION, LESS HARMONICS, MUDDY SOUND GONE 


All EasyEda PCB's for different version are in EadyEDA folder.

This is an active guitar pickup with one coil per string. It has 6 coils.
Made by ghitara dot com, this high-quality pickup is designed to provide exceptional sound and performance. 
The model sexa-ccw is a perfect choice for those who want to upgrade their guitar's sound. This electric guitar pickup is perfect 
for enhancing the sound of your guitar due low inductance. Each coil has between 500 and 800 turns. The frequency response is better than 
classic guitar pickups. I did tests on EMG active pickup and Harley Benton Passive, see Bode diagrams below. 
To find more search on youtube '6 coils guitar pickup'


# EXI-CCW, Six Continous Coils Winding guitar pickup


### 3D casing models

[STL 3d MODEL](https://github.com/circinusX1/sexa-ccw/blob/main/3d/exi-emboss.stl)


### Performance

---
  * Frequency response and cutoff

Here are typical freqencies ranges for different instruments. An electric guitar max is about 1.2Khz, If we include the harmonics 
we can consider it will go up to 4..6Khz. All studios would cut off a guitar before processing at 4 or 6.

 ![freq_ranges7](https://github.com/user-attachments/assets/84ee54c9-d4f3-42eb-9eab-dfd46383acb1)


     * Original document: http://guitarbuilding.org/wp-content/uploads/2014/06/Instrument-Sound-EQ-Chart.pdf


#### Frequency response

       

    Here Ive tested couple of pickups I had handy in the range of 100 to 15 Khz. The probe is a coil with almost
    0 inductance was made as: 140..160 turns of 0.1mm wire on a wood coffe stiring stick.
    The yellow one is the EXI-CCW, Excuse the spelling

See it here: https://www.youtube.com/watch?v=KD3PIVsBRIo


    


![frequency-response-guitar-graph](https://github.com/circinusX1/sexa-ccw/assets/69641625/6f998b94-56da-473a-8156-6cec2b3ec632)



---

#### Magnetic field distribution

![image](https://github.com/user-attachments/assets/b8a5d370-a5ae-42d9-b2ab-b33b3e6394ff)



#### SNR


   * Signal to Noise ratio measurements (Left Side: noise [Pickup, cables, Probe] in dB, Right All strings hit signal dB) SNR > 45dB
   * Test on EXI-CCW V1 V2 and V3

![snr_measurements](https://github.com/user-attachments/assets/9e77f4ac-187c-401d-b68d-649ec1bbebdc)

     


### Active pickup, V1

![sche_6coils](https://github.com/circinusX1/sexa-ccw/assets/69641625/2b5d4f61-82ba-425c-bbf4-3223ea398ee7)

---

![pick-pcb-6c](https://github.com/circinusX1/sexa-ccw/assets/69641625/6b53ffa5-7a11-4bb3-852e-07e3fcdf1ea7)

---


---


#### V3 sexa-ccw

![pick_v3](https://github.com/circinusX1/sexa-ccw/assets/69641625/90c53b04-8858-478b-84e9-50dcb3daaf10)


---


[DEMO Version 2/3 with TL071 ](https://www.youtube.com/watch?v=29cAE45jkJk)

[DEMOVersion 1 with Transistor](https://www.youtube.com/watch?v=PKX4ls18GiM)

[DEMO BETA Version with Transistor](https://www.youtube.com/watch?v=EW_jxvgFBk8)

[ORDER & BUY HERE Version 3](https://ghitara.com/?p=_sexa_ccw.php)

---

By: Marius C.
overview

### Wiring, as any humbucker active pickup:
![hum_pickup_schem](https://github.com/user-attachments/assets/ab6aecd4-c662-405d-a481-3dcc77360dc5)






## One or Double coil standard guitar pickups comments

Standard guitar pickup core is mostly plastic (75%). The active iron adds up up 30% in few cases,
but 90% of the pickups core is 24..26% being extremely inneificient. 
This tehnology is a century old and has not evolved a bit. With new modern low noise IC's
this can be improved as I said above. Here are the drawbacks of such a bad old tehnology.


![filling-factor](https://github.com/user-attachments/assets/97ca918b-d1ad-4c51-9ae8-c7bfb1c99bd2)



### Single or dual coil pickups problems

A regular pickup coil is extremely inefficient. The shape of the coil is elongated along all strings.This decreases the coil inductance, actually you barely can calculate the inductance of such a coil. A second factor is the permeability of the mixed plastic and string iron nuts. 70% of the inner core is plastic. The whole core adds up to 480 .. 500 squared mm. The nuts area is: 6(nuts) x PI x 2.5mm(radius)^2 → 110..120 squared mm. This represents 25%. To compensate such inneficiency the coil has around 6000 .. 8000 turns, with a wire which adds up a lot of capacitance and resitance. Such a coil has 1.8 to 2.5 Henrys. A humbucker dual coil would be double, like 4..5 Henrys. 


![image](https://github.com/user-attachments/assets/ceea8f12-f662-4d90-ba2e-e98fb5aa3d4b)

This huge number of turns adds up parasite capacitance. This makes the standard pickup sound dull and muddy. Exi coil uses 6 separate coils with 99% full iron core. Exi pickup achieves same inductance with 10 times fewer turns. Coils turns tunning and proper phasing and assembly makes the magnetic field uniform across the pickup. Exi-pickup has 10 times less turns, reduced capacitance, the sound is much clean and the muddy effect is almost gone. 


### Order and buy
   * https://exicoil.from-ca.com/
   * https://www.ebay.ca/itm/226431325173
   * https://www.ebay.ca/itm/226431719766
   * https://www.ebay.ca/itm/226431844051
   * https://www.kijiji.ca/v-view-details.html?adId=1705665369

### Issues, Help 
   * https://github.com/circinusX1/exi-ccw/issues




