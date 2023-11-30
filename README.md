# Awesome 5G [![Awesome](https://raw.githubusercontent.com/sindresorhus/awesome/main/media/badge.svg)](https://github.com/sindresorhus/awesome)

[![Build Status](https://travis-ci.org/calee0219/awesome-5g.svg?branch=main)](https://travis-ci.org/calee0219/awesome-5g)
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
- [sysmo-usim-tool](https://gitea.sysmocom.de/sysmocom/sysmo-usim-tool/) - Tool to (re)configure the sysmoUSIM-SJS1 cards.

## UE/CPE

- [my5G-non3GPP-access](https://github.com/my5G/my5G-non3GPP-access) - Implement a UE for untrusted non3GPP access to 5GCN.

## RAN

- [free5GRAN](https://github.com/free5G/free5GRAN) - free5GRAN is an open-source 5G RAN stack.
- [gNBSim](https://github.com/omec-project/gnbsim) = Open source simulation software for 5G Core testing
- [gnbsim](https://github.com/hhorai/gnbsim) - gnbsim is a 5G SA gNB/UE simulator for testing 5GC system. (The origin repo has been deleted. You can find [backup here](AlohaLuo/gnbsim-backup). Refer to [issue#9](../../issues/9).)
- [OAI-RAN](https://gitlab.eurecom.fr/oai/openairinterface5g/) - The project implements 4G LTE and 5G Radio Access Network. Both NodeB and User Equipment (UE) are implemented.
- [PacketRusher](https://github.com/HewlettPackard/PacketRusher) - High performance 5G UE/gNB Simulator and CP/UP load tester. From Valentin D'Emmanuele - France.
- [pfm](https://github.com/arv-sajeev/pfm) - DPDK implementation of a prototype on gNB-CU-UP.
- [srsRAN](https://github.com/srsran/srsRAN) - Open source SDR 4G/5G software suite from Software Radio Systems (SRS).
- [UERANSIM](https://github.com/aligungr/UERANSIM) - Open source 5G UE and RAN (gNodeB) implementation. 

## Core Network

- [5GCore](https://github.com/dukl/5gCore) - 5G system written in python.
- [free5GC](https://github.com/free5gc/free5gc) - Open source 5G core network base on 3GPP R15.
- [Internship-5GCN](https://github.com/bubblecounter/Internship-5GCN) - Implementation of RESTful Web Services between 5G Control Plane Nodes(AMF,NRF,SMF,UDM).
- [OAI-CN](https://gitlab.eurecom.fr/oai/cn5g) - This project implements a 4G LTE Evolved Packet Core (EPC) and 5G Core Network.
- [open5gs](https://github.com/open5gs/open5gs) - Open5GS is a C-language Open Source implementation of 5GC and EPC, i.e. the core network of NR/LTE network (Release-16).

## Platforms

- [5G-EmPOWER](https://github.com/5g-empower/empower-runtime) - 5G-EmPOWER is a mobile network operating system designed for heterogeneous wireless/mobile networks.
- [CNF Testbed](https://github.com/cncf/cnf-testbed) - Cloud-native Network Function (CNF) Testbed.
- [DANM](https://github.com/nokia/danm) - TelCo grade network management in a Kubernetes cluster.
- [docker_open5gs with IMS](https://github.com/miaoski/docker_open5gs) - Docker files to run open5gs in a docker.
- [free5gc-k8s](https://github.com/sumichaaan/free5gc-k8s) - Dockerized Free5gc and Kubernetes Manifests.
- [free5gc-cli](https://github.com/shynuu/free5gc-cli) - An interactive CLI for free5gc.
- [free5gmano](https://github.com/free5gmano/free5gmano) - This is a 5G MANO (Management and Network Orchestration) project developed that refer to 3GPP TS 28.531, TS 28.532 Release 15 (R15).
- [my5G-core](https://github.com/my5G/my5G-core) - Currently, my5G-core is a fork of the free5GC project, with some extensions to facilitate the deployment.
- [Magma](https://github.com/magma/magma) - Platform for building access networks and modular network services.
- [Magma Orchestrator](https://github.com/ShubhamTatvamasi/magma-galaxy) - Ansible Deployment for Magma Orchestrator.
- [ONAP](https://www.onap.org/) - Open Network Automation Platform.
- [Open Source MANO](https://osm.etsi.org/) - OSM is delivering an open source Management and Orchestration (MANO) stack aligned with ETSI NFV Information Models.
- [openNetVM](https://github.com/sdnfv/openNetVM) - A high performance container-based NFV platform from GW and UCR.
- [opnfv](https://www.opnfv.org/) - Open Platform for NFV (OPNFV) facilitates the development and evolution of NFV components across various open source ecosystems.
- [Polycube](https://github.com/polycube-network/polycube) - eBPF/XDP-based software framework for fast network services running in the Linux kernel.
- [towards5GS-helm](https://github.com/Orange-OpenSource/towards5gs-helm) - Provide helm charts in order deploy on one click a 5G system on top of Kubernetes.
- [x-k8s](https://github.com/ITRI-ICL-Peregrine/x-k8s) - ITRI's Kubernetes platform for 5G Edge VNF.
- [Zato](https://zato.io/en/industry/telecom/index.html) - Python-based, open-source platform for orchestration, automation and integrations of APIs or hardware assets.

## NFs

- [NextMN-UPF](https://github.com/louisroyer/nextmn-upf) - An experimental 5G UPF implementation
- [omec-project/upf](https://github.com/omec-project/upf) - This UPF implementation is actively used as part of the Aether platform in conjunction with the SD-Core mobile core control plane.
- [OpenUPF](https://github.com/5GOpenUPF/openupf) - A 3GPP R16 compliant open source 5G core UPF (User Plane Function).
- [SD-Core](https://docs.sd-core.opennetworking.org/master/index.html) - Open Source 5G Network Functions orchestrated through Kubernetes
- [UPF-EPC](https://github.com/omec-project/upf-epc) - 4G/5G Mobile core user plane.
- [up4](https://github.com/omec-project/up4) - ONOS app and P4 program abstracting a network of switches as one big 4G/5G UPF.
- [upg-vpp](https://github.com/travelping/upg-vpp) - User Plane Gateway (UPG) based on VPP.
- [upf-xdp](https://github.com/801room/upf-xdp) - It is just a toy, but it shows the possibility of using xdp to implement 5g upf.
- [upf_p4_poc](https://github.com/801room/upf_p4_poc) - This project is a proof of concept for 5g upf based on p4.
- [vpp](https://github.com/travelping/vpp) - 5G User Plane Function (UPF) based on VPP.
- [upf-bpf](https://github.com/navarrothiago/upf-bpf) - An in-kernel solution based on XDP for 5G UPF.

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

### eap-5g

- [strongswan-eap-5g-plugin](https://github.com/syujy/strongswan-eap-5g-plugin) - EAP-5g plugin for strongswan.

### GTP

- [dpdk_gtp_gateway](https://github.com/edingroot/dpdk_gtp_gateway) - DPDK based GTPv1 gateway.
- [gtp5g](https://github.com/PrinzOwO/gtp5g) - Linux kernel module 5G GTP-U.
- [gtplib](https://github.com/travelping/gtplib) - Erlang GTPv1/GTPv2 library.
- [gtpv2](https://github.com/blorticus/gtpv2) - GPRS Tunneling Protocol Library for golang.
- [go-gtp](https://github.com/wmnsk/go-gtp) - GTP(GPRS Tunneling Protocol) implemented in pure Golang.

### SCTP

- [ishidawataru/sctp](https://github.com/ishidawataru/sctp) - SCTP library for the Go programming language.
- [pion/sctp](https://github.com/pion/sctp) - A Go implementation of SCTP.
- [sctp-go](https://github.com/thebagchi/sctp-go) - SCTP Library for golang.
- [usrsctp](https://github.com/sctplab/usrsctp) - A portable SCTP userland stack.

### NGAP

- [ngap](https://github.com/haodhh/ngap) - Encode Decode NGAP for 5G.

### NAS

- [NAS-5GS](https://github.com/hzane/nas-5gs) - Routines for Non-Access-Stratum (NAS) protocol for NAS-NR(5GS).

### DTLS

- [pion/dtls](https://github.com/pion/dtls) - DTLS 1.2 Server/Client implementation for Go.

### PFCP

- [go-pfcp](https://github.com/wmnsk/go-pfcp) - PFCP (Packet Forwarding Control Protocol) implementation in Golang.
- [pfcplib](https://github.com/travelping/pfcplib) - Erlang library for encoding and decoding Packet Forwarding Control Protocol (PFCP) frames.

### Diameter

- [go-diameter](https://github.com/fiorix/go-diameter) - Diameter stack and Base Protocol (RFC 6733) for the Go programming language.

## Tools

- [3gpp.guru](https://3gpp.guru) - Look up 3GPP abbreviations.
- [3GPP Bibtex entry generator](https://github.com/martisak/3gpp-citations) - Generate .bib-file for 3GPP specifications.
- [5G Trace Visualizer](https://github.com/telekom/5g-trace-visualizer) - Tools to generate call flows from pcap.
- [5GC_APIs](https://github.com/jdegre/5GC_APIs) - RESTful APIs of main Network Functions in the 3GPP 5G Core Network.
- [5G_ciphered_NAS_decipher_tool](https://github.com/jimtangshfx/5G_ciphered_NAS_decipher_tool) - A python tool to decipher/decrypt 5G ciphered NAS message and export plain 5G NAS into wireshark pcap file.
- [5GC build](https://github.com/H21lab/5GC_build) - Project to use OpenAPI generators to build code from 5GC_API.
- [5g ldpc codes](https://github.com/xiaoshaoning/5g-ldpc) - 5g ldpc codes.
- [MCC_MNC](https://github.com/P1sec/MCC_MNC) - Providing accurate JSON and Python dicts about the many public information available about MNO.
- [MilenageTest](https://github.com/jimtangshfx/MilenageTest) - 3G/4G/5G authentication test troubleshooting tool.
- [New Radio 5G Physical layer utilities](https://github.com/prtkmishra/New_Radio_5G_Utils) - This repository contains Physical layer utilities based on 3GPP specs for NR 5G.
- [nrarfcn](https://github.com/blevic/nrarfcn) - A 5G NR-ARFCN calculator, as a Python package
- [pysim5g](https://github.com/edwardoughton/pysim5g) - Open-source techno-economic assessment framework for 5G deployment.
- [speX](https://github.com/CoRfr/spex-3gpp) - A WebService to deliver 3GPP specifications.
- [5GCoreNetSDK](https://github.com/5GCoreNet/5GCoreNetSDK) - 5GCoreNetSDK is a fully-featured Golang SDK for developing inside 5GC (Release-18).

## Research

- [5G-Core-gRPC-SBA](https://github.com/iithnewslab/SBA-gRPC-5G) - This repository is the proof of concept for Service Based Architecture of 5G using gRPC.
- [5GMdata](https://github.com/lasseufpa/5gm-data) - Datasets and code for machine learning in 5G mmWave MIMO systems involving mobility (5GMdata).
- [Beamformed Fingerprint Learning](https://github.com/gante/mmWave-localization-learning) - ML-based positioning method from mmWave transmissions - with high accuracy and energy efficiency.
- [DeepCoMP](https://github.com/CN-UPB/DeepCoMP) - Dynamic multi-cell selection for cooperative multipoint (CoMP) using (multi-agent) deep reinforcement learning 
- [mobile-env](https://github.com/stefanbschneider/mobile-env) - An open, minimalist Gym environment for autonomous coordination in wireless mobile networks
- [Network Function Framework for Go (former YANFF)](https://github.com/intel-go/nff-go) - NFF-Go -Network Function Framework for GO (former YANFF).
- [SliceSim](https://github.com/cerob/slicesim) - 5G Network Slicing Simulation.
- [Sub-6 Predicts mmWave Beam-forming Vectors](https://github.com/malrabeiah/Sub6-Preds-mmWave) - Using sub-6 GHz channels to predict mmWave beams and link blockage.

## Documents

- [3gpp-documentation](https://github.com/emanuelfreitas/3gpp-documentation) - 3GPP Documentation.
- [5G Mobile Networks: A Systems Approach](https://github.com/SystemsApproach/5G) - Open source eBook for 5G system.
- [nickel0/3GPP-Overall-Architecture](https://github.com/nickel0/3GPP-Overall-Architecture) - 3GPP Overall Architecture and Specifications including 2G, 3G, 4G, and 5G Systems up to Release-17.
- [vigp/awesome-5g](https://github.com/vigp/awesome-5g) - Knowledge base for 5G wireless.

