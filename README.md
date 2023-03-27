# Fuzzy-logic
Fuzzy logic implementation using python scikit-fuzzy

Example - 

Create a fuzzy rule-based system for Washing Machine.

Input Variables -
degree_of_dirt and type_of_dirt - (ranging between 1 to 100)

Rules -

1. If dirtness_of_clothes is Large and type_of_dirt is Greasy then wash_time is VeryLong
2. If dirtness_of_clothes is Medium and type_of_dirt is Greasy then wash_time is Long
3. If dirtness_of_clothes is Small and type_of_dirt is Greasy then wash_time is Long
4. If dirtness_of_clothes is Large and type_of_dirt is Medium then wash_time is Long
5. If dirtness_of_clothes is Medium and type_of_dirt is Medium then wash_time is Medium
6. If dirtness_of_clothes is Small and type_of_dirt is Medium then wash_time is Medium
7. If dirtness_of_clothes is Large and type_of_dirt is NotGreasy then wash_time is Medium
8. If dirtness_of_clothes is Medium and type_of_dirt is NotGreasy then wash_time is Short
9. If dirtness_of_clothes is Small and type_of_dirt is NotGreasy then wash_time is VeryShort




