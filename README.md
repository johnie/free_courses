

# Coursera courses database
This comprises of data on courses assisting a noesis on technical subjects

### Rules:
1. ***platform*** name should be in **lowercase**
2. ***id*** is the number assigned by your mentor
3. ***module_number*** should be an **integer**
4. if modules are unavailable, videos, chapters etc can be added
5. ***free_courses*** - can have either **'yes'** or **'no'** against them
6. ***certification*** maybe one of three options- **'free'** (for courses with free certifications), **'paid'** (either for *paid courses* or *free courses with paid certifications* ) and **'none'**.

   
  ```
   [
     {
       'id' :  1,
       'platform' : 'coursera',
       'free_course' : 'yes',
       'course_name' : 'Basic Python',
       'link' : 'https://coursera.com/Basic-python',
       'module_number' : 5,
       'certification' : 'free'
     }
   ]
