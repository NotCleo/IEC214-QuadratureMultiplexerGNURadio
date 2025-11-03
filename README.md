# Quadrature-Multiplexing


To run GNU radio on my Ubuntu I had to run the .ova on VBox taken https://wiki.gnuradio.org/index.php/UbuntuVM
lsmod | grep kvm

sudo modprobe -r kvm_amd
sudo modprobe -r kvm


Overview

The Quadrature Carrier Multiplexing Transceiver project demonstrates the implementation of a QAM/QCM-based communication system designed to efficiently transmit multiple message signals over a single channel. By using quadrature carriers, the system achieves bandwidth conservation while maintaining signal integrity. The project utilizes GNU Radio for signal processing and Python for scripting and visualization, providing a practical exploration of digital communication principles.

This transceiver is capable of:

    Generating multitone message signals.
    Modulating them using QAM/QCM techniques.
    Multiplexing the signals onto quadrature carriers.
    Demodulating the received signals to recover the original messages.
    Visualizing the signal processing in real-time using GNU Radio Companion (GRC).

Features

    QAM/QCM Implementation: Efficiently modulates and multiplexes multitone signals using quadrature carriers.
    Bandwidth Conservation: Reduces the required bandwidth by leveraging QCM techniques.
    GNU Radio Integration: Uses GNU Radio for signal generation, modulation, and demodulation.
    Real-Time Visualization: Plots signal waveforms and spectra in real-time using GNU Radio Companion.
    Python Scripting: Automates signal processing and analysis with Python.

Requirements

    GNU Radio (version 3.8 or higher)
    Python (version 3.6+)
    Libraries:
        numpy (for numerical operations)
        matplotlib (for plotting, optional for custom visualizations)
        gnuradio (GNU Radio Python bindings, typically installed with GNU Radio)
    GNU Radio Companion (GRC): For running the provided flowgraphs.
    Operating System: Linux (recommended, e.g., Ubuntu 20.04+), macOS, or Windows (with WSL for best compatibility).
