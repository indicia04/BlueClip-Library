# BlueClip-Library
Statutes for App Sync

# BlueClip — Statute Library Data

Curated offence datasets consumed by the **BlueClip** app (publisher: Kraken Ink Inc.).

## Licensing
- **Underlying legislation** is reproduced from official government sources
  (e.g. BC Laws under the King's Printer Licence – British Columbia; federal
  statutes under the Reproduction of Federal Law Order). It is unofficial —
  always verify against the official source.
- **The curation** in these files — the selection, arrangement, plain-language
  titles, categorization, keywords, and short forms — is © Kraken Ink Inc. and
  is not licensed for reuse or redistribution.

## Files

| File | Statute |
|---|---|
| `PROV-BC-MVA.JSON` | BC Motor Vehicle Act & Regulations |
| `BC-LIQUORCONTROL` | BC Liquor Control and Licensing Act |
| `BC-TRESSPASSACT` | BC Trespass Act |
| `BC-WILDLIFEACT` | BC Wildlife Act |
| `BC-PASSENGERTRANSPORTATION` | BC Passenger Transportation Act |
| `BC-TRANSPORTDANGEROUSGOODS` | BC Transport of Dangerous Goods Act |
| `MUN-CHWK-FIREWORKS` | City of Chilliwack Fireworks Bylaw |
| `MUN-CHWK-NUISANCE` | City of Chilliwack Nuisance & Safety Bylaw |
| `FED-CRIMINALCODE.JSON` | Criminal Code of Canada |
| `FED-CDSA` | Controlled Drugs and Substances Act |
| `FED-YCJA` | Youth Criminal Justice Act |
| `FED-FISHERY` | Fisheries Act |
| `FED-CANADASHIPPING` | Canada Shipping Act, 2001 |
| `BC-CHARTER-DEMANDS` | Charter of Rights & Demands scripts card |

Each file is versioned; the app downloads updates when the `version` increases.
Statute files are **schema v2**: self-contained, including each statute's own
category definitions (title, icon, color).
