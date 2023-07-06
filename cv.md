# Mikalai Serhiyenia

![photo](/assets/img/photo.jpeg)

## Contacts

email: _mikalai.serhiyenia@gmail.com_  
tel (pl): _+48572119619_  
tel (by): _+375295662268_  
discord: _mikalaiserhiyenia_  
telegram: _@mikalaiserhiyenia_

## About myself

<p>I graduated from the Philology Department of Belarusian State University with a specialization in "Philologist. Teacher of Russian Language and Literature". I worked as a proofreader and editor at the children's literature publishing house "Azbookvarik" for one year. Then, for a year, I worked as a freelance copywriter. For the past 10 years, I have been working as a content manager at "HOLODILNIK.RU". My responsibilities included content management, copywriting, proofreading and editing, formatting, and publishing texts on the website, writing advertising texts, creating infographics, and preparing presentations.</p>
<p>During my work, I acquired basic skills in HTML/CSS and became passionate about web development. In 2019, I graduated from the "Web Application Development with JavaScript" program at the High-Tech Park Educational Center (IT-Academy), where I gained fundamental knowledge of programming in JS.</p>
<p>Due to my relocation to a new country, I would like to dive deeper into studying JavaScript and utilize RS School to enhance my job search opportunities.</p>

## Skills

- HTML5
- CSS3
- JavaScript Basics
- Git, GitHub
- VS Code

## Code examples

`Human Readable Time`

```
function humanReadable (seconds) {
  function addZero(num) {
    return (num < 10) ? `0${num}` : num;
  }
  let hh = Math.floor(seconds / 3600);
  let mm = Math.floor((seconds % 3600) / 60);
  let ss = Math.floor((seconds % 3600) % 60);
  return `${addZero(hh)}:${addZero(mm)}:${addZero(ss)}`;
}
```

`Count characters in your string`

```
function count(string) {
  let charCount = {};
  for (let char of string) { charCount[char] ? charCount[char]++ : charCount[char]=1 }
  return charCount;
}
```

`Find the unique number`

```
function findUniq(arr) {
  arr.sort((a,b)=>a-b);
  return arr[0]==arr[1]?arr.pop():arr[0];
}
```

## Experience

- **Azbookvarik** _(2011-2012)_ - proofreader, editor
- **HOLODILNIK.RU** _(2013-2023)_ - content manager, copywriter, editor, proofreader

## Education

- **Belarusian State University**  
  Russian Language and Literature  
  _Sep 2006 - Jun 2011_
- **High-Tech Park Educational Center (IT-Academy)**  
  Web Application Development with JavaScript  
  _Nov 2018 - May 2019_

## Language

- **English** - Intermediate/Upper-intermediate
- **Russian** - Native
- **Belarusian** - Advanced
- **Polish** - Beginner, Elementary
