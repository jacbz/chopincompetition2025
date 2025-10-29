# 2025 International Chopin Piano Competition - Results & Analysis

This document provides an analysis of the results from the [2025 Chopin Competition](https://en.wikipedia.org/wiki/XIX_International_Chopin_Piano_Competition). The raw data is sourced from the [official competition website](https://www.chopincompetition.pl/en/newsroom/19th-chopin-competition-judges-scores?id=144&type=news) and is available as a JSON file in this repository.

## Official Scoring System (CMEAN)

The competition results presented first are based on the official **CMEAN (Correction to the Mean)** score correction method. This system is designed to moderate extreme juror assessments and reduce the impact of outlier scores.

The process works as follows for each performance:
1.  An initial average score (mean) is calculated from the marks of all jurors.
2.  A predetermined deviation limit (e.g., *k* points) is set. In the Chopin Competition, *k* is 3 points in Stage I and 2 points in subsequent stages.
3.  Any individual juror's score that deviates from the initial average by more than *k* points is adjusted.
    -   Scores that are too high (e.g., `score > mean + k`) are lowered to `mean + k`.
    -   Scores that are too low (e.g., `score < mean - k`) are raised to `mean - k`.
4.  A final, "corrected" mean (`cmean`) is then calculated from these adjusted scores. This `cmean` is the official score for the performance.

While intended to ensure fairness, this method has been criticized for potentially distorting juror preferences and being susceptible to strategic manipulation. [A section later in this document](#jurors-score-transposition-jst-analysis) explores an alternative system (JST) and its impact on the competition's outcome.

## Prize Winners

| Prize | Name | Country | Age | Piano | Final Cumulative Score |
|:---|:---|:---|:---:|:---|:---:|
| **1st Prize** | Lu, Eric | United States | 27 | Fazioli | **22.43** |
| **2nd Prize** | Chen, Kevin | Canada | 20 | Steinway | **22.15** |
| **3rd Prize** | Wang, Zitong | China | 26 | Kawai | **21.45** |
| **4th Prize** | Kuwahara, Shiori | Japan | 29 | Steinway | **21.30** |
| **4th Prize** | Lyu, Tianyao | China | 16 | Fazioli | **21.30** |
| **5th Prize** | Alexewicz, Piotr | Poland | 25 | Kawai | **21.03** |
| **5th Prize** | Ong, Vincent | Malaysia | 24 | Kawai | **21.01** |
| **6th Prize** | Yang, William | United States | 24 | Steinway | **20.91** |
| | Khrikuli, David | Georgia | 24 | Steinway | **20.84** |
| | Li, Tianyou | China | 21 | Steinway | **20.72** |
| | Shindo, Miyu | Japan | 23 | Steinway | **20.63** |

## Stage-by-Stage Progression

### Stage 1

| Rank | Name | Country | Score (cmean) | Advancement |
|:---:|:---|:---|:---:|:---:|
| 1 | Chen, Kevin | Canada | 22.93 | ✔ |
| 2 | Guo, Eric | Canada | 22.78 | ✔ |
| 3 | Ong, Vincent | Malaysia | 22.07 | ✔ |
| 4 | Lyu, Tianyao | China | 22.06 | ✔ |
| 5 | Kuwahara, Shiori | Japan | 22.03 | ✔ |
| 6 | Shindo, Miyu | Japan | 21.92 | ✔ |
| 7 | Lu, Eric | United States | 21.82 | ✔ |
| 8 | Wu, Yifan | China | 21.47 | ✔ |
| 9 | Kałduński, Adam | Poland | 21.44 | ✔ |
| 10 | Rao, Hao | China | 21.27 | ✔ |
| 11 | Milstein, Nathalia | France | 21.26 | ✔ |
| 12 | Lee, Hyo | South Korea | 21.13 | ✔ |
| 13 | Lee, Hyuk | South Korea | 21.13 | ✔ |
| 14 | Ratinov, Anthony | United States | 21.06 | ✔ |
| 15 | Wang, Zitong | China | 21.03 | ✔ |
| 16 | Alexewicz, Piotr | Poland | 21.02 | ✔ |
| 17 | Lynov, Philipp | INP | 21.00 | ✔ |
| 18 | Pawlak, Piotr | Poland | 20.92 | ✔ |
| 19 | Li, Xiaoxuan | China | 20.88 | ✔ |
| 20 | Ushida, Tomoharu | Japan | 20.81 | ✔ |
| 21 | Zhang, Jacky | United Kingdom | 20.75 | ✔ |
| 22 | Prokopowicz, Yehuda | Poland | 20.73 | ✔ |
| 23 | Micieli, Ruben | Italy | 20.61 | ✔ |
| 24 | Jin, Zihan | China | 20.53 | ✔ |
| 25 | Khrikuli, David | Georgia | 20.52 | ✔ |
| 26 | Gao, Yang (Jack) | China | 20.51 | ✔ |
| 27 | Aumiller, Jonas | Germany | 20.46 | ✔ |
| 28 | Chen, Xuehong | China | 20.40 | ✔ |
| 29 | Bao, Yanyan | China | 20.35 | ✔ |
| 30 | Chen, Zixi | China | 20.25 | ✔ |
| 31 | Yang, William | United States | 20.22 | ✔ |
| 32 | Li, Zhexiang | China | 19.89 | ✔ |
| 33 | Lee, Kwanwook | South Korea | 19.87 | ✔ |
| 34 | Strata, Gabriele | Italy | 19.84 | ✔ |
| 35 | Nakagawa, Yumeka | Japan | 19.78 | ✔ |
| 36 | Deng, Yubo | China | 19.72 | ✔ |
| 37 | Li, Tianyou | China | 19.69 | ✔ |
| 38 | Yamagata, Miki | Japan | 19.61 | ✔ |
| 39 | Hu, Xiaoyu | China | 19.60 | ✔ |
| 40 | Chang, Kai-Min | Chinese Taipei | 19.59 | ✔ |
| 41 | Ma, Tiankun | China | 19.45 |  |
| 42 | Cheong, Hoi Leong | China | 19.39 |  |
| 43 | Nguyen, Viet Trung | Vietnam | 19.37 |  |
| 44 | Kyomasu, Shushi | Japan | 19.30 |  |
| 45 | Shimada, Jun | Japan | 19.25 |  |
| 46 | Dubiel, Mateusz | Poland | 19.12 |  |
| 47 | Krzyżowski, Mateusz | Poland | 19.03 |  |
| 48 | Li, Luwangzi | China | 19.03 |  |
| 49 | Hsieh, Wei-Ting | Chinese Taipei | 19.02 |  |
| 50 | Wierciński, Andrzej | Poland | 19.02 |  |
| 51 | Ferro, Alberto | Italy | 18.98 |  |
| 52 | Kobayashi, Kaito | Japan | 18.96 |  |
| 53 | Yang, Fanze | China | 18.95 |  |
| 54 | Shoji, Mana | Japan | 18.93 |  |
| 55 | Gong, Shuguang | China | 18.91 |  |
| 56 | Nishimoto, Yuya | Japan | 18.84 |  |
| 57 | Yu, Yichen | China | 18.79 |  |
| 58 | Cooper, Diana | France | 18.71 |  |
| 59 | Wu, Maiqi | China | 18.66 |  |
| 60 | Zhu, Hanyuan | China | 18.59 |  |
| 61 | Mao, Xuanyi | China | 18.56 |  |
| 62 | Ignatov, Hasan | Bulgaria | 18.51 |  |
| 63 | Widlarz, Jan | Poland | 18.50 |  |
| 64 | Yu, Yuewen | China | 18.46 |  |
| 65 | Tao, Ziye | China | 18.41 |  |
| 66 | Wierciński, Krzysztof | Poland | 18.40 |  |
| 67 | Yang, Yuanfan | United Kingdom | 18.38 |  |
| 68 | Zhu, Jingting | China | 18.33 |  |
| 69 | Wong, Victoria | United States | 18.29 |  |
| 70 | Strejcová, Eva | Czechia | 18.11 |  |
| 71 | Basista, Michał | Poland | 17.87 |  |
| 72 | Deng, Athena | Canada | 17.80 |  |
| 73 | Zenin, Andrey | INP | 17.78 |  |
| 74 | Sejbuk, Zuzanna | Poland | 17.72 |  |
| 75 | Fan, Yu-Ang | China | 17.71 |  |
| 76 | Kłeczek, Antoni | United States | 17.64 |  |
| 77 | Onoda, Arisa | Japan | 17.63 |  |
| 78 | Nakashima, Yulia | Japan | 17.56 |  |
| 79 | Yamazaki, Ryota | Japan | 17.54 |  |
| 80 | Zhong, Yonghuan | China | 17.33 |  |
| 81 | Lin, Hao-Wei | Chinese Taipei | 17.22 |  |
| 82 | Wang, Ryan | Canada | 17.07 |  |
| 83 | U, Chun Lam | Hong Kong | 15.79 |  |
| 84 | López Salas, Pedro | Spain | 15.33 |  |

### Stage 2

| Rank | Name | Country | Score (cmean) | Cumulative Score | Advancement |
|:---:|:---|:---|:---:|:---:|:---:|
| 1 | Lu, Eric | United States | 23.03 | **22.67** | ✔ |
| 2 | Chen, Kevin | Canada | 22.41 | **22.57** | ✔ |
| 3 | Yang, William | United States | 22.38 | **21.73** | ✔ |
| 4 | Kuwahara, Shiori | Japan | 21.28 | **21.51** | ✔ |
| 5 | Ong, Vincent | Malaysia | 21.23 | **21.48** | ✔ |
| 6 | Li, Tianyou | China | 21.86 | **21.21** | ✔ |
| 7 | Lyu, Tianyao | China | 20.78 | **21.16** | ✔ |
| 8 | Shindo, Miyu | Japan | 20.82 | **21.15** | ✔ |
| 9 | Khrikuli, David | Georgia | 21.35 | **21.10** | ✔ |
| 10 | Alexewicz, Piotr | Poland | 21.08 | **21.06** | ✔ |
| 11 | Guo, Eric | Canada | 20.32 | **21.06** | ✔ |
| 12 | Ushida, Tomoharu | Japan | 21.08 | **21.00** | ✔ |
| 13 | Gao, Yang (Jack) | China | 21.18 | **20.98** | ✔ |
| 14 | Lee, Hyo | South Korea | 20.79 | **20.89** | ✔ |
| 15 | Lee, Hyuk | South Korea | 20.79 | **20.89** | ✔ |
| 16 | Wang, Zitong | China | 20.69 | **20.79** | ✔ |
| 17 | Pawlak, Piotr | Poland | 20.59 | **20.69** | ✔ |
| 18 | Wu, Yifan | China | 20.32 | **20.66** | ✔ |
| 19 | Li, Xiaoxuan | China | 20.30 | **20.47** | ✔ |
| 20 | Prokopowicz, Yehuda | Poland | 20.36 | **20.47** | ✔ |
| 21 | Ratinov, Anthony | United States | 20.13 | **20.41** |  |
| 22 | Strata, Gabriele | Italy | 20.63 | **20.39** |  |
| 23 | Chang, Kai-Min | Chinese Taipei | 20.52 | **20.24** |  |
| 24 | Kałduński, Adam | Poland | 19.72 | **20.24** |  |
| 25 | Yamagata, Miki | Japan | 20.35 | **20.13** |  |
| 26 | Chen, Xuehong | China | 19.90 | **20.05** |  |
| 27 | Aumiller, Jonas | Germany | 19.81 | **20.00** |  |
| 28 | Nakagawa, Yumeka | Japan | 19.98 | **19.92** |  |
| 29 | Milstein, Nathalia | France | 19.26 | **19.86** |  |
| 30 | Rao, Hao | China | 19.15 | **19.79** |  |
| 31 | Chen, Zixi | China | 19.29 | **19.58** |  |
| 32 | Micieli, Ruben | Italy | 19.12 | **19.57** |  |
| 33 | Jin, Zihan | China | 19.14 | **19.56** |  |
| 34 | Lynov, Philipp | INP | 18.71 | **19.40** |  |
| 35 | Zhang, Jacky | United Kingdom | 18.80 | **19.39** |  |
| 36 | Li, Zhexiang | China | 19.08 | **19.32** |  |
| 37 | Bao, Yanyan | China | 18.82 | **19.28** |  |
| 38 | Deng, Yubo | China | 19.09 | **19.28** |  |
| 39 | Lee, Kwanwook | South Korea | 18.72 | **19.06** |  |
| 40 | Hu, Xiaoyu | China | 18.81 | **19.05** |  |

### Stage 3

| Rank | Name | Country | Score (cmean) | Cumulative Score | Advancement |
|:---:|:---|:---|:---:|:---:|:---:|
| 1 | Lu, Eric | United States | 23.29 | **23.09** | ✔ |
| 2 | Chen, Kevin | Canada | 22.36 | **22.43** | ✔ |
| 3 | Wang, Zitong | China | 22.80 | **22.20** | ✔ |
| 4 | Li, Tianyou | China | 21.98 | **21.73** | ✔ |
| 5 | Kuwahara, Shiori | Japan | 21.36 | **21.41** | ✔ |
| 6 | Lyu, Tianyao | China | 21.43 | **21.36** | ✔ |
| 7 | Shindo, Miyu | Japan | 21.06 | **21.10** | ✔ |
| 8 | Yang, William | United States | 20.69 | **20.98** | ✔ |
| 9 | Khrikuli, David | Georgia | 20.77 | **20.86** | ✔ |
| 10 | Alexewicz, Piotr | Poland | 20.74 | **20.84** | ✔ |
| 11 | Ong, Vincent | Malaysia | 20.55 | **20.84** | ✔ |
| 12 | Lee, Hyo | South Korea | 20.79 | **20.82** |  |
| 13 | Ushida, Tomoharu | Japan | 20.58 | **20.70** |  |
| 14 | Lee, Hyuk | South Korea | 20.03 | **20.29** |  |
| 15 | Gao, Yang (Jack) | China | 19.88 | **20.20** |  |
| 16 | Wu, Yifan | China | 19.80 | **20.07** |  |
| 17 | Li, Xiaoxuan | China | 19.85 | **20.04** |  |
| 18 | Guo, Eric | Canada | 19.54 | **20.02** |  |
| 19 | Prokopowicz, Yehuda | Poland | 19.49 | **19.79** |  |
| 20 | Pawlak, Piotr | Poland | 19.31 | **19.73** |  |

## Juror Agreement and Disagreement Analysis

### Stage 1 Agreement

#### Most Contentious Performances (Highest Score Variance)

| Rank | Pianist | Mean Score | Score Std. Dev. |
|:---:|:---|:---:|:---:|
| 1 | Hu, Xiaoyu | 19.60 | 3.71 |
| 2 | López Salas, Pedro | 15.33 | 3.56 |
| 3 | Pawlak, Piotr | 20.92 | 3.50 |
| 4 | Ong, Vincent | 22.07 | 3.47 |
| 5 | Lin, Hao-Wei | 17.22 | 3.17 |
| 6 | Fan, Yu-Ang | 17.71 | 3.01 |
| 7 | Zenin, Andrey | 17.78 | 3.00 |
| 8 | Kałduński, Adam | 21.44 | 3.00 |
| 9 | Zhang, Jacky | 20.75 | 2.97 |
| 10 | Bao, Yanyan | 20.35 | 2.97 |
| 11 | Zhu, Hanyuan | 18.59 | 2.97 |
| 12 | Krzyżowski, Mateusz | 19.03 | 2.96 |
| 13 | Yang, Fanze | 18.95 | 2.95 |
| 14 | Strejcová, Eva | 18.11 | 2.89 |
| 15 | Mao, Xuanyi | 18.56 | 2.88 |
| 16 | Rao, Hao | 21.27 | 2.85 |
| 17 | Hsieh, Wei-Ting | 19.02 | 2.81 |
| 18 | Yu, Yuewen | 18.46 | 2.80 |
| 19 | Nishimoto, Yuya | 18.84 | 2.77 |
| 20 | Kuwahara, Shiori | 22.03 | 2.72 |

#### Most Unanimous Performances (Lowest Score Variance)

| Rank | Pianist | Mean Score | Score Std. Dev. |
|:---:|:---|:---:|:---:|
| 1 | Jin, Zihan | 20.53 | 1.46 |
| 2 | Wu, Maiqi | 18.66 | 1.54 |
| 3 | Wang, Ryan | 17.07 | 1.57 |
| 4 | Wong, Victoria | 18.29 | 1.61 |
| 5 | Widlarz, Jan | 18.50 | 1.66 |
| 6 | Lynov, Philipp | 21.00 | 1.68 |
| 7 | Yang, Yuanfan | 18.38 | 1.68 |
| 8 | Zhu, Jingting | 18.33 | 1.69 |
| 9 | Nakashima, Yulia | 17.56 | 1.72 |
| 10 | Wu, Yifan | 21.47 | 1.72 |
| 11 | Lee, Kwanwook | 19.87 | 1.81 |
| 12 | Shindo, Miyu | 21.92 | 1.82 |
| 13 | Chen, Zixi | 20.25 | 1.83 |
| 14 | Shimada, Jun | 19.25 | 1.83 |
| 15 | Chen, Xuehong | 20.40 | 1.85 |
| 16 | Chen, Kevin | 22.93 | 1.85 |
| 17 | Dubiel, Mateusz | 19.12 | 1.86 |
| 18 | Lee, Hyuk | 21.13 | 1.89 |
| 19 | Yang, William | 20.22 | 1.89 |
| 20 | Lee, Hyo | 21.13 | 1.92 |

### Stage 2 Agreement

#### Most Contentious Performances (Highest Score Variance)

| Rank | Pianist | Mean Score | Score Std. Dev. |
|:---:|:---|:---:|:---:|
| 1 | Khrikuli, David | 21.35 | 3.22 |
| 2 | Gao, Yang (Jack) | 21.18 | 2.89 |
| 3 | Strata, Gabriele | 20.63 | 2.72 |
| 4 | Yang, William | 22.38 | 2.72 |
| 5 | Ong, Vincent | 21.23 | 2.56 |
| 6 | Wang, Zitong | 20.69 | 2.47 |
| 7 | Deng, Yubo | 19.09 | 2.33 |
| 8 | Micieli, Ruben | 19.12 | 2.32 |
| 9 | Nakagawa, Yumeka | 19.98 | 2.31 |
| 10 | Yamagata, Miki | 20.35 | 2.29 |
| 11 | Rao, Hao | 19.15 | 2.27 |
| 12 | Li, Zhexiang | 19.08 | 2.26 |
| 13 | Pawlak, Piotr | 20.59 | 2.25 |
| 14 | Chen, Zixi | 19.29 | 2.16 |
| 15 | Milstein, Nathalia | 19.26 | 2.15 |
| 16 | Kuwahara, Shiori | 21.28 | 2.14 |
| 17 | Jin, Zihan | 19.14 | 2.10 |
| 18 | Lyu, Tianyao | 20.78 | 2.09 |
| 19 | Lynov, Philipp | 18.71 | 2.09 |
| 20 | Li, Xiaoxuan | 20.30 | 2.05 |

#### Most Unanimous Performances (Lowest Score Variance)

| Rank | Pianist | Mean Score | Score Std. Dev. |
|:---:|:---|:---:|:---:|
| 1 | Lee, Hyo | 20.79 | 1.29 |
| 2 | Zhang, Jacky | 18.80 | 1.53 |
| 3 | Ratinov, Anthony | 20.13 | 1.54 |
| 4 | Chang, Kai-Min | 20.52 | 1.58 |
| 5 | Lee, Kwanwook | 18.72 | 1.69 |
| 6 | Chen, Kevin | 22.41 | 1.70 |
| 7 | Kałduński, Adam | 19.72 | 1.73 |
| 8 | Hu, Xiaoyu | 18.81 | 1.73 |
| 9 | Chen, Xuehong | 19.90 | 1.78 |
| 10 | Lee, Hyuk | 20.79 | 1.80 |
| 11 | Aumiller, Jonas | 19.81 | 1.80 |
| 12 | Li, Tianyou | 21.86 | 1.81 |
| 13 | Alexewicz, Piotr | 21.08 | 1.81 |
| 14 | Lu, Eric | 23.03 | 1.82 |
| 15 | Guo, Eric | 20.32 | 1.91 |
| 16 | Shindo, Miyu | 20.82 | 1.93 |
| 17 | Bao, Yanyan | 18.82 | 1.94 |
| 18 | Ushida, Tomoharu | 21.08 | 1.94 |
| 19 | Wu, Yifan | 20.32 | 1.97 |
| 20 | Prokopowicz, Yehuda | 20.36 | 2.02 |

### Stage 3 Agreement

#### Most Contentious Performances (Highest Score Variance)

| Rank | Pianist | Mean Score | Score Std. Dev. |
|:---:|:---|:---:|:---:|
| 1 | Khrikuli, David | 20.77 | 2.68 |
| 2 | Pawlak, Piotr | 19.31 | 2.48 |
| 3 | Gao, Yang (Jack) | 19.88 | 2.40 |
| 4 | Chen, Kevin | 22.36 | 2.07 |
| 5 | Guo, Eric | 19.54 | 2.05 |
| 6 | Kuwahara, Shiori | 21.36 | 1.90 |
| 7 | Ong, Vincent | 20.55 | 1.88 |
| 8 | Wang, Zitong | 22.80 | 1.87 |
| 9 | Prokopowicz, Yehuda | 19.49 | 1.81 |
| 10 | Yang, William | 20.69 | 1.81 |
| 11 | Alexewicz, Piotr | 20.74 | 1.80 |
| 12 | Wu, Yifan | 19.80 | 1.71 |
| 13 | Lee, Hyuk | 20.03 | 1.65 |
| 14 | Lyu, Tianyao | 21.43 | 1.65 |
| 15 | Li, Tianyou | 21.98 | 1.47 |
| 16 | Lee, Hyo | 20.79 | 1.42 |
| 17 | Lu, Eric | 23.29 | 1.38 |
| 18 | Li, Xiaoxuan | 19.85 | 1.27 |
| 19 | Shindo, Miyu | 21.06 | 1.26 |
| 20 | Ushida, Tomoharu | 20.58 | 1.17 |

### Final Agreement

#### Most Contentious Performances (Highest Score Variance)

| Rank | Pianist | Mean Score | Score Std. Dev. |
|:---:|:---|:---:|:---:|
| 1 | Ong, Vincent | 21.04 | 2.58 |
| 2 | Lyu, Tianyao | 21.25 | 2.42 |
| 3 | Khrikuli, David | 20.72 | 2.40 |
| 4 | Kuwahara, Shiori | 21.04 | 2.23 |
| 5 | Yang, William | 20.48 | 2.18 |
| 6 | Alexewicz, Piotr | 21.30 | 1.93 |
| 7 | Wang, Zitong | 20.64 | 1.79 |
| 8 | Chen, Kevin | 21.58 | 1.78 |
| 9 | Li, Tianyou | 19.09 | 1.76 |
| 10 | Lu, Eric | 21.41 | 1.75 |
| 11 | Shindo, Miyu | 19.72 | 1.50 |

## Rank Volatility Analysis

### Largest Rank Improvements (Based on Stage-Wise Rank)

| Pianist | Stage Transition | Rank Change | From Rank | To Rank |
|:---|:---|:---:|:---:|:---:|
| Li, Tianyou | I → II | +33 | 37 | 4 |
| Yang, William | I → II | +28 | 31 | 3 |
| Chang, Kai-Min | I → II | +22 | 40 | 18 |
| Khrikuli, David | I → II | +20 | 25 | 5 |
| Gao, Yang (Jack) | I → II | +18 | 26 | 8 |
| Strata, Gabriele | I → II | +18 | 34 | 16 |
| Yamagata, Miki | I → II | +18 | 38 | 20 |
| Wang, Zitong | II → III | +13 | 15 | 2 |
| Ushida, Tomoharu | I → II | +10 | 20 | 10 |
| Nakagawa, Yumeka | I → II | +10 | 35 | 25 |
| Lyu, Tianyao | II → III | +9 | 14 | 5 |
| Ong, Vincent | III → Final | +7 | 13 | 6 |
| Alexewicz, Piotr | I → II | +7 | 16 | 9 |
| Alexewicz, Piotr | III → Final | +7 | 10 | 3 |
| Li, Xiaoxuan | II → III | +7 | 23 | 16 |
| Lu, Eric | I → II | +6 | 7 | 1 |
| Wu, Yifan | II → III | +5 | 22 | 17 |

## Performance by Piano Brand

| Piano Brand | Avg. Stage I | Avg. Stage II | Avg. Stage III | Avg. Final |
|:---|:---:|:---:|:---:|:---:|
| Bechstein | 18.50 |  |  |  |
| Fazioli | 19.27 | 20.59 | 22.36 | 21.33 |
| Kawai | 19.63 | 20.38 | 20.68 | 20.99 |
| Steinway | 19.67 | 20.27 | 20.63 | 20.44 |
| Yamaha | 19.02 | 18.72 |  |  |

## Juror Scoring Analysis

### Stage 1 Juror Statistics

| Juror | Scores Given | Mean | Std. Dev. | Min Score (Pianist) | Max Score (Pianist) |
|:---|:---:|:---:|:---:|:---|:---|
| Krzysztof Jabłoński | 84 | 17.32 | 2.66 | 12 (Kobayashi, Pawlak, Zenin) | 24 (Chen, Lyu, Ong) |
| John Allison | 84 | 17.35 | 3.27 | 9 (López Salas) | 24 (Pawlak) |
| Nelson Goerner | 84 | 18.77 | 3.06 | 12 (López Salas) | 25 (Guo, Kuwahara, Milstein, Rao) |
| Wojciech Świtała | 81 | 18.78 | 2.65 | 12 (López Salas, U) | 25 (Chen) |
| Dang Thai Son | 74 | 18.80 | 2.61 | 14 (López Salas) | 24 (Hu, Khrikuli, Ong, Strata) |
| Garrick Ohlsson | 84 | 18.98 | 3.38 | 8 (López Salas) | 24 (Gao, Hu, Kyomasu, Milstein, Pawlak, Prokopowicz) |
| John Rink | 84 | 19.05 | 2.79 | 13 (Kłeczek, López Salas) | 25 (Guo) |
| Kevin Kenner | 81 | 19.33 | 2.54 | 15 (Ferro, Kłeczek, Nakashima, Pawlak, U, Wierciński, Zenin) | 25 (Ong) |
| Ewa Pobłocka | 80 | 19.44 | 2.81 | 14 (Nakashima) | 24 (Hu, Kuwahara, Li, Lyu, Ratinov, Zhang) |
| Michel Béroff | 84 | 19.56 | 2.92 | 15 (Strata, Strejcová, Zhong, Zhu) | 25 (Chen, Lee, Ma, Zhang) |
| Robert McDonald | 78 | 19.82 | 2.53 | 15 (Wang) | 24 (Chen, Fan, Nakagawa, Ong, Ushida, Zhang) |
| Katarzyna Popowa-Zydroń | 79 | 19.91 | 2.25 | 15 (López Salas, Mao) | 24 (Chang, Gao, Hu, Rao, Yu) |
| Piotr Paleczny | 82 | 20.02 | 2.22 | 16 (U, Wang) | 25 (Rao) |
| Momo Kodama | 84 | 20.38 | 2.08 | 17 (Deng, Krzyżowski, Mao, U, Wang) | 25 (Guo) |
| Akiko Ebi | 84 | 20.73 | 2.49 | 16 (Fan, López Salas, U) | 25 (Chen, Kałduński) |
| Yulianna Avdeeva | 84 | 20.82 | 1.85 | 18 (Kłeczek, Onoda, U, Yamagata, Yang, Yu, Zhong, Zhu) | 25 (Hu, Kuwahara, Pawlak) |
| Sa Chen | 84 | 21.52 | 1.35 | 17 (U) | 24 (Chen, Kuwahara, Li, Li, Li, Micieli, Ong, Prokopowicz, Zhang) |

### Stage 2 Juror Statistics

| Juror | Scores Given | Mean | Std. Dev. | Min Score (Pianist) | Max Score (Pianist) |
|:---|:---:|:---:|:---:|:---|:---|
| Krzysztof Jabłoński | 40 | 18.45 | 2.12 | 16 (Li, Milstein, Prokopowicz, Wang, Zhang) | 24 (Chen, Li, Ushida) |
| Katarzyna Popowa-Zydroń | 38 | 19.03 | 2.05 | 15 (Nakagawa) | 24 (Yang) |
| Dang Thai Son | 36 | 19.33 | 2.07 | 17 (Bao, Chen, Milstein, Prokopowicz, Rao, Wu, Yamagata) | 24 (Ong, Yang) |
| John Allison | 40 | 19.55 | 2.37 | 15 (Deng) | 24 (Khrikuli) |
| Wojciech Świtała | 40 | 19.77 | 1.99 | 16 (Deng) | 24 (Chen) |
| Ewa Pobłocka | 38 | 19.82 | 3.32 | 12 (Khrikuli) | 25 (Lu, Yang) |
| Garrick Ohlsson | 40 | 20.05 | 2.38 | 16 (Rao, Strata) | 25 (Gao, Pawlak) |
| Piotr Paleczny | 39 | 20.15 | 2.07 | 16 (Gao, Jin) | 25 (Lyu) |
| Robert McDonald | 36 | 20.19 | 1.81 | 16 (Kuwahara) | 24 (Lee) |
| Momo Kodama | 40 | 20.43 | 2.42 | 16 (Bao, Jin) | 25 (Ong) |
| John Rink | 40 | 20.45 | 2.27 | 16 (Deng) | 25 (Lu, Yang) |
| Kevin Kenner | 40 | 20.45 | 2.01 | 17 (Alexewicz, Aumiller, Deng, Lynov, Strata) | 24 (Chen, Wang, Yang) |
| Nelson Goerner | 40 | 20.85 | 2.35 | 16 (Yang) | 25 (Lu, Strata) |
| Akiko Ebi | 40 | 20.98 | 2.41 | 17 (Hu, Jin, Lynov, Micieli, Rao) | 24 (Lu, Nakagawa, Strata, Yang) |
| Yulianna Avdeeva | 40 | 21.35 | 1.17 | 20 (Chang, Deng, Gao, Jin, Lee, Lee, Lyu, Milstein, Nakagawa, Ong, Shindo, Yang, Zhang) | 24 (Ushida) |
| Michel Béroff | 40 | 21.48 | 2.05 | 18 (Hu, Jin, Lynov, Strata) | 25 (Lee, Ushida) |
| Sa Chen | 40 | 21.50 | 1.28 | 19 (Pawlak) | 24 (Chen, Gao, Li, Yang) |

### Stage 3 Juror Statistics

| Juror | Scores Given | Mean | Std. Dev. | Min Score (Pianist) | Max Score (Pianist) |
|:---|:---:|:---:|:---:|:---|:---|
| Dang Thai Son | 18 | 19.50 | 1.61 | 17 (Gao, Wu) | 23 (Chen) |
| Ewa Pobłocka | 18 | 19.67 | 2.77 | 14 (Khrikuli) | 24 (Lu, Wang) |
| Garrick Ohlsson | 20 | 20.20 | 2.60 | 16 (Chen) | 25 (Gao) |
| Robert McDonald | 17 | 20.24 | 1.80 | 17 (Ong) | 23 (Chen, Ushida) |
| Krzysztof Jabłoński | 20 | 20.25 | 1.87 | 17 (Gao) | 25 (Chen) |
| Katarzyna Popowa-Zydroń | 19 | 20.47 | 1.93 | 17 (Pawlak) | 24 (Yang) |
| Sa Chen | 20 | 20.50 | 1.63 | 17 (Pawlak) | 24 (Li) |
| Piotr Paleczny | 19 | 20.74 | 1.48 | 18 (Gao) | 23 (Chen, Lyu, Shindo) |
| John Allison | 20 | 20.80 | 2.09 | 18 (Guo, Lee, Ong) | 24 (Khrikuli, Li, Lu, Pawlak) |
| Yulianna Avdeeva | 20 | 21.00 | 1.00 | 20 (Gao, Lee, Li, Lu, Ong, Pawlak, Shindo, Wu, Yang) | 23 (Li) |
| Kevin Kenner | 20 | 21.00 | 2.30 | 17 (Kuwahara, Pawlak) | 25 (Wang) |
| Akiko Ebi | 20 | 21.05 | 2.50 | 16 (Gao, Khrikuli) | 25 (Lu) |
| Wojciech Świtała | 20 | 21.05 | 1.53 | 19 (Li, Ong, Pawlak, Prokopowicz) | 24 (Lu) |
| John Rink | 20 | 21.20 | 2.20 | 18 (Li, Pawlak) | 25 (Gao, Wang) |
| Nelson Goerner | 20 | 21.65 | 1.93 | 18 (Yang) | 25 (Lu) |
| Momo Kodama | 20 | 21.70 | 1.58 | 20 (Gao, Lee, Lee, Li, Li, Pawlak, Shindo, Ushida) | 24 (Guo, Lu, Ong) |
| Michel Béroff | 20 | 22.15 | 1.88 | 18 (Prokopowicz) | 25 (Wang) |

### Final Juror Statistics

| Juror | Scores Given | Mean | Std. Dev. | Min Score (Pianist) | Max Score (Pianist) |
|:---|:---:|:---:|:---:|:---|:---|
| Yulianna Avdeeva | 11 | 17.82 | 1.75 | 15 (Shindo) | 21 (Chen) |
| Garrick Ohlsson | 11 | 18.64 | 0.88 | 17 (Khrikuli, Lyu) | 20 (Lu) |
| Ewa Pobłocka | 11 | 19.82 | 2.33 | 16 (Li) | 24 (Lyu) |
| Akiko Ebi | 11 | 20.45 | 2.15 | 17 (Li) | 25 (Alexewicz) |
| Katarzyna Popowa-Zydroń | 10 | 20.50 | 1.91 | 17 (Ong) | 23 (Kuwahara, Yang) |
| Wojciech Świtała | 11 | 20.64 | 1.43 | 19 (Khrikuli, Ong, Wang) | 23 (Alexewicz, Chen) |
| Dang Thai Son | 9 | 20.67 | 1.63 | 19 (Kuwahara, Li) | 24 (Ong) |
| Kevin Kenner | 11 | 20.73 | 2.26 | 16 (Kuwahara) | 24 (Lyu) |
| Robert McDonald | 9 | 20.78 | 1.31 | 19 (Li, Shindo) | 23 (Kuwahara) |
| Sa Chen | 11 | 20.82 | 2.33 | 18 (Lyu, Wang) | 24 (Chen, Li, Ong) |
| Krzysztof Jabłoński | 11 | 21.09 | 1.83 | 19 (Alexewicz, Li, Wang) | 24 (Chen, Lyu) |
| Piotr Paleczny | 11 | 21.18 | 1.95 | 18 (Li, Ong) | 24 (Lyu) |
| John Rink | 11 | 21.27 | 1.60 | 19 (Lyu, Shindo) | 24 (Lu) |
| John Allison | 11 | 21.55 | 2.23 | 18 (Ong) | 25 (Khrikuli, Wang) |
| Nelson Goerner | 11 | 21.82 | 2.29 | 17 (Yang) | 25 (Ong) |
| Momo Kodama | 11 | 22.00 | 1.60 | 20 (Li, Lyu, Shindo) | 25 (Ong) |
| Michel Béroff | 11 | 22.45 | 1.50 | 21 (Khrikuli, Li, Wang, Yang) | 25 (Chen, Lu) |

## Bias Analysis

This analysis measures how much a juror's score for a pianist deviates from the average score of all other jurors for that same performance. A positive 'Net Bias' suggests a tendency to score compatriots higher than their colleagues do, relative to their scoring of non-compatriots.

| Juror | Country | Avg. Deviation (Compatriot) | Avg. Deviation (Other) | Net Bias |
|:---|:---|:---:|:---:|:---:|
| Piotr Paleczny | Poland | +1.78 | +0.13 | **+1.66** |
| Momo Kodama | Japan | +1.77 | +0.64 | **+1.13** |
| John Rink | United States | +0.85 | -0.16 | **+1.00** |
| Robert McDonald | United States | +1.15 | +0.20 | **+0.95** |
| Garrick Ohlsson | United States | +0.22 | -0.63 | **+0.86** |
| Michel Béroff | France | +1.46 | +0.70 | **+0.76** |
| Wojciech Świtała | Poland | +0.11 | -0.59 | **+0.70** |
| Akiko Ebi | Japan | +1.40 | +0.87 | **+0.53** |
| Sa Chen | China | +1.64 | +1.44 | **+0.19** |
| Kevin Kenner | United States | +0.18 | -0.01 | **+0.18** |
| Katarzyna Popowa-Zydroń | Poland | -0.53 | -0.06 | **-0.47** |
| Dang Thai Son | Vietnam / Canada | -1.94 | -0.73 | **-1.21** |
| Ewa Pobłocka | Poland | -1.52 | -0.16 | **-1.36** |
| Krzysztof Jabłoński | Poland | -3.65 | -1.51 | **-2.14** |

## Student Analysis

Jurors recuse themselves from scoring their students. This section aggregates the performance of these students to provide insight into the jurors as teachers.

| Teacher (Juror) | No. of Students | Student Names | Avg. Score S1 | Avg. Score S2 | Avg. Score S3 | Avg. Score S4 |
|:---|:---:|:---|:---|:---:|:---:|:---:|
| Wojciech Świtała | 3 | Nishimoto, Wierciński, Zhong | 18.40 |  |  |  |
| Kevin Kenner | 2 | Gong, Wong | 18.60 |  |  |  |
| Dang Thai Son | 10 | Chang, Deng, Deng, Lu, Nguyen, Onoda, Tao, U, Wang, Zhu | 18.98 | 20.83 | 23.05 | 21.02 |
| Ewa Pobłocka | 4 | Kłeczek, Lee, Lee, Wu | 19.64 | 20.79 | 20.41 |  |
| Robert McDonald | 5 | Cheong, Li, Ratinov, Yang, Zhu | 19.98 | 20.94 | 20.27 | 20.48 |
| Katarzyna Popowa-Zydroń | 4 | Kałduński, Lyu, Shoji, Widlarz | 20.23 | 20.25 | 21.43 | 21.25 |
| Piotr Paleczny | 1 | Ushida | 20.81 | 21.08 | 20.58 |  |

## Jurors’ Score Transposition (JST) Analysis

This section presents an alternative set of results based on the **Jurors’ Score Transposition (JST)** method, a newer system designed to address the shortcomings of CMEAN. This analysis is based on the research paper [*"The 'Proven' vs. the 'Unproven': A Comparative Analysis of Score Correction Methods in Classical Music Competitions"*](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5143593) by K. Kontek & K. Kenner (2025).

### Shortcomings of CMEAN and the JST Alternative

The paper argues that the official CMEAN method, while intended to curb extreme scores, has several critical flaws:
-   **Ranking inconsistencies:** It can alter rankings in unpredictable ways based on the variance of juror scores, not just their average.
-   **Preference reversal:** It can produce final rankings that contradict the collective preference of the jury.
-   **Susceptibility to manipulation:** The system can be "gamed" by jurors who understand its mechanics.

The **JST method** offers a more robust solution by normalizing each juror's scores. It transforms every juror's set of marks so that they all share the same mean and the same spread (range from min to max score), while perfectly preserving each juror's individual ranking of the pianists. This process ensures that all jurors have an equal "voice," regardless of whether they tend to give high, low, or wide-ranging scores.

The following tables show how the competition results would change if JST were applied instead of CMEAN.

> [!NOTE]
> Overall, the differences are relatively minor. In a win for Bechstein, Tiankun Ma would have advanced to Stage II instead of Miki Yamagata, and Vincent Ong would not have advanced to the Final round. The difference between prizewinner Eric Lu and runner-up Kevin Chen is significantly reduced under JST, to just 0.07 points.

### JST Stage I Results (Advancing to Stage II)

| Rank (JST) | Name | Country | Score (JST) | CMEAN Adv. |
|:---:|:---|:---|:---:|:---:|
| 1 | Chen, Kevin | Canada | 22.85 | ✔ |
| 2 | Guo, Eric | Canada | 22.70 | ✔ |
| 3 | Lyu, Tianyao | China | 22.07 | ✔ |
| 4 | Kuwahara, Shiori | Japan | 21.96 | ✔ |
| 5 | Shindo, Miyu | Japan | 21.94 | ✔ |
| 6 | Ong, Vincent | Malaysia | 21.77 | ✔ |
| 7 | Lu, Eric | United States | 21.71 | ✔ |
| 8 | Wu, Yifan | China | 21.39 | ✔ |
| 9 | Rao, Hao | China | 21.25 | ✔ |
| 10 | Kałduński, Adam | Poland | 21.23 | ✔ |
| 11 | Lynov, Philipp | INP | 21.08 | ✔ |
| 12 | Ratinov, Anthony | United States | 21.03 | ✔ |
| 13 | Milstein, Nathalia | France | 21.01 | ✔ |
| 14 | Lee, Hyo | South Korea | 20.95 | ✔ |
| 15 | Lee, Hyuk | South Korea | 20.93 | ✔ |
| 16 | Alexewicz, Piotr | Poland | 20.89 | ✔ |
| 17 | Ushida, Tomoharu | Japan | 20.88 | ✔ |
| 18 | Zhang, Jacky | United Kingdom | 20.82 | ✔ |
| 19 | Li, Xiaoxuan | China | 20.79 | ✔ |
| 20 | Wang, Zitong | China | 20.73 | ✔ |
| 21 | Prokopowicz, Yehuda | Poland | 20.61 | ✔ |
| 22 | Pawlak, Piotr | Poland | 20.54 | ✔ |
| 23 | Micieli, Ruben | Italy | 20.51 | ✔ |
| 24 | Khrikuli, David | Georgia | 20.38 | ✔ |
| 25 | Chen, Xuehong | China | 20.38 | ✔ |
| 26 | Aumiller, Jonas | Germany | 20.37 | ✔ |
| 27 | Jin, Zihan | China | 20.36 | ✔ |
| 28 | Gao, Yang (Jack) | China | 20.26 | ✔ |
| 29 | Chen, Zixi | China | 20.17 | ✔ |
| 30 | Bao, Yanyan | China | 20.13 | ✔ |
| 31 | Nakagawa, Yumeka | Japan | 20.09 | ✔ |
| 32 | Yang, William | United States | 19.93 | ✔ |
| 33 | Hu, Xiaoyu | China | 19.83 | ✔ |
| 34 | Li, Zhexiang | China | 19.82 | ✔ |
| 35 | Lee, Kwanwook | South Korea | 19.82 | ✔ |
| 36 | **Ma, Tiankun** | China | 19.77 |  |
| 37 | Li, Tianyou | China | 19.77 | ✔ |
| 38 | Strata, Gabriele | Italy | 19.59 | ✔ |
| 39 | Chang, Kai-Min | Chinese Taipei | 19.59 | ✔ |
| 40 | Deng, Yubo | China | 19.54 | ✔ |
|(cutoff)|
| 41 | **Yamagata, Miki** | Japan | 19.47 | ✔ |
| 42 | Shimada, Jun | Japan | 19.28 |  |
| 43 | Nguyen, Viet Trung | Vietnam | 19.26 |  |
| 44 | Cheong, Hoi Leong | China | 19.23 |  |
| 45 | Li, Luwangzi | China | 19.18 |  |
| 46 | Kyomasu, Shushi | Japan | 19.15 |  |
| 47 | Wierciński, Andrzej | Poland | 19.04 |  |
| 48 | Krzyżowski, Mateusz | Poland | 18.99 |  |
| 49 | Hsieh, Wei-Ting | Chinese Taipei | 18.96 |  |
| 50 | Shoji, Mana | Japan | 18.96 |  |
| 51 | Ferro, Alberto | Italy | 18.93 |  |
| 52 | Dubiel, Mateusz | Poland | 18.90 |  |
| 53 | Zhu, Hanyuan | China | 18.89 |  |
| 54 | Nishimoto, Yuya | Japan | 18.86 |  |
| 55 | Yang, Fanze | China | 18.83 |  |
| 56 | Gong, Shuguang | China | 18.78 |  |
| 57 | Kobayashi, Kaito | Japan | 18.72 |  |
| 58 | Yu, Yichen | China | 18.61 |  |
| 59 | Mao, Xuanyi | China | 18.61 |  |
| 60 | Yu, Yuewen | China | 18.58 |  |
| 61 | Cooper, Diana | France | 18.54 |  |
| 62 | Ignatov, Hasan | Bulgaria | 18.49 |  |
| 63 | Wu, Maiqi | China | 18.45 |  |
| 64 | Widlarz, Jan | Poland | 18.44 |  |
| 65 | Tao, Ziye | China | 18.38 |  |
| 66 | Wierciński, Krzysztof | Poland | 18.36 |  |
| 67 | Wong, Victoria | United States | 18.25 |  |
| 68 | Zhu, Jingting | China | 18.24 |  |
| 69 | Strejcová, Eva | Czechia | 18.14 |  |
| 70 | Yang, Yuanfan | United Kingdom | 18.13 |  |
| 71 | Fan, Yu-Ang | China | 18.02 |  |
| 72 | Basista, Michał | Poland | 17.80 |  |
| 73 | Deng, Athena | Canada | 17.73 |  |
| 74 | Sejbuk, Zuzanna | Poland | 17.73 |  |
| 75 | Zenin, Andrey | INP | 17.70 |  |
| 76 | Yamazaki, Ryota | Japan | 17.51 |  |
| 77 | Onoda, Arisa | Japan | 17.46 |  |
| 78 | Nakashima, Yulia | Japan | 17.44 |  |
| 79 | Kłeczek, Antoni | United States | 17.42 |  |
| 80 | Zhong, Yonghuan | China | 17.24 |  |
| 81 | Lin, Hao-Wei | Chinese Taipei | 17.14 |  |
| 82 | Wang, Ryan | Canada | 16.88 |  |
| 83 | López Salas, Pedro | Spain | 15.55 |  |
| 84 | U, Chun Lam | Hong Kong | 15.44 |  |

### JST Stage II Results (Advancing to Stage III)

| Rank (Cum. JST) | Name | Country | Score (JST) | Cum. Score (JST) | CMEAN Adv. |
|:---:|:---|:---|:---:|:---:|:---:|
| 1 | Chen, Kevin | Canada | 22.43 | **22.55** | ✔ |
| 2 | Lu, Eric | United States | 22.57 | **22.31** | ✔ |
| 3 | Yang, William | United States | 21.98 | **21.36** | ✔ |
| 4 | Kuwahara, Shiori | Japan | 21.07 | **21.33** | ✔ |
| 5 | Ong, Vincent | Malaysia | 21.01 | **21.23** | ✔ |
| 6 | Ushida, Tomoharu | Japan | 21.38 | **21.23** | ✔ |
| 7 | Li, Tianyou | China | 21.83 | **21.21** | ✔ |
| 8 | Guo, Eric | Canada | 20.37 | **21.07** | ✔ |
| 9 | Lyu, Tianyao | China | 20.64 | **21.07** | ✔ |
| 10 | Khrikuli, David | Georgia | 21.36 | **21.06** | ✔ |
| 11 | Shindo, Miyu | Japan | 20.56 | **20.97** | ✔ |
| 12 | Alexewicz, Piotr | Poland | 20.84 | **20.86** | ✔ |
| 13 | Lee, Hyo | South Korea | 20.76 | **20.82** | ✔ |
| 14 | Lee, Hyuk | South Korea | 20.77 | **20.82** | ✔ |
| 15 | Gao, Yang (Jack) | China | 20.86 | **20.68** | ✔ |
| 16 | Wu, Yifan | China | 20.36 | **20.67** | ✔ |
| 17 | Wang, Zitong | China | 20.58 | **20.63** | ✔ |
| 18 | Pawlak, Piotr | Poland | 20.55 | **20.55** | ✔ |
| 19 | Prokopowicz, Yehuda | Poland | 20.25 | **20.36** | ✔ |
| 20 | Li, Xiaoxuan | China | 20.13 | **20.33** | ✔ |
| (cutoff) |
| 21 | Ratinov, Anthony | United States | 19.93 | **20.26** |  |
| 22 | Strata, Gabriele | Italy | 20.50 | **20.23** |  |
| 23 | Chang, Kai-Min | Chinese Taipei | 20.34 | **20.11** |  |
| 24 | Chen, Xuehong | China | 19.94 | **20.07** |  |
| 25 | Kałduński, Adam | Poland | 19.54 | **20.05** |  |
| 26 | Nakagawa, Yumeka | Japan | 20.00 | **20.03** |  |
| 27 | Aumiller, Jonas | Germany | 19.76 | **19.94** |  |
| 28 | Rao, Hao | China | 19.25 | **19.85** |  |
| 29 | Micieli, Ruben | Italy | 19.25 | **19.63** |  |
| 30 | Milstein, Nathalia | France | 19.04 | **19.63** |  |
| 31 | Lynov, Philipp | INP | 18.98 | **19.61** |  |
| 32 | Li, Zhexiang | China | 19.49 | **19.59** |  |
| 33 | Chen, Zixi | China | 19.27 | **19.54** |  |
| 34 | Jin, Zihan | China | 18.98 | **19.40** |  |
| 35 | Bao, Yanyan | China | 19.07 | **19.39** |  |
| 36 | Zhang, Jacky | United Kingdom | 18.76 | **19.38** |  |
| 37 | Lee, Kwanwook | South Korea | 18.91 | **19.18** |  |
| 38 | Hu, Xiaoyu | China | 18.89 | **19.17** |  |
| 39 | Deng, Yubo | China | 18.94 | **19.12** |  |
| * | Ma, Tiankun | China |  |  |  |

### JST Stage III Results (Advancing 10 to Final)

| Rank (Cum. JST) | Name | Country | Score (JST) | Cum. Score (JST) | CMEAN Adv. |
|:---:|:---|:---|:---:|:---:|:---:|
| 1 | Lu, Eric | United States | 22.94 | **22.74** | ✔ |
| 2 | Chen, Kevin | Canada | 22.32 | **22.40** | ✔ |
| 3 | Wang, Zitong | China | 22.48 | **21.93** | ✔ |
| 4 | Li, Tianyou | China | 21.95 | **21.71** | ✔ |
| 5 | Kuwahara, Shiori | Japan | 21.38 | **21.38** | ✔ |
| 6 | Lyu, Tianyao | China | 21.41 | **21.32** | ✔ |
| 7 | Shindo, Miyu | Japan | 20.91 | **20.94** | ✔ |
| 8 | Khrikuli, David | Georgia | 20.89 | **20.93** | ✔ |
| 9 | Alexewicz, Piotr | Poland | 20.87 | **20.87** | ✔ |
| 10 | Yang, William | United States | 20.66 | **20.85** | ✔ |
| (cutoff) |
| 11 | Lee, Hyo | South Korea | 20.75 | **20.77** |  |
| 12 | Ushida, Tomoharu | Japan | 20.53 | **20.74** |  |
| 13 | **Ong, Vincent** | Malaysia | 20.42 | **20.67** | ✔ |
| 14 | Guo, Eric | Canada | 19.84 | **20.23** |  |
| 15 | Lee, Hyuk | South Korea | 19.93 | **20.20** |  |
| 16 | Wu, Yifan | China | 19.87 | **20.12** |  |
| 17 | Gao, Yang (Jack) | China | 19.82 | **20.07** |  |
| 18 | Prokopowicz, Yehuda | Poland | 19.76 | **19.94** |  |
| 19 | Li, Xiaoxuan | China | 19.59 | **19.82** |  |
| 20 | Pawlak, Piotr | Poland | 19.39 | **19.74** |  |

### JST Final Results (Prizewinners)

| Prize (JST) | Name | Country | Age | Piano | Final Cum. Score (JST) |
|:---|:---|:---|:---:|:---|:---:|
| **1st Prize** | Lu, Eric | United States | 27 | Fazioli | **22.28** |
| **2nd Prize** | Chen, Kevin | Canada | 20 | Steinway | **22.21** |
| **3rd Prize** | Wang, Zitong | China | 26 | Kawai | **21.28** |
| **4th Prize** | Kuwahara, Shiori | Japan | 29 | Steinway | **21.24** |
| **5th Prize** | Lyu, Tianyao | China | 16 | Fazioli | **21.13** |
| **6th Prize** | Alexewicz, Piotr | Poland | 25 | Kawai | **21.04** |
| | Yang, William | United States | 24 | Steinway | **20.78** |
| | Khrikuli, David | Georgia | 24 | Steinway | **20.77** |
| | Li, Tianyou | China | 21 | Steinway | **20.75** |
| | Shindo, Miyu | Japan | 23 | Steinway | **20.48** |

