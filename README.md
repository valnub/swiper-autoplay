# Swiper React Autoplay Demo

Just a quick demo how to use autoplay feature in Swiper React.

## How to run

```
$ npm install
$ npm run build && npm start
```

## In a nutshell

Assuming you already have your swiper up and running, add this to turn on autoplay:

### Add imports

```javascript
import { Autoplay } from 'swiper';
import 'swiper/css/autoplay';
```

### Create jsx

```jsx
<Swiper
  modules={[Autoplay]}
  autoplay={{ delay: 1000 }}
  // Alternative with 3sec default timeout:
  // autoplay={true}
>
  {/* Add slides here */}
</Swiper>
```
