# Network Inventory Dashboard

## Project Scope

I want to create a inventory dashboard for network managers to view networking devices on their networks, such as endpoints, switches, and routers. This project is part of the final for my web development course. The scope of this project will have a preconfigured set of devices, as well as features for adding and editing devices. In the future, this application could be set up with an API to request and receive information from actual networking equipment.

## Users

Network managers, home-lab owners, possibly useful for penetration testers

## Problems this Project Seeks to Solve

Simplifies management of networking devices by having all the information in one place, provides an intuitive, graphical interface to do this.

## Feature Examples

 - Sortable GUI for endpoints, switches, and routers
 - Add/Edit Devices
 - Preconfigured list of devices for demonstration purposes
 - Network Topology Mapper

## Main Screen Sketch

View main_screen_sketch.png

## Example Object

{ name: "RouterA", type: "Router", ip: "192.168.0.1", mask: "255.255.255.0", up: true, connections: ["SwitchA", "RouterB"] }

## Event Types

submit, click

## Human-Only Feature

Preconfigured list of network devices, and functions for reducing this list into lists of each type of network device (endpoint, switch, router)