Microcontroller Architecture Specification

## Goals
1. As many IO pins as we can have
2. Don't need a FP-unit
3. Availablity and long-term support
4. Low-power (neglible power-budget requirements)
5. Performance not as necessary

## STM32
The STM32 family of microcontrollers has been identified as a 
strong candidate for this application due to it being very well
supported, its wide selections, and its low cost.

## MCU Candidates
<table>
    <tr>
        <th>Microcontroller</th>
        <th>Processor</th>
    </tr>
    <tr>
        <td>STM32C0</td>
        <td>48MHz Cortex-M0+</td>
    </tr>
    <tr>
        <td>STM32G0</td>
        <td>64MHz Cortex-M0+</td>
    </tr>
    <tr>
        <td>STM32F0</td>
        <td>48MHz Cortex-M0</td>
    </tr>
    <tr>
        <td>STM32F1</td>
        <td>72MHz Cortex-M3</td>
    </tr>
    <tr>
        <td>STM32L0</td>
        <td>32MHz Cortex-M0+</td>
    </tr>
    <tr>
        <td>STM32L4</td>
        <td>80MHz Cortex-M4</td>
    </tr>
    <tr>
        <td>STM32L4+</td>
        <td>120MHz Cortex-M4</td>
    </tr>
</table>

