---
layout: page
title: About
permalink: /about/
---

{% raw %}<script src="https://cdnjs.cloudflare.com/ajax/libs/mermaid/8.4.4/mermaid.min.js"></script>{% endraw %}


{% raw %}<div class="mermaid">
graph TD;
    project proposal-->project starts (if sufficient interest);
    project starts (if sufficient interest)-->asynchron discussions, note sharing, live meetings in small cohorts;
    asynchron discussions, note sharing, live meetings in small cohorts-->deliverable
</div>{% endraw %}

{% raw %}<div class="mermaid">
stateDiagram
    [*] --> Still
    Still --> [*]

    Still --> Moving
    Moving --> Still
    Moving --> Crash
    Crash --> [*]
</div>{% endraw %}

{% raw %}<div class="mermaid">
gitGraph:
options
{
    "nodeSpacing": 150,
    "nodeRadius": 10
}
end
commit
branch newbranch
checkout newbranch
commit
commit
checkout master
commit
commit
merge newbranch
</div>{% endraw %}

### Types of Projects

- Reading Groups.
- Distillation.
- Research.


### Contact

[email@domain.com](mailto:email@domain.com)
