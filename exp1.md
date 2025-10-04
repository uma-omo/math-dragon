``` mermaid 
flowchart TD
    A["🏰 The Great Hogwarts<br/>Cake Sharing"] --> B["✨ THE GOLDEN RULE:<br/>Division is Fair-Sharing"]
    
    B --> C
    subgraph C [The Magical Spell Components]
        C1["🍰 The Treasure Pile<br/>(What you have to share)"]
        C2["📦 The Number of Chests<br/>(Who you're sharing with)"]
        C3["⚡ The Sharing Charm<br/>(The ÷ symbol)"]
    end
    
    C --> D
    subgraph D [Casting the Spell]
        D1["Start with 15 Golden Galleons"]
        D2["Share with 3 friends"]
        D3["Wave wand: 15 ÷ 3 = 5"]
        D4["Each gets 5 Galleons!"]
        
        D1 --> D2 --> D3 --> D4
    end
    
    D --> E
    subgraph E [Special Magical Cases]
        E1["🤔 The Curious Case of<br/>Leftover Knuts<br/>14 ÷ 3 = 4 R2"]
        E2["🎁 The Solitary Galleon<br/>9 ÷ 1 = 9<br/>(All for you!)"]
    end
    
    E --> F["🎯 Foundation Stone:<br/>Whenever you see ÷, ask<br/>'How do I share this fairly?'"]

    %% Styling for better visual flow
    class A,B,F importantNode
    class C1,C2,C3 spellComponents
    class D1,D2,D3,D4 castingProcess
    class E1,E2 specialCases

```
