PROJECT TITLE:
          YOUTUBE DATAHARVESTING AND WAREHOUSING
                     In this project we create a Streamlit application that allows us to access and analyze data from multiple YouTube channels.
                         *Streamlit: It is a great choice for building data visualization and analysis tools quickly and easily. We are using it to create a simple UI where users can enter a YouTube channel ID, view the channel details, and select channels to migrate to the data warehouse.
                         *YouTube API:We are using the YouTube API to retrieve channel and video data. we can use the Google API client library for Python to make requests to the API.
                         *MongoDB: Once we retrieve the data from the YouTube API, you can store it in a MongoDB. MongoDB is a great choice to store a data because it can handle unstructured and semi-structured data easily.
                         *4.	Migrate data to a SQL data warehouse: After we've collected data for multiple channels, we can migrate it to a SQL data warehouse.We can use a SQL database as PostgreSQL for this.
                         *5.	Query the SQL data warehouse: We can use SQL queries to join the tables in the SQL data warehouse and retrieve data for specific channels based on input. We can use a Python SQL library such as SQLAlchemy to interact with the SQL database.
                         *6.	Display data in the Streamlit app: Finally, we can display the retrieved data in the Streamlit app.We can use Streamlit's data visualization features to create charts and graphs to help users analyze the data.
                         Overall,in this project we build a simple UI with Streamlit, retrieving data from the YouTube API, storing it in a MongoDB data lake, migrating it to a SQL data warehouse, querying the data warehouse with SQL, and displaying the data in the Streamlit app.
