# Capacitive Water Level Controller

An analog closed-loop water level control system designed and implemented
for the EE 316 Electronic Design Project at İzmir Institute of Technology.

The system detects liquid-level variations using a custom cylindrical
capacitive sensor. The sensor output is processed through phase detection,
filtering, amplification, error generation, and PWM stages. The resulting
PWM signal controls a submersible DC water pump through an L298N motor driver.

## Key Features

- Custom cylindrical capacitive water-level sensor
- TLC555-based oscillator
- XOR-based phase detection
- RC filtering and LM358 signal amplification
- Adjustable reference water level
- PWM-based pump speed control
- Motor overcurrent protection
- LTspice simulation and real-world circuit testing
