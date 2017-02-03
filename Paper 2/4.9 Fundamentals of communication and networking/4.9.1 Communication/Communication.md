#Communication

> **You should be able to**:
>* Define serial and parallel transmission methods
>and discuss the advantages of serial over parallel
>transmission.
>* Define and compare synchronous and
>asynchronous data transmission.
>* Describe the purpose of start and stop bits in
>asynchronous data transmission.
> * Define:
>   * baud rate
>   * bit rate
>   * bandwidth
>   * latency
>   * protocol.
>* Differentiate between baud rate and bit rate
>* Understand the relationship between bit rate and bandwidth.

## Serial and Parallel Transmission
**Serial Transmission** -This is where bits are sent one at a time down a single wire.
**Parallel Transmission** - data is transmitted several bits a time using multiple wires.

> ###Key Differences Between Serial And Parallel Transmission
>
>1. Serial transmission requires a single line to communicate and transfer data whereas, parallel transmission requires multiple lines.
>2. Serial transmission used for long distance communication whereas, the parallel transmission used for shorter distance.
>3. Error and noise are least in serial as compared to parallel transmission. Since one bit follows another in Serial Transmission whereas, in Parallel Transmission multiple bits are sent together.
>4. Parallel transmission is faster as the data is transmitted using multiples lines whereas, in Serial transmission data flows through a single wire.
>5. Serial Transmission is full duplex as the sender can send as well as receive the data whereas, Parallel Transmission is half duplex since the data is either sent or received.
>6. Serial transmission cables are thinner, longer and economical in comparison with the Parallel Transmission cables.
>7. Serial Transmission is reliable and straightforward whereas, Parallel Transmission is unreliable and complicated.

## Synchronus and Asynchronus Data Transmission
**Synchronus** - Data transmission between two devices that shares a common clock signal.
The system clock is used by sender to control the transmission rate to be in time with the device or computer receiving the signal.

**Asynchronus** - Data transmission between two devices that does need to share a common clock signal; does not require permanent synchronisation. Instead use start bit and stop bits.
>### Start Bits and Stop Bits in Asynchronus
>*  **Start Bits** – Allows the receiver clock to be synchronised to the same rate as the sender
>*  **Stop Bits** - Indicates that the data has arrived and are able to be handled by the processor.

##Keywords
| | Description|
|:-:|:---------|
|Baud rate | number of bits per signal change|
|Bit Rate | Number of bits per second |
| Bandwidth | Range of frequencies that can be transmitted |
| Latency | Time delay that occurs when transmitting data between devices |
|Protocol| Set of Rules |
