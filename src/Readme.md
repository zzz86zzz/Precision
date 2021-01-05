# Отчёт о тестировании приложения "Precision"

## Краткое описание

05.01.2021 - 05.01.2021 проведено модульное тестирование приложения Precision.

На тестирование потрачено: 1 час.

Проверка *итогового*  результата в приложении при *сложении* регуляргого и специального бонусов.


## Описание тестов

Было проведено модульное тестирование c входными данными:
* регулярный бонус со значением = 0.3;
* дополнительный бонус со значением = 0.6;
* переменная для хранения итогового значения - тип `double`

Пример кода:

<div class="highlight highlight-source-java"><pre><span class="pl-k">public</span> <span class="pl-k">class</span> <span class="pl-en">Main</span> {
  <span class="pl-k">public</span> <span class="pl-k">static</span> <span class="pl-k">void</span> <span class="pl-en">main</span>(<span class="pl-k">String</span>[] <span class="pl-v">args</span>) {
    <span class="pl-k">double</span> regularBonus <span class="pl-k">=</span> <span class="pl-c1">0.3</span>;
    <span class="pl-k">double</span> specialBonus <span class="pl-k">=</span> <span class="pl-c1">0.6</span>;
    <span class="pl-k">double</span> totalBonus <span class="pl-k">=</span> regularBonus <span class="pl-k">+</span> specialBonus;
    <span class="pl-smi">System</span><span class="pl-k">.</span>out<span class="pl-k">.</span>println(totalBonus);
  }
}</pre></div>

## Результаты

1. 100% неуспешных тестов;
2. [Ссылка на баг репорт](https://github.com/zzz86zzz/Precision/issues/1)

### Тестирование производилось в следующем окружении:

Windows 10 Домашняя x64
Openjdk version "11.0.9.1" 2020-11-04
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)