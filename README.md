# 🧠💻 Debugging Your Brain: A Wellness Hack for Data Nerds  

> *"Your IDE won’t optimize your mental health—but this guide will."*  

## 🔧 The Pomodoro Technique (For Coders Who Forget to Blink)  
**Problem**: You’ve been staring at `pandas.DataFrame` for 3 hours straight.  
**Solution**:  
1. Code for **25 mins** (set a timer).  
2. **Break for 5 mins**—and *do not touch a screen*.  
   - Stare at a tree (higher resolution than your monitor).  
   - Stretch like your `import numpy` depends on it.  

*(Pro tip: Trees don’t throw `IndentationError`.)*  

## ⏰ Automated Break Timer (`break_timer.py`)  
Run this Python script to enforce breaks (no willpower required):  

```python
import time  
from winsound import Beep  

def take_break(duration=300, interval=1500):  
    print("🛑 Step away from the keyboard!")  
    Beep(interval, 1000)  # Annoying beep to force compliance  
    time.sleep(duration)  
    print("💡 Break’s over. You’ve been missed.")  

# Usage: Call this after 25 mins of work  
take_break()  
```

🤔 Why This Works

Science: Your prefrontal cortex needs rest to debug well.
My TA Experience: HKU MSBA students who took breaks solved bugs 40% faster (unofficial survey).
🌱 Homework for Your Heart

Today, thank yourself for one bug you fixed with patience.

✨ Contributions welcome! Add your wellness hacks via PR.
