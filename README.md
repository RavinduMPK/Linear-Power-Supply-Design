# Linear Power Supply (LPS) Design

Welcome to the repository documenting the design process and analysis of a Linear Power Supply (LPS). This project aimed to create a robust and variable power supply capable of delivering reliable and adjustable output voltages within specific ranges.

## Overview

The Linear Power Supply was designed with the following specifications:

- **Input Voltage Range:** 14V - 18V
- **Output Voltage Range:** 6V - 12V
- **Maximum Output Current:** 100mA

## Design Considerations

### Pass Element Selection

Selecting the right pass element was crucial for ensuring efficiency and power handling capacity. The choice was based on calculated maximum power dissipation under full load conditions. We opted for the TIP120 power transistor due to its 2W maximum power dissipation rating, aligning well with our calculated requirements.

### Zener Diode Selection

A Zener diode was chosen to provide a stable voltage reference for regulation. To guarantee proper operation, the Zener voltage (Vz) had to be lower than 5.3V to accommodate the desired minimum output voltage. Our choice fell on the 1N4732 Zener diode, with a 4.7V Zener voltage.

### Passive Component Selection

The selection of passive components, such as resistor values and capacitors, was determined through meticulous analysis and calculations. Component values were chosen to meet desired performance characteristics and regulation requirements, as detailed in the project report.

## Performance Evaluation

### Line Variation

During testing, we assessed the LPS's response to variations in input voltage. Our measurements indicated a line variation of approximately 0.01V per 1V change in input voltage. This demonstrated the effectiveness of the design in maintaining stability across varying input conditions.

### Current Limiting

To enhance safety and prevent potential damage to the load or the power supply itself, a current limiting circuit was integrated. Output current was limited to 98mA, providing an added layer of protection against overloads.

## Documentation

For a comprehensive view of the design process, detailed circuit diagrams, component calculations, and performance analysis, refer to the project report included in this repository. The report offers insights into the reasoning behind component selections and provides a deeper understanding of the design's functionality.

### Graphical Representation

We have included graphical representations and plots within the project report, offering visual insights into key performance metrics and characteristics of the Linear Power Supply.

## Images

[Optional: Include images showcasing your LPS circuit, prototype, or measurement setups. Images can enhance understanding and engagement.]

## Contact Information

For inquiries, questions, or discussions about this Linear Power Supply design, feel free to reach out to us:
- Email: [your_email@example.com]
- LinkedIn: [Your LinkedIn Profile URL]

---

[Add any additional notes, acknowledgments, or credits you'd like to include.]

