# Add To Calendar

## Example

![Screenshot](sample.png)

## Installation

The preferred way to install this extension is through [composer](https://getcomposer.org/download/)

```
$ composer require pixiumdigital/yii2-widget-add-to-calendar:~1.0.1
```

or add

```
"pixiumdigital/yii2-widget-add-to-calendar": ">=1.0.1"
```

to the require section of your composer.json file.


### Usage

```
use pixium\widgets\AddToCalendar;

<?= AddToCalendar::widget([
        'label' => '<i class="fas fa-calendar-plus"></i>',
        'text' => 'Title Coach',
        'classes' => 'btn-success',
        'add' => 'xxx@gmail.com',
        'start' => 1234567890,
        'duration' => 60,
        'ctz' => 'Asia/Singapore',
        'details' => 'This session has been planned.',
    ]); 
?>
```