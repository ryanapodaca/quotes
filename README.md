# quotes

This application outputs the name of an author and a respective quote from them when it is run.  
If the app can connect to the internet, it will request a quote from the Forisnatic API.  It will then display the author and 
a quote from them  If a 200 response is not acquired, an arraylist is used to display random quotes from a JSON file from 
within the resources folder of this project.  

Please install Gson as an implementation in your dependencies folder. This is a gradle project, so alos ensure your gradle is updated and refreshed.
