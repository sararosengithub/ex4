cmake_minimum_required(VERSION 3.17)
project(ex4)

set(CMAKE_CXX_STANDARD 14)

add_executable(ex4 mainTrain.cpp anomaly_detection_util.cpp SimpleAnomalyDetector.cpp timeseries.cpp minCircle.cpp HybridAnomalyDetector.cpp)