# TOPIC : 5.1.5 Input Validation
## Source
> - [www.simplilearn.com](https://www.simplilearn.com/data-quality-article)

## Definition 5.1.5 Input Validation
> - Verify that URL redirects and forwards only allow destinations which appear
on an allow list, or show a warning when redirecting to potentially untrusted
content.

## Definition by ChatGPT
> - Input Validation (การตรวจสอบความถูกต้องของข้อมูลนำเข้า) หมายถึง กระบวนการตรวจสอบและจำกัดข้อมูลที่ผู้ใช้หรือระบบภายนอกป้อนเข้ามาในแอปพลิเคชัน เพื่อให้แน่ใจว่าข้อมูลมีรูปแบบที่ถูกต้อง ปลอดภัย และไม่เป็นอันตรายต่อระบบ

## Definition by Gemini
> - การตรวจสอบอินพุต (Input Validation) คือกระบวนการตรวจสอบข้อมูลที่ผู้ใช้ป้อนเข้ามาในระบบ เพื่อให้แน่ใจว่าข้อมูลนั้นถูกต้องตามรูปแบบที่กำหนดไว้ และปลอดภัยต่อการนำไปใช้งาน

## My Summary
> - Data Uniqueness คือข้อมูลที่มีคุณสมบัติที่มีเอกลักษณ์ของตัวเองและไม่ซ้ำกับข้อมูลอื่นๆ โดยข้อมูลชนิดนี้จะไม่สามารถมีข้อมูลที่เหมือนหรือซ้ำกันได้

## Sample
> - การเก็บข้อมูลลูกค้าลงในฐานข้อมูลจะต้องกำหนด ID ของลูกค้าไม่ซ้ำกันหรือการกำหนด primary key เป็น customerID เช่น
> - CustomerID : 001        Name : "John"
> - CustomerID : 002        Name : "Ben"
> - CustomerID : 003        Name : "Jesse"
