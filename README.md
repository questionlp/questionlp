# Howdy!

My name is Linh Pham (he/him) and I am the person behind the
[Wait Wait... Don't Tell Me! Stats Page](https://stats.wwdt.me). I am also an
IT/DevOps Engineer that works on automating and orchestrating applications.

Python is my it thing when it comes to programming or playing around with the
data that I've collected over the years from
[Wait Wait... Don't Tell Me!](https://waitwait.npr.org). I still dabble around
in C#, PHP and JavaScript when I have chance to do so. I definitely want to
play around with Swift and Go when I have the free cycles.

## Wait Wait Stats Page Projects

If you are interested in taking a gander at the code for the Stats Page and its
supporting and related components, check out the repos listed below. The projects
are published under the terms of
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0) (unless
otherwise noted in the repo's `LICENSE` file).

### Sites

The current version of the Stats Page, Stats API, Graphs and Reports sites
are developed in Python and on top of the
[Flask](https://github.com/pallets/flask) micro web app framework.

 * [stats.wwdt.me](https://github.com/questionlp/stats.wwdt.me)
 * [api.wwdt.me](https://github.com/questionlp/api.wwdt.me)
 * [api.wwdt.me_fastapi](https://github.com/questionlp/api.wwdt.me_fastapi) *(Currently in development)*
 * [graphs.wwdt.me](https://github.com/questionlp/graphs.wwdt.me)
 * [reports.wwdt.me](https://github.com/questionlp/reports.wwdt.me)

### Library

The Stats Page, Stats API and Graphs sites make use of a Python library that
is used to pull data from the Stats database and does some of the stats
calculations for guests, hosts, panelists and scorekeepers on the show.

 * [libwwdtm](https://github.com/questionlp/libwwdtm)

There is an effort underway to completely refactor the library to make use of
features added after the release of Python 3.6; as well as, to make it easier
to use the various modules within the library. The early stages of the new
library is available at:

 * [wwdtm](https://github.com/questionlp/wwdtm)

### Database Schema

The data that I've collected is stored in a MariaDB/MySQL database and I've
published the schema for it in its own repo.

 * [wwdtm_database](https://github.com/questionlp/wwdtm_database)

### Previous Versions

Versions 2 and 3 of the Stats Page were developed in PHP, with version 3 using
the now deprecated [Silex](https://github.com/silexphp/Silex) framework. I've
published the code in case anyone is interested at looking at the progression
of the Stats Page over the years.

 * [stats.wwdt.me_v2](https://github.com/questionlp/stats.wwdt.me_v2)
 * [stats.wwdt.me_v3](https://github.com/questionlp/stats.wwdt.me_v3)

## Connect

 * Twitter: [@questionlp](https://twitter.com/questionlp)
 * Flickr: [questionlp](https://www.flickr.com/photos/questionlp)
 * Webpage: https://linhpham.org
