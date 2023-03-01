# hse_hw2_chip
## Анализ выдачи fastqc
### ENCFF001EXM
![2023-03-01_11-13-10](https://user-images.githubusercontent.com/87602071/222082022-8e22cc97-a7e7-466a-9ff2-60971bc97d78.png)
![2023-03-01_11-13-53](https://user-images.githubusercontent.com/87602071/222082033-eec38f70-e642-4abe-ba21-855c2af3a635.png)

Качество чтения вполне удовлетворительное
### ENCFF000ASV
![2023-03-01_11-17-08](https://user-images.githubusercontent.com/87602071/222082908-31d9af17-569b-464b-a403-99526980b065.png)
![2023-03-01_11-17-34](https://user-images.githubusercontent.com/87602071/222082915-e3e3b40b-439b-4f32-a1cf-32a36d6c820a.png)

Качество довольно плохое, произведем фильтрацию и подрезание c помощью trimmomatic
### ENCFF000ASV trimmed
![2023-03-01_11-26-21](https://user-images.githubusercontent.com/87602071/222084685-248c3c08-bf15-4799-a8fe-68179e189f8c.png)
![2023-03-01_11-26-37](https://user-images.githubusercontent.com/87602071/222084693-3179762a-d172-4f53-8705-5f303e11445d.png)

Качество чтений улучшилось
### ENCFF001HID
![2023-03-01_11-27-40](https://user-images.githubusercontent.com/87602071/222084967-c5171015-6d9a-4214-b9b8-7a6ed8a84929.png)
![2023-03-01_11-27-56](https://user-images.githubusercontent.com/87602071/222084977-f9637cff-afaa-49d8-ac96-a9939770621e.png)

Есть ошибки, но в целом качество удовлетворительное
## Выравнивание на хромосому 14

|                       |**всего ридов**|**выровненные 0 раз**|**выровненные ровно 1 раз**|**выровненные более 1 раза**|
|-----------------------|---------------|---------------------|---------------------------|----------------------------|
|ENCFF001EXM            |   14462737    |  12026837 (83.16%)  |      570510 (3.94%)      |       1865390 (12.90%)     |
|ENCFF000ASV            |   7618759     |  6167495 (80.95%)  |      306055 (4.02%)      |      1145209 (15.03%)     |
|ENCFF001HID            |   16990693    |  13761137 (80.99%)  |      752052 (4.43%)      |       2477504 (14.58%)     |
## Диаграммы Венна
### ENCFF001EXM
![2023-03-01_12-04-12](https://user-images.githubusercontent.com/87602071/222093124-64137799-0c6a-428c-85ec-039365eef64e.png)
![2023-03-01_12-04-34](https://user-images.githubusercontent.com/87602071/222093130-915a10b0-f368-4563-be7e-6861800d6693.png)
### ENCFF000ASV
![2023-03-01_12-05-25](https://user-images.githubusercontent.com/87602071/222093373-f766e11b-eb48-409c-887a-a7d747247057.png)
![2023-03-01_12-05-46](https://user-images.githubusercontent.com/87602071/222093391-d1be578d-2442-4fc5-b280-a53ef7d43a1e.png)
