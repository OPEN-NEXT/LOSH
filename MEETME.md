Squashed Meeting Minutes
-

…of the OSHI working group

# 30-04-2020 – little kickoff

**Attendees:**

- Julieta
- Robin
- Erik
- Moe (minutes)

forgot to invite: Emilio (sorry, Emilio)

**Notes:**

- first draft for DB structure
  - various specified DBs with own onthologies, compatible with each other so that queries across different DBs can be performed
  - DB for OSH-Modules (target for v1.0 of this wikibase instance)
    - = OSH assemblies
    - which consist of
      - other OSH-Modules
      - OSH Components
      - standard parts
      - proprietary parts
  - DB for standard parts (optional target for v1.0)
  - ideas for further DBs:
    - manufacturers (to enable decentralised production of OSH as manufacturer metadata can be mapped over OSH metadata (tolerances, dimensions, material etc.))
    - funding programes (matchmaking between funders and cool projects)
    - scientific publications (e.g. in  cooperation with Journal of Open Hardware)
    - connection to Wikidata (to connect technical documentation with _real_ data :) )
- standards are the backbone of this structure
  - technical documentation: DIN SPEC 3105 & [TsDC](https://gitlab.com/OSEGermany/oh-tsdc/)
  - metadata: Open Know-How manifest v1.0 (+v2.0 (or hard fork) see below ↓)
    - first draft for metadata (and its structure) of OSH [here](OSH%20metadata.md)
    - will be pitched to Open Know-How working group
- we will make use of
  - guidelines & standard modules for onthologies (thanks @Julieta! 🎉)
  - [wbstack.com](wbstack.com) in order to test our onthology approaches

**ToDo:**

- @Moe sends a short project description and mail addresses of the working group to @Julieta, so…
- @Julieta creates an instance using [wbstack.com](wbstack.com)) where we all create accounts, and…
- @Julieta connects us/@Moe to a group of smart people who designed guidelines & standard modules for onthologies (Cristina Sarasua, ETH Zurich)
- @Moe invites everyone to GitHub repo
