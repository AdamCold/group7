**USE CASE: 1 Retrieve List of Countries in the world by Population Order largest to smallest**
===============================================================================

**CHARACTERISTIC INFORMATION**
================================

**Goal in Context**
===================

As an Analyst, I want to retrieve a list of all countries in the world organized by their population from largest to smallest, so that I can use this information to assist the understanding of the demographic distribution across countries in the world.

**Scope**
===========
 
organizational black box

**Level**
==========

Primary task.

**Preconditions**
=================

The system has access to a database containing the population data for all countries in the world.

**Success End Condition**
===============================

A list of countries in the world, ordered by population from largest to smallest, is provided to the Analyst.

**Failed End Condition**
========================

No list is generated, or an error occurs during the retrieval process the system will shows "Failed to get country details".

**Primary Actor**
==================

Analyst 

**Trigger**
===========

A request for population information is sent to Analyst by organization. Analyst initiates the request to retrieve the list of countries in the world organized by population largest to smallest.

**MAIN SUCCESS SCENARIO**
===========================

1. The analyst initiates the request to retrieve the list of countries in the world organized by population order.
2. The system receives the request.
3. The system retrieves the population data of all countries in the world from the database.
4. The system organizes the list of countries in the world from largest population to smallest.
5. The system provides the ordered list of countries in the world from largest to smallest population to the analyst according to organization request. 

**EXTENSIONS**
================

In step 3,

1. if there is an error during the retrieval or processing of data, the system informs the analyst about the issue.
2. if the database does not contain the required population data, the system informs the analyst that the information is unavailable.

**SUB-VARIATIONS**
====================

None.

**SCHEDULE**
===============

DUE DATE: 2/2/2024

