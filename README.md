# 🚖 Glider Taxi Inspection Verification Bot Solution

In 🇧🇾 **Belarus**, taxi drivers must complete a **🩺 Medical Inspection** (for the driver) and a **🔧 Technical Inspection** (for the vehicle) before starting their shifts. The **📡 Dispatcher Platform** connects drivers with passengers, while **🏢 Taxi Parks** (back-office administration) manage operations and compliance.  

To ensure that only **✅ inspected drivers** can access the dispatcher service, we have developed a **🤖 Telegram Three-Bot Solution** for inspection verification.  

---

## 🏆 How It Works

### **1️⃣ Driver Bot** 🚕
- 🏁 Before starting work, drivers must **initiate a work session** via the bot.  
- 🏥 They visit an authorized **inspection company** for both **medical** and **technical** inspections.  
- 📸 After inspection, the inspector provides a **QR code** that the driver scans to confirm compliance.  
- ✅ Once verified, the driver can begin **accepting passenger requests**.  
- 🛑 At the end of the shift, drivers **end their work session** through the bot.  

### **2️⃣ Inspection Company Bot** 🏥🔍
- 🏢 Used by **inspection companies** to **generate QR codes** for completed inspections.  
- 📜 QR codes can be displayed on-site for easy **scanning by drivers**.  
- 🔄 Generating a **new QR code** automatically **invalidates** the previous one.  

### **3️⃣ Back-Office Administration Bot** 🏢🛠️
- 📝 Used by **taxi parks** to **verify drivers** and link their **license numbers** to the dispatcher platform.  
- 🚫 Ensures **only inspected drivers** can access the dispatcher system and pick up passengers.  

---

## 🌟 Key Features & Benefits
- ✅ **Mandatory Verification for Dispatcher Access** – Ensures all drivers **complete inspections** before working.  
- 🚫 **Prevents Unauthorized Access** – Drivers **cannot work** unless they pass inspections and register in the system.  
- 📲 **Simple & Efficient QR Code System** – Allows **quick verification** without requiring manual input from inspectors.  
- 🔗 **Seamless Integration with Existing Systems** – Connects with **dispatcher platforms** like **Yandex** for automatic compliance enforcement.  

By implementing **Glider’s bot solution**, taxi services in Belarus can maintain **⚖️ regulatory compliance**, improve **🚦 safety**, and ensure **only verified drivers** operate within the dispatcher network.  

---

## 📚 User Manuals
For detailed instructions, refer to the specific user manuals for each bot:
- 🚕 **[Driver Bot User Manual](DRIVER.md)**  
- 🏥 **[Inspection Company Bot User Manual](INSPECTION-COMPANY.md)**  
- 🏢 **[Admin & Inspection Company Bot User Manual](ADMIN.md)**  

---

## 📞 Contact for Setup
For assistance in setting up the system, please contact **[Jean Legendre](https://t.me/Jeanlegendre)**. 💬

