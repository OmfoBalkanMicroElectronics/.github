## OBM — OmfoBalkanMicroElectronics


Welcome to **OBM (OmfoBalkanMicroElectronics)**, an embedded systems and hardware research organization focused on exploring, developing, and documenting microcontroller-based technologies.


## Our Story


OBM started from a simple idea: two electronics enthusiasts from Türkiye working with **STM32** microcontrollers and experimenting with embedded systems.


Our first project ideas and designs were created under the name **OCM32**, where we explored STM32-based concepts, including custom development board and Nucleo-style shield designs. Over time, we decided to turn our experiments into a proper organization where we could share our work, improve our skills, and document our discoveries.


The name **OmfoBalkanMicroElectronics** was originally created as a joke, inspired by OMFO, a Balkan music project that is one of our favorite groups. What started as a fun name eventually became the identity of our growing embedded systems journey.


## What We Do


Our work focuses on:




• Embedded systems development


• Microcontroller programming


• Firmware development and modification


• Hardware research and reverse engineering


• Documentation of undocumented platforms


• Development tools and experimental hardware




Our main platforms include:




**STM32** (including STM32F7 and RTOS-based projects)


**Microchip PIC** microcontrollers


**JieLi (AC69xx series)** audio platforms


**NationalChip / GuoXin GX series**


Other embedded platforms encountered during research




## Current Main Projects

OBM will contain many repositories covering different experiments, research, and development efforts. Since it is not practical to list every project here, this section highlights some of our main and most active projects.

## MagicPIC
### Maintainer(s)
**Barbaror4**
**MeteÖnelge**

**MagicPIC** is our PIC-based development project focused on exploring the simplicity and capabilities of classic PIC microcontrollers.


The project is based around the **PIC16F886** and aims to create custom boards, experiments, and learning resources. Starting from a simple microcontroller platform, MagicPIC may grow into a larger ecosystem over time.

Project Status: MagicPIC is currently one of our main development focuses, as embedded systems are our primary area of interest and curiosity. We aim to expand the project through hardware development, software experiments, and documentation. Contributions, ideas, and feedback are always welcome.

## STM32F746G-DISCO Zephyr RTOS MP3 Player

### Maintainer(s)

**Barbaror4**


An advanced embedded audio project based on the **STM32F746G-DISCO** development board.

The goal of this project is to create a feature-rich MP3 player featuring:

- STM32F746 microcontroller
- Zephyr RTOS
- Custom audio handling
- A modern graphical user interface

The repository is currently private while the core architecture and software foundation are being refined.

Project Status: I am currently focusing my development efforts on the MagicPIC platform and other embedded systems research. As a result, this project is temporarily paused. Development will continue once a stable roadmap is established, after which the repository will be made public.


## JieLi AC6925 Research & Firmware Development
### Maintainer(s)

**Barbaror4**

One of our major research areas has been the **JieLi AC6925** platform.


Work includes:




- Developing custom peripheral code


- Software I2C implementations


- Driving displays such as SSD1306/SSD1315-based OLEDs


- Working with 4x20 OLED/LCD interfaces


- Firmware modification and analysis


- Exploring boot modes and firmware loading methods


- Creating custom hardware tools for development and testing




The goal is to better understand and document these commonly used but poorly documented audio SoCs.

Project Status: I am currently refining the research and documentation around the JieLi platform. This project will include detailed documentation, examples, and testing resources to make experimentation and prototyping easier. Contributions are always welcome, especially in this area, as community knowledge can greatly help in understanding and preserving these often overlooked embedded platforms.

## NationalChip / GuoXin Research
### Maintainer(s)

**Barbaror4**
**MeteÖnelge**

We also work with **NationalChip (GuoXin GX series)** platforms.


Research includes:




UART communication analysis


GXDownloader interaction


Boot communication research


Firmware research and preservation




Our current research has reached successful communication with GX platforms, including UART handshaking, with further firmware analysis ongoing.

Project Status: We are actively researching NationalChip-based platforms. MeteÖnelge has access to a GX-based STB receiver currently under investigation, while Barbaror4 is researching various STB boards, including hardware based around the AT1511S, which was identified through reverse engineering as a rebranded NationalChip GX6101D platform. Contributions, documentation, and additional hardware information are always welcome, as community research helps preserve and understand these lesser-documented embedded systems.

## Reverse Engineering & Hardware Research


A major part of OBM is understanding hardware that lacks proper documentation.


Examples include:




Reverse engineering unknown chips and boards


Identifying undocumented ICs through pin analysis


Hardware investigation of consumer electronics




One example was the investigation of the **AT1511S**, where reverse engineering revealed it was actually based around a **NationalChip GX6101D** platform.


## Our Goal


OBM exists to learn, experiment, and share knowledge.


We believe that even obscure hardware, forgotten platforms, and undocumented chips can be understood through curiosity, testing, and collaboration.


From simple PIC experiments to advanced embedded reverse engineering, our goal is to keep exploring the world of electronics.


Welcome to OBM.


