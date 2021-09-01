# Physical layer

## Definition

Physical layer is the lowest layer of the OSI reference model. It is responsible for sending bits from one computer to another. This layer is not concerned with the meaning of the bits and deals with the setup of physical connection to the network and with transmission and reception of signals.

![Physical Layer in OSI Networking System](http://fiberbit.com.tw/wp-content/uploads/2013/07/physical-layer-in-osi-model.png)

## 

## Functions of Physical layer

- **Representation of Bits:** Data in this layer consists of stream of bits. The bits must be encoded into signals for transmission. It defines the type of encoding i.e. how 0's and 1's are changed to signal.

- **Data Rate:** This layer defines the rate of transmission which is the number of bits per second.

- **Synchronization:** It deals with the synchronization of the transmitter and receiver. The sender and receiver are synchronized at bit level.

- **Interface:** The physical layer defines the transmission interface between devices and transmission medium.

- **Line Configuration:** This layer connects devices with the medium: Point to Point configuration and Multipoint configuration.

- **Topologies:** Devices must be connected using the following topologies: Mesh, Star, Ring and Bus.

- **Transmission Modes:** Physical Layer defines the direction of transmission between two devices: Simplex, Half Duplex, Full Duplex.

- Deals with baseband and broadband transmission.

  

  ![Physical Layer in ISO-OSI Model](https://static.studytonight.com/computer-networks/images/Figure28-1.png)

## Protocol

### 1. Ethernet (802.3)

According to Wikipedia, Ethernet is a computer networking technologies commonly used in LANs, MANs, and WANs. In other words, Ethernet is a form of technology that helps devices such as laptops and computers connect to the Internet and transfer data to other devices.

![Ethernet là gì, khái niệm giao thức, cáp, kênh và cổng Ethernet](https://yeutrithuc.com/wp-content/uploads/2019/11/ethernet-la-gi.jpg)

1.1. Traditional Ethernet

The original Ethernet standard was developed in 1983 and had a maximum speed of 10 Mbps over coaxial cable. The Ethernet protocol allows for bus, star, or tree topologies, depending on the type of cables used and other factors.

1.2. Fast Ethernet

The Fast Ethernet protocol supports transmission up to 100 Mbps. Fast Ethernet requires the use of different, more expensive network concentrators/hubs and network interface cards. In addition, category 5 twisted pair or fiber optic cable is necessary. Fast Ethernet standards include:

- 100BaseT    - 100 Mbps over 2-pair category 5 or better UTP cable.
- 100BaseFX  - 100 Mbps over fiber cable.
- 100BaseSX  - 100 Mbps over multimode fiber cable.
- 100BaseBX - 100 Mbps over single mode fiber cable.

1.3. Gigabit Ethernet

Gigabit Ethernet standard is a protocol that has a transmission speed of 1 Gbps (1000 Mbps). It can be used with both fiber optic cabling and copper.

- 1000BaseT    - 1000 Mbps over 2-pair category 5 or better UTP cable.
- 1000BaseTX  - 1000 Mbps over 2-pair category 6 or better UTP cable.
- 1000BaseFX  - 1000 Mbps over fiber cable.
- 1000BaseSX  - 1000 Mbps over multimode fiber cable.
- 1000BaseBX  - 1000 Mbps over single mode fiber cable.

**Advantages**

- **Signal stability**: Ethernet uses wires to connect the devices to the network modem, so the signal will always be stable.
- **Security**: With a wired connection, you can easily control how many people want to connect to your local network.

**Disadvantages**

- **Cost**: The bigger and more complex your wired LAN, the higher your costs.
- **Available ports**
- **Mobility**: Ethernet is not suitable for mobile devices such as smart phone and tablet.

### 2. Wifi (802.11)

Wi-Fi is a wireless network technology that allows devices such as computers (laptops and desktops), mobile devices, and other equipment (printers and video cameras) to interface with the Internet without direct cable connection. It allows these devices--and many more--to exchange information with one another, creating a network.

<img src="https://bonlaptop.com/wp-content/uploads/2016/12/wifi1.jpg" alt="Laptop Lenovo G40-70 không bắt được wifi | GIA TÍN Computer" style="zoom:50%;" />

**Advantages**

- **Convenience**: Wi-Fi makes it possible for devices to connect to the internet wherever they can locate a Wi-Fi signal. Those locations are increasing all the time.
- **Productivity**: Wi-Fi can keep workers in near-constant contact with the office and each other.
- **Expandability**: A new devices can connect to the network easily
- **Mobility**: Users aren't tied to the office or home for their communication needs.

**Disadvantages**

- **Range**: A Wi-Fi signal reaches a limited range, which may not cover your entire home or office.
- **Security**: Because wireless signals travel through the air, they can be intercepted. Using [encryption technology](https://www.lifewire.com/introduction-to-network-encryption-817993) minimizes the danger.
- **Disruption**: Large metal objects, such as a refrigerator, can block a Wi-Fi signal in your home. A microwave oven can disrupt the signal.

### 3. Another protocols

3.1. RS232

<img src="https://huphaco.vn/wp-content/uploads/2020/03/rs232.jpg" alt="Giao tiếp RS232 là gì? – Ưu nhược điểm của cổng RS232 là gì?" style="zoom: 25%;" />

3.2. USB

<img src="https://mesidas.com/wp-content/uploads/2020/11/USB-A.jpg" alt="USB là gì? Cùng tìm hiểu về USB A-B-C Mini Micro 2.0 3.0" style="zoom:50%;" />