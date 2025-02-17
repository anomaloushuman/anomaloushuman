# 🚀 About Me

I'm a technology-driven entrepreneur and innovator, dedicated to transforming conventional human experiences through automation, AI, and open-source solutions. As the founder of NextGen AutoGlass and now Ubiquity Automotive / AutoGlass, I've specialized in leveraging unique technologies like AI, LiDAR, VR/AR, Native Applications and Backend Cloud Networks while harnessing my mastery of the OSI Model and its components in the design, development, and deployment of real-world applications.

# 🧬 Design & Development Skills
- Understanding, developing, designing, and deploying all aspects of the OSI Model.
- Artificial Intelligence - 3D Point Segmentation, 2D Image Segmentation, Image Classification, OCR, Object Detection, LLM, RAG, LAM
- Custom kernel / specialized operating system design & development (including the Development of Kernel Drivers to extend AI subsystems and automation engines (LAM)).
- Development and publishing of native (Windows, Mac, Linux, iOS, Android, TV, Auto) cross platform applications. (Userspace & Kernelspace Level)
- Connecting real-time data to AI for better comprehension (RAG).
- Constructing network ecosystems for scalable AI operations.
- AutoCAD, Blender, AfterEffects, Spline, Cinema4D, PremierPro, Illustrator, Postman, Framer, Xcode, Common IDE's

# 💬 Languages I Speak:
Primary: 
- English

Secondary (Programming & Technical):
- Low-Level & Systems Programming: C, C+, C++, C#, Rust, Assembly, Nix, Meson
- Web & Frontend: JavaScript, TypeScript, HTML, CSS, Vue, Svelte, Next.js
- Backend & Cloud: Python, Node.js, PHP, Go
- Mobile & Native: Swift, Objective-C, Kotlin, Java
- Scripting & Automation: Shell, Perl, Makefile
- AI & Data Science: Python (ML/DL), Jinja
- Database & Query Languages: MySQL, SQL, GraphQL

# 👨🏻‍💻 Prior Industry Experience
## Paid Internship - Oil & Gas (2013 - 2014)
Software Engineering Intern, ION Geophysical
- Developed a code documentation system using DoxyGen, improving maintainability across 1M+ lines of code.
- Contributed to CUDA development for ION's BASIN SPAN & Prometheus Software Suite, enhancing GPU-accelerated geophysical processing.
- Designed Trade Show Marketing Software using KDE's Marble mapping platform, integrating marketing with technical solutions.
- Provided corporate IT support, including imaging/administering devices, ensuring operational efficiency.

## Freelance Work - Medical & Automotive (2014 - 2015)
Front End Web Development, Texas Direct Auto
- Developed front end instant search functionality for TDA's vehicle inventory (AJAX/Jquery) based on multiple vehicle data points, including vin, year make model, features (heated seats, red, leather), trim, etc.

Website Development, Family Practice Doctors
- Developed website for Family Practice Doctors in Humble TX.
- Designed logo based on client vision

Website Development, NexIT Group
- Designed and developed website, logo, and content.

# Milestone 01 - Founded Xymbi Corporation (2015)
🖥️ Developed xyOS – A Unified, Cross-Platform, Cloud-Based Operating System

From 2012 to 2016, while in high school, I developed xyOS, a custom-built multi-platform execution environment that seamlessly unified Windows, macOS, Android, and iOS applications into a single native operating system.

At its core, xyOS was a Linux-based OS that integrated and extended:
- Wine (Windows compatibility layer)
- Darling (macOS compatibility layer)
- Android Runtime (ART) & iOS Mach-O support
- Advanced game console emulation for PS2, Xbox 360, GameCube, and more
  
This resulted in a fully integrated OS capable of running applications from multiple ecosystems natively, without virtualization.

## Key Technical Achievements:
1. Unified Windows, macOS, Android & iOS Execution
   - Combined Wine’s NT kernel translation with Darling’s Mach-O binary support to allow applications from Windows and macOS to run natively.
   - Integrated Android Runtime (ART) and iOS ABI support, allowing native execution of mobile apps.
   - Implemented a shared binary translation layer that dynamically resolved system calls between Windows, macOS, Android, iOS, and Linux.
   - Mapped NTFS, HFS+, EXT, and APFS file systems for seamless cross-compatibility.

2. Custom Kernel Modifications for Multi-Platform Support
Linux kernel modifications to support dynamic binary translation across:
   - Windows PE (Portable Executable) format
   - macOS Mach-O binaries
   - Android ART & Dalvik VM
   - iOS ARM64 binaries with syscall translation
   - Integrated a custom syscall proxy to allow Windows DLLs, macOS frameworks, and Linux shared objects (.so) to coexist.
  
3. Native Game Console Emulation – PS2, Xbox 360, GameCube, and More
   - PlayStation 1 & PlayStation 2 – Integrated PCSX2, dynamically patched for native performance on xyOS.
   - Nintendo 64 & GameCube – Used Dolphin Emulator, enhancing OpenGL/Vulkan support for better game rendering.
   - Xbox & Xbox 360 – Implemented a hybrid Wine-like translation layer to run XQEMU and early builds of Xenia, enabling execution of native Xbox/Xbox 360 games.
   - Sony PSP & PlayStation 3 (early builds) – Experimental integration of PPSSPP and preliminary work on RPCS3.
   - Implemented direct API translation (DirectX, Metal, OpenGL, Vulkan) to improve compatibility across platforms.

4. Dynamic Dependency Resolution
   - Built a hybrid compatibility layer that automatically wrapped and translated system calls from Windows/macOS to Linux.
   - Implemented a shared OpenGL/Vulkan driver model to support DirectX and Metal API calls.
   - Used QEMU-based syscall translation to dynamically execute non-native system calls.
  
5. Native Filesystem and Registry Abstraction
   - Created a custom FUSE-based VFS layer that allowed Windows NTFS registry emulation alongside macOS .plist configurations.
   - Unified application sandboxing for cross-platform runtime execution without OS constraints.
  
6. Pre-Virtualization, Pre-Containerization Era Innovation
   
Achieved full cross-OS compatibility without virtual machines, Docker, or WSL-like environments (which were not mainstream at the time).

Created a multi-platform software ecosystem before the widespread adoption of cross-compatibility frameworks like:
   - Proton (Steam's Windows-to-Linux gaming compatibility layer)
   - Rosetta 2 (Apple’s ARM-to-x86 translation for macOS apps)
   - WSL (Windows Subsystem for Linux)
   - Developed before Microsoft enabled Appx virtualization technologies, which later simplified Windows process emulation on Linux.

The xyOS project, an ambitious open-source, decentralized operating system, ultimately came to an end due to a combination of technical challenges, external competitive forces, and a devastating security breach. The project initially garnered attention for its promise of integrating artificial intelligence, modularity, and a decentralized architecture, but several factors contributed to its eventual conclusion.

The most significant setback occurred in 2016 while pitching xyOS to investors at the NextGen Summit in Austin, TX, when both Xymbi's backend servers and my primary development systems at home were remotely breached and wiped. This breach compromised every aspect of my lifes work and halted development, making it nearly impossible to continue the project without essentially starting over. 

At the same time, the tech landscape was evolving rapidly. Microsoft’s Windows 8/10, with the introduction of AppX/MSIX virtualization and containerization technologies, gained substantial traction. These changes in the Windows ecosystem posed a direct challenge to xyOS, as Microsoft’s new execution environment was becoming more streamlined, controlled, and competitive, making it harder for a decentralized OS to compete.

Apple also played a significant role in reshaping the environment. The introduction of "rootless" on iOS, along with other changes to both iOS and macOS, restricted system-level access and made it more difficult to achieve true continuity across devices. Apple’s increasingly closed ecosystem, combined with tight control over application interactions and system-level modifications, posed a significant hurdle for a project like xyOS, which required a high degree of flexibility and modularity. This shift in Apple’s approach further complicated the vision of a decentralized, open-source system capable of operating seamlessly across multiple platforms.

Ultimately, the combination of the security breach, the rising dominance of Microsoft’s ecosystem, and Apple's tighter security measures led to the project’s shelving. However, despite its conclusion, the lessons learned from xyOS, particularly regarding decentralized computing and platform continuity, influenced future projects.

The xyOS project may not have achieved its original vision, but it contributed valuable insights that shaped the development of subsequent technologies.
<!--
## 🔥 Key Projects & Innovations

# 🔹 Xymbi Corporation
Xymbi Corporation was a Houston-based startup focused on revolutionizing daily technology use. I developed an operating system called xyOS, which enabled users to run native Windows and Mac OS applications on the same system. While out seeking investment at the NextGen Summit in Austin TX I fell victim to an attack which was premeditated. I came home to my system completely wiped and unbootable, years of dedication was wiped from my existence purposefully at the same time our website was hacked and taken offline. 
With an orchestrated hack such as one accomplished against me, I felt utterly defeated and gave up on the pursuit of a multi-dimensional Operating System that included translation layers for different operating systems and a hardware, a feat that took years to accomplish. To have internal and external systems disks completely wiped and a breach of that catastrophe led to the immediate halt on further development.

# 🔹 NextGen AutoGlass
Disrupted the automotive glass industry with AI-driven service automation in the glass replacement industry. Providing service 24/7/365 on over 10K vehicles throughout the State of Texas for Hertz Rent-A-Car in 2020-2021 generating over 2.7M in revenue over its inagural 12 months of service existence. 

# 🔹 TesseractOS
A custom-built Unix, non-POSIX compliant OS for real-time AI-driven automation.
Powers NextGen Services, integrating OCR, Object Detection, and AI-based automation.
TesseractOS: A decentralized AI bot capable of orchestrating system tasks via OpenStack kernel modifications.

# 🔹 Heimdall LLM
A custom LLM trained on 300,000+ vehicle parts and specifications.
Enhances accuracy in automotive part identification, reducing human error in procurement.

# 🔹 Patent-Pending LiDAR & Camera System
Fully automates vehicle identification, damage assessment, part ID, and service procurement.
Integrates OBD-II coding for ADAS recalibration.
Cloud-connected via satellite/cellular, powered by solar and battery tech.


## 🌍 Open-Source & AI Alignment
I believe in aligning technology with humanity for the better. My work with TesseractOS, RealmOS, and AI-driven automation is aimed at reducing inefficiencies and driving innovation in various industries.

## 📫 Connect With Me
🚀 LinkedIn: [linkedin.com/in/patrick-garcia](https://www.linkedin.com/in/anomaloushuman/)
🌐 Website: ubiquityglass.com
📧 Email: patrick@ubiquityglass.com
💡 Always pushing boundaries. Let's build the future, one innovation at a time.


<!--
**anomaloushuman/anomaloushuman** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
