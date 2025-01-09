# udp-file-transfer-protocol
C program implementing reliable file transfer over UDP with full-duplex Stop and Wait protocol, supporting multimodal file transmission, logging, and error recovery
Title
Reliable File Transfer using UDP with Full-Duplex Stop and Wait Protocol

Description
This repository contains a C program for reliable file transmission over the UDP protocol using a naïve flow control mechanism with the Stop and Wait protocol. The program supports the transfer of multimodal files (text, image, audio, and video) and includes a logging mechanism for detailed reporting.

Features
Full-duplex communication using the Stop and Wait protocol.
Resume transfer functionality to continue from the point of interruption.
Support for multimodal files (text, images, audio, video).
Packet metadata includes the file name, sequence number, and acknowledgment number.
Detailed logging of:
List of uncommon files between the server and client.
Start and end time of transmission.
Connection interruptions and resume details.
Percentage of file uploaded when connection breaks.
Total packets lost and time-outs occurred.
