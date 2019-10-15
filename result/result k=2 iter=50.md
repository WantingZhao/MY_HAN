/usr/local/bin/python3.7 /Users/bytedance/PycharmProjects/HAN/ex_acm3025.py
model: pre_trained/acm/acm_allMP_multi_fea_.ckpt
Dataset: acm
WARNING:tensorflow:From /Users/bytedance/PycharmProjects/HAN/ex_acm3025.py:13: The name tf.ConfigProto is deprecated. Please use tf.compat.v1.ConfigProto instead.
----- Opt. hyperparams -----
lr: 0.005

l2_coef: 0.001
----- Archi. hyperparams -----
nb. layers: 1
nb. units per layer: [8]
nb. attention heads: [8, 1]
residual: False
nonlinearity: <function elu at 0x110d56a70>
model: <class 'models.gat.HeteGAT_multi'>
data---------
 {'__header__': b'MATLAB 5.0 MAT-file Platform: posix, Created on: Mon Oct 14 12:12:19 2019', '__version__': '1.0', '__globals__': [], 'PTP': array([[1., 1., 1., ..., 1., 1., 1.],
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

2019-10-14 12:57:02.961309: I tensorflow/core/platform/cpu_feature_guard.cc:142] Your CPU supports instructions that this TensorFlow binary was not compiled to use: AVX2 FMA
Epoch: 0, att_val: [0.46722192 0.5327782 ]
Training: loss = 1.18201, acc = 0.31500 | Val: loss = 0.77984, acc = 0.64000
Epoch: 1, att_val: [0.19984585 0.8001535 ]
Training: loss = 0.76341, acc = 0.66500 | Val: loss = 0.48226, acc = 0.72000
Epoch: 2, att_val: [0.24359518 0.7564047 ]
Training: loss = 0.55617, acc = 0.71000 | Val: loss = 0.20681, acc = 0.96667
Epoch: 3, att_val: [0.53630793 0.4636919 ]
Training: loss = 0.27435, acc = 0.94000 | Val: loss = 0.14242, acc = 0.95667
Epoch: 4, att_val: [0.7986412  0.20135754]
Training: loss = 0.17134, acc = 0.96833 | Val: loss = 0.11931, acc = 0.96333
Epoch: 5, att_val: [0.8971324  0.10286835]
Training: loss = 0.13292, acc = 0.96000 | Val: loss = 0.10997, acc = 0.97000
Epoch: 6, att_val: [0.9315378  0.06846279]
Training: loss = 0.11241, acc = 0.97000 | Val: loss = 0.10770, acc = 0.95667
Epoch: 7, att_val: [0.94340014 0.05659946]
Training: loss = 0.10862, acc = 0.97833 | Val: loss = 0.10537, acc = 0.96000
Epoch: 8, att_val: [0.93294615 0.0670536 ]
Training: loss = 0.09295, acc = 0.98000 | Val: loss = 0.09540, acc = 0.96000
Epoch: 9, att_val: [0.9149854  0.08501325]
Training: loss = 0.08643, acc = 0.97333 | Val: loss = 0.08248, acc = 0.97333
Epoch: 10, att_val: [0.88155854 0.11844017]
Training: loss = 0.08991, acc = 0.97500 | Val: loss = 0.08506, acc = 0.97000
Epoch: 11, att_val: [0.8886348  0.11136479]
Training: loss = 0.08213, acc = 0.97833 | Val: loss = 0.08547, acc = 0.97333
Epoch: 12, att_val: [0.872461   0.12753952]
Training: loss = 0.08515, acc = 0.97667 | Val: loss = 0.09446, acc = 0.97000
Epoch: 13, att_val: [0.8862997  0.11370137]
Training: loss = 0.07079, acc = 0.98500 | Val: loss = 0.11145, acc = 0.96333
Epoch: 14, att_val: [0.8829486  0.11705062]
Training: loss = 0.06861, acc = 0.98167 | Val: loss = 0.12266, acc = 0.97000
Epoch: 15, att_val: [0.88561493 0.11438458]
Training: loss = 0.07575, acc = 0.98333 | Val: loss = 0.12605, acc = 0.97333
Epoch: 16, att_val: [0.86480916 0.13519192]
Training: loss = 0.06701, acc = 0.98333 | Val: loss = 0.12383, acc = 0.96667
Epoch: 17, att_val: [0.84873796 0.15126109]
Training: loss = 0.05909, acc = 0.98500 | Val: loss = 0.11770, acc = 0.96667
Epoch: 18, att_val: [0.82846963 0.17153111]
Training: loss = 0.05335, acc = 0.98667 | Val: loss = 0.11237, acc = 0.96667
Epoch: 19, att_val: [0.79105306 0.20894732]
Training: loss = 0.07148, acc = 0.98000 | Val: loss = 0.10452, acc = 0.96667
Epoch: 20, att_val: [0.7602703  0.23972905]
Training: loss = 0.04814, acc = 0.98833 | Val: loss = 0.09840, acc = 0.97333
Epoch: 21, att_val: [0.7190738 0.2809261]
Training: loss = 0.05606, acc = 0.98667 | Val: loss = 0.09208, acc = 0.98000
Epoch: 22, att_val: [0.67725754 0.3227431 ]
Training: loss = 0.04349, acc = 0.98667 | Val: loss = 0.09212, acc = 0.98000
Epoch: 23, att_val: [0.63999945 0.36000085]
Training: loss = 0.05230, acc = 0.98500 | Val: loss = 0.09137, acc = 0.98000
Epoch: 24, att_val: [0.638462   0.36153775]
Training: loss = 0.05827, acc = 0.98167 | Val: loss = 0.09177, acc = 0.97667
Epoch: 25, att_val: [0.67605734 0.32394287]
Training: loss = 0.05021, acc = 0.98667 | Val: loss = 0.09852, acc = 0.97333
Epoch: 26, att_val: [0.71729547 0.28270486]
Training: loss = 0.04500, acc = 0.98833 | Val: loss = 0.10712, acc = 0.96667
Epoch: 27, att_val: [0.76342666 0.2365753 ]
Training: loss = 0.02652, acc = 0.99333 | Val: loss = 0.11495, acc = 0.96667
Epoch: 28, att_val: [0.79356575 0.20643276]
Training: loss = 0.03181, acc = 0.99167 | Val: loss = 0.12021, acc = 0.96667
Epoch: 29, att_val: [0.81577444 0.18422532]
Training: loss = 0.03651, acc = 0.99333 | Val: loss = 0.11696, acc = 0.97000
Epoch: 30, att_val: [0.8199628  0.18003707]
Training: loss = 0.04209, acc = 0.98833 | Val: loss = 0.11325, acc = 0.96667
Epoch: 31, att_val: [0.82567585 0.174324  ]
Training: loss = 0.03888, acc = 0.98833 | Val: loss = 0.10812, acc = 0.97333
Epoch: 32, att_val: [0.8269317  0.17306931]
Training: loss = 0.03270, acc = 0.98500 | Val: loss = 0.10438, acc = 0.97333
Epoch: 33, att_val: [0.82867646 0.17132391]
Training: loss = 0.02118, acc = 0.99333 | Val: loss = 0.10251, acc = 0.97667
Epoch: 34, att_val: [0.8205919  0.17940791]
Training: loss = 0.04772, acc = 0.97833 | Val: loss = 0.10078, acc = 0.98000
Epoch: 35, att_val: [0.8145464  0.18545392]
Training: loss = 0.03517, acc = 0.99000 | Val: loss = 0.09970, acc = 0.98000
Epoch: 36, att_val: [0.806233   0.19376774]
Training: loss = 0.03546, acc = 0.98833 | Val: loss = 0.09882, acc = 0.98000
Epoch: 37, att_val: [0.79901624 0.20098296]
Training: loss = 0.03105, acc = 0.98833 | Val: loss = 0.09862, acc = 0.98000
Epoch: 38, att_val: [0.8012003  0.19880083]
Training: loss = 0.02876, acc = 0.98667 | Val: loss = 0.09736, acc = 0.97667
Epoch: 39, att_val: [0.82270163 0.17729731]
Training: loss = 0.03144, acc = 0.98667 | Val: loss = 0.09780, acc = 0.97333
Epoch: 40, att_val: [0.8369845  0.16301508]
Training: loss = 0.03562, acc = 0.99333 | Val: loss = 0.10174, acc = 0.97000
Epoch: 41, att_val: [0.8490935  0.15090567]
Training: loss = 0.02964, acc = 0.99000 | Val: loss = 0.10816, acc = 0.97000
Epoch: 42, att_val: [0.8496467  0.15035209]
Training: loss = 0.02882, acc = 0.99333 | Val: loss = 0.11587, acc = 0.96667
Epoch: 43, att_val: [0.8680122  0.13198826]
Training: loss = 0.02171, acc = 0.99500 | Val: loss = 0.12202, acc = 0.96000
Epoch: 44, att_val: [0.8703909  0.12960882]
Training: loss = 0.02856, acc = 0.99167 | Val: loss = 0.12644, acc = 0.95667
Epoch: 45, att_val: [0.8828457  0.11715439]
Training: loss = 0.03514, acc = 0.99000 | Val: loss = 0.12643, acc = 0.96000
Epoch: 46, att_val: [0.8610812  0.13891885]
Training: loss = 0.02430, acc = 0.99000 | Val: loss = 0.12390, acc = 0.96000
Epoch: 47, att_val: [0.845086   0.15491329]
Training: loss = 0.03062, acc = 0.99333 | Val: loss = 0.12003, acc = 0.96000
Epoch: 48, att_val: [0.81657386 0.18342534]
Training: loss = 0.02865, acc = 0.99333 | Val: loss = 0.11732, acc = 0.96000
WARNING:tensorflow:From /usr/local/lib/python3.7/site-packages/tensorflow/python/training/saver.py:1276: checkpoint_exists (from tensorflow.python.training.checkpoint_management) is deprecated and will be removed in a future version.
Epoch: 49, att_val: [0.80567586 0.19432533]
Instructions for updating:
Use standard file APIs to check for files with this prefix.
Training: loss = 0.02681, acc = 0.98833 | Val: loss = 0.11349, acc = 0.96333
load model from : pre_trained/acm/acm_allMP_multi_fea_.ckpt
{'__header__': b'MATLAB 5.0 MAT-file Platform: posix, Created on: Mon Oct 14 12:12:19 2019', '__version__': '1.0', '__globals__': [], 'PTP': array([[1., 1., 1., ..., 1., 1., 1.],
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
       [0., 0., 0., ..., 0., 0., 1.]]), 'feature': array([[ 1.        ,  1.        ,  1.        , ..., -0.41220528,
         1.11557233, -0.13434336],
       [ 0.        ,  1.        ,  0.        , ..., -0.62019664,
         1.71331906, -0.34187105],
       [ 0.        ,  1.        ,  0.        , ..., -0.53210109,
         1.15460432, -0.0266341 ],
       ...,
       [ 1.        ,  1.        ,  0.        , ..., -0.3828243 ,
         1.70376956, -0.59792721],
       [ 0.        ,  1.        ,  0.        , ..., -0.59153318,
         1.53599346, -0.31333208],
       [ 0.        ,  0.        ,  1.        , ..., -0.30756387,
         1.79605544, -0.71700424]]), 'label': array([[1., 0., 0.],
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
jhy_final_embedding (3025, 64) 
 [[-0.21418975 -0.37029955 -0.7517785  ... -0.41220528  1.1155723
  -0.13434336]
 [ 0.03663111 -0.20613432 -0.875585   ... -0.62019664  1.7133191
  -0.34187105]
 [-0.29575658 -0.35266235 -0.8107363  ... -0.5321011   1.1546043
  -0.0266341 ]
 ...
 [ 0.922876   -0.05874936 -0.78302246 ... -0.3828243   1.7037696
  -0.5979272 ]
 [ 0.00920407 -0.26600257 -0.83953273 ... -0.5915332   1.5359935
  -0.31333208]
 [ 1.0807267   0.2531212  -0.82620585 ... -0.30756387  1.7960554
  -0.71700424]]
Test loss: 0.3930906653404236 ; Test accuracy: 0.8809388875961304
start knn, kmean.....
xx: (2125, 64), yy: (2125, 3)
KNN(10avg, split:0.2, k=5) f1_macro: 0.8898, f1_micro: 0.8881
KNN(10avg, split:0.4, k=5) f1_macro: 0.8927, f1_micro: 0.8909
KNN(10avg, split:0.6, k=5) f1_macro: 0.8960, f1_micro: 0.8945
KNN(10avg, split:0.8, k=5) f1_macro: 0.8968, f1_micro: 0.8946
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
  FutureWarning)
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
  FutureWarning)
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
  FutureWarning)
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
  FutureWarning)
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
  FutureWarning)
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
  FutureWarning)
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
  FutureWarning)
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
  FutureWarning)
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
  FutureWarning)
/usr/local/lib/python3.7/site-packages/sklearn/metrics/cluster/supervised.py:859: FutureWarning: The behavior of NMI will change in version 0.22. To match the behavior of 'v_measure_score', NMI will use average_method='arithmetic' by default.
  FutureWarning)
NMI (10 avg): 0.6280 , ARI (10avg): 0.6647

Process finished with exit code 0
