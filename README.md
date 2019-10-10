# Hyperledger-study-29

하이퍼레져 앱 만들기 실습 29일차 - node.js 공부

출처 : https://opentutorials.org/course/3332/21061

1. Number

        console.log(1+1);
        console.log(4+1);
        console.log(2*2);
        console.log(10/2);

2. String

        console.log('1'+'1');

3. variable

        var a = 1;
        console.log(a);
        a = 2;
        console.log(a);

4. Template

        var name = 'k8805';
        // String literals
        var letter = 'Dear '+name+'\n\nLorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. '+name+' Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa egoing qui officia deserunt mollit anim id est laborum. '+name;

        // Template literals
        var letter = `Dear ${name}

        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. ${name} Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. ${1+1} Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa egoing qui officia deserunt mollit anim id est laborum. ${name}`;

        console.log(letter);

5. boolean

        console.log(true);
        console.log(false);

6. comparison

        console.log(1==1); //true
        console.log(1==2); //false
        console.log(1>2); //false
        console.log(1<2); //true
        console.log(1===1); //true
        console.log(1===2); //false
        name == 1;

7. variable2

        var name = 'k8805';
        var letter = 'Dear '+name+' Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. '+name+' Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa egoing qui officia deserunt mollit anim id est laborum. '+name;
        console.log(letter);


8. program1

        console.log('A');
        console.log('B');
        console.log('C1');
        console.log('D');

9. program2

        console.log('A');
        console.log('B');
        console.log('C2');
        console.log('D');

10. 조건문

        console.log('A');
        console.log('B');
        if(false){
            console.log('C1');
        }else{
            console.log('C2');
        }
        console.log('D');
