# BEETLE: **BE**LLW**E**THER **T**RANSFER **LE**ARNER 
![](https://github.com/rahlk/BEETLE/blob/master/beetle.png?raw=true)
## Submission 

Published in IEEE Transactions on Software Engineering (TSE) 2020. ARXIV Link: https://arxiv.org/pdf/1911.01817.pdf

## Abstract

As software systems grow in complexity and the space of possible configurations increases exponentially, finding the near-optimal configuration
of a software system becomes challenging. Recent approaches address this challenge by learning performance models based on a sample set of
configurations. However, collecting enough sample configurations can be very expensive since each such sample requires configuring, compiling, and
executing the entire system using a complex test suite. When learning on new data is too expensive, it is possible to use Transfer Learning to “transfer”
old lessons to the new context. Traditional transfer learning has a number of challenges, specifically, (a) learning from excessive data takes excessive time,
and (b) the performance of the models built via transfer can deteriorate as a result of learning from a poor source. To resolve these problems, we propose
a novel transfer learning framework called BEETLE, which is a “bellwether”-based transfer learner that focuses on identifying and learning from the most
relevant source from amongst the old data. This paper evaluates BEETLE with 57 different software configuration problems based on five software systems
(a video encoder, an SAT solver, a SQL database, a high-performance C-compiler, and a streaming data analytics tool). In each of these cases, BEETLE
found configurations that are as good as or better than those found by other state-of-the-art transfer learners while requiring only a fraction ( 1
7th) of the measurements needed by those other methods. Based on these results, we say that BEETLE is a new high-water mark in optimally configuring software.

## Cite As

```
@article{krishna2020whence,
  title={Whence to Learn? Transferring Knowledge in Configurable Systems using BEETLE},
  author={Krishna, Rahul and Nair, Vivek and Jamshidi, Pooyan and Menzies, Tim},
  journal={IEEE Transactions on Software Engineering},
  year={2020},
  publisher={IEEE}
}
```

## Authors

+ Rahul Krishna(a), Vivek Nair(b), Pooyan Jamshidi(c), Tim Menzies (d)

  + (a) i.m.ralk@gmail.com, Columbia Univ., USA
  + (b) vivekaxl@gmail.com, Facebook, Inc., USA
  + (c) pooyan.jamshidi@gmail.com, Univ. South Carolina, USA
  + (d) tim.menzies@gmail.com, NC State Univ., USA

## Data

+ [Configuration Data](/src/Data)


## Source Code

+ [BEETLE](/src/)

## License

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or distribute this software, either in source code form or as a compiled binary, for any purpose, commercial or non-commercial, and by any means.

(BTW, it would be great to hear from you if you are using this material. But that is optional.)

In jurisdictions that recognize copyright laws, the author or authors of this software dedicate any and all copyright interest in the software to the public domain. We make this dedication for the benefit of the public at large and to the detriment of our heirs and successors. We intend this dedication to be an overt act of relinquishment in perpetuity of all present and future rights to this software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to http://unlicense.org
