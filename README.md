# Homebrew Motor Controller
#### Table of Contents
[Notes](#Meeting Notes)
[Progress](#Future Concerns)
# Meeting Notes 
### Goal: Develop a single board for inverter and motor control ( X Volts) :+1:

| June | 1 | 2021 |
| :----- |:--- | :--- |

**Select Operating point/Motor _(Conrad)_**

- [ ] Make Design Matrix
- [ ] testing
- [ ] testing 2

- Cost is determining factor
  - Find cheapest analogy to our current motor
  - Encoderless? - ask Elliot, Tucker
  - LV (0 - 12V)
    - Safety, cheaper
  - HV (48V +)
    - Maybe more realistic?
  - TestPack Voltage?

**Select Microcontroller/Launchpad _(Leo)_**
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