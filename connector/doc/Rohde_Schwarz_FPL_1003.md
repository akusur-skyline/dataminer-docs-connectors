---
uid: Connector_help_Rohde_Schwarz_FPL_1003
---

# Rohde Schwarz FPL1003

The Rohde Schwarz FPL1003 is a compact spectrum analyzer with the functionality of high-end instruments. It operates at frequencies from 5 kHz to 3 GHz and can analyze signals with an analysis bandwidth of 12.8 MHz (standard) or 40 MHz (with option), with an optional tracking generator available up to 3 GHz. This connector communicates with the spectrum analyzer using serial communication (TCP/IP).

## About

### Version Info

| Range | Key Features                                                             | Based on | System Impact |
|-----------|-----------------------------------------------------------------------------|--------------|-------------------|
| 1.0.0.x   | Initial version.  | -            | -                 |

### Product Info

| Range     | Supported Firmware     |
|-----------|------------------------|
| 1.0.0.x   | -                      |

### System Info

| Range     | DCF Integration     | Cassandra Compliant     | Linked Components     | Exported Components     |
|-----------|---------------------|-------------------------|-----------------------|-------------------------|
| 1.0.0.x   | No                  | Yes                     | -                     | -                       |

## Installation and configuration

### Creation

#### GPIB main connection

This connector uses a serial connection and requires the following input during element creation:

GPIB CONNECTION:

- Interface connection:

  - **Device address**: The polling device address of the device.
  - **I/O API**: The I/O API of the device.

## Usage

On the **Spectrum Analyzer** page, you can find the spectrum analyzer user interface. For more information on how to work with this, refer to [Working with spectrum analyzer elements](https://aka.dataminer.services/Working_with_spectrum_analyzer_elements).

On the **General** page, you can find device information such as the Manufacturer, Model, Serial Number, Firmware Version and Display Status. The **DMS Spectrum Measurements** toggle button allows you to put the spectrum analyzer in automatic sweep mode.
