# basics
Selection sort sample;
[22,27,16,2,18,6] ;

[2,22,27,16,18,6]
[2,6,22,27,16,18]
[2,6,16,22,27,18]
[2,6,16,18,22,27]
[2,6,16,18,22,27]

bigO for this example is O(n).

Insertiom sort type of above sample;
[22,27,16,2,18,6] ;

[22,27,16,2,18,6]
[16,22,27,2,18,6]
[2,16,22,27,18,6]
[2,16,18,22,27,6]
[2,6,16,18,22,27]

bigO for this example is O(n^2).

we can talk about the number of 18 is avarage case in both of situations, because for placing the number 18, we did not make the sort until the last placement. ıf we did, then we could have talked about worst case.


Selection sort for first four steps;

[7,3,5,8,2,9,4,15,6];

[2,7,3,5,8,9,4,15,6]
[2,3,7,5,8,9,4,15,6]
[2,3,4,7,5,8,9,15,6]
[2,3,4,5,7,8,9,15,6]