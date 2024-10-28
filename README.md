# Wireless-Communications-Link-SDR

## Overview
This project focuses on developing a wireless communications link using Software-Defined Radio (SDR) with MATLAB and Simulink. The goal is to transmit and receive over-the-air (OTA) signals, addressing practical challenges in wireless communication. 

Gain practical experience in wireless communication by designing inexpensive software-defined radios. This project provides a hands-on approach to learning about propagation loss, synchronization loss, and other critical aspects of wireless data transmission.

## Motivation
The world has gone wireless! So many bits flying through the air. This project is an opportunity for me to learn how to transmit digital data through the air using MATLAB, RF signals, and software-defined radio (SDR). The industry needs engineers with wireless experience due to the use of wireless signals in many applications.

## Project Goals
- Design and implement a wireless communication link.
- Optimize for criteria such as transfer speed, reliability, or security.
- Develop a receiver capable of carrier frequency synchronization and error correction.
- Document the entire process to facilitate learning and knowledge sharing.

## Technologies Used
- **MATLAB**: For modeling and simulation.
- **Simulink**: For visual programming and simulation of the wireless link.
- **Software-Defined Radio (SDR)**: Such as ADALM-Pluto for transmission and reception.

## Steps
1. Select source data and break it down into bundles of bits.
2. Design OTA transmission scheme, including modulation type and optional forward error correction.
3. Model a channel in software, accounting for impairments expected in the actual link.
4. Build a corresponding receiver that accomplishes carrier frequency synchronization, timing synchronization, and frame synchronization.
5. Decode the source bits.
6. Once the link works as expected in software, remove the channel model and transmit and receive using SDR hardware.
7. Optimize your design for selected criteria such as throughput, reliability, or security.

## Project Structure
- `/src`: Source code and MATLAB scripts
- `/docs`: Documentation and resources
- `/data`: Sample data used for testing and simulation
- `README.md`: Project overview and instructions

## Getting Started
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/maheen055/Build-a-Wireless-Communications-Link.git

## Contributing
Feel free to fork the repository and submit pull requests with improvements or additional features.

## Contact
For any questions or feedback, please reach out to mshoaib@uwaterloo.ca.

## License
This project is licensed under the MIT License.

Project endorsed by: 
![image](https://github.com/user-attachments/assets/c6d1441f-a316-400f-8571-d56965eda46f)
