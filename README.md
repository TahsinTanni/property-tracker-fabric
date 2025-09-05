## property-tracker-fabric

Property Tracker Application on Hyperledger Fabric

## Project Overview
This project develops a blockchain-based application for tracking property details securely using Hyperledger Fabric. The application facilitates recording and managing comprehensive property information including address, city, property size, owner name, and property type. Each property is uniquely identified by a unique ID to ensure reliable referencing and traceability.

This solution leverages blockchain technology to provide a transparent, tamper-resistant ledger of property assets, enhancing trustworthiness and accountability in property management.

## Features
The Property Tracker Application supports the following core functionalities:

# Add New Properties: Users can register new properties in the ledger with detailed attributes.

# View All Properties: Users have access to view the entire list of registered properties.

# Search Properties: Users can search properties by:

# Unique Property ID

# City Name

# Update Property Information: Allows users to modify existing property details stored on the blockchain.

## Property Attributes
Each tracked property contains the following data fields:

Unique ID (identifier)

Address

City

Property Size

Owner Name

Property Type

## Architecture & Flow
The property tracking system follows a clear transaction flow for querying and updating data via the blockchain API and chaincode, based on a predefined network setup analogous 
The architecture ensures data integrity and consistency in property state management.

## Prerequisites

Node.js

Hyperledger Fabric environment setup

Wallet and user credentials configured 

Installation

Clone this repository.

Ensure your Hyperledger Fabric network is running and accessible.

Use the existing chaincode configuration and wallet setup.

Run the application APIs to interact with the blockchain network.
