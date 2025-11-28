# EX-NO-6-EXPERIMENTAL-VERIFICATION-AND-SIMULATION-OF-ACTIVELPF-HPF-AND-BPF
## 6 DESIGN OF ACTIVE LOW PASS, HIGH PASS AND BAND PASS FILTERS USING OP-AMP
            
**DATE:**  
         
---

## AIM
            
**DATE:**  
         
---

## AIM and obtain the frequency response of

i)	First order Low Pass Filter (LPF)
ii)	First order High Pass Filter (HPF)
iii)	Band pass filter

---

** 6 A :- LOW PASS FILTER**



## THEORY
## LOW PASS FILTER
A LPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.
## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |

---
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-28 at 4 04 02 PM](https://github.com/user-attachments/assets/ca28bd45-a753-477c-b52b-ad4a04658681)

![WhatsApp Image 2025-11-28 at 4 25 04 PM](https://github.com/user-attachments/assets/10785940-aba0-4e23-8fcf-43327aced0e1)

## MODEL GRAPH

![WhatsApp Image 2025-11-28 at 4 07 16 PM](https://github.com/user-attachments/assets/dbe4028e-b939-44c4-8c31-8f7169e5caa1)

---

## DESIGN

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


## PROCEDURE

PROCEDURE - (LPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency  lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION
![WhatsApp Image 2025-11-28 at 4 07 58 PM](https://github.com/user-attachments/assets/06e583a7-fc0e-4408-844d-ad88be3708a7)

		

---

## OUT PUT WAVEFORM AND DISCUSSION 

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/7b056165-7a34-45d2-94d9-e1753d3b49ef" />


![WhatsApp Image 2025-11-28 at 4 08 49 PM](https://github.com/user-attachments/assets/1f6c2eee-3579-4291-ac9e-9b2a6da44994)


 ## 6 B HIGH PASS FILTER

---

## THEORY
HIGH PASS FILTER
A HPF allows frequencies from 0 to higher cut of frequency, fH. At fH the gain is 0.707 Amax, and after fH gain decreases at a constant rate with an increase in frequency. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1.6K,10K,5.86K, 0.1 µF | 1 |
| 7 | Connecting wires and probes | As required | — |


## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-28 at 4 09 34 PM](https://github.com/user-attachments/assets/35fc90a6-c57b-4e5e-9362-dc23abedde48)

![WhatsApp Image 2025-11-28 at 4 26 13 PM](https://github.com/user-attachments/assets/4e456af4-e329-468e-ad41-94033442e55d)


## MODEL GRAPH

![WhatsApp Image 2025-11-28 at 4 10 08 PM](https://github.com/user-attachments/assets/5849ed91-b7ec-4b8b-b918-0d1ee986d8d6)


---

## DESIGN

Given: fH = 1 KHz = 1/ (2πRC) Let C = 0.1 µF, R = 1.6 KΩ
For n = 2, α (damping factor) = 1.414, Passband gain = Ao = 3 - α =3 – 1.414 = 1.586.
Transfer function of second order butterworth LPF as:
1.586
 
H(s) =
 
S2 + 1.414 s + 1
 
Now	Ao = 1 + (Rf / R1) = 1.586 = 1 + 0.586
Let Ri = 10 KΩ, then Rf = 5.86 KΩ


## PROCEDURE

PROCEDURE - ( HPF):
1.	Connect the circuit as shown in the circuit diagram.
2.	Select the corresponding cut-off frequency ( lower) and determine the value of C&R. select the value of R1 & Rf depending on desired passband gain Af..
3.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
4.	Tabulate the output voltage Vo with respect to different values of input frequency.
5.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![WhatsApp Image 2025-11-28 at 4 10 56 PM](https://github.com/user-attachments/assets/67a4a7f3-bba2-4ee1-a6e2-f699daed73d4)


## OUT PUT WAVEFORM AND DISCUSSION 

<img width="1280" height="719" alt="image" src="https://github.com/user-attachments/assets/9bae968b-c2d0-45d9-adad-13b4fa04a2b5" />


![WhatsApp Image 2025-11-28 at 4 11 40 PM](https://github.com/user-attachments/assets/16e04f59-7c6e-43d4-ad98-6983d8389b82)


 ## 6C Band Pass Filter

---

## THEORY
 ##Band Pass Filter
A BPF allows frequencies in between lower cut of frequency and higher cut of frequency, fH-fL. A band-pass (BP) filter passes frequencies in a band fL_fH and attenuates below fL and above fH.. The gain decreases 20dB each time the frequency is increased by 10. Hence the rate at which the gain rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in frequency. The frequency f=fH is called the cut off frequency because the gain of the filter at this frequency is down by 3 dB from 0 Hz. Other equivalent terms for cut-off frequency are -3dB frequency, break frequency, or corner frequency.


## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 2 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors |10K,38.8K,7.9K,0.01uf | 1 |
| 7 | Connecting ires and probes | As required | — |


## CIRCUIT DIAGRAM

![WhatsApp Image 2025-11-28 at 4 12 36 PM](https://github.com/user-attachments/assets/c88f3697-7186-4a8c-893d-dc7b79645a13)

![WhatsApp Image 2025-11-28 at 4 27 04 PM](https://github.com/user-attachments/assets/7cd00e40-4a3f-4ea1-b0e9-d4852e68146b)

## MODEL GRAPH

![WhatsApp Image 2025-11-28 at 4 13 37 PM](https://github.com/user-attachments/assets/20a00e6b-eec2-4390-ad38-1c8c99b30136)


---

## DESIGN

DESIGN: BAND PASS FILTER

Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.
1.	Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency of HPF as fL = 1 KHz.
2.	Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf. Let C = 0.1μf.
3.	Calculate R from the expression. Given: fH = 2KHz = 1/ (2πR1C1) Let C1 = 0.1 µF, R1 = 7.9 KΩ
Given: fL = 400Hz = 1/ (2πR2C2)
Let C2 = 0.1 µF, R2 = 39.8 KΩ
Pass band Gain=4
Now		Ao = 1 + (Rf / R1) 2-1=(Rf / Ri)
Ri = Rf
Let Ri = Rf = 10 KΩ


## PROCEDURE

PROCEDURE:BAND PASS FILTER
1.	Select the lower and higher cut-off frequency and calculate the value of R & C for the given frequencies.
2.	Design for LPF & HPF separately and then combine the circuit by first placing the HPF followed by a LPF (i.e) HPF in series with LPF.
3.	Connect the circuit as shown in the circuit diagram.
4.	Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp.
5.	Tabulate the output voltage Vo with respect to different values of input frequency.
6.	Calculate passband gain and plot the graph of frequency versus voltage gain & check the graph to get approximately the same characteristic as shown in the model graph.



## TABULATION

![WhatsApp Image 2025-11-28 at 4 14 12 PM](https://github.com/user-attachments/assets/4b3ab634-9c03-43b0-a6da-92dea6be3409)


---

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-28 at 4 15 06 PM](https://github.com/user-attachments/assets/a965feb9-3e41-4eb9-b6d6-f8b70d0ff8fe)

<img width="784" height="339" alt="image" src="https://github.com/user-attachments/assets/cdac995a-4394-46d5-83d9-57f6bed22acd" />


---
##RESULT:
	Thus an Active Low pass, High pass and Band Pass Filters are designed and
tested using op-amp IC 741.
---

   ![WhatsApp Image 2025-11-28 at 4 17 10 PM](https://github.com/user-attachments/assets/33897859-ddfa-49e3-a1a2-f6aa9a312446)

