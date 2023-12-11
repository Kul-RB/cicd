# Задание 1
Создайте новый проект, название произвольное.
Скачайте пакет sonar-scanner, который вам предлагает скачать SonarQube.
Сделайте так, чтобы binary был доступен через вызов в shell (или поменяйте переменную PATH, или любой другой, удобный вам способ).
Проверьте sonar-scanner --version.
Запустите анализатор против кода из директории example с дополнительным ключом -Dsonar.coverage.exclusions=fail.py.
Посмотрите результат в интерфейсе.
Исправьте ошибки, которые он выявил, включая warnings.
Запустите анализатор повторно — проверьте, что QG пройдены успешно.
Сделайте скриншот успешного прохождения анализа, приложите к решению ДЗ.

# Решение

![image](https://github.com/Kul-RB/cicd/assets/53901269/70381b14-bdce-4dac-82aa-10ee48895404)

![image](https://github.com/Kul-RB/cicd/assets/53901269/6baeceb7-6f7c-448e-9bda-def1c397d1fe)

![image](https://github.com/Kul-RB/cicd/assets/53901269/b006ff49-0245-4c79-973e-b4258fb1baa6)

![image](https://github.com/Kul-RB/cicd/assets/53901269/8d8179ed-96cf-46a9-abcb-61efd9c000c8)

![image](https://github.com/Kul-RB/cicd/assets/53901269/a3619ff8-c260-4ed5-bfda-81e1adde5ec0)

# Задание 2
В репозиторий maven-public загрузите артефакт с GAV-параметрами:
groupId: netology;
artifactId: java;
version: 8_282;
classifier: distrib;
type: tar.gz.
В него же загрузите такой же артефакт, но с version: 8_102.
Проверьте, что все файлы загрузились успешно.
В ответе пришлите файл maven-metadata.xml для этого артефекта.

# Решение
![image](https://github.com/Kul-RB/cicd/assets/53901269/ed8015bd-6265-43ff-bd2e-3b59e76ea9b0)

