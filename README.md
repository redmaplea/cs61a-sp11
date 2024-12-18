# The UCB CS61A in Spring 2011

This repo contained some materials and notes when I learned the UCB cs61a.

## Getting started

The course of this version based on SICP and used UCB Scheme rather than Python3. You could find a ubuntu image of containing UCB STk 4.0.1 environments in res directory. I wish you could use straightly the image to enjoy this course rather than wasting your time on how to install ucb scheme.

You can use docker or chroot enjoy it. Example for docker (Maybe need sudo):
```
cat cs61a-sp11.tgza* > cs61a-sp11.tgz
cat cs61a-sp11.tgz | docker import - cs61a-sp11:latest
docker run -it --name cs61a cs61a-sp11:latest /bin/bash
```

At shell, you could run stk-simply:

![本地图片](./res/sample_1.jpg)

At emacs, you could debug programs by typing M-x stkdb-debug-file:
```
su sicp
cd /home/sicp
emacs 1.scm
```

![本地图片](./res/sample_2.jpg)

![本地图片](./res/sample_3.jpg)

![本地图片](./res/sample_4.jpg)

## Resources

- [Homepage](https://people.eecs.berkeley.edu/~bh/61a-pages)
- [Textbook SICP](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html)

## Assignments

<table>
    <thead align="right">
        <tr>
            <th><h4 align="center">Week</h4></th>
            <th><h4 align="center">Reading</h4></th>
            <th><h4 align="center">Lab</h4></th>
            <th><h4 align="center">Homework</h4></th>
            <th><h4 align="center">Project</h4></th>
            <th><h4 align="center">Lecture</h4></th>
            <th><h4 align="center">Exam</h4></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">1</td>
            <td align="center">1.1</td>
            <td align="center">&#9744;</td>
            <td align="center">&#9744;</td>
            <td align="center"></td>
            <td align="left">
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes">01. functional programming</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=2">02. functional programming</a>
            </td>
            <td align="center"></td>
        </tr>
        <tr>
            <td align="center">2</td>
            <td align="center">1.3</td>
            <td align="center">&#9744;</td>
            <td align="center">&#9744;</td>
            <td align="center"></td>
            <td align="left">
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=3">03. higher-order procedures</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=4">04. higher-order procedures</a>
            </td>
            <td align="center"></td>
        </tr>
        <tr>
            <td align="center">3</td>
            <td align="center">1.2.1 - 1.2.4</td>
            <td align="center">&#9744;</td>
            <td align="center">&#9744;</td>
            <td align="left">&#9744; Project 1: Twenty-one </td>
            <td align="left">
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=5">05. user interface - Alan Kay</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=6">06. user interface - Alan Kay</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=7">07. orders of growth</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=8">08. recursion and iteration</a>
            </td>
            <td align="left"></td>
        </tr>
        <tr>
            <td align="center">4</td>
            <td align="center">2.1, 2.2.1</td>
            <td align="center">&#9744;</td>
            <td align="center">&#9744;</td>
            <td align="center"></td>
            <td align="left">
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=9">09. data abstraction</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=10">10. sequences</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=11">11. Example: calculator</a>
            </td>
            <td align="left">&#9744; Midterm 1 </td>
        </tr>
        <tr>
            <td align="center">5</td>
            <td align="center">2.2.2 - 2.2.3<br>2.3.1, 2.3.3</td>
            <td align="center">&#9744;</td>
            <td align="center">&#9744;</td>
            <td align="left">&#9744; Project 2: A Picture Language </td>
            <td align="left">
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=12">12. hierarchical data</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=13">13. hierarchical data</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=14">14. Example: Scheme interpreter</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=15">15. Example: Scheme interpreter</a>
            </td>
            <td align="center"></td>
        </tr>
        <tr>
            <td align="center">6</td>
            <td align="center">2.4 - 2.5.2</td>
            <td align="center">&#9744;</td>
            <td align="center">&#9744;</td>
            <td align="left"></td>
            <td align="left">
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=16">16. generic operators</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=17">17. generic operators</a>
            </td>
            <td align="left"></td>
        </tr>
        <tr>
            <td align="center">7</td>
            <td align="center">OOP</td>
            <td align="center">&#9744;</td>
            <td align="center">&#9744;</td>
            <td align="left"></td>
            <td align="left">
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=18">18. object-oriented programming</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=19">19. object-oriented programming</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=20">20. object-oriented programming</a>
            </td>
            <td align="left">&#9744; Midterm 2 </td>
        </tr>
        <tr>
            <td align="center">8</td>
            <td align="center">3.1, 3.2</td>
            <td align="center">&#9744;</td>
            <td align="center">&#9744;</td>
            <td align="left">&#9744; Project 3(a): Adventure Game </td>
            <td align="left">
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=21">21. assignment and state</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=22">22. environments</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=23">23. environments</a>
            </td>
            <td align="left"></td>
        </tr>
        <tr>
            <td align="center">9</td>
            <td align="center">3.3.1 - 3.3.3</td>
            <td align="center">&#9744;</td>
            <td align="center">&#9744;</td>
            <td align="left">&#9744; Project 3(b): Adventure Game </td>
            <td align="left">
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=24">24. mutable data 1</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=25">25. mutable data 2</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=26">26. vectors</a>
            </td>
            <td align="left"></td>
        </tr>
        <tr>
            <td align="center">10</td>
            <td align="center">3.4</td>
            <td align="center">&#9744;</td>
            <td align="center">&#9744;</td>
            <td align="left"></td>
            <td align="left">
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=30">30. client-server programming</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=31">31. concurrency</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=32">32. concurrency</a>
            </td>
            <td align="left"></td>
        </tr>
        <tr>
            <td align="center">11</td>
            <td align="center">3.5.1 - 3.5.3<br>3.5.5<br>Therac-25</td>
            <td align="center">&#9744;</td>
            <td align="center">&#9744;</td>
            <td align="left"></td>
            <td align="left">
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=33">33. streams</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=34">34. streams</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=35">35. therac-25</a>
            </td>
            <td align="left">&#9744; Midterm 3 </td>
        </tr>
        <tr>
            <td align="center">12</td>
            <td align="center">4.1<br>Mapreduce</td>
            <td align="center">&#9744;</td>
            <td align="center">&#9744;</td>
            <td align="left"></td>
            <td align="left">
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=36">36. metacircular evaluation</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=37">37. metacircular evaluation</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=38">38. mapreduce</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=39">39. mapreduce</a>
            </td>
            <td align="left"></td>
        </tr>
        <tr>
            <td align="center">13</td>
            <td align="center"></td>
            <td align="center">&#9744;</td>
            <td align="center">&#9744;</td>
            <td align="left">&#9744; Project 4(a): Logo interpreter</td>
            <td align="left">
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=40">40. analyzing evaluator</a>
            </td>
            <td align="left"></td>
        </tr>
        <tr>
            <td align="center">14</td>
            <td align="center">4.2 - 4.3</td>
            <td align="center">&#9744;</td>
            <td align="center">&#9744;</td>
            <td align="left">&#9744; Project 4(b): Logo interpreter</td>
            <td align="left">
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=41">41. lazy evaluator</a>
            </td>
            <td align="left"></td>
        </tr>
        <tr>
            <td align="center">15</td>
            <td align="center">4.4.1 - 4.4.3</td>
            <td align="center">&#9744;</td>
            <td align="center">&#9744;</td>
            <td align="left"></td>
            <td align="left">
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=42">42. logic programming</a><br>
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=43">43. logic programming</a>
            </td>
            <td align="left"></td>
        </tr>
        <tr>
            <td align="center">16</td>
            <td align="center"></td>
            <td align="center"></td>
            <td align="center"></td>
            <td align="left"></td>
            <td align="left">
                <a href="https://www.bilibili.com/video/BV12t411p7jA?spm_id_from=333.788.videopod.episodes&p=44">44. review</a>
            </td>
            <td align="left">&#9744; Final </td>
        </tr>
    </tbody>
</table>

## Refrences and Thanks

Thanks a lot for the UCB, MIT, Brian Harvey and other people who offered the high-quality resources to this course.

[decuser](https://decuser.github.io/development/scheme/ucb-stk/2023/06/27/ucb-stk-for-harveys-cs61a.html)

[bzliu94](https://github.com/bzliu94/cs61a_fa07)

[zackads](https://github.com/zackads/sicp)

[theurere](https://github.com/theurere/berkeley_cs61a_spring-2011_archive)

[romanbird](https://romanbird.github.io/sicp/)
