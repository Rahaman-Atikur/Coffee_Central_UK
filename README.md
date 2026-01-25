Deployed Server : https://coffee-central-uk.vercel.app/coffees
Deployed Client : https://coffee-central-uk.web.app/

<img width="1893" height="853" alt="image" src="https://github.com/user-attachments/assets/b145e433-ff61-4b8b-a4ce-363c8c0702c3" />



About Coffee Central UK Projects :

BrewManager: Coffee Business Management SystemA full-stack web application designed for coffee shop owners and managers to streamline inventory and user management. This platform allows administrators to control product listings, pricing, and monitor user data through a secure, intuitive dashboard.🚀 FeaturesFor Store ManagersInventory CRUD: Full control to Create, Read, Update, and Delete coffee items (titles, descriptions, pricing, and images).User Management: View detailed lists of registered users and manage account permissions.Real-time Updates: Changes to prices or stock reflect immediately on the client side.Security & AuthFirebase Authentication: Secure Sign-In and Sign-Up flows using industry-standard protocols.Protected Routes: Backend API endpoints and frontend pages are restricted based on authentication status.
Frontend:	React.js, CSS/Tailwind
Backend:	Node.js, Express.js
Database:MongoDB (Atlas)
Authentication:	Firebase Auth
Image Hosting: Firebase Storage / Cloudinary


Architecture OverviewThe application follows a standard Client-Server architecture:Client: React handles the UI and state management, communicating with Firebase for auth tokens.Server: Express acts as the middleware, validating requests and interacting with MongoDB.Database: MongoDB stores coffee product schemas and extended user profiles.📦 Installation & Setup1. PrerequisitesNode.js installedMongoDB Atlas accountFirebase Project credentials2. Clone the RepositoryBashgit clone https://github.com/yourusername/coffee-management-system.git
cd coffee-management-system
3. Backend SetupNavigate to the server directory and install dependencies:Bashcd server
npm install
Create a .env file in the server folder:Code snippetPORT=5000
MONGO_URI=your_mongodb_connection_string
FIREBASE_ADMIN_SDK_JSON=your_config
4. Frontend SetupNavigate to the client directory and install dependencies:Bashcd ../client
npm install
Start the development server:Bashnpm start
🧪 API Endpoints (Example)MethodEndpointDescriptionGET/api/coffeeGet all coffee productsPOST/api/coffeeAdd a new coffee itemPUT/api/coffee/:idUpdate price/detailsDELETE/api/coffee/:idRemove a productGET/api/usersFetch all registered users🤝 ContributingFork the ProjectCreate your Feature Branch (git checkout -b feature/AmazingFeature)Commit your Changes (git commit -m 'Add some AmazingFeature')Push to the Branch (git push origin feature/AmazingFeature)Open a Pull Request


