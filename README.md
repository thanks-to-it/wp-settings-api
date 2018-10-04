# wp-settings-api
This repository is an override from [tareq1988/wordpress-settings-api-class](https://github.com/tareq1988/wordpress-settings-api-class) with some new features

## Features

* **Subsection field**
* **No padding on submit button**

## Subsection field
A new subsection input type allowing to create a Subsection
```php
array(
  'name'  => 'subsection_general',
  'label' => __( 'A subsection', 'domain' ),
  'desc'  => __( 'Now we can have a subsection description too ;)', 'domain' ),
  'type'  => 'subsection'
),
```
![Subsection field](https://i.imgur.com/M28opH7.png)

## No padding on submit button
On the original class, there is a anoying `style="padding-left: 10px"` on submit button.
No more
