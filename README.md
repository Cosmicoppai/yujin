# Pi-hole Network Setup

This project implements a Pi-hole ad-blocking DNS server on a Raspberry Pi, securely exposed via router for trusted remote users. It includes strict firewall rules for enhanced security.

## Project Overview

<table>
<tr>
<td width="50%">

![Pi-hole Logo](https://github.com/user-attachments/assets/2bc244c8-5309-4d29-9500-d52ab96629a9)

</td>
<td width="500%">

```mermaid
graph TD
    A[Internet] <-->|Port Forwarding| B[Router]
    B <--> C[Firewall]
    C <--> D[Raspberry Pi with Pi-hole]
    B <--> E[Local Devices]
    E -.-> D
    F[Remote Devices] -.->|Secure Connection| C
```

</td>
</tr>
</table>

## Features

- Ad-blocking DNS server using Pi-hole
- Remote access for trusted users
- Firewall protection for enhanced security
- Raspberry Pi based setup

## Setup

[...]

## Usage

[...]
