<h1 align="center">
Example Inference Extension v1.0.0
</h1>

## Table of Contents

- [About](#about)
- [For More](#for-more)

## About

This extension is a part of the [Example Template](https://github.com/harescyber/hares_engine_template_example/tree/main) as a **inference** extension.

It is a tiny extension that uses [VirusTotal API](https://developers.virustotal.com/reference/overview) to request a complete analysis and predictions for **src_ip** addresses extracted by [Example Feature Extension](https://github.com/harescyber/hares_engine_example_feature_extension.git).
After each response, the extension publish an object includes an `id`, `timestamp`, the `data`, `result` and the requested `url` into another redis channel to provide this object for other extensions that may use it.

## For More

- [Hares Engine Extensions API](https://github.com/harescyber/hares_engine/tree/as-package#extensions-api)
- [Hares Engine Repo](https://github.com/harescyber/hares_engine/tree/as-package#readme)
- [Hares Engine Templates](https://github.com/harescyber/hares_engine_template_example/tree/main)
- [Example Feature Extension](https://github.com/harescyber/hares_engine_example_feature_extension.git)
- [Example Reporting Extension](https://github.com/harescyber/hares_engine_example_reporting_extension.git)
