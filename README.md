# Smart India Hackathon Workshop
# Date: 14-11-2025
## Register Number: 212223220080
## Name: Preethi J
## Problem Title
SIH 1555: Create a Virtual Herbal Garden that provides an interactive, educational, and immersive experience to users, showcasing the diverse range of medicinal plants used in AYUSH (Ayurveda, Yoga & Naturopathy, Unani, Siddha, and Homeopathy).
## Problem Description
Background: The AYUSH sector relies heavily on medicinal plants and herbs, which form the backbone of traditional healing practices. However, physical gardens that are not accessible to everyone. A Virtual Herbal Garden will bridge this gap by offering a digital platform where users can explore, learn, and understand the significance of various medicinal plants from the comfort of their homes. Description: Participants are tasked with developing a Virtual Herbal Garden that is engaging, informative, and user-friendly. This virtual garden should include: Interactive 3D Models: Realistic 3D models of medicinal plants that users can rotate, zoom, and explore from different angles. Detailed Information: Comprehensive details about each plant, including its botanical name, common names, habitat, medicinal uses, and methods of cultivation. Multimedia Integration: High-quality images, videos, and audio descriptions to enhance the learning experience. Search and Filter Options: Advanced search functionality to easily locate specific plants and filter them based on various criteria like medicinal uses, region, and type. Virtual Tours: Guided virtual tours highlighting specific themes, such as plants for digestive health, immunity, skin care, etc. User Interaction: Features that allow users to bookmark favourite plants, take notes, and share information on social media. Expected Outcome: The expected outcome is a comprehensive Virtual Herbal Garden that serves as a valuable educational tool for students, practitioners, and enthusiasts of the AYUSH sector. This platform should make the knowledge of medicinal plants accessible to a wider audience, promoting awareness and understanding of traditional herbal practices. It should be visually appealing, informative, and interactive, providing users with an immersive experience that combines technology with traditional knowledge.

## Problem Creater's Organization
Ministry of Ayush

## Idea
The Virtual Herbal Garden aims to digitize the exploration of medicinal plants from the AYUSH system. It provides an immersive 3D experience where users can rotate and inspect plant models, read detailed herbal information, watch videos, take virtual tours, and bookmark their favourite plants. This platform bridges the accessibility gap by bringing herbal knowledge to students, practitioners, and the public through an interactive online experience.


## Proposed Solution / Architecture Diagram
The proposed solution is to build an interactive Virtual Herbal Garden that allows users to explore medicinal plants digitally through an immersive 3D environment. The platform integrates 3D plant models created using Blender or scanned assets, rendered in the browser using Three.js or Babylon.js. A modern web interface built with React or Vue provides smooth navigation, search, filtering, virtual tours, and detailed plant information pages. Each plant entry includes botanical details, habitat, medicinal uses, cultivation methods, images, audio, and videos stored in secure cloud storage. The backend—developed using Node.js or Django—serves plant data through REST APIs, while a database such as MongoDB or PostgreSQL stores structured herbal information. Additional components include a search engine, user authentication, bookmarking, and a note-taking system. The system architecture ensures high accessibility, scalability, and an engaging user experience, effectively making Ayurvedic and traditional herbal knowledge available to learners, researchers, and the public without requiring physical access to herbal gardens.


## Use Cases

* Explore Plants in 3D: Users interact with rotatable, zoomable herbal plant models.
* Search & Filter: Users search plants by medicinal use, name, region, plant type, etc.
* View Plant Details: Each plant displays botanical name, uses, habitat, and multimedia.
* Virtual Guided Tours: Narrated tours showcasing plants grouped by health themes.
* Bookmark Plants: Users save favourite plants for quick access.
* Take Notes: Users write personal notes linked to each plant.
* Admin Management: Admins add, update, and manage plant info and multimedia content.


## Technology Stack
* Frontend:
  - React.js / Vue.js
  - Three.js / Babylon.js for 3D models
  - TailwindCSS for UI

* Backend:
  - Node.js (Express) or Django REST Framework

* Database:
  - MongoDB or PostgreSQL

* 3D Assets:
  - Blender-generated GLB/FBX models

* Storage:
  - Cloud storage (AWS S3 / Firebase)

* Search:
  - ElasticSearch or built-in DB filtering


## Dependencies

* Three.js / Babylon.js – 3D model rendering
* React / Vue – Frontend architecture
* Axios / Fetch API – API requests
* Node.js / Django – Backend framework
* MongoDB/PostgreSQL drivers – Database drivers
* Cloud Storage SDKs – For storing multimedia
* JWT Authentication – Secure login
* Blender Tools – For preparing 3D plant models


