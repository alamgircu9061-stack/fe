# পথসাথী – ট্রাভেল ট্র্যাকার (SQLite সংস্করণ)
কোনো আলাদা ডাটাবেস ইনস্টল লাগে না। ডাটা server/data.db ফাইলে জমা হয়।

cd server && cp .env.example .env && npm i && npm start
cd client && npm i && npm run dev     (http://localhost:5173)

Node.js 22.13 বা নতুন (LTS/24) লাগবে। Windows-এ শুধু start.bat ডাবল-ক্লিক করলেই দুটি সার্ভার চালু হয়। লোকেশনের জন্য প্রোডাকশনে HTTPS লাগবে।

## Google Maps
client/.env ফাইলে VITE_GOOGLE_MAPS_KEY=... বসান (Google Cloud Console → Maps JavaScript API চালু করে key নিন), তারপর npm run dev আবার চালান।
