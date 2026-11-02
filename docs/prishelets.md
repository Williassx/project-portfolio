# Prishelets: A New Home for the Alien

**Status:** early Godot prototype, in development. This is a project overview, not a playable download or source release.

## Concept

After a crash landing on Earth, an alien explores the surroundings, collects materials and learns to make simple tools. A damaged ship provides the starting landmark. The larger survival and production systems are design goals, not a promise that they are complete.

## Prototype scope

The inspected project contains a test scene, a player and camera, a crashed ship, resource and pickup scenes, inventory and journal interfaces, and hand-crafting code. An earlier build screenshot in the [main overview](../README.md#prishelets--a-new-home-for-the-alien) shows the inventory and a fibre crafting action with temporary visuals. The screenshot is evidence of that build, not proof that all planned features work.

A local movement/camera check and a hand-crafting check were attempted on 2 November 2026. The movement/camera check passed. The hand-crafting check failed because its expected snapshot did not account for a `winter` field. The cause and impact have not been investigated in this portfolio audit.

## Design example: from manual work to production

*Adapted and condensed from the project's Obsidian design note on manual actions, campfires and early workstations. This describes a design direction, not a claim that all steps are implemented.*

1. Manual crafting requires the character to do the work. Interrupting an unfinished unit should preserve its input, while completed units remain available.
2. A manually driven machine could hold a loaded batch but needs the character to operate it; walking away pauses work.
3. A later powered machine could work without the character if a suitable energy source is connected.
4. Automation is a further design goal: equipment would receive materials and pass on results. Specific machines, energy and logistics remain to be designed and verified.

This staged approach makes the intended transition clear and gives each stage separate conditions to test. The Obsidian vault contains requirements, design decisions, handoffs and checks. This page is a deliberately selected, plain Markdown adaptation; Obsidian is not required to read it.

## Work process

Mykyta defines the direction and requirements, breaks work into tasks, directs AI coding agents, reviews their output and checks prototypes manually. AI tools assisted with code and documentation. Role cards and task descriptions are documentation, not evidence of continuously running agents. Test results and human acceptance are recorded separately.

