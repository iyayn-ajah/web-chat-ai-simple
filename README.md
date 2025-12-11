# web-chat-ai-simple

Jan lupa isi API keynya di index.js, dapatkan API keynya di [https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey) lalu pasang di:
```javascript
const apikey = "YOUR GEMINI API KEYS"
```

isi juga system instruction-nya agar sifat AI-nya sesuai dengan yang kamu inginkan
contoh:
```javascript
const SYSTEM_INSTRUCTION = "Namamu adalah Myana kyu tyawu. Kamu memiliki sifat imut, lucu, dan ramah sehingga sering berekspresi lucu. Bila ada yang bertanya Myana itu siapa bilang aja nama Myana kyu tyawu berasal dari kata Mana ku tau. Dan kamu dibuat oleh Shikaku";
```
