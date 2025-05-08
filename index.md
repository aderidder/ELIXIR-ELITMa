---
title: ELITMa
---


<img src="{{site.baseurl}}/assets/img/main_logo.svg" alt="ELIXIR-ELITMa" class="size-small" />

## Empowering ELIXIR staff members
The ELIXIR network has grown significantly in recent years, with several new Nodes and Communities joining. To effectively support the planning and delivery of Node activities such as coordination, training, service provision, infrastructure management, events and communication, it’s essential to empower new and existing ELIXIR members in growing their skills and capacities. Members also need easy access to key information, including clear onboarding pathways to participate in the wide range of activities across ELIXIR.

In 2019, the ELITMa management training programme was initiated to address these needs – ELITMa modules are designed for ELIXIR Node staff. In 2023, five modules were delivered, covering topics such as governance, Node data management strategy, strategic management, financial management and project management. In the near future, the programme will offer ten modular training courses on operations and management, including technical management. These activities are part of the EU-funded ELIXIR-STEERS project and PeoplePulse, the internally-funded ELIXIR project.

## By the Nodes, for the Nodes 
Experts from the Nodes develop, lead and deliver ELITMa modules to benefit all ELIXIR members. Each module has a dedicated contact person at the ELIXIR Hub, to ensure alignment of strategic goals between the Hub and Nodes. As part of the PeoplePulse Project, an ELITMa Steering Group will be set up, with representatives from the Hub and Nodes. This group will oversee and guide the content, development and integration of the growing ELITMa portfolio.

Current efforts focus on consolidating and rolling out existing modules, as well as designing, developing and delivering the newly-planned ones. This will involve collaboration between ELIXIR-STEERS and the PeoplePulse internal project. The team will also engage with the wider ELIXIR community, inviting colleagues to contribute their expertise to ELITMa module development. The course portfolio will be developed using Training Platform resources and best practices, and showcased in the Training Platform portal SPLASH – short for Skills, Professional development, Learning Assessment, Support and Help. The ELITMa development team will also coordinate with the Professionalising Careers in Research Infrastructures Focus Group. Please contact Celia van Gelder at celia.vangelder@health-ri.nl if you would like to contribute.

## ELITMa module overview
A comprehensive introduction to European and global research infrastructures, focusing on ELIXIR’s role and associated modules designed to enhance skills in various areas such as data management, strategic management, leadership and communication. Each module targets specific roles within ELIXIR Nodes, offering practical tools and best practices.

<div class="gridlayout">
  {% for module in site.data.modules %}
    <div class="gridlayout-cell">
        <span class="icon">{{ module.icon }}</span><a href="{{ module.url }}"><b>{{ module.title }}</b></a>
    </div>
  {% endfor %}
</div>
