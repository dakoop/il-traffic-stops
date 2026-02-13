# Illinois Traffic Stop Data

Data about Illinois traffic stops from 2004-2023, compiled, processed, and analyzed by [Matt Kiefer](https://www.wbez.org/author/matt-kiefer) and [Andjela Padejski](https://www.wbez.org/author/andjela-padejski) at [WBEZ Chicago](https://www.wbez.org). The original dataset, information, and related stories are available from this [page](https://interactive.wbez.org/traffic-stops/illinois-statewide/) from [WBEZ](https://www.wbez.org).

This version of the dataset drops a few of the fields in the original 12+GB sqlite3 and converts WBEZ's unified fields to booleans. The data is available in both gzip-compressed JSON and Parquet formats, and the stops data is partitioned by the year. This version of the data was created for educational purposes.

Documentation about the fields can be found in [WBEZ's technical documentation](https://docs.google.com/document/d/1Yk1J9SAPfZXfYk2Kb-z6K4p4eU6Rhnoc0RciRscymgY/edit?tab=t.0#heading=h.3f2v1umji09d) and analysis code is available from [WBEZ's reposistory](https://github.com/wbez/traffic_stops).
