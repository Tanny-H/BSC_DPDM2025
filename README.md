# BSC_DPDM2025
## SC663403 Data Preparation and Data Mining
**Sec1** 9 A.M.- 12 P.M. (Tue) / 4.30 P.M. - 6.30 P.M. (Thu)

Teacher : Thanapong Intharah  
Student : Tanawut Hancherngchai 663020280-8

# SCORE ⭐
| งาน | คะแนน |
|--------|-------------|
| **1. Midterm** | 25% |
| **2. Final** | 25% |
| **3. Project** | 20% |
| **4. Homework** | 15% |
| **5. Quiz** | 10% |
| **6. GitHub** | 5% |

# บทที่ 1 บทนำ (Introduction to Data Mining)

## ⭐ Overview
Data Mining คือกระบวนการค้นหารูปแบบ ความสัมพันธ์ และความรู้ใหม่จากข้อมูลจำนวนมหาศาล โดยผสานศาสตร์หลายแขนง เช่น Machine Learning, Statistics, Database Systems และ High-performance Computing เพื่อสร้างข้อมูลเชิงลึกที่สามารถนำไปตัดสินใจเชิงธุรกิจ วิทยาศาสตร์ หรือวิศวกรรม

# Why Data Mining?
## 📈 การเติบโตของข้อมูลแบบก้าวกระโดด
ข้อมูลจากธุรกิจ วิทยาศาสตร์ อินเทอร์เน็ต และสังคมมนุษย์ เพิ่มขึ้นจากระดับ TB → PB → EB อย่างต่อเนื่อง 
เช่น:
  - ข้อมูลเว็บและอีคอมเมิร์ซ
  - การทำธุรกรรมทางการเงิน
  - เซนเซอร์และ IoT
  - ข้อมูลวิทยาศาสตร์ เช่น ภาพถ่ายดาวเทียมหรือชีวสารสนเทศ
  - วิดีโอ YouTube และโซเชียลมีเดีย
แม้ข้อมูลจำนวนมหาศาลจะถูกเก็บไว้ แต่ ความรู้ที่ใช้งานได้จริงกลับมีน้อยมาก → ทำให้ Data Mining กลายเป็นเครื่องมือสำคัญในการดึง Insight ที่ซ่อนอยู่

# What is Data Mining?
Data Mining คือการค้นพบความรู้ (Knowledge Discovery) ที่มี ความหมาย, ไม่ชัดเจนในทันที, และ มีประโยชน์ จากข้อมูลขนาดใหญ่
ชื่ออื่น ๆ ของ Data Mining:
 - Knowledge Discovery in Databases (KDD)
 - Pattern Analysis
 - Information Harvesting
 - Business Intelligence
สิ่งที่ ไม่ใช่ Data Mining:
 - การค้นหาข้อมูลแบบ query ธรรมดา
 - ระบบกฎแบบ Deductive expert system
## KDD Process (Knowledge Discovery Process)
## 🔎 KDD Process — Knowledge Discovery in Databases

| ขั้นตอน | คำอธิบาย |
|--------|-----------|
| **1. Data Cleaning** | กำจัด noise, แก้ missing values, ทำข้อมูลให้มีคุณภาพมากขึ้น |
| **2. Data Integration** | รวมข้อมูลจากหลายแหล่งให้เป็นชุดเดียว เช่น DB, CSV, APIs |
| **3. Data Selection** | เลือกเฉพาะข้อมูลที่เกี่ยวข้องกับงานวิเคราะห์ |
| **4. Data Transformation** | แปลงข้อมูลให้เหมาะกับการทำเหมือง เช่น normalization, feature selection |
| **5. Data Mining** | ใช้อัลกอริทึมเพื่อค้นหารูปแบบ เช่น classification, clustering, association |
| **6. Pattern Evaluation** | ประเมินว่า pattern ที่ได้ “น่าสนใจ” และมีประโยชน์หรือไม่ |
| **7. Knowledge Presentation** | แสดงผลในรูปแบบที่เข้าใจง่าย เช่น visualization, reports |

# Types of Data That Can Be Mined
ข้อมูลที่สามารถนำมาทำ Data Mining ได้มีหลากหลาย
เช่น:
 - Database / Data Warehouse
 - Time-series และ Sequence Data
 - Streaming & Sensor Data
 - Text, Web, และ Multimedia
 - Spatial / Spatiotemporal Data
 - Graph และ Social Network Data

# Data Mining Functions
สิ่งที่ Data Mining ทำได้หลัก ๆ 
ได้แก่:
 - Generalization — สรุปข้อมูลระดับสูง เช่น OLAP, Data Cube
 - Frequent Patterns — หา itemsets และ association rules
 - Classification — ทำนาย class จากข้อมูลที่มี label
 - Clustering — จัดกลุ่มโดยไม่รู้ label ล่วงหน้า
 - Outlier Detection — หาค่าผิดปกติหรือเหตุการณ์แปลก
 - Sequential / Trend Analysis — วิเคราะห์แนวโน้มตามเวลา
 - Graph / Network Analysis — วิเคราะห์โครงสร้างเครือข่าย

# Applications of Data Mining
นำไปใช้ในงานจริงได้หลายด้าน 
เช่น:
 - Web mining และ Recommendation systems
 - Marketing & Customer analytics
 - Fraud detection และความปลอดภัย
 - Bioinformatics และการแพทย์
 - Social network analysis
 - Software engineering analytics

# บทที่ 2 Getting to Know Your Data
## Data Types & Data Sets
- Record Data: ตาราง, เมทริกซ์, เทรนแซกชัน เช่น ข้อมูลขายของ
- Graph/Network Data: เครือข่ายโซเชียล, ถนน, molecular network
- Ordered Data: ข้อมูลเวลา (time-series), ลำดับเหตุการณ์
- Spatial / Image / Multimedia: แผนที่, รูปภาพ, วิดีโอ

## การทำ Visualization
- Pixel-based visualization
- Geometric projection เช่น parallel coordinates
- TreeMap สำหรับข้อมูลลำดับชั้น
- Tag cloud สำหรับแสดงความถี่คำ
- Social network visualization

## Similarity & Distance
- Minkowski distance: L1 (Manhattan), L2 (Euclidean), L∞ (max diff)
- Binary similarity: เช่น Jaccard สำหรับข้อมูล yes/no
- Categorical: simple matching
- Ordinal: แปลงลำดับเป็นค่าระหว่าง 0–1 ก่อนวัด
- Mixed attributes: รวมด้วยสูตรถ่วงน้ำหนัก
- Cosine similarity: ใช้กับเวกเตอร์ เช่น document-term frequency

# บทที่ 3 📊 Data Preprocessing
Data Preprocessing คือขั้นตอนสำคัญก่อนการทำ Data Mining / Machine Learning เพื่อปรับปรุงคุณภาพข้อมูลให้เหมาะสมต่อการวิเคราะห์
🔹 เป้าหมายหลัก
 - เพิ่มคุณภาพข้อมูล (Data Quality)
 - ลดความผิดพลาดและสัญญาณรบกวน
 - ทำให้โมเดลเรียนรู้ได้มีประสิทธิภาพมากขึ้น

## 🧹 Data Cleaning
จัดการข้อมูลที่ไม่สมบูรณ์ ผิดพลาด หรือไม่สอดคล้องกัน
 - Missing Data: ละทิ้งข้อมูล, เติมค่าเฉลี่ย, เติมตามคลาส, หรืออนุมานด้วยโมเดล
 - Noisy Data: ใช้ binning, regression, clustering เพื่อลด noise
 - Inconsistent Data: ตรวจสอบความซ้ำซ้อน ชื่อเรียก และค่าที่ขัดแย้งกัน
 - ตรวจจับ outliers และข้อมูลผิดปกติ

## 🔗 Data Integration
รวมข้อมูลจากหลายแหล่งให้เป็นชุดข้อมูลเดียว
 - แก้ปัญหาชื่อแอตทริบิวต์ไม่ตรงกัน (Schema Integration)
 - ระบุตัวตนของข้อมูลซ้ำ (Entity Identification)
 - ลดข้อมูลซ้ำซ้อนด้วย correlation / covariance analysis

## 📉 Data Reduction & Transformation
ลดขนาดข้อมูลโดยยังคงสาระสำคัญ
 - Numerosity Reduction: ลดจำนวน record
 - Data Compression
 - Normalization: ปรับช่วงข้อมูลให้อยู่ในสเกลเดียวกัน
 - Data Discretization: แปลงค่าต่อเนื่องเป็นช่วง

## 📐 Dimensionality Reduction
ลดจำนวนตัวแปรเพื่อลดปัญหา Curse of Dimensionality
 - Feature Selection: เลือกเฉพาะคุณลักษณะที่สำคัญ
 - Feature Extraction: สร้างคุณลักษณะใหม่
 - PCA (Principal Component Analysis): แปลงข้อมูลให้เหลือมิติน้อยลงโดยคงความแปรปรวนสูงสุด
 - ช่วยลดเวลาในการประมวลผล และทำ visualization ได้ง่ายขึ้น

# บทที่ 6 🍎 Frequent Pattern Mining
🌟 แนวคิดหลัก
Frequent Pattern Mining เป็นเทคนิคสำคัญใน Data Mining ที่ใช้ค้นหารูปแบบหรือความสัมพันธ์ที่เกิดขึ้นบ่อยในข้อมูลขนาดใหญ่ เช่น สินค้าที่มักถูกซื้อร่วมกันในซูเปอร์มาร์เก็ต หรือพฤติกรรมผู้ใช้บนเว็บไซต์

## หัวใจของบทนี้คือการค้นหา:
 - Frequent Itemsets (ชุด item ที่เกิดบ่อย)
 - Association Rules (กฎความสัมพันธ์ เช่น X → Y)

## 📌 เทคนิคนี้ถูกใช้ใน:
 - Recommendation Systems
 - Market Basket Analysis
 - Web Usage Mining
 - Customer Behavior Analysis

## 🧠 1. Basic Concepts
🔹 Transaction Data
ข้อมูลจะอยู่ในรูปแบบ transaction เช่น:
T1: {Milk, Bread}
T2: {Milk, Diaper, Beer}
T3: {Bread, Butter}

🔹 Frequent Itemset

คือชุด item ที่มีความถี่สูงกว่าค่าที่กำหนด (min_support)

📊 สูตร Support
- $s(X) = \frac{\text{จำนวน Transaction ที่มี } X}{\text{จำนวน Transaction ทั้งหมด}}$
	​
- 📌 ใช้ทำอะไร?
→ วัดว่า itemset “เกิดบ่อยแค่ไหน”

## 2. Association Rules
**รูปแบบกฎ**
- $X \rightarrow Y$
หมายถึง:
👉 ถ้ามี X → มีแนวโน้มจะมี Y

**Support ของ Rule**
- $s(X \cup Y) = \frac{\text{จำนวน Transaction ที่มีทั้ง } X \text{ และ } Y}{\text{จำนวน Transaction ทั้งหมด}}$
- วัดความถี่ของการเกิดร่วมกัน

**Confidence**
- $\text{conf}(X \rightarrow Y) = \frac{s(X \cup Y)}{s(X)}$
- → ความน่าจะเป็นว่า “ถ้ามี X จะมี Y”

**Lift**
- $\text{lift}(X \rightarrow Y) = \frac{\text{conf}(X \rightarrow Y)}{s(Y)}$
- → วัด “ความสัมพันธ์จริง” ระหว่าง X และ Y

## ⚙️ 3. Apriori Algorithm

Apriori ใช้หลักการสำคัญ: If a subset is not frequent, then the superset cannot be frequent.

👉 เรียกว่า Apriori Property

**🔁 ขั้นตอนการทำงาน**

1.หา frequent 1-itemsets

2.สร้าง candidate k-itemsets

3.ตัด (prune) itemsets ที่ไม่ผ่าน

4.คำนวณ support

5.ทำซ้ำจนไม่มี itemsets ใหม่


## 🚀 4. FP-Growth Algorithm
FP-Growth ถูกพัฒนามาเพื่อแก้ข้อเสียของ Apriori

✔ ไม่ต้อง generate candidate

✔ ใช้โครงสร้างข้อมูลที่เรียกว่า FP-tree

**🧱 ขั้นตอน**

1️⃣ Scan ข้อมูล
→ นับความถี่ของแต่ละ item
2️⃣ สร้าง FP-tree
→ เก็บข้อมูลในรูป tree
3️⃣ Mining
→ สร้าง frequent patterns แบบ recursive

## 📊 5. Pattern Evaluation

ไม่ใช่ทุก pattern ที่มีค่า ต้องมีการประเมิน

🔑 Criteria
Support → เกิดบ่อยไหม
Confidence → เชื่อถือได้ไหม
Lift → มีความสัมพันธ์จริงไหม

💡 Interestingness
บาง pattern:
support สูง แต่ “ไม่มีประโยชน์”
ต้องใช้ domain knowledge ร่วม

## 🧪 6. Applications
🛒 Market Basket Analysis

วิเคราะห์สินค้าที่ถูกซื้อร่วมกัน

ตัวอย่าง:

Diaper → Beer

-🎯 Recommendation Systems

ใช้ใน:

Amazon
Netflix

-🌐 Web Mining

วิเคราะห์พฤติกรรมการคลิก

-📊 Business Intelligence

ใช้วิเคราะห์ลูกค้าและยอดขาย

## ⚠️ 7. Challenges
🔸 Scalability

ข้อมูลมีขนาดใหญ่มาก

🔸 Rare Items

item บางตัวสำคัญแต่เกิดน้อย

🔸 Dense Data

จำนวน combination สูงมาก

🔸 Dynamic Data

ข้อมูลเปลี่ยนตลอดเวลา

🔸 Pattern Explosion

ได้ pattern เยอะเกินไป

## 🎯 8. Summary
Frequent Pattern = รูปแบบที่เกิดบ่อย

ใช้ Support, Confidence, Lift

Apriori → เข้าใจง่ายแต่ช้า

FP-Growth → เร็วและนิยมใช้

ใช้จริงในธุรกิจจำนวนมาก

# บทที่ 8 📘 Classification
🌟 Overview

Classification คือเทคนิคใน Supervised Learning ที่ใช้ข้อมูลที่มี label เพื่อสร้างโมเดลสำหรับทำนาย class ของข้อมูลใหม่ เช่น การจำแนกอีเมลว่าเป็น spam หรือไม่ หรือการวินิจฉัยโรคจากข้อมูลผู้ป่วย

**หัวใจของ Classification คือ:**

-สร้าง model (classifier) จาก training data
-ใช้ model นั้นในการ predict label ของข้อมูลใหม่

## 🧠 1. Basic Concepts
🔹 Training vs Testing
 Training set → ใช้สร้างโมเดล
 Test set → ใช้ประเมินโมเดล

🔹 Classification Process
 1. เตรียมข้อมูล (preprocessing)
 2. สร้างโมเดล
 3. ประเมินผล
 4. นำไปใช้งาน

🔹 Feature & Label
 - Feature (X) → ตัวแปร input
 - Label (Y) → คำตอบที่ต้องการทำนาย

## 🌳 2. Decision Tree
🌟 แนวคิด
 Decision Tree เป็นโมเดลที่ใช้โครงสร้างแบบต้นไม้:
 - Node = feature
 - Branch = decision
 - Leaf = class

📊 Entropy (ความไม่แน่นอน)

  $Entropy(S) = - \sum_{i=1}^{n} p_i \log_2 p_i$
  
  → วัดความ “ปนกัน” ของข้อมูล

📊 Information Gain

  $Gain(S, A) = Entropy(S) - \sum_{v \in Values(A)} \frac{|S_v|}{|S|} Entropy(S_v)$
  
   → เลือก feature ที่ดีที่สุดในการ split
  
## 📈 3. Naïve Bayes
🌟 แนวคิด
 ใช้ Bayes theorem โดยสมมติว่า feature เป็นอิสระต่อกัน

📊 สูตร

  $P(C|X) = \frac{P(X|C)P(C)}{P(X)}$
  
  → คำนวณ probability ของ class

## 🧠 4. k-Nearest Neighbors (k-NN)
🌟 แนวคิด
 - หาข้อมูลใกล้เคียง k ตัว
 - ใช้ majority vote

📊 สูตร Distance

  $d(x,y) = \sqrt{\sum_{i=1}^{n} (x_i - y_i)^2}$

 → วัดความใกล้ของข้อมูล

## 📊 5. Model Evaluation
🔹 Confusion Matrix

| Actual \ Predicted | Positive | Negative |
|-------------------|----------|----------|
| **Positive**       | TP       | FN       |
| **Negative**       | FP       | TN       |

- **TP (True Positive)** → ทำนายว่าเป็น Positive และเป็นจริง  
- **TN (True Negative)** → ทำนายว่าเป็น Negative และเป็นจริง  
- **FP (False Positive)** → ทำนายว่าเป็น Positive แต่จริง ๆ ไม่ใช่ (False Alarm)  
- **FN (False Negative)** → ทำนายว่าเป็น Negative แต่จริง ๆ ใช่ (Miss)  

### 📊 Accuracy
 $Accuracy = \frac{TP + TN}{TP + TN + FP + FN}$

📌 ใช้: ความถูกต้องโดยรวม

### 📊 Precision
 $Precision = \frac{TP}{TP + FP}$

📌 ใช้: ความแม่นของการทำนาย Positive

### 📊 Recall
 $Recall = \frac{TP}{TP + FN}$

📌 ใช้: ความสามารถในการจับ Positive

### 📊 F1-score
 $F1 = 2 \cdot \frac{Precision \cdot Recall}{Precision + Recall}$

📌 ใช้: balance precision และ recall

## 🧪 6. Evaluation Methods
🔹 Hold-out Method
แบ่ง train/test
🔹 Cross-validation
เช่น k-fold
ลด bias

## ⚠️ 7. Challenges in Classification
🔸 Overfitting

โมเดลจำ training data มากเกินไป

🔸 Underfitting

โมเดลง่ายเกินไป

🔸 Imbalanced Data

class ไม่เท่ากัน

🔸 Feature Selection

เลือก feature ที่สำคัญ

🔸 Noise

ข้อมูลผิดพลาด

## 🧠 8. Applications
- 📧 Spam detection
- 🏥 Medical diagnosis
- 💳 Fraud detection
- 🛒 Customer classification
- 📄 Document classification

## 🎯 9. Summary
- Classification = ทำนาย label
- ใช้ training data
- โมเดลหลัก:
   - Decision Tree
   - Naïve Bayes
   - k-NN
- ใช้ metrics:
   - Accuracy, Precision, Recall, F1

# บทที่ 9 📈 Classification: Advanced Methods
🌟 Overview

Chapter 9 เป็นการต่อยอดจาก Chapter 8 โดยเน้นไปที่ โมเดลที่มีประสิทธิภาพสูงขึ้น (Advanced Classification Models) ซึ่งสามารถจัดการกับข้อมูลที่ซับซ้อนและมีมิติสูงได้ดีกว่า

โมเดลสำคัญในบทนี้:

 - 🌲 Random Forest
 - 🚀 Boosting (AdaBoost)
 - 🧠 Support Vector Machine (SVM)
 - 🤖 Neural Networks

## 🌲 1. Random Forest
🌟 แนวคิด

Random Forest เป็นเทคนิค Ensemble Learning ที่รวมหลาย Decision Trees เพื่อเพิ่มความแม่นยำและลด overfitting

🔧 หลักการทำงาน
 1. สุ่มข้อมูล (Bootstrap Sampling)
 2. สร้าง Decision Tree หลายต้น
 3. สุ่ม feature ตอน split
 4. รวมผลด้วย majority vote

📊 แนวคิดเชิงสูตร (Voting)

   $\hat{y} = \text{mode}(T_1(x), T_2(x), ..., T_n(x))$

→ รวมผลจากหลายโมเดล

## 🚀 2. Boosting (AdaBoost)
🌟 แนวคิด

Boosting คือการรวมโมเดลหลายตัว โดยเน้นเรียนรู้จาก “ความผิดพลาด”

🔧 หลักการ
- เริ่มจาก model ง่าย (weak learner)
- เพิ่มน้ำหนักให้ข้อมูลที่ทำนายผิด
- สร้าง model ใหม่เพื่อแก้ error

### 📊 สูตรรวมโมเดล

   $F(x) = \sum_{i=1}^{n} w_i h_i(x)$

→ รวม weak learners ให้เป็น strong model

### 📊 Error Rate

   $\epsilon = \frac{\text{จำนวนตัวอย่างที่ทำนายผิด}}{\text{จำนวนทั้งหมด}}$

### 📊 Weight Update

   $w_i \leftarrow w_i \cdot e^{\alpha}$

## 🧠 3. Support Vector Machine (SVM)
🌟 แนวคิด

SVM ใช้การหาเส้น (หรือ hyperplane) ที่แยกข้อมูลได้ดีที่สุด

### 📊 สมการ Hyperplane

   $w \cdot x + b = 0$

📌 ใช้: แบ่ง class

### 📊 Margin Maximization

   $\min \frac{1}{2} ||w||^2$

📌 ใช้: ทำให้เส้นแบ่ง “ห่างที่สุด”

🧠 Kernel Trick

ใช้เมื่อข้อมูลไม่สามารถแยกด้วยเส้นตรง

ตัวอย่าง:

- Linear
- Polynomial
- RBF (Radial Basis Function)
  
### 📊 Kernel Function (ตัวอย่าง RBF)

   $K(x, x') = e^{-\gamma ||x - x'||^2}$

## 🤖 4. Neural Networks
🌟 แนวคิด

เลียนแบบการทำงานของสมองมนุษย์ โดยใช้ neuron หลายชั้น

**🧱 โครงสร้าง**
 - Input Layer
 - Hidden Layer
 - Output Layer
   
### 📊 สูตร Neuron
$y = f(wx + b)$

📌 ใช้: คำนวณ output ของ neuron

### 📊 Activation Function (ตัวอย่าง Sigmoid)
$\sigma(x) = \frac{1}{1 + e^{-x}}$

🔁 Backpropagation

ใช้ในการ train model โดย:

 - คำนวณ error
 - ปรับ weight

### 📊 Loss Function (ตัวอย่าง)
$Loss = \frac{1}{n} \sum (y_{true} - y_{pred})^2$

## ⚖️ 5. Comparison of Models
| Model | จุดเด่น | จุดด้อย |
|------|--------|--------|
| Random Forest | ลด overfitting | interpret ยาก |
| Boosting | แม่นยำสูง | sensitive noise |
| SVM | ดีใน high dimension | training ช้า |
| Neural Network | powerful มาก | ใช้ resource สูง |

## ⚠️ 6. Challenges
🔸 Overfitting

โมเดลซับซ้อนเกินไป

🔸 High-dimensional data

feature เยอะ

🔸 Computation cost

ใช้เวลาและ resource สูง

🔸 Parameter tuning

ต้องเลือกค่า hyperparameters

## 🧠 7. Applications
 - 🧠 Image classification
 - 🎤 Speech recognition
 - 💳 Fraud detection
 - 🧬 Bioinformatics
 - 🚗 Autonomous systems

## 🎯 8. Summary
 - ใช้ Ensemble & Advanced Models
 - Random Forest → หลาย tree
 - Boosting → แก้ error
 - SVM → หาเส้นแบ่ง
 - Neural Network → deep learning

# บทที่ 10 🔥 Cluster Analysis
🌟 Overview

Clustering หรือ Cluster Analysis เป็นเทคนิคใน Unsupervised Learning ที่ใช้จัดกลุ่มข้อมูลโดยไม่มี label เป้าหมายคือให้ข้อมูลที่ “คล้ายกัน” อยู่ในกลุ่มเดียวกัน และ “ต่างกัน” อยู่คนละกลุ่ม

📌 แนวคิดหลัก:

- Intra-cluster similarity → สูง
- Inter-cluster similarity → ต่ำ
  
## 🧠 1. Basic Concepts
🔹 Clustering คืออะไร?

การแบ่งข้อมูลออกเป็นกลุ่ม (clusters) โดย:

 - ไม่รู้คำตอบล่วงหน้า
 - ให้ algorithm หา pattern เอง
 - 
🔹 Similarity & Distance

การวัดความเหมือน/ต่างของข้อมูลสำคัญมาก

**📊 Euclidean Distance**

$d(x,y) = \sqrt{\sum_{i=1}^{n} (x_i - y_i)^2}$

📌 ใช้ทำอะไร:
→ วัดระยะห่างระหว่างจุด

📌 ใช้กับ:

 - K-means
 - k-NN
   
## 🔵 2. K-Means Clustering
🌟 แนวคิด

แบ่งข้อมูลออกเป็น k กลุ่ม โดยใช้ centroid เป็นตัวแทน

**🔁 ขั้นตอน**
 1. เลือกจำนวน cluster (k)
 2. สุ่ม centroid
 3. assign จุดเข้ากลุ่ม
 4. update centroid
 5. ทำซ้ำจน converge

**📊 Objective Function (SSE)**

$SSE = \sum_{i=1}^{n} (x_i - c)^2$

📌 ใช้ทำอะไร:
→ วัดความแน่นของ cluster

📌 เป้าหมาย:
→ ทำให้ SSE ต่ำที่สุด

## 🌊 3. Hierarchical Clustering
🌟 แนวคิด

สร้าง cluster แบบลำดับชั้น (tree structure)

🔹 ประเภท

🔼 Agglomerative (Bottom-up)

 - เริ่มจากจุดเดียว
 - รวมกันเรื่อย ๆ
   
🔽 Divisive (Top-down)
 - เริ่มจาก cluster ใหญ่
 - แยกออก
   
**🔗 Linkage Methods**
| Method   | แนวคิด        |
|----------|--------------|
| Single   | ระยะใกล้สุด   |
| Complete | ระยะไกลสุด   |
| Average  | ค่าเฉลี่ย     |

**📊 Distance ตัวอย่าง**
$D(A,B) = \min(d(x,y)) \quad \text{(Single linkage)}$

## 🧠 4. DBSCAN
🌟 แนวคิด

Clustering แบบใช้ density (ความหนาแน่น)

**🔑 Parameters**
eps (ε) → รัศมี

minPts → จำนวนจุดขั้นต่ำ

🔹 ประเภทของจุด
 - Core point
 - Border point
 - Noise point
   
📌 หลักการ

 - จุดที่อยู่ใกล้กันมาก → cluster เดียวกัน
 - จุดโดดเดี่ยว → outlier

## 📏 5. Cluster Evaluation
🔹 Silhouette Score

$s = \frac{b - a}{\max(a, b)}$

📌 โดย:

 - $a$ = ระยะเฉลี่ยใน cluster เดียวกัน
 - $b$ = ระยะเฉลี่ยไป cluster อื่น

**🔹 SSE (ใช้ใน K-means)**

→ ยิ่งต่ำยิ่งดี

## ⚠️ 6. Challenges in Clustering
🔸 Choosing k

เลือกจำนวน cluster ยาก

🔸 High-dimensional Data

distance ใช้ยาก

🔸 Noise & Outliers

ข้อมูลผิดปกติ

🔸 Arbitrary Shape

cluster รูปร่างไม่แน่นอน

🔸 Scalability

ข้อมูลขนาดใหญ่

## 🧠 7. Applications
 - 🛒 Customer Segmentation
 - 🖼️ Image Segmentation
 - 🌐 Social Network Analysis
 - 🧬 Bioinformatics
 - 📊 Data Exploration
   
## ⚖️ 8. Comparison of Methods
| Method | จุดเด่น | จุดด้อย |
|--------|--------|--------|
| K-Means | เร็ว ใช้ง่าย | ต้องกำหนด k |
| Hierarchical | ไม่ต้องกำหนด k | ช้า |
| DBSCAN | หา outlier ได้ | เลือก eps ยาก |

## 🎯 9. Summary
 - Clustering = จัดกลุ่มไม่มี label
 - K-means → centroid-based
 - Hierarchical → tree-based
 - DBSCAN → density-based
 - ใช้ distance เป็นหัวใจ






