# Howdy!

My name is Linh Pham (he/him/they/them) and I am the person behind the [Wait Wait Don't Tell Me! Stats Page](https://stats.wwdt.me). I am also an Software Release Engineer with a background in IT Systems Engineering and DevOps.

Python is my it thing when it comes to programming or playing around with the data that I've collected over the years from [Wait Wait... Don't Tell Me!](https://waitwait.npr.org). I still dabble around in C#, PHP and JavaScript when I have chance to do so. I definitely want to play around with Swift and Go when I have the free cycles.

If you like the Wait Wait Stats Page and collection of sites and would like to help support the project, please consider [sponsoring me on GitHub](https://github.com/sponsors/questionlp).

## Links

 * **Mastodon:** [qlp@linh.social](https://linh.social/@qlp)
 * **Bluesky:** [@linh.social](https://bsky.app/profile/linh.social)
 * **Flickr:** [questionlp](https://www.flickr.com/photos/questionlp)
 * **Website:** [linhpham.org](https://linhpham.org)
 * **Blog:** [linhpham.org/blog](https://linhpham.org/blog)
 * **GitHub Gists:** [gist.github.com/questionlp](https://gist.github.com/questionlp)

## Wait Wait Stats Page Projects

If you are interested in taking a gander at the code for the Stats Page and its supporting and related components, check out the repos listed below. The projects are published under the terms of [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0) (unless otherwise noted in the repo's `LICENSE` file).

### Sites

The current version of the Stats Page, Graphs and Reports web applications are developed in Python and built top of the [Flask](https://github.com/pallets/flask) micro web app framework. The Stats API is developed in Python and built on top of [FastAPI](http://fastapi.tiangolo.com).

 * [stats.wwdt.me](https://github.com/questionlp/stats.wwdt.me)
 * [api.wwdt.me_v2](https://github.com/questionlp/api.wwdt.me_v2)
 * [graphs.wwdt.me](https://github.com/questionlp/graphs.wwdt.me)
 * [reports.wwdt.me](https://github.com/questionlp/reports.wwdt.me)

### Library

A Python library was created to query, collect and return data from the Wait Wait Stats database. Package for the library are available on PyPi at: <https://pypi.org/project/wwdtm/>

 * [wwdtm](https://github.com/questionlp/wwdtm)

Documentation for version 2 of the Stats Library is available at [docs.wwdt.me](https://docs.wwdt.me).

### Database Schema

The data that I've collected is stored in a MariaDB/MySQL database and I've published the schema for it in its own repo.

 * [wwdtm_database](https://github.com/questionlp/wwdtm_database)

### Database Export

A Python program has been created to export the contents of each table in the Wait Wait Stats Database as individual JSON files.

 * [wwdtm_database_export](https://github.com/questionlp/wwdtm_database_export)

### Slugify Names

A Python program has been created to generate slug strings for guests, hosts, locations, panelists and scorekeepers, which are used throughout the libraries and applications listed above.

 * [wwdtm_slugify](http://github.com/questionlp/wwdtm_slugify)

### Previous Versions

The following projects have been superceded by newer versions that including some significant structural and/or framework updates

 * [api.wwdt.me](https://github.com/questionlp/api.wwdt.me)
 * [graphs.wwdt.me_v1](https://github.com/questionlp/graphs.wwdt.me_v1)
 * [libwwdtm](https://github.com/questionlp/libwwdtm)
 * [reports.wwdt.me_v1](https://github.com/questionlp/reports.wwdt.me_v1)
 * [stats.wwdt.me_archived](https://github.com/questionlp/stats.wwdt.me_archived)
 
Versions 2 and 3 of the Stats Page were developed in PHP, with version 3 using the now deprecated [Silex](https://github.com/silexphp/Silex) framework. I've published the code in case anyone is interested at looking at the progression of the Stats Page over the years.

 * [stats.wwdt.me_v2](https://github.com/questionlp/stats.wwdt.me_v2)
 * [stats.wwdt.me_v3](https://github.com/questionlp/stats.wwdt.me_v3)
