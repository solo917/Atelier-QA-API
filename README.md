# Loungeo Backend Upgrade - QA Component

![Screenshot](https://imgur.com/9SfncH4.gif)

## :writing_hand: Details

After completing the front end portion of Loungeo, I was tasked with helping to rebuild and optimize the backend architecture. I was tasked with completing a total rework of the QA Backend Component. <strong>This project utilized Node/Express, k6, Loader.io, PM2, and was deployed on AWS:EC2</strong>

## :muscle: Optimizations

* Seeded a MySQL database with more than 1 Million data points
* Optimized local query times to less than 1ms
* Improved throughput from 500 rps with a 200ms latency and 2 percent error to 1350 rps with 30ms latency and 0 percent error using horizontal scaling.

## :heavy_check_mark: Installation

Install dependencies

```
npm Install
```

Start backend service

Development:

```
npm start
```

Production:

```
PM2 start index.js
```

## :man: Developed By

[Khai Tran](https://github.com/solo917)
