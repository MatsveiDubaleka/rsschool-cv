# Markdown CV

## Mathew Duboleko

### My Contacts

_Email: matvey.duboleko@yandex.ru_
_Tel: +375-44-715-11-03_
_City: Minsk, Belarus_

---

### My social networks

---

_GitHub_ - **https://github.com/MatsveiDubaleka**
<br>_Discord_ - **chotkigus #1377**
<br>_Telegram_ - **MatsveiDubaleka**

---

### About me

-I'm 18. I'm enjoying sport, web-development and computers.
I'm cheerful and very responsible person. I can easily adapt to any conditions.
Also, I have ability to talk and conduct in 2 languages.
I'm fast learner. I'm interested in everything that surrounds me. 
I like to communicate with new people, like to read and otherwise develop.
I want to achieve new goals, so thats why I'm here. 
In future i want begin my career like a Web Developer in company and
after 5 years grow to TeamLeader.

> I extremely motivated to become a good programmist

---

### Skills

HTML & CSS, JS, Git.

---

### Code examples

#### Drag-nd-Drop
```
const item = document.querySelector(".item");
const placeholders = document.querySelectorAll(".placeholder");

item.addEventListener("dragstart", dragstart);
item.addEventListener("dragend", dragend);

for (const placeholder of placeholders) {
  placeholder.addEventListener("dragover", dragover);
  placeholder.addEventListener("dragenter", dragenter);
  placeholder.addEventListener("dragleave", dragleave);
  placeholder.addEventListener("drop", dragdrop);
}

function dragstart(event) {
  //   console.log("drag start", event.target);
  event.target.classList.add("hold");
  setTimeout(() => {
    event.target.classList.add("remove");
  }, 0);
}

function dragend(event) {
  //   console.log("drag end", event.target);
  event.target.classList.remove("hold", "remove");
}

function dragover(event) {
  event.preventDefault();
}

function dragenter(event) {
  event.target.classList.add("hovered");
  console.log("drag enter");
}

function dragleave(event) {
  event.target.classList.remove("hovered");
  console.log("drag leave");
}

function dragdrop(event) {
  event.target.append(item);

  event.target.classList.remove("hovered");
}
```
---

### Relevant experience

#### Covid Finder / AIIJC (Sberbank)

> _Finalist of International Artificial Intelligence Competition for Children Sberbank_

##### May 2021 - November 2021

* Developed the website
* Added the framework
* Supported the system of detection defeated lungs

__Link:__ [Github](https://github.com/Vovinsa/COVID_classification_and_segmentation "Covid Finder")

---

### Education

#### RSSCHOOL

###### February 2021 - May 2021

I started to learn JS, when i had joined RS-SCHOOL courses. 
I've made websites 'Online Zoo', 'WildHunt', 'Virtual Piano' and so on.

#### HTML Academy

###### December 2020 - January 2021

Over 3 months ago i started to perform new courses, there were so exciting.
Tasks in courses, whiсh put me down in despire, but I did them successfully anyway.
HTML Academy helped me to make websites in different ways.
It was a good experience for me, and i want to pass difficulties and be stronger in web-development.

#### Yandex Praktikum

###### September 2020 - December 2020

This is my first acquaintance with development of websites. At first it was so hard, but when i started
to get deaper and deaper, i understood that it's so easy. If you want to be a good developer you must spent at least
6 hours to make what you want. And for me it was such a good experience to make something new and interesting
In yandex praktikum i studied for 3 months, during this time i understood that i want to connect my carreer with
development of websites.

---

### English

My English level is B1 - B2.
I fluently read and write in English. I speak with a native speaker(my sister, who was born in USA).
Every year my sister arrives from USA, and we talk about different events.

---