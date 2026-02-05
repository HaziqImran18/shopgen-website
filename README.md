# ShopGen - WhatsApp Shopping Assistant

## Project Overview
ShopGen AI is an AI-powered conversational shopping assistant built for WhatsApp. 
It allows users to search products, receive personalized recommendations, and place orders using text or voice messages.

The system demonstrates AI integration with messaging platforms, secure order processing, and multi-user memory management.

## Key Features
- **Conversational AI**: Understands user queries and provides intelligent responses.
- **WhatsApp Integration**: Users interact with the system through WhatsApp using Twilio API.
- **Text & Voice Support**: Supports both text and voice inputs and outputs.
- **Product Recommendations**: Fetches and ranks Pakistani fashion products from local brands.
- **Secure Order System**: Order confirmation via OTP verification.
- **User Data Isolation**: Each user has separate conversation memory and order data.
- **Backend**: Built with FastAPI and Firebase.
- **AI Workflow**: Uses LangGraph for intelligent agent processing.

## Purpose
This project is developed as a **Final Year Project** for demonstration purposes. It showcases AI integration with messaging platforms and secure order management, without commercial deployment.

## How It Works
1. User sends a message to the WhatsApp number.
2. AI agent processes the message, fetches product recommendations, or handles order requests.
3. System responds with text or voice messages.
4. For orders, an OTP is sent for verification before final confirmation.
5. All interactions are logged securely in Firebase, ensuring separate data for each user.


---

**Note:** This project is a student demonstration project and not a commercial product.
