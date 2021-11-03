# Conformance Tester for TAGs EPC-GEN2 UHF RFID

- **Students:** Alexandre Almeida Edington / Bruno Signorelli Domingues / Lucas Leal Vale / Rafael Dos Santos
- **Course:** Computer Engineering
- **Semester:** 8
- **Teacher:** Rafael Corsi Ferrão
- **Contato:** alexandreae@al.insper.edu.br / brunosd1@al.insper.edu.br / lucaslv1@al.insper.edu.br / rafaels6@al.insper.edu.br / rafael.corsi@insper.edu.br
- **Year:** 2021

## About

This project aims to develop an equipment capable of performing a series of tests on RFID TAGs, based on the communication protocol "EPC-GEN2 UHF RFID" [1]. The project simplifies the development of  new TAGs that conform to the defined protocol, being able to assert wether the tag satisfies the requirements of said protocol, and also wether the TAG itself is working as intended.

### Insper

This project is being developed by four computer engineering students at "Insper Instituto de Ensino e Pesquisa" [2], together with "Indago Services Inc." [3]. As part of their completion of course work, the students must communicate with their selected company to identify a problem the company currently has and work together to find and implement a solution to it. For each group of students there is also a teaches that acts as a mentor and aids the group with matters of communication, organization, meetings, and project and report feedbacks.

### Indago Devices Inc.

Indago Devices Inc. is a startup that has its headquarters in the city of Birmingham Alabama, US, and works in the field of development and study of electronics. Despite having few employees, it seeks to innovate in the electronics market, specifically in the development of systems that communicate through RFID. They had already been communicating with Insper in the previous semester, and also another group of students who planned to do a similar project. This semester they decided to request a conformance tester to help develop RFID TAGs. One of the driving points of the project is that currently there is no similar sofware avaliable on open source for the RFID community, so it could impact not only their company, but also the worldwide RFID development community.

## Project Overview

The main objetive of this project is to develop and assemble a conformance tester for RFID TAGs composed of a FPGA [4] where a microcontroller will be implemented and an IP Core for communication with the DUT (device under testing). This device then shall be able to run a series of tests as a READER interacting with a TAG through the EPC-GEN2 protocol, analysing if the TAG works as intended and complies with the requirements of the protocol.
The tests will be implemented using C, allowing for a large amount of tests to be made that target different aspects of the TAG's process, independently evaluating most of them. Also, it will be possible to customize the tests or develop new ones should the user need to do so.
This project does not make use of RFID communication, nor does it intend to test wether the TAG is able to communicate through it. Given the compleity of communicating through radio waves, the group and the teacher agreed to not cover those points in this project. Therefore, the device, TAG and computer shall be connected by cables. 


## Getting Started

### Tools

- **Hardware:** DE10-Standard e acessórios
- **Softwares:** Quartus 18.01
- **Documentos:** [DE10-Standard_User_manual.pdf](https://github.com/Insper/DE10-Standard-v.1.3.0-SystemCD/tree/master/Manual)

### Cloning

### Testing / Runninng

### How to collaborate

## Documentation

### Specification

### Hardware

### Firmware

### References

1. EPC UHF Gen2 Air Interface Protocol.

<https://www.gs1.org/sites/default/files/docs/epc/Gen2_Protocol_Standard.pdf>

Accessed on: 16/08/2021.

2. Insper Instituto de Ensino e Pesquisa.

<https://www.insper.edu.br/>

Accessed on: 16/08/2021.

3. Indago Devices Inc..

<https://indagodevices.com>

Accessed on: 16/08/2021.

4. FPGA Intel.

<https://www.intel.com.br/content/www/br/pt/products/programmable.html>

Accessed on: 23/08/2021