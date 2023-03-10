![image](https://user-images.githubusercontent.com/79916736/210174229-e5832e4d-e904-4f14-81a4-978e879f298d.png)

# Deep Knowledge Tracing

# π RECCAR νμ μκ°

| <img src="https://user-images.githubusercontent.com/79916736/207600031-b46e76d2-cba3-4c94-9fc3-d9f29cd3bef8.png" width=200> | <img src="https://user-images.githubusercontent.com/79916736/207600420-dd537303-d69d-439f-8cc8-5af648fe8941.png" width=200> | <img src="https://user-images.githubusercontent.com/79916736/207601023-bbf9e64f-1447-41d8-991f-677593094592.png" width=200> | <img src="https://user-images.githubusercontent.com/79916736/207600724-c140a102-39fc-4c03-8109-f214773a64fc.png" width=200> | <img src="https://user-images.githubusercontent.com/79916736/208005357-e98d106d-a207-4acd-ab4b-1abf7dbcb69f.png" width=200> | <img src="https://user-images.githubusercontent.com/79916736/207600926-eb59f2cd-2805-4a8a-b43b-084b0ff7d6b5.png" width=200> |
| :-------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------: |
|                                           [κΉμ±μ°](https://github.com/KSY1526)                                            |                                           [λ°°μ±μ¬](https://github.com/SeongJaeBae)                                            |                                            [μμΉν](https://github.com/Seunghoon-Schini-Yang)                                            |                                         [μ‘°μμ°](https://github.com/Suyeonnie)                                          |                                            [ν©μ ν](https://github.com/HSUNEH)                                            |                                            [νμ¬ν](https://github.com/secrett2633)                                            |


# ποΈ νλ‘μ νΈ λͺ©ν
<!-- <p align="center"><img src="https://user-images.githubusercontent.com/65529313/168472960-0eac76e2-4fe3-4ebc-b093-f9c0aab59859.png" /></p> -->
- μ¬μ©μμ λ¬Έμ  νμ΄ κΈ°λ‘μ λ³΄κ³  λ€μ λ¬Έμ μ μ λ΅ μ¬λΆλ₯Ό λ§μΆλ λͺ¨λΈ μ€κ³
- μ¬μ©μμ μ§μ μνλ₯Ό μΆμ νλ λ₯λ¬λ λͺ¨λΈ μ€κ³

<br /> 
<br /> 

# π» νμ© μ₯λΉ
- GPU Tesla V100-PCIE-32GB

<br /> 
<br /> 

# ππ»ββοΈπ»ββοΈ νλ‘μ νΈ ν κ΅¬μ± λ° μ­ν 
- **κΉμ±μ°**: EDA, μ λ°μ μΈ ν νλ‘μ νΈ νμλΌμΈ μ‘κΈ°, λΆμ€ν λͺ¨λΈ μ μ© μμ
- **λ°°μ±μ¬**: νμμ λ§€λλ½κ² νκΈ° μν μ½λ μ λ¦¬ λ° Git λ΄λΉνκΈ°, ELO λ± νΌμ²μμ§λμ΄λ§ μ§ν
- **μμΉν**: μ λ°μ μΈ κ·Έλν λͺ¨λΈ νμ, GKT, Saint+ λͺ¨λΈ μ μ© μμ
- **μ‘°μμ°**: EDA μ§ν, λΆμ€ν λͺ¨λΈκ³Ό MF λͺ¨λΈ μ μ© μμ
- **νμ¬ν**: GKT λͺ¨λΈ μ μ© μμ, Optuna, K-Fold Cross Validation λ±μ μ΄μ©ν λͺ¨λΈ κ³ λν
- **ν©μ ν**: μ λ°μ μΈ μνμ λͺ¨λΈ νμ, Saint+μ LightGCN λͺ¨λΈ μ μ© μμ


<br /> 
<br /> 

# ποΈ Model Architecture
<!-- <p align="center"><img src="https://user-images.githubusercontent.com/65529313/168473170-938e1ce0-395f-40be-9118-ea127668b11d.png" /></p> -->

- λ²μ£Όν λ°μ΄ν° μ²λ¦¬μ μ’μ μ±λ₯μ λ΄λ Catboost Model μ¬μ©
- νΌμ² μμ§λμ΄λ§ ν μ μ  λ¨μλ‘ LGBM μ¬μ©
- Surprise λΌμ΄λΈλ¬λ¦¬λ₯Ό μ΄μ©ν μ¬νν MF Model μ¬μ©
- μνμ μ λ³΄λ₯Ό λ΄λ λ₯λ¬λ λͺ¨λΈ Saint_plus μ¬μ©
- μ μ μ λ¬Έμ  κ° κΉμ μνΈμμ©μ μ νννλ κ·Έλν κΈ°λ° LightGCN Model μ¬μ©
- κ·Έλνμ μνμ λ ννλ₯Ό λͺ¨λ κ°μ§κ³  μλ GKT Model μ¬μ©
~~~
EDA λ΄ κ°μΈ λ³ EDAμ νΌμ²μμ§λμ΄λ§μ΄ λ΄κ²¨μμ΅λλ€.
requirements.txt λ΄ λΌμ΄λΈλ¬λ¦¬λ§ λ€μ΄λ°μΌλ©΄ μ€νμν€λλ° λ¬΄λ¦¬ μμ΅λλ€.
λ¨, LightGCN λͺ¨λΈμ κ²½μ° ν΄λ λ΄ install.sh μ μ€νμν¨ κ°μνκ²½μμλ§ μλν©λλ€.
μμΈν μ€λͺμ λ°νμλ£ λ° λ ν¬νΈλ₯Ό μ°Έκ³ ν΄μ£ΌμΈμ.
~~~

<br /> 
<br /> 



# π― νλ‘μ νΈ μν κ²°κ³Ό - μ΅μ’ Private 2λ±

|λ¦¬λλ³΄λ| auroc  |     μμ     |
|:--------:|:------:|:----------:|
|public| 0.8362 |  **2μ**   |
|private| 0.8549 | **μ΅μ’ 2μ** |

![image](https://user-images.githubusercontent.com/79916736/210174782-89b8297a-dd02-4585-aff2-873a4717fb2c.png)