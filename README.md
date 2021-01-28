# CHAOS
Chris Home Automation Operating System

## Description
Core Control plane and API Server that exposes endpoints for executing commands and accessing information.
Dotnet Core server running in a Docker container, on a Raspberry Pi exposed on a local network. (Non Internet, yet.. maybe) 

## Stack
.NET Core 3.1 Server
Docker 

## API Endpoints
Example  
``` /api/v1/ping ``` - Pings the Endpoint  
``` /api/v1/commands ``` - Returns a list of availabe commands  
