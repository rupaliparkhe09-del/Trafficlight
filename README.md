🚦 Smart Traffic Light Controller Using Icarus Verilog

📌 Project Overview

The Smart Traffic Light Controller is a digital logic project developed using Verilog HDL. It simulates a traffic signal system with three lights: Red, Yellow, and Green. A simple web-based user interface (UI) allows users to interact with the traffic light demonstration.

🎯 Objectives

- To design a traffic light controller using Verilog HDL.
- To understand Finite State Machines (FSM).
- To simulate digital logic using Icarus Verilog.
- To create a mobile-friendly interactive UI.

⚙️ Technologies Used

- Verilog HDL
- Icarus Verilog
- HTML
- CSS
- JavaScript

🚥 Features

- Red light: Stop
- Green light: Go
- Yellow light: Wait
- Interactive UI with signal controls
- Verilog testbench for simulation
- Mobile-friendly interface

📂 Project Files

- "index.html" — Web user interface
- "traffic_light_controller.v" — Verilog logic
- "tb_traffic_light_controller.v" — Testbench

▶️ How to Run the Verilog Simulation

Install Icarus Verilog, then run:

iverilog -o traffic_sim traffic_light_controller.v tb_traffic_light_controller.v
vvp traffic_sim

🌐 User Interface

Open "index.html" in a web browser to use the interactive traffic-light demo.

Note: The browser UI is a JavaScript demonstration. The actual Verilog simulation runs separately through Icarus Verilog.

🎓 Applications

- Digital electronics learning
- FSM design practice
- Traffic signal simulation
- Verilog HDL mini-projects

👨‍💻 Project Type

Academic / Educational Project

📝 Conclusion

This project demonstrates how digital logic and finite state machines can be used to design a basic traffic light controller. It combines Verilog simulation with a simple interactive web interface.
