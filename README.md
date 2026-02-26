# test-styles COP

*description of the COP*

**COP timeframe** 2026-02-12 - 2026-05-21

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-proto.github.io/test-styles](https://cra-proto.github.io/test-styles)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-02-26

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(Tax credits and benefits for individuals)
    node4(Canada child benefit #40;CCB#41;)
    node5(Canada child benefit #40;CCB#41;<br>Who can apply)
    node1 --> node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/services/taxes.html" _blank
    click node3 "https://www.canada.ca/en/services/taxes/child-and-family-benefits.html" _blank
    click node4 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/canada-child-benefit.html" _blank
    click node5 "https://www.canada.ca/en/revenue-agency/services/child-family-benefits/canada-child-benefit/who-apply.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node5 inscope
```
