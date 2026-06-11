# 📱 Social Commerce Keyboard Simulator (Prototype)

> Turning WhatsApp into a trustless CRM to eliminate fake-alert fraud for social media vendors.

## 🚀 The Problem
Social commerce in emerging markets thrives on chat apps like WhatsApp and Instagram DMs. However, vendors face two massive pain points:
1. **Context Switching:** Sellers must constantly leave the chat to open banking apps, generate payment links, or update inventory spreadsheets.
2. **Fake Bank Alerts:** Vendors lose millions to fraudsters using photoshopped receipts or fake alert generator apps. 

## 💡 The Solution
This project is a high-fidelity web prototype simulating a **Custom iOS/Android Commerce Keyboard**. It allows vendors to generate secure, one-time virtual bank accounts directly inside the chat interface. Instead of relying on vulnerable screenshots, the system waits for automated bank webhooks to confirm the payment, making the transaction 100% trustless and fraud-proof.

## ✨ Core Features (Demo Ready)
* **Chat Interface Simulation:** A mocked WhatsApp environment to demonstrate the native feel of the extension.
* **Seamless Keyboard Toggle:** Simulates switching from a standard typing keyboard to the "Commerce Mode" UI.
* **Virtual Account Generation:** Instantly creates a temporary, dedicated account number for the specific transaction.
* **Simulated Bank Webhook:** A testing button to mimic a real-time API ping from a payment gateway, automatically turning the transaction status to "Paid" and alerting the vendor in the chat.

## 🛠️ Tech Stack
* **Framework:** React + Vite
* **Language:** TypeScript
* **Styling:** Tailwind CSS
* **Icons:** Lucide React

## 💻 How to Run Locally

If you want to run this prototype on your local machine:

1. **Clone the repository:**
```bash
git clone [https://github.com/yourusername/commerce-keyboard-sim.git](https://github.com/yourusername/commerce-keyboard-sim.git)
```

2. **Navigate into the directory:**
```bash
cd commerce-keyboard-sim
```

3. **Install the dependencies:**
```bash
npm install
```

4. **Start the development server:**
```bash
npm run dev
```

5. Open your browser and visit the `localhost` link provided in the terminal.

## 🎥 Pitch & Demo
This prototype was explicitly built to demonstrate the user flow for our startup incubator application. 

**Demo Flow:**
1. View the simulated chat where the customer requests an account number.
2. Tap the text input to trigger the Commerce Keyboard.
3. Enter the item price and click **Generate Virtual Account**.
4. Click the **Simulate Bank Webhook** button at the bottom of the screen to witness the trustless payment confirmation loop.
