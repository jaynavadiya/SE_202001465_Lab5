# SE_202001465_Lab5 Submission
This is a submission repository for the Lab 5 in which we understand Static Analysis Tools for debugging and other purposes for writing cleaner code

# Jaykumar Navadiya - 202001465

## Used tool for static analysis of code: Pylint
## IDE used for the purpose: Pycharm

### I have used my [own repository](https://github.com/jaynavadiya/TF3-Video-Streaming-With-RTSP-And-RTP) which was a project in last semester for the course of Computer Networks and was fully written in Python.

#### Analyzing [Client.py](https://github.com/jaynavadiya/TF3-Video-Streaming-With-RTSP-And-RTP/blob/main/Client.py) using Pylint in Pycharm's integrated local terminal...

<img width="1420" alt="Screenshot 2023-03-24 at 2 43 44 PM" src="https://user-images.githubusercontent.com/67496808/227476314-4188e638-956c-4615-9a00-2e14e84131da.png">

The above screenshot mostly shows identation issues and trailing whitespace identified with Pylint.

<img width="1419" alt="Screenshot 2023-03-24 at 2 44 23 PM" src="https://user-images.githubusercontent.com/67496808/227476465-1885708d-55d5-417e-a539-8ab06a006790.png">

The above screenshot mostly shows identation issues identified with Pylint.

<img width="1418" alt="Screenshot 2023-03-24 at 2 45 03 PM" src="https://user-images.githubusercontent.com/67496808/227476609-517668b5-0fac-4ad4-b039-a6aa6a52714c.png">

The above screenshot shows warnings like multiple libraries have been imported by using only one import command, some of the variable names are not following snake_case convention that python recommends.

<img width="1421" alt="Screenshot 2023-03-24 at 2 45 29 PM" src="https://user-images.githubusercontent.com/67496808/227476697-9d17d38a-f236-4317-a8a9-85d2b5070a91.png">

The above screenshot shows warnings like the isSet() Method is deprecated and is no longer supported, indentation warnings and warnings mentioning that the type of the exceptions have not been mentioned. The screenshots given below shows the editor image as well.

<img width="906" alt="Screenshot 2023-03-24 at 2 55 04 PM" src="https://user-images.githubusercontent.com/67496808/227479037-e599a599-f2eb-4cc0-bd55-ae8c897dce04.png">

<img width="790" alt="Screenshot 2023-03-24 at 2 53 10 PM" src="https://user-images.githubusercontent.com/67496808/227478482-11132b70-d64b-4286-961f-0bc364c9a965.png">

<img width="1422" alt="Screenshot 2023-03-24 at 2 45 47 PM" src="https://user-images.githubusercontent.com/67496808/227476758-edd6811b-44e6-46fa-9638-e4f4038fdc43.png">

The above screenshot shows identation warnings, unused library that have been imported, code rearrangements when it comes to importing in-built libraries and custom files, mentions attributed mentioned outside of the class (making it global and violating OOPs concepts).

As we can see, the Pylint analyzer gives a code rating at last as well. The [Client.py](https://github.com/jaynavadiya/TF3-Video-Streaming-With-RTSP-And-RTP/blob/main/Client.py) has been rated 4.34/10.


#### Analyzing [The whole repository](https://github.com/jaynavadiya/TF3-Video-Streaming-With-RTSP-And-RTP) using Pylint in Pycharm's integrated local terminal...

##### The given below is the code that was used for analyzing the whole repository by using Pylint:

<img width="446" alt="Screenshot 2023-03-24 at 3 08 27 PM" src="https://user-images.githubusercontent.com/67496808/227483137-a7fea7d6-e2ab-47bd-a475-be3c40fb1298.png">

There was various warnings mentioned by the pylint static code analyzer, most of them was same as before, some errors were new and are given with output screenshots and explanation below.

<img width="1447" alt="Screenshot 2023-03-24 at 3 10 47 PM" src="https://user-images.githubusercontent.com/67496808/227483720-c8da1c1e-0e82-4023-b642-e830d75645d0.png">

The screenshot given above shows one suggestion, to remove the unused variable.

<img width="1418" alt="Screenshot 2023-03-24 at 3 12 06 PM" src="https://user-images.githubusercontent.com/67496808/227484061-030907d9-7b62-439e-b08e-c3816550396a.png">

<img width="1424" alt="Screenshot 2023-03-24 at 3 12 29 PM" src="https://user-images.githubusercontent.com/67496808/227484119-041c5ba6-123c-4452-8ee5-51985809f2f5.png">

The above two screenshots show two different files, having same functions/same lines of code, and as we know..

![reuse](https://user-images.githubusercontent.com/67496808/227488779-f8c520bb-60b3-4ed8-92f6-21dd7fd710e4.jpeg)

If we would have used the pylint static code analyzer in the first place, we would have made a new custom library storing the same lines of code and reusing the code when needed!

<img width="1420" alt="Screenshot 2023-03-24 at 3 24 35 PM" src="https://user-images.githubusercontent.com/67496808/227488956-7ecf019b-c606-47cd-890e-dfcc838c385a.png">

As you can see in the screenshot given above, the whole repository has been rated 1.48/10 which is very low and could have been avoided if we re-used the same code and followed identation and naming conventions of python correctly.
