## Piotr Stashukevich

![Logo](https://i.ibb.co/r6465gz/photo.jpg)


* **E-mail:** <petriken82@gmail.com>
* **Telephone number:** +375 29 7014145
* **Telephone number:** +375 29 1260445
* **Github:** <https://github.com/petriken>

### Summary

> Моя цель - получить как можно больше знаний, умение писать лаконичные алгоритмы, хорошо изучить `core js` для трудоустройства frontend-разработчиком в компанию. В дальнейшем, в зависимости от проекта, более глубокое погружение в разработку. На текущей работе совмещаю разработку проектов и должность руководителя проектного подразделения. Имею большой опыт общения с заказчиками и согласующими организациями - полезные `soft skills` при устройстве в компанию, полагаю это поможет стать в дальнейшем `teamlead'ом`. Готов много учиться, желание быть востребованным разработчиком крайне велико. Твердо намерен быть частью этой МАГИИ...

### Technical Skills

**Programming languages and technologies:** JavaScript, HTML, CSS/SASS

**Frameworks and Libraries from 2018-Q3:** little experience of use React, jQuery, Redux, bootstrap, reactstrap

**Tools:** VS Code, Chrome Dev Tools, little experience of use GIT 

**Other skills:** sociability, power supply design (current work)

### Code example

```
function setScore(mentor, name) {
  return getStudent(mentor).map(studentName => (
    <td
      style={{ textAlign: "center" }}
      className={
        !getScore(studentName, getCurrentMentor(mentor), name) &&
        getTaskStatus(name) === "Checked"
          ? "failed"
          : getTaskStatus(name)
      }
      key={studentName}>
      <a
        className="link"
        rel="noopener noreferrer"
        target="_blank"
        href={getPrTask(studentName, getCurrentMentor(mentor), name)}>
        {getScore(studentName, getCurrentMentor(mentor), name)}
      </a>
    </td>
  ));
}
```
```
const loginPattern = /\/([^\/]+)\/?$/;
const getMentor = (sheet, currentRow) => {
  const mentorData = {
    name: sheet[fieldMappingMentor.name + currentRow].v,
    Surname: sheet[fieldMappingMentor.Surname + currentRow].v,
    ID: `${sheet[fieldMappingMentor.name + currentRow].v} ${
      sheet[fieldMappingMentor.Surname + currentRow].v
    }`,
    Github: sheet[fieldMappingMentor.Github + currentRow].v,
    GithubLogin: sheet[fieldMappingMentor.Github + currentRow].v.split(
      loginPattern
    )[1],
    mentorStudents: {}
  };
return mentorData;
}
```

### Professional Experience

**RSSchool 2018-Q3**

* **Game:** 

 Project: <https://petriken.github.io/padawan-s_wisdom>  
Environment: HTML (+canvas), CSS/SASS, JavaScript, jQuery

* **Culture portal**

  Project: <https://petriken.github.io/CodeJam-5_Dream-Team> - `ProducerCard` and partially `ProducersPage`  
Environment: HTML, JavaScript, React, Redux

* **Mentor-dashboard**

 Project: <https://petriken.github.io/rss-mentor-dashboard>  
Environment: HTML, CSS, JavaScript, React

**Community Lab**

* **Mentor-dashboard**

 Project: <https://petriken.github.io/rss-mentor-dashboard>  
Position: developer  
Environment: HTML, CSS, JavaScript, React

### Education

The Rolling Scopes School (https://school.rollingscopes.com/), 09.2018 – 02.2019  
Belarusian National Technical University, Information Technologies and Robotics, Minsk, Belarus                                                                             
Specialist – Electric Drive and Automation of Industrial Plants and Technological Complexes ( Electrical Engineer )

### English

Pre-intermediate (I attend courses)
