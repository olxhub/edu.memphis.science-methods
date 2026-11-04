# Ambitious Science Teaching — ELED 3261 science methods SBA

Scenario-based assessment for ELED 3261 (Science Methods for Inclusive
Elementary Classrooms) at the University of Memphis, built on the
Ambitious Science Teaching framework. Before a field placement, a teacher
candidate and four classmates study the transcript of their cooperating
teacher launching a fourth-grade unit on matter with a frozen Michigan
lake, argue about what the launch did with what four children offered,
replay it making her moves against the clock, and plan a launch of their
own for the same room.

## Layout

- `investigating-matter/` — Unit 1: Investigating Matter. One OLX course
  with its own `manifest.yaml`, cast, reference material, session, and the
  replay episodes (`replay/`). Namespace `wp` (from the unit's working
  title, "Whose Phenomenon?"; block ids keep that prefix). Later units go
  in sibling directories.
- Each unit directory carries `wp_study.olx`, the research-consent gate the
  study deployment lands on, and `consent.olx`, the form it shows.

The classroom, school, teacher, and children in the unit are fictional.
Built with [lo-blocks](https://github.com/olxhub/lo-blocks).
