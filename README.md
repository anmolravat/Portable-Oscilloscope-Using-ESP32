# Portable Oscilloscope Using ESP32

A compact and low-cost portable oscilloscope developed using **ESP32** and **ADS1115 (16-bit ADC)** for real-time analog signal acquisition and waveform visualization.

##  Project Overview

The system captures analog signals through the ADS1115 ADC, processes the sampled data using the ESP32, and displays the waveform and signal parameters on a 0.96-inch OLED display.

The oscilloscope can display:
- Real-time waveform
- Peak-to-peak voltage (Vpp)
- RMS voltage (Vrms)
- Frequency
- DC voltage

##  Components Used

- ESP32
- ADS1115 16-bit ADC
- 0.96-inch OLED Display
- Push Button
- Jumper Wires
- Breadboard
- Laptop

##  Technologies Used

- Embedded Systems
- ESP32
- Arduino IDE
- C/C++
- I2C Communication
- Analog-to-Digital Conversion
- Real-Time Signal Processing

##  Working Principle

1. The analog input signal is connected to the ADS1115 ADC.
2. ADS1115 converts the analog signal into digital samples.
3. ESP32 receives and processes the samples through I2C.
4. The processed signal is converted into waveform coordinates.
5. The waveform is displayed on the OLED screen.
6. Frequency and voltage parameters are calculated and displayed in real time.

## Testing

The system was tested using sine, square, and triangular wave signals from a function generator. The ESP32 processed the sampled signals and displayed their waveforms and parameters on the OLED.

##  Repository Contents

- `portable_oscilloscope.ino` – ESP32 source code
- `mini_Project_Report.pdf` – Complete project report
- `projectimage1.jpeg` – Project image
- `miniproject2.jpeg` – Project image
- `oscilloscope_component_crops.zip` – Component images

##  Future Enhancements

- Higher sampling rate and bandwidth
- Multi-channel signal acquisition
- Wi-Fi/Bluetooth waveform transmission
- Data logging
- FFT-based frequency analysis
- Rechargeable battery operation
- Automatic triggering and scaling

##  Project Type

**Mini Project – Electronics and Communication Engineering**
