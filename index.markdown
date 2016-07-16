---
layout: default
title: DopCert
group: "navigation"
id: home
---

Every database system contains a query optimizer that performs query rewrites.
Unfortunately, developing query optimizers remains a highly challenging task.
Part of the challenges comes from the intricacies and rich features of query
languages, which makes reasoning about rewrite rules difficult. In this paper,
we propose a machine-checkable denotational semantics for SQL, the de facto
language for relational database, for rigorously validating rewrite rules.
Unlike previously proposed semantics that are either non-mechanized or only
cover a small amount of SQL language features, our semantics covers all major
features of SQL, including bags, correlated subqueries, aggregation, and
indexes. Our mechanized semantics, called HoTTSQL, is based on K-Relations and
homotopy type theory, where we denote relations as mathematical functions from
tuples to univalent types. We have implemented HoTTSQL in Coq, which takes only
fewer than 300 lines of code and have proved a wide range of SQL rewrite rules,
including those from database research literature (e.g., magic set rewrites) and
real-world query optimizers (e.g., subquery elimination). Several of these
rewrite rules have never been previously proven correct. In addition, while
query equivalence is generally undecidable, we have implemented an automated
decision procedure using HoTTSQL for conjunctive queries: a well-studied
decidable fragment of SQL that encompasses many real-world queries.

### People

If you have any question, want to be kept up-to date, or just want to say hi, email us at 
<DopCert@cs.washington.edu>.
<!-- chushumo at cs dot uw dot edu or weitzkon at cs dot uw dot edu. -->

<a class="person" href="http://shumochu.com/">
  <span class="name">Shumo Chu</span><br/>
  <img class="profile" src="http://stechu.github.io/images/my_portrait.jpg"/>
</a>

<a class="person" href="http://konne.me">
  <span class="name">Konstantin Weitz</span><br/>
  <img class="profile" src="http://www.konne.me/assets/profile.png"/>
</a>

<a class="person" href="https://homes.cs.washington.edu/~akcheung/">
  <span class="name">Alvin Cheung</span><br/>
  <img class="profile" src="https://homes.cs.washington.edu/~akcheung/self.jpg"/>
</a>

<a class="person" href="https://homes.cs.washington.edu/~suciu/">
  <span class="name">Dan Suciu</span><br/>
  <img class="profile" src="https://homes.cs.washington.edu/~suciu/files/me-7-2006-mexico.jpg"/>
</a>

