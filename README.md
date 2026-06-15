
# Riot 
I had a dream.
I was lazy.
 I always thought I would work hard when I grew up.
 I always thought I'll put effort when it matters. 
 Now I know. 
 Now is all that matters,
 And all I want right now is to get into RIOT.

## Links
[Agent planning](https://docs.google.com/document/d/1vGnSk40fjbgmQI5ZqUuRZxLUeQVUPWlWfQGAfZToDHU/edit?usp=sharing)
[Video Script Planning](https://docs.google.com/document/d/1fuRnrWFvWlfO56szch4ggAWZeI4g-fNL1pPCX4eLr6Y/edit?usp=sharing)

 
 ## RoadMap ---[Lets do this]-->
My genius plan to get to Riot starts with determination 

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#1F2026', 'primaryBorderColor': '#FF4655', 'primaryTextColor': '#F3F4F6', 'lineColor': '#FF4655', 'fontSize': '14px'}}}%%
graph TD
    subgraph P1["Phase 1 — Foundations"]
        UE5["Learn UE5\nBlueprints · movement · maps"]
        CPP["Learn C++\nOOP · memory · game patterns"]
    end

    subgraph P2["Phase 2 — Prototyping"]
        UTIL["Functional UE5 prototype\nFirst-person controller · basic scene"]
    end

    subgraph P3["Phase 3 — Agent Design"]
        AGENT["Agent Planning: Genesis\nBelizean Controller · toolkit · lore"]
        CONCEPT["Design Agent Concept\nKit mechanics · visuals · balance"]
    end

    subgraph P4["Phase 4 — Game Build"]
        PLAYER["Functional Player Model\nFPS rig · animations · hitbox"]
        GAME["Bare-bones Valorant Replica\nGenesis playable in-engine"]
    end

    subgraph SIDE["Side Track — Riot API"]
        RIOT["Riot API Key\nAuth · endpoints · rate limits"]
        APP["Valorant Tracker App\nStats · ranks · match history"]
    end

    subgraph P5["Phase 5 — Content Expansion"]
        RECORD["Record Gameplay Showcase\nCapture Genesis kit + tracker UI"]
        SCRIPT["Video Script Execution\nHook · project breakdown · technical deep-dive"]
        EDIT["Edit and Post Video\nYouTube release · portfolio link"]
    end

    GOAL(["Goal: Riot Games Portfolio
    Portfolio: game + tracker + content"])

    %% Links
    UE5 --> UTIL
    CPP --> UTIL
    UTIL --> AGENT
    UTIL --> CONCEPT
    AGENT --> PLAYER
    CONCEPT --> PLAYER
    PLAYER --> GAME
    RIOT --> APP
    GAME --> RECORD
    APP -.->|integrates with| RECORD
    RECORD --> SCRIPT
    SCRIPT --> EDIT
    GAME --> GOAL
    APP --> GOAL
    EDIT --> GOAL

    %% Styling
    classDef foundation fill:#2A2640,stroke:#6B5CE7,color:#E2DBFF;
    classDef build fill:#162E2A,stroke:#00BFA5,color:#A7F3D0;
    classDef sidetrack fill:#2D1C1E,stroke:#FF4655,color:#FCA5A5;
    classDef content fill:#2C2519,stroke:#C4A35A,color:#FEF3C7;
    classDef goal fill:#332211,stroke:#FFD700,color:#FEF08A,font-weight:bold;

    class UE5,CPP foundation;
    class UTIL,AGENT,CONCEPT,PLAYER,GAME build;
    class RIOT,APP sidetrack;
    class RECORD,SCRIPT,EDIT content;
    class GOAL goal;
```
