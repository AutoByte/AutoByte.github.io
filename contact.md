---
title: Contact
layout: default-contact
---

#Contact Us




{% yuml %}
[Note: Cosmic Class Diagram {bg:lightblue}]
[Player|email:string;password:enc-String|login();logout();landTf();splitTf()]
[Player]<>1-*>[TaskForce]
[Player]<>1-*>[Star]
[Star]<>1-*>[Planet]
{% endyuml %}