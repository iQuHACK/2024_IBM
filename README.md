# Welcome to MIT iQuHACK 2024 - IBM Challenge!!

> [!IMPORTANT]
**IBM Challenge is only for in-person attendees**

## Table of Contents:

- [Welcome to MIT iQuHACK 2024 - IBM Challenge!!](#welcome-to-mit-iquhack-2024---ibm-challenge)
  - [Table of Contents:](#table-of-contents)
  - [**Overview**](#overview)
  - [**Requirement**](#requirement)
    - [Access to IBM Hardware](#access-to-ibm-hardware)
    - [Working on qBraid Lab](#working-on-qbraid-lab)
    - [Working on IBM Quantum Lab](#working-on-ibm-quantum-lab)
    - [Working on Locally](#working-on-locally)
  - [Submitting the tasks](#submitting-the-tasks)
  - [Judging Criteria](#judging-criteria)
  - [Winners and Awards](#winners-and-awards)
  - [Resources](#resources)
    - [Learning Materials](#learning-materials)
      - [Quantum Computing and Algorithms](#quantum-computing-and-algorithms)
      - [Workflow Example Tutorials](#workflow-example-tutorials)
    - [API Reference](#api-reference)
    - [Useful Resources](#useful-resources)
  - [Tips](#tips)
  - [Feedbacks and Discussions](#feedbacks-and-discussions)


## **Overview**

We've entered a new era of quantum computing - The Quantum Utility era.

Quantum utility is what we get when a quantum computer can perform reliable computations at a scale beyond brute force classical computing methods that provide exact solutions to computational problems.

Now, computational scientists and other researchers can tackle these large-scale problems using quantum computers with IBM's 100+ qubits backends accessible to everybody. That's an enormous milestone in the field's history because, until recently, all quantum computers were small, experimental devices primarily used to advance the study of quantum computing. Entering the era of quantum utility is, in other words, the quantum computers we have today are valuable tools researchers can use to explore meaningful scientific problems. Now it is your turn to tackle and explore issues with this leading-edge computational resource.

This challenge aims to design and build a cloud-based, quantum-powered application that addresses a real-world problem and is accessible to end users. This includes applications of quantum algorithms that can have practical usage and, in theory, be exposed to businesses or individual users on the internet for consumption. Teams should identify a problem that can be solved (not necessarily more efficiently) with quantum computers.

Some examples include but are not limited to:

- An application involving a Random Number Generator
- An application involving Optimization
- An application involving Chemical Simulation
- An application involving a Quantum Calculator
- An application involving Sentiment Analysis
- An application involving Image Classification
- A game involving a quantum algorithm
- An application that utilizes the 100+ qubit hardware

> [!NOTE]
The idea is that it serves a practical use case and can be accessed by anyone without special tooling that is not already included in a typical computer installation (or minimal installation)

## **Requirement**

### Access to IBM Hardware
In order to gain access to IBM Quantum hardware for working on qBraid Lab or Locally:

1. Login to https://quantum.ibm.com/. If you don't have your IBMid, please signin first. 
2. After login, please copy your "API Token" by clicking double square butten at the top right and save it for the aBraid Quantum Lab
<img src="./img/apitoken.png" width=100%>

### Working on qBraid Lab
[<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com/?gitHubUrl=https://github.com/iQuHACK/2024_IBM.git)


1. If you're working on qBraid, first fork this repository and click the above `Launch on qBraid` button. It will take you to your qBraid Lab with the repository cloned.
   
2. Use the default environment to use the latest Qiskit.

<img width="287" alt="image" src="./img/default_env.png">

### Working on IBM Quantum Lab

You can also work on the [IBM Quantum Platform](https://quantum.ibm.com/), by using [IBM Quantum Lab](https://quantum.ibm.com/lab). In Quantum Lab, you can write scripts that combine Qiskit code, equations, visualizations, and narrative text in a customized Jupyter Notebook environment — no installation required. Run code on real quantum hardware(opens in a new tab) or simulators(opens in a new tab). Store, access, and manage your files from anywhere.

> [!IMPORTANT]
While you are using IBM Quantum Lab, you don't need to select a channel or save tokens.

### Working on Locally
If you will work locally or in a cloud environment, the first step for all users is to install Qiskit. 

Please follow [this installation tutorial](https://docs.quantum.ibm.com/start/install). After installing the latest Qiskit, You can access IBM Quantum systems by using the `IBM Quantum Platform` or `IBM Cloud` channel. Channel is the term used to describe the method you use to access IBM Quantum services, and for this challenge, we suggest you use the `IBM Quantum Platform` channel and follow this [instruction](https://docs.quantum.ibm.com/start/setup-channel#set-up-to-use-ibm-quantum-platform) to set up a channel for your project.


## Submitting the tasks

> [!IMPORTANT]
Submission Due: 10am ET, 4th Feb (Sunday)</br>
Link will expires after due.


LINK: TBA

## Judging Criteria

1. **Technical Aspects (30%)** : This category includes the following subcategories:
    - Quantum Complexity : How complex is the quantum algorithm? How optimized is it?
    - Architecture : Does the architecture leverage cloud technologies to optimize cost? Can the architecture serve users at a reasonable scale?
    - Accessibility/User Experience : How accessible is the end user application? Is it easy to use and intuitive for end users?
2. **Originality and Uniqueness (25%)** : How unique is this project compared to others? How interesting is it? Did the team attempt something new or difficult?
3. **Usefulness and Complexity (25%)** : How useful is the project and how well-designed is it? How functional is it at the time of judging? Can it be used in real-world business applications or serve as a valuable tool for individuals?
4. **Presentation (20%)** : How well did the team present their project? Were they able to explain their decisions? Did the entire team have a chance to speak?

## Winners and Awards

TBA


## Resources

### Learning Materials

#### Quantum Computing and Algorithms

- [Basics of quantum information](https://learning.quantum.ibm.com/course/basics-of-quantum-information) by John Watrous (Award Badge Available)
- [Fundamentals of quantum algorithms](https://learning.quantum.ibm.com/course/fundamentals-of-quantum-algorithms) by John Watrous
- [Variational algorithm design](https://learning.quantum.ibm.com/course/variational-algorithm-design)

#### Workflow Example Tutorials

- [Qiskit Runtime Lab](https://github.com/JavaFXpert/qiskit-runtime-lab) by [James Weaver](https://github.com/JavaFXpert)
- [Variational quantum eigensolver](https://learning.quantum.ibm.com/tutorial/variational-quantum-eigensolver)
- [Quantum approximate optimization algorithm](https://learning.quantum.ibm.com/tutorial/quantum-approximate-optimization-algorithm)
- [CHSH inequality](https://learning.quantum.ibm.com/tutorial/chsh-inequality)
- [Max-Cut](https://learning.quantum.ibm.com/tutorial/max-cut)
- [Heisenberg chain](https://learning.quantum.ibm.com/tutorial/heisenberg-chain)
- [And More!](https://learning.quantum.ibm.com/catalog/tutorials)


### API Reference

- [Qiskit](https://docs.quantum.ibm.com/api/qiskit)
- [Qiskit Runtime IBM Client](https://docs.quantum.ibm.com/api/qiskit-ibm-runtime)
- [Qiskit IBM Runtime REST API](https://docs.quantum.ibm.com/api/runtime/tags/jobs)
- [Qiskit IBM Provider](https://docs.quantum.ibm.com/api/qiskit-ibm-provider)

### Useful Resources

- [Qiskit Youtubes](https://www.youtube.com/Qiskit)
- [IBM Quantum Blogs](https://www.ibm.com/quantum/blog)
- [Qiskit Slack](https://qisk.it/join-slack): Meet the community!


## Tips
This year’s iQuHACK challenges require a write-up/documentation portion that is heavily considered during
judging. The write-up is a chance for you to be creative in describing your approach and describing
your process. It can be in the form of a blog post, a short YouTube video or any form of
social media. It should clearly explain the problem, the approach you used, your implementation with results
from simulation and hardware, and how you accessed the quantum hardware (total number of shots used, 
backends used, etc.).

Make sure to clearly link the documentation into the `README.md` and to include a link to the original challenge 
repository from the documentation.

## Feedbacks and Discussions

Your opinions matter! Place to share your feedback on Qiskit [here](https://github.com/Qiskit/feedback
); stay up to date with release planning and DemoDays; and find out where to get support.





[def]: #winners-and-awards