<!DOCTYPE html>
<html>
<head>
    <style>
        table {
            border-collapse: collapse;
            width: 100%;
        }

        table, th, td {
            border: 1px solid black;
        }

        th, td {
            padding: 8px;
            text-align: center;
        }

        .morning {
            background-color: #ccf;
        }

        .evening {
            background-color: #ffc;
        }
    </style>
</head>
<body>
    <table>
        <tr>
            <th>الأحد</th>
            <th>صباحا</th>
            <th class="morning">علوم</th>
            <th class="morning">عربية</th>
            <th class="morning">فرنسية</th>
            <th class="morning">فيزياء</th>
            <th class="evening">مساء</th>
            <th class="evening">فرنسية و إنجليزية</th>
            <th class="evening">أفواج</th>
            <th class="evening">تم</th>
            <th class="evening">رياضيات</th>
        </tr>
        <tr>
            <th>الاتنين</th>
            <th>صباحا</th>
            <th class="morning">رياضيات</th>
            <th class="morning">إنجليزية</th>
            <th class="morning">اجتماعيات</th>
            <th class="evening">مساء</th>
            <th class="evening">عربية</th>
            <th class="evening">رياضة</th>
        </tr>
        <tr>
            <th>الثلاثاء</th>
            <th>صباحا</th>
            <th class="morning">عربية</th>
            <th class="morning">رياضيات</th>
            <th class="morning">علوم</th>
            <th class="morning">فيزياء</th>
            <th class="evening">مساء</th>
            <th class="evening">لاتوجد دراسة</th>
        </tr>
        <tr>
            <th>الاربعاء</th>
            <th>صباحا</th>
            <th class="morning">انجليزية</th>
            <th class="morning">رياضيات</th>
            <th class="morning">اجتماعيات</th>
            <th class="morning">فرنسية</th>
            <th class="evening">مساء</th>
            <th class="evening">رسم</th>
            <th class="evening">فرنسية</th>
            <th class="evening">عربية</th>
            <th class="evening">رياضيات</th>
            <th class="evening">أفواج</th>
        </tr>
        <tr>
            <th>الخميس</th>
            <th>صباحا</th>
            <th class="morning">عربية</th>
            <th class="morning">إنجليزية</th>
            <th class="morning">اجتماعيات</th>
            <th class="morning">اسلامية</th>
            <th class="evening">مساء</th>
            <th class="evening">أفواج</th>
            <th class="evening">مكتبة</th>
            <th class="evening">اعلام</th>
            <th class="evening">تم</th>
            <th class="evening">فرنسية</th>
        </tr>
    </table>
    <button onclick="printTable()">اطبع الجدول</button>

    <script>
        function printTable() {
            window.print();
        }
    </script>
</body>
</html>
