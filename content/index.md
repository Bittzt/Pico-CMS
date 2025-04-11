---
Title: บทความแนะนำ Pico CMS
Description: บทความนี้อธิบายการสร้างเว็บไซต์ด้วย Pico CMS
Author: บาส
Date: 2025-02-14
---

# สวัสดี!

นี่คือบทความเกี่ยวกับการใช้ Pico CMS ในการสร้างเว็บไซต์แบบ static  
ใช้ Markdown ในการเขียนเนื้อหาได้อย่างง่ายดาย!

---

# สมการตัวอย่าง

สมการของเส้นตรงในรูปแบบ $$ y = mx + b $$  
สามารถใช้ในการแสดงความสัมพันธ์ระหว่าง $$ x $$ และ $$ y $$

สมการพลังงานของ Einstein: $$ E = mc^2 $$  
ที่นี่ $$ E $$ คือพลังงาน, $$ m $$ คือมวล, และ $$ c $$ คือความเร็วของแสง

---


# ตัวอย่างกราฟ

<canvas id="myChart" width="400" height="200"></canvas>

<script>
document.addEventListener("DOMContentLoaded", function () {
    var ctx = document.getElementById('myChart');
    if (ctx) {
        new Chart(ctx, {
            type: 'bar',
            data: {
                labels: ['แดง', 'น้ำเงิน', 'เขียว'],
                datasets: [{
                    label: 'ตัวอย่าง',
                    data: [12, 19, 3],
                    backgroundColor: ['red', 'blue', 'green']
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: true
            }
        });
    }
});
</script>
