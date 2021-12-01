## What’s changed

## 🐛 Bug fixes

- Fix log level, settings and example config @mdegat01 (#10)
- Add USB to add-on config @mdegat01 (#12)
- Fix message types config option @mdegat01 (#14)
- Fix message types config option @mdegat01 (#15)
- Incorrect syntax for f strings @mdegat01 (#16)
- Initialize `interval_cur` so check works @mdegat01 (#19)
- Don't run rtl_tcp as a user @mdegat01 (#22)
- Use `/ssl` for ca cert and not for client certs @mdegat01 (#23)
- Missing port config option @mdegat01 (#24)
- Using incorrect EV name for auth @mdegat01 (#25)
- Fix handling list configs @mdegat01 (#30)
- Grant read permission on /data @mdegat01 (#34)

## 🚀 Enhancements

- Initial state of the addon @mdegat01 (#1)
- Inherit org's release drafter template @mdegat01 (#7)
- Inherit org's pull request template @mdegat01 (#8)
- Map udev and add rtl-sdr config/rules @mdegat01 (#11)
- Add support for scm type messages @mdegat01 (#13)
- Change name to `amr2mqtt` @mdegat01 (#17)
- Use `rtlamr`'s built-in ID filter @mdegat01 (#20)
- Start `rtl_tcp` as a separate managed service @mdegat01 (#21)
- Keep connection to MQTT broker while running @mdegat01 (#26)
- Change `wh_multiplier` to `reading_multiplier` @mdegat01 (#27)
- Quiet `rtl_tcp` based on `log_level` @mdegat01 (#28)
- Add scm+ and r900 support @mdegat01 (#31)
- Remove discovery mode @mdegat01 (#32)
- Change config to be based around meters @mdegat01 (#33)
- Fix docs and add HA discovery options @mdegat01 (#36)
- Add support for HA MQTT discovery @mdegat01 (#37)
- Set availability on birth and will @mdegat01 (#38)

## 🧰 Maintenance

- Use yq instead of jq in deploy @mdegat01 (#2)
- Switch to centralized GitHub Actions workflows @mdegat01 (#3)
- Pass ghcr token to deploy workflow @mdegat01 (#4)
- Recover release drafter template @mdegat01 (#5)

## 📚 Documentation

- Add a PR template @mdegat01 (#6)
- Use new name in generated readme @mdegat01 (#18)
- Fill in documentation and add discovery mode @mdegat01 (#29)
- Add troubleshooting info to docs @mdegat01 (#39)

## ⬆️ Dependency updates

- Bump alpine from 3.14.3 to 3.15.0 in /amr2mqtt @dependabot (#35)
