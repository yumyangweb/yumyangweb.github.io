# Yum Yang

## Information
Is a profile pages
You can saw our current page on our site [Yue](https://yue.ke-et.com)
We are friendly if you have any issue when you using our same pages , contact us or create a issue!

## Creater

#### Editor
I was born in a place where I could see various faces of Guishan Island. 
Originally studying electrical engineering, I eventually ventured into the culinary industry due to my passion for food and cooking. 
Apart from my work, I enjoy sharing my thoughts on food and observing people's relationship with it from different perspectives. 
I established a studio called "Yang Yang" with the aim of deconstructing food and observing people's relationship with it from different angles. 
Everyone has a different definition of what good food is, but there are always surprises in life. 
Regarding the mountains in Taiwan, which account for 70% of the island, many people appreciate our natural surroundings. 
Just like the diversity of flowers and tea plants in the small peaks that are endowed by the Da-fu Tree, I want to present my best work in such an environment. 
After getting to know me, do you have any other interests apart from cooking and food? What are your dreams or goals? 
Let's share and explore our food stories together!

#### Engineer 
by [Kevin K](https://github.com/tingruikp0925)

by [Andrew](https://github.com/woohoolin)



## How to use if you want to build the same page?

##### Clone this repo
```
git clone https://github.com/yumyangweb/yumyangweb.github.io.git
```

##### Build the docker image via our docker file
```
docker build -t <container-name> . --no-cache
```

##### Run the image to be a container
```
docker run -d -p <port-you-want-to-listen-http>:80 -p <port-you-want-to-listen-https>:443 --restart=always --name <container-name> yumyangweb:v1
```

Now you can run the same page with our pages !

<Templete create by [HTML5](https://html5up.net/)>
