# Проектирование АСОиУ
## Курс проектирования автоматизированных систем обработки информации и управления
Данный репозиторий предназначен для хранения материалов курса и результатов выполнения лабораторных работ. Это описание будет дополняться постепенно по мере проведения лекций и лабораторных работ.

### Структура репозитория
В репозитории имеется папка **Labs** для всех лабораторных работ. В неё будут постепенно добавляться отдельные папки для каждой лабораторной работы (**Lab_#**), в корень каждой из которых необходимо помещать свои результаты лабораторной работы: созданные файлы, протоколы и т.п. Также в каждой из них может быть папка с материалами для лабораторной работы (**Materials**), например, лекциями, шпаргалками, исходниками и т.п.

Например, сейчас уже имеется папка **Lab_1**, в корень которой нужно будет поместить .bpmn-файл своей диаграммы BPMN и файл протокола. В ней также имеется папка **Materials** с файлом лекции для лабораторной работы.

Также в репозитории имеется Excel-таблица с данными о посещаемости лабораторных работ и отметками о выполнении домашних заданий, которая будет обновляться по мере проведения работ и проверки результатов.

### Порядок работы с репозиторием
Каждому магистру необходимо стать участником данного репозитория, каждому будет выслано приглашение, если указанный почтовый ящик привязан к аккаунту GitHub. Ветка master предназначена только для преподавателя, он в неё будет выкладывать задания и прочие материалы. Каждый магистр должен создать для себя отдельную ветку от ветки **master**, начиная с последнего имеющегося коммита, назвав её своей фамилией на латинице (например, **Ivanov**). В свою ветку необходимо коммитить результаты выполнения лабораторных работ (файлы исходного кода, диаграммы, протоколы) в папки лабораторных (можно создавать свои подпапки для различных групп файлов). Периодически необходимо сливать ветку master со своей веткой для получения материалов и заданий для новых лабораторных. **Сливать свою ветку в master НЕ НУЖНО!** **Делать коммиты в master НЕ НУЖНО!** Протоколы лучше сохранять в файлы формата .pdf.

Советую также подобрать себе красивый GUI для работы с Git, чтобы проще ориентироваться в ветках. [Вот, хорошая подборка](https://git-scm.com/download/gui/windows), например GitKraken - очень красивый, а SourceTree - простой и один интерфейс для Git и Hg. Но некоторые могут лагать на разных системах, так что выбирайте.

### Описание лабораторных работ
#### Лабораторная работа №1: Диаграммы BPMN
Данная лабораторная работа посвящена нотации моделирования бизнес-процессов BPMN. В папке с материалами имеется короткая лекция, которая была рассказана на лабораторной.

**Задание на дом:** необходимо разработать модель некоторого бизнес-процесса, связанного с тематикой своей магистерской диссертации или непосредственно для неё. Необходимо закоммитить в репозиторий .bpmn-файл своей диаграммы, а также документ отчёта, в котором нужно словесно описать данный бизнес-процесс, прокомментировать его этапы, возможно, добавить какие-то примечания к диаграмме, чтобы преподавателю было проще положительно оценить её. Программы для моделирования диаграмм и прочая дополнительная информация описана в лекции для лабораторной.
