# Lab Report 4


* Code in MarkdownParseTest.java

![test image](https://user-images.githubusercontent.com/103288344/169751820-b0e4b730-a188-436f-b768-26de58ac1658.png)



* corresponding output when running the tests in my implementation

![errors](https://user-images.githubusercontent.com/103288344/169751860-12b8822c-1f2d-471b-8185-521c6985badb.png)


* corresponding output when running the tests in the implementation I reviewed

![errors1](https://user-images.githubusercontent.com/103288344/169752937-7e6b02ba-6e9f-48a8-9b74-a19bd866e828.png)


---

1. Snippet1

I think a small code change will make the program work for snippet 1. I can simply add an if statement to check if there is a  \` mark prior to the open bracket. And, if there is one, the currentIndex should directly jump to the index of charactor after the following close paratheses.


2. Snippet2

I don’t think a small code change would work in this case, because I need to match the open paratheses with correct closing paratheses and this step need to consider many different cases. 


3. Snippet3

I think I can fix this by simply adding an if statement. So if there is a blank link in [] or (), currIndex should directly jump to next open bracket.

