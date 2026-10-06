# AI-Based Market Basket Analysis for Retail Promotion and Product Placement

Final Project — CP020003 Artificial Intelligence, Khon Kaen University (2026)

## เปิดใน Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Panatchai22/cp/blob/claude/project-thread-37gt22/notebooks/market_basket_analysis.ipynb)

## สิ่งที่ notebook ทำ
1. Mount Google Drive แล้วดาวน์โหลด dataset (KKU Online Retail) ลง `MyDrive/CP_Project/data` ครั้งเดียว จากนั้นโหลดจาก Drive
2. EDA และทำความสะอาดข้อมูล
3. แบ่ง train/test ตามเวลา (train: ธ.ค. 2010–ส.ค. 2011, test: ก.ย.–ธ.ค. 2011)
4. หากฎด้วย Apriori และ FP-Growth และสร้าง Item2Vec embedding
5. วัดผล Hit@10 บน test set เทียบกับ baseline (สินค้าขายดี)
6. แปลงผลเป็นโปรโมชัน (ซื้อ A ลด B พร้อมประเมินรายได้) และโซนวางสินค้า (community detection)
7. บันทึกผลลง `MyDrive/CP_Project/outputs`
