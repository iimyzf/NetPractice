<h1 align=center>
  <strong> NetPractice </strong>
</h1>

## 💡 About the project

> Since the project is a system administration related one, I'll document pretty much everything you need to know about the project from start to finish in this readme file, hope you find this usefull 😇

## What is an IP?

  An IP address stands for **Internet Protocol Address**, which is a set of rules for communication over the internet, such as sending emails, streaming videos, or connecting to a website, etc..., an IP address identifies a network or a device on the internet.

  An IP `(for example: 192.108.42.64)` got two important parts, which are:
  1. **The Network ID:** which is the first 3 numbers of the IP address -> `(192.108.42)`
  2. **The Host ID:** which is the last number of the IP address     -> `(64)`

## What are the types of an IP address?

  There are two important types of an IP address, which are:
  1. **Static IP address:** which stay permanent and it doesn't change, and it's used mostly for important equipement, such as (businesses, servers...)
  2. **Dynamic IP address:** which changes occasionally, and it's used for consumer equipement, such as (laptop, smartphone, tablet...)

## What is the purpose of the IP addresses?

  * The purpose of the IP address is to **handle the connection** between devices that send and recieve data all across the network.
  * The IP address uniquely **identifies every device on the internet,** without one there's no other way to contact them.
  * IP addresses allow computing devices to **communicate with destinations** like websites and streaming services, and they let websites know who is connecting.

## What is the difference between the IPv4 and the IPv6?

  * **IPv4:** deployed in the 1981, works with a 32-bits address, and has over `4.3 billion addresses` (which is a small amount of addresses compared to IPv6), so IP addresses must be reused and masked, and it uses Numeric Dot-Decimal Notation `(ex: 192.108.42.64)`, and you have to configure it manually.
  * **Ipv6:** deployed in the 1998, works with a 128-bits address, and has over `340 undecillion addresses` (which is 340 trillion, trillion, trillion, trillion [36 zeros]), so every device can have it's unique IP address, and it uses Alphanumeric Hexadecimal Notation `(ex: 2002:0de6:0001:0042:0100:8c2e:0370:7234)`, and it supports auto-configuration.

## What is TCP/IP?

  TCP/IP stands for **Transmission Control Protocol/Internet Protocol**, which is a set of rules that guide and allow computers to communicate on a network such as the internet.

## What is the difference between TCP and IP?

  * TCP and IP are two separate computer network protocols.
  * IP is the part that **obtains the address** which the data is sent to, while TCP is the part that is responsible for **data delivery** once that IP address has been found.

## How does TCP/IP exactly work?

  TCP/IP job is to divide the different communication tasks into layers, each layer has a different function. Data goes through four individual layers before it is recieved on the other end, TCP/IP then goes through these layers in reverse to reassemble the data and represent it to the reciepent.
  * The four layers of the TCP/IP model are:

    * Datalink Layer: also called the physical layer, is what handles the physical parts of sending and recieving data using the Ethernet, or WiFi, etc...
    * Internet Layer: also called the network layer, and it controls the movement of the packets around the internet.
    * Transport Layer: is what provides a reliable data connection between two devices. it divides the data into packets, knows the packets that are recieved from the other device, and it makes sure that the other device knows the packets it recieves.
    * Application Layer: is the group of the applications that requires a network communication, which is what the user typically interacts with, such as emails, and messaging, because the lower layer handles the details of communication, and there's no need for the applications to concern themselves with it.
