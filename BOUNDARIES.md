# A2A-SIN-Beeper Boundaries

## Role
`A2A-SIN-Beeper` owns Beeper messaging integration, routing workflows, and Beeper-specific contracts.

## This repo should own
- Beeper integration, routing, and coordination flows
- message evidence, recovery, sync, and delivery handling
- Beeper contracts used by downstream automation agents
- runbooks tied to Beeper integration on OpenSIN platforms

## This repo must not own
- unrelated messaging surfaces or generic app automation
- browser/runtime infrastructure
- organization SSOT docs or architecture canon
- downstream business logic unrelated to Beeper ownership

## Hard rules
- Keep changes scoped to Beeper messaging integration and routing.
- Move non-Beeper behavior back to the repos that own it.
- Keep reusable contracts focused on message coordination and delivery.
