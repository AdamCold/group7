USE CASE: 10 Retrieve List of cities in a country by Population Order largest to smallest
================================================================================

CHARACTERISTIC INFORMATION
=================================

Goal in Context
===================

As an Analyst, I want to retrieve a list of all cities in a country organized by their population from largest to smallest, so that I can use this information to assist the understanding of the demographic distribution across cities in a country.

Scope
==========
 
organizational black box

Level
==========

Primary task.

Preconditions
=================

The system has access to a database containing the population data for all cities of a country.

Success End Condition
=========================

A list of cities in a country, ordered by population from largest to smallest, is provided to the Analyst.

Failed End Condition
======================

No list is generated, or an error occurs during the retrieval process the system will show "Failed to get city details by country" message.

Primary Actor
=================

Analyst 

Trigger
============

A request for population information is sent to Analyst by organization. Analyst initiates the request to retrieve the list of cities in a country organized by population largest to smallest.

MAIN SUCCESS SCENARIO
==========================

1. The analyst initiates the request to retrieve the list of cities in a country organized by population largest to smallest.
2. The system receives the request.
3. The system retrieves the population data of all cities in a country from the database.
4. The system organizes the list of cities in a country from largest population to smallest.
5. The system provides the ordered list of cities in a country from largest to smallest population to the analyst according to organization request. 

EXTENSIONS
================

In step 3,

1. if there is an error during the retrieval or processing of data, the system informs the analyst about the issue.
2. if the database does not contain the required population data, the system informs the analyst that the information is unavailable.

SUB-VARIATIONS
====================

None.

SCHEDULE
================

DUE DATE: 9/2/2024
