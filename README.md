![WhatsApp Image 2025-11-27 at 10 35 21_9340944a](https://github.com/user-attachments/assets/60fd92fa-55f3-4f85-9c8c-efbfd3361de1)
# Exp 4 Experimental verification of frequency response of Analog fiber optic link
# Fiber Optic Link Analysis (660nm)

## AIM
To analyze the relationship between input and received signal of a 660nm fiber optic cable using analog and digital link.

---


## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections (as shown in Figure 19):  
   a. Connect the 1KHz sine wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to AC amplifier 1 input.  
4. On the board, switch emitter 1's driver to analog mode.  
5. Switch on the power.  
6. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
7. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
8. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

<img width="931" height="555" alt="image" src="https://github.com/user-attachments/assets/f7933923-f8d4-49d0-bbb6-0eb8954dae45" />

---

## CONNECTION DIAGRAM  
**Setting up an Analog Link**

<img width="931" height="555" alt="image" src="https://github.com/user-attachments/assets/f7933923-f8d4-49d0-bbb6-0eb8954dae45" />

---

## TABULATION  
**Transmission through Analog Link**

| Frequency (Hz) | Output Signal Amplitude (V) | Gain = Vo / Vi | Gain (dB) |
| -------------- | --------------------------- | -------------- | --------- |
| 1 kHz          | 1.3                         | 1.083          | 0.6952    |
| 10 kHz         | 1.32                        | 1.1            | 0.81      |
| 40 kHz         | 1.55                        | 1.292          | 2.273     |
| 100 kHz        | 1.92                        | 1.6            | 4.082     |
| 160 kHz        | 1.98                        | 1.65           | 4.35      |
| 190 kHz        | 1.98                        | 1.65           | 4.35      |
| 220 kHz        | 1.98                        | 1.65           | 4.35      |
| 320 kHz        | 1.95                        | 1.625          | 4.35      |
| 450 kHz        | 1.6                         | 1.342          | 3.78      |
| 510 kHz        | 1.45                        | 1.253          | 2.499     |
| 1 MHz          | 1.29                        | 1.075          | 0.628     |

---

## MODEL GRAPH

<img width="1290" height="674" alt="image" src="https://github.com/user-attachments/assets/76f5d47f-6e80-4c84-b13f-b9ffe1aca44d" />
<img width="1125" height="824" alt="image" src="https://github.com/user-attachments/assets/c8b05538-521b-40f1-9105-35de4bd45f7b" />


---

## RESULT

Thus, the relationship between input and received output signal from 660nm fibre optic cable using analog link is analyzed
