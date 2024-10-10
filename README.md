				<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->
# LAI Detector
Final project for the Building AI course

## Summary
Describe briefly in 2-3 sentences what your project is about. About 250 characters is a nice length! 

## Background
Today we have a real concern that the democracy is decreasing. A big reason for this might be a contempt for politicians, and a belief that they lie and don't speak truthfully. There is also a problem with alternative new sites that report alternative versions of truth.

## How is it used?
If speech input, it is first translated to text. Text is then analyzed first using NLP to understand the meaning of the text. Then this text is being verified using all available BIG DATA informationIf speech input, it is first translated to text. Then the text is analyzed first using NLP to understand the meaning of the text. Then this text is being verified for truthfulness using all available BIG DATA information. The result is then presented on the fly, summarizing what might be wrong in the statements (might be several different options), correct these wrongs with possible truths, in case of uncertainty, predict a possibility value for truthfulness. 

This would allow listeners to react on lies and untruths to be able to ask counter-questions . It would help in case of arguments which statement to believe in. In the end, it would be harder to get away with lying.
![image](https://github.com/user-attachments/assets/46af9f50-2181-4a1f-ad62-74695e3b9e51)

![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)
				If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">
				This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]
				totPop = sum(pop)
   totFish = sum(fishers)
				# write your solution here
				for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%
				main()
```
				## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)
				| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges
In case of particular domain knowledge, e.g. for politicinas specific economc figures not available for the public, it might not be possible to have the correct data to verify lies against.

## What next?
I think the usefulness is great for this AI-tool. It's a fact controller tool, not only to spot possible lies, but also to correct wrong information and misunderstandings.

## Acknowledgments
				* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
![image](https://github.com/user-attachments/assets/65731546-4584-42bc-89ec-f4425bcdce44)
