# DARYA KONCHYTS
![personal photo](https://scontent-frt3-1.xx.fbcdn.net/v/t1.18169-9/11813460_977730792289812_4647594510029455373_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=174925&_nc_ohc=lH4NITSi4_EAX_xjV3o&_nc_oc=AQkyDnowcA8JTRQA_de6ukXwMGhZIcUYXG4BNY2BgUFh3Q0fHdnWlk1R4VHlXXo6ti4&_nc_ht=scontent-frt3-1.xx&oh=00_AT9imcyUXoDxBvBb2FJfCdGCP4d9G2ko2XSPV_QlQE_FZw&oe=62AD6768)

## __Junior Frontend Developer__
### Contact information:

#### `Phone:` +375 29 693 45 81

`E-mail:` forexamplednk@gmail.com

`Telegram:` @tooldnk


### About myself:

Worked for six years in a cafe at the bar. I realized that I needed to change my life and immerse myself in something new and interesting that I had never encountered before.

Six months ago, I started studying layout on my own, then, after going through several stages of an interview, I got into Mate Academy courses, which I could not finish due to lack of time.

I am interested in web development because this profession provides endless opportunities for professional growth,
in addition, there are a huge number of free quality resources for self-education and a large community of developers.

I believe that my ability to learn and acquire new skills will help me become an experienced Frontend Developer.
### Skills and Proficiency:
* JavaScript extended

* HTML, CSS / SCSS advanced

* SQL basics

* Git, GitHub

* VS Code


### Landing example: <br>
https://dnk-forexample.github.io/Eco_cosmetics/

### Code example:
_Implement calculateAverageAgeDiff function. The function returns an average age difference between a child and his or her mother in the array. (A mother's age at child birth). If onlyWithSon is specified then function calculates age difference only
 for sons and their mothers._
 
``` javaScript
function calculateAverageAgeDiff(people, onlyWithSon) {
  const women = people.filter(woman => woman.sex === 'f'
  && people.some(child => child.mother === woman.name));
  const children = people.filter(man => onlyWithSon ? man.sex === 'm'
  && people.some(person => man.mother === person.name)
    : people.some(person => man.mother === person.name));
  const diffAge = children.map(child =>
    child.born - women.find(person => person.name === child.mother).born
  );

  return diffAge.reduce((a, b) => a + b) / children.length;
} 
```


### Courses:
* `HTML and CSS` (Basics, Extended, Adviced), _at Mate Academy_

* `JavaScript` (Basics, Extended), _at Mate Academy_

* `JavaScript/Front-end. Stage 0`, _at RS School in progress_


### Languages:
* `English` - High Pre-Intermediate, _at International House school_

* `Russian` - Native,

* `German` - Elementary,


