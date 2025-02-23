### Attribute
#### 1. The href Attribute
1. 跳转到外部网
``` html
<a href="https://www.google.com">Go to Google</a>
```
2. 跳转到同一个网站的内部页面
```html
<!-- 📌 点击后会跳转到 about.html 页面（相对路径） -->
<a href="about.html">About Us</a>
```
3. 跳转到页面的某个部分（锚点）
```html
<!-- 点击后会跳转到 ID 为 section2 的部分（适用于单页面跳转） -->
<a href="#section2">Go to Section 2</a>
```
4. 让链接在新标签页打开
```html
<a href="https://www.example.com" target="_blank">Open in new tab</a>
```
5. 创建一个邮件链接
```html
<a href="mailto:someone@example.com">Send Email</a>
```

#### 2. The src Attribute
The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:
There are two ways to specify the URL in the src attribute:

1. Absolute URL - Links to an external image that is hosted on another website.  
   Example: src="https://www.w3schools.com/images/img_girl.jpg".

2. Relative URL - Links to an image that is hosted within the website.   
If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg".
If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

#### 3. The title Attribute
```html
<p title="I'm a tooltip">This is a paragraph.</p>
```
<img width="201" alt="image" src="https://github.com/user-attachments/assets/aa94c76d-450e-4b84-9730-5177438ba881" />
