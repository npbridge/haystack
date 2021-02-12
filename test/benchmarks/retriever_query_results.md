|    | retriever   | doc_store     |   n_docs |   n_queries |   retrieve_time |   queries_per_second |   seconds_per_query |   recall |      map |   top_k | date_time                  | error   |
|---:|:------------|:--------------|---------:|------------:|----------------:|---------------------:|--------------------:|---------:|---------:|--------:|:---------------------------|:--------|
|  1 | dpr         | elasticsearch |     1000 |        1064 |        34.6755  |             30.6845  |          0.0325897  | 0.991541 | 0.929511 |      10 | 2021-02-01 11:27:43.048502 |         |
|  5 | dpr         | elasticsearch |    10000 |        5637 |       288.061   |             19.5688  |          0.0511019  | 0.974987 | 0.89871  |      10 | 2021-02-01 11:37:21.149887 |         |
|  9 | dpr         | elasticsearch |   100000 |        5637 |      1225.63    |              4.59928 |          0.217425   | 0.957956 | 0.865456 |      10 | 2021-02-01 12:15:52.757320 |         |
| 13 | dpr         | elasticsearch |   500000 |        5637 |      5339.01    |              1.05581 |          0.947136   | 0.930814 | 0.808614 |      10 | 2021-02-01 14:52:23.056230 |         |
|  0 | elastic     | elasticsearch |     1000 |        1064 |         4.04654 |            262.941   |          0.00380314 | 0.890977 | 0.742044 |      10 | 2021-02-01 11:26:04.346134 |         |
|  4 | elastic     | elasticsearch |    10000 |        5637 |        30.7014  |            183.607   |          0.00544641 | 0.81107  | 0.662063 |      10 | 2021-02-01 11:31:20.470092 |         |
|  8 | elastic     | elasticsearch |   100000 |        5637 |        34.7055  |            162.424   |          0.00615673 | 0.719354 | 0.562596 |      10 | 2021-02-01 11:50:36.048887 |         |
| 12 | elastic     | elasticsearch |   500000 |        5637 |        68.3838  |             82.4318  |          0.0121312  | 0.627461 | 0.455945 |      10 | 2021-02-01 13:02:16.905187 |         |
|  2 | dpr         | faiss_flat    |     1000 |        1064 |        30.0533  |             35.4038  |          0.0282456  | 0.991541 | 0.929511 |      10 | 2021-02-01 11:28:55.544474 |         |
|  6 | dpr         | faiss_flat    |    10000 |        5637 |       218.594   |             25.7875  |          0.0387785  | 0.974987 | 0.89871  |      10 | 2021-02-01 11:42:07.545869 |         |
| 10 | dpr         | faiss_flat    |   100000 |        5637 |       865.744   |              6.51116 |          0.153582   | 0.957956 | 0.865461 |      10 | 2021-02-01 12:34:29.493598 |         |
| 14 | dpr         | faiss_flat    |   500000 |        5637 |      3717.95    |              1.51616 |          0.659561   | 0.930814 | 0.808614 |      10 | 2021-02-01 16:12:52.804436 |         |
|  3 | dpr         | faiss_hnsw    |     1000 |        1064 |        27.1677  |             39.1641  |          0.0255336  | 0.991541 | 0.929511 |      10 | 2021-02-01 11:30:02.684535 |         |
|  7 | dpr         | faiss_hnsw    |    10000 |        5637 |       167.552   |             33.6432  |          0.0297237  | 0.972503 | 0.896994 |      10 | 2021-02-01 11:46:07.130588 |         |
| 11 | dpr         | faiss_hnsw    |   100000 |        5637 |       167.482   |             33.6573  |          0.0297112  | 0.940216 | 0.850798 |      10 | 2021-02-01 12:43:21.697968 |         |
| 15 | dpr         | faiss_hnsw    |   500000 |        5637 |       164.456   |             34.2767  |          0.0291743  | 0.882562 | 0.769148 |      10 | 2021-02-01 16:47:01.710072 |         |