# mp4grep-to-SRT
Simple Javascript function that turns the madeup transcription syntax generated by [mp4grep](https://github.com/o-oconnell/mp4grep) into an SRT syntax compliant file

# Usage
CD to the root folder of the script using a command line
The script requires an argument(full name of the mp4grep generated transcription file) which has no flags, and parses whatever is written after  **main.js**.
> node main.js text.transcribed.txt

After a short while, the script will create two different files:
1. The generated .srt version of the script
2. Text only .txt file
