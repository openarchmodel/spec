Introduction
------------

OpenArchitectureModel is a *language for defining and querying software architecture models*.
Its main goal is to enable developers to define architecture elements in a standard way.

OpenArchitectureModel is an open standard developed by `Sheikh Mohammad Sajid`_.

This document describes version |release| of the :ref:`core <scope>` OpenArchitectureModel standard.
It is intended that it will be superseded by new incremental releases with additional features in the future.


.. _goals:

Design Goals
~~~~~~~~~~~~

.. index:: design goals, portability

The design goals of OpenArchitectureModel are the following:

* Fast, safe, and portable *semantics*:

  * **Well-defined**: fully and precisely defines the syntax.

  * **Language-independent**: does not privilege any particular language, programming model, or object model.

  * **Open**: programs can interoperate with their environment in a simple and universal manner.

* Efficient and portable *representation*:

  * **Modular**: programs can be split up in smaller parts that can be transmitted, cached, and consumed separately.

  * **Portable**: makes no architectural assumptions that are not broadly supported across modern hardware.


.. _scope:

Scope
~~~~~

At its core, OpenArchitectureModel is a model for storing and retrieving data about software elements.
To encompass their variety and enable maximum reuse, the OpenArchitectureModel specification is split and layered into several documents.

This document is concerned with the core layer of OpenArchitectureModel.
It defines the base model, query syntax, validation, and execution semantics.
It does not, however, define how OpenArchitectureModel data are stored within a specific environment they execute in, nor how they are invoked from such an environment.


.. index:: ! module

.. index::  Unicode, name, text format, UTF-8, character
.. _dependencies:

