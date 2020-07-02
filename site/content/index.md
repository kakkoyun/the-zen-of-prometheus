
`The Zen of Prometheus` is beginner friendly set of core values and guidelines for instrumenting your applications and writing idiomatic alerts using Prometheus.

> This is a community driven afford.
TODO: Explain more.

# Instrument first, ask questions later

During development you will never know what questions you need to ask later.

# Measure what users care most about

RED, USE and The Four Golden Signals are known frameworks to get you started.

TODO: Let your SLOs to guide your instrumentation.
TODO: Add links for them.
Your users don't care about your CPU cycles, they care about latency and availability.

# Slice and dice using Labels

Labels are the new hierarchy. Using labels one can group and aggregate measurements afterwards.

# Absent timeseries do not count

TODO: Add proper explanation with examples.
Initialize your metrics with a zero value.

# Avoid cardinality explosion

TODO: Add proper explanation with examples.
[Cardinality is key](https://www.robustperception.io/cardinality-is-key) so watch out what you put on those labels.
... And don't try this at home.

# First the rate, then aggregate

[Rate then sum, never sum then rate](https://www.robustperception.io/rate-then-sum-never-sum-then-rate)

# Consistency over personal preferences

TODO: (Convetion over preferences)
[Naming](https://prometheus.io/docs/practices/naming/) && [On Naming Things](https://www.robustperception.io/on-the-naming-of-things)
Gofmt's style is no one's favorite, yet gofmt is everyone's favorite.

# Don't over alert, alert-fatigue is real

Remember [Measure what users care most about](#measure-what-users-care-most-about)

TODO: Explain more.

# Symptom-based alerts for paging, caused-based for debugging

TODO: Explain more.
For more context [My Philosophy on Alerting](https://docs.google.com/document/d/199PqyG3UsyXlwieHaqbGiWVa8eMWi8zzAn0YfcApr8Q/edit).

# If you can graph it, you can alert on it

You don't look at dashboards 24/7.

# You cannot query what is absent

TODO: Consider removing it.
Remember [Absent timeseries do not count](#absent-timeseries-do-not-count)

TODO: Use only one document. Read about it here, here and here.
[`absent`](https://prometheus.io/docs/prometheus/latest/querying/functions/#absent) is you friend!
[Avoid missing metric](https://prometheus.io/docs/practices/instrumentation/#avoid-missing-metrics)
[What's `up` Doc?](https://www.robustperception.io/whats-up-doc)
[Existential Issues with Metrics](https://www.robustperception.io/existential-issues-with-metrics)

# Don't alert just now

TODO: Flaky/flappy ??
TODO: Use `FOR` in your alerts
TODO: Explain more.

# Labels are ~~Context is~~ king!

Preserve your labels for your alerts.
TODO: Content or context?
TODO: Half-way there!

---

Inspration [The Zen of Go](https://the-zen-of-go.netlify.app), [Go Proverbs](https://go-proverbs.github.io/) and [The Zen of Python](https://zen-of-python.info/).

TODO: Björn's and Julius' talk.

Feel free to [contribute](https://github.com/kakkoyun/the-zen-of-prometheus/compare)!
