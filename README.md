### Hi I'm Yian. 👋 🌳

<!--
**clikiii/clikiii** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

Currently a final year CS student at [City University of Hong Kong](https://www.cityu.edu.hk/).

I have moved most of the open-sourced hobby projects/course projects to this account. 

I interned as a Backend Developer previously. You may find other work projects [here](https://github.com/YianW).


#### Actually I am a robot 🤖️
```Java
import java.util.ArrayList;
import java.util.Arrays;

public class Robot {
    private String firstName;
    private String lastName;
    private String major;
    private String university;
    private ArrayList<String> mainLanguages;
    private String others;
    
    public Robot() {
        this.firstName = "Yian";
        this.lastName = "Wang";
        this.major = "Computer Science";
        this.university = "CityU HK";
        this.mainLanguages = new ArrayList<String>(
            Arrays.asList("Python", "Java", "JavaScript", "Golang", "C++")
        );
        this.others = "There is still a long way to go, but I will keep moving. By the way, I like trees.";
    }

    public static void main(String[] args) {
        Robot yianWang = new Robot();
        System.out.printf("yianWang says: \"%s\"", yianWang.others);
    }
}
```
