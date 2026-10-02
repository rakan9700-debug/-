# -<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>منيو فدم</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: #f7f4ed;
            color: #3a2e2b;
            margin: 0;
            padding: 15px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .container {
            width: 100%;
            max-width: 480px;
        }
        .header {
            text-align: center;
            margin-bottom: 20px;
            padding-top: 10px;
        }
        .logo-text {
            font-size: 2.5rem;
            font-weight: bold;
            color: #3a2e2b;
            margin: 0;
        }
        .section-title {
            font-size: 1.15rem;
            font-weight: bold;
            margin: 25px 0 10px 0;
            border-bottom: 2px solid #3a2e2b;
            padding-bottom: 4px;
            display: inline-block;
        }
        .menu-table {
            width: 100%;
            border-collapse: collapse;
            background: #fff;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 2px 8px rgba(0,0,0,0.05);
            margin-bottom: 10px;
            font-size: 0.85rem;
        }
        .menu-table th, .menu-table td {
            padding: 10px 6px;
            text-align: center;
        }
        .menu-table th {
            background-color: #3a2e2b;
            color: #fff;
            font-weight: 600;
        }
        .menu-table td:first-child, .menu-table th:first-child {
            text-align: right;
            padding-right: 12px;
        }
        .menu-table tr:nth-child(even) {
            background-color: #faf8f5;
        }
        .card-list {
            display: flex;
            flex-direction: column;
            gap: 8px;
        }
        .menu-item-card {
            background: #fff;
            padding: 12px 15px;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.05);
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-size: 0.9rem;
        }
        .item-name {
            font-weight: 600;
        }
        .item-price {
            color: #6b5b54;
            font-size: 0.82rem;
            text-align: left;
        }
        .footer {
            text-align: center;
            margin-top: 35px;
            color: #8c7d75;
            font-size: 0.8rem;
            padding-bottom: 20px;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="header">
            <h1 class="logo-text">فدم</h1>
        </div>

        <!-- المشروبات الحارة -->
        <div>
            <div class="section-title">المشروبات الحارة</div>
            <table class="menu-table">
                <thead>
                    <tr>
                        <th>الطلب</th>
                        <th>ورق</th>
                        <th>قزاز</th>
                        <th>استكانة</th>
                        <th>براد</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>الشاي</td>
                        <td>٥ ريال</td>
                        <td>٦ ريال</td>
                        <td>٣ ريال</td>
                        <td>١٤ ريال</td>
                    </tr>
                    <tr>
                        <td>كرك</td>
                        <td>٦ ريال</td>
                        <td>٧ ريال</td>
                        <td>-</td>
                        <td>١٥ ريال</td>
                    </tr>
                    <tr>
                        <td>نعناع طائفي</td>
                        <td>٥ ريال</td>
                        <td>٦ ريال</td>
                        <td>-</td>
                        <td>١٤ ريال</td>
                    </tr>
                    <tr>
                        <td>قهوة سعودية</td>
                        <td>٧ ريال</td>
                        <td>٨ ريال</td>
                        <td>-</td>
                        <td>١٧ ريال</td>
                    </tr>
                </tbody>
            </table>
        </div>

        <!-- المشروبات الباردة -->
        <div>
            <div class="section-title">المشروبات الباردة</div>
            <table class="menu-table">
                <thead>
                    <tr>
                        <th>الطلب</th>
                        <th>ورق</th>
                        <th>قزاز</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>آيس تي فدم</td>
                        <td>١٤ ريال</td>
                        <td>١٥ ريال</td>
                    </tr>
                    <tr>
                        <td>آيس تي كركديه</td>
                        <td>١٤ ريال</td>
                        <td>١٥ ريال</td>
                    </tr>
                </tbody>
            </table>
        </div>

        <!-- نابولي -->
        <div>
            <div class="section-title">نابولي</div>
            <div style="font-size: 0.78rem; color: #6b5b54; margin-bottom: 6px;">(ثلاث حبات ٢٤ ريال / حبة وحدة ٩ ريال)</div>
            <div class="card-list">
                <div class="menu-item-card">
                    <span class="item-name">ناپولي بريسكيت تشيز</span>
                    <span class="item-price">حبة ٩ / ٣ حبات ٢٤</span>
                </div>
                <div class="menu-item-card">
                    <span class="item-name">ناپولي مسخن</span>
                    <span class="item-price">حبة ٩ / ٣ حبات ٢٤</span>
                </div>
                <div class="menu-item-card">
                    <span class="item-name">ناپولي تونة سبايسي</span>
                    <span class="item-price">حبة ٩ / ٣ حبات ٢٤</span>
                </div>
                <div class="menu-item-card">
                    <span class="item-name">ناپولي شبس عمان</span>
                    <span class="item-price">حبة ٩ / ٣ حبات ٢٤</span>
                </div>
            </div>
        </div>

        <!-- فطاير فدم بر -->
        <div>
            <div class="section-title">فطاير فدم (بر)</div>
            <div class="card-list">
                <div class="menu-item-card">
                    <span class="item-name">فطيرة مسخن</span>
                    <span class="item-price">٣ حبات ١٠ ريال</span>
                </div>
                <div class="menu-item-card">
                    <span class="item-name">فطيرة اجبان</span>
                    <span class="item-price">٣ حبات ١٠ ريال</span>
                </div>
                <div class="menu-item-card">
                    <span class="item-name">خلية نحل بر</span>
                    <span class="item-price">٨ ريال <br><small style="font-size: 0.75rem; color:#8c7d75;">(نستلة / عسل / شيرة)</small></span>
                </div>
            </div>
        </div>

        <!-- الحلويات والإضافات -->
        <div>
            <div class="section-title">الإضافات والحلويات</div>
            <div class="card-list">
                <div class="menu-item-card">
                    <span class="item-name">كوكيز</span>
                    <span class="item-price">٩ ريال</span>
                </div>
                <div class="menu-item-card">
                    <span class="item-name">مكسرات يابانية</span>
                    <span class="item-price">٧ ريال</span>
                </div>
            </div>
        </div>

        <div class="footer">
            فدم Qadam
        </div>
    </div>

</body>
</html>
