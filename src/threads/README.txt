README

In order to add the alarm-mega test, I edited the following files:

pintos/src/tests/threads/tests.c
pintos/src/tests/threads/tests.h

These files required that a handle to test_alarm_mega was added in the array of known 
test functions.

pintos/src/tests/threads/alarm-wait.c

This file needed to be modified to include a method test_alarm_mega that tests 
5 threads with 70 interruptions.

pintos/src/tests/threads/alarm-mega.ck

This file needed to be added as a test case.

pintos/src/tests/threads/Rubric.alarm

This file needed to modified to include the alarm-mega test case.
