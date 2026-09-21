# Nova AI — Master Core (No Social Media)

This project intentionally EXCLUDES YouTube, Facebook, TikTok and Instagram.
Those are reserved for a separate future APK.

## Requested feature modules
1. AI Chat
2. Web Search
3. Voice Input
4. Voice Answer / Text-to-Speech
5. Live AI Conversation
6. AI Image Generator
7. AI Video Generator
8. Writing & Script Generator
9. PDF & File Assistant
10. File Creator: PDF, DOCX, XLSX, PPTX, CSV, TXT, MD
11. Movie & Series Finder
12. Translator
13. Camera AI
14. Image / Screenshot Q&A
15. Study / Tutor Mode
16. Coding Assistant
17. Document Analyzer
18. Smart Notes
19. Audio-to-Text
20. OCR
21. CV / Resume Maker
22. AI Planner
23. AI Model Selector
24. Chat History
25. Favorites / Saved Prompts
26. Download / Share Center
27. Notifications
28. Privacy / Security
29. English + Urdu UI
30. User Account
31. Admin Panel
32. Custom Branding / App Icon

## Additional useful modules
33. Prompt Library / Templates
34. Conversation Export
35. Recent Files
36. Usage / Provider Status
37. Error & Retry Center
38. Settings / Permissions Center
39. Theme / Appearance Settings
40. Feedback / Report Problem
41. App Help / About
42. Feature Search
43. Quick Actions
44. Secure Provider Configuration
45. Offline Drafts / Local Notes

## Reality check
This ZIP is an Android project with the complete module registry/UI and an APK build workflow.
It is NOT an honest claim that every external service is already live.

To make modules actually work, each required backend/provider must be implemented and configured.
A Gemini API key does not automatically activate web search, movie databases, OCR, TTS,
video generation, file conversion, accounts, notifications, etc.

For production, API keys must not be hard-coded into the APK. Use a secure backend/proxy
and environment/secret variables. Google explicitly recommends keeping Gemini API keys
confidential and not exposing them in client-side mobile apps.

The next development phases should implement and test each provider one by one.
