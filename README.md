### CS389 HW3: Testy Cache.

#### David Herrero-Quevedo & Michael Kalange

#### Instructions

g++ -std=c++11 -Wall -o 010-TestCase 010-TestCase.cpp && 010-TestCase --success -I$(CATCH_SINGLE_INCLUDE)

#### Our cache

Test | Description | Status
--- | --- | ---
Set/Get          | "A value in the cache can be retrieved." |  PASS
Set/Get          | "The size of the value returned is correct."                            |  FAIL
Set/Get          | "Getting a value not in the cache returns null."                      |  PASS
Space_used  | "Ensure space_used is 0 when no values are inserted."        |  PASS
Space_used  | "Ensure space_used is correct when cache has k/v's in it."  |  PASS
Del                 | "Delete removes the key/value from the cache."                   |  PASS
Del                 | "Delete on k/v not in cache has no effect."                            |  PASS

#### Sierra and Mercy's cache

Test | Status
--- | ---
Set/Get          |  PASS
Set/Get          |  FAIL
Set/Get          |  PASS
Space_used  |  PASS
Space_used  |  PASS
Del                 |  PASS
Del                 |  PASS