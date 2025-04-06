TaskPay: Poverty Alleviation via SMS-Based Tasks  


PROBLEM STATEMENT
- 200M+ Indians lack smartphone access but own feature phones  
- AI companies face severe shortages of local language datasets  
- Existing gig platforms exclude low-income populations  

PROPOSED SOLUTION 
A serverless platform where workers:  
1. Text `HI` to our number  
2. Complete microtasks (voice recordings, local photos) via SMS/MMS  
3. Earn instant UPI payments (as low as ₹10 per task)  

TECH STACK
- **Frontend**: Twilio SMS API, WhatsApp Business  
- **Backend**: Firebase Cloud Functions (Node.js), Firestore  
- **Payments**: Razorpay UPI (Phase 2)  
- **AI Pipeline**: Python data cleaning scripts  

DEMO FLOW  
User: 1/HI 
TaskPay: Choose language: 1. English, 2. हिंदी , 3.తెలుగు
User: 2
TaskPay: टास्कपे में आपका स्वागत है
आपका पहला काम हिंदी मुहावरों की रिकॉर्डिंग भेजना है
User:  //audio file 
TaskPay:बहुत बढ़िया! आपका कार्य #ID223 स्वीकृत हो गया है। ₹70 का भुगतान शीघ्र ही UPI के माध्यम से भेजा जाएगा।
TaskPay: पैसे भेजे गए!
₹70 के लिए अपना UPI ऐप चेक करें।
TaskPay: धन्यवाद!
अपना डैशबोर्ड देखने के लिए यहां जाएं|
https://architadhole7.github.io/TaskPay1/
