<a href="https://www.packtpub.com/en-us/unlock"><img src="https://drive.google.com/uc?export=view&id=1lQCTQQ8iV5pGuPA1n5wuds-3pwJi0OD_"></a>
<h1 align="center">
Zephyr RTOS Cookbook, First Edition</h1>
<p align="center">This is the code repository for <a href ="https://www.packtpub.com/en-us/product/zephyr-rtos-cookbook-first-edition-9781807429171"> Zephyr RTOS Cookbook, First Edition</a>, published by Packt.
</p>

<h2 align="center">
Build portable and scalable embedded systems through hands-on recipes
</h2>
<p align="center">
Dr. Roy Jamil, Dr. Ayoub Bourjilat</p>

<p align="center">
  <a href="https://a.co/d/0f4vHvo5"><img width="32px" alt="Amazon" title="Get your copy" src="https://cdn-icons-png.flaticon.com/512/15466/15466027.png"/></a>
  &#8287;&#8287;&#8287;&#8287;&#8287;
</p>

<details open> 
  <summary><h2>About the book</summary>
<a href="https://www.packtpub.com/en-us/product/zephyr-rtos-cookbook-first-edition-9781807429171">
<img src="https://content.packt.com/B37681/cover_image_small.jpg" alt="Zephyr RTOS Cookbook, First Edition" height="256px" align="right">
</a>

Adopting Zephyr RTOS can feel very different from working with bare-metal systems, traditional RTOSes, or embedded Linux. Instead of tightly coupled board-specific code, Zephyr follows a platform-oriented approach built around reusable components, standardized subsystems, and configuration-driven behavior. This shift can be unfamiliar at first, especially for developers moving to Zephyr for real-world products.
Zephyr RTOS Cookbook is a recipe-led guide designed to help you make that transition with confidence. Rather than treating Zephyr as just a kernel, the book shows how to work with it as a complete platform. You'll learn how to structure projects using West-managed, multi-repo workspaces, enable and customize system features with Kconfig, and describe hardware cleanly using devicetree to keep applications portable across boards.
Each recipe focuses on a practical task you'll encounter when building Zephyr-based systems, from integrating drivers and subsystems to reasoning about initialization order, device availability, and permissions at runtime. By the end of the book, you'll be able to develop maintainable Zephyr applications, adapt them to different hardware configurations, and confidently scale your codebase across projects and teams.</details>

<details open> 
  <summary><h2>Key Learnings</summary>
<ul>

<li>Set up a reproducible Zephyr development environment and West workspace</li>

<li>Structure apps and modules</li>

<li>Navigate the Zephyr build flow and inspect key generated outputs</li>

<li>Configure features with Kconfig</li>

<li>Describe and customize hardware using devicetree</li>

<li>Use common subsystems: GPIO, I2C, ADC, logging, and shell</li>

<li>Apply user mode to enforce security</li>

<li>Control peripherals from applications using drivers</li>

</ul>

</details>

<details open> 
  <summary><h2>Chapters</summary>
<ol>

  <li>Introducing the Zephyr Project</li>

  <li>Structuring and Building Zephyr Applications</li>

  <li>Configuring Zephyr Applications with Kconfig</li>

  <li>Using Devicetree to Describe Hardware</li>

  <li>Exploring Zephyr's Device Driver Model</li>

  <li>System Initialization and Multithreading</li>

  <li>Working with Zephyr Subsystems</li>

  <li>User Mode in Zephyr</li>

</ol>

</details>

<details open> 
  <summary><h2>Requirements for this book</summary>

This book is for embedded developers and engineers who are transitioning to Zephyr from traditional RTOSes, bare-metal environments, or embedded Linux. It is aimed at readers with experience in embedded C who want to adopt Zephyr as a scalable platform for building portable systems that can be deployed consistently across multiple boards and development teams. The target audience of this book are as follows:

- **Embedded developers moving to Zephyr:** They already write firmware in C and want a practical, task-oriented path into Zephyr's workspace model, configuration system (Kconfig and devicetree), and hardware abstractions.
- **Engineers building portable, scalable products:** They work on industrial or IoT devices that must run across several boards, and they need code that stays maintainable as the product and the team grow.
- **Developers and architects evaluating Zephyr:** They want to understand how West, Kconfig, devicetree, subsystems, and User Mode fit together before committing Zephyr to a real project.

You will need a working knowledge of the C programming language and an understanding of the basics of embedded development, including compiling firmware and flashing it onto a development board. No prior experience with Zephyr is required.

| Software/Hardware covered in the book | OS Requirements |
| ------------------------------------- | --------------- |
| Zephyr RTOS and the SDK | Windows 10/11, Linux (Ubuntu 24.04 or newer), or macOS on Apple Silicon |
| West (the Zephyr meta-tool) | |
| Visual Studio Code with the Workbench for Zephyr extension | |
| Recommended: NXP FRDM-MCXN236 or ST NUCLEO-H563ZI development boards | |
| Recommended: OpenSmart Rich Shield | |

The recipes are written for real hardware, but most can also be run in a simulation environment. For the development board, we recommend the NXP FRDM-MCXN236 or the ST NUCLEO-H563ZI, which are used throughout the book. Any other officially supported dev kit also works; you can follow most recipes on it directly, while a few will need minor board-specific adjustments.

Several recipes use external peripherals. We recommend the OpenSmart Rich Shield, which bundles the components used in the book. If you don't have it, you can follow those recipes with a few discrete parts instead, at a minimum, an LED and a potentiometer.

</details>

<details> 
  <summary><h2>Get to know Authors</h2></summary>

_Dr. Roy Jamil_ is an Embedded Systems Engineer, trainer, and consultant at AC6 specializing in Zephyr RTOS and embedded Linux. He holds a PhD in Embedded Systems focused on asymmetric multiprocessing platforms combining Linux and real-time operating systems. A Zephyr Project Technical Steering Committee (TSC) representative, Roy has delivered Zephyr professional training worldwide since 2022. He supports companies adopting Zephyr and porting new drivers and boards.

_Dr. Ayoub Bourjilat_ is an Embedded Systems Engineer, trainer, and consultant at AC6. He holds a PhD in Embedded Systems and brings hands-on experience across RTOSes, processor architectures, and FPGA platforms. Through training and consulting, he focuses on robust system architecture, scalable Zephyr integration, and building auditable, secure-by-design embedded products aligned with modern industrial and IoT constraints.

</details>

<details> 
  <summary><h2>Other Related Book</h2></summary>
<ul>

  <li><a href="https://www.packtpub.com/en-us/product/hands-on-rtos-with-microcontrollers-second-edition-9781803237725">Hands-On RTOS with Microcontrollers, Second Edition</a></li>

</ul>

</details>
