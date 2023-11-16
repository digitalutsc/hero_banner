# Hero Banner for Drupal

## Installation 

````
composer require digitalutsc/drupal_hero_banner
````

## How to setup

### Add Banner images
* Enable drupal_hero_banner module 
* Go to /admin/content, add media > Hero Banner Image
* Configure Hero Description
     
![image](https://github.com/digitalutsc/islandora_lite_docs/assets/7862086/4849fe1e-06b5-49e1-a51a-40ecbf9dadaf)

==> it's for 
![Screenshot 2023-08-11 at 10 48 45 AM](https://github.com/digitalutsc/islandora_lite_docs/assets/7862086/6ca21e72-444a-48b7-a087-7fea2c74bd05)

* Configure Hero Image: 

![image](https://github.com/digitalutsc/islandora_lite_docs/assets/7862086/5214dc09-ff41-432c-b11f-189113bb7922)

==> it's for 
![Screenshot 2023-08-11 at 10 50 12 AM](https://github.com/digitalutsc/islandora_lite_docs/assets/7862086/b471a31e-84e6-4c6f-963e-11f5de71bd2c)

### Setup the block

* Go to `/admin/structure/block`, place `Hero banner: 16:9 and 16:5 Mixed aspect ratio - Hero banner - front page` in a region

![image](https://github.com/digitalutsc/islandora_lite_docs/assets/7862086/7cb0d3f8-faa0-41c6-8bb8-c5c5249e8070)

### Add Landing page node

* Go to /admin/content > `Add content` > `Landing page`, In Hero Banner (Homepage Only), click add Media, and select the newly added media as 
![image](https://github.com/digitalutsc/islandora_lite_docs/assets/7862086/50f0521a-4f6b-46fd-b524-38aba64b7443)

* Go to `/admin/config/system/site-information`, set the new create Landing page as Front page. 
