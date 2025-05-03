# Results

![grafana](https://github.com/rukpet/Assignment-3/blob/ee2f17bc57eed6ae4e9d792005cdc53e3cb899a1/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-05-03%20220946.png)

![jmeter](https://github.com/rukpet/Assignment-3/blob/ee2f17bc57eed6ae4e9d792005cdc53e3cb899a1/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-05-03%20221035.png)


# How to run

**Prerequisites:** Installed Docker and JMeter with plugins

1. ```docker-compose -f docker-compose.yaml up --detach```
2. Open http://localhost:3000/connections/datasources
3. Configure Grafana
- Add InfluxDB in Data sources
  ![datasource](https://github.com/rukpet/Assignment-3/blob/ee2f17bc57eed6ae4e9d792005cdc53e3cb899a1/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-05-03%20221202.png)
  ![http](https://github.com/rukpet/Assignment-3/blob/ee2f17bc57eed6ae4e9d792005cdc53e3cb899a1/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-05-03%20221301.png)
  ![details](https://github.com/rukpet/Assignment-3/blob/ee2f17bc57eed6ae4e9d792005cdc53e3cb899a1/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-05-03%20221340.png)
- Add dashboard
  ![http](https://github.com/rukpet/Assignment-3/blob/ee2f17bc57eed6ae4e9d792005cdc53e3cb899a1/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-05-03%20221415.png)
  ![details](https://github.com/rukpet/Assignment-3/blob/ee2f17bc57eed6ae4e9d792005cdc53e3cb899a1/%D0%97%D0%BD%D1%96%D0%BC%D0%BE%D0%BA%20%D0%B5%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202025-05-03%20221452.png)
3. Run PerfTest.jmx via JMeter
  
