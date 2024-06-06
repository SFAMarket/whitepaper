# SFA Market:

**Transforming Decentralized Storage with Storage Forward Agreements**

_NOTE: This document is a work in progress. Please check back regularly for updates!_

## Table of Contents

- [Abstract](#Abstract)

- [Introduction](#Introduction)

# Abstract

Decentralized storage faces significant challenges in terms of incentives and reliability, limiting its widespread adoption. SFA Market introduces Storage Forward Agreements (SFAs), an innovative solution in the crypto ecosystem that allows content publishers to ensure the availability of their data through a one-time payment, guaranteeing its storage for a defined period. Unlike the monthly subscription model of Web2, SFAs offer stability and predictability, better aligning incentives for publishers and hosts. Hosts must make a collateral deposit, which is refundable upon fulfilling the agreement, and can be penalized in case of non-compliance, ensuring the system's integrity. Additionally, SFAs allow for the transfer of responsibilities in a secondary market, providing flexibility, liquidity, and efficiency in decentralized storage. This innovative approach offers a robust and flexible solution to the current incentive challenges of data storage in the Web3 era.

# Introduction

Decentralized data storage has gained significant attention due to its ability to offer greater privacy, security, and control over data compared to traditional centralized solutions. Despite its benefits, the widespread adoption of decentralized storage technologies faces significant challenges, particularly in creating a robust incentive system that is fair for both publishers and storage providers.

In the Web2 model, incentives are primarily focused on storage usage or bandwidth, benefiting large corporations that can offer services on a large scale. This model does not adapt well to a decentralized environment, where infrastructure is distributed among many small providers. Additionally, transparency and verification of storage and bandwidth usage are challenging to implement and maintain in a truly decentralized system.

SFA Market proposes an innovative solution that redefines incentives in decentralized storage. Through Storage Forward Agreements (SFAs), content publishers can create agreements in open and transparent markets where hosts can choose to take on this responsibility. This ensures that their data will be available in the system for a defined period, eliminating the need for monthly subscriptions. This document details how SFA Market works to align incentives, improve the reliability and efficiency of storage, and facilitate the adoption of decentralized storage technologies.

# Antecedentes / Estado del Arte

Decentralized storage has seen remarkable growth with the introduction of technologies such as IPFS (InterPlanetary File System), Filecoin, Swarm Ethereum, Storj, among others. These platforms have established a solid foundation for distributed data storage, offering alternatives to traditional centralized solutions.

**IPFS**: is a protocol and network designed to create a peer-to-peer method of storing and sharing hypermedia in a distributed file system.

**Filecoin**: is a decentralized storage network that turns cloud storage into an algorithmic market.

**Storj**: is a decentralized cloud storage platform that uses encryption and file fragmentation.

**Sia**: is a decentralized cloud storage platform that uses smart contracts to ensure data integrity and availability.

**SWARM**: is a distributed storage platform and content distribution service native to Ethereum, designed to serve as a decentralized storage system.

Despite these advancements, significant limitations persist. Current incentive models often focus on storage and bandwidth usage, which may not be sustainable or equitable in a distributed environment. Additionally, verifying and validating storage can be complicated, impacting the system's reliability and efficiency.

SFA Market aims to overcome these limitations by introducing Storage Forward Agreements (SFAs). These agreements are essentially NFTs that are introduced into our smart contract, allow content publishers to create offers to store files through a one-time payment, ensuring their data will be available for a defined period. Hosts can accept to store the content in exchange for a collateral deposit, ensuring compliance with the agreement and providing a more secure and efficient solution for decentralized storage.

A similar case with nuanced qualities could be Sia, which allows publishers to upload files that will be maintained for a predetermined time defined by its blockchain, currently three months. Meanwhile Sia presents an all-in-one platform where they provide their own blockchain, wallet, host, and the terms of agreements seem predefined, SFA Market is more focus in cypherpunk principles, we are decided to build open tools that can be compatible and connectable with ecosystem tools also giving some freedom on qualities like TTL (time-to-live), pricing, collateral required and re-sell market (second market).

SFAs will add a new instrument to the EVm and a new form of free agreements between parties, allowing both publishers and storage providers to agree on the price of storing a document. Each NFT will have two transferable properties: the publisher and the storage provider, allowing users to transfer the obligation of storage or sell the publisher's right to the content. This creates the possibility of a secondary market where storage costs can fluctuate freely based on agreements, not necessarily tied to the tokens used as rewards and collateral.