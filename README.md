# Clustering
2) Hiearchial Clustering


      Parameter     |    No Data Processing    | Using Normalization   |     Using Transform      |         Using PCA        |       Using T + N        |    Using T + N + PCA     |  
+-------------------+--------+--------+--------+-------+-------+-------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+
|                   |    c=3 |    c=4 |    c=5 |   c=3 |   c=4 |   c=5 |    c=3 |    c=4 |    c=5 |    c=3 |    c=4 |    c=5 |    c=3 |    c=4 |    c=5 |    c=3 |    c=4 |    c=5 |
+===================+========+========+========+=======+=======+=======+========+========+========+========+========+========+========+========+========+========+========+========+
| Silhouette        |   0.68 |   0.46 |   0.45 |  0.48 |  0.5  |  0.47 |   0.51 |   0.55 |   0.59 |   0.8  |   0.69 |   0.69 |   0.63 |   0.64 |   0.66 |   0.63 |   0.63 |   0.67 |
+-------------------+--------+--------+--------+-------+-------+-------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+
| Calinski-Harabasz | 158.22 | 158.86 | 196.48 | 63.51 | 82.78 | 92.9  | 121.9  | 202.72 | 263.61 | 286.02 | 421.73 | 750.36 | 145.09 | 172.9  | 182.05 | 262.5  | 367.84 | 430.81 |
+-------------------+--------+--------+--------+-------+-------+-------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+
| Davies-Bouldin    |   0.31 |   0.7  |   0.64 |  0.81 |  0.57 |  0.72 |   0.56 |   0.66 |   0.49 |   0.16 |   0.43 |   0.31 |   0.58 |   0.44 |   0.31 |   0.42 |   0.54 |   0.4  |
+-------------------+--------+--------+--------+-------+-------+-------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+--------+
