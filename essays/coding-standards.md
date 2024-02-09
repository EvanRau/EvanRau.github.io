---
layout: essay
type: essay
title: "Coding Standards and the Dependencies of the Internet"
# All dates must be YYYY-MM-DD format!
date: 2024-02-08
published: true
labels:
  - Javascript
  - OpenSSL
---


While many junior programmers may see coding standards as trivial minutiae that don't truly matter for personal projects, history shows that even individual projects can leave a lasting legacy on the internet. Utilities such as OpenSSL and core-js, despite only being maintained by one or two people, have become integral to countless pieces of software. If you stray from coding standards and write your code so that only you can understand it, nobody else will be able to update it once you are no longer able to.

Furthermore, adherence to coding standards not only ensures the maintainability and accessibility of code beyond its creator's tenure but also fosters collaboration and scalability within development teams. Consistent coding practices facilitate smoother integration of new members into projects, as they can quickly grasp the structure and style of existing code. Additionally, when code conforms to established standards, it becomes more modular and adaptable, enabling easier iteration and expansion as project requirements evolve. In this way, coding standards serve as a linchpin for sustained project success, promoting cohesion and efficiency in development efforts.

Additionally, coding standards can be vital to helping correct major bugs or exploits in one's code. The heartbleed bug in OpenSSL is one major example of a small-scale utility allowing a lethal backdoor into many programs, and despite only being a team of two, the developers were quickly able to patch the vulnerability before any more damage was done. It is likely that if their code was not well organized and laid out, it would have taken significantly longer to push a patch out, and a lot more damage could have occurred.

In conclusion, the significance of adhering to coding standards cannot be overstated. Beyond ensuring the longevity and accessibility of code, these standards foster collaboration, scalability, and code quality within development teams. Moreover, they play a crucial role in addressing critical bugs and vulnerabilities, as exemplified by the rapid response to the heartbleed bug in OpenSSL. By upholding coding standards, developers not only safeguard the integrity of their projects but also contribute to the resilience and reliability of the broader software ecosystem.
