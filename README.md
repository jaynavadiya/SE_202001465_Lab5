# SE_202001465_Lab5 Submission
This is a submission repository for the Lab 5 in which we understand Static Analysis Tools for debugging and other purposes for writing cleaner code

# Jaykumar Navadiya - 202001465

## Used tool for static analysis of code: Pylint
## IDE used for the purpose: Pycharm

### I have used my [own repository](https://github.com/jaynavadiya/TF3-Video-Streaming-With-RTSP-And-RTP) which was a project in last semester for the course of Computer Networks and was fully written in Python.

#### Analyzing [Client.py](https://github.com/jaynavadiya/TF3-Video-Streaming-With-RTSP-And-RTP/blob/main/Client.py) using Pyling in Pycharm's integrated local terminal...

<img width="1420" alt="Screenshot 2023-03-24 at 2 43 44 PM" src="https://user-images.githubusercontent.com/67496808/227476314-4188e638-956c-4615-9a00-2e14e84131da.png">

The above screenshot mostly shows identation issues identified with Pylint.

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
