# prep_note.md


#### Yellow Belt Throughput: 

- Yellow belts can carry up to 15 items/second, which is 900 items/minute.
- But in most cases, for our design to acheive required production rate of 120 items/minute for green circuits with minimum resources, we will not be using full capacity of yellow belts.

#### Green Circuits Production
**Target:** 120 green circuits/min  

| Material | Required Rate (items/min) | 
|-----------|---------------------------|
| Iron Plates | 110-120                         |      
| Copper Plates | ~180                       |      


---

#### Basic Oil Ratios

**Oil is not available in the demo of factorio.**

---

#### Bottleneck & Fix
**Bottleneck Observed:**  

- Not Providing copper coils and iron plates to green circuit assemblers in the correct ratios (3:2) caused underproduction. 
- Also, providing materials to assemblers/smelters via belts caused uneven distribution.

**Fix Implemented:**  
- Modify the design such that copper coils and iron plates are provided in the correct ratios to green circuit assemblers.
- Use splitters to evenly distribute materials to assemblers/smelters. (It was straight forward for dividing one belt into two belts using splitters but dividing one belt into three was tricky, but bypassed this by using divinding into two and each assembler (with two inserters) taking from one of the split belts.)


---

#### Simplification
**Layout Simplification That Helped:**  

- Using underground belts to cross belts and reduce space usage.
- Using splitters to evenly distribute materials to assemblers/smelters.
- Deciding an overall layout before placing machines to minimize belt crossing and space usage.
---

### Note

- Oil is not available in the demo of factorio.
- I wasn't able to find the way to include/use blueprints in the demo version of factorio.
- Using or loading seeds is also not found in the demo version of factorio.
- So, I had to design the layout in the tutorial level 5 map itself.
- I haven't submitted the blueprint file and save.zip file because of the above reasons.