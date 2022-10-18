### Scoring criteria
| Criteria                                                                                                                                                                                             | Points                   |
|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------|
| Deployed on `gh-pages`, the link is submitted                                                                                                                                                        | 10                       |
|GM chck <p style="text-align: right;">Deployed on `main`</p>                                                                                                                                                        | <p style = "color: red;">0</p>                      |
| The layout pass the validation (https://validator.w3.org/). <br/>"Document checking completed. No errors or warnings to show."<br/> in case no errors, but exist warning                             | <br/>10 <br/>5           |
|GM chck <p style="text-align: right;">exist warning Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.</p>                             | <p style = "color: yellow;">5</p>           |
| There are semantic tags in the code (pay attention, they should be logically used, not just for points)<br/> `header`, `main`, `footer` <br/> `nav` <br/>  only one `h1` for page <br/> several `h2` | <br/>5<br/>5<br/>5<br/>5 |
|GM chck <p style="text-align: right;">semantic tags <br>`header`, `main`, `footer` <br/> `nav` <br/>  only one `h1` for page <br/> several `h2` </p> | <p style = "color: green;">5</p><p style = "color: green;">5</p><p style = "color: red;">0</p><p style = "color: green;">5</p> |
| Footer contains link to your github , date (month, year), course logo with the link                                                                                                                      | 10                       |
|GM chck <p style="text-align: right;">Footer contains links</p>                                                                                                                                           |<p style = "color: green;">10</p>                     |
| Present css styles                                                                                                                                                                                   | 10                       |
|GM chck <p style="text-align: right;">Css styles </p>                                                                                                                                             | <p style = "color: green;">10</p>                     |
| Horizontal centegreen layout (decreasing the browser width - the layout still in the center)                                                                                                           | 10                       |
| GM chck <p style="text-align: right;">decreasing the browser width - the layout still in the center </p>                                                                             | <p style = "color: green;">10</p>                       |
| The photo exist, the alt attribute is present                                                                                                                                                        | 10                       |
| GM chck <p style="text-align: right;">photo exist, the alt attribute is present  </p>                                                                        | <p style = "color: green;">10</p>                       |
| Navigation (contacts and skills) did with `ul > li` or `ul > li > a`                                                                                                                                 | 10                       |
| GM chck <p style="text-align: right;"> 'contacts' has `ul > li` or `ul > li > a` links(navigation) missing </p>                                                                          | <p style = "color: yellow;">5</p>                       |
| Brief information about yourself                                                                                                                                                                     | 5                        |
| GM chck <p style="text-align: right;"> information about yourself in 'about me' </p>                                                                                                         | <p style = "color: green;">5</p>                       |
| Contacts                                                                                                                                                                                             | 5                        |
| GM chck <p style="text-align: right;"> contacts present </p>                                                                                                         | <p style = "color: green;">5</p>                       |
| Skills                                                                                                                                                                                               | 5                        |
| GM chck <p style="text-align: right;"> skills present </p>                                                                                                         | <p style = "color: green;">5</p>                       |
| Code examples ( using appropriate symbols or tags)                                                                                                                                                   | 5                        |
| GM chck <p style="text-align: right;"> missing code example </p>                                                                                                         | <p style = "color: red;">0</p>                       |
| Project examples ( if you have no, add the link to CV task)                                                                                                                                          | 5                        |
| GM chck <p style="text-align: right;"> Project examples</p>                                                                                                         | <p style = "color: green;">5</p>                       |
| Education and English level                                                                                                                                                                          | 5                        |
| GM chck <p style="text-align: right;"> Education and English leve</p>                                                                                                         | <p style = "color: green;">5</p>                       |

**Total score** available 120 points

<p style = "color: green; font-size: 20px;"><b>Check Score 90</b></p>

Comments for check:
 - Page deployed from `master` branch
 - warning from validator. `<img src="#" alt="Lama" class="left__image"/>` you must remove backslash  `<img src="image" alt="Lama" class="left__image">`
 - missing `nav` tag. I see no use for navigation, but you could make one link block as nav. for example contacts.
 - navigation (skills and contacts) and `ul` and `li` usage. partialy conatacs are not in `ul`
 - and no `code` in document.


 - <b>Suggestion</b>
    - in style.css you marked property with `*`(all document) and `display: inline-block;` that made even head visible. try to avoid mark everything. use `body` instead of `*` if you want give same properties for all
    - logo in footer is very big. since img already is in container (your case a tag) you can control size for example `width: 10%;` for img
    
