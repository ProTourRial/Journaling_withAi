# Zero Error Reviewer Skill

**AI Academic Manuscript Review Skill for Structured, Evidence Based, and Traceable Research Quality Assurance**

Zero Error Reviewer is a `.skill` package for AI assisted academic manuscript review. It helps review research papers, journal articles, theses, dissertations, proposals, and conference papers through a structured workflow based on evidence, academic writing rules, citation standards, and manuscript quality control.

> Copyright © 2026 Abia Nugrahanto. All rights reserved.

---

## Repository Description

Zero Error Reviewer is designed to support academic reviewers, researchers, lecturers, students, journal editors, and research teams in reviewing scholarly manuscripts with higher consistency and traceability.

This repository contains a reusable AI skill package that guides manuscript review across several critical dimensions:

* IMRaD structure validation
* APA 7th Edition citation checking
* IEEE citation checking
* Data consistency review
* Methodology completeness review
* Results and discussion alignment
* Reference list consistency
* Ambiguity detection
* Evidence based review reporting
* Academic quality assurance

The purpose of this skill is not to replace human academic judgment. It supports reviewers by identifying structural, logical, citation, and consistency issues that may reduce manuscript quality before journal submission, thesis defense, proposal review, or internal academic evaluation.

---

## Package Structure

```text
zero-error-reviewer.skill
├── SKILL.md
├── references/
│   ├── APA7_essentials.md
│   ├── IEEE_essentials.md
│   └── IMRaD_structure.md
├── templates/
│   └── review_report_template.md
└── scripts/
```

---

## Core Files

### `SKILL.md`

The main instruction file. It defines the identity, purpose, workflow, principles, and review behavior of Zero Error Reviewer.

This file instructs the AI to review manuscripts based on:

* Verifiable evidence from the manuscript
* Explicit academic writing standards
* Structured review categories
* Transparent reasoning
* Clear reviewer feedback
* Non speculative conclusions

The skill is designed to avoid unsupported claims. Every review finding must be grounded in text evidence, citation rules, manuscript logic, or academic structure requirements.

---

### `references/APA7_essentials.md`

A concise reference guide for APA 7th Edition formatting and citation review.

It supports checking:

* In text citation format
* Author and year citation patterns
* Use of `et al.`
* Reference list format
* Journal article references
* Book references
* DOI and URL presentation
* Citation and reference matching
* Font, spacing, margin, and general formatting rules

This file helps the AI detect citation inconsistencies, missing reference entries, incomplete bibliographic details, and formatting problems in APA based manuscripts.

---

### `references/IEEE_essentials.md`

A practical reference guide for IEEE citation style.

It supports checking:

* Numbered citation format
* Citation order
* Bracketed citation style
* Journal article format
* Book format
* Conference proceeding format
* Reference list sequencing
* Missing or mismatched citations

This file is useful for engineering, computer science, technology, and applied science manuscripts that use IEEE citation rules.

---

### `references/IMRaD_structure.md`

A structural guide for reviewing academic manuscripts that follow the IMRaD model.

IMRaD stands for:

* Introduction
* Methods
* Results
* Discussion

This file helps evaluate whether a manuscript contains a clear research background, research gap, objectives, replicable methods, objective results, strong discussion, and evidence based conclusions.

It can detect issues such as:

* Missing research gap
* Weak problem statement
* Unclear research objective
* Incomplete method description
* Non replicable procedure
* Results mixed with interpretation
* Discussion not linked to findings
* Conclusion not supported by data

---

### `templates/review_report_template.md`

A structured template for producing review reports.

The template organizes findings into clear categories:

* `[Pasti]` for findings supported by strong evidence
* `[Perlu Verifikasi]` for findings that require clarification
* `[Tidak Dapat Disimpulkan]` for issues that cannot be judged due to insufficient information

This format makes the review process more transparent, auditable, and useful for academic revision.

---

## Main Functions

### 1. Academic Structure Validation

Zero Error Reviewer checks whether a manuscript follows a logical academic structure. It evaluates whether the introduction explains the research background, identifies a research gap, states the problem, and presents clear objectives.

It also checks whether the methods, results, discussion, and conclusion are connected in a coherent research flow.

---

### 2. IMRaD Review

The skill evaluates each IMRaD component in detail.

It checks whether:

* The introduction builds a clear rationale
* The methods are specific and replicable
* The results present findings objectively
* The discussion interprets results with literature support
* The conclusion answers the research objectives

This function is useful for journal articles, theses, dissertations, and research proposals.

---

### 3. Citation and Reference Checking

Zero Error Reviewer supports both APA 7th Edition and IEEE citation review.

It checks whether:

* Every in text citation appears in the reference list
* Every reference is cited in the manuscript
* Citation style is consistent
* Reference elements are complete
* Author names, years, titles, journals, volumes, issues, pages, DOI, and URLs are formatted correctly
* IEEE references follow citation order

This helps reduce reference errors before submission.

---

### 4. Data Consistency Review

The skill identifies contradictions across manuscript sections.

It can detect inconsistencies in:

* Sample size
* Participant count
* Research variables
* Statistical values
* Units of measurement
* Tables and figures
* Findings and claims
* Abstract and results
* Methods and analysis

For example, if the methods section states that the study used 200 samples but the results section reports only 195 analyzed samples without explanation, the skill will flag the issue for verification.

---

### 5. Methodology Completeness Review

Zero Error Reviewer checks whether the methodology section provides enough detail for replication.

It reviews whether the manuscript explains:

* Research design
* Population and sample
* Sampling technique
* Instruments
* Data collection procedure
* Data analysis method
* Validity and reliability
* Ethical considerations, when relevant

This is important because unclear methods reduce research credibility and make the study difficult to evaluate.

---

### 6. Results and Discussion Alignment

The skill checks whether the discussion actually explains the results.

It identifies problems such as:

* Results repeated without interpretation
* Discussion not connected to research questions
* Literature not used to support interpretation
* Claims that exceed the data
* Conclusion introduced without evidence
* Contradiction between findings and final statements

This helps improve the analytical depth of academic manuscripts.

---

### 7. Ambiguity Detection

Zero Error Reviewer detects unclear academic writing.

It can flag:

* Vague claims
* Undefined terms
* Inconsistent terminology
* Ambiguous sentences
* Unsupported causal statements
* Overgeneralized conclusions
* Statements that require additional evidence

This function helps improve clarity, precision, and academic readability.

---

### 8. Evidence Based Review Reporting

The skill is designed to produce review findings that are traceable.

Each finding should be connected to:

* A specific part of the manuscript
* A clear academic rule
* A citation style requirement
* A structural writing principle
* A consistency issue found across sections

This makes the review more reliable than general writing feedback.

---

## Use Cases

Zero Error Reviewer can be used for:

* Journal manuscript review
* Thesis checking
* Dissertation checking
* Undergraduate research review
* Master thesis review
* Doctoral research review
* Conference paper preparation
* Research proposal validation
* Pre submission journal screening
* Internal academic quality assurance
* APA 7 citation checking
* IEEE citation checking
* IMRaD validation
* Editorial workflow support
* Research writing improvement
* Academic manuscript quality control

---

## Recommended Users

This skill is suitable for:

* Students preparing final projects, theses, or dissertations
* Lecturers reviewing student research
* Researchers preparing journal submissions
* Journal editors conducting initial screening
* Academic writing consultants
* Research groups and laboratories
* Universities and academic institutions
* AI workflow builders for academic review systems

---

## How to Use

1. Upload or install the `zero-error-reviewer.skill` package into a compatible AI skill environment.
2. Provide the manuscript that needs to be reviewed.
3. Specify the required review focus, such as IMRaD, APA 7, IEEE, methodology, data consistency, or complete manuscript review.
4. Run the review process.
5. Use the generated findings to revise the manuscript.
6. Recheck the revised manuscript if needed.

Example instruction:

```text
Review this manuscript using Zero Error Reviewer. Focus on IMRaD structure, APA 7 citation consistency, data consistency, methodology completeness, and unsupported claims.
```

---

## Example Review Focus

You can ask the skill to check:

```text
Check whether the introduction contains a clear research gap.
```

```text
Review the consistency between sample size, method, results, tables, and conclusion.
```

```text
Check all APA 7 in text citations and references.
```

```text
Review this manuscript using IMRaD structure.
```

```text
Find unsupported claims and ambiguous academic statements.
```

---

## Why This Skill Matters

Many academic manuscripts fail because of preventable issues. Common problems include unclear research gaps, incomplete methods, inconsistent data, weak discussion, missing references, incorrect citation style, and conclusions that are not supported by findings.

Zero Error Reviewer helps reduce these risks. It guides AI to review manuscripts through structured criteria and evidence based reporting. This allows authors and reviewers to identify problems earlier and improve manuscript quality before submission.

---

## Bahasa Indonesia

## Gambaran Umum

Zero Error Reviewer adalah paket `.skill` untuk membantu review naskah akademik berbasis AI. Skill ini dirancang untuk memeriksa artikel jurnal, skripsi, tesis, disertasi, proposal penelitian, dan makalah konferensi secara sistematis, berbasis bukti, dan mengikuti kaidah penulisan ilmiah.

Skill ini membantu peneliti, dosen, mahasiswa, editor jurnal, pengelola jurnal, dan reviewer akademik dalam mengevaluasi kualitas naskah dengan lebih konsisten.

Fokus utama skill ini meliputi:

* Struktur IMRaD
* Sitasi APA 7th Edition
* Sitasi IEEE
* Konsistensi data
* Kelengkapan metode
* Kesesuaian hasil dan pembahasan
* Konsistensi daftar pustaka
* Deteksi ambiguitas
* Laporan review berbasis bukti
* Quality assurance akademik

Skill ini tidak menggantikan penilaian akademik manusia. Skill ini berfungsi sebagai alat bantu untuk menemukan masalah struktural, logis, teknis, dan sitasi sebelum naskah dikirim ke dosen pembimbing, penguji, konferensi, repository institusi, atau jurnal ilmiah.

---

## Isi Paket

```text
zero-error-reviewer.skill
├── SKILL.md
├── references/
│   ├── APA7_essentials.md
│   ├── IEEE_essentials.md
│   └── IMRaD_structure.md
├── templates/
│   └── review_report_template.md
└── scripts/
```

---

## Penjelasan File

### `SKILL.md`

File instruksi utama yang mendefinisikan identitas, tujuan, prinsip, alur kerja, dan perilaku review Zero Error Reviewer.

File ini mengarahkan AI untuk menilai naskah berdasarkan:

* Bukti dari teks naskah
* Aturan akademik yang jelas
* Kategori temuan yang terstruktur
* Umpan balik yang dapat ditelusuri
* Kesimpulan yang tidak spekulatif

---

### `references/APA7_essentials.md`

Panduan ringkas untuk pemeriksaan sitasi dan referensi APA 7th Edition.

File ini membantu memeriksa:

* Format sitasi dalam teks
* Pola penulis dan tahun
* Penggunaan `et al.`
* Format daftar pustaka
* Referensi artikel jurnal
* Referensi buku
* DOI dan URL
* Kesesuaian sitasi dan daftar pustaka
* Aturan dasar margin, spasi, font, dan format dokumen

---

### `references/IEEE_essentials.md`

Panduan ringkas untuk pemeriksaan sitasi IEEE.

File ini membantu memeriksa:

* Format sitasi numerik
* Urutan sitasi
* Penggunaan kurung siku
* Format artikel jurnal
* Format buku
* Format prosiding
* Urutan daftar pustaka
* Sitasi yang hilang atau tidak sesuai

---

### `references/IMRaD_structure.md`

Panduan untuk mengevaluasi struktur Introduction, Methods, Results, and Discussion.

File ini membantu mendeteksi:

* Gap penelitian yang belum jelas
* Rumusan masalah yang lemah
* Tujuan penelitian yang belum spesifik
* Metode yang tidak replikatif
* Hasil yang bercampur dengan interpretasi
* Pembahasan yang tidak terhubung dengan hasil
* Kesimpulan yang tidak didukung data

---

### `templates/review_report_template.md`

Template laporan review naskah.

Template ini membagi temuan menjadi tiga kategori:

* `[Pasti]` untuk temuan yang didukung bukti kuat
* `[Perlu Verifikasi]` untuk temuan yang membutuhkan klarifikasi
* `[Tidak Dapat Disimpulkan]` untuk bagian yang tidak dapat dinilai karena informasi tidak cukup

---

## Fungsi Utama

### 1. Validasi Struktur Akademik

Skill ini memeriksa apakah naskah memiliki struktur akademik yang logis. Pemeriksaan mencakup latar belakang, gap penelitian, rumusan masalah, tujuan penelitian, metode, hasil, pembahasan, dan kesimpulan.

---

### 2. Review IMRaD

Skill ini mengevaluasi setiap bagian IMRaD secara lebih rinci.

Pemeriksaan meliputi:

* Introduction menjelaskan alasan penelitian
* Methods cukup jelas untuk direplikasi
* Results menyajikan temuan secara objektif
* Discussion menafsirkan hasil dengan dukungan literatur
* Conclusion menjawab tujuan penelitian

---

### 3. Pemeriksaan Sitasi dan Referensi

Zero Error Reviewer mendukung pemeriksaan APA 7th Edition dan IEEE.

Skill ini memeriksa apakah:

* Sitasi dalam teks ada di daftar pustaka
* Daftar pustaka benar benar dikutip dalam naskah
* Gaya sitasi konsisten
* Elemen referensi lengkap
* Format referensi sesuai gaya yang digunakan
* Urutan referensi IEEE mengikuti kemunculan sitasi dalam teks

---

### 4. Pemeriksaan Konsistensi Data

Skill ini mendeteksi kontradiksi antarbagian naskah.

Contoh aspek yang diperiksa:

* Jumlah sampel
* Jumlah responden
* Variabel penelitian
* Nilai statistik
* Satuan ukuran
* Tabel dan gambar
* Klaim penelitian
* Abstrak dan hasil
* Metode dan analisis

---

### 5. Pemeriksaan Kelengkapan Metode

Skill ini memeriksa apakah metode penelitian cukup jelas untuk dipahami dan direplikasi.

Aspek yang ditinjau meliputi:

* Desain penelitian
* Populasi dan sampel
* Teknik sampling
* Instrumen
* Prosedur pengumpulan data
* Metode analisis data
* Validitas dan reliabilitas
* Etika penelitian jika relevan

---

### 6. Keselarasan Hasil dan Pembahasan

Skill ini menilai apakah pembahasan benar benar menjelaskan hasil.

Masalah yang dapat dideteksi:

* Pembahasan hanya mengulang hasil
* Pembahasan tidak menjawab rumusan masalah
* Literatur tidak digunakan untuk mendukung interpretasi
* Klaim melebihi data
* Kesimpulan tidak sesuai hasil

---

### 7. Deteksi Ambiguitas

Skill ini membantu menemukan kalimat yang kurang jelas.

Contohnya:

* Klaim terlalu umum
* Istilah belum didefinisikan
* Terminologi tidak konsisten
* Kalimat multitafsir
* Pernyataan sebab akibat tanpa bukti
* Kesimpulan terlalu luas

---

### 8. Pelaporan Berbasis Bukti

Setiap temuan review harus memiliki dasar yang jelas.

Dasar temuan dapat berasal dari:

* Bagian tertentu dalam naskah
* Aturan sitasi
* Prinsip struktur akademik
* Masalah konsistensi antarbagian
* Kaidah penulisan ilmiah

Hal ini membuat hasil review lebih transparan, dapat ditelusuri, dan mudah diaudit.

---

## Kegunaan

Zero Error Reviewer dapat digunakan untuk:

* Review artikel jurnal
* Pemeriksaan skripsi
* Pemeriksaan tesis
* Pemeriksaan disertasi
* Review makalah mahasiswa
* Persiapan artikel konferensi
* Validasi proposal penelitian
* Screening naskah sebelum submit jurnal
* Quality assurance akademik internal
* Pemeriksaan sitasi APA 7
* Pemeriksaan sitasi IEEE
* Validasi struktur IMRaD
* Dukungan workflow editorial
* Perbaikan tulisan ilmiah

---

## Pengguna yang Direkomendasikan

Skill ini cocok untuk:

* Mahasiswa tingkat akhir
* Dosen pembimbing
* Dosen penguji
* Peneliti
* Editor jurnal
* Pengelola jurnal
* Konsultan penulisan akademik
* Tim riset
* Institusi pendidikan tinggi

---

## Cara Menggunakan

1. Upload atau pasang file `zero-error-reviewer.skill` pada environment AI yang mendukung skill.
2. Masukkan naskah yang ingin diperiksa.
3. Tentukan fokus review, seperti IMRaD, APA 7, IEEE, metode, konsistensi data, atau review lengkap.
4. Jalankan proses review.
5. Gunakan hasil temuan untuk merevisi naskah.
6. Lakukan pengecekan ulang setelah revisi jika diperlukan.

Contoh instruksi:

```text
Review naskah ini menggunakan Zero Error Reviewer. Fokus pada struktur IMRaD, konsistensi sitasi APA 7, konsistensi data, kelengkapan metode, dan klaim yang belum didukung bukti.
```

---

## Mengapa Skill Ini Penting

Banyak naskah akademik gagal bukan karena topiknya buruk, tetapi karena masalah teknis yang sebenarnya bisa diperbaiki. Masalah umum meliputi gap penelitian yang tidak jelas, metode tidak lengkap, data tidak konsisten, pembahasan lemah, referensi tidak rapi, sitasi tidak sesuai, dan kesimpulan yang tidak didukung hasil.

Zero Error Reviewer membantu mengurangi risiko tersebut melalui proses review yang terstruktur, berbasis bukti, dan dapat ditelusuri.

---

## العربية

## نظرة عامة

Zero Error Reviewer هو ملف مهارة بصيغة `.skill` لدعم مراجعة المخطوطات الأكاديمية باستخدام الذكاء الاصطناعي. صمم هذا الملف لمساعدة المستخدمين في فحص المقالات العلمية، الرسائل الجامعية، رسائل الماجستير، أطروحات الدكتوراه، المقترحات البحثية، وأوراق المؤتمرات بطريقة منظمة وقائمة على الأدلة.

تساعد هذه المهارة الباحثين، المحاضرين، الطلاب، محرري المجلات، ومديري النشر الأكاديمي على مراجعة جودة المخطوطات بدرجة أعلى من الاتساق.

تركز المهارة على:

* بنية IMRaD
* استشهادات APA 7th Edition
* استشهادات IEEE
* اتساق البيانات
* اكتمال المنهجية
* توافق النتائج والمناقشة
* اتساق قائمة المراجع
* كشف الغموض
* تقارير مراجعة قائمة على الأدلة
* ضمان الجودة الأكاديمية

لا تهدف هذه المهارة إلى استبدال الحكم الأكاديمي البشري. بل تعمل كأداة مساعدة لاكتشاف الأخطاء البنيوية والمنطقية والفنية وأخطاء الاستشهاد قبل إرسال المخطوط إلى المشرف، الممتحن، المؤتمر، المستودع المؤسسي، أو المجلة العلمية.

---

## محتويات الحزمة

```text
zero-error-reviewer.skill
├── SKILL.md
├── references/
│   ├── APA7_essentials.md
│   ├── IEEE_essentials.md
│   └── IMRaD_structure.md
├── templates/
│   └── review_report_template.md
└── scripts/
```

---

## شرح الملفات

### `SKILL.md`

ملف التعليمات الرئيسي. يحدد هوية المهارة، هدفها، مبادئها، سير العمل، وطريقة تنفيذ المراجعة.

يوجه هذا الملف الذكاء الاصطناعي إلى مراجعة المخطوطات بناء على:

* أدلة من نص المخطوط
* قواعد أكاديمية واضحة
* تصنيف منظم للملاحظات
* ملاحظات قابلة للتتبع
* استنتاجات غير تخمينية

---

### `references/APA7_essentials.md`

دليل مختصر لفحص الاستشهادات والمراجع وفق APA 7th Edition.

يساعد هذا الملف في مراجعة:

* تنسيق الاستشهاد داخل النص
* نمط المؤلف والسنة
* استخدام `et al.`
* تنسيق قائمة المراجع
* مراجع المقالات العلمية
* مراجع الكتب
* DOI و URL
* توافق الاستشهادات مع قائمة المراجع

---

### `references/IEEE_essentials.md`

دليل مختصر لفحص الاستشهادات وفق نمط IEEE.

يساعد هذا الملف في مراجعة:

* الاستشهاد الرقمي
* ترتيب الاستشهادات
* استخدام الأقواس المربعة
* تنسيق مقالات المجلات
* تنسيق الكتب
* تنسيق أوراق المؤتمرات
* ترتيب قائمة المراجع
* الاستشهادات المفقودة أو غير المتطابقة

---

### `references/IMRaD_structure.md`

دليل لتقييم بنية Introduction, Methods, Results, and Discussion.

يساعد هذا الملف في كشف:

* غياب فجوة البحث
* ضعف صياغة المشكلة
* عدم وضوح أهداف البحث
* منهجية غير قابلة للتكرار
* اختلاط النتائج بالتفسير
* مناقشة غير مرتبطة بالنتائج
* استنتاجات غير مدعومة بالبيانات

---

### `templates/review_report_template.md`

قالب لتقرير مراجعة المخطوط.

يقسم القالب الملاحظات إلى ثلاث فئات:

* `[Pasti]` للملاحظات المدعومة بأدلة قوية
* `[Perlu Verifikasi]` للملاحظات التي تحتاج إلى تحقق إضافي
* `[Tidak Dapat Disimpulkan]` للحالات التي لا يمكن الحكم عليها بسبب نقص المعلومات

---

## الوظائف الرئيسية

### 1. التحقق من البنية الأكاديمية

تفحص المهارة ما إذا كان المخطوط يمتلك بنية أكاديمية منطقية. يشمل ذلك الخلفية، فجوة البحث، مشكلة البحث، أهداف البحث، المنهجية، النتائج، المناقشة، والاستنتاج.

---

### 2. مراجعة IMRaD

تقيم المهارة كل جزء من بنية IMRaD بشكل تفصيلي.

ويشمل ذلك:

* المقدمة تشرح سبب إجراء البحث
* المنهجية واضحة وقابلة للتكرار
* النتائج تعرض البيانات بموضوعية
* المناقشة تفسر النتائج بدعم من الأدبيات
* الاستنتاج يجيب عن أهداف البحث

---

### 3. فحص الاستشهادات والمراجع

تدعم Zero Error Reviewer مراجعة APA 7th Edition وIEEE.

تفحص المهارة ما إذا كانت:

* الاستشهادات داخل النص موجودة في قائمة المراجع
* المراجع في القائمة مستخدمة داخل النص
* طريقة الاستشهاد متسقة
* عناصر المراجع مكتملة
* تنسيق المراجع مطابقا للنمط المستخدم
* ترتيب مراجع IEEE يتبع ظهور الاستشهادات في النص

---

### 4. مراجعة اتساق البيانات

تكشف المهارة التناقضات بين أقسام المخطوط.

تشمل الجوانب التي تتم مراجعتها:

* عدد العينات
* عدد المشاركين
* المتغيرات البحثية
* القيم الإحصائية
* وحدات القياس
* الجداول والأشكال
* الادعاءات البحثية
* الملخص والنتائج
* المنهجية والتحليل

---

### 5. مراجعة اكتمال المنهجية

تفحص المهارة ما إذا كانت المنهجية واضحة بما يكفي للفهم والتكرار.

تشمل الجوانب التي تتم مراجعتها:

* تصميم البحث
* المجتمع والعينة
* أسلوب اختيار العينة
* أدوات البحث
* إجراءات جمع البيانات
* طريقة تحليل البيانات
* الصدق والثبات
* أخلاقيات البحث عند الحاجة

---

### 6. توافق النتائج والمناقشة

تقيم المهارة ما إذا كانت المناقشة تشرح النتائج بشكل صحيح.

يمكنها كشف مشكلات مثل:

* المناقشة تكرر النتائج فقط
* المناقشة لا تجيب عن أسئلة البحث
* الأدبيات لا تدعم التفسير
* الادعاءات تتجاوز البيانات
* الاستنتاجات لا تتوافق مع النتائج

---

### 7. كشف الغموض

تساعد المهارة في كشف الجمل غير الواضحة.

ومن أمثلتها:

* ادعاءات عامة جدا
* مصطلحات غير معرفة
* مصطلحات غير متسقة
* جمل متعددة المعنى
* علاقات سببية دون دليل
* استنتاجات واسعة جدا

---

### 8. التقرير القائم على الأدلة

يجب أن تستند كل ملاحظة في المراجعة إلى أساس واضح.

قد يكون هذا الأساس:

* جزءا محددا من المخطوط
* قاعدة استشهاد
* مبدأ في البنية الأكاديمية
* مشكلة اتساق بين الأقسام
* قاعدة من قواعد الكتابة العلمية

هذا يجعل تقرير المراجعة أكثر شفافية وقابلية للتتبع.

---

## حالات الاستخدام

يمكن استخدام Zero Error Reviewer في:

* مراجعة المقالات العلمية
* فحص الرسائل الجامعية
* فحص رسائل الماجستير
* فحص أطروحات الدكتوراه
* مراجعة أوراق الطلاب
* إعداد أوراق المؤتمرات
* التحقق من المقترحات البحثية
* فحص المخطوط قبل إرساله إلى مجلة
* ضمان الجودة الأكاديمية داخل المؤسسات
* مراجعة استشهادات APA 7
* مراجعة استشهادات IEEE
* التحقق من بنية IMRaD
* دعم سير العمل التحريري
* تحسين الكتابة الأكاديمية

---

## المستخدمون المستهدفون

هذه المهارة مناسبة لـ:

* الطلاب في المرحلة النهائية
* المشرفين الأكاديميين
* الممتحنين
* الباحثين
* محرري المجلات
* مديري المجلات
* مستشاري الكتابة الأكاديمية
* فرق البحث
* مؤسسات التعليم العالي

---

## طريقة الاستخدام

1. ارفع أو ثبت ملف `zero-error-reviewer.skill` في بيئة ذكاء اصطناعي تدعم المهارات.
2. أضف المخطوط الذي تريد مراجعته.
3. حدد مجال المراجعة مثل IMRaD، APA 7، IEEE، المنهجية، اتساق البيانات، أو المراجعة الكاملة.
4. شغل عملية المراجعة.
5. استخدم الملاحظات لتحسين المخطوط.
6. أعد الفحص بعد التعديل عند الحاجة.

مثال:

```text
Review this manuscript using Zero Error Reviewer. Focus on IMRaD structure, APA 7 citation consistency, data consistency, methodology completeness, and unsupported claims.
```

---

## أهمية هذه المهارة

تفشل كثير من المخطوطات الأكاديمية بسبب مشكلات يمكن إصلاحها قبل الإرسال. تشمل هذه المشكلات غموض فجوة البحث، نقص المنهجية، عدم اتساق البيانات، ضعف المناقشة، عدم انتظام المراجع، أخطاء الاستشهاد، والاستنتاجات غير المدعومة بالنتائج.

تساعد Zero Error Reviewer في تقليل هذه المخاطر من خلال مراجعة منظمة، قائمة على الأدلة، وقابلة للتتبع.

---

## Keywords

AI academic reviewer, manuscript checker, research paper review, APA 7 checker, IEEE citation checker, IMRaD validator, academic writing assistant, journal article reviewer, thesis checker, dissertation reviewer, research quality assurance, zero error reviewer, AI skill, `.skill`, `.skills`.

---

## License and Copyright

Copyright © 2026 Abia Nugrahanto. All rights reserved.

This repository and all files contained in it, including the Zero Error Reviewer Skill, documentation, references, templates, and related materials, are protected by copyright law.

You are allowed to download, install, and use this repository for personal, academic, research, educational, and internal non-commercial purposes.

You may use the Zero Error Reviewer Skill as provided in this repository, as long as the original copyright notice and ownership information remain visible and unchanged.

You are not allowed to edit, modify, adapt, translate, repackage, rebrand, sublicense, redistribute modified versions, sell, resell, rent, or commercially exploit this repository or any part of it without prior written permission from the copyright owner.

Public availability on GitHub does not mean this repository is open source. Permission is granted only for downloading and using the original files as provided.

If you want to modify, redistribute, integrate into a commercial product, or use this skill for commercial purposes, you must obtain written permission from the copyright owner first.

If you want to use, adapt, integrate, or redistribute this skill, please request permission from the copyright owner first.
