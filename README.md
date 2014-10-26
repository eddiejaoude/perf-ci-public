# PerfCI Public

PerfCI - Build Measure Learn (BML) - docs &amp; issues are public

*Note: Code is private. This Repository is for Documentation & Issue Tracking.*

---

Use ySlow in your CI build (for example with Phantomjs or Selenium) & your results will get beacon to our service, where we will monitor your `Page Load Time` & `Page Size`.

### Examples

| Badge | Description |
| ----- | ----------- |
| ![ySlow](docs/images/yslow-green.png "ySlow") | ySlow rating |
| ![download time](docs/images/downloadtime-orange.png "Download Time") | Download Time |
| ![page size](docs/images/pagesize-red.png "Page Size") | Page size |

---

### Default SLAs

| Type | Green | Orange | Red |
| ---- | ----- | ------ | --- |
| ySlow | 80-100% | 40-80% | 0-40% |
| Download Time | <1s | 1-3s | 3s+ |
| Page Size | <100kb | 100-200kb | 200kb+ |

*Subject to change*

---

### Current Features

* Free for Public Projects
* Profiling of Project's `Page Size` & `Download Time` for Project Life Cycle


### Future Features

* Customisable SLAs
* Alerting
* Private Projects

---

### Resources

* PhantomJS with ySlow http://yslow.org/phantomjs/
* Selenium with Firefox & ySlow plugin

---

### Ideas / Features

For any ideas & feature requests please log it in the issue section https://github.com/eddiejaoude/perf-ci-public/issues 
