🇮🇹Italian Guide🇮🇹 (English below)
# 📚 Guida ai Componenti e Tutorial - Starter Kit Arduino

Benvenuto! Se hai acquistato uno dei nostri Kit, in questa pagina troverai le risorse essenziali e i link ufficiali per far funzionare ogni singolo componente. Niente teoria noiosa, solo guide pratiche per arrivare subito al risultato.

## 🛠️ 1. Il Software (Punto di partenza)
Prima di collegare i fili, ti serve il programma per scrivere il codice:
* [Scarica l'IDE ufficiale di Arduino (Windows/Mac/Linux)](https://www.arduino.cc/en/software)
* Se hai la **R4 Minima**, ricordati che potresti dover andare su *Strumenti > Gestione Schede* nell'IDE e installare il pacchetto "Arduino UNO R4 Boards".

---

## 🟢 2. Componenti di Base

### LED, Resistenze e Breadboard
Impara a chiudere un circuito base e a far lampeggiare il tuo primo LED.
* **Progetto:** [Blink (Far lampeggiare un LED)](https://docs.arduino.cc/built-in-examples/basics/Blink)
* **Progetto:** [Fade (Cambiare la luminosità del LED progressivamente)](https://docs.arduino.cc/built-in-examples/analog/Fade)

### Potenziometro
Usa la manopola per variare dati e controllare altri componenti.
* **Progetto:** [Leggere un valore analogico (AnalogReadSerial)](https://docs.arduino.cc/built-in-examples/basics/AnalogReadSerial)

### Fotoresistenza (Sensore di luce)
Crea un interruttore crepuscolare: fai accendere i LED quando la stanza diventa buia.
* **Tutorial:** [Come usare una Fotoresistenza con Arduino](https://arduinogetstarted.com/tutorials/arduino-light-sensor)

### Buzzer
Fai suonare allarmi o melodie.
* **Progetto:** [Suonare una melodia con Arduino (Tone Melody)](https://docs.arduino.cc/built-in-examples/digital/toneMelody)

---

## 🟡 3. Sensori Intermedi

### Sensore a Ultrasuoni (HC-SR04)
Il componente perfetto per misurare le distanze e creare un radar o un robot che evita gli ostacoli.
* **Tutorial:** [Guida completa al sensore HC-SR04](https://arduinogetstarted.com/tutorials/arduino-ultrasonic-sensor)

### Sensore Touch Capacitivo
Sostituisci i vecchi pulsanti meccanici con un tocco stile smartphone.
* **Tutorial:** [Usare il sensore Touch capacitivo](https://arduinogetstarted.com/tutorials/arduino-touch-sensor)

### Display a 7 Segmenti (4 Cifre)
Ottimo per creare timer, orologi o contatori.
* **Tutorial:** [Come usare un Display a 7 Segmenti](https://howtomechatronics.com/tutorials/arduino/arduino-and-7-segment-display/)

---

## 🔴 4. Componenti Avanzati (Robotica e Domotica)

### Servomotore SG90
Il motore per dare movimento ai tuoi progetti (es. spazzole di un radar, bracci robotici).
* **Progetto:** [Sweep (Far ruotare il motore da 0° a 180°)](https://docs.arduino.cc/built-in-examples/servo/Sweep)

### Schermo LCD 1602 con Modulo I2C
Stampa messaggi di testo e dati dei sensori. *Nota: Grazie al modulo nero pre-saldato (I2C), ti basteranno solo 4 cavi invece di 16!*
* **Tutorial:** [Guida allo Schermo LCD con I2C](https://lastminuteengineers.com/i2c-lcd-arduino-tutorial/)

---

💡 **Consiglio per l'esame o il tuo progetto:**
Inizia sempre testando **un componente alla volta**. Solo quando sei sicuro che il sensore a ultrasuoni funziona, aggiungi il display o il buzzer per creare il progetto completo. Buon making!

🇬🇧English Version🇬🇧
# 📚 Components Guide & Tutorials - Arduino Starter Kit

Welcome! If you purchased one of our Kits, this page contains the essential resources and official links to get every single component working. No boring theory, just practical guides to get results immediately.

## 🛠️ 1. The Software (Starting Point)
Before connecting any wires, you need the software to write your code:
* [Download the Official Arduino IDE (Windows/Mac/Linux)](https://www.arduino.cc/en/software)
* If you have the **R4 Minima**, remember you may have to go to *Tools > Board > Boards Manager* in the IDE and install the "Arduino UNO R4 Boards" package.

---

## 🟢 2. Basic Components

### LEDs, Resistors & Breadboard
Learn how to close a basic circuit and blink your first LED.
* **Project:** [Blink (Turn an LED on and off)](https://docs.arduino.cc/built-in-examples/basics/Blink)
* **Project:** [Fade (Smoothly change LED brightness)](https://docs.arduino.cc/built-in-examples/analog/Fade)

### Potentiometer
Use the knob to vary data and control other components.
* **Project:** [Read an Analog Value (AnalogReadSerial)](https://docs.arduino.cc/built-in-examples/basics/AnalogReadSerial)

### Photoresistor (Light Sensor)
Create a twilight switch: make LEDs turn on when the room gets dark.
* **Tutorial:** [How to use a Photoresistor with Arduino](https://arduinogetstarted.com/tutorials/arduino-light-sensor)

### Buzzer
Play alarms or melodies.
* **Project:** [Play a Melody with Arduino (Tone Melody)](https://docs.arduino.cc/built-in-examples/digital/toneMelody)

---

## 🟡 3. Intermediate Sensors

### Ultrasonic Sensor (HC-SR04)
The perfect component to measure distances and create a radar or an obstacle-avoiding robot.
* **Tutorial:** [Complete Guide to the HC-SR04 Sensor](https://arduinogetstarted.com/tutorials/arduino-ultrasonic-sensor)

### Capacitive Touch Sensor
Replace old mechanical buttons with smartphone-style touch input.
* **Tutorial:** [Using the Capacitive Touch Sensor](https://arduinogetstarted.com/tutorials/arduino-touch-sensor)

### 7-Segment Display (4 Digits)
Great for creating timers, clocks, or counters.
* **Tutorial:** [How to use a 7-Segment Display](https://howtomechatronics.com/tutorials/arduino/arduino-and-7-segment-display/)

---

## 🔴 4. Advanced Components (Robotics & Smart Home)

### SG90 Servo Motor
The motor to give movement to your projects (e.g., radar sweeps, robotic arms).
* **Project:** [Sweep (Rotate the motor from 0° to 180°)](https://docs.arduino.cc/built-in-examples/servo/Sweep)

### 1602 LCD Screen with I2C Module
Print text messages and sensor data. *Note: Thanks to the pre-soldered black module (I2C), you will only need 4 wires instead of 16!*
* **Tutorial:** [Guide to LCD Screen with I2C](https://lastminuteengineers.com/i2c-lcd-arduino-tutorial/)

---

💡 **Pro-Tip for your project or exam:**
Always start by testing **one component at a time**. Only when you are sure the ultrasonic sensor works perfectly, add the display or the buzzer to complete your full project. Happy making!
