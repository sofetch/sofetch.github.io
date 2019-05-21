---
Date: 2019-04-17
Time: 21:53 PM EDT
times:
  - "2019-01-07"
  - "2019-01-21"
  - "2019-02-04"
  - "2019-02-18"
  - "2019-03-04"
  - "2019-03-18"
  - "2019-04-01"
  - "2019-04-15"
  - "2019-04-29"
  - "2019-05-13"
  - "2019-05-27"
  - "2019-06-10"
  - "2019-06-24"
  - "2019-07-22"
  - "2019-08-05"
  - "2019-08-19"
  - "2019-09-02"
  - "2019-09-16"
  - "2019-09-30"
  - "2019-10-14"
  - "2019-10-28"
  - "2019-11-11"
  - "2019-11-25"
---

We've learned a few lessons of how best to start working with new customers over the past 15 years and 100+ projects. The basic idea is: we have specific dates in the year that we start any new project. This way we can schedule the work like normal people and actually get things done without burning out on any given project. The benefit for you, our customer, is consistent quality work. 

All of software development is done between the ears. If we overload our brains by trying to do too much work than what our neanderthal brains can handle, quality starts to plummet. Thats why we have the dates below that we will start any new project.

Our 2019 schedule:

{% for time in page.times %}
  {{ time | date: "%A, %B %d, %Y" }}
{% endfor %}

December OFF / No Projects starting (We love Christmas)
