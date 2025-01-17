# Video Chat Website

This is a **Video Chat Website** built using Django, designed to facilitate real-time video communication. The project is complete and includes all the necessary files for setup and execution.

## Features

- Real-time video chat functionality.
- User-friendly interface.
- Scalable architecture.

## Prerequisites

Ensure you have the following installed:

- Python 3.x
- pip (Python package manager)
- Virtualenv (recommended for dependency management)

## Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/shuva-kharel/video-chat-website.git
   cd video-chat-website
   ```

2. **Set Up a Virtual Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate       # On Linux/Mac
   venv\Scripts\activate          # On Windows
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

   > **Note:** The `requirements.txt` file includes the following packages:
   >
   > - `agora-token-builder==1.0.0` (Latest version as of December 29, 2021)
   > - `asgiref==3.8.1` (Latest version as of January 17, 2025)
   > - `Django==5.0.9` (Latest version as of January 17, 2025)
   > - `sqlparse==0.5.1` (Latest version as of January 17, 2025)
   > - `tzdata==2024.2` (Latest version as of January 17, 2025)

4. **Apply Migrations**

   ```bash
   python manage.py migrate
   ```

5. **Run the Development Server**

   ```bash
   python manage.py runserver
   ```

6. **Access the Application**

   Open your browser and navigate to:

   ```
   http://127.0.0.1:8000/
   ```

## Usage

1. Register or log in to access the video chat functionality.
2. Create or join a video chat room to start a conversation.

## Contributing

Feel free to submit issues or pull requests if you find bugs or have ideas for improvement.

## License

This project is licensed under the MIT License.

---

**Developed by [shuva-kharel](https://github.com/shuva-kharel)**
