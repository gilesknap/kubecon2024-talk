Please review and correct this abstract for a talk at KubeCon 2024.

# Running a Particle Accelerator Control System in Kubernetes

Diamond Light Source is the UK's national synchrotron, driving scientific research at universities and institutes. The facility is used by over 14,000 academic and industrial researchers across a wide range of disciplines including structural biology, energy, engineering, environmental sciences and more.

The facility produces intense beams of synchrotron light, which are used to study anything from viruses and vaccines to jet engines and catalysts.

To control the thousands of components that make up the accelerator and beamlines, DLS uses a control system called EPICS. EPICS is a set of open-source software tools and libraries used worldwide to create distributed control systems for scientific instruments.

This talk will tell the story of adoption of Kubernetes at the facility. Early on, workloads were primarily data analysis. The organization gradually came to appreciate the benefits of a centralized deployment platform, and eventually in 2021 a project to containerize EPICS began.

EPICS is critical to the operation of the synchrotron. It's roots are from the 1990s, and it prioritizes stability and reliability, meaning that change can be gradual.

This story will discuss the challenges faced in containerizing EPICS, such as supporting legacy network protocols, interfacing with hardware and convincing a conservative community to accept change. It will cover details of how the team overcame these challenges, and discuss the many benefits of running EPICS in Kubernetes.
