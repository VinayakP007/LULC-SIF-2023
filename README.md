# LULC-SIF-2023

Our Approach here was to create indiviual season LULC maps then composite them.

here is the Google earth engine link 
https://code.earthengine.google.com/?accept_repo=users/vinayakvpatil61/SIF_Hackathon_LULC
there are four code scripts
the three will make and Exporte image of three seasons will be used to make final Composite of all three seasons combined 
and Final Composite one will Create composite of all seasons

this is the drive link where results were stored 
https://drive.google.com/drive/folders/1_2iHRNAxzf3XCilfbtERlY2-koNV6XsF?usp=sharing

Here is the result of zaid in 2020 
acuuracy1 is for Random Forest and accuracy2 for CART algo 
you can verify result by yourself by checking the Google earth engine link
![image](https://github.com/VinayakP007/LULC-SIF-2023/assets/153257058/e9848c55-0987-40d1-9368-add18074e833)

We used two models for all seasons and then merged the result to improve accuracy 
As you see over here when we utilized ensemble learning with RF (Random Forest) and CART models our accuracy improved.
![image](https://github.com/VinayakP007/LULC-SIF-2023/assets/153257058/1ef7fece-39c8-4384-a4a5-2af4f6ded26a)

here is the LULC of zaid 2020 from Random forest algo 
![Zaid 2020 RF only](https://github.com/VinayakP007/LULC-SIF-2023/assets/153257058/fc9f1012-4697-446d-9b32-3233886c2934)


here is after merging RF and CART model for zaid 2020 
![Zaid Reclassified](https://github.com/VinayakP007/LULC-SIF-2023/assets/153257058/ef48c12e-fc48-4270-95b3-a5e155719182)



Here is Results for Kharif 
![image](https://github.com/VinayakP007/LULC-SIF-2023/assets/153257058/d6311e1d-611d-4d0b-bb9f-84d8446de7b7)
![image](https://github.com/VinayakP007/LULC-SIF-2023/assets/153257058/d56a5446-8910-43ef-aaa9-33177a7d7374)

Here is the Results for Rabi
![image](https://github.com/VinayakP007/LULC-SIF-2023/assets/153257058/168eecd3-cda7-449e-aa59-74d9eb10cd2c)
![image](https://github.com/VinayakP007/LULC-SIF-2023/assets/153257058/d2033ddb-bfce-4ac0-88ec-d49a6d13c3d9)


Final composite image of all three seasons 
![image](https://github.com/VinayakP007/LULC-SIF-2023/assets/153257058/e1c50ffa-4d2c-4cb8-a80c-a4b55259a423)
