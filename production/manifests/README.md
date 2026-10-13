# A World Between Us Asset Records

Copy `ASSET_TEMPLATE.json` for each real asset and fill it with observed values. It is a blank template, not evidence of a completed generation. An input asset record should include its asset ID, version, path, and hash when available.

Production status values are `planned`, `experimental`, `review`, `approved`, and `rejected`. Narrative status values are `established`, `provisional`, and `not_applicable`. Use a separate manifest for a start frame and its generated video; link them through `input_assets`.

Do not populate approval fields until the owner explicitly approves that asset and scope. Record approved narrative/design decisions in the development decision log as well when relevant.
