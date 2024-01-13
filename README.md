# r10-firmware

Custom IOT firmware for hardware deployed to [ruutu10](https://ruutu10.ee) improv theatre.
Come see our shows, and observe the hardware at work in the event space.

## Projects

- `clock-remote`: On-desk remote control module for the stage clock. Mirrors time remaining and allows for control
- `stage-clock`: Huge 7-segment display, HASS controlled
- `portable-clock`: Huge 7-segment display, similar features to `stage-clock`, but also local control

## Development

```
$ cd esphome
$ python -m venv venv
$ ./venv/bin/activate
$ pip install -r requirements.txt
$ esphome run portable-clock.yml
```

## License

MIT