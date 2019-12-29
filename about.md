---
layout: page
title: About
permalink: /about/
---

{% raw %}<script src="https://cdnjs.cloudflare.com/ajax/libs/mermaid/8.4.4/mermaid.min.js"></script>{% endraw %}

## What?

<div class="container" >
  <div class="row">
    <div class="col-6">
    Open Tribes is a platform that allows anyone no matter who and where they are to participate in interesting, meaningful projects.  
    </div>
    <div class="col-6" style="maring: 0 auto;">
      <img src="https://raw.githubusercontent.com/open-tribes/open-tribes.github.io/master/tribes.png" alt="Tribes">
    </div>
  </div>
</div>







## How?

<div class="container" >
  <div class="row">
    <div class="col-6">
    It all starts with project proposals which consist of a specific goal, a rough plan and a description that motivates why the project is interesting. Anyone can propose new projects and browse through a list of all project proposals. <br><br> Once a sufficient number of users has expressed interest in a project (typically 3-5), a starting date is announced by the project leader. At the starting date, the participants meet online to discuss the project plan. They discussion continues afterwards asynchronously through chat discussions and shared notes. Moreover, there are weekly online live meetings to discuss the everyone's progress and the next steps. <br><br> Each project ends with a deliverable. This could be a paper that summarizes the project's results, but also an improved Wikipedia entry or something completely different.
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
    Sarah-->|participates|projectA
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

## Why?

<div class="container" >
  <div class="row">
        <div class="col-6">
In the current academic system an incredibly large talent pool is locked out from participating. <br><br>
          
Most interesting projects never get picked up because they are not the kind of thing you can get funding for. The current funding structures favor monocultures since in order to [rake up citations](https://arxiv.org/abs/1603.01204) you must publish papers on topics that attract many papers by other researchers. 
    </div>
    <div class="col-6" style="maring: 0 auto;">
      <img src="https://raw.githubusercontent.com/open-tribes/open-tribes.github.io/master/academic.png" alt="Academic System">
    </div>
  </div>
</div>


Important contributes like the reduction of [research debt](https://distill.pub/2017/research-debt/) are not valued at all and even considered a waste of time. In addition, there is no funding for [risky research](https://physicstoday.scitation.org/doi/10.1063/1.1996476) and thus most researchers only carry out incremental, planable research. <br><br>

Another root cause for the [diminishing returns in science](https://www.theatlantic.com/science/archive/2018/11/diminishing-returns-science/575665/) is that "[traditionally taught science and mathematics teach little except obedience](https://arxiv.org/abs/physics/0512202)". Since no one is trying to reduce research debt and the teaching methods are so antiquated, most disciplines have failed to "[build a portal for most people to even understand what the issues are, what are the objects, what is the game?](http://podcasts.joerogan.net/podcasts/eric-weinstein-2)" <br><br>

Motivated by these observations, we want to provide an alternative framework that allows anyone to participate, to learn, and to discover [previously-unknown truths](https://meaningness.com/metablog/upgrade-your-cargo-cult). 



### Contact

[jakobschwich@gmail.com](mailto:jakobschwich@gmail.com)
