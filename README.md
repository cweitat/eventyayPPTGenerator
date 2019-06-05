# Eventyay Door Screen Slides Generator
### **NOTE**
**Check that all slides are there after generating. There's cases where some sessions are skipped. If a fix is found, please make a PR.**

### Software/Services used
    
   - [PptxGenJS]( https://github.com/gitbrent/PptxGenJS)
   - [Eventyay](https://eventyay.com) API

### Setup Instructions
	
- Update the option values to rooms/venues available in your event.
- Logo image sizing and position needs to adjust
- Set the screen ratio, default in script is 16:9
- Session name, time, speakers name and track will be generated. (refer to screenshot below)

---

### Operating flow
Export one session by keying in session ID or export slides by venue through the dropdown.
You can do this by taking the JSON generated by the API and beautifying to read it.


File name will be in the following structure:
**DD-M(Time)HH_MM - HH_MM-Session Name**

Example: 
**17-3.(Time)16_35 - 17_00-FOSSASIA Summit 2019 - Closing**

---

**Screenshot**

![screenshot sample](https://github.com/cweitat/eventyayPPTGenerator/raw/master/screenshot.PNG)

---
#### **Credits**
   Copyright [2019] [cweitat]

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.-editor).  
    
    
