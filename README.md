# API Diner

An interactive team game about web services, set in a diner kitchen. Built for a presentation on **REST vs SOAP**.

The client is the customer, the API is the waiter, and the server is the kitchen. Two teams compete to serve orders correctly and win the night.


## What it covers

- HTTP methods: GET, POST, PUT, DELETE
- Status codes: 200, 201, 204, 400, 404, 500
- REST vs SOAP, and when to choose which
- JSON and XML
- The SOAP message: Envelope, Header, Body, Fault
- WSDL, HTTPS and WS-Security
- REST constraints: stateless, cacheable, layered system, uniform interface

## The game

| Section | How it plays |
|---|---|
| **Quiz** (4 rounds) | Teams take turns answering order tickets before a 15-second timer runs out. Faster answers earn more points. |
| **Burger builder** | Each correct answer adds a layer to the burger. A perfect burger earns a bonus. |
| **Rush hour** | Orders roll along a conveyor belt. Sort each one into the REST pot or the SOAP pot before it falls off. |
| **The critic's table** | Both teams secretly bet points and lock in an answer. A right answer doubles the bet, a wrong one loses it. |

## How to play

1. Open the link on the presentation laptop and press **F** for full screen.
2. Split the room into two teams. Click a team name to rename it.
3. The presenter enters each team's answer:
   - **Quiz and burger builder:** keys `1`–`4`, then `Space` for the next order
   - **Rush hour:** `←` for REST, `→` for SOAP
   - **Critic's table:** left team bets with `1` `2` `3` and answers with `Q` `W` `E`; right team bets with `8` `9` `0` and answers with `I` `O` `P`
4. In the critic's table, teams whisper their answer so the other team can't copy it.

A full game takes about 8 to 10 minutes.

## Run it locally

No installation needed. Download `index.html` and open it in a browser. It also works offline, with simpler fonts.

## Built with

A single HTML file with plain HTML, CSS and JavaScript. No frameworks, no server, no data collected. Sounds are generated in the browser.
