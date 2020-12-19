# Getting used to PySpark

## References
* About Spark:
  - Spark: The Definitve Guide (2018)

* About Colab: https://towardsdatascience.com/pyspark-in-google-colab-6821c2faf41c

## Running PySpark in Colab
* local에 별도로 Spark를 설치하지 않고 Colab 환경에서 PySpark 실습

### How to install PySpark in Colab
Colab 환경에서 PySpark을 사용하기 위해선 Apache Spark `ver1` with haddop`ver2`, Java 8을 설치해야한다. 
`ver1`, `ver2`는 [spark](https://www-us.apache.org/dist/spark/) 에 들어가서 버전 확인 후 그에 맞게 지정해야한다.
필자가 확인 시에는 `ver1=2.4.1`, `ver2=2.7`이기에 이를 적용한다.

``` python
!apt-get install openjdk-8-jdk-headless -qq > /dev/null
!wget -q https://www-us.apache.org/dist/spark/spark-2.4.1/spark-2.4.1-bin-hadoop2.7.tgz
!tar xf spark-2.4.1-bin-hadoop2.7.tgz
!pip install -q findspark
```


