# Project Name

Ethernet Packet Parser

## Prerequisites

Make sure you have a C++ compiler installed. You can install `g++` on Ubuntu using the following command:

```bash
sudo apt-get update
sudo apt-get install g++
```

## How to Compile and Run
Clone the repository:

```bash
git clone <repository_url>
cd <repository_directory>
```
## Compile the C++ program:

```bash
g++ -o tst main.cpp EthernetPacket.cpp RawEthernetPacket.cpp PrintPacketVisitor.cpp EcpriEthernetPacket.cpp
```
This command compiles the C++ source files into an executable named `tst`.


### On Windows:

```bash
g++ -o tst.exe main.cpp EthernetPacket.cpp RawEthernetPacket.cpp PrintPacketVisitor.cpp EcpriEthernetPacket.cpp
```
### On Linux:

```bash
g++ -o tst main.cpp EthernetPacket.cpp RawEthernetPacket.cpp PrintPacketVisitor.cpp EcpriEthernetPacket.cpp
```
## Run the program:

### On Windows:

```bash
./tst.exe <input_file> <output_file>
```
### On Linux:

```bash
./tst <input_file> <output_file>
```
