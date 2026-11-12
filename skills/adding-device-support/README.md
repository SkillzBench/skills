# adding-device-support

[![SkillzBench](https://skillzbench.com/api/badge/adding-device-support)](https://skillzbench.com/skills/adding-device-support)

Add or extend support for a Samsung OCF appliance in localthings from a /device/0 diagnostics dump. Use when a device-support issue lands, a device raises the "incomplete capability coverage" repair, a diagnostics JSON needs triaging, or you're mapping OCF resources to HA entities. Covers reading dumps, routing a device to a registry from its `/oic/d` device type first and an unrecognized board family second (modelNum board tokens, resource signatures), OCF-standard vs vendor hrefs, the diagnostic/config/normal entity taxonomy, preferring dynamic (device-reported) select options over hardcoded lists, ensuring every href is bound or ignored, and locking it in with a fixture + golden + test. Also covers multi-subdevice ("composite") appliances that expose several logical indoor subdevices over one IP — triaging a missing second subdevice, and why registry hrefs stay canonical rather than indexed.

Mirrored from [skillzbench.com/skills/adding-device-support](https://skillzbench.com/skills/adding-device-support) — Trust Score, benchmarks and install options live there.
