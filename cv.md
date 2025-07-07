
 
### Curriculum vitae

## Name: 
Julia Ott

## Contact Information: 
[LinkedIn](https://de.linkedin.com/in/yulia-ott-bb306b1a1) 
[yuliia_ott@proton.me](mailto:yuliia_ott@proton.me)



## Self-Introduction: 
Hello, I am AnotherJulila. My passion for software development started in 201* and since then I have finished a Software Engineering Bachelor's program.   I have also completed a Master's in Business Administration and found a dream job. I believe in lifelong learning and am constantly updating my skills to stay current with industry trends


## Experience
- **Software Developer**
  - Cycos AG, Aachen
  - Duration: Oktober 2021 - now
  - Responsibilities and achievements:
        - Developed and maintained frontend applications using C#.
        - Contributed to an Angular project, focusing on frontend development and enhancing user experience (UX).

## Skills :
Java, C#, C++, Python, Data Science, Machine Learning and etc. 

## Code Examples: 
Binary tree task that i have written during Bachelor study
```
 /**
     *
     * @param data
     *            Datensatz
     * @return true: Datensatz wurde eingefuegt; false: Datensatz war schon
     *         vorhanden.
     */
    public boolean insert ( int data){
        if(root == null){
            root = new Node(data);
            return true;
        }
        Node temp = root;
        while(temp.data != data){
            if( data> temp.data) {
                if (temp.right == null) {
                temp.right = new Node(data);
                return true;
            } else {
                temp = temp.right;
            }
        }
        else if (temp.left == null) {
                temp.left = new Node(data);
                return true;
            } else {
                temp = temp.left;
            }
            }
            return false;
    }
```

## Education
- **Bachelor in Scientific Programming**
  - Fh Aachen
  - 2015 - 2018

- **Master in Bussiness Administration**
  - RWTH Aachen
  - 2019 - 2024

## Fun fact :
I do really love reading. 


## Languages:  
* German : C1  
* English : C1 
* Russian : C2 
* Ukrainian: C2 
* Spanish: A1
 