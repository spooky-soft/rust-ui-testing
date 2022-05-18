# Rust UI Testing

Some tests to identify and evaluate various Rust UI options

Head to the [wiki](https://github.com/spooky-soft/ui-testing/wiki) to find out more.

The program is the [binarytrees](https://programming-language-benchmarks.vercel.app/problem/binarytrees) problem from [hanabi1224's language and compiler benchmarks](https://programming-language-benchmarks.vercel.app/). The source code for the Rust implementation can be found [here](https://github.com/hanabi1224/Programming-Language-Benchmarks/blob/main/bench/algorithm/binarytrees/4.rs). The program maintains an inner list of the item that was most recently compared to the search query, and the UI renders that value at about 60 Hz, just so I can see how much overhead each of the UI implementations brings with it, with the CLI program being used as a base for comparison.
