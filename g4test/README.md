# How to run NTST?

0. please checkout directory setup in `loglog.sh` in both NTST, TNTST first. It should work without modifying.

1. enter `NTST/`, add the `type` of steppers you want to run into the loop. For example, if we want to test `G4ClassicalRK4`, we put 4 in there. 

2. ` sh loglog.sh`, and then you will obtain the data in `data.txt`, open the file and you can directly copy the data into your excel. 

3. enter `TNTST/`, and set the `type` as exactly you put into `NTST/`, in our case, put 4, as for `TClassicalRK4`. 

4. repeat above step 2. in `TNTST/` and you will obtain the data for templated version. 

# How to run test/?

1. `test/` for non-templated classes and `Ttest/` for templated classes.

2. compile: run `sh maketest.sh`.

3. correctness test: run `sh test.sh`. 
