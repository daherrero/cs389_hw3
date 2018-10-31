### CS389 HW3: Testy Cache.

#### David Herrero-Quevedo & Michael Kalange

#### Instructions

g++ -std=c++11 -Wall -o tests_cache tests_cache.cpp\ ./tests_cache --success

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

Their cache doesn't have any compiling error using our setting and it passes all of our tests.

Test | Status
--- | ---
Set/Get          |  PASS
Set/Get          |  PASS
Set/Get          |  PASS
Space_used  |  PASS
Space_used  |  PASS
Del                 |  PASS
Del                 |  PASS

#### Naomi and Grant's cache

Their cache gives a warning when compiling
68:44: warning: field 'memused_' will be initialized after field 'hasher_'
but apart from that it passes all of our tests and runs perfectly.

Test | Status
--- | ---
Set/Get          |  PASS
Set/Get          |  PASS
Set/Get          |  PASS
Space_used  |  PASS
Space_used  |  PASS
Del                 |  PASS
Del                 |  PASS

