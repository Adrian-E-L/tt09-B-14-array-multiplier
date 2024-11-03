<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

A 4-bit array multipler is a combinational circuit that multiplies two 4-bit binary numbers using AND gates and full adders. Each bit of one number is multiplied by each bit of the other to create partial products. These products are alligend in a grid, with each row shited one position to the left, like multiplication. These partial products are then added together using half adders and full adders. Each taking three inputs and created a sum that will resutl in a 8-bit binary number. 

## How to test

In order to test the product there needs to be two binary inputs inputed into the code. The first 4-bits being the first number and the last 4-bits being the last number. These numbers are then run though the code, and output an 8-bit number that is the result of the multiplication of the two given numbers. 

## External hardware
N/A
