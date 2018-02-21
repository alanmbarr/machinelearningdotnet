- title : Intro to Machine Learning with Dot Net 
- description : Machine Learning with Dot Net 
- author : Alan Barr 
- theme : white 
- transition : none 

*********************************

<section data-background-video="https://s3.amazonaws.com/www.alanmbarr.com/aibo.mp4" data-background-color="#000000" data-background-video-loop>
</section>
<table>
<tr><td class="noborder" style="width:75%;">
# <div id="fancy" class="title streamster">Machine Learning .NET</div>
</td><td class="noborder" style="width:25%;">
<br>
<br>
<br>
<br>
<br>
</td></tr><tr><td>
## <div class="shadow alien" style="color:#b967ff;">Alan Barr</div>
</td></tr>
</table>

**********************************

---

- data-background : #01cdfe

# What is Machine Learning?

<script>
let stopAnimating = function(event){
    let title = $("#fancy")
    if(event.indexh === 1 && event.indexv === 1){
        title.removeClass("title");
    }
    if(event.indexh === 0 && event.indexv === 0 && !(title.hasClass("title"))){
        title.addClass("title");
    }
}
$(function(){
Reveal.addEventListener('slidechanged', stopAnimating);
});
</script>

---

- data-background : #ff71ce

<h1 style="color:white;">Isn't Machine Learning just statistics?</h1>

---

- data-background : #fffb96

# Warning... Clean Data required

- Garbage In Garbage Out
- Context is King 
- Big data is not necessarily helpful
- Overfitting - prediction is suspiciously good

---

- data-background : #01cdfe

## Focused on prediction, not just analysis

- Classification : Who's a good dog (Breed)?
- What two or multiple categories does an item fit into
![Kaggle Border Collies](images/kaggle_border_collies.png)

---

### Regression : values are continuous and have a constant slope
![uhhh](https://imgs.xkcd.com/comics/extrapolating.png)

---

### Clustering
- Identify a relationship between things without predefined labels
- Outlier/Anomaly detection
- insert image here

---

### Recommendation
![You might also like](images/grocery.jpg)