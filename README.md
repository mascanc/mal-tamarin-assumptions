# MAL And Tamarin Assumptions


Cybersecurity in Operational Technology (OT) environments poses unique challenges due to legacy systems, safety-critical constraints, and the complexity introduced by IT/OT convergence. One such challenge concerns the use of security protocols to exchange messages in environments under persistent threat. While formal methods are powerful tools for proving the correctness of security protocols, the assumptions made during protocol modeling often lack systematic translation into subsequent system architecture design. 
In this paper, we present a novel methodology aimed to bridge this gap by mapping the security protocol and the respective formal proof assumptions into concrete architectural assets. Verification of proof assumptions is achieved through threat analysis of the system architecture, assessed against the correctness goals established during formal method analysis. The approach is validated through a real-world OT use case involving a SCADA-controlled pump system, where the formal verification and threat simulation reveal vulnerabilities arising from evolving infrastructure demands. We demonstrate how simulations expose potential attacker paths and guide the application of security mitigations. Our method enables iterative validation of architecture against formal assumptions, thereby aligning protocol-level proofs with real-world system resilience

## How to run the examples

To run the examples you need to install [Tamarin Prover](https://tamarin-prover.com), and run, ´tamarin modbus.spthy´.

To run the MAL examples, you need to simulate the archi.json with the scenario.yml, as indicated in the [MAL](https://github.com/mal-lang) home page. 

