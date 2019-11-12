# QuestN - Multi-Quest spaces
*QuestN* provides ability for users to create their own virtual spaces, and invite others into them. It does this using an external server hosted on (AWS|Azure|Whatever).

It acts much as a Mog server: each player reports their actions to a central server, which then validates and sends state update packets to all nearby users.

## Introduction
This is a prototype WIP. Nothing to see here yet.

## Building
Should build out of the box. All externalities are either directly included in the repo, or proscribed via external Packages.

Some of those Packages are also run by me, so I try to keep everything up to date.

## Dependancies
Fuck VRTK.

## Usage
Run the 'Start' scene.

## Testing
There are both Editor- and Runtime-Test suites.

## Known Issues
Only supports Occulus at the moment. I am focusing on the Quest and betting that Quest2 will leapfrog the competition.

## Future Work
Ideally this is a purely P2P (Peer to Peer) application, which does not require a central Arbration Server.
