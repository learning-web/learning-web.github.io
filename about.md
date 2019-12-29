---
layout: page
title: About
permalink: /about/
---

{% raw %}<script src="https://cdnjs.cloudflare.com/ajax/libs/mermaid/8.4.4/mermaid.min.js"></script>{% endraw %}

{% raw %}<div class="mermaid">
graph TD;
    id1(This is the text in the box);
    id2(This is the text in the boxss);
    id3(This is the text in the boxssz);
    id1-->|text|id2;
    id2-->id3;
</div>{% endraw %}

{% raw %}<div class="mermaid">
graph TB
    John-->|participates|projectA
    John-->|publishes|proposalA
    proposalA-->projectA
    proposalB-->projectB
    Sarah-->|participates|projectB
    Sarah-->|publishes|proposalB
    Sarah-->projectA
    Mike-->|participates|projectB
    projectA-->paper
    projectB-->website
    subgraph deliverables
    paper 
    website
    end
    subgraph proposals
    proposalA
    proposalB
    end
    subgraph projects
    projectA
    projectB
    end
    subgraph users
   John;
   Sarah;
    Mike;
    end
</div>{% endraw %}

### Types of Projects

- Reading Groups.
- Distillation.
- Research.


### Contact

[email@domain.com](mailto:email@domain.com)
