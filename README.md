# Rhythm Versioning System (RhyVer)

"Rhythm Versioning" or "RhyVer" helps teams build a release cadence. Using the format `vMAJOR.YYQ#.WEEK.PATCH`, it combines semantic versioning principles with granular temporal context, creating a natural rhythm for product releases. For example, `v2.24Q4.45.32` indicates a major version 2 release from the year 2024, quarter 4, week 45, with 32 backward compatible changes, enabling predictable release cycles and better alignment with business goals.


### Specification
```
vMAJOR.YYQ#.WEEK.PATCH[-PRERELEASE][+BUILD]

Example:   v2.24Q4.45.32-rc.2
            │ │    │  │  │
            │ │    │  │  └──  Release candidate
            │ │    │  └─────  Patch
            │ │    └────────  ISO week
            │ └─────────────  Year & quarter
            └───────────────  Major version
```

