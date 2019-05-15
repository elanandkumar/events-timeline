# @elanandkumar/events-timeline

![npm (scoped)](https://img.shields.io/npm/v/@elanandkumar/events-timeline.svg?color=blue&label=npm)
![npm bundle size (scoped)](https://img.shields.io/bundlephobia/min/@elanandkumar/events-timeline.svg?label=minified%20size)
![GitHub](https://img.shields.io/github/license/elanandkumar/events-timeline.svg)

An npm package for events timeline. Useful for the cases where you have scheduled an event and want to show details about speakers and the time with details.

## Install
```bash
$ npm install @elanandkumar/events-timeline
```

## Usages

```jsx
import EventsTimeline from '@elanandkumar/events-timeline';

const EventsTimelineWrapper = () => (
    <EventsTimeline/>
);
```

## Publish
First, update the package version using `npm version`
```bash
$ npm version major|minor|patch
```

Then,

```bash
$ npm publish
```

[LICENSE](./LICENSE)
