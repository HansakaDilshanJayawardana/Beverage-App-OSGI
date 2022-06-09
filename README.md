# Beverage-App-OSGI

## Group Details
Member Details:
| Name | Student ID | Username |
| ---- | ---------- | -------- |
| Rupasinghe KASS | IT19953052 | shash1996-san |
| Mendis BNV | IT19047720 | NarthanaVeenavi |
| Sajani YN | IT19953984 | NethmaSajani |
| Jayawardana GVHD | IT19972176 | HansakaDilshanJayawardana | 

## System Introduction
In this project we have created a Beverage Management System based on OSGi (Open-Source Gateway Initiative) framework with producer-consumer implementation. Here we implement 4 producers and 4 consumers. Here the following functions can be fulfilled as producers (Beverage server, Bill server, Employee server and Stock server). Here Beverage Manager, Cashier, Admin, and Stock Manager act as consumers. To use all these features, we need to import and install all the packages. Here to import packages initially we need to import the OSGi framework package to producer manifest and consumer manifest. After that when building the connection between the producer and consumer first we have to export producer packages in the producer manifest. And, then in the consumer manifest we need to import all the exported packages of producer.

Rupasinghe KASS - Employee Producer & Beverage Shop Admin Subscriber | Mendis BNV - Stock Publisher & Stock Manager Subscriber | Sajani YN - Beverage Producer & Beverage Manager Subscriber | Jayawardana GVHD - Bill Item Producer & Cashier Subscriber

## Technologies
Language - Java | IDE - Eclipse | Integrate Technology Service - GitHub
