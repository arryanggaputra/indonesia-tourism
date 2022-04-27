# indonesia-tourism

This repository contains tourism data in Indonesia in JSON format. The data contained in this repository can be freely used, and shared. You can use all the data in this repository on the platform you want, such as MySQL, NoSQL, Excel, and so on. Below is an example of the data we provide

```json
[
  {
    "name": "Danau Nyadeng",
    "location": "Kampung Merabu,Kelay,Berau",
    "description": "Dari kampung Merabu ke Danau Nyadeng ditempuh dalam waktu sekitar 30 menit, sepanjang pejalanan disuguhi pemandangan alam berupa kawasan hutan yang masih lebat di sisi kiri dan kanan sungai.\r\n\r\nSelain dapat menikmati indahnya hutan yang asri, sesekali juga bisa menyaksikan kumpulan monyet bermain di antara rimbunan pohon yang berdiri gagah di sepanjang tepian sungai....",
    "thumbnail": "http://images1.prokal.co/webkp/file/berita/2015/05/05/warga-sadar-wisata-tak-boleh-tinggalkan-sampah.jpg",
    "image": "http://images1.prokal.co/webkp/file/berita/2015/05/05/warga-sadar-wisata-tak-boleh-tinggalkan-sampah.jpg"
  }
]
```
---
## How we collect the data
We collect data from various sources, such as:

- Wikipedia
- Google
- Facebook
- More

If you want to contribute to our repository by adding or improving existing data, you can read how to contribute on [this page](CONTRIBUTING.md)


---
## How to use in any programming language

JSON is a text format that is completely language independent but uses conventions that are familiar to programmers.

### Consuming data in JavaScript

to use the `data.json` in JavaScript by simply downloading `data.json` and import to your project, example:

```javascript
import TourismData from './data.json'

TourismData.map(item=> {
    return item.title
})

```

---

## Community
### Author
All data inside this repository is initiate by [arryanggaputra](https://github.com/arryanggaputra)

### Contributing
If you like this project and are willing to help add more data or fix exising data, please read the [contributions](CONTRIBUTING.md) page