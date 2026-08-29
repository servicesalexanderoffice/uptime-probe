# uptime-probe

Scheduled GitHub Actions job that probes a private health endpoint and sends
an SMS alert (via a CRM API) when it stops answering. All endpoints and
credentials live in repo secrets. Public repo = free unlimited scheduled runs.
