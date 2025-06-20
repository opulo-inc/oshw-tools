---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# <span class="badge badge-primary">Github CI</span>
#<span class="badge badge-secondary">Web Service</span>
#<span class="badge badge-success">Open Source</span>
#<span class="badge badge-danger">Paid Service</span>
#<span class="badge badge-info">Free Service</span>

title: "What Tests and Certs Do I Need?"
layout: single
---

**Disclaimer**: Nothing on this website should be considered legal advice. You should always consult with a lawyer and a certification house in regards to the tests you are legally required to complete. Everything on this site should be considered anecdotal advice, and has no guarantee of being factually correct.

{% mermaid %}
graph TD;
    B[I want to sell my electronic device in Europe] --> |You need a CE mark| C[Intentional or Unintentional Radiator?]

    C --> |Intentional| D[Residential or Commercial?]
    C --> |Unintentional| E[Residential or Commercial?]

    D --> |Residential| G[**Doc:** CE DoC 
    **Test:** Class B 
    Intentional Radiator]
    D --> |Commercial| H[CE DoC Class A Intentional Radiator]

    E --> |Residential| I[CE DoC Class B Unintentional Radiator]
    E --> |Commercial| J[CE DoC Class A Unintentional Radiator]
{% endmermaid %}

{% mermaid %}
graph TD;
    B[I want to sell my electronic device in the US] --> |You need to be FCC compliant| C[Intentional or Unintentional Radiator?]

    C --> |Intentional| D[Doc: FCC Certification Filing
    Test: Part 15 Supbart C]
    C --> |Unintentional| E[Doc: FCC SDoC
    Test: Part 15 Supbart B]

{% endmermaid %}

{% mermaid %}
graph TD;
    C[Does my device have integrated Mains?]

    C --> |Yes| D[You need UL certification]
    C --> |No| E[You do not need UL certification]

{% endmermaid %}