BACKEND:
- Cài dependencies: npm install
- cp env.example .env
- npm run dev hoặc npm start
- Copy-paste vào tệp .env:
JWT_SECRET=your_super_secret_jwt_key_here_123456
JWT_EXPIRE=7d
PORT=5000
NODE_ENV=development
REDIS_URL=redis://default:QNWp8BVDdLXUfule6FxaBHRPjuTkoYx3@redis-10579.c326.us-east-1-3.ec2.redns.redis-cloud.com:10579

FRONTEND:
- Cài dependencies: npm install
- Copy-paste vào tệp .env: VITE_API_BASE_URL=http://localhost:5000
- npm run dev

IMPORT DATABASE (MongoDB):
- MONGODB_URI=mongodb+srv://root:21082004@cluster0.oqhctgp.mongodb.net/travel_website?retryWrites=true&w=majority&appName=Cluster0
