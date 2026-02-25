# Telecom Transport Network Simulator

## Overview
This project simulates a simplified real-world telecom transport network from access layer to core.

The goal is to model how traffic flows from BTS nodes through aggregation and transport routers into the core network and finally to application servers.

## Topology v1

Access → Aggregation → Transport → Core → Application

Components:

- BTS (4G eNodeB / 5G gNodeB)  
  Radio access nodes where user traffic originates.

- MUX-01 (Aggregation Layer)  
  Aggregates multiple BTS links into transport network.

- T3 Router (Transport Layer)  
  Handles IP routing and future OSPF/BGP simulation.

- Core Router  
  Represents operator backbone network.

- Media / Application Server  
  Traffic termination and test endpoint.

Diagram available in:
docs/topology-v1.png

## Simulation Scope

Planned implementation includes:

- OSPF routing simulation
- BGP peering simulation
- VLAN segmentation
- ACL-based traffic filtering
- Python-based configuration validation

## Project Structure

docs/        -> Topology diagrams and documentation  
src/         -> Simulation and automation scripts  
configs/     -> Router configuration templates and IP plans  
tests/       -> Validation and test cases  
