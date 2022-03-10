# hse_hw2_chip

[Collab](https://colab.research.google.com/drive/1kK7LZjc-maAqOe8lQjfmRAJSzPP2C7Ui?usp=sharing)

# Main part

## Анализ FastQC

### ENCFF877GMR (реплика 1)
Использовалось подрезание чтения

<img width="495" alt="Screenshot 2022-03-10 at 19 09 31" src="https://user-images.githubusercontent.com/71605966/157705232-0fffd843-171e-46a8-8fbb-3a475841eac4.png"> <img width="495" alt="Screenshot 2022-03-10 at 19 10 05" src="https://user-images.githubusercontent.com/71605966/157705416-cd3334fe-475a-4f9d-8df1-c676a2e70c06.png">

<img width="495" alt="Screenshot 2022-03-10 at 19 11 35" src="https://user-images.githubusercontent.com/71605966/157705910-ce50ce25-93b1-4bef-8242-929b63ea60de.png"> <img width="495" alt="Screenshot 2022-03-10 at 19 13 06" src="https://user-images.githubusercontent.com/71605966/157706202-03723fe4-4080-4c8b-915d-776ca0f7c3f9.png">

<img width="495" alt="Screenshot 2022-03-10 at 19 14 09" src="https://user-images.githubusercontent.com/71605966/157706398-d32482ac-479b-42ac-b081-78f3530d5503.png"> <img width="495" alt="Screenshot 2022-03-10 at 19 14 49" src="https://user-images.githubusercontent.com/71605966/157706542-492f0bbb-b510-47a8-8f52-8962bcfe5178.png">

### ENCFF691TDE (реплика 2)
Использовалось подрезание чтения

<img width="495" alt="Screenshot 2022-03-10 at 19 16 39" src="https://user-images.githubusercontent.com/71605966/157706875-6f56ae90-33f3-4548-bdc1-2d8a69a1f2f3.png"> <img width="495" alt="Screenshot 2022-03-10 at 19 17 06" src="https://user-images.githubusercontent.com/71605966/157706958-5ad089b1-cca3-49a5-95ec-90e0b5899623.png">

<img width="495" alt="Screenshot 2022-03-10 at 19 17 54" src="https://user-images.githubusercontent.com/71605966/157707083-d1475a07-498a-4eb6-8e24-7332c0a15eb8.png"> <img width="495" alt="Screenshot 2022-03-10 at 19 18 47" src="https://user-images.githubusercontent.com/71605966/157707249-ef7b176e-d84f-417c-87fd-755e29145c99.png">

<img width="495" alt="Screenshot 2022-03-10 at 19 19 55" src="https://user-images.githubusercontent.com/71605966/157707426-1a90adfa-5400-443e-874e-6b6df74f8319.png"> <img width="495" alt="Screenshot 2022-03-10 at 19 20 31" src="https://user-images.githubusercontent.com/71605966/157707532-7d53de6a-020b-42c5-a948-70c0bd84fd8f.png">

### ENCFF421HCG (контроль)

<img width="495" alt="Screenshot 2022-03-10 at 19 26 43" src="https://user-images.githubusercontent.com/71605966/157708791-615ff4b1-95e2-4989-bfc6-491572e3f943.png"> <img width="495" alt="Screenshot 2022-03-10 at 19 27 47" src="https://user-images.githubusercontent.com/71605966/157708976-406417e7-e20a-4dfc-b538-f3549606736e.png">

<img width="495" alt="Screenshot 2022-03-10 at 19 28 30" src="https://user-images.githubusercontent.com/71605966/157709129-b96aa7fb-2b7c-47ac-a156-f922471ce4ba.png"> <img width="495" alt="Screenshot 2022-03-10 at 19 29 48" src="https://user-images.githubusercontent.com/71605966/157709462-5a8c38b6-27a2-42f5-925d-0b02087548fd.png">

<img width="495" alt="Screenshot 2022-03-10 at 19 30 43" src="https://user-images.githubusercontent.com/71605966/157709580-36d4a188-143e-47ed-ad28-b1a3f3825ed2.png"> <img width="495" alt="Screenshot 2022-03-10 at 19 31 10" src="https://user-images.githubusercontent.com/71605966/157709676-7def1368-490e-4bc9-88f5-759a221e6c2c.png">


## Статистика выравнивания на 18 хромосому

| ID | Всего ридов | Уникально выровнилось | Неуникально выравнилось | Не выравнилось |
|----|-------------|-----------------------|-------------------------|----------------|
| ENCFF877GMR   |  4260897   |  158125 (3.71%)  |   708153 (16.62%)  |  3394619 (79.67%)  |
| ENCFF691TDE   |  5161543   |  191469 (3.71%)   |  813356 (15.76%)   |   4156718 (80.53%)   |
| ENCFF421HCG   |  14994492   |  481294 (3.21%)   |  1615293 (10.77%)   |   12897905 (86.02%)   |

Процент выравнивания зависит от выбранной хромасомы

## Диаграммы Эйлера - Вена

<img width="495" alt="Screenshot 2022-03-10 at 19 40 25" src="https://user-images.githubusercontent.com/71605966/157711494-6db7d63a-f9d8-4223-bd21-4c3d6d6ccc56.png"> <img width="495" alt="Screenshot 2022-03-10 at 19 40 52" src="https://user-images.githubusercontent.com/71605966/157711583-366eebf2-57eb-4479-88d0-a9bdfcad0892.png">


<img width="495" alt="Screenshot 2022-03-10 at 19 41 28" src="https://user-images.githubusercontent.com/71605966/157711714-233e5281-77f7-45f5-90c8-6c430017bffc.png"> <img width="495" alt="Screenshot 2022-03-10 at 19 41 52" src="https://user-images.githubusercontent.com/71605966/157711800-ef0deae3-ff32-477a-a573-a115757151d1.png">

Перечесений мало, скорее всегоэто связано с тем, что выравнивание было только на одну хромосому

