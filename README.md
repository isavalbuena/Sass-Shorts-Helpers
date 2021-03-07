<p align="center">
  	<a href="" rel="noopener">
		<img width=200px height=200px src="src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/288_Sass_logo-512.png" alt="Project logo">
	</a>
</p>
 
<h3 align="center">Sass Helper's</h3>

---

<p align="center"> Few lines describing your project.
	<br> 
</p>

## 📝 Table of Contents

- [padding](#padding)
- [padding-top](#pt)
- [padding-bottom](#pb)
- [padding-left](#pl)
- [padding-right](#pr)
- [padding-horizontal](#ph)
- [padding-vertical](#pv)
<!-- - [Acknowledgments](#acknowledgement) -->

<!-- ## 🧐 About <a name = "about"></a>

Write about 1-2 paragraphs describing the purpose of your project. -->

## Getting Started <a name = "getting_started"></a>

Ready for Copy and paste in your Scss project!

## Padding <a name = "padding"></a>

The repetitions are increasing from 5 to 5 from 0 to 30.

#### SCSS

```scss
@for $i from 0 through 30{
    $m: 5; // The repetitions are increasing from 5 to 5 from 0 to 30.
	$p: ($m * $i)px;
    $p_label: ($m) * $i;

    .p-#{$p_label} { 
        padding: $p !important;
    }
}
```
#### CSS
```css
.p-0 {
  padding: 0 px !important;
}
.p-5 {
  padding: 5 px !important;
}
.p-10 {
  padding: 10 px !important;
}
.p-15 {
  padding: 15 px !important;
}
...
```
## PADDING TOP <a name = "pt">:top:</a>

The repetitions are increasing from 5 to 5 from 0 to 30.

#### SCSS

```scss
@for $i from 0 through 30{
    $m: 5;
    $p: ($m * $i)px;
    $p_label: 5 * $i;

    .p-t-#{$p_label} { 
        padding-top: $p !important;
    }
}
```
#### CSS
```css
.p-t-0 {
  padding-top: 0 px !important;
}
.p-t-5 {
  padding-top: 5 px !important;
}
.p-t-10 {
  padding-top: 10 px !important;
}
.p-t-15 {
  padding-top: 15 px !important;
}
...
```


### Installing

A step by step series of examples that tell you how to get a development env running.

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo.

## 🔧 Running the tests <a name = "tests"></a>

Explain how to run the automated tests for this system.

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## 🎈 Usage <a name="usage"></a>

Add notes about how to use the system.

## 🚀 Deployment <a name = "deployment"></a>

Add additional notes about how to deploy this on a live system.

## ⛏️ Built Using <a name = "built_using"></a>

- [MongoDB](https://www.mongodb.com/) - Database
- [Express](https://expressjs.com/) - Server Framework
- [VueJs](https://vuejs.org/) - Web Framework
- [NodeJs](https://nodejs.org/en/) - Server Environment

## ✍️ Authors <a name = "authors"></a>

- [@kylelobo](https://github.com/kylelobo) - Idea & Initial work

See also the list of [contributors](https://github.com/kylelobo/The-Documentation-Compendium/contributors) who participated in this project.

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- Hat tip to anyone whose code was used
- Inspiration
- References
