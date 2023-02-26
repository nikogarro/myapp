# myapp
An application with **``Python``** using a **``Flask``** server to connect with the **``Spotify API``**, get my songs names saved in a csv format.
Afterwards take the file and automatically scrap the web (youtube), to get the most popular songs urls with **``Selenium``** or **``Beautiful Soup``** modules.

The 3 main methods which where used are
1. Google Colab and ngrok in order to make a tunnel which our **``Flask``** server can communicate with spotify's api in order to aquire our song names.
2. A **``Python``** file which takes the song names csv file and then scraps the web (youtube) with **``Beautiful Soup``**.
3. A **``Jupyter Notebook``** which takes the song names csv file and then scraps the web (youtube) with **``Selenium``**.
