YouTube Downloader with pyTube

1.	Install the Pytube library i.e pip install pytube;
Pytube is a Python library that allows easy interaction with YouTube data, including downloading videos.
2.	Once pytube is installed, import the necessary modules from Pytube in the Python script.
3.	Use tkinter to import filedialog.
Tkinter is a standard GUI (Graphical User Interface) library in Python used for creating desktop applications with graphical interfaces. By providing a faster and easier way to create windows, dialogs, buttons, menus, and other GUI elements for Python applications.
4.	Prompt the user to input the URL of the YouTube video they want to download.
5.	 Use the YouTube class from Pytube to create a YouTube object representing the video.
6.	Using the YouTube object, you can access the available streams. 
Streams represent different formats and resolutions of the video that are available for download.
7.	You can choose a specific stream from the available streams. E.g highest resolution stream.
7.	 Use the chosen stream to download the video.
8.	Add error handling to your script to deal with cases where the video cannot be downloaded, the URL is invalid, or any other issues that may arise during execution. You can also enhance your script by adding features like progress tracking, or specifying a download location.
