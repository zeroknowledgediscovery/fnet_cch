# Fractalnet Event Predictions for Chihuahua Mexico

+ Performance in th eout-of-sample period is logged in the
performance folder.

+ Preidiction snapshots for th eout-of-sample period (Jan 1 - Mar 2, 2023) is shown in the folder `movies/frames`
+ Prediction in **true future** (beyond Mar 2) is shown in the folder `movies_future/frame`

+ Also check *.webm movies in the `movies/` and `movies_future/` folders

# Directory Structure

```
├── LICENSE
├── LICENSE.md
├── models
│   └── packed.tgz
├── movies
│   ├── frames
│   │   ├── snapshot_2023-01-01.png
│   │   ├── snapshot_2023-01-02.png
│   │   ├── snapshot_2023-01-03.png
│   │   ├── snapshot_2023-01-04.png
│   │   ├── snapshot_2023-01-05.png
│   │   ├── snapshot_2023-01-06.png
│   │   ├── snapshot_2023-01-07.png
│   │   ├── snapshot_2023-01-08.png
│   │   ├── snapshot_2023-01-09.png
│   │   ├── snapshot_2023-01-10.png
│   │   ├── snapshot_2023-01-11.png
│   │   ├── snapshot_2023-01-12.png
│   │   ├── snapshot_2023-01-13.png
│   │   ├── snapshot_2023-01-14.png
│   │   ├── snapshot_2023-01-15.png
│   │   ├── snapshot_2023-01-16.png
│   │   ├── snapshot_2023-01-17.png
│   │   ├── snapshot_2023-01-18.png
│   │   ├── snapshot_2023-01-19.png
│   │   ├── snapshot_2023-01-20.png
│   │   ├── snapshot_2023-01-21.png
│   │   ├── snapshot_2023-01-22.png
│   │   ├── snapshot_2023-01-23.png
│   │   ├── snapshot_2023-01-24.png
│   │   ├── snapshot_2023-01-25.png
│   │   ├── snapshot_2023-01-26.png
│   │   ├── snapshot_2023-01-27.png
│   │   ├── snapshot_2023-01-28.png
│   │   ├── snapshot_2023-01-29.png
│   │   ├── snapshot_2023-01-30.png
│   │   ├── snapshot_2023-01-31.png
│   │   ├── snapshot_2023-02-01.png
│   │   ├── snapshot_2023-02-02.png
│   │   ├── snapshot_2023-02-03.png
│   │   ├── snapshot_2023-02-04.png
│   │   ├── snapshot_2023-02-05.png
│   │   ├── snapshot_2023-02-06.png
│   │   ├── snapshot_2023-02-07.png
│   │   ├── snapshot_2023-02-08.png
│   │   ├── snapshot_2023-02-09.png
│   │   ├── snapshot_2023-02-10.png
│   │   ├── snapshot_2023-02-11.png
│   │   ├── snapshot_2023-02-12.png
│   │   ├── snapshot_2023-02-13.png
│   │   ├── snapshot_2023-02-14.png
│   │   ├── snapshot_2023-02-15.png
│   │   ├── snapshot_2023-02-16.png
│   │   ├── snapshot_2023-02-17.png
│   │   ├── snapshot_2023-02-18.png
│   │   ├── snapshot_2023-02-19.png
│   │   ├── snapshot_2023-02-20.png
│   │   ├── snapshot_2023-02-21.png
│   │   ├── snapshot_2023-02-22.png
│   │   ├── snapshot_2023-02-23.png
│   │   ├── snapshot_2023-02-24.png
│   │   ├── snapshot_2023-02-25.png
│   │   ├── snapshot_2023-02-26.png
│   │   ├── snapshot_2023-02-27.png
│   │   ├── snapshot_2023-02-28.png
│   │   ├── snapshot_2023-03-01.png
│   │   └── snapshot_2023-03-02.png
│   └── movie.webm
├── movies_future
│   ├── frames
│   │   ├── snapshot_2023-01-01.png
│   │   ├── snapshot_2023-01-02.png
│   │   ├── snapshot_2023-01-03.png
│   │   ├── snapshot_2023-01-04.png
│   │   ├── snapshot_2023-01-05.png
│   │   ├── snapshot_2023-01-06.png
│   │   ├── snapshot_2023-01-07.png
│   │   ├── snapshot_2023-01-08.png
│   │   ├── snapshot_2023-01-09.png
│   │   ├── snapshot_2023-01-10.png
│   │   ├── snapshot_2023-01-11.png
│   │   ├── snapshot_2023-01-12.png
│   │   ├── snapshot_2023-01-13.png
│   │   ├── snapshot_2023-01-14.png
│   │   ├── snapshot_2023-01-15.png
│   │   ├── snapshot_2023-01-16.png
│   │   ├── snapshot_2023-01-17.png
│   │   ├── snapshot_2023-01-18.png
│   │   ├── snapshot_2023-01-19.png
│   │   ├── snapshot_2023-01-20.png
│   │   ├── snapshot_2023-01-21.png
│   │   ├── snapshot_2023-01-22.png
│   │   ├── snapshot_2023-01-23.png
│   │   ├── snapshot_2023-01-24.png
│   │   ├── snapshot_2023-01-25.png
│   │   ├── snapshot_2023-01-26.png
│   │   ├── snapshot_2023-01-27.png
│   │   ├── snapshot_2023-01-28.png
│   │   ├── snapshot_2023-01-29.png
│   │   ├── snapshot_2023-01-30.png
│   │   ├── snapshot_2023-01-31.png
│   │   ├── snapshot_2023-02-01.png
│   │   ├── snapshot_2023-02-02.png
│   │   ├── snapshot_2023-02-03.png
│   │   ├── snapshot_2023-02-04.png
│   │   ├── snapshot_2023-02-05.png
│   │   ├── snapshot_2023-02-06.png
│   │   ├── snapshot_2023-02-07.png
│   │   ├── snapshot_2023-02-08.png
│   │   ├── snapshot_2023-02-09.png
│   │   ├── snapshot_2023-02-10.png
│   │   ├── snapshot_2023-02-11.png
│   │   ├── snapshot_2023-02-12.png
│   │   ├── snapshot_2023-02-13.png
│   │   ├── snapshot_2023-02-14.png
│   │   ├── snapshot_2023-02-15.png
│   │   ├── snapshot_2023-02-16.png
│   │   ├── snapshot_2023-02-17.png
│   │   ├── snapshot_2023-02-18.png
│   │   ├── snapshot_2023-02-19.png
│   │   ├── snapshot_2023-02-20.png
│   │   ├── snapshot_2023-02-21.png
│   │   ├── snapshot_2023-02-22.png
│   │   ├── snapshot_2023-02-23.png
│   │   ├── snapshot_2023-02-24.png
│   │   ├── snapshot_2023-02-25.png
│   │   ├── snapshot_2023-02-26.png
│   │   ├── snapshot_2023-02-27.png
│   │   ├── snapshot_2023-02-28.png
│   │   ├── snapshot_2023-03-01.png
│   │   ├── snapshot_2023-03-02.png
│   │   ├── snapshot_2023-03-03.png
│   │   ├── snapshot_2023-03-04.png
│   │   ├── snapshot_2023-03-05.png
│   │   ├── snapshot_2023-03-06.png
│   │   ├── snapshot_2023-03-07.png
│   │   ├── snapshot_2023-03-08.png
│   │   ├── snapshot_2023-03-09.png
│   │   ├── snapshot_2023-03-10.png
│   │   ├── snapshot_2023-03-11.png
│   │   ├── snapshot_2023-03-12.png
│   │   ├── snapshot_2023-03-13.png
│   │   ├── snapshot_2023-03-14.png
│   │   ├── snapshot_2023-03-15.png
│   │   ├── snapshot_2023-03-16.png
│   │   ├── snapshot_2023-03-17.png
│   │   ├── snapshot_2023-03-18.png
│   │   ├── snapshot_2023-03-19.png
│   │   ├── snapshot_2023-03-20.png
│   │   ├── snapshot_2023-03-21.png
│   │   ├── snapshot_2023-03-22.png
│   │   └── snapshot_2023-03-23.png
│   └── movie.webm
├── performance
│   ├── outputP#z0.07#d0.00175#r0.008#m0.007.txt
│   ├── README.md
│   └── res_dayP#z0.07#d0.00175#r0.008#m0.007.csv
└── README.md
```

## License

LICENSE.md

