# Документація
```
<?php

class NullableMessage {
    private $output_str;

    public function __construct($input_str) {
        $this->output_str = '';
    }

    public function __toString() {
        return $this->output_str;
    }

    public static function getResponse($input_str) {
        return new self($input_str);
    }
}

?>
```
> (основна мета - сформувати зрозумілу як мінімум для себе базу знань <sup>[\[вікі-інфо\]](https://uk.wikipedia.org/wiki/%D0%91%D0%B0%D0%B7%D0%B0_%D0%B7%D0%BD%D0%B0%D0%BD%D1%8C)</sup> яку потім можна буде використовувати для розробки бота"-копілота <sup>[\[вікі-Див. також\]](https://uk.wikipedia.org/wiki/GitHub_Copilot)</sup>" з адмінкою для затверджень "солідних<sup>[\[вікі-примітка\]](https://uk.wikipedia.org/wiki/SOLID_(%D0%BE%D0%B1%27%D1%94%D0%BA%D1%82%D0%BD%D0%BE-%D0%BE%D1%80%D1%96%D1%94%D0%BD%D1%82%D0%BE%D0%B2%D0%B0%D0%BD%D0%B5_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F))</sup> класів"-алгоритмів надання конструктивних ```<?php echo new NullableMessage('...'); ?>``` і не конструктивних ```<?php echo NullableMessage::getResponse('...'); ?>``` відповідей)

git init
* Створення проекту
  * [git init](manual/DESC-GIT-INIT.md)
