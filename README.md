# Café Simulator

## Project simulating the dynamic operations of a coffee shop, in NetLogo.
How it works?
- Clients approach the order counter and interact with available baristas. Orders are recorded based on client preferences and a variable called "order", that helps the baristas.
- Baristas move to the respective drink preparation area (patch) and reduce stock levels as drinks are prepared.
- Completed orders are delivered to clients, who then leave the café via the exit patches.
- If a drink's stock reaches zero, the corresponding patch turns black to indicate unavailability. Clients who can't get their preferred drink due to stock depletion exit the café, marked in red.

## How to run the simulation
- Ensure that you have the NetLogo software installed.
- Clone or download the repository to your local machine.
- Open the `Cafe-Sim.nlogo` file, using NetLogo.
- Adjust model parameters such as stocks, baristas, and clients as desired within the code.
- Run the simulation to observe changes in client drink preferences and fluctuations in revenue.

## Features
- A switch to easily observe available stock levels.
- Graphs to monitor sales revenue and highlight consumption trends, as well as track the number of dissatisfied clients.
