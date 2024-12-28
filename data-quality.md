# Data Quality

=> **Consistency**

| **Soruces**               | **Definition**                                                                                                              |
|--------------------------|--------------------------------------------------------------------------------------------------------------------------
| **คำอธิบาย (SmartBridge)** | Consistency means data across all systems reflects the same information and are in synch with each other across the enterprise. | 
| **คำอธิบาย (ChatGPT)**   | Data consistency in the context of data quality refers to the degree to which data values are uniform, reliable, and aligned across different datasets, systems, or formats. Consistent data ensures that there are no contradictions or discrepancies, which can cause errors in analysis or decision-making.|
| **คำอธิบาย (Gemini)**    | Data consistency is a critical aspect of data quality, ensuring that all copies or instances of data are identical across various systems and databases. This uniformity guarantees that data remains accurate, up-to-date, and coherent, regardless of the platform or location it's accessed from.|
| **Summary**              | Data consistency คือการที่ข้อมูลดิบเป็นไปในทางเดียวกันคือ มีรูปแบบ(Format)เดียวกันหรือมีความอัปเดตของข้อมูลเหมือนกันหรือการที่ไม่มีข้อมูลที่ผิดปกติ(outlier)อยู่ในฐานข้อมูล โดยความสม่ำเสมอและความถูกต้องของข้อมูลที่กล่าวมาจะต้องเป็นไปในทางเดียวกันตลอดทั้งฐานข้อมูล หรือทุกระบบ หรือทุกแพลตฟอร์ม |

# Examples

1. ในฐานข้อมูลนิสิตเกษตร ศรีราชา เมื่อมีการแก้ไขข้อมูลที่อยู่ของนิสิต A ซึ่งมีที่อยู่เดิมคือ 00 เปลี่ยนเป็น 11 การอัปดเตของข้อมูลดังกล่าวจะต้องได้รับการแก้ไขในทุกๆระบบหรือในตารางข้อมูลอื่นๆที่มีข้อมูลนิสิต A อยู่ให้เหมือนกัน
2. ในการเก็บข้อมูลอายุของนิสิตเกษตร ศรีราชา ต้องตรวจสอบให้ไม่มีข้อมูลอายุนิสิตที่เป็นไปไม่ได้หรือผิดปกติ เช่น อายุ 100 , -1 เป็นต้น อยู่ในฐานข้อมูล

# Reference source
[SmartBridge](https://smartbridge.com/data-done-right-6-dimensions-of-data-quality/)
