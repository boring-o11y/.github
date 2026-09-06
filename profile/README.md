# Boring Observability

We provide tools for Laravel for effective monitoring of your application.

Follow us:
- X [BoringO11y](https://x.com/BoringO11y)
- BlueSky [boring-o11y.bsky.social](http://boring-o11y.bsky.social/)
- Mastodon [@BoringObservability](https://phpc.social/@BoringObservability)

Check out our blog: https://boring-observability.dev/blog

## Free packages
- [horizon-delayed-jobs](https://github.com/boring-o11y/horizon-delayed-jobs) - Delayed job controls for Laravel Horizon.
- [httptheus](https://github.com/boring-o11y/httptheus) - Prometheus exporter and Grafana dashboard for outbound Http requests.
- [skystan](https://github.com/boring-o11y/skystan) - A PHPStan extension to enforce correct usage of Laravel background jobs.
- [wirestan](https://github.com/boring-o11y/wirestan) - A collection of PHPStan rules for correct LiveWire usage.

## Paid packages

### Laravel Skyline

Production queue control for Laravel Horizon.

A commercial, drop-in replacement for Laravel Horizon that turns the dashboard
into a control room: pause a queue, jump a job to the front, drain a backlog,
delete stuck jobs, and read metrics that finally tell the truth — all from the
UI, no SSH-ing in or firing Redis commands by hand.

Same config, same `Laravel\Horizon` namespace, same `/horizon` route, **zero
code changes**. Built on Horizon 5.x for Redis queues, and it runs entirely on
your own servers — no agent, no data egress.

Built and run in production by the team at Boring Observability.

[boring-observability.dev/skyline](https://boring-observability.dev)

---

<sub>Not affiliated with or endorsed by Laravel LLC. Laravel and Laravel Horizon
are trademarks of Taylor Otwell.</sub>
