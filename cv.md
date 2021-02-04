# Zhenya Dubinkin

## Contacts

*Phone:* +380955291493

*Email:* jeka54390@gmail.com

*Web-site:* [My page in github](https://ZhenyaDybinkin.github.io/rsschool-cv/cv)

*Telegram:* [Zhenya_Flan](https://t.me/zhenya_flan)


## Brief information about yourself

> ### My goal is to become a Full Stack Developer. And for this I want to first study Front End Development.

I am fond of IT technologies, programming and technological innovation.

Before studying at the institute and during my studies i worked in many jobs and decided to change its field of activity to programming.

> ### Personal qualities:
 + purposefulness
 + honesty
 + analytic mind
 + active life position
 + punctuality
 + responsibility
 + lack of bad habits
 + great desire to work and learn new things
 
## Skills

Programming languages

| Level | Skills | Time | 
| --- | --- | --- |
| ◾◾◽◽◽ | HTML/CSS | 2 months |
| ◾◽◽◽◽ | Git | 1 month |
| ◾◽◽◽◽ | Markdown | 1 month |
| ◾◽◽◽◽ | MySQL | 1 month |
| ◾◾◽◽◽ | PHP | 1 month |

---

Development Tools

| Level | Skills | Time |
| --- | --- | --- |
| ◾◽◽◽◽ | PHPStorm | 1 month |
| ◾◽◽◽◽ | NetBeans | 1 month |
| ◾◽◽◽◽ | Visual Code Studio | 1 month |
| ◾◾◽◽◽ | Sublime Text | 2 months |
| ◾◾◽◽◽ | Openserver | 2 months |

## Code examples:

``` 
<DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>My Page</title>
</head>
<body>
<div class="cabinet">
    <div class="case row">
    <input class="upload_profile" type="file" multiple="multiple" accept=".txt,image/*" style="display: none;">
        <div class="cabinet__user user">
            <div class="user__info">
                <div class="user__photo">
                  <?php
                      $get_my_pic = "SELECT * FROM `pictures_profile` WHERE `user_id` = '$user_id' LIMIT 1";
                      $get_my_pic_sql = $conn->query($get_my_pic);
                      if($get_my_pic_sql->num_rows > 0){
                          $get_my_pic_row = $get_my_pic_sql->fetch_array();
                      ?>
                <div class="user__photo">
                    <img class="img_profile" style="width: 131px" src="profiles/profile<?=$user_id?>/<?=$get_my_pic_row['img_id']?>" alt="">
                </div>
                  <?php
                  }
                  else{
                    ?>
                <div class="user__photo">
                    <img class="img_profile" src="upload/icons/lk/photo.png" alt=">
                </div>
                  <?php
                }
                ?>
            </div>
        </div>
    </div>
</div>
</body>
</html>

```

## Work experience
I have no work experience yet.

## Education
#### **Courses which I finished:**
There is nothing here yet, but will be updated soon.

#### **Now I am taking courses:**
- [ ] PHP bacis course on [Code-Basics](https://ru.code-basics.com/languages/php)

**Goal:** I want to take more courses to learn more about web programming 

## English Language
I have  A1 level, but i continue to study the language.
