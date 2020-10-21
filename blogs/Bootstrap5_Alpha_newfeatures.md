<h1 style="font-size:30px;">Here Added Some New Features of Bootstrap 5 Alpha<h1>

<h2 style="text-decoration:underline;font-size:25px;">1. Switching to vanilla JS -</h2>
<p style="font-size: 20px;">
<img src="./img/vanila.png"><br></br>
Now a days javascript is the essential part of web development. you move to react, angular or vue. It is a very important part. Most of the devices today use the javascript interpreters. 
Also after removing the jquery it is all set to become the universal scripting standard of the world. As a result, this will improve the size and weight of the files and libraries used by the framework.
</p>

<h2 style="text-decoration:underline;font-size:25px;">2. JQuery removed -</h2>
<p style="font-size: 20px;">
<img src="./img/jquery.jpeg" /><br></br>
After hearing this thing I thought why they removed the jquery. Then I go through a article about the actual reason for removing the jquery.
According to them they are using jquery for many years and it has been so bloated that for downloading and website loading time it is giving slower performance due to it’s virtual DOM. Besides that there are other frameworks like angular, vue and react which are better than jquery. So, they moved to vanilla JS which will give them a general standard of writing code.
</p>

<h2 style="text-decoration:underline;font-size:25px;">3. Internet Explorer 10 & 11 support removed -</h2>
<p style="font-size: 20px;">
In bootstrap 5 there is no support for IE 10 and 11. So, the alternative remains chrome, firefox, opera or edge. But it will encourage the designers and developers to make more responsive websites for modern browsers.
</p>

<h2 style="text-decoration:underline;font-size:25px;">4. Responsive Font sizes -</h2>
<p style="font-size: 20px;">
Bootstrap 5 will enable responsive font sizes by default which will automatically resize the typography element according to the size of the user’s viewport through Responsive Font Sizes.
According to RFS repository, Responsive Font Size is a unit resizing engine which was originally developed to resize font sizes. RFS offers the ability to resize basically every value for any CSS property with units, like margin, padding, border-radius or box-shadow. Suppose, we have header class which we will use for main section title according to the font-size:
<h2>

.header { @include font-size(5rem); }

.header { font-size: calc(1.5rem + 3.2vw); }

@media (min-width: 1000px) {

.header {

font-size: 5rem;

    }
}
</h2>
</p>

<h2 style="text-decoration:underline;font-size:25px;">5. Gutter width Measurement -</h2>
<p style="font-size: 20px;">
Actually gutter-width means the spacing between two columns.In bootstrap 5 they have made a few changes with gutter-width.
Normally we use px, rem, em for margin,padding and in border property also. Bootstrap has been using px for its gutter width for quite a long time which will no longer be the case in Bootstrap 5. According to the fixes made on Bootstrap 5’s official Github project tracking board, the gutter width will now be on rem instead of px. rem basically means for root em.
1rem is equivalent t 16px and it will be calculated according to the font-size. Previously we used card-deck in bootstrap and now bootstrap 5 brings us new grid system which gives more responsive control.
</p>

<h2 style="text-decoration:underline;font-size:25px;">6. Modification in CSS classes -</h2>
<p style="font-size: 20px;">
They have done some modifications in the css classes. css classes are a major part of bootstrap for design purpose. some classes are removed like (form-row, form-inline,list-inline,card-deck).<br><br>
Also some classes are added also which are -<br><br>
i) gx-* classes control the horizontal/column gutter width,<br><br>
ii) gy-* classes control the vertical/row gutter width<br><br>
iii) g-* classes control the horizontal & vertical gutter width<br><br>
iv) row-cols-auto
</p>

<h1>So, Here is the new updates from the bootstrap 5 alpha. Also there are some other updates also. Bootstrap 5 first alpha was officially released on June 16, 2020. Thank you😊</h1>