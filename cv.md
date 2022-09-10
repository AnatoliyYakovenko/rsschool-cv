# **Anatoliy Yakovenko**
****
## **Contacts:**
* Address:			Kyiv oblast, Obukhiv 
* Mobile phone: +38(067)320-71-91
* E-mail:				yakovenko.anatoliy@gmail.com
## **About Myself:**
I have been working in one B2B Telecom company for 14 years but eventually realized that I got into the comfort zone therefore last few years, more and more often have been looking for a moment to switch to IT. In 2021 I finally left this happy place(comfort zone). Then I got a job in another company, also related to the telecom industry. I was responsible for developing a new direction. When the war began, the company had not been working for two months. I used this period to get to know IT fundamentals. When my company began to return to work, I decided to quit and devote all my time to learning IT. I took the course "IT fundamentals for switchers" and was once again convinced that I made the right choice.


I am unemployed now and have a lot of free time to dive into the IT world as deeply as possible. I have already tried Java basic course and Front-End basic as well. I liked them both but Front-end more because I am a creative person and visual learner. In addition, I like to work in a team. I know that this skill is also critical for IT. So that's why I do want to study front-end development and then work as a developer.
## **Hard skills:**
* HTML5, CSS3
* Java Basic
* JavaScript Basics
* Git, GitHub
* VS Code, IntelliJ IDEA
* Adobe Photoshop
## **Soft skills:**
Easy learning, responsibility, sociable, hard-working, punctual, creative 
## **Work experience:**
21.12.21 – 16.05.22      Kyiv, Development department, DEPS Telecom Ltd, head of infrastructure solutions
* Solutions studying
* Market analyzing
* Looking for suppliers
* Annual sales, purchase, marketing planning    
* Lunching a new product and product’s lines
* Participating in local and international exhibitions
* Purchasing of equipment, communications with suppliers
* Technical supporting
14.06.07 – 10.12.21      Kyiv, Telecommunications equipment department, Romsat Ltd, head of cable systems direction
* Organizing and holding of seminars, conferences and courses 
* Marketing
* Active sales
* Purchasing of equipment, communications with suppliers
* Participating in local and international exhibitions
* Lunching new product and product’s lines
* Holding courses of structured cable system. Certified trainer of Commscope SYSTIMAX cable system
* Technical supporting
09.07.05 – 01.06.07     Kyiv, Department of digital communication, “Ukrtelecom”, engineer
* Knowledge of SDH, xWDM; xPON network; 
* Install and maintenance of cable systems; DWDM and SDH’s equipment (Ericsson, ECI)
## **Code example:**
```
package com.epam.rd.autotasks;

import java.util.Arrays;

class CycleSwap {
    static void cycleSwap(int[] array) {
        if (array.length != 0) {
            int[] swapArr = new int[array.length];
            System.arraycopy(array, 0, swapArr, 1, array.length - 1);
            swapArr[0] = array[array.length - 1];
            System.arraycopy(swapArr, 0, array, 0, array.length);
            System.out.println(Arrays.toString(array));
        }
    }

    static void cycleSwap(int[] array, int shift) {
        if (array.length != 0) {

            int[] tmp = new int[array.length];

            System.arraycopy(array, array.length - shift, tmp, 0, shift);
            System.arraycopy(array, 0, tmp, shift, array.length - shift);
            System.arraycopy(tmp, 0, array, 0, array.length);

            System.out.println(Arrays.toString(array));
        }
    }
}
```
## **Languages:**
* English level - B2
* Chinese level - HSK3
* Ukrainian level - Native
