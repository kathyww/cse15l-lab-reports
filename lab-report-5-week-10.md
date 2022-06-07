# Lab Report 5

## Explain:

I found the test cases with different results using `vimdiff`

* [file 516](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/516.md)

* [file 567](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/567.md)

(left side: my markdownParse/right side: Lab9 markdownParse)
## 1. 1st Test ##
Both give the wrong outputs.


Different expected outputs: 516


![image1](https://user-images.githubusercontent.com/103288344/172296126-8b46f052-f6fd-49e9-a2f2-4c66dfcaa867.png)


Expected output:


![image2](https://user-images.githubusercontent.com/103288344/172296134-1776c628-ba81-43bc-a863-46103fb8347b.png)

* In this case the link should be /uri. My markdownParse didn't count the brackets correctly so it gets out of the loop before reaching the last paratheses and returns a empty string. To fix this, I need to add more if statement to test through the nested brackets and check if the line in the paratheses is not end with .jpg. 






## 2. 2nd Test ##
Both give the wrong outputs.

Different expected outputs: 567


![image3](https://user-images.githubusercontent.com/103288344/172296328-4faf5a1c-cd83-4ec1-ac15-c95cd26df3c2.png)



Expected output:


![image4](https://user-images.githubusercontent.com/103288344/172296330-18ab37db-5820-4a65-96f5-3c5f9d76f8b9.png)


* In this case the correct output is /url1. My markdownParse failed this by printing out the message instead of the link. To fix this, I need to add an if statement to check if the "link" in the paratheses contains space, and if it dose then ignore the line insides the paratheses. Also, the expected output shows that `[]:` can also create a link, so I need to add another if statement to check if there is any form of `[]:` in the file, and if it does then what's after `:` is the link.
