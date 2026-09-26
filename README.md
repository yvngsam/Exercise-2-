<!DOCTYPE html>
<html lang="ru">

<head>
    <meta charset="UTF-8">
    <title>Мой сайт</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- Шапка сайта -->
    <header>
        <div class="logo">
            <img src="logo.jpg" alt="Логотип">
        </div>

        <!-- Меню -->
        <nav>
            <a href="#links">Ссылка 1</a>
            <a href="#table">Ссылка 2</a>
            <a href="#form">Ссылка 3</a>
        </nav>

    </header>


    <!-- Основное содержимое -->
    <main>

        <!-- Список гиперссылок -->
        <section id="links">

            <h2>Список гиперссылок</h2>

            <!-- Здесь можно оставить список из задания 1 -->

        </section>


        <!-- Таблица -->
        <section id="table">

            <h2>Таблица</h2>

            <table>

                <tr>
                    <th>Название 1</th>
                    <th>Название 2</th>
                    <th>Название 3</th>
                    <th>Название 4</th>
                </tr>

                <tr>
                    <td>Ячейка 1</td>
                    <td>Ячейка 2</td>
                    <td>Ячейка 3</td>
                    <td>Ячейка 4</td>
                </tr>

                <tr>
                    <td>Ячейка 5</td>
                    <td colspan="2">Объединённые ячейки</td>
                    <td>Ячейка 8</td>
                </tr>

                <tr>
                    <td>Ячейка 9</td>
                    <td>Ячейка 10</td>
                    <td>Ячейка 11</td>
                    <td>Ячейка 12</td>
                </tr>

                <tr>
                    <td rowspan="2">Объединённые строки</td>
                    <td>Ячейка 14</td>
                    <td>Ячейка 15</td>
                    <td>Ячейка 16</td>
                </tr>

                <tr>
                    <td>Ячейка 18</td>
                    <td>Ячейка 19</td>
                    <td>Ячейка 20</td>
                </tr>

            </table>

        </section>


        <!-- Форма -->
        <section id="form">

            <h2>Форма</h2>

            <form>

                <p>
                    <label>
                        ФИО:
                        <input type="text" name="fullname">
                    </label>
                </p>

                <p>
                    <label>
                        Телефон:
                        <input type="tel" name="phone">
                    </label>
                </p>

                <p>
                    <label>
                        E-mail:
                        <input type="email" name="email">
                    </label>
                </p>

                <p>
                    <label>
                        Дата рождения:
                        <input type="date" name="birthdate">
                    </label>
                </p>

                <p>
                    Пол:
                    <br>

                    <input type="radio" name="gender" value="male">
                    Мужской

                    <br>

                    <input type="radio" name="gender" value="female">
                    Женский
                </p>

                <p>
                    <label>
                        Любимый язык программирования:
                    </label>

                    <br>

                    <select name="language" multiple size="5">

                        <option>Pascal</option>
                        <option>C</option>
                        <option>C++</option>
                        <option>JavaScript</option>
                        <option>PHP</option>
                        <option>Python</option>
                        <option>Java</option>
                        <option>Haskel</option>
                        <option>Clojure</option>
                        <option>Prolog</option>
                        <option>Scala</option>

                    </select>
                </p>

                <p>
                    <label>
                        Биография:
                    </label>

                    <br>

                    <textarea name="biography"
                              rows="5"
                              cols="40"></textarea>
                </p>

                <p>
                    <input type="checkbox" name="contract">
                    С контрактом ознакомлен(а)
                </p>

                <p>
                    <input type="submit" value="Сохранить">
                </p>

            </form>

        </section>

    </main>


    <!-- Подвал сайта -->
    <footer>
        (c) Семён Сергеевич Нехаев
    </footer>

</body>

</html>
