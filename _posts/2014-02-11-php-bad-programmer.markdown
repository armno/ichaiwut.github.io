---
layout: post
title: "Why you're bad PHP programmer"
slug: "whay-youre-bad-php-programmer"
date: 2014-02-11 12:16:44
categories: Trick
comments: true
image: http://farm6.staticflickr.com/5507/12450834123_41478d00b6_o.jpg
description: "จำได้ว่าเมื่อเดือนสองเดือนก่อนผมอ่านไปเจอบทความหนึ่งที่อธิบายถึงคุณลักษณะที่แย่ๆ ของ PHP Programmer ในเว็บไซต์หนึ่ง เลยอยากเอามาเล่าให้ได้ฟังว่าอะไรกันที่ทำให้เรากลายเปนโปรแกรมเมอร์ที่แย่ๆ
คุณลักษณะเหล่านี้แหละที่จะทำให้เราติดนิสัย และไม่ดีนักหากเราทำงานเป็นทีม"
---

จำได้ว่าเมื่อเดือนสองเดือนก่อนผมอ่านไปเจอบทความหนึ่งที่อธิบายถึงคุณลักษณะที่แย่ๆ ของ PHP Programmer ในเว็บไซต์หนึ่ง เลยอยากเอามาเล่าให้ได้ฟังว่าอะไรกันที่ทำให้เรากลายเปนโปรแกรมเมอร์ที่แย่ๆ
คุณลักษณะเหล่านี้แหละที่จะทำให้เราติดนิสัย และไม่ดีนักหากเราทำงานเป็นทีม

### ไม่เคยแพลนก่อนเขียนโค๊ด
การคิดการก่อนทำนั้นเป็นสิ่งที่เสมอ เหมือนกับการเดินทางถ้าเราไม่วางแผนก่อนทำก็เหมือนเราสุ่มไปข้างหน้าบางทีอาจจะทำให้เราหลงทางและเสียเวลา การเชียนโค๊ดโดยปราศจากการวางแผนจะทำให้เราเสียเวลา
และต้องเขียนๆ แก้ๆ ทำให้เกิดความสับสนบางครั้งอาจให้ให้เกิดความผิดพลาดได้ง่าย

### ไม่เคยคอมเมนต์
การทำงานเป็นทีม หรือแม้การทำงานคนเดียวการคอมเมนต์เป็นอะไรที่สำคัญและจำเป็นอย่างมาก เพราะทุกครั้งที่เรากลับมาอ่านโค๊ดเราจะได้รู้ว่าตรงนี้ทำอะไรหรือตัวแปรนี้เก็บอะไร หากเรากลับมาอ่านโค๊ดโดยไม่มีคอมเมนต์
คุณจะต้องกลับไปหาว่าส่วนนี้มาจากไหน ส่วนนี้กำลังทำอะไรอยู่ ต้องไล่แกะไล่อ่านทีละบรรทัด มันแย่มาก

### เขียนโค๊ดไม่สะอาด ไม่เป็นระเบียบ
อีกเรื่องหนึ่งที่สำคัญไม่แพ้กัน ทุกครั้งที่คุณเขียนโค๊ดแบบช่างมัน อันนี้แย่มาก การเว้นช่องว่าง (space) ในแต่ละ condition หรือแม้แต่การเว้นบรรทัดเพื่อให้โค๊ดดูเป็นระเบียบอ่านง่ายนั้นทำได้ไม่ยากเลย คุณอาจจะเสียเวลา
ไปเพียงแค่ 1- 3 วินาที รวมไปถึงการตั้งชื่อตัวแปรสมมุติหากคุณตั้งชื่อ `$a` เราจะเดายากมากว่าตัวแปรนี้เก็บอะไร จะดีไม่น้อยหากเราเปลี่ยนเป็น `$employees` นั่นทำให้เราเดาได้ง่ายกว่าตัวแปรนี้เก็บค่าอะไรอยู่

### Coding Standard
การเขียนโค๊ดให้เป็นไปตามมาตรฐานสากลเป็นสิ่งที่โปรแกรมเมอร์พึงกระทำเป็นอย่างยิ่ง โค๊ดของคุณจะมีระเบียบ อ่านง่าย และที่สำคัญทุกคนส่วนใหญ่บนโลกใบนี้ต่างก็เขียนไปในทางเดียวกัน มันทำให้ง่ายเวลาคุณมีปัญหาเกี่ยวกับการเขียนโปรแกรมและต้องการให้คนอื่นบนโลกออนไลน์
หรือแม้แต่เพื่อนคุนเองช่วยแก้ไข เมื่อเขียนไปในทางทิศเดียวกันก็ไม่ยากที่จะเข้าใจโค๊ดของคุณ และเข้าใจปัญหาที่เกิดขึ้นได้ง่ายอีกด้วย

### เขียนโค๊ดซ้ำไปซ้ำมา
โค๊ดที่ใช้ซ้ำๆ ควรจะออกแบบให้มีการเขียนเพียงครั้งเดียวและเรียกใช้เอาจากหลายๆที่ จะทำให้เราไม่ต้องเสียเวลาเขียนอะไรที่มันมีอยู่แล้วและง่ายต่อการแก้ไขโดยไม่ต้องไปไล่หาว่าผิดพลาดตรงไหน

### ไม่เคยเรียนรู้สิ่งใหม่ๆ
โลกนี้หมุนไปเร็วมาก มีโปรแกรมเมอร์ใหม่ๆเกิดขึ้นมากมาย หลายคนก็หลายความคิดมักจะมีไอเดียดีๆ หรือเทคโนโลยีดีๆให้เราได้ซึมซับเก็บเกี่ยวยู่เสมอ หากเราพลาดในส่วนนี้ไปงานของคุณก็จะกลายเป็นงานที่ล้หลังไปโดยปริยาย

### ทำทุกอย่างด้วยตัวเองทั้งหมด
อยากที่ได้เกริ่นไปในหัวข้อที่แล้ว โลกนี้มีอะไรที่เขาทำไว้อยู่แล้วไม่ว่าจะเป็นตัวอย่างการเขียนโค๊ดในหลายๆส่วน เราเพียงแค่ทำความเข้าใจศึกษาปรับปรุงวิธีการพัฒนาเรียนรู้จากตัวอย่าง ยกตัวอย่างเช่นหากคุณต้องทำเว็บไซต์ที่มีระบบเว็บบอร์ด
คุณเองจะใช้ opensource หรือเขียนเองขึ้นมาใหม่ทั้งหมด?

### ไม่แชร์ประสบการณ์ หรือเปิดรับอะไรใหม่ๆ
ทางที่ดีที่สุดในการพัฒนาตัวเองและปรับปรุงตัวเองคือการแชร์ประสบการณ์กับผู้อื่น คุณเองอาจจะได้อะไรกลับมาเพื่อพัฒนาและปรับปรุงตัวเอง ในทางกลับกันโปรแกรมเมอร์คนอื่นก็จะได้ประสบการณ์ของคุณเองไปพัฒนาฝีมือของเขา
การแชร์ประสบการณ์เป็นสิ่งที่ดี และควรทำหากคุณเองเป็นโปรแกรมเมอร์

ที่ผมกล่าวมาข้างต้นเป็นเพียงส่วนหนึ่งของโปรแกรมเมอร์ที่ไม่น่าคบ ลองไปอ่านบทความเต็มๆได้ที่นี่เลยครับ [Why You're a Bad PHP Programmer](http://code.tutsplus.com/tutorials/why-youre-a-bad-php-programmer--net-18384)