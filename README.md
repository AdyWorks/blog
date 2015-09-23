I am a researcher and computer scientist. I was once in San Francisco, but am now traveling.

**Note**: Things may be a bit of a mess here while I de-jekyll all the previous posts. This may all go away if I find that jekyll actually did something valuable for me, but at this point I wouldn't worry about that.


### Posts

---

#### [An introduction to Timely Dataflow in Rust, part 3](https://github.com/frankmcsherry/blog/blob/master/posts/2015-09-21.md)

In part 3 we are going to build a small program to do breadth-first search in a random graph! That is basically the most important thing ever. As a side-effect, we will also see a more realistic program, get some numbers, think about some optimizations, and then broaden our minds with a neat new algorithm that fits timely dataflow's features really well.

---

#### [An introduction to Timely Dataflow in Rust, part 2](https://github.com/frankmcsherry/blog/blob/master/posts/2015-09-18.md)

In part 2 of the introduction to timely dataflow in Rust, we look at how to write custom operators, and how to use notifications, one of timely dataflow's defining characteristics. We'll get familiar with the `unary_stream` and `unary_notify` operators, and position ourselves for some graph computation in the next post.

---

#### [An introduction to Timely Dataflow in Rust, part 1](https://github.com/frankmcsherry/blog/blob/master/posts/2015-09-14.md)

It's been a long time since I've said anything about timely dataflow in Rust, and I don't think I've ever said anything about how to get started with it. I'm going to try and fix that now, by walking through some relatively simple examples of timely dataflow programming. We'll see how to set up a streaming timely dataflow computation, an iterative computation, and a streaming-iterative computation.

That sound amazing, right? There is going to be more, soon!

---

#### [Epic Graph Battle of History: Chaos vs Order](https://github.com/frankmcsherry/blog/blob/master/posts/2015-08-20.md)

A reader wrote in about the "Sorting out graph processing" post, with some questions about how well sorting works when compared against the newest as-yet-unpublished (but SOSP 2015 bound!) systems research on how best to process graphs. I didn't know the answer, but I set out to discover it!

The perf numbers for the system itself are not yet in (my contact is PDT), but I'll update with them as they flow in.

**Update**: Numbers for PageRank on Chaos are in. Other numbers will have to wait until October, says author.

---

#### [Sorting out graph processing](https://github.com/frankmcsherry/blog/blob/master/posts/2015-08-15.md)

We revisit the conventional wisdom that sorting is expensive, and random access is fast. In particular, if you think you might need to do a bunch of random accesses, maybe you should consider sorting the requests first. We look at some results in a paper from SOSP 2013 and see how speedy sorting algorithms likely change the trade-offs the paper proposes.

Also, differential dataflow goes a lot faster as a result of this stuff, so you should read about it.

---

#### [The impact of fast networks on graph analytics, part 2.](https://github.com/frankmcsherry/blog/blob/master/posts/2015-07-31.md)

Malte and I did a bit deeper into the sources of the performance discrepancies between GraphX and Timely dataflow. We measure many things, and work through some neat time series that look like

![Timely](https://github.com/frankmcsherry/blog/blob/master/assets/timeseries/pagerank/timely_uk_16x8_10g/caelum-401.png)

---

#### [The impact of fast networks on graph analytics, part 1.](https://github.com/frankmcsherry/blog/blob/master/posts/2015-07-08.md)

Malte Schwarzkopf and I look in to the question of to what degree does improving networking help in graph computation. We do some measurement, comparing a PageRank implementation in both GraphX and in Timely dataflow.

---

#### [Differential graph computation](https://github.com/frankmcsherry/blog/blob/master/posts/2015-05-12.md)

Prompted by reader questions, we take a light tour through some of the things that differential dataflow can do.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=WO23WBji_Z0
" target="_blank"><img src="http://img.youtube.com/vi/WO23WBji_Z0/0.jpg"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

---

#### [Abomonation: terrifying serialization](https://github.com/frankmcsherry/blog/blob/master/posts/2015-05-04.md)

---

#### [Data-parallelism in timely dataflow](https://github.com/frankmcsherry/blog/blob/master/posts/2015-04-19.md)

---

#### [Worst-case optimal joins, in dataflow](https://github.com/frankmcsherry/blog/blob/master/posts/2015-04-11.md)

---

#### [Differential dataflow](https://github.com/frankmcsherry/blog/blob/master/posts/2015-04-07.md)

---

#### [Bigger data; same laptop](https://github.com/frankmcsherry/blog/blob/master/posts/2015-02-04.md)

---

#### [Scalability! But at what COST?](https://github.com/frankmcsherry/blog/blob/master/posts/2015-01-15.md)

---

#### [Timely dataflow: core concepts](https://github.com/frankmcsherry/blog/blob/master/posts/2015-12-29.md)

---

#### [Timely dataflow: reboot](https://github.com/frankmcsherry/blog/blob/master/posts/2015-12-27.md)

---

#### [Columnarization in Rust, part 2](https://github.com/frankmcsherry/blog/blob/master/posts/2015-12-16.md)

---

#### [Columnarization in Rust](https://github.com/frankmcsherry/blog/blob/master/posts/2015-12-15.md)
