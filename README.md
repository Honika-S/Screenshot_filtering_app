## Screenshot Filtering App
An advanced image management and processing web application. It enables users to upload images, extract text via Optical Character Recognition (OCR), generate captions, detect objects, recognize and tag faces, and search based on multiple criteria. The application leverages MongoDB for storing metadata and React.js for a modern, user-friendly frontend. The backend handles various image processing tasks using Python and integrates seamlessly with Node.js for serving the API.

Features
Image Upload: Upload single or multiple images (via ZIP) and store metadata in MongoDB.
OCR (Optical Character Recognition): Extract text from images using Tesseract OCR.
Image Captioning: Generate descriptive captions using the BLIP model from Hugging Face.
Object Detection: Detect objects in images with the YOLO model.
Face Detection and Tagging: Detect faces, encode them, and allow users to tag and identify faces.
Search Functionality: Search by keywords, OCR results, captions, and face recognition. Support for searching by similar faces or objects.
Running the Application
Run the Backend:
cd backend
node app.js
Run the Frontend:
cd frontend
npm start
Open the application at http://localhost:3000 (default port for React).
Contributions
Contributions are welcome! If you have any feature requests, bug reports, or suggestions, feel free to open an issue or submit a pull request.
