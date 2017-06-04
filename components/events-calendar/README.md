[![Build Status](https://travis-ci.org/Hispar/events-calendar.svg?branch=master)](https://travis-ci.org/Hispar/events-calendar)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/Hispar/events-calendar)

## &lt;events-calendar&gt;

Events calendar based on https://github.com/mpachnis/mp-calendar

## Demo

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="events-calendar.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<events-calendar day-labels='["Su","Mo","Tu","We","Th","Fr","Sa"]'
             disable-prev-days
             show-days-in-month=42>
</events-calendar>
<script>
        var calendar = document.querySelector('events-calendar');

        calendar.eventList = {
            '2017-05-01' : [
                {
                    summary: '7-11 | S',
                    slot: '7:00-11:00',
                    name: 'test',
                    category: 'Supervisor'
                },
                {
                    summary: '11-15 | S',
                    slot: '11:00-15:00',
                    name: '',
                    category: 'Supervisor'
                }
            ],
            '2017-05-02' : [
                {
                    summary: '7-11 | S',
                    slot: '7:00-11:00',
                    name: '',
                    category: 'Supervisor'
                }
            ],
            '2017-05-03' : [
                {
                    summary: '7-11 | S',
                    slot: '7:00-11:00',
                    name: '',
                    category: 'Supervisor'
                }
            ],
        };
    </script>
```

https://hispar.github.io/events-calendar/components/events-calendar/


### Install

```bash
# via bower
$ bower install events-calendar
```

### Usage


```html

<events-calendar day-labels='["Su","Mo","Tu","We","Th","Fr","Sa"]'
             disable-prev-days
             show-days-in-month=42>
</events-calendar>
<script>
        var calendar = document.querySelector('events-calendar');

        calendar.eventList = {
            '2017-05-01' : [
                {
                    summary: '7-11 | S',
                    slot: '7:00-11:00',
                    name: 'test',
                    category: 'Supervisor'
                },
                {
                    summary: '11-15 | S',
                    slot: '11:00-15:00',
                    name: '',
                    category: 'Supervisor'
                }
            ],
            '2017-05-02' : [
                {
                    summary: '7-11 | S',
                    slot: '7:00-11:00',
                    name: '',
                    category: 'Supervisor'
                }
            ],
            '2017-05-03' : [
                {
                    summary: '7-11 | S',
                    slot: '7:00-11:00',
                    name: '',
                    category: 'Supervisor'
                }
            ],
        };
    </script>

```
## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## Credits

The creator of the base code for this calendar is Minas Pachnis https://github.com/mpachnis

### License

MIT License
