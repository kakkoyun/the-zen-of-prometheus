
`The Zen of Prometheus` is beginner friendly set of core values and guidelines for instrumenting your applications and writing idiomatic alerts using Prometheus.

# Instrument all the things!

Instrument first, ask questions later. Spread the metrics very liberally! Whitebox monitoring!

# But think about what you are going to ask (TODO)

RED, USE and The Four Golder Signals.

## SLx (TODO)

`TODO`

SLx to guide your instrumentation.

# It's all about Labels (TODO)

`TODO`

# Absent labels say nothing!

Initialize your labels.

# Cardinality is key (TODO)

`TODO`

[Cardinality is key](https://www.robustperception.io/cardinality-is-key)

# Conventions, conventions, conventions (TODO)

[Naming](https://prometheus.io/docs/practices/naming/)

[On Naming Things](https://www.robustperception.io/on-the-naming-of-things)

[Monitoring Mixins](https://monitoring.mixins.dev/) are everyone's favorite!

# Symptom based alerts, not caused based (TODO)

Read famous [My Philosophy on Alerting](https://docs.google.com/document/d/199PqyG3UsyXlwieHaqbGiWVa8eMWi8zzAn0YfcApr8Q/edit).
Use causal metrics for debugging.

# If you can graph it, you can alert on it

`TODO`

# Avoid missing metric (TODO)

[`absent`](https://prometheus.io/docs/prometheus/latest/querying/functions/#absent) is you friend!

[Avoid missing metric](https://prometheus.io/docs/practices/instrumentation/#avoid-missing-metrics)

[Existential Issues with Metrics](https://www.robustperception.io/existential-issues-with-metrics)

[What's `up` Doc?](https://www.robustperception.io/whats-up-doc)

# Don't panic(alert?) just now!

(Use `FOR` in your alerts) (TODO)

`TODO`

# Labels are ~~Context is~~ king!

Preserve your labels for your alerts.

# First the rate, then aggregate

(Rate then sum, never sum then rate)

[Rate then sum, never sum then rate](https://www.robustperception.io/rate-then-sum-never-sum-then-rate)

---

Inspration [The Zen of Go](https://the-zen-of-go.netlify.app), [Go Proverbs](https://go-proverbs.github.io/) and [The Zen of Python](https://zen-of-python.info/).

Feel free to [contribute](https://github.com/kakkoyun/the-zen-of-prometheus/compare)!
