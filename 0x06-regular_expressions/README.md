# Regular expression

In this project, I learned how to use regular expressions. I practiced building
them using Ruby's Oniguruma library.

All code in this directory was tested using [Rubular](https://rubular.com/). Rubular is a Ruby-based regular expression editor. It's a handy way to test regular expressions as you write them.

## Tasks :p
  the regular expression `hbn` with between 2-5 `t`'s in between `hb` and `n`.

* **2. Repetition Token #1**
  * [2-repetition_token_1.rb](./2-repetition_token_1.rb): Ruby script that matches
  the regular expression `hn` with 0 or 1 occurrences of `b` and 0 or 1
  occurrences of `t` in between `h` and `n`.


* **7. OMG WHY ARE YOU SHOUTING?**
  * [7-OMG_WHY_ARE_YOU_SHOUTING.rb](./7-OMG_WHY_ARE_YOU_SHOUTING.rb): Ruby script that
  matches regular expressions of uppercase letters.

* **8. Textme**
  * [100-textme.rb](./100-textme.rb): Ruby script that runs statistics on TextMe app text
  message transcations.
  * Output: `[SENDER],[RECEIVER],[FLAGS]` where
    * `[SENDER]` is the sender phone number or name (including country code
    if present).
    * `[RECEIVER]` is the receiver phone number or name (including country code
    if present).
    * `[FLAGS]` is the flags that were used.
