# hse_hw2_chip

## Ссылка на эксперисмент
https://www.encodeproject.org/experiments/ENCSR526UWU/

## Ссылка на Colab
https://colab.research.google.com/drive/15oBoGD66BVxGoKGxWkx7EJKBQUVnilNV?usp=sharing

## FastQC

### ENCFF058HFU

![image](https://user-images.githubusercontent.com/71763293/222211089-a8afe95e-12cf-42ef-b600-9dc7194f9700.png)
![image](https://user-images.githubusercontent.com/71763293/222211153-b390344e-064e-42d7-b658-d37085e9353e.png)

### ENCFF275PNU

![image](https://user-images.githubusercontent.com/71763293/222242701-17f94710-e9b0-4f1d-9a9f-113b5859ca8d.png)
![image](https://user-images.githubusercontent.com/71763293/222242739-d7b8048e-534f-461b-a159-03beb2bfb79f.png)

### ENCFF308KEO (контроль)

![image](https://user-images.githubusercontent.com/71763293/222211446-e21ffefb-39ff-4104-b31e-999ce8f228fa.png)
![image](https://user-images.githubusercontent.com/71763293/222211466-496342e2-1d73-4390-92f1-0583cbcbfe5e.png)

## Анализ выравнивания (выдача bowtie2)
![image](https://user-images.githubusercontent.com/71763293/222244178-851e3b24-2584-482b-8a11-626d359604df.png)

## Сравнение с данными из ENCODE
(По две картинки нужно, так как для процедуры сравнения важен порядок того, что с чем сравниваем.)

### ENCFF058HFU & ENCODE
![image](https://user-images.githubusercontent.com/71763293/222233386-e986256f-d0f1-4e9c-b023-75c6f562f882.png)
### ENCODE & ENCFF058HFU
![image](https://user-images.githubusercontent.com/71763293/222233435-1fe3ef7f-f1f3-499d-be51-bb36d5216b77.png)

### ENCFF275PNU & ENCODE
![image](https://user-images.githubusercontent.com/71763293/222242460-7a3e5d53-08c8-48e1-99c1-92f0520f6840.png)
### ENCODE & & ENCFF275PNU
![image](https://user-images.githubusercontent.com/71763293/222242515-f4c39789-2661-4d90-b0cc-9f21517a43ee.png)

Видно, что пересечений в целом немного: видимо, из-за того, что мы делали выравнивание только с одной хромосомой. То есть нам (в упрощённом примере) удалось найти далеко не все места, где есть модификация, по сравнению с предшественниками.
