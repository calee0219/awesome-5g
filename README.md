# Awesome 5G [![Awesome](https://raw.githubusercontent.com/sindresorhus/awesome/main/media/badge.svg)](https://github.com/sindresorhus/awesome)

[![Build Status](https://travis-ci.org/calee0219/awesome-5g.svg?branch=master)](https://travis-ci.org/calee0219/awesome-5g)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/calee0219/awesome-5g/pulls)

[![5G](https://www.3gpp.org/images/5G-logo_250px.jpg)](https://www.3gpp.org/)

A curated list of awesome 5G frameworks, libraries, software and resources.

Consult [awesome-telco](https://github.com/ravens/awesome-telco) for more general telco resources including EPS, UMTS, and GSM's system or project.

## Contents

<!--ts-->
* [SIM](#sim)
* [UE/CPE](#uecpe)
* [RAN](#ran)
* [Core Network](#core-network)
* [Platforms](#platforms)
* [NFs](#nfs)
* [Edge/Applications](#edgeapplications)
* [Protocols](#protocols)
* [Tools](#tools)
* [Research](#research)
* [Documents](#documents)

<!-- Added by: calee, at: 2020年 7月17日 週五 13時39分28秒 CST -->

<!--te-->

## SIM

- [pysim](https://github.com/osmocom/pysim) - A python tool to program SIMs.
- [sysmo-usim-tool](https://git.sysmocom.de/sysmo-usim-tool/) - Tool to (re)configure the sysmoUSIM-SJS1 cards.

## UE/CPE

- [UE-IoT-non3GPP](https://github.com/my5G/UE-IoT-non3GPP) - Implement a UE for untrusted non3GPP access to 5GS.

## RAN

- [gnbsim](https://github.com/hhorai/gnbsim) - gnbsim is a 5G SA gNB/UE simulator for testing 5GC system.
- [OAI-RAN](https://gitlab.eurecom.fr/oai/openairinterface5g/) - The project implements 4G LTE and 5G Radio Access Network. Both NodeB and User Equipment (UE) are implemented.
- [UERANSIM](https://github.com/aligungr/UERANSIM) - 5G UE/RAN Simulator.

## Core Network

- [5GCore](https://github.com/dukl/5gCore) - 5G system writen in python.
- [free5GC](https://github.com/free5gc/free5gc) - Open source 5G core network base on 3GPP R15.
- [Internship-5GCN](https://github.com/bubblecounter/Internship-5GCN) - Implementation of RESTful Web Services between 5G Control Plane Nodes(AMF,NRF,SMF,UDM).
- [OAI-CN](https://github.com/openairinterface) - This project implements 4G LTE Evolved Packet Core (EPC) and 5G Core Network.
- [open5gs](https://github.com/open5gs/open5gs) - Open5GS is a C-language Open Source implementation of 5GC and EPC, i.e. the core network of NR/LTE network (Release-16).

## Platforms

- [5G-EmPOWER](https://github.com/5g-empower/empower-runtime) - 5G-EmPOWER is a mobile network operating system designed for heterogeneous wireless/mobile networks.
- [DANM](https://github.com/nokia/danm) - TelCo grade network management in a Kubernetes cluster.
- [docker_open5gs with IMS](https://github.com/miaoski/docker_open5gs) - Docker files to run open5gs in a docker.
- [free5gc-k8s](https://github.com/sumichaaan/free5gc-k8s) - Dockerized Free5gc and Kubernetes Manifests.
- [Freecli](https://github.com/srajdax/free5gc-cli) - An interactive CLI for free5gc.
- [free5gmano](https://github.com/free5gmano/free5gmano) - This is a 5G MANO (Management and Network Orchestration) project developed that refer to 3GPP TS 28.531, TS 28.532 Release 15 (R15).
- [my5G-core](https://github.com/my5G/my5G-core) - Currently, my5G-core is a fork of the free5GC project, with some extensions to facilitate the deployment.
- [Magma](https://github.com/magma/magma) - Platform for building access networks and modular network services.
- [ONAP](https://www.onap.org/) - Open Network Automation Platform.
- [Open Source MANO](https://osm.etsi.org/) - OSM is delivering an open source Management and Orchestration (MANO) stack aligned with ETSI NFV Information Models.
- [x-k8s](https://github.com/ITRI-ICL-Peregrine/x-k8s) - ITRI's Kubernetes platform for 5G Edge VNF.

## NFs

- [UPF-EPC](https://github.com/omec-project/upf-epc) - 4G/5G Mobile core user plane.
- [upg-vpp](https://github.com/travelping/upg-vpp) - User Plane Gateway (UPG) based on VPP.
- [vpp](https://github.com/travelping/vpp) - 5G User Plane Function (UPF) based on VPP.

## Edge/Applications

### MEC

- [OpenNESS](https://github.com/open-ness/specs) - This repository includes the literature related to OpenNESS solution.

### Network Slice

- [katana-slice_manager](https://github.com/medianetlab/katana-slice_manager) - 5G Network E2E Slice Manager.

### IoT

- [Open MTC](https://github.com/openMTC/openMTC) - OpenMTC is a reference implementation of the oneM2M standard, for conducting applied research and developing innovative M2M and IoT applications.
- [YoMo](https://github.com/yomorun/yomo) - Build your own IoT & Edge Realtime Computing system easily, engaging 5G technology.

### Applications

- [Kamailio](https://github.com/kamailio/kamailio) - The Open Source SIP Server for large VoIP and real-time communication platforms.

## Protocols

### GTP

- [dpdk_gtp_gateway](https://github.com/edingroot/dpdk_gtp_gateway) - DPDK based GTPv1 gateway.
- [gtp5g](https://github.com/PrinzOwO/gtp5g) - Linux kernel module 5G GTP-U.
- [gtplib](https://github.com/travelping/gtplib) - Erlang GTPv1/GTPv2 library.
- [go-gtp](https://github.com/wmnsk/go-gtp) - GTP(GPRS Tunneling Protocol) implemented in pure Golang.

### SCTP

- [ishidawataru/sctp](https://github.com/ishidawataru/sctp) - SCTP library for the Go programming language.
- [pion/sctp](https://github.com/pion/sctp) - A Go implementation of SCTP.
- [usrsctp](https://github.com/sctplab/usrsctp) - A portable SCTP userland stack.

### PFCP

- [go-pfcp](https://github.com/wmnsk/go-pfcp) - PFCP(Packet Forwarding Control Protocol) implementation in Golang.
- [pfcplib](https://github.com/travelping/pfcplib) - Erlang library for encoding and decoding Packet Forwarding Control Protocol (PFCP) frames.

### Diameter

- [go-diameter](https://github.com/fiorix/go-diameter) - Diameter stack and Base Protocol (RFC 6733) for the Go programming language.

## Tools

- [5G Trace Visualizer](https://github.com/telekom/5g-trace-visualizer) - Tools to generate call flows from pcap.
- [5GC_APIs](https://github.com/jdegre/5GC_APIs) - RESTful APIs of main Network Functions in the 3GPP 5G Core Network.
- [5GC build](https://github.com/H21lab/5GC_build) - Project to use OpenAPI generators to build code from 5GC_API.
- [5g ldpc codes](https://github.com/xiaoshaoning/5g-ldpc) - 5g ldpc codes.
- [MCC_MNC](https://github.com/P1sec/MCC_MNC) - Providing accurate JSON and Python dicts about the many public information available about MNO.
- [New Radio 5G Physical layer utilities](https://github.com/prtkmishra/New_Radio_5G_Utils) - This repository contains Physical layer utilities based on 3GPP specs for NR 5G.
- [3gpp.guru](https://3gpp.guru) - Look up 3GPP abbreviations.
- [speX](https://github.com/CoRfr/spex-3gpp) - Accessible 3GPP specs (PDF, DOC, HTML). [Site](https://spex.cor-net.org)

## Research

- [5G-Core-gRPC-SBA](https://github.com/iithnewslab/SBA-gRPC-5G) - This repository is the proof of concept for Service Based Architecture of 5G using gRPC.
- [5GMdata](https://github.com/lasseufpa/5gm-data) - Datasets and code for machine learning in 5G mmWave MIMO systems involving mobility (5GMdata).
- [Beamformed Fingerprint Learning](https://github.com/gante/mmWave-localization-learning) - ML-based positioning method from mmWave transmissions - with high accuracy and energy efficiency.
- [SliceSim](https://github.com/cerob/slicesim) - 5G Network Slicing Simulation.
- [Sub-6 Predicts mmWave Beam-forming Vectors](https://github.com/malrabeiah/Sub6-Preds-mmWave) - Using sub-6 GHz channels to predict mmWave beams and link blockage.

## Documents

- [3gpp-documentation](https://github.com/emanuelfreitas/3gpp-documentation) - 3GPP Documentation.
- [5G Mobile Networks: A Systems Approach](https://github.com/SystemsApproach/5G) - Open source eBook for 5G system.
