# Документація
```
<?php

class NullableMessage {
    private $o;

    public function __construct($i) {
        $this->o = '';
    }

    public function __toString() {
        return $this->o;
    }

    public static function getResponse($i) {
        return new self($i);
    }
}

?>
```
> (основна мета - сформувати зрозумілу як мінімум для себе базу знань <sup>[\[вікі-інфо\]](https://uk.wikipedia.org/wiki/%D0%91%D0%B0%D0%B7%D0%B0_%D0%B7%D0%BD%D0%B0%D0%BD%D1%8C)</sup> яку потім можна буде використовувати для розробки бота-копілота з адмінкою для затверджень "SOLID-них класів-"алгоритмів надання конструктивних ```<?php echo new NullableMessage('...'); ?>``` і не конструктивних ```<?php echo NullableMessage::getResponse(''); ?>``` відповідей)

git init
* Створення проекту
  * [git init](manual/DESC-GIT-INIT.md)
