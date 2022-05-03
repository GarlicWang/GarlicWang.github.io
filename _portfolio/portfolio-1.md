---
title: "Motion Detect LED Bike Vest"
excerpt: "A LED bike vest using STM32 and Rpi with Machine Learning technique<br/><img src='/images/LED_Bike_Vest.png'>"
collection: portfolio
---

It's the final project of Embedded System Course. We use the STM32 board to collect data by its accelerometers. Depending on the data, we design and train a DNN model using CMSIS-NN and deploy it on the STM32 board. Then we can use the model to predict the direction of the bike.

To control the LED, we use a Raspberry Pi as the controller. After the inference in the STM32 board, we pass the direction from STM32 to Raspberry Pi by BLE. Eventually, the Raspberry Pi and relays can control the LED depending on the motion of the rider.
