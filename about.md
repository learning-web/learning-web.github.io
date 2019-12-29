---
layout: page
title: About
permalink: /about/
---

{% raw %}<script src="https://cdnjs.cloudflare.com/ajax/libs/mermaid/8.4.4/mermaid.min.js"></script>{% endraw %}


<div class="container" >
  <div class="row">
    <div class="col-6">
    It all starts with project proposals. Anyone can propose new projects which should consists of a specific goal, a rough plan and a description that motivates why the project is interesting. Users can browse through a list of all project proposals and express interest in particpating. Once a sufficient number of users has expressed interest in a project (typically 3-5), a starting date is announced by the project leader. At the starting date, the participants meet online to discuss the project plan. They discussion continues afterwards asynchronously through chat discussions and shared notes. Moreover, there are weekly online live meetings to discuss the everyone's progress and the next steps. Each project ends with a deliverable. This could be a paper, but also an improved Wikipedia entry or something completely different.
    </div>
    <div class="col-6" style="maring: 0 auto;">
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
    </div>
  </div>
</div>




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
