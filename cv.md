# Aeleh Kudzelka #
## Contacts ##

+ *Phone number -* +375-25-631-52-83
+ *Email -* Krendilek766@gmail.com
+ *Instagram -* [oleg.kudelko](https://www.instagram.com/oleg.kudelko)
+ *Git -* [Krendil766](https://github.com/Krendil766) 
+ *Linkedin -* [Олег Куделько](https://www.linkedin.com/in/%D0%BE%D0%BB%D0%B5%D0%B3-%D0%BA%D1%83%D0%B4%D0%B5%D0%BB%D1%8C%D0%BA%D0%BE-14ab561a3/)

## Summary ##
> I am 27 years old. I live in the city of Minsk. Married, no children.
I am fond of sports (BISON RACE), snowboarding, motorcycling, I love hockey (I drown for Washington Capitals). We love to travel with my wife, have visited many countries of the world.

>From 2010 to 2015 he studied VF BSU on a specialty Geoinformation systems.
From 2015 to 2020, he worked in the Ministry of Defense of the Republic of Belarus.
At the moment, take part in TeachMeSkills courses on Front End specificity.

> I love to study. I quickly master new technologies and large amounts of information myself. I possess highly motivation, self-discipline and the ability to work with the minimum of supervision.

## Skills ##
* JavaScript
* React
* Redux
* Hooks
* Webpack
* HTML
* CSS
* SASS/SCSS
* Bootstrap
* jQuery
* Gulp
* GIT
* Visual Studio Code
* Adobe Photoshop, Adobe Illustrator
  
## Education ##
1. 2010-2015 - Belarusian State University (specialty Geoinformation systems)
2. 2015-2020 - Ministry of Defense of the Republic of Belarus
3. 2019-2021 - Glo Academ webinars
4. 2019-2021 - TeachMeSkills courses

## Code examples ##

```javascript

class FetchData {
    getResourse = async url => {
        const res = await fetch(url);
        if (!res.ok) {
            throw new Error('Произошда ошибка ' + res.status)
        }
        return res.json();
    }
    getPost = () => {
        return this.getResourse('db/dataBase.json')
    }
}
class Posts {
    constructor({
        posts = []
    } = {}) {
        this.posts = posts;
    }
    addPost = tweet => {
        this.posts.push(new Post(tweet))
    }
    deletePost(id) {
        this.posts = this.posts.filter(item => {
            return item.id !== id;
        })
    }
    likePost(id) {
        this.posts.filter((item => {
            if (item.id === id) {
                item.changeLike()
            }
        }))
    }
}
```

## English ##
  __A2__. 
