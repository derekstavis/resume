# Derek Willian Stavis
> Full-stack software engineer

## Characteristics

- Breathes technology, programming and systems
- UNIX lover. Seamless at Linux and OS X
- Open-minded, passionate about beautiful architecture and code
- Fast learning, communicative and a team player
- Adventurous in Linux internals (libc, epoll, allocators, syscalls)

## Languages

- Portuguese (native)
- English (fluent)
- Spanish (entry level)

## Experience

### Software Engineer @ Healfies
> April 2016 - Until now

Healfies is a startup focused in providing a social network approach for healthcare, allowing patients to receive health data securely and have full control of it while sharing with physicians and other health professionals. It's a new way to keep your data and communicate with health professionals.

#### Languages, Tools and Skills
* Linux
* Git
* AWS
* Node.js
* MongoDB

#### Web Application:
Deployed Webpack to application as a way to slim down its size, minimize the number of HTTP requests, and give an end to issues related to caching. As a side effect of applying Webpack, also refactored the application structure to ease the code collaboration process and avoid merge conflicts.

### Software Engineer @ DBA Tecnologia
> June 2012 - April 2016 (3 years an 10 months)

DBA Tecnologia is a company focused in traffic analysis and paid parking systems. I worked there on a lot of challenging projects, which I enumerate a few below:

#### Company-wide:
Helped in growing company's infrastructure by making changes on hardware and software stack, deploying Git versioning system using Gitlab, creating the documentation habit by using a Wiki system. Also deployed virtualization technologies for fast-paced machine creation and destruction.

#### Traffic System:
Designed a system to organize company's most important service: Vehicle traffic counting and classification. The solution was projected to take care of the whole process: Orders, data acquisition spots, equipment callibration, data extraction, synchronization and digestion. As a lead developer, took strategic decisions based on team knowlege and performance requirements, by  benchmarking multiple languages and choosing the best software frameworks.

In the platform front, developed the core of data receiving system in JavaScript and crafted the background workers that processed the data in C + GLib, resulting in the most complex historic data set found (2 million records in 2 months) being processed in a minute, while the most common data set taking average 17 seconds to process, greatly improving the report generation time.

In the field front, designed the user interface and developed a desktop application based on JavaScript + Electron for callibrating, installing and acquiring electronic vehicle counter data, doing serial communication and internet API integration to send data on the fly, without need to return to office.

In the office front, also designed the user interface and developed a desktop application to allow users to classify vehicles imagery visually, making the classification process faster.

In this project, the feeling was that that the code written added great value, contributing to make field process less error-prone, raising reports quality and lowering the delivery time. This allowed the company to do more work more efficiently.

#### Parking System:
Helped find market requirements and design the whole system architecture, which integrates lots of clients: Parking meter, parking fiscal apps, voice response unit, citizen mobile application and website.

On the equipment front, designed and developed from the ground-up the whole embedded system running on the parking meter, from the ARM processor used, the operating system architecture (deployment, update) and tweaks (memory allocator, libc), device driver development (Python, C), application (Python, D-Bus) and user interface development (Python). Also contributed to mechanical design ideas and problem solving.

On the integrations front, designed and developed the Interactive Voice Response Unit based on Asterisk, written in pure functional and asynchronous JavaScript running on Node.js.

On the platform front, aided in HTTPS certificate emission and management, cloud deploys and management using Amazon Web Services.

#### Languages, Tools and Skills

* Linux
* Git
* AWS
* Ruby
  - Sinatra
  - Rails
  - PostgreSQL
  - pg_search
* Python
  - setuptools
  - Twisted
  - treq
  - MongoDB
  - Kivy
* NodeJS
  - express
  - mongojs
  - electron
  - asterisk
* Front-end
  - Angular
  - Grunt
  - React
  - Webpack
  - LESS
  - SCSS
  - SVG
* Android
  - Jackson
  - Volley
* Designer Stuff
  - Adobe Illustrator and Photoshop
  - Inkscape
  - GIMP

### Embedded Software Engineer @ Ahgora Sistemas
> January 2012 - June 2012 (6 months)

Ahgora is a company focused in attendance and access control systems. I worked with bleeding edge technologies and an awesome team of experts. For them I worked mostly on embedded team, with some interesting projects.

#### RFID:
Rewrote the code of active, battery-powered RFID tags, making the code production-proof and focusing on lowering power usage, keeping protocol compatibility with previous product. Surprisingly, even not knowing the microcontroller and protocol I achieved this task in a week. We went to the bar with boss to celebrate the accomplishment! :)

Developed an Android passive RFID (ISO 18000-6c) reader software for asset management project, and started porting the software to a already existent embedded Linux platform.

#### Other projects:

Worked on prototypes for electronic labelling project, whose was used on supermarkets to update automatically the prices of shelves in a dedicated, low power embedded system which communicated using a own developed protocol over 2.4Ghz wireless.

#### Languages, Tools and Skills

* Linux
* Git
* Linux C
* Bare-metal C
* sdcc
* Android

### Operations Intern @ Unioeste
> March 2011 - December 2011 (10 months)

Unioeste is the name of Universidade Estadual do Oeste do Paraná (or Paraná's West State University), where I studied Computer Science course for 4 years. There I was an intern in the IT division, helping other students with system login, troubleshoot wireless issues and fix laboratory computers. In the internship I participated in interesting tasks:

- Windows/Linux operating system deployment and domain migration
- PlayStation 3 clusterization for scientific processing
- Various proccess automatizations using batch scripts

#### Languages, Tools and Skills

* Linux
* Bash Scripting
* Windows Scripting
* Active Directory

### Full-stack web developer and graphical designer @ Freelancer
> January 2011 - December 2011 (12 months)

Designed the whole art of Harucon event, the anual Genshiken's anime club meeting, producing posters, flyers, tickets, tees and the website based on event's theme. The art was created using Adobe's Illustrator and Photoshop, designed taking care of the different media types, using CMYK process for print and RGB process for web.

The website frontend was designed in standards-compliant HTML5, CSS and JavaScript, including hand-made SVG animations. The backend was based in Drupal 7, which was pretty new at the time, and rendered a lot of contribution in porting Drupal 6 modules.

The deployment was planned in two parts, being the first phase a landing page with an animation of event's theme with a countdown timer for the event day, and the second, which replaced the first phase, the main website, deployed one month before the event, which included event's schedule, the description of each activity and a photo stream of previous events. There was an integrated Facebook comments box, which proved to be a nice channel for communicating with people interested in the event. In the end of the event the website was fed with photos taken by the staff, and stayed alive until the next event.

#### Languages, Tools and Skills

* Linux
  - Server Management 
* OS X
  - Adobe Illustrator and Photoshop
  - Tumult Hype
* PHP
  - Drupal 7
* JavaScript
* jQuery
* HTML
* CSS
* SVG

### Full-stack web developer @ mz2 webdesign studio (freelancer)
> October 2006 - July 2009

Implemented designs from Adobe Photoshop into standards-compliant HTML, CSS and JavaScript. Helped modelling MySQL databases and implemented backends mostly in PHP. Developed web components using Adobe Flash and ActionScript 3, integrated with page using JavaScript callbacks.

#### Languages, Tools and Skills

* OS X
* Adobe
  - Illustrator
  - Photoshop
  - Flash
  - Fireworks 
* PHP
* HTML
* CSS
* JavaScript

## Projects

### Native Linux and Python GPIO access
A pure-python and Linux native GPIO access library. Include the ability to be asynchronously notified when a signal changes using Linux edge triggered polling. See more at [project's GitHub](https://github.com/derekstavis/python-sysfs-gpio).

### Oh My Fish
Core developer at Oh My Fish, a shell framework for managing plugins and prompts. Manages the community, accepts package pull requests and reviews code. See more at [project's GitHub](https://github.com/oh-my-fish/oh-my-fish).

### Fish Foreign Environment
A compatibility layer which allows running bash-based applications and import environment variables changed. See more at [project's GitHub](https://github.com/oh-my-fish/plugin-foreign-env).

### nvm plugin for Oh My Fish
Uses Fish Foreign Environment compatibility layer to make node version manager work under fish, also providing nice completions. See more at [project's GitHub](https://github.com/derekstavis/plugin-nvm).

### Nordic nRF24LE1 toolkit for RaspberryPi
A toolkit for flashing and dumping Nordic's nRF24LE1 microcontrollers via Raspberry Pi. See more at [project's GitHub](https://github.com/derekstavis/nrf24le1-libbcm2835).

### Transmission torrent client
Theme of my [term-paper](https://github.com/derekstavis/term-paper), it's a port of GTK client compliant with GNOME Human Interface Guidelines. See more at [project's GitHub](https://github.com/derekstavis/transmission).

## Education

### Bachelor in Computer Science @ Unioeste
> January 2008 - December 2011 (4 years)

### Software Analysis and Development Techologist @ SENAI
> January 2012 - December 2015 (3 years)
