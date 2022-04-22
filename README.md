# indonesia-tourism
This repo contains a list of tourism in Indonesia in JSON format. The JSON structure that we provide is
```json
[
  {
    "name": "", //string
    "location": "", //string
    "description": "", //string
    "thumbnail": "", //string
    "image": "" //string
  }
]
```
---
## How we collect the data
- Wikipedia
- Google
- Facebook
- More
---
## How to use

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
If you like this project and are willing to help add more data, please read the [contributions](CONTRIBUTING.md) page