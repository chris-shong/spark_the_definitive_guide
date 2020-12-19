# Getting used to PySpark

## References
* About Spark:
- SparkL The Definitve Guide (2018)

* About Colab: https://towardsdatascience.com/pyspark-in-google-colab-6821c2faf41c

## Running PySpark in Colab
local에 별도로 Spark를 설치하지 않고 Colab 환경에서 PySpark 실습

### How to install PySpark in Colab

''' python
!apt-get install openjdk-8-jdk-headless -qq > /dev/null
!wget -q https://www-us.apache.org/dist/spark/spark-2.4.1/spark-2.4.1-bin-hadoop2.7.tgz
!tar xf spark-2.4.1-bin-hadoop2.7.tgz
!pip install -q findspark
'''
