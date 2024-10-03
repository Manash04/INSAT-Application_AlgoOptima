
# INSAT Application

This repository contains the development of innovative applications for INSAT satellite data using Cloud Optimized GeoTIFFs (COGs). The project focuses on efficient handling of satellite imagery, including functionalities such as selective streaming, partial downloads, and web-based visualization. 

## Project Structure

The repository is structured into two main components:

1. **Web Application** (`Web_app/`):  
   A web-based interface for interacting with INSAT satellite data. The web app provides users with tools for visualizing and downloading satellite imagery using COG functionalities.
   
2. **COG Conversion Model** (`model/`):  
   Contains the scripts and tools for converting INSAT satellite data into Cloud Optimized GeoTIFF (COG) format. This model ensures the satellite imagery is stored in an efficient and accessible manner, enabling selective streaming and partial downloads.

## Features

- **Selective Streaming**:  
  Stream only the required portion of satellite imagery based on user selection.
  
- **Partial Downloads**:  
  Download specific sections of satellite imagery without downloading the entire file.

- **Web-based Visualization**:  
  Visualize the satellite images directly in the browser through the web application.

## Project Folders

- `Web_app/`: Contains the code for the front-end and back-end of the web application, designed to interact with COG data.
  
- `model/`: Includes the COG conversion scripts that prepare the satellite data for optimized storage and retrieval.

## Installation and Setup

To get started with the project, follow these steps:

### Prerequisites
- Python 3.x
- FastAPI (for API creation)
- Streamlit (for visualization)
- Docker (optional, for containerization)

### Setup Instructions

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/INSAT-project.git
    cd INSAT-project
    ```

2. **Install dependencies** for the Web Application and COG Conversion Model:
    ```bash
    cd Web_app
    pip install -r requirements.txt
    ```

3. **Run the Web Application**:
    ```bash
    uvicorn main:app --reload
    ```

4. **COG Conversion Model**:  
   Inside the `model/` directory, use the scripts to convert INSAT satellite data into COG format.

5. **Access the Application**:  
   Once the web app is running, open your browser and navigate to `http://localhost:8000`.

## Usage

1. Upload INSAT satellite data through the web interface.
2. Visualize the data in the browser using the built-in tools.
3. Stream or download specific parts of the imagery based on your needs.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any improvements or bugs.

## License

This project is licensed under the MIT License.

---

