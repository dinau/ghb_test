<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [This is just a private practice and memo to use Git and Github.](#this-is-just-a-private-practice-and-memo-to-use-git-and-github)
  - [Local side (1)](#local-side-1)
  - [Server side:](#server-side)
  - [Return local side:](#return-local-side)
  - [Local side (2)](#local-side-2)
  - [Nim lang](#nim-lang)
  - [Ruby lang](#ruby-lang)
  - [C lang](#c-lang)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

### This is just a private practice and memo to use Git and Github.

#### Local side (1)

---

1. Make new `topic branch` on origin/master.
1. Make some changes to source code.
1. Commit them to `local repository`.
1. Repeat form 2. some times. 
1. In `topic barnch`, push self to git server. 

#### Server side:

---

1. A `compare & pull request`  becomes available. 
1. Push `Crete pull request`.
1. Push `Merge pull request`.
1. or select `Rebase and merge`.
1. Wait for a while.
1. Push `Confirm ...` .

####  Return local side:

---

1. Do `fetch` from server.
1. Do `fast forward` with `remote/origin/master`.
1. Complete.

#### Local side (2)

---

1. Do change some source code `without topic branch`.
1. Commit them to local repository.
1. Repeat form 2 some times. 
1. In `topic branch`, push self to git server. 
1. On git server, a `compare & pull request` becomes available. 
1. Do merge `the pull request` on git server.


#### Nim lang

---

- nim

   ```nim
   proc ntest(mee:uint8) =
       discard
   ```

#### Ruby lang

--- 

- ruby

   ```ruby
   def rtest
       if true
           print "ruby"
       end
   ```

#### C lang

---

- c

   ```c
   const char*    t1;
   uint8_t        t2;
   int16_t ctest(void){
       return 5;
   }
   ```
