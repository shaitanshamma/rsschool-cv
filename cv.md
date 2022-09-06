# Andrey Kurbatov

---
## My Contacts: 

* __Location__: Moscow, Russia;
* __Telegram__: @shamma77;
* __Email__: [kurbatov_andr@hotmail.com](mailto:kurbatov_andr@hotmail.com);
* __Github__: [shaitanshamma](https://github.com/shaitanshamma);
* __Discord__: Andrey Kurbatov (@shaitanshamma).

---

## About myself:

I am a radio engineer. Now I want to change my activity profile.
I am studying frontend and backend programming. I had a little practice working in a team when compiling a course project.

---

## Skills:

* __PHP & Laravel__;
* __Js, HTML, CSS__;
* __JavaCore & Spring__;
* __Git__.

---

## Code example:

```
function sortByThanos(array $mas): array
{
    $arrCount = count($mas);

    if ($arrCount <= 1) {
        return $mas;
    }
    if (!checkDuplicate($mas)) {
        $sum = 0;
        for ($j = 0; $j < $arrCount; $j++) {
            $sum += $mas[$j];
        }
        $midle = $sum / $arrCount;
        $left = [];
        $right = [];
        for ($i = 0; $i < $arrCount; $i++) {
            if ($mas[$i] <= $midle) {
                $left[] = $mas[$i];
                $GLOBALS['count']++;
            } else {
                $right[] = $mas[$i];
                $GLOBALS['count']++;
            }
        }

        $left = sortByThanos($left);
        $right = sortByThanos($right);

        return array_merge($left, $right);
    } else return $mas;
}

function checkDuplicate($list)
{
    $tmp = 1;
    $arrCount = count($list);
    for ($i = 1; $i < $arrCount; $i++) {
        if ($list[$i] === $list[0]) {
            $tmp++;
            $GLOBALS['count']++;
        }
    }
    if ($tmp < $arrCount) {
        return false;
    } else return true;
}

```
___

## Projects:

* [Basic e-shop ](https://github.com/shaitanshamma/myAwesomeShop);
* [Laravel project ](https://github.com/shaitanshamma/Laravel);
* [Team project ](https://github.com/shaitanshamma/shelter-dom).

___

## Education:

* Moscow Aviation Institute (National Research University);
* Geekbrains University - Java Developer;
* Geekbrains University - Web Developer - present time;

___

## English:

* A1 Elementary