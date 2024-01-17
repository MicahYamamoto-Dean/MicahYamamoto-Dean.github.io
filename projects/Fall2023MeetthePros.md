---
layout: project
type: project
image: https://www.hscpa.org/writable/documents/mtp-p_1.png
title: "Fall 2023 Meet the Pros"
date: 2024
published: true
labels:
  - Accounting Club at University of Hawaii at Manoa
  - Accounting
  - Hawaii Society of Certified Public Accountants
summary: "Networking event, where you learn more about the fields/avenues within accounting, and be able to practice your communication, business etiquette, and interview skills. "
---

HSCPA Meet the Pros, is a professional interaction event, that allows Shidler College of Business students at the University of Hawaii at Manoa, who are members of Beta Alpha Psi and/or the Accounting Club, the opprotunity to essentially, "meet the pros". The students at this event is given the opprotunity to network with various professionals in the accounting profession and learn more about the fields/avenues within accounting through their conversations, with these professionals. The overall goal for this event is for the students to learn more about the professions in accounting, and be able to practice their communication, business etiquette, and interview skills.

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>



Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
