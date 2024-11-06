Overview
--------

.. index:: concepts, value, instruction, function, table, module
.. _concepts:

Concepts
~~~~~~~~

OpenArchitectureModel is a high-level, SQL-like programming language.
This language is structured around the following concepts:

.. _organisation:

**Organization**
An organization operates as a single tenant, maintaining its own set of architectural information that is versioned collectively. Transactions are restricted to the scope of one organization and cannot extend across multiple organizations. User access and permissions are likewise confined to a single organization, ensuring isolated data governance and security at the tenant level.

.. _space:

**Space**
Spaces are functional areas within an organization, designed to group and manage related information specific to teams, departments, groups, or sections. These spaces follow a hierarchical structure, supporting multiple sub-levels to reflect organizational complexity. The hierarchical model ensures that information is organized according to business needs and roles, promoting streamlined workflows and role-based access management.

.. _application:

**Application**

.. _framework:

**Framework**

.. _profile:

**Profile**

.. _element:

**Element**

.. _extension:

**Extensions**

.. _release:

**Release**

.. _deployment:

**Deployment**

.. _adr:

**Architecture Decision Records**

.. _fitness:

**Fitness Functions**
