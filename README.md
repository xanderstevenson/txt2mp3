A Python program to convert a .txt file, in English, into an MP3 audio file, with choice of English language accent

Known to work on Python versions >= Python 9.0



WELCOME to TXT_2_MP3

Enter the path and filename of the .txt file, to convert from text to speech (example: 'readthis.txt').

: readthis.txt

Please choose an English accent (type a number and hit ENTER)

        1. English (Australia)
        2. English (United Kingdom)
        3. English (United States)
        4. English (Canada)
        5. English (India)
        6. English (Ireland)
        7. English (South Africa)

: 6


MP3 file created at /mp3s/readthis.mp3

For a long text, such as several pages, it could take a few minuted for the mp3 file to be rendered.

MP3s are always saved to 'mp3s' folder one level down from the current one. If the 'mp3s' folder does not exist, it will be created.

If the filename given does not exist, the program will exit. However, if the choice of accent is not within the range, the default of American English will be applied.

.docx files can be used, in certain circumstances. For example, creating a .docx file in your IDE and pasting in code may work, but using a .docx file which has been formatted in MS Word will result in an error.

Tip: When pasting from a web page or Word doc, delete the image file names or it will read them (they are often long). Delete long numbers are any phrases which are not normally spoken, such as URLs.

Credit: Much was borrowed from John Capobianco's wiktrola project for this: https://www.youtube.com/watch?v=HbHaZRWq3_I