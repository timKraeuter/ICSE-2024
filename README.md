# ICSE-2024

This repository contains the sources of [our paper](./paper.pdf) submitted to the IDE Workshop at the [46th International Conference on Software Engineering (ICSE 2024)](https://conf.researchr.org/home/icse-2024) and associated artifacts.

The paper describes our experience and lessons learned from implementing the [open-source](https://github.com/timKraeuter/VisualDebugger) [Visual Debugger](https://plugins.jetbrains.com/plugin/16851-visual-debugger).

We also describe _improvements and new features_ in the Visual Debugger compared to our [previous publication at ICMSE-2022](https://doi.org/10.1109/ICSME55016.2022.00066).

# Demonstration of the Visual Debugger 2.0
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/LsAMTnLxWJw/0.jpg)](https://www.youtube.com/watch?v=LsAMTnLxWJw)

Follow the [demonstration](https://www.youtube.com/watch?v=LsAMTnLxWJw) doing the following steps:
1. Clone the Visual Debugger [repository](https://github.com/timKraeuter/VisualDebugger) using git.
2. Open the repository clone using IntelliJ IDEA as a new project.
3. Install the Visual Debugger plugin from the IntelliJ IDEA marketplace (```File < Settings < Plugins``` and search for **Visual Debugger**).
4. Go to the class ```BSTNodeTest``` and set a breakpoint at line 10 (directory: ```src/test/java```, package: ```no.hvl.tk.visual.debugger.manueltests.bst```).
5. Start debugging and activate the Visual Debugger in the Visual Debugger window.
6. Open the Visual Debugger by clicking on the "Launch browser" or "Launch embedded browser" button in the Visual Debugger window.
7. Enjoy the Visual Debugger.

# Visual Debugger API
The Visual Debugging API is described [here](https://github.com/timKraeuter/VisualDebugger/tree/master/documentation#visual-debugging-api).

# Further resources
- More information about the Visual Debugger, including screenshots, can be found on the [its plugin page](https://plugins.jetbrains.com/plugin/16851-visual-debugger) in the IntelliJ IDEA marketplace.
- The **visualization component** of the Visual Debugger can be found [here](https://github.com/timKraeuter/object-diagram-js).
- You can edit object diagrams created during debugging using my [object diagram modeler](https://timkraeuter.com/object-diagram-js/).
- A short documentation of the visual debugger implementation can be found [here](https://github.com/timKraeuter/VisualDebugger/blob/master/documentation/README.md).
- There is also a description of the Visual Debugger on [my website](https://timkraeuter.com//visual-debugger/).
