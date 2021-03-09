# Assignment For AsIndiaInnovation

Question 1 : Used C++ Language.

<b>Approach1</b>
1. In this approach I used an array to keep track of numbers which are not present in n-1 elements.
2. First i declare an array with n+1 elements then fill all the entries of array with false (means element is not present).
3. Then i have taken each of n-1 elements and marks that entry(index) of array to be true (means element is present).
4. Then looping the array and printing that value which has false in it (It means it is not present in given n-1 elements).
5. Solving through this method i also applied constraint by making sure that no one hits same element twice or goes out of bound.

<b>Approach2</b>
1. In this approach I have taken sum of 1 to n number using n(n+1)/2.
2. Then i started subtracting each element of n-1 elements from the above sum.
3. After substracting all the elements from the above sum. The remaining value of sum will be the element which is not present in n-1 elements.
4. This method is more efficient.
5. In this method i have not check constraint i.e duplicates , range bounds . I assumed correct inputs according to constraints are given by user.

Question 2 : Used React.js (Project live running at <a href='https://review-movie-system.herokuapp.com/'>https://review-movie-system.herokuapp.com</a>)

1. Deployed using heroku.
2. PreBuild version is uploaded to github along with all source file.
3. Used Material-Ui For the development Of UI.
4. As there is no mention of dedicated backend, I have used localStorage to store all data.
5. A simple login form is made. Using this login form old user could login with their password or email. If a new user logsIn then the record of him is saved in localStorage.And user is considerd to be logged in. Next time he will log through the application it will required same username or password.
6. For rating interface there is modal which shows a form for rating a movie and below that we have older reviews(done by other person) show there.
7. One can check demo through the above heroku deployed link or can download q2-movie-review folder and then by using command npm i in the root of the folder throug CLI.![image](https://user-images.githubusercontent.com/56810787/110410489-f6e80e00-80ae-11eb-8d29-4796a382b235.png)
![image](https://user-images.githubusercontent.com/56810787/110410542-0d8e6500-80af-11eb-96b5-b2c1a5b459e0.png)
![image](https://user-images.githubusercontent.com/56810787/110410598-24cd5280-80af-11eb-844d-8b9ee4931783.png)
![image](https://user-images.githubusercontent.com/56810787/110410638-34e53200-80af-11eb-923a-02e5ca48feb6.png)
![image](https://user-images.githubusercontent.com/56810787/110410663-43cbe480-80af-11eb-9fb1-7cc25776fcdd.png)
![image](https://user-images.githubusercontent.com/56810787/110410695-50503d00-80af-11eb-98c8-12ea146a7ff4.png)
![image](https://user-images.githubusercontent.com/56810787/110410737-64943a00-80af-11eb-8448-ba7721ed7684.png)
