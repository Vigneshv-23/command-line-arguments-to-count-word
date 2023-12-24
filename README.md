# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a new file in visual studio code and type the words in that files
### Step 2: 
 save the file and after opening new folder type the required code to generate the program
### Step 3: 
import sys from the module
### Step 4:  
split the word count  using command line arguments
### Step 5: 
print the len(words())
### Step 6: 
end of the program
## PROGRAM:
#to find word count using command line arguments
#developed by:vignesh v
#register no:23002301
import sys
if len(sys.argv) == 2:
    word_count = len(sys.argv[1].split())
    print(f"Number of words: {word_count}")
else:
    print("Usage: python word_count.py <text>")
### OUTPUT:
<img width="326" alt="image" src="https://github.com/Vigneshv-23/command-line-arguments-to-count-word/assets/110780412/34126686-6b44-4167-8dec-6b8d4e0619e5">
<img width="337" alt="image" src="https://github.com/Vigneshv-23/command-line-arguments-to-count-word/assets/110780412/ab6ebf31-cc86-493f-89d7-cdb4f9942b72">
<img width="805" alt="image" src="https://github.com/Vigneshv-23/command-line-arguments-to-count-word/assets/110780412/5653aa9a-dd96-4398-a844-ebefd7747d40">
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
