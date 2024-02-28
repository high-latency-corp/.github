# QUIC Performance Analysis in Satellite Communications README

## Overview

This repository contains the research and analysis of the performance of the QUIC protocol in satellite communications, focusing on various congestion control mechanisms. The study investigates how QUIC, a protocol designed to improve upon TCP's limitations, performs over satellite connections, known for their high latency and loss rates. The research compares several congestion control algorithms, including CUBIC, BBR, Hybla, and LEDBAT, to determine their impact on QUIC's efficiency and reliability in satellite networks.

## Introduction

The exponential growth of internet connectivity has propelled advancements in network protocols to ensure reliable and efficient user experiences. QUIC (Quick UDP Internet Connections) emerges as a significant enhancement over TCP, offering reduced connection establishment time, improved multiplexing, and built-in security features. This research delves into QUIC's potential to enhance satellite internet connections, examining its interaction with different congestion control algorithms in the unique environment of satellite communications.

<!-- ## Repository Structure

- `/docs` - Documentation and papers related to QUIC and its performance in various network settings.
- `/src` - Source code for simulation and real-world testbed experiments.
- `/results` - Collected data and analysis results from the conducted experiments.
- `/tools` - Utilities and scripts used for setting up experiments and analyzing data. -->

## Experiment Setup

The research comprises two primary experiments:

1. **Simulated Experiment**: Using the NS-3 network simulator to model satellite connections and evaluate QUIC's performance with different congestion control algorithms.
2. **Real-World Experiment**: Establishing a testbed that mimics satellite communication conditions to measure and compare the performance of QUIC under various congestion control mechanisms.

## Key Findings

- Initial results indicate that QUIC's performance in satellite networks is significantly influenced by the choice of congestion control algorithm.
- Algorithms like Hybla and LEDBAT, designed for high-latency environments, show promising improvements in QUIC's efficiency over satellite links.
- The research highlights the potential for QUIC, coupled with appropriate congestion control strategies, to enhance the reliability and speed of satellite internet services.

<!-- ## How to Use This Repository

- To replicate the experiments, follow the setup instructions in `/docs/setup.md`.
- The source code for the simulation and testbed experiments can be found in `/src`.
- Analyzed data and results are available in `/results` for further exploration and comparison.

## Contributing

We welcome contributions from the research community. Whether it's adding new congestion control algorithms, enhancing simulation models, or providing insights into the data, your input is valuable. Please refer to `CONTRIBUTING.md` for more details on how to contribute. -->
<!-- 
## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.

## Acknowledgments

This research was conducted at the University of Connecticut's School of Computing. We extend our gratitude to all collaborators and contributors who have provided insights, feedback, and support throughout this study.

For more information or to get involved, please contact the primary authors through the provided email addresses in the publication. -->

