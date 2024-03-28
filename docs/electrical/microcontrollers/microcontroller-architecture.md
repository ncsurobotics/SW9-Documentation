## Goals & Requirements
1. As many IO pins as we can have
2. Don't need a FP-unit
3. Availablity and long-term support
4. Low-power (neglible power-budget requirements)
5. Performance not as necessary

The STM32 family of microcontrollers has been identified as a
strong candidate for this application due to it being very well
supported, its wide selections, and its low cost.

## Candidates

| Microcontroller | Processor        |
|-----------------|------------------|
| STM32C0         | 48MHz Cortex-M0+ |
| STM32G0         | 64MHz Cortex-M0+ |
| STM32F0         | 48MHz Cortex-M0  |
| STM32F1         | 72MHz Cortex-M0  |
| STM32L0         | 32MHz Cortex-M0+ |
| STM32L4         | 80MHz Cortex-M4  |
| STM32L4+        | 120MHz Cortex-M4 |


The current front-running candidate is the [STM32L051C6T6](https://estore.st.com/en/stm32l051c6t6-cpn.html), due to the following:

- ARM Cortex M0+
- 32KB Flash Memory
- 32 MHz
- Up to 51 GPIO pins
- 88&#956;A/MHz in run mode
- 2 I2C Busses
- 1 UART
- [Guaranteed support until 2033](https://www.st.com/content/st_com/en/about/quality-and-reliability/product-longevity.html#10-year-longevity)

