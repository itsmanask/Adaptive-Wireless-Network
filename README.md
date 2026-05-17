# Adaptive Wireless Network Simulation 📡📶

A simulation-driven Wireless Networks project focused on adaptive WiFi communication, interference resilience, and network survivability under realistic indoor and war-like conditions.

The project models IEEE 802.11 wireless networks using adaptive modulation, channel modeling, BER analysis, Rayleigh fading, and anti-jamming mechanisms to evaluate real-world wireless communication performance.

## 🚀 Features

- IEEE 802.11 WiFi network simulation
- Adaptive modulation and rate selection
- Multi-node wireless topology simulation
- Rayleigh fading channel modeling
- BER and throughput analysis
- Anti-jamming frequency hopping
- Interference and fault scenario testing
- Network survivability evaluation

## 🧠 Core Concepts

The system dynamically switches between:
- BPSK
- QPSK
- 16-QAM
- 64-QAM

based on real-time Signal-to-Noise Ratio (SNR) conditions to maximize throughput while maintaining reliable communication.

## ⚙️ Technologies Used

- Python
- NumPy
- SciPy
- Matplotlib
- NetworkX

## 🌐 Simulation Architecture

The project includes:
- Point-to-point WiFi simulation
- 3-node relay network
- 15-node random wireless topology
- Indoor path loss modeling
- Rayleigh fading simulation
- Dynamic throughput analysis

The network consists of:
- 1 Access Point (AP)
- Up to 14 wireless stations (STAs)
- 50m indoor coverage environment

## 📊 Channel & Environment Modeling

Implemented wireless impairments include:
- AWGN Noise
- Indoor Log-Distance Path Loss
- Multipath Rayleigh Fading
- Interference Scenarios
- Relay Failures
- Active Jamming Conditions

## 🔄 Adaptive Features

The system supports:
- Dynamic rate adaptation
- Automatic modulation switching
- Frequency hopping from 2.4 GHz to 5 GHz under jamming
- Real-time BER-based throughput optimization

## 📈 Results

### Scenario A – Normal Indoor Environment
- Maintained high throughput with stable connectivity
- Achieved near full network survivability
- Adaptive modulation selected optimal data rates dynamically

### Scenario B – War-like / Worst-Case Environment
- Simulated dense interference and jamming conditions
- Maintained connectivity for **13/14 nodes**
- Demonstrated automatic recovery using anti-jamming techniques
- Throughput degradation and SNR variations analyzed extensively

## 🛠️ Functional Modules

- Adaptive Rate Selection
- SNR Calculation Engine
- BER Estimation
- Rayleigh Fading Generator
- Throughput Analysis
- Network Survivability Evaluation
- Frequency Hopping Mechanism

## 👨‍💻 Development

The complete system including:
- Mathematical wireless channel modeling
- Simulation architecture
- Adaptive communication algorithms
- Performance analysis
- Graphical visualization
- Network topology generation
- Experimental evaluation

was developed from scratch as part of a Wireless Networks project.

## 🏫 Institution

Developed at:
- Vishwakarma Institute of Information Technology (VIIT Pune)

## 🌟 Project Goal

To simulate and analyze adaptive wireless communication systems capable of maintaining reliable connectivity and survivability under realistic indoor, interference-heavy, and hostile wireless environments.
