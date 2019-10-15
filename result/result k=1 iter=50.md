/usr/local/bin/python3.7 /Users/bytedance/PycharmProjects/HAN/ex_acm3025.py
model: pre_trained/acm/acm_allMP_multi_fea_.ckpt
WARNING:tensorflow:From /Users/bytedance/PycharmProjects/HAN/ex_acm3025.py:13: The name tf.ConfigProto is deprecated. Please use tf.compat.v1.ConfigProto instead.
Dataset: acm

----- Opt. hyperparams -----
lr: 0.005
l2_coef: 0.001
----- Archi. hyperparams -----
nb. layers: 1
nb. units per layer: [8]
nb. attention heads: [8, 1]
residual: False
nonlinearity: <function elu at 0x12cd0aa70>
model: <class 'models.gat.HeteGAT_multi'>
data---------
 {'__header__': b'MATLAB 5.0 MAT-file Platform: nt, Created on: Wed Feb 27 20:29:23 2019', '__version__': '1.0', '__globals__': [], 'PTP': array([[1., 1., 1., ..., 1., 1., 1.],
       [1., 1., 1., ..., 1., 1., 1.],
       [1., 1., 1., ..., 1., 1., 1.],
       ...,
       [1., 1., 1., ..., 1., 1., 1.],
       [1., 1., 1., ..., 1., 1., 1.],
       [1., 1., 1., ..., 1., 1., 1.]]), 'PLP': array([[1., 0., 0., ..., 0., 0., 0.],
       [0., 1., 0., ..., 0., 1., 0.],
       [0., 0., 1., ..., 1., 0., 1.],
       ...,
       [0., 0., 1., ..., 1., 0., 1.],
       [0., 1., 0., ..., 0., 1., 0.],
       [0., 0., 1., ..., 1., 0., 1.]]), 'PAP': array([[1., 0., 0., ..., 0., 0., 0.],
       [0., 1., 0., ..., 0., 0., 0.],
       [0., 0., 1., ..., 0., 0., 0.],
       ...,
       [0., 0., 0., ..., 1., 0., 0.],
       [0., 0., 0., ..., 0., 1., 0.],
       [0., 0., 0., ..., 0., 0., 1.]]), 'feature': array([[1., 1., 1., ..., 0., 0., 0.],
       [0., 1., 0., ..., 0., 0., 0.],
       [0., 1., 0., ..., 0., 0., 0.],
       ...,
       [1., 1., 0., ..., 0., 0., 0.],
       [0., 1., 0., ..., 0., 0., 0.],
       [0., 0., 1., ..., 0., 0., 0.]]), 'label': array([[1., 0., 0.],
       [1., 0., 0.],
       [1., 0., 0.],
       ...,
       [0., 0., 1.],
       [0., 0., 1.],
       [0., 0., 1.]]), 'train_idx': array([[   0,    1,    2,    3,    4,    5,    6,    7,    8,    9,   10,
          11,   12,   13,   14,   15,   16,   17,   18,   19,   20,   21,
          22,   23,   24,   25,   26,   27,   28,   29,   30,   31,   32,
          33,   34,   35,   36,   37,   38,   39,   40,   41,   42,   43,
          44,   45,   46,   47,   48,   49,   50,   51,   52,   53,   54,
          55,   56,   57,   58,   59,   60,   61,   62,   63,   64,   65,
          66,   67,   68,   69,   70,   71,   72,   73,   74,   75,   76,
          77,   78,   79,   80,   81,   82,   83,   84,   85,   86,   87,
          88,   89,   90,   91,   92,   93,   94,   95,   96,   97,   98,
          99,  100,  101,  102,  103,  104,  105,  106,  107,  108,  109,
         110,  111,  112,  113,  114,  115,  116,  117,  118,  119,  120,
         121,  122,  123,  124,  125,  126,  127,  128,  129,  130,  131,
         132,  133,  134,  135,  136,  137,  138,  139,  140,  141,  142,
         143,  144,  145,  146,  147,  148,  149,  150,  151,  152,  153,
         154,  155,  156,  157,  158,  159,  160,  161,  162,  163,  164,
         165,  166,  167,  168,  169,  170,  171,  172,  173,  174,  175,
         176,  177,  178,  179,  180,  181,  182,  183,  184,  185,  186,
         187,  188,  189,  190,  191,  192,  193,  194,  195,  196,  197,
         198,  199, 1061, 1062, 1063, 1064, 1065, 1066, 1067, 1068, 1069,
        1070, 1071, 1072, 1073, 1074, 1075, 1076, 1077, 1078, 1079, 1080,
        1081, 1082, 1083, 1084, 1085, 1086, 1087, 1088, 1089, 1090, 1091,
        1092, 1093, 1094, 1095, 1096, 1097, 1098, 1099, 1100, 1101, 1102,
        1103, 1104, 1105, 1106, 1107, 1108, 1109, 1110, 1111, 1112, 1113,
        1114, 1115, 1116, 1117, 1118, 1119, 1120, 1121, 1122, 1123, 1124,
        1125, 1126, 1127, 1128, 1129, 1130, 1131, 1132, 1133, 1134, 1135,
        1136, 1137, 1138, 1139, 1140, 1141, 1142, 1143, 1144, 1145, 1146,
        1147, 1148, 1149, 1150, 1151, 1152, 1153, 1154, 1155, 1156, 1157,
        1158, 1159, 1160, 1161, 1162, 1163, 1164, 1165, 1166, 1167, 1168,
        1169, 1170, 1171, 1172, 1173, 1174, 1175, 1176, 1177, 1178, 1179,
        1180, 1181, 1182, 1183, 1184, 1185, 1186, 1187, 1188, 1189, 1190,
        1191, 1192, 1193, 1194, 1195, 1196, 1197, 1198, 1199, 1200, 1201,
        1202, 1203, 1204, 1205, 1206, 1207, 1208, 1209, 1210, 1211, 1212,
        1213, 1214, 1215, 1216, 1217, 1218, 1219, 1220, 1221, 1222, 1223,
        1224, 1225, 1226, 1227, 1228, 1229, 1230, 1231, 1232, 1233, 1234,
        1235, 1236, 1237, 1238, 1239, 1240, 1241, 1242, 1243, 1244, 1245,
        1246, 1247, 1248, 1249, 1250, 1251, 1252, 1253, 1254, 1255, 1256,
        1257, 1258, 1259, 1260, 2026, 2027, 2028, 2029, 2030, 2031, 2032,
        2033, 2034, 2035, 2036, 2037, 2038, 2039, 2040, 2041, 2042, 2043,
        2044, 2045, 2046, 2047, 2048, 2049, 2050, 2051, 2052, 2053, 2054,
        2055, 2056, 2057, 2058, 2059, 2060, 2061, 2062, 2063, 2064, 2065,
        2066, 2067, 2068, 2069, 2070, 2071, 2072, 2073, 2074, 2075, 2076,
        2077, 2078, 2079, 2080, 2081, 2082, 2083, 2084, 2085, 2086, 2087,
        2088, 2089, 2090, 2091, 2092, 2093, 2094, 2095, 2096, 2097, 2098,
        2099, 2100, 2101, 2102, 2103, 2104, 2105, 2106, 2107, 2108, 2109,
        2110, 2111, 2112, 2113, 2114, 2115, 2116, 2117, 2118, 2119, 2120,
        2121, 2122, 2123, 2124, 2125, 2126, 2127, 2128, 2129, 2130, 2131,
        2132, 2133, 2134, 2135, 2136, 2137, 2138, 2139, 2140, 2141, 2142,
        2143, 2144, 2145, 2146, 2147, 2148, 2149, 2150, 2151, 2152, 2153,
        2154, 2155, 2156, 2157, 2158, 2159, 2160, 2161, 2162, 2163, 2164,
        2165, 2166, 2167, 2168, 2169, 2170, 2171, 2172, 2173, 2174, 2175,
        2176, 2177, 2178, 2179, 2180, 2181, 2182, 2183, 2184, 2185, 2186,
        2187, 2188, 2189, 2190, 2191, 2192, 2193, 2194, 2195, 2196, 2197,
        2198, 2199, 2200, 2201, 2202, 2203, 2204, 2205, 2206, 2207, 2208,
        2209, 2210, 2211, 2212, 2213, 2214, 2215, 2216, 2217, 2218, 2219,
        2220, 2221, 2222, 2223, 2224, 2225]], dtype=int32), 'val_idx': array([[ 200,  201,  202,  203,  204,  205,  206,  207,  208,  209,  210,
         211,  212,  213,  214,  215,  216,  217,  218,  219,  220,  221,
         222,  223,  224,  225,  226,  227,  228,  229,  230,  231,  232,
         233,  234,  235,  236,  237,  238,  239,  240,  241,  242,  243,
         244,  245,  246,  247,  248,  249,  250,  251,  252,  253,  254,
         255,  256,  257,  258,  259,  260,  261,  262,  263,  264,  265,
         266,  267,  268,  269,  270,  271,  272,  273,  274,  275,  276,
         277,  278,  279,  280,  281,  282,  283,  284,  285,  286,  287,
         288,  289,  290,  291,  292,  293,  294,  295,  296,  297,  298,
         299, 1261, 1262, 1263, 1264, 1265, 1266, 1267, 1268, 1269, 1270,
        1271, 1272, 1273, 1274, 1275, 1276, 1277, 1278, 1279, 1280, 1281,
        1282, 1283, 1284, 1285, 1286, 1287, 1288, 1289, 1290, 1291, 1292,
        1293, 1294, 1295, 1296, 1297, 1298, 1299, 1300, 1301, 1302, 1303,
        1304, 1305, 1306, 1307, 1308, 1309, 1310, 1311, 1312, 1313, 1314,
        1315, 1316, 1317, 1318, 1319, 1320, 1321, 1322, 1323, 1324, 1325,
        1326, 1327, 1328, 1329, 1330, 1331, 1332, 1333, 1334, 1335, 1336,
        1337, 1338, 1339, 1340, 1341, 1342, 1343, 1344, 1345, 1346, 1347,
        1348, 1349, 1350, 1351, 1352, 1353, 1354, 1355, 1356, 1357, 1358,
        1359, 1360, 2226, 2227, 2228, 2229, 2230, 2231, 2232, 2233, 2234,
        2235, 2236, 2237, 2238, 2239, 2240, 2241, 2242, 2243, 2244, 2245,
        2246, 2247, 2248, 2249, 2250, 2251, 2252, 2253, 2254, 2255, 2256,
        2257, 2258, 2259, 2260, 2261, 2262, 2263, 2264, 2265, 2266, 2267,
        2268, 2269, 2270, 2271, 2272, 2273, 2274, 2275, 2276, 2277, 2278,
        2279, 2280, 2281, 2282, 2283, 2284, 2285, 2286, 2287, 2288, 2289,
        2290, 2291, 2292, 2293, 2294, 2295, 2296, 2297, 2298, 2299, 2300,
        2301, 2302, 2303, 2304, 2305, 2306, 2307, 2308, 2309, 2310, 2311,
        2312, 2313, 2314, 2315, 2316, 2317, 2318, 2319, 2320, 2321, 2322,
        2323, 2324, 2325]], dtype=int32), 'test_idx': array([[ 300,  301,  302, ..., 3022, 3023, 3024]], dtype=int32)}
y_train:(3025, 3), y_val:(3025, 3), y_test:(3025, 3), train_idx:(1, 600), val_idx:(1, 300), test_idx:(1, 2125)
build graph...
WARNING:tensorflow:From /Users/bytedance/PycharmProjects/HAN/ex_acm3025.py:128: The name tf.placeholder is deprecated. Please use tf.compat.v1.placeholder instead.

WARNING:tensorflow:From /Users/bytedance/PycharmProjects/HAN/utils/layers.py:19: calling dropout (from tensorflow.python.ops.nn_ops) with keep_prob is deprecated and will be removed in a future version.
Instructions for updating:
Please use `rate` instead of `keep_prob`. Rate should be set to `rate = 1 - keep_prob`.
WARNING:tensorflow:From /Users/bytedance/PycharmProjects/HAN/utils/layers.py:20: conv1d (from tensorflow.python.layers.convolutional) is deprecated and will be removed in a future version.
Instructions for updating:
Use `tf.keras.layers.Conv1D` instead.
WARNING:tensorflow:From /usr/local/lib/python3.7/site-packages/tensorflow/python/ops/init_ops.py:1251: calling VarianceScaling.__init__ (from tensorflow.python.ops.init_ops) with dtype is deprecated and will be removed in a future version.
Instructions for updating:
Call initializer instance with the dtype argument instead of passing it to the constructor
WARNING:tensorflow:
The TensorFlow contrib module will not be included in TensorFlow 2.0.
For more information, please see:
  * https://github.com/tensorflow/community/blob/master/rfcs/20180907-contrib-sunset.md
  * https://github.com/tensorflow/addons
  * https://github.com/tensorflow/io (for I/O related ops)
If you depend on functionality not listed there, please file an issue.

WARNING:tensorflow:From /Users/bytedance/PycharmProjects/HAN/utils/layers.py:145: The name tf.random_normal is deprecated. Please use tf.random.normal instead.

WARNING:tensorflow:From /Users/bytedance/PycharmProjects/HAN/models/gat.py:68: dense (from tensorflow.python.layers.core) is deprecated and will be removed in a future version.
Instructions for updating:
Use keras.layers.dense instead.
de
WARNING:tensorflow:From /Users/bytedance/PycharmProjects/HAN/models/base_gattn.py:44: softmax_cross_entropy_with_logits (from tensorflow.python.ops.nn_ops) is deprecated and will be removed in a future version.
Instructions for updating:

Future major versions of TensorFlow will allow gradients to flow
into the labels input on backprop by default.

See `tf.nn.softmax_cross_entropy_with_logits_v2`.

WARNING:tensorflow:From /Users/bytedance/PycharmProjects/HAN/models/base_gattn.py:14: The name tf.trainable_variables is deprecated. Please use tf.compat.v1.trainable_variables instead.

WARNING:tensorflow:From /Users/bytedance/PycharmProjects/HAN/models/base_gattn.py:19: The name tf.train.AdamOptimizer is deprecated. Please use tf.compat.v1.train.AdamOptimizer instead.

WARNING:tensorflow:From /Users/bytedance/PycharmProjects/HAN/ex_acm3025.py:155: The name tf.train.Saver is deprecated. Please use tf.compat.v1.train.Saver instead.

WARNING:tensorflow:From /Users/bytedance/PycharmProjects/HAN/ex_acm3025.py:157: The name tf.global_variables_initializer is deprecated. Please use tf.compat.v1.global_variables_initializer instead.

2019-10-14 12:09:24.460864: I tensorflow/core/platform/cpu_feature_guard.cc:142] Your CPU supports instructions that this TensorFlow binary was not compiled to use: AVX2 FMA
Epoch: 0, att_val: [0.4955789  0.50442106]
Training: loss = 1.14984, acc = 0.32667 | Val: loss = 0.98673, acc = 0.33333
Epoch: 1, att_val: [0.20312367 0.796877  ]
Training: loss = 1.02085, acc = 0.35000 | Val: loss = 0.93201, acc = 0.65333
Epoch: 2, att_val: [0.35052487 0.649475  ]
Training: loss = 0.92699, acc = 0.65500 | Val: loss = 0.62344, acc = 0.85000
Epoch: 3, att_val: [0.5660625 0.4339376]
Training: loss = 0.70543, acc = 0.75333 | Val: loss = 0.49149, acc = 0.90333
Epoch: 4, att_val: [0.75736016 0.24264178]
Training: loss = 0.54738, acc = 0.87667 | Val: loss = 0.46171, acc = 0.85000
Epoch: 5, att_val: [0.7997707 0.2002295]
Training: loss = 0.47037, acc = 0.88000 | Val: loss = 0.32330, acc = 0.92667
Epoch: 6, att_val: [0.7469513  0.25304922]
Training: loss = 0.36095, acc = 0.92500 | Val: loss = 0.25137, acc = 0.94667
Epoch: 7, att_val: [0.6509511 0.3490492]
Training: loss = 0.31034, acc = 0.92500 | Val: loss = 0.22692, acc = 0.95333
Epoch: 8, att_val: [0.5337483 0.4662517]
Training: loss = 0.25691, acc = 0.94000 | Val: loss = 0.20574, acc = 0.95000
Epoch: 9, att_val: [0.50610805 0.49389237]
Training: loss = 0.23951, acc = 0.93667 | Val: loss = 0.17534, acc = 0.94333
Epoch: 10, att_val: [0.56190854 0.43809128]
Training: loss = 0.20535, acc = 0.94333 | Val: loss = 0.14953, acc = 0.95000
Epoch: 11, att_val: [0.6407764  0.35922384]
Training: loss = 0.18614, acc = 0.95500 | Val: loss = 0.13225, acc = 0.96333
Epoch: 12, att_val: [0.6918025  0.30819625]
Training: loss = 0.14587, acc = 0.96500 | Val: loss = 0.12257, acc = 0.96667
Epoch: 13, att_val: [0.7251597  0.27484122]
Training: loss = 0.14831, acc = 0.95167 | Val: loss = 0.12049, acc = 0.96667
Epoch: 14, att_val: [0.74630636 0.253694  ]
Training: loss = 0.14625, acc = 0.95667 | Val: loss = 0.12224, acc = 0.95333
Epoch: 15, att_val: [0.7285973 0.2714013]
Training: loss = 0.14072, acc = 0.95667 | Val: loss = 0.12347, acc = 0.95333
Epoch: 16, att_val: [0.7345245 0.2654752]
Training: loss = 0.12701, acc = 0.96167 | Val: loss = 0.12007, acc = 0.96000
Epoch: 17, att_val: [0.68347883 0.31652185]
Training: loss = 0.12674, acc = 0.96667 | Val: loss = 0.11660, acc = 0.96667
Epoch: 18, att_val: [0.65191174 0.3480882 ]
Training: loss = 0.12072, acc = 0.96333 | Val: loss = 0.11391, acc = 0.96667
Epoch: 19, att_val: [0.5778373  0.42216256]
Training: loss = 0.10270, acc = 0.97167 | Val: loss = 0.11566, acc = 0.96333
Epoch: 20, att_val: [0.5470436  0.45295593]
Training: loss = 0.10869, acc = 0.97167 | Val: loss = 0.12032, acc = 0.96333
Epoch: 21, att_val: [0.5345839  0.46541664]
Training: loss = 0.09326, acc = 0.97000 | Val: loss = 0.12503, acc = 0.95667
Epoch: 22, att_val: [0.53410566 0.4658944 ]
Training: loss = 0.09603, acc = 0.96500 | Val: loss = 0.12667, acc = 0.95333
Epoch: 23, att_val: [0.55482244 0.44517788]
Training: loss = 0.08179, acc = 0.97333 | Val: loss = 0.12671, acc = 0.95333
Epoch: 24, att_val: [0.5862423  0.41375762]
Training: loss = 0.08027, acc = 0.97500 | Val: loss = 0.12609, acc = 0.96000
Epoch: 25, att_val: [0.6286925  0.37130776]
Training: loss = 0.06878, acc = 0.98000 | Val: loss = 0.12588, acc = 0.96000
Epoch: 26, att_val: [0.64411837 0.35588202]
Training: loss = 0.05553, acc = 0.98667 | Val: loss = 0.12562, acc = 0.96000
Epoch: 27, att_val: [0.6525337  0.34746662]
Training: loss = 0.07590, acc = 0.97667 | Val: loss = 0.12368, acc = 0.96333
Epoch: 28, att_val: [0.6503776  0.34962237]
Training: loss = 0.06354, acc = 0.97833 | Val: loss = 0.12119, acc = 0.96667
Epoch: 29, att_val: [0.6382004 0.3617998]
Training: loss = 0.06923, acc = 0.97833 | Val: loss = 0.11975, acc = 0.96333
Epoch: 30, att_val: [0.62041295 0.37958783]
Training: loss = 0.06151, acc = 0.97833 | Val: loss = 0.11954, acc = 0.96333
Epoch: 31, att_val: [0.6075198  0.39248013]
Training: loss = 0.05589, acc = 0.98667 | Val: loss = 0.11875, acc = 0.96667
Epoch: 32, att_val: [0.6007355  0.39926466]
Training: loss = 0.05258, acc = 0.99000 | Val: loss = 0.11667, acc = 0.96667
Epoch: 33, att_val: [0.6063726 0.393627 ]
Training: loss = 0.06136, acc = 0.98000 | Val: loss = 0.11377, acc = 0.96667
Epoch: 34, att_val: [0.6243718 0.3756277]
Training: loss = 0.05057, acc = 0.98500 | Val: loss = 0.11244, acc = 0.96667
Epoch: 35, att_val: [0.6552982  0.34470153]
Training: loss = 0.05691, acc = 0.98333 | Val: loss = 0.11034, acc = 0.96667
Epoch: 36, att_val: [0.6833053 0.3166951]
Training: loss = 0.05721, acc = 0.98333 | Val: loss = 0.10786, acc = 0.96667
Epoch: 37, att_val: [0.693813  0.3061866]
Training: loss = 0.06017, acc = 0.98167 | Val: loss = 0.10464, acc = 0.96667
Epoch: 38, att_val: [0.71065235 0.28934798]
Training: loss = 0.05774, acc = 0.98333 | Val: loss = 0.10134, acc = 0.96667
Epoch: 39, att_val: [0.69454354 0.30545688]
Training: loss = 0.04745, acc = 0.98333 | Val: loss = 0.09726, acc = 0.96667
Epoch: 40, att_val: [0.68033516 0.31966382]
Training: loss = 0.04620, acc = 0.98500 | Val: loss = 0.09452, acc = 0.96667
Epoch: 41, att_val: [0.64940685 0.35059267]
Training: loss = 0.04505, acc = 0.98833 | Val: loss = 0.09389, acc = 0.97000
Epoch: 42, att_val: [0.61524695 0.3847532 ]
Training: loss = 0.04036, acc = 0.99000 | Val: loss = 0.09495, acc = 0.97000
Epoch: 43, att_val: [0.5911567  0.40884334]
Training: loss = 0.05422, acc = 0.98500 | Val: loss = 0.09518, acc = 0.97000
Epoch: 44, att_val: [0.5934044 0.4065957]
Training: loss = 0.05505, acc = 0.98167 | Val: loss = 0.09606, acc = 0.96333
Epoch: 45, att_val: [0.61706084 0.38293934]
Training: loss = 0.04352, acc = 0.98833 | Val: loss = 0.09907, acc = 0.96333
Epoch: 46, att_val: [0.6525211  0.34747756]
Training: loss = 0.04844, acc = 0.98667 | Val: loss = 0.10221, acc = 0.96667
Epoch: 47, att_val: [0.6714746  0.32852435]
Training: loss = 0.03140, acc = 0.99500 | Val: loss = 0.10437, acc = 0.96667
Epoch: 48, att_val: [0.69304883 0.30695036]
Training: loss = 0.04163, acc = 0.98833 | Val: loss = 0.10488, acc = 0.96667
Epoch: 49, att_val: [0.72095495 0.2790458 ]
Training: loss = 0.05069, acc = 0.98333 | Val: loss = 0.10191, acc = 0.96667
load model from : pre_trained/acm/acm_allMP_multi_fea_.ckpt
{'__header__': b'MATLAB 5.0 MAT-file Platform: nt, Created on: Wed Feb 27 20:29:23 2019', '__version__': '1.0', '__globals__': [], 'PTP': array([[1., 1., 1., ..., 1., 1., 1.],
       [1., 1., 1., ..., 1., 1., 1.],
       [1., 1., 1., ..., 1., 1., 1.],
       ...,
       [1., 1., 1., ..., 1., 1., 1.],
       [1., 1., 1., ..., 1., 1., 1.],
       [1., 1., 1., ..., 1., 1., 1.]]), 'PLP': array([[1., 0., 0., ..., 0., 0., 0.],
       [0., 1., 0., ..., 0., 1., 0.],
       [0., 0., 1., ..., 1., 0., 1.],
       ...,
       [0., 0., 1., ..., 1., 0., 1.],
       [0., 1., 0., ..., 0., 1., 0.],
       [0., 0., 1., ..., 1., 0., 1.]]), 'PAP': array([[1., 0., 0., ..., 0., 0., 0.],
       [0., 1., 0., ..., 0., 0., 0.],
       [0., 0., 1., ..., 0., 0., 0.],
       ...,
       [0., 0., 0., ..., 1., 0., 0.],
       [0., 0., 0., ..., 0., 1., 0.],
       [0., 0., 0., ..., 0., 0., 1.]]), 'feature': array([[ 1.        ,  1.        ,  1.        , ..., -0.47190422,
        -0.26694456,  0.28576994],
       [ 0.        ,  1.        ,  0.        , ..., -0.39964229,
        -0.19356529,  0.08938528],
       [ 0.        ,  1.        ,  0.        , ..., -0.31065589,
        -0.12109841,  0.07468073],
       ...,
       [ 1.        ,  1.        ,  0.        , ..., -0.05724558,
         0.45221037,  0.03634376],
       [ 0.        ,  1.        ,  0.        , ..., -0.37223813,
        -0.17173035,  0.06762663],
       [ 0.        ,  0.        ,  1.        , ...,  0.0025543 ,
         0.46422756,  0.14256948]]), 'label': array([[1., 0., 0.],
       [1., 0., 0.],
       [1., 0., 0.],
       ...,
       [0., 0., 1.],
       [0., 0., 1.],
WARNING:tensorflow:From /usr/local/lib/python3.7/site-packages/tensorflow/python/training/saver.py:1276: checkpoint_exists (from tensorflow.python.training.checkpoint_management) is deprecated and will be removed in a future version.
       [0., 0., 1.]]), 'train_idx': array([[   0,    1,    2,    3,    4,    5,    6,    7,    8,    9,   10,
Instructions for updating:
Use standard file APIs to check for files with this prefix.
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
          11,   12,   13,   14,   15,   16,   17,   18,   19,   20,   21,
  FutureWarning)
          22,   23,   24,   25,   26,   27,   28,   29,   30,   31,   32,
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
          33,   34,   35,   36,   37,   38,   39,   40,   41,   42,   43,
  FutureWarning)
          44,   45,   46,   47,   48,   49,   50,   51,   52,   53,   54,
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
          55,   56,   57,   58,   59,   60,   61,   62,   63,   64,   65,
  FutureWarning)
          66,   67,   68,   69,   70,   71,   72,   73,   74,   75,   76,
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
          77,   78,   79,   80,   81,   82,   83,   84,   85,   86,   87,
  FutureWarning)
          88,   89,   90,   91,   92,   93,   94,   95,   96,   97,   98,
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
          99,  100,  101,  102,  103,  104,  105,  106,  107,  108,  109,
  FutureWarning)
         110,  111,  112,  113,  114,  115,  116,  117,  118,  119,  120,
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
         121,  122,  123,  124,  125,  126,  127,  128,  129,  130,  131,
  FutureWarning)
         132,  133,  134,  135,  136,  137,  138,  139,  140,  141,  142,
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
         143,  144,  145,  146,  147,  148,  149,  150,  151,  152,  153,
  FutureWarning)
         154,  155,  156,  157,  158,  159,  160,  161,  162,  163,  164,
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
         165,  166,  167,  168,  169,  170,  171,  172,  173,  174,  175,
  FutureWarning)
         176,  177,  178,  179,  180,  181,  182,  183,  184,  185,  186,
         187,  188,  189,  190,  191,  192,  193,  194,  195,  196,  197,
         198,  199, 1061, 1062, 1063, 1064, 1065, 1066, 1067, 1068, 1069,
        1070, 1071, 1072, 1073, 1074, 1075, 1076, 1077, 1078, 1079, 1080,
        1081, 1082, 1083, 1084, 1085, 1086, 1087, 1088, 1089, 1090, 1091,
        1092, 1093, 1094, 1095, 1096, 1097, 1098, 1099, 1100, 1101, 1102,
        1103, 1104, 1105, 1106, 1107, 1108, 1109, 1110, 1111, 1112, 1113,
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
        1114, 1115, 1116, 1117, 1118, 1119, 1120, 1121, 1122, 1123, 1124,
  FutureWarning)
        1125, 1126, 1127, 1128, 1129, 1130, 1131, 1132, 1133, 1134, 1135,
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
        1136, 1137, 1138, 1139, 1140, 1141, 1142, 1143, 1144, 1145, 1146,
  FutureWarning)
        1147, 1148, 1149, 1150, 1151, 1152, 1153, 1154, 1155, 1156, 1157,
        1158, 1159, 1160, 1161, 1162, 1163, 1164, 1165, 1166, 1167, 1168,
        1169, 1170, 1171, 1172, 1173, 1174, 1175, 1176, 1177, 1178, 1179,
        1180, 1181, 1182, 1183, 1184, 1185, 1186, 1187, 1188, 1189, 1190,
        1191, 1192, 1193, 1194, 1195, 1196, 1197, 1198, 1199, 1200, 1201,
        1202, 1203, 1204, 1205, 1206, 1207, 1208, 1209, 1210, 1211, 1212,
        1213, 1214, 1215, 1216, 1217, 1218, 1219, 1220, 1221, 1222, 1223,
        1224, 1225, 1226, 1227, 1228, 1229, 1230, 1231, 1232, 1233, 1234,
        1235, 1236, 1237, 1238, 1239, 1240, 1241, 1242, 1243, 1244, 1245,
        1246, 1247, 1248, 1249, 1250, 1251, 1252, 1253, 1254, 1255, 1256,
        1257, 1258, 1259, 1260, 2026, 2027, 2028, 2029, 2030, 2031, 2032,
        2033, 2034, 2035, 2036, 2037, 2038, 2039, 2040, 2041, 2042, 2043,
        2044, 2045, 2046, 2047, 2048, 2049, 2050, 2051, 2052, 2053, 2054,
        2055, 2056, 2057, 2058, 2059, 2060, 2061, 2062, 2063, 2064, 2065,
        2066, 2067, 2068, 2069, 2070, 2071, 2072, 2073, 2074, 2075, 2076,
        2077, 2078, 2079, 2080, 2081, 2082, 2083, 2084, 2085, 2086, 2087,
        2088, 2089, 2090, 2091, 2092, 2093, 2094, 2095, 2096, 2097, 2098,
        2099, 2100, 2101, 2102, 2103, 2104, 2105, 2106, 2107, 2108, 2109,
        2110, 2111, 2112, 2113, 2114, 2115, 2116, 2117, 2118, 2119, 2120,
        2121, 2122, 2123, 2124, 2125, 2126, 2127, 2128, 2129, 2130, 2131,
        2132, 2133, 2134, 2135, 2136, 2137, 2138, 2139, 2140, 2141, 2142,
        2143, 2144, 2145, 2146, 2147, 2148, 2149, 2150, 2151, 2152, 2153,
        2154, 2155, 2156, 2157, 2158, 2159, 2160, 2161, 2162, 2163, 2164,
        2165, 2166, 2167, 2168, 2169, 2170, 2171, 2172, 2173, 2174, 2175,
        2176, 2177, 2178, 2179, 2180, 2181, 2182, 2183, 2184, 2185, 2186,
        2187, 2188, 2189, 2190, 2191, 2192, 2193, 2194, 2195, 2196, 2197,
        2198, 2199, 2200, 2201, 2202, 2203, 2204, 2205, 2206, 2207, 2208,
        2209, 2210, 2211, 2212, 2213, 2214, 2215, 2216, 2217, 2218, 2219,
        2220, 2221, 2222, 2223, 2224, 2225]], dtype=int32), 'val_idx': array([[ 200,  201,  202,  203,  204,  205,  206,  207,  208,  209,  210,
         211,  212,  213,  214,  215,  216,  217,  218,  219,  220,  221,
         222,  223,  224,  225,  226,  227,  228,  229,  230,  231,  232,
         233,  234,  235,  236,  237,  238,  239,  240,  241,  242,  243,
         244,  245,  246,  247,  248,  249,  250,  251,  252,  253,  254,
         255,  256,  257,  258,  259,  260,  261,  262,  263,  264,  265,
         266,  267,  268,  269,  270,  271,  272,  273,  274,  275,  276,
         277,  278,  279,  280,  281,  282,  283,  284,  285,  286,  287,
         288,  289,  290,  291,  292,  293,  294,  295,  296,  297,  298,
         299, 1261, 1262, 1263, 1264, 1265, 1266, 1267, 1268, 1269, 1270,
        1271, 1272, 1273, 1274, 1275, 1276, 1277, 1278, 1279, 1280, 1281,
        1282, 1283, 1284, 1285, 1286, 1287, 1288, 1289, 1290, 1291, 1292,
        1293, 1294, 1295, 1296, 1297, 1298, 1299, 1300, 1301, 1302, 1303,
        1304, 1305, 1306, 1307, 1308, 1309, 1310, 1311, 1312, 1313, 1314,
        1315, 1316, 1317, 1318, 1319, 1320, 1321, 1322, 1323, 1324, 1325,
        1326, 1327, 1328, 1329, 1330, 1331, 1332, 1333, 1334, 1335, 1336,
        1337, 1338, 1339, 1340, 1341, 1342, 1343, 1344, 1345, 1346, 1347,
        1348, 1349, 1350, 1351, 1352, 1353, 1354, 1355, 1356, 1357, 1358,
        1359, 1360, 2226, 2227, 2228, 2229, 2230, 2231, 2232, 2233, 2234,
        2235, 2236, 2237, 2238, 2239, 2240, 2241, 2242, 2243, 2244, 2245,
        2246, 2247, 2248, 2249, 2250, 2251, 2252, 2253, 2254, 2255, 2256,
        2257, 2258, 2259, 2260, 2261, 2262, 2263, 2264, 2265, 2266, 2267,
        2268, 2269, 2270, 2271, 2272, 2273, 2274, 2275, 2276, 2277, 2278,
        2279, 2280, 2281, 2282, 2283, 2284, 2285, 2286, 2287, 2288, 2289,
        2290, 2291, 2292, 2293, 2294, 2295, 2296, 2297, 2298, 2299, 2300,
        2301, 2302, 2303, 2304, 2305, 2306, 2307, 2308, 2309, 2310, 2311,
        2312, 2313, 2314, 2315, 2316, 2317, 2318, 2319, 2320, 2321, 2322,
        2323, 2324, 2325]], dtype=int32), 'test_idx': array([[ 300,  301,  302, ..., 3022, 3023, 3024]], dtype=int32)}
jhy_final_embedding (3025, 64) 
 [[ 0.00604042  0.4127618   0.894066   ... -0.47190422 -0.26694456
   0.28576994]
 [ 0.11082105  0.73682153  0.8777518  ... -0.3996423  -0.1935653
   0.08938528]
 [-0.07945052  0.53286225  0.58108956 ... -0.3106559  -0.12109841
   0.07468073]
 ...
 [ 0.32815292  0.79809576  0.18554522 ... -0.05724558  0.45221037
   0.03634376]
 [ 0.03676745  0.59195095  0.8226902  ... -0.37223813 -0.17173035
   0.06762663]
 [ 0.4672919   0.75375354 -0.04265698 ...  0.0025543   0.46422756
   0.14256948]]
Test loss: 0.39122143387794495 ; Test accuracy: 0.8710565567016602
start knn, kmean.....
xx: (2125, 64), yy: (2125, 3)
KNN(10avg, split:0.2, k=5) f1_macro: 0.8910, f1_micro: 0.8898
KNN(10avg, split:0.4, k=5) f1_macro: 0.8903, f1_micro: 0.8885
KNN(10avg, split:0.6, k=5) f1_macro: 0.9005, f1_micro: 0.8988
KNN(10avg, split:0.8, k=5) f1_macro: 0.8940, f1_micro: 0.8920
NMI (10 avg): 0.6103 , ARI (10avg): 0.5965

Process finished with exit code 0
