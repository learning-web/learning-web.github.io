---
layout: page
title: About
permalink: /about/
---

{% raw %}<script src="https://cdnjs.cloudflare.com/ajax/libs/mermaid/8.4.4/mermaid.min.js"></script>{% endraw %}

{% raw %}<div class="mermaid">
graph TB;
    id1(project proposal);
    id2(project starts);
    id31(discussions);
    id32(note sharing);
    id33(live meetings);
    id4(deliverable);
    id1-->|once there is sufficient interest|id2;
    id2-->id31;
    id2-->id32;
    id2-->id33;
    id31---id32;
    id32---id33;
    id31-->id4;
    id32-->id4;
    id33-->id4;
</div>{% endraw %}

{% raw %}<div class="mermaid">
graph LR
    proposalA(Noether's theorem);
    proposalB(stochastic quantization);
    projectA(Noether's theorem);
    projectB(stochastic quantization);
    deliverableA(arXiv paper);
    deliverableB(Wiki entry);
    John-->|participates|projectA
    John-->|publishes|proposalA
    proposalA-->projectA
    proposalB-->projectB
    Sarah-->|participates|projectB
    Sarah-->|publishes|proposalB
    Sarah-->projectA
    Mike-->|participates|projectB
    projectA-->deliverableA
    projectB-->deliverableB
    subgraph deliverables
    deliverableA 
    deliverableB
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
