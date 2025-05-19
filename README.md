# Lab 7 - Khang Nguyen

1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
- I would place my automated test winith a Githubaction that runs whenever the code is pushed. I don't think the second option is a good idea because if I was manually running the test there would be a higher chance of me making a mistake. The third option could be bad too because what if we see a bunch of bugs after everything is done and we didn't catch it when it first occured. This leaves the first option because it helps catch bugs early on. If everything automatic test passes, then we are able to safely merge without any conflicts. This also stops us from depending on ourselves to run the test manually. 

2. Would you use an end to end test to check if a function is returning the correct output? (yes/no)
- No. It wouldn't make sense if we are using E2E testing to see if something return correct. The whole point of E2E is to simulate a user interacting with your app. Checking if a function is returning a correct output is unit testing. 

3. What is the difference between navigation and snapshot mode?
- Navigation mode simulates the whole page when loading and than analyzing it (checks for overall perfermance) and snapshot mode is more for static view and does not simulates user interaction (which makes it more faster).

4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
- Something that can lower the load time is compressing the images on the website, maybe making it smallers. 
- Serve images in next-gen formats
- add a ```<meta name="viewport">``` tag with width or initial-scale

