**

Protocol

A system of rules that allow two different devices to communicate. A protocol includes things such as rules, syntax, semantics, and possible error recovery methods

Radio Access Network (RAN) 

Connectes individual devices to other parts of the network through radio connections 

(SCADA)

A collection of software and hardware components that allows for supervision and control of devices locally and remotely. I also collects and processes data in real time

Distributed Control System (DCS)

A system that supervises an entire “plant” of many varying processes 

Home Subscriber Subsystem (HSS)

Subscriber device database that includes authentication, service assignments, and prioritization

Mobility Management Entity (MME)

Controls eNodeB functionality and supports services and prioritization and authentication of devices and services

Serving Gateway (S-GW)

Manages the routing of user data traffic

Policy, Charging and Rules Function (PCRF)

Manages service quality and policies

Packet Gateway (P-GW)

Manages user data streams and is the gateway to the internet. It contains many key functions including Network Address Translation (NAT) and deep packet inspection to identify the type of services for management

Operational Support System (OSS)

Responsible for: alarm and network performance, network service provisioning, network configuration, maintenance software updates

Instant Messaging System (IMS)

Service logic function for Voice and multimedia services (including mission critical services)

eNodeB

Radio connection management to field devices including access class prioritization

Spectrum Access System (SAS)

Serves as an automated frequency coordinator across the CBRS band. It provides dynamic allocation and management of spectrum resources that fall into 3 tiers

network

Computers and peripheral devices connected to each other to transmit and share data and information

Local Area Network (LAN)

A network that exists in a limited geographical location (a singular building, a singular campus etc)

Peer-to-peer network

There is not one devices that controls access to the network

Wide Area Network (WAN)

Covers a “large” geographical area and includes multiple LAN’s within it (example: a campus in California and its satellite campus in New York)

Types of Cables

-   Fiber optic
    
-   Coaxial cable
    
-   Twisted wire
    

Modulator-DeModulator (MODEM)

Converts signals from Analog to digital (or vice versa)

Internet connection methods

-   DSL
    

-   Cable modem
    
-   Satellite
    
-   Wireless
    
-   Fiber-to-home (pretty much unlimited bandwidth)
    

-   Wave division multiplex (single mode fiber) WDM
    
-   Dense wave division multiplex (single mode fiber, multi colored) DWDM
    

IP Address

A number that uniquely identifies each computer or the device on a network. It is a series of four number separated by a dot (12.34.567.89). A static IP address rarely changes while a dynamic IP address is temporary 

Http vs Https

Https is the secure version of http which is used for things such as online banking

latency

The delay from time sent to time received

jitter

The variance of latency (since latency will never be constant)

bandwidth

The capacity of data that can be sent. The variation in frequency that can be received, in telecom. 

Information to transmit

Three types:

-   Sound (2 way, usually) very sensitive to latency and jitter
    
-   Data (2 way, usually) sensitivity depends on application of data
    
-   Stream (1 way) only sensitive to bandwidth
    

Mission critical information

Information to transmit that is highly important (first responder communication during a disaster, data communication when a power line breaks etc)

geosync

A satellite staying over one geographical location on the earth. This is not good for sound communication because there is a 250 ms latency (can have a max of 200 ms)

leosync

Low earth orbit satellite. Satellites are moving fast around the earth so the signal has to be passed off to satellites in range (what Starlink is trying to do). These require many satellites so that there is always a connection

am

Amplitude modulation

Very prone to noise, went out of main stream use in the early 2000s

fm

Frequency modulation

Much clearer than am

pm

Phase modulation

QAM

Quadrature Amplitude modulation

Mapping out vectors onto a vector field of four quadrants (why not 8 quadrants? Too complicated? Too much processing power required?)

Phase + amplitude modulation

Used in all modern digital/analog modulation

Up to 4096 QAM used today. The higher the QAM the more information can be sent, but the signal to noise ratio is higher

PSK

Phase shift keying

Quantization noise

When you translate between digital and analog too much, there is a lot more noise which leads to the resulting analog coming out “metallic”. The quality highly degrades. 

General process

Analog -> digital -> modulation -> transmit -> demodulation -> digital -> analog

SN or SNR or S/N

Signal to noise ratio

FDD

Frequency Division Duplex

TDD

Time Division Duplex

MIMO

Multiple In Multiple Out

TCO

Total Cost of Ownership

LTE

Long Term Evolution (4G)

Carrier Aggregation

Aggregating spectrum across multiple carriers to make a system with greater broadband

Streetmicro

Putting a small radio cell on a street light or street poe in order to have service within a mile of the location

MBB

Mobile Broadband

EPC

Evolve Packet Core 

CCDM

Cloud Core Data Manager

CCPC

Cloud Core Policy Controller

CCSM

Cloud Core Subscription Manager

PCC

Policy and Changing Control Technology

CCRC

Cloud Core Resource Controller

PCG

Packet Core Gateway

DP

Domain proxy

CBSD

Citizens Broadband Radio Service Device (a CBRS device)











**