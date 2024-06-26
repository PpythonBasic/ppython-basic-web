# คำศัพท์ย่อในโลกโอเพ่นซอร์สและการพัฒนาซอฟต์แวร์

เคยสงสัยไหมว่าเวลาเห็นคอมเมนต์ใน GitHub เต็มไปด้วยคำสั้นๆ อย่าง LGTM, ACK, NACK, RFC หรือ WIP แล้วมันแปลว่าอะไร? บทความนี้จะมาไขข้อสงสัยเหล่านั้นให้

## คำศัพท์ย่อทั่วไป

| คำศัพท์ย่อ   | ความหมาย                                                                      |
| ------------ | ----------------------------------------------------------------------------- |
| LGTM         | Looks Good To Me - เห็นด้วย, โค้ดโอเค                                         |
| ACK          | Acknowledgement - รับทราบ, เห็นด้วยกับการเปลี่ยนแปลง                          |
| NACK/NAK     | Negative Acknowledgement - ไม่เห็นด้วยกับการเปลี่ยนแปลง                       |
| RFC          | Request For Comments - ขอความเห็น, คิดว่าไอเดียนี้น่าสนใจ ลองมาคุยกัน         |
| WIP          | Work In Progress - ยังไม่เสร็จ, อย่าเพิ่ง merge                               |
| AFAIK/AFAICT | As Far As I Know / Can Tell - เท่าที่ฉันรู้ / เท่าที่เข้าใจ                   |
| IIRC         | If I Recall Correctly - ถ้าจำไม่ผิด                                           |
| IANAL        | I Am Not A Lawyer - ฉันไม่ใช่ทนายความนะ แต่กลิ่นๆ ว่ามีประเด็นเรื่องลิขสิทธิ์ |

## คำศัพท์ย่อเฉพาะ

| คำศัพท์ย่อ                | ความหมาย                                                  |
| ------------------------- | --------------------------------------------------------- |
| Concept ACK               | เห็นด้วยกับแนวคิด แต่ยังไม่ได้ตรวจสอบโค้ด                 |
| utACK (aka. Untested ACK) | เห็นด้วยกับการเปลี่ยนแปลงและตรวจสอบแล้ว แต่ยังไม่ได้ทดสอบ |
| Tested ACK                | เห็นด้วยกับการเปลี่ยนแปลง ตรวจสอบและทดสอบเรียบร้อย        |

## เกร็ดความรู้

- +1 ใช้แทน ACK (และบางกรณีคือ Concept ACK) ได้
- หลังมีจดหมาย "Dear Github" ทางแพลตฟอร์มได้เพิ่ม reactions ให้ใช้แทนคอมเมนต์สั้นๆ (ไม่ใช่การเปลี่ยน Github ให้เป็นเฟสบุ๊ค!)
- ACK ยังพบได้ใน commit message อย่างเช่นในเคอร์เนลลินุกซ์
- คำศัพท์ย่อแบบนี้ใช้กันทั่วไปในวงการวิศวกรรมซอฟต์แวร์และโอเพ่นซอร์ส เพื่อให้การสื่อสารมีประสิทธิภาพ

## ศัพท์เฉพาะสำหรับโค้ด

นอกจากนี้ ยังมีคำศัพท์เฉพาะสำหรับโค้ดอีกด้วย เช่น TODO, FIXME, XXX, NOTE ฯลฯ อยากรู้ว่า XXX แปลว่าอะไร ลองไปหาที่ The Jargon File ซึ่งเป็นแหล่งรวมศัพท์เฉพาะทางคอมพิวเตอร์มาตั้งแต่ปี 1975

## โบนัส

**ACK/NACK มาจากไหน?**

น่าจะมาจากโปรโตคอลเครือข่าย/อินเตอร์เฟซ อาจจะเป็นเพราะความนิยมของ TCP ที่ทำให้คำพวกนี้แพร่หลาย

หวังว่าบทความนี้จะช่วยไขข้อสงสัยเกี่ยวกับคำศัพท์ย่อในโลกโอเพ่นซอร์สและการพัฒนาซอฟต์แวร์นะครับ!

ที่มา [What do cryptic Github comments mean?](https://www.freecodecamp.org/news/what-do-cryptic-github-comments-mean-9c1912bcc0a4/)
