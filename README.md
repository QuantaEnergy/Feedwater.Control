# Feedwater.Control #System
The Temperature of water inside a Steam Boiler is a function of it´s Pressure and Flow rate (amount of steam leaving pipe outlet). Likewise the quantity of Heat Absorbed by the water is a function of the Surface area & Thermal conductivity of the Boiler, and itś Water Fill Level and it´s Pressure & Temperature: Water is more conductive than steam, but higher pressure steam also conducts heat better than lower pressure. Supercritical steam has the highest thermal conductivity.

All these quantities can be used to create a Feedwater Control Loop that has very few sensors: Pressure, Flowrate, Temperature.

If the water level gets too low? The temperature & pressure will increase. If the boiler is out of water / Empty? The temperature will increase independently of pressure, which will be ambient & the turbine will stop. IF there is too much water? A Conductivity of supersaturated steam near the Outlet pipe will increase, and a conductivity sensor can detect it, just like a Volkswagen´s Coolant Resevour.

Use a microcontroller & Feedback Loop to always keep the Boiler & Turbine running at a steady state, as closely as possible. There will be a maximum efficiency where the most thermal energy is absorbed, at a certain Water Level - and that can be determined by measuring the steam quantity and temperature/pressure reaching the turbine.
