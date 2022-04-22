# Who_Wrote_It
A basic Android app which serves to showcase the use of the AsyncTask class.

This app uses the AsyncTask class to perform background work on a thread that is separate from the UI thread. Given a search term which is the book title, 
it attempts to display the author of the book by using the Google Books API. It unfortunately does not persist through configuration changes - for that one
needs the AsyncTaskLoader class.
