# DWDM21
Data Warehouse &amp; Data Mining 2021
Data Warehouse & Data Mining 2021

Chanakarn Poonpol 6230210467

Group Name: Natasha Romanoff

1 ฐิติวัฒน์ จันทรเสนา 623021047-5

2 ขนิษฐา ภูโสภา 623021042-5	

3 จิตติยา ศิริธรรมจักร 623021043-3

4 จุฑากาญจน์ ชิงจันทร์ 623020514-5

5 ชนกานต์ พูลผล 623021046-7	

##  สารบัญเนื้อหา
วิชา Data Mining and Data Warehouse
* บทที่ 1 Introduction https://github.com/Chanakarn06/DWDM21/blob/main/HW1%20Chapter1
  
   * ทำไมต้องมีการทำเหมืองข้อมูล (Why Data Mining?)

   * อะไรคือเหมืองข้อมูล (What Is Data Mining?)

   * มุมมองหลายมิติของเหมืองข้อมูล (A Multi-Dimensional View of Data Mining)

   * สามารถขุดเเหมืองข้อมูลที่ไหนได้บ้าง (What Kinds of Data Can Be Mined?)

   * รูปแบบหรือทิศทางของข้อมูล (What Kinds of Patterns Can Be Mined?)

   * ใช้เทคโนโลยีประเภทใด? (What Kinds of Technologies Are Used?)

   * แอพพลิเคชั่นเป้าหมาย(What Kinds of Applications Are Targeted?)

   * ความสำคัญในการทำเหมือง(Major Issues in Data Mining)

   * ประวัติความเป็นมา(A Brief History of Data Mining and Data Mining Society)

   * สรุป (Summary)
   
 * บทที่ 2 Getting to Know Your Data 
  
   * Basic Python https://github.com/Chanakarn06/DWDM21/blob/main/Data101(Chapter2).ipynb

      *  การ Casting int() float() str()
      *  Data Structure list() #ตัวเลขหรือตัวแปล
      *  วิธีการสร้าง listt ว่าง
      *  เติมค่าลงไปใน list (.append())
      *  การชี้ค่าใน list
      *  list + list
      *  Loop
      *  Nested loop
      *  Condition (if statement)
      *  Function
      *  Quiz4 11.05 27/07/2021 สร้างฟังก์ชั่น,วาดรูปบ้าน,วาดรูปต้นไม้

    * Plot Data https://github.com/Chanakarn06/DWDM21/blob/main/Data102_(Chapter2).ipynb
    
      * Besic Data
 
      * การตรวจสอบตารางข้อมูลโดยใช้ .head()&.tail()
 
      * Boxplot
 
      * Time Series Plot

     * Visualizetion https://github.com/Chanakarn06/DWDM21/blob/main/Data_Visualization.ipynb
     
       *  Scatter plot
       *  Plot
       *  Bar chart (Grouped Barchart)
       *  Stacked Barchart
       *  Histogram
       
     * Distance Numpy https://github.com/Chanakarn06/DWDM21/blob/main/Distance_Numpy.ipynb
     
       * Numpy Array
       * สร้าง numpy array (matrix) จาก list
       * สร้าง matrix เริ่มต้น (zeros, ones)
       * สร้าง matrix random
       * matrix properties
       * Indexing & Slicing
       * useful functions
       * วนลูปเอง summation
       * np.sum(np_a,axis=0)
       * Distance Matrix
       * Euclidean Distance (L2-norm)
       * Distance function
       * Manhattan Distance (L1-norm)
       * quiz6 เขียน function คำนวณ manhattan distance ของ ข้อมูล 2 dimensions
       * HW11
       * Distance of Binary Value -Create Table
    
* บทที่3 https://github.com/Chanakarn06/DWDM21/blob/main/Data_Preprocessing(Chapter_3).ipynb
  
  * Meta Data (Data ที่ใช้อธิบาย Data) การจัดการข้อมูลในตารางก่อนนำไปวิเคราะห์
  
     *  ชี้แบบธรรมดา ใช้ [ชื่ออ column][index]
     *  ชี้แบบ .iloc[] (มองข้อมูลเป็น matrix)
     *  Missing Values
     *  Handlind Missing Value 1 (ลบค่า missing)
        *  Quiz 3 หาว่า การทำ dropna() ทำให้ข้อมูลหายไปกี่ %
     *  Handling Missing Value 1.5 (ลบค่า Missing เฉพาะใน column ที่เราสนใจ)
        *  Quiz 3.1 ให้หาว่า การทำ dropna() แบบเลือก drop เฉพาะ column ที่เราสนใจ ทำให้ข้อมูลหายไปกี่ %
     *  Handling Missing Value 2 (แทนด้วย class ใหม่ (unknown)
     *  Handling Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
     *  Handling Missing Value 4 (แทนด้วย ค่ากลาง)
     *  Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน)
     *  Select data by values [PD]
     *  การเลือก record สามารถเลือกโดยใช้ list ของ boolean(ความยาวของ list เท่ากับ จำนวน record)
     *  ชื่อตาราง[list ของ boolean]
     *  สร้าง list ของ boolean
     *  เอาค่า mean ไปติมตรง missing column 'age'
     *  เติมค่า mean แทน missimg ของเชียงใหม่
     *  ต่อตารางแนวแกน Y [PD]
     *  Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน) ต่อ
     *  การเรียงข้อมูล [PD]
     *  outlier
     *  HW8 + Quiz 5
     *  Pandas' looping(.iterrows)
     *  [PD] save ตารางเอาไปใช้ที่อื่น
     *  [PD] save ตารางเอาไปใช้ที่อื่น

* บทที่4 https://github.com/Chanakarn06/DWDM21/blob/main/%E0%B8%9A%E0%B8%974.pdf

  * Basic Data Warehouse
        
      * อะไรคือคลังข้อมูล
      * วัตถุประสงค์
      * การบูรณาการ

  * Data Cube and OLAP

     * OLTP vs. OLAP
     * Data Cubes
     * Conceptual Modeling of Data Warehouse
    
  * การออกแบบ และการใช้งานคลังข้อมูล 
  * ความสำคัญของคลังข้อมูล 

* บทที่5 Association_Rules https://github.com/Chanakarn06/DWDM21/blob/main/Chapter6_Association_Rules.ipynb
  
  *  การลบ records ที่ถูก cancel ออกไป
  *  Basic concepts

     *  มีประเทศสาขาของ supermarket นี้ทั้งหมดกี่ประเทศ
     *  [HW13] วาดกราฟสรุปจำนวน items และ ยอดขายของแต่ละประเทศ
     *  เตรียม Data สำหรับ (Fequence Pattern) Association Rule
  *  Apriori
  
*  บทที่6 Classification 

   *  Desition Tree https://github.com/Chanakarn06/DWDM21/blob/main/Chapter7_Classification_(Decision).ipynb
      *   Load Data
      *   Train Model
      *   import (เรียกใช้ algolithm ที่เราต้องการ)
      *   define (กำหนด parameters ให้กับ model)
      *   train (ตัวแบบฝึกสอน)
      *   plot tree
      *   Evaluation
      *   Random
      *   Advanced Tree
      *   TEST
      *   Start here
      *   HW
      
   * KNN https://github.com/Chanakarn06/DWDM21/blob/main/Chap7_Classification_(KNN_NN).ipynb
     *  Load data
     *  Split Data
     *  Train Model
     *  knn1
     *  knn2
     *  knn3
     *  Retrain & Evaluate
     *  Neural Network
     *  ANN 2
     *  ANN 3
   
    * Evaluation  https://github.com/Chanakarn06/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb
      *  Load data
      *  แบ่ง Data
      *  สร้าง Model ทำนาย
      
 * บทที่7 Clustering https://github.com/Chanakarn06/DWDM21/blob/main/Chap8_Clustering.ipynb
 
    * K-means
    * Generate Data
    
    * Explore data
    * Clustering
        * Import
        * Define
        * Fit-Predict

     * Example Application(Color Quantization)
        * นับจำนวนสี
        * ใช้ centorid เป็นตัวแทนของสี
  
* เอกสารประกอบ https://github.com/Chanakarn06/DWDM21/blob/main/Chapter%208%20Nai%CC%88ve%20Bayes%20Classifier.pdf
* Project กลุ่ม Natasha   https://github.com/Chanakarn06/DWDM21/blob/main/Project.ipynb
* Project กลุ่ม Natasha สไลด์ https://github.com/Chanakarn06/DWDM21/blob/main/Project.pdf
     
