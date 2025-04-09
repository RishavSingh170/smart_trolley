# 🛒 Smart Trolley with RFID and Bluetooth

This project implements a **Smart Trolley** using an **Arduino**, **RFID module**, **LCD display**, and **Bluetooth** communication. It allows users to scan items using RFID tags, view them on an LCD, and send billing information over Bluetooth.

---

## 🔧 Hardware Components

- Arduino Uno (or compatible board)
- MFRC522 RFID Reader
- 16x2 LCD Display
- HC-05 Bluetooth Module
- Push Buttons (x2) - Add & Remove
- Jumper Wires & Breadboard
- Power Supply

---

## ⚙️ Features

- RFID-based item detection
- Add or remove items using push buttons
- Real-time billing display on LCD
- Bluetooth communication of scanned items and total bill

---

## 📦 Item List (Predefined)

| Item Name | RFID Tag ID      | Price (Rs) |
|-----------|------------------|------------|
| Salt      | 73 62 02 29      | 100        |
| Milk      | 03 06 DB 13      | 50         |

> Note: Update the `itemList[]` array in the code to add more items.

---

## 🖥️ How It Works

1. User scans an RFID-tagged item.
2. LCD displays item name with options:
   - Press **Add Button** to add to the bill.
   - Press **Remove Button** to remove it.
3. Total bill updates on LCD and is sent via Bluetooth.

---

## 📲 Bluetooth Output Example

