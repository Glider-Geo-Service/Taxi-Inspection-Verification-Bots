# Glider Admin Bot User Manual

The **Glider Admin Bot** is designed for taxi service administrators to manage driver registrations and ensure compliance with medical and technical inspections. This bot allows system administrators to register new admins and enables approved admins to verify drivers by linking them to their dispatcher platform.

## **1. Administrator Registration & Authentication**

### **Step 1: Starting the Registration**
- Send the command `/start` to the bot.
- If you are already registered and approved, the bot will reply: **"You are already registered!"**
- If not, the bot will prompt: **"Do you want to register?"** with options:
  - ✅ **Yes** (proceeds with registration)
  - ❌ **No** (cancels the process)

### **Step 2: Submitting Registration Request**
- If you tap **"Yes"**, the bot collects your **Telegram ID, username, and full name**.
- The bot will send a request to the **system administrator** for approval.
- You will receive a confirmation message: **"⏳ Please wait for verification..."**

### **Step 3: Approval by System Administrator**
- The system administrator will receive a request containing your details.
- They can either:
  - ✅ **Approve** (grants admin access)
  - ❌ **Reject** (declines the request)
- If approved, you will receive: **"🤝 Your registration was approved!"**
- If rejected, you will receive: **"❌ Your request for registration was rejected!"**

## **2. Driver Registration & Authentication**
Approved admins can register drivers by verifying their **license numbers** using the bot.

### **Step 1: Initiating Driver Registration**
- Admins receive a **"Enter License Number"** request for a specific driver.
- Clicking the request prompts: **"✍️ Please send the driver's license number."**
- Option to cancel: ❌ **Cancel**

### **Step 2: Entering the License Number**
- Admin enters the **driver’s license number**.
- If incorrect format, bot replies: **"❌ Invalid license format. Please enter a valid license number."**

### **Step 3: Yandex Platform Verification**
- The bot checks the **Yandex platform** for the driver's details.
- If found, the bot displays:
  - ✅ **Driver’s full name**
  - ✅ **Phone number**
  - ✅ **License confirmation request**

### **Step 4: Approving or Editing License Number**
- Admin confirms the license by selecting:
  - ✅ **Approve** (saves the license, completes registration)
  - ✏️ **Edit** (allows entering a new license number)

### **Step 5: Rejecting Driver Registration**
- Admin can reject a driver request using ❌ **Reject**.
- The bot informs the driver: **"❌ Your request for registration was rejected!"**

## **Conclusion**
The **Glider Admin Bot** streamlines the verification process for taxi administrators, ensuring only verified drivers gain access to the dispatcher platform. This system helps maintain regulatory compliance while simplifying registration procedures.

