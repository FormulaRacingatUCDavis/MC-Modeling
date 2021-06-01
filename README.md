# Homebrew Motor Controller
#### Table of Contents
[Notes](#Meeting-Notes)
[Progress](#Future-Concerns)
# Meeting Notes 

| June | 1 | 2021 |
| :----- |:--- | :--- |

### Goal: Develop a single board for inverter and motor control ( X Volts) :+1:
 
## Select Operating point/Motor (Conrad)

- [ ] Make Design Matrix

- Cost is determining factor
  - Find cheapest analogy to our current motor
    - Encoderless? 
    - [ ] ask Elliot, Tucker
  - LV (0 - 12V)
    - Safety, cheaper
  - HV (48V +)
    - Maybe more realistic?
  - TestPack Voltage?

## Select Microcontroller/Launchpad (Leo)
	Metrics
		- COST
		- Speed
		- High frequency PWM
		- High speed ADC
	TI - suitable chip-line
		- Piccolo

# Future Concerns

Select Driving Circuitry
- FET/IGBT
- Driving IC

How To Quantify Performance?

Board design for high frequency performance?