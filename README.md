# FactoryInsight

FactoryInsight is a web-based application that seamlessly integrates frontend and backend technologies to provide an efficient and user-friendly platform for searching and analyzing factory part records. Leveraging a powerful combination of cutting-edge technologies, FactoryInsight offers a comprehensive solution for managing and extracting valuable insights from factory part data and related analysis images.

## Project Goals

- Efficient Data Retrieval: Ensure efficient and rapid retrieval of factory part records and associated analysis images from the database and storage, optimizing the search process.

- Comprehensive Data Presentation: Present search results in a user-friendly and comprehensive format, including failure code counts, detailed attributes, and clickable analysis images.

- Data Export and Sharing: Facilitate the export of search result data in CSV format and provide shareable URLs for quick data sharing, promoting efficient collaboration among team members.

- User-Friendly Experience: Deliver an intuitive and user-friendly interface that allows users, including quality control professionals, production managers, and engineers, to easily access and analyze factory part data.

- Reliability and Scalability: Ensure that the project is reliable and scalable, accommodating future growth and increased data volumes.

## Technologies Used

### Frontend
![Framework - Vue.js](https://img.shields.io/badge/Framework-Vue.js-2ea44f) ![Library - Vue Router](https://img.shields.io/badge/Library-Vue_Router-2ea44f) ![Library - Vuex](https://img.shields.io/badge/Library-Vuex-2ea44f) [![Library - AG Grid](https://img.shields.io/badge/Library-AG_Grid-4599ff)](https://) [![Framework - Vuetify](https://img.shields.io/badge/Framework-Vuetify-4599ff)](https://)

- **Vue**: FactoryInsight harnesses the power of Vue.js, a progressive JavaScript framework, to create a responsive and dynamic user interface. Vue's component-based architecture simplifies the development process and ensures a smooth user experience.
- **Vuex**: For state management, Vuex is employed, enabling the application to efficiently manage and share data between components. This ensures consistency and synchronization in the application's state.
- **Vue Router**: To facilitate frontend page navigation and create a seamless user experience, we employ Vue Router, a powerful routing library for Vue.js.
- **Axios**: Axios is utilized for making HTTP requests to the backend. It provides a simple and intuitive way to handle asynchronous operations and communicate with the server.
- **AG Grid Vue**: This advanced data grid component is integrated to display factory part records in a tabular format. It offers powerful data manipulation and filtering features for an enhanced user experience.
- **Vue Multiselect**: For intuitive and efficient filtering and selection of data, FactoryInsight uses vue multiselect. Users can easily choose from a range of options to refine their search criteria.
- **Vuetify**: Vuetify is employed for the application's UI framework, delivering a consistent and visually appealing design. It offers a wide range of pre-designed components and layouts for a polished user interface.
- **V-viewer**: To enable users to view and analyze analysis images, v-viewer is integrated. It allows users to click on images for zoomed-in, detailed inspection.

### Backend
![Framework - Laravel](https://img.shields.io/badge/Framework-Laravel-eb4034) ![Database - MySQL](https://img.shields.io/badge/Database-MySQL-346beb) [![Storage - MinIO](https://img.shields.io/badge/Storage-MinIO-ff7391)](https://)

- **Laravel**: FactoryInsight's backend is built on the Laravel PHP framework, known for its robustness and ease of use. Laravel provides the necessary structure for handling API requests, data management, and user authentication.
- **MySQL**: MySQL is the database management system of choice, housing the factory part records. It ensures data integrity, reliability, and efficient retrieval of information.
- **MinIO**: MinIO, a high-performance object storage server, is seamlessly integrated into FactoryInsight. It serves as the repository for analysis images, allowing for easy storage and retrieval of visual data.

## Key Features

FactoryInsight is equipped with a wide array of features that cater to the needs of users seeking efficient access to factory part records and their associated analysis images. The main features include:

1. **Database Connectivity**: Connects seamlessly to a MySQL database containing factory part records, allowing users to access a wealth of data effortlessly.

2. **Image Storage Integration**: Links to MinIO storage, housing analysis images for each factory part, making it easy to view and analyze visual data alongside records.

3. **Flexible Search**: Provides users with the ability to search factory part records based on various parameters, such as reference number, product name, failure code, and time range. This flexibility ensures that users can quickly locate the information they need.

4. **Comprehensive Search Results**: Upon conducting a search, FactoryInsight displays a user-friendly results page, featuring the number of records found, a breakdown of failure code counts, detailed attributes for each record, and quick access to analysis images of failed product parts. These images can be clicked on to zoom in and view in full detail.

5. **Image Export**: Allows users to export analysis images from the search results into a convenient zip file, streamlining the process of sharing visual data.

6. **Data Export**: Permits the export of search result attribute data in CSV format, making it easy to perform further analysis or share information with others.

7. **Shareable URLs**: Provides a feature to generate shareable URLs for search results, enabling quick and efficient sharing of specific data with team members or colleagues.

8. **View Modes**: Offers two distinct view modes for the search result page. Users can choose between an attribute+image mode, which displays both detailed attributes and analysis images, and an attributes table mode, which focuses solely on the tabulated attributes for quick reference.

## License

This project is the proprietary code of Seagate Technology LLC. and is not open-source. Only README.md is provided here solely for the purpose of showcasing developer skills and project capabilities. Unauthorized use, reproduction, or distribution of this code is prohibited.

**© 2023 Seagate Technology LLC. All rights reserved.**
