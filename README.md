# SignalSense: Enhancing Driver Safety with Intelligent Traffic Sign Detection

Welcome to SignalSense, your advanced solution for identifying and understanding traffic signs on the road. This application leverages the power of machine learning to detect various traffic signs, providing drivers with essential guidelines and instructions to enhance their driving experience and safety.

## Features

- **Traffic Sign Detection**: Uses advanced algorithms to detect and recognize traffic signs from camera feeds.
- **Sign Information**: Provides detailed information and guidelines about each detected sign to help drivers stay informed and safe.
- **User-Friendly Interface**: Built with Next.js for an intuitive and responsive user experience.
- **Real-Time Data Retrieval**: Gives the Live results using cams and updates the info.

## Technology Stack

SignalSense is built using a combination of modern technologies and tools:

### Backend
- **[Flask](https://flask.palletsprojects.com/)**: A lightweight WSGI web application framework in Python used to handle backend processes and API requests.
- **[MongoDB](https://www.mongodb.com/)**: A NoSQL database used to store and manage traffic sign data.

### Frontend
- **[Next.js](https://nextjs.org/)**: A React framework for building server-side rendered applications with a focus on performance and user experience.


## Getting Started

### Prerequisites

- Node.js and npm installed.
- Git to pull the forked repo.
- Python 3.7 or higher
- pip (Python package installer)

## Setup

1. **Clone the Repository**

```bash
git init
git clone https://github.com/Aryan741x/SignalSense.git
```

### Setup Backend

2. **Install Dependencies**

```bash
cd Backend
pip install -r requirements.txt
```

3. **Setup .env**
- Go to .env file present inside the Backend.
- Put your Roboflow key as [ROBOFLOW_API_KEY](https://docs.roboflow.com/api-reference/authentication) and MongoDB URI
```bash
ROBOFLOW_API_KEY=''
MONGODB_URI=''
```
4. **Run the Backend**

```bash
python main.py
```

### Setup Frontend

5. **Install Dependencies**

```bash
cd ..
cd Frontend
npm i
```

6. **Run the Frontend**

```bash
npm run dev
```


### Running the Application

7. **Flask Server**
```bash
https://localhost:5000
```
8. **View the Project at**
```bash
https://localhost:3000
```


## Demo Video

[![Watch the video](https://img.youtube.com/vi/Nm-ryCR42VI/maxresdefault.jpg)](https://youtu.be/Nm-ryCR42VI)




Feel free to dive into the project, explore the code. Happy coding!
