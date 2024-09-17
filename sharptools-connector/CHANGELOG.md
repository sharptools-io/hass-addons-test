# Changelog

## 1.1.0
- Make `light` and `cover` service data excluded (use static definitions)
- Improve logging if payload response size limit is exceeded (incl. calculated payload size)

## 1.0.9
- Include 'static' Album Art and Fan Speed metadata with events
- Fix: Support 4-speed fan devices ([video](./media/hass-4-speed.mov))

## 1.0.7
- Hotfix for an API change in Home Assistant 2023.4.x

## 1.0.4-1.0.6

- Update climate entity to ignore `null` values for `target_temp_high` and `target_temp_low` when setting temperature
- Fix S6 Overlay Images: https://developers.home-assistant.io/blog/2022/05/12/s6-overlay-base-images/

## 1.0.3

- Climate entity's target temperature attribute/argument conversion enhancements

## 1.0.2

- Add support for Scene entities

## 1.0.1

- Production release
