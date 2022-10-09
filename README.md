# Srinag Rao S

## Education
### B.Tech from NITK, Surathkal
B.Tech in Information Technology from National Institute of Technology Karnataka. CGPA: 8.82/10.

## Interests & Skills
### Systems and Security
I am primarily interested in the field of databases internals, distributed systems, high-performance systems, and their security. I have worked with technologies like SQL Server, Docker, Kubernetes, VPC,  mbedTLS, Linux and kernel programming.

### IoT and Robotics
I have programmed extensively for the Raspberry Pi and Arduino, and I have experience building connected robots and tools with digital electronics. 

### Languages
C++, C, Javascript and Python3.

## Work Experience
### Software Engineer II at Microsoft
_May 2021 - Present_

As part of the Storage Engine team at Microsoft SQL DB, I work with database fundamentals like access-methods, transactions, on-disk storage and recovery in SQL Server.

### Software Engineer at Samsung R&D
_January 2021 - May 2021_

At the IoT R&D division, I worked on migrating execution of Javascript routines between IoT devices. To facilitate the migration, we capture and restore the state of variables used by the routine. I extended the scope that can be captured to include local variables and complex objects in addition to globals, thereby increasing the range of functions that qualify for migration.

## Internships

### DevOps Intern at IUDX, IISc
_June 2020 - December 2020_

IUDX is an open-source non-profit entity based out of IISc, Bengaluru to facilitate open data exchange among various Smart City stakeholders. I was responsible for designing [deployment strategies](https://github.com/datakaveri/iudx-deployment), and clustering and containerizing their Vert.x-based backend microservices, their data pipeline powered by the ELK stack, their RabbitMQ messaging service, and a metrics service to monitor system health. 

### Summer Intern at Morgan Stanley
_May 2019 - July 2019_

During my internship at the Wealth Management division, I worked on a chatbot to help engineers monitor their DevOps pipelines and deployment.

### Summer Research Intern at CSA, IISc 
_May 2018 - July 2018_

I designed [MudBoxer](https://github.com/srinskit/MudBoxer) during my internship at the Department of Computer Science and Automation (CSA), IISc, Bengaluru, under [Dr Vinod Ganapathy](https://www.csa.iisc.ac.in/~vg/), as part of the Narendra Summer Internship 2018 program.

## Personal Projects

### Process Migration - Capstone Project
Under the guidance of [Dr Ananthanarayana V. S.](https://infotech.nitk.ac.in/faculty/ananthanarayana-v-s), I designed the [Process Migration System](https://github.com/srinskit/process-migration-system), to migrate live processes across Linux machines. The process state consists of the virtual memory state, and dependencies like CPU registers, which are maintained by the kernel. I developed a kernel module to query and modify the kernel state of a suspended process, and designed tools to capture and restore virtual memory state via procfs. 

### IPoX - Tunnel over any transport
I developed [IPoX](https://github.com/srinskit/IPoX) to create custom virtual links over any transport medium. IPoX uses [TUN](https://www.kernel.org/doc/html/v5.8/networking/tuntap.html) to create a virtual network interface, to which custom transport modules can be plugged-in. I have implemented WebSocket, WebRTC and audio transport modules. Since IPoX links are exposed as regular network interfaces, networked applications like SSH, FTP, remote-desktop, etc readily run on top of it. IPoX creates a peer-to-peer VPN-like link with almost no configuration required.

### MudBoxer - A security wrapper for ROS
I developed [MudBoxer](https://github.com/srinskit/MudBoxer), a security wrapper for Robot Operating System ([ROS](https://www.ros.org/)) applications written in C++. It ensures the confidentiality and integrity of ROS messages. MudBoxer uses the LD_PRELOAD override to dynamically load a custom shared object that intercepts and wraps function calls made by the app. Being a non-intrusive solution, it can be used directly with existing apps and extensions. 

### Rach - Communication module for IoT
I developed Rach, a pub-sub message-broker for IoT applications, inspired by the [ROS](https://www.ros.org/). Clients publish data to a “topic”. All clients subscribed to that topic or any of the parent topics are notified about the data. It also features service calls which mimic RPC. [RachServer](https://github.com/srinskit/RachServerJs) is a NodeJs implementation of the Rach backend. [RachPy](https://github.com/srinskit/RachPy) and [RachJs](https://github.com/srinskit/RachJs) are Python and Javascript clients. 

### Velocity Raptor - A graphic game for Bash
I developed [Velocity Raptor](https://github.com/srinskit/Velocity_Raptor), an avoid-the-obstacle game inspired by the [Chrome T-Rex game](https://en.wikipedia.org/wiki/Dinosaur_Game), written entirely in Bash. The engine uses a model system where the relative position and color of a pixel are encoded in a model string. Several optimizations were implemented to obtain a playable refresh rate. For example, re-rendering only part of a model when it moves along one of the axes. A decoupled model and engine system allowed for features like customizable player and object models.

## Extracurriculars & Awards

### Singapore India Hackathon, 2018
My team was among the 20 teams representing India in the Singapore India Hackathon 2018 held at NTU, Singapore. We presented an RFID-based IoT campus security and monitoring system, powered by [Rach](#1-Rach-Communication-module-for-IoT).

### Smart India Hackathon, 2018
My team won second place at Smart India Hackathon 2018 at BITS-KNL for Witty Lights, an IoT street lighting and monitoring system for smart cities, powered by [Rach](#1-Rach-Communication-module-for-IoT).

### Tronix Committee
The Tronix Committee hosts displays, workshops and robotics competitions at NITK’s Technical Fest “Engineer”. As a member of the core team, I developed a web portal for event announcements and registration. In addition to overseeing projects, I proposed and led a new project to display the game of Atari Breakout on a large custom LED matrix.

## Contact
* GitHub: [srinskit](https://github.com/srinskit)
* Linkedin: [srinskit](https://www.linkedin.com/in/srinskit/)
* YouTube: [EiPi isquar](https://www.youtube.com/channel/UCn_mbl3o1iYw3UqhPE-cIMA)
