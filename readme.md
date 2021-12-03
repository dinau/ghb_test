## This is just a private practice and memo to use Git and Github.
## (a)
* Local side
    1. Make new **topic branch** on origin/master.
    1. Make some changes to source code.
    1. Commit them to **local repository**.
    1. Repeat form 2 some times. 
    1. In **topic barnch**, push self to git server. 
    * Server side:
        1. A **compare & pull request** becomes available. 
        1. Do merge **the pull request**.
    * Return local side:
        1. Do **fetch** from server.
        1. Do **fast forward** with **remote/origin/master**.
        1. Complete.

## (b)
1. Do change some source code **without topic branch**.
1. Commit them to local repository.
1. Repeat form 2 some times. 
1. In **topic branch**, push self to git server. 
1. On git server, a **compare & pull request** becomes available. 
1. Do merge **the pull request** on git server.


### first
* nim
    ```nim
    proc ntest(mee:uint8)=
        discard
    ```
#### second test
* ruby
    ```ruby
    def rtest
        if true
            print "ruby"
        end
    ```
##### third test
* c
    ```c
    const char*    t1;
    uint8_t        t2;
    int16_t ctest(void){
        return 5;
    }
        
    ```
