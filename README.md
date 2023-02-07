## Get Direct Down Link Of Yt songs/video From tubemp3.biz

- Author : [Vihanga-YT](https://github.com/vihangayt0)

***

## Example
```js
const {
getVideoWithTubeMp3
} = require('tubemp3-biz.js');

const res = await getVideoWithTubeMp3('https://youtu.be/5C8yvJUVB-0');
console.log(res);
```
***
## OutPut
```js
[
  {
    quality: '720p',
    size: '5.3 MB',
    url: 'https://ytmp4.buzz/download/5C8yvJUVB-0/mp4/22/1675782332/d6af65aad1e1f06419602c3eb9b0c00d25de25a33513e7ed59241ddd9eb4b791/1'
  },
  {
    quality: '360p',
    size: '4.53 MB',
    url: 'https://ytmp4.buzz/download/5C8yvJUVB-0/mp4/18/1675782332/d6af65aad1e1f06419602c3eb9b0c00d25de25a33513e7ed59241ddd9eb4b791/1'
  }
]
```
***

```js
const {
getAudioWithTubeMp3
} = require('tubemp3-biz.js');

const res = await getAudioWithTubeMp3('https://youtu.be/5C8yvJUVB-0');
console.log(res);
```
***
## OutPut
```js
[
  {
    quality: '320 kbps',
    size: '8.85 MB',
    url: 'https://ytmp4.buzz/download/5C8yvJUVB-0/mp3/320/1675782544/84d1aeecc77e001f6315364ba96e0dee29d80f5e24e91c92d3c4ab81376b5f8f/1'
  },
  {
    quality: '256 kbps',
    size: '7.08 MB',
    url: 'https://ytmp4.buzz/download/5C8yvJUVB-0/mp3/256/1675782544/84d1aeecc77e001f6315364ba96e0dee29d80f5e24e91c92d3c4ab81376b5f8f/1'
  },
  {
    quality: '192 kbps',
    size: '5.31 MB',
    url: 'https://ytmp4.buzz/download/5C8yvJUVB-0/mp3/192/1675782544/84d1aeecc77e001f6315364ba96e0dee29d80f5e24e91c92d3c4ab81376b5f8f/1'
  },
  {
    quality: '128 kbps',
    size: '3.54 MB',
    url: 'https://ytmp4.buzz/download/5C8yvJUVB-0/mp3/128/1675782544/84d1aeecc77e001f6315364ba96e0dee29d80f5e24e91c92d3c4ab81376b5f8f/1'
  },
  {
    quality: '64 kbps',
    size: '1.77 MB',
    url: 'https://ytmp4.buzz/download/5C8yvJUVB-0/mp3/64/1675782544/84d1aeecc77e001f6315364ba96e0dee29d80f5e24e91c92d3c4ab81376b5f8f/1'
  }
]
```
***
