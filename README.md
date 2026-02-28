AI Market Analysis Bot


Overview
AI Market Analysis Bot is an automated multi-timeframe trading intelligence system built with n8n.
The system collects market data across multiple timeframes, processes technical structures,
merges contextual news, and generates structured AI-driven trading insights delivered via
Telegram in both text and voice formats. The architecture is modular, scalable, and designed to
enforce structured AI outputs for workflow reliability.


System Architecture
• Data Collection: Fetches candlestick data across multiple timeframes (1m, 5m, 1h, 4h, 1D, 1W).
• Technical Processing: Extracts structured signals per timeframe and standardizes outputs.
• Data Aggregation: Merges timeframe structures with contextual news and session metadata.
• AI Analysis Layer: Generates structured text analysis and voice-ready summaries using
OpenAI.
• Delivery Layer: Sends formatted text and audio insights to Telegram.


Key Features
• Multi-timeframe technical analysis
• Structured AI output enforcement (JSON schema)
• Telegram bot integration
• Voice message generation
• Modular n8n workflow design
• Error-safe structured parsing

Technologies Used
• n8n (Workflow Orchestration)
• OpenAI API
• Telegram Bot API
• Text-to-Speech Engine
• JavaScript Transformation Nodes

Structured Output Format
The AI response is strictly enforced into the following structure:
{ "text_message": "Detailed trading analysis", "voice_message": "Short voice-ready market
summary" }

