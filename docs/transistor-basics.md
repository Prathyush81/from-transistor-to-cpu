# Transistor Basics

## What is a Transistor?

A transistor is a semiconductor device that can act as an electronic switch or amplifier.

In this repository, the BC547 transistor is used primarily as a switch to build digital logic circuits.

---

## BC547 Overview

| Parameter                         | Value  |
| --------------------------------- | ------ |
| Type                              | NPN    |
| Package                           | TO-92  |
| Maximum Collector Current         | 100 mA |
| Maximum Collector-Emitter Voltage | 45 V   |

### BC547 Pinout

```text
Flat side facing you

Collector   Base   Emitter
    |         |        |
    C         B        E
```

> Always verify the pinout using the transistor datasheet before wiring your circuit.

---

## How an NPN Transistor Works

A small current flowing into the base allows a larger current to flow from collector to emitter.

Think of the base as a control signal:

* Base LOW → Transistor OFF
* Base HIGH → Transistor ON

This switching behavior makes transistors useful for digital electronics.

---

## Transistor as a Switch

### OFF State (Cutoff Region)

* No base current
* Collector-emitter path is open
* Current cannot flow

```text
Input = 0
Transistor = OFF
```

### ON State (Saturation Region)

* Base current present
* Collector-emitter path conducts
* Current flows

```text
Input = 1
Transistor = ON
```

---

## Why Logic Gates Can Be Built from Transistors

Digital circuits use only two states:

| Logic Level | Voltage |
| ----------- | ------- |
| 0 (LOW)     | 0V      |
| 1 (HIGH)    | 9V      |

Since a transistor can switch between ON and OFF states, it can represent binary values and implement logic functions.

---

## Key Terms

### Collector (C)

Receives current from the power source and passes it through the transistor when it is ON.

### Base (B)

Controls whether the transistor is ON or OFF.

### Emitter (E)

Provides the path for current to leave the transistor.

### Saturation

The transistor is fully ON and conducts current.

### Cutoff

The transistor is fully OFF and blocks current flow.

---

## Why Use BC547 Transistors?

The BC547 is:

* Inexpensive
* Easy to obtain
* Suitable for low-power circuits
* Commonly used for learning electronics
* Ideal for transistor-based logic gate projects

---

## Transistor Logic in This Repository

This repository uses BC547 transistors to build:

* NOT Gates
* NAND Gates
* AND Gates
* NOR Gates
* OR Gates
* XOR Gates
* Half Adders
* Full Adders
* Sequential Logic Circuits
* Simple CPU Components

---

## What You Will Learn

By completing the projects in this repository, you will learn:

* Transistor switching
* Digital logic fundamentals
* Boolean algebra implementation
* Combinational logic circuits
* Sequential logic circuits
* Computer architecture fundamentals

---

## Further Reading

* Truth Tables
* Boolean Algebra
* Logic Gates
* Flip-Flops
* Registers
* Counters
* Computer Architecture

---

This document serves as a quick introduction to transistor operation and provides the foundation required to understand the projects contained in this repository.
