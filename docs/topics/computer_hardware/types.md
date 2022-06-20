<style>
    @import url('../../scss/tooltip.css');
    
    @keyframes floating {
	    0% { transform: translateY(0); }
	    50% { transform: translateY(-16px); }
	    100% { transform: translateY(0); }
    }

    .images {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
        align-items: center;
        margin: 1em 1em 1em 1em
    }

    .imagebox {
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        margin: 0.2em auto;
        max-width: fit-content;
        padding: 0;
    }

    .imagebox span {
        font-size: 1.4em;
        color: #999;
        animation: floating 6s ease-in-out infinite;
    }

    .imagebox img {
        width: 10em;
        height: 10em;
        border-radius: 5%;
        animation: floating 6s ease-in-out infinite;
    }

    .small {
        width: 5em;
        height: 5em;
    }
    .tag {
        background-color: #832257;
        padding-left: 0.3em;
        padding-right: 0.3em;
        padding-top: 0.2em;
        padding-bottom: 0.2em;
        border-radius: 10em
    }
</style>
<span class="tag">Computer Hardware</span>

# Basic Hardware of the Computer System

## Input

**Input** is any data or instruction that is inserted into the computer system. Within the computer system, there are specialized devices that can be used to enter data into the computer system, known as **INPUT DEVICES**.

Some examples of input devices include:

<div class="images">
    <div class="imagebox">
        <span>Keyboard</span>
        <img src="media/examples/keyboard.jpg"></img>
    </div>
        <div class="imagebox">
        <span>Mouse</span>
        <img src="media/examples/mouse.jpg"></img>
    </div>
    <div class="imagebox">
        <span>Microphone</span>
        <img src="media/examples/microphone.jpg"></img>
    </div>
</div>

Input devices are split into 3 categories, based on how they deliver data into the computer system:

1. **Key Input**

?> These devices have keys which are utilized to enter the data. The only device of this type is the **keyboard**, which has rows of keys which are pressed to input alphanumeric characters, or to carry out a particular function of the computer.

2. **Point and Draw**

?> These devices are used to point to, select, or click a particular object or text found on the computer screen. They can also be used to draw. Some examples include, **mouse**, **joystick**, **touchpad**,**trackball**, etc.

3. **Source Data Automation**

?> These devices input audio, video or source document(s) directly into the computer in a machine-readable format without the use of the keyboard or mouse. For example: **Scanner**, **Barcode Reader**, **Digital Camera**, **Microphone**

## Processing

Processing hardware consists of the electronic circuitry inside the computer rhat runs programs and directs the activities of the entire computer. It controls all other hardware. The main element of this type of hardware is the CPU (Centrall Processing Unit), also known as the processor or microprocessor.

### CPU

Considered to be the brain of the computer for it performs all calculations and coordinates all activities, often the factor that mostly determines how powerful a computer is.

The speed of processing is measured in megaherts (MHz) or Gigahertz (GHz), which the higher the amount, the faster the processing speed.

#### Components

- The **Control Unit (CU)**

?> Responsible for all control signals in the processor.

- The **Arithmetic Logic Unit (ALU)**

?> The ALU is responsible for performing all mathematical, logical and decision operations in a computer

- Registers

?> High speed storage locations that temporarily hold data and instructions that are being processed by the central processing unit

<div class="images">
<img src="media/examples/cpu.webp" title="Central Processing Unit (intel)"></img>
</div>

## Storage

This is any type of computer hardware which stores data or information, being separated into 2 types:

- Primary Storage
- Secondary Storage

### Primary Storage

Also known as **internal memory** and **main memory**, refers to memory used to store instructions and data to be executed and manipulated by the CPU. This type of storage is <b>volatile</b>, meaning the data will be lost if the computer loses power. The data is stored for short periods of time.

### Examples of Primary Storage

<style>
    .rightside {
        float: right;
        margin: 0 0 1em 1em;
    }
</style>

#### RAM

<img class="rightside" title="RAM" src="media/examples/ram.png"></img>

- Temporary, volatile storage. Holds data for processing, instructions for processing the data and information to be output.
- This type of primary storage allows data to be retrieved at random from anywhere in a RAM chip and is the most common type of memory in computers. 
- It is temporarily installed on the motherboard and the contents change every time the computer is booted.

#### ROM

<img class="rightside" title="ROM chips" src="media/examples/rom.png"></img>

- This type of primary storage allows information crtical to a computer's operation to be stored in a permanent, **non-volatile** form. 
- It is read-only, meaning the data (that is determined by the manufacturer) can be retrieved but not changed.
- ROM is permanently installed on the motherboard by its manufacturer at the factory, with the programs on ROM chips called firmware, which may include: 
  - Utility programs like anti-virus, and disk management programs
  - Part of the operating system needed to start up the program.

### Secondary Storage

Also known as **auxiliary storage**, refers to memory that that is used to store information for extended periods of time. This type of storage is **non-volatile**, meaning that the data remains when the computers power is lost.

There are 3 types of secondary storage.
- **Optical Storage**
- **Mechanical Storage**
- **Solid State Storage**