| Feature                            | Meaning                                                 | Typical Healthy Range (Approx.) | What Abnormal Values Suggest (General Knowledge Only)   |
| ---------------------------------- | ------------------------------------------------------- | ------------------------------- | ------------------------------------------------------- |
| **Age**                            | Patient age                                             | Adults: variable                | Higher age sometimes correlates with chronic conditions |
| **Gender**                         | Male/Female (encoded 0/1)                               | —                               | Some markers differ by gender                     |
| **TB – Total Bilirubin**           | Breakdown product of red blood cells processed by liver | **0.1 – 1.2 mg/dL**             | High → jaundice, obstruction, hepatitis, cirrhosis      |
| **DB – Direct Bilirubin**          | Conjugated bilirubin                                    | **0.0 – 0.3 mg/dL**             | High → cholestasis, liver damage                        |
| **Alkphos – Alkaline Phosphatase** | Enzyme linked to bile ducts (Enzyme)                             | **44 – 147 U/L**                | High → bile duct obstruction, cirrhosis, cholestasis    |
| **Sgpt (ALT)**                     | Alanine Aminotransferase (Enzyme)                                | **7 – 56 U/L**                  | High → hepatocellular injury (hepatitis, fatty liver)   |
| **Sgot (AST)**                     | Aspartate Aminotransferase  (Enzyme)                            | **8 – 48 U/L**                  | High → hepatitis, alcohol-related injury                |
| **TP – Total Protein**             | Albumin + Globulin      Protein (Albumin + Globulin)                                | **6.3 – 8.2 g/dL**              | Low → chronic liver disease, cirrhosis                  |
| **ALB – Albumin**                  | Produced by liver (Protein (synthesis marker))                                      | **3.5 – 5.5 g/dL**              | Low → chronic liver disease, cirrhosis                  |
| **A/G Ratio**                      | Albumin/Globulin Ratio                                  | **1.1 – 2.2**                   | Low → cirrhosis, chronic inflammation                   |
| **Dataset Label**                  | 1 = Diseased, 0 = Non-diseased                          | —                               | —                                                       |


Markers for testing: 
| Feature        | Normal Range | Cirrhosis Indication                |
| -------------- | ------------ | ----------------------------------- |
| **Age**        | —            | >50 higher risk                     |
| **TB**         | 0.1–1.2      | >3 (moderate), >10 (severe)         |
| **DB**         | 0–0.3        | >1 (strong), >3 (severe)            |
| **Alkphos**    | 44–147       | >200 (cholestasis), >400 (advanced) |
| **ALT (Sgpt)** | 7–40         | >200 (injury, not specific)         |
| **AST (Sgot)** | 10–40        | AST/ALT >2 → alcoholic cirrhosis    |
| **TP**         | 6.0–8.3      | <6 may indicate reduced function    |
| **ALB**        | 3.4–5.4      | <3.4 (strong), <2.8 (advanced)      |
| **A/G Ratio**  | 1.0–2.5      | <1.0 (classic cirrhosis sign)       |
