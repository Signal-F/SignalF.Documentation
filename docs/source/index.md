
# Welcome to the SignalF documentation!

```{toctree}
---
caption: Getting started
maxdepth: 1
hidden:
---
/getting-started/getting-started
```

```{toctree}
---
caption: Tutorial - CPU-Temperature
maxdepth: 1
hidden:
---
/tutorial/signalf-application
/tutorial/configuration
/tutorial/devices
/tutorial/signal-flow
/tutorial/calculators
/tutorial/gpio
```

```{toctree}
---
caption: Architecture
maxdepth: 1
hidden:
---
/architecture/overview
```

```{toctree}
---
caption: Credits
maxdepth: 1
hidden:
---
/credits/credits
```


SignalF is a configurable, modular .NET measurement and control software specially designed for operation on single-board computers such as the Raspberry Pi or the Orange Pi. In industry, single-board computers are primarily used in measurement and control technology (MCR), where they often replace the much more expensive programmable logic controllers (PLCs).

SignalF is a soft real-time system. The sensor data is read in, the control algorithms and calculators are executed and the control values are output to the actuator at defined time intervals using configurable tasks. When creating your measurement and control software, you no longer have to worry about the architecture of the application, but can concentrate entirely on connecting the hardware and implementing your algorithms.

:::{note}
This project is under active development.
The documentation has not yet been finalised. If you would like to know more about SignalF or if you need support in using it, please contact me at the following email address: <br>
signalf@scotec-software.com
:::

## Source code

You can download the full source code for this tutorial on [GitHub](https://github.com/Signal-F/SignalF.Tutorials/tree/develop){target="_blank"}.

## Licence

SignalF is licensed under the MIT licence.
