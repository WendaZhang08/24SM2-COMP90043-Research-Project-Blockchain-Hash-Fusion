# Blockchain & Hash Function Research Project

This repository contains the implementation and analysis code for the **COMP90043 Cryptography and Security research project "The Crucial Role of Hash Functions in Blockchain: The Fusion of Cryptography and Decentralization"**.

## Project Overview

This project explores the critical role of cryptographic hash functions, particularly **SHA-256**, in ensuring the security and data integrity of decentralized blockchain systems. We implement a **small-scale blockchain** to demonstrate key concepts and analyze the performance of various hash functions.

## Key Features

- Implementation of a **basic blockchain structure**
- Demonstration of **Proof of Work (PoW)** consensus mechanism
- Visualization of blockchain structure and **tampering** effects
- **Performance comparison** of different hash functions (SHA-256, SHA-224, SHA-1, MD5)

## File Structure

- `codeartifact.py`: Main Python script containing the blockchain implementation and analysis code
- `Dockerfile`: Configuration for creating a Docker container to run the project
- `requirements.txt`: List of Python dependencies

## Setup and Running

### Prerequisites

- Docker installed on your system

### Running the Program

1. Pull the Docker image:

``` bash
$ docker pull damonzzz/blockchain-demo:latest
```

2. Run the container:

``` bash
$ docker run -it --rm damonzzz/blockchain-demo:latest
```

## Implementation Details

The project includes:
- Basic blockchain structure with blocks and transactions
- SHA-256 hash function integration
- Proof of Work consensus mechanism
- Blockchain visualization
- Performance analysis of different hash functions

## Research Findings

- Demonstrated the **tamper-evident** nature of blockchain using **SHA-256**
- Analyzed the performance of various hash functions in different data scenarios
- Explored the relationship between **hash functions**, **blockchain security**, and **decentralization**

## Future Work

- Implement more advanced attack simulations (e.g., 51% attack, Sybil attack)
- Explore **quantum-resistant** cryptographic algorithms
- Investigate more efficient consensus mechanisms

## Contributors

- [Langze Lu](https://github.com/LangzeL) - langzel@student.unimelb.edu.au - 1185039
- [Wenda Zhang](https://github.com/WendaZhang08) - wendaz@student.unimelb.edu.au - 1126164
- [Yilin Chen](https://github.com/6188145) - yilinc6@student.unimelb.edu.au - 1239841

## Acknowledgements

This project was completed as part of the COMP90043 Cryptography and Security course at the University of Melbourne, under the guidance of Prof. Udaya Parampalli.