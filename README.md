# HW14
BE 534
Peter Moma


When used the program should 'splode the word as in: https://codingbat.com/prob/p118366

'Given a non-empty string like "Code" return a string like "CCoCodCode".'


```
$ ./open.py
usage: open.py [-h] Word
open.py: error: the following arguments are required: Word
$ ./open.py -h
usage: open.py [-h] Word

A Dynamite Python script

positional arguments:
  Word        Your word to be 'sploded

optional arguments:
  -h, --help  show this help message and exit
  
$ ./open.py Foo
FFoFoo

$ ./open.py Python
PPyPytPythPythoPython

$ ./open.py foobarbaz
ffofoofoobfoobafoobarfoobarbfoobarbafoobarbaz    
 
$ make test
python3 -m pytest -v test.py
========================================================================================== test session starts ==========================================================================================
platform linux -- Python 3.7.1, pytest-4.0.2, py-1.7.0, pluggy-0.8.0 -- /TOPSECRET
cachedir: .pytest_cache
rootdir: REDACTED, inifile:
plugins: remotedata-0.3.1, openfiles-0.3.1, doctestplus-0.2.0, arraydiff-0.3
collected 5 items                                                                                                                                                                                       

test.py::test_exists PASSED                                                                                                                                                                       [ 20%]
test.py::test_usage PASSED                                                                                                                                                                        [ 40%]
test.py::test_word1 PASSED                                                                                                                                                                        [ 60%]
test.py::test_word2 PASSED                                                                                                                                                                        [ 80%]
test.py::test_word3 PASSED                                                                                                                                                                        [100%]

======================================================================================= 5 passed in 0.42 seconds ========================================================================================
  ```




# Author
Peter Moma
pmoma@email.arizona.edu
