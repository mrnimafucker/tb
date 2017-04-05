
<br><a href="https://telegram.me/Milad0S">@Milad0S</a>

<h3 align="right"> <strong> نصب و راه‌اندازی</strong> 🚀
</h3>
<hr>
<h4 dir="rtl">ابتدا سورس <em>ربات تبلیغ‌گر</em> را کپی کرده و پیش‌زمینه‌ها را نصب کنید.</h4>
<h6>(موارد زیر را در ترمینال وارد کنید)</h6>
<pre>
<span>git clone https://github.com/Milad0S/tb.git -b persian</span>
<span>cd tb</span>
<span>chmod +x bot</span>
<span>./bot install</span>
</pre>
<h4 dir="rtl"> برای ساخت ربات جدید <strong>bot create/.</strong> را وارد کنید.
</h4>
<pre>
<span>./bot create</span>
</pre>
<h4 dir="rtl">حال با توجه به شناسه ای که برای ربات جدید داده شده تبلیغ‌گر خود را راه‌اندازی کنید.
<br>مثال:</h4>
<pre>
<span></span>
<span>./bot 1</span>
</pre>
<h5 dir="rtl">توجه داشته باشید برای اولین بار که ربات را راه اندازی می‌کنید،از شما شناسه عددی مدیر ربات (شما و یا هرکس که می خواهید مدیر ربات شود) ، شماره ربات و کد ورود به حساب کاربری خواسته می‌شود.
<h6 dir="rtl"> شما می توانید با استفاده از ربات <a href="https://telegram.me/userinfobot">@userinfobot</a> شناسه عددی خود را بدست آورید.</h6>
<h6 dir="rtl">از <a href="#help">راهنمای‌تبلیغ‌گر</a> برای آشنا شدن با طرز کار رباتتان استفاده کنید.</h6>
<br>
<h3 align="right"><strong>جلوگیری از قطع شدن عملکرد تبلیغ‌گر</strong>🛡
<hr>
<h4 dir="rtl">یکی از مشکلات کار با SSH، قطع شدن آن در زمان قطع اتصال اینترنت است.<br>وقتی اتصال اینترنت قطع می‌شود اجرای تمامی برنامه‌ها و فرامینی که در حال استفاده از SSH بودند، متوقف می‌شود. فرمان screen این‌جا به‌کمک شما می‌آید. کافی است این دستور را قبل از دستورراه‌اندازی تبلیغ‌گر قرار دهید.</h4>
<h6 dir="rtl">مثال:</h6>
<pre>
<span><strong>screen ./bot 1</strong></span>
</pre>
<h4 dir="rtl">برای خارج شدن از محیط screen کلید‌های ترکیبی Ctrl+A و سپس کلید D را بفشارید.<br>برای مشاهده فهرست screen های موجود می‌توانید از دستور<strong>  screen -ls  </strong>  استفاده کنید.<br>این دستور فهرست تمامی screen های در حال اجرا را نمایش می‌دهد.<br>برای مشاهده screen اجرا‌شده، کافی است دستور زیر را وارد کنید:</h4>
<pre>
<span><strong>screen -r [screen name]</strong></span>
</pre>
<br>
<h4> برای ران کردن همه ربات ها و یا همون اتولانچ از دستور زیر استفاده میکنیم </h4>
<pre>
<span><strong>screen ./bot autolaunch</strong></span>
</pre>
<br>
<h4 id="help" dir="rtl">&#x272F; راهنمای تبلیغ‌گر :</h4>
<table style="width:100%" dir="rtl">
  <tr>
    <th colspan="3">مخصوص مدیر</th>
  </tr>
  <tr>
    <th colspan="2">دستور</th>
    <th>عملکرد</th>
    <th></th>
    <th>فقط در گروه (&#x2724;)<br>فقط در ریپلای (&#x21BB;)</th>
    </tr>
   <tr>
    <td colspan="2">reload/</td>
    <td align="center">بارگذاری مجدد ربات و راه‌اندازی دوباره</td>
  </tr>
  <tr>
    <td colspan="2">بروزرسانی ربات</td>
    <td align="center">بروزرسانی ربات به آخرین نسخه<br> و بارگذاری مجدد</td>
  </tr>
   <tr>
    <td colspan="2">تازه سازی</td>
    <td align="center">تازه سازی آمار تبیلغ‌گر<br>(حدکثر یک بار در روز)</td>
  </tr>
     <tr>
    <td colspan="2">ریپورت</td>
    <td align="center">اطلاع از وضعیت ریپورت ربات</td>
  </tr>
   <tr>
    <td colspan="2">تازه سازی ربات</td>
    <td align="center">تازه سازی اطلاعات فردی تبلیغ‎گر<br>بعد از تغییر در مشخصات فردی تبلیغ‎گر <br>مانند اسم انجام گیرد</td>
  </tr>
  <tr>
    <td>افزودن مدیر</td>
    <td>شناسه</td>
    <td align="center">افزودن مدیر با شناسه وارد شد</td>
  </tr>
    <tr>
    <td>افزودن مدیرکل</td>
    <td>شناسه</td>
    <td align="center">افزودن مدیرکل با شناسه وارد شد</td>
  </tr>
   <tr>
    <td>حذف مدیر</td>
    <td>شناسه</td>
    <td align="center">حذف مدیر یا مدیر کل با شناسه خاص</td>
  </tr>
  <tr>
    <td colspan="2">ترک کردن</td>
    <td align="center">خارج شدن از گروه و حذف<br>از اطلاعات گروه‌ها</td>
    <td align="center">&#x2724;</td>
  </tr>
  <tr>
    <td colspan="2">افزودن همه مخاطبین</td>
    <td align="center">افزودن تمام مخاطبین و افراد در گفت‌و‎گوی شخصی<br>به گروه</td>
    <td align="center">&#x2724;</td>
  </tr>
  <tr>
    <td colspan="2">شناسه من</td>
    <td align="center">ارسال شناسه عددی شما</td>
  </tr>
  <tr>
   <td>بگو</td>
    <td>متن</td>
    <td align="center">ارسال متن</td>
    </tr>
  <tr>
  <tr>
   <td>ارسال کن</td>
    <td>"شناسه" متن</td>
    <td align="center">ارسال متن به شناسه گروه یا فرد</td>
    </tr>
  <tr>
   <td>تنظیم نام</td>
    <td>"نام" نام‌خانوادگی</td>
    <td align="center">تغییر نام</td>
    </tr>
      <tr>
   <td>تنطیم نام کاربری</td>
    <td>نام کاربری</td>
    <td align="center">جایگزینی نام کاربری داده شده<br>(دفعات استفاده محدود در زمان کوتاه)</td>
    </tr>
    <tr>
   <td colspan="2">حذف نام کاربری</td>
    <td align="center">حذف نام کاربری<br>(دفعات استفاده محدود در زمان کوتاه)</td>
    </tr>
  <tr>
   <td rowspan="2">افزودن با شماره</td>
    <td>روشن</td>
    <td rowspan="2" align="center">تغییر وضعیت اشتراک شماره تبلیغ‌گر<br>در جواب شماره به اشتراک گذاشته شده</td>
    </tr>
    <tr>
    <td>خاموش</td>
    </tr>
     <tr>
   <td rowspan="2">افزودن با پیام</td>
    <td>روشن</td>
    <td rowspan="2" align="center">تغییر وضعیت ارسال پیام در جواب<br>شماره به اشتراک گذاشته شده</td>
    </tr>
    <tr>
    <td>خاموش</td>
    </tr>
    <tr>
    <td>تنظیم پیام افزودن مخاطب</td>
    <td>متن</td>
    <td align="center">تنظیم متن داده شده به عنوان جواب<br>شماره به اشتراک گذاشته شده</td>
  </tr>
  <tr>
   <td rowspan="2">پاسخگوی خودکار</td>
    <td>روشن</td>
    <td rowspan="2" align="center">تغییر وضعیت پاسخ ‌گویی خودکار </td>
    </tr>
    <tr>
    <td>خاموش</td>
    </tr>
    <tr>
   <td>تنظیم جواب</td>
    <td>"متن" جواب</td>
    <td align="center">تنظیم جوابی به عنوان پاسخ خودکار<br> به پیام وارد شده مطابق با متن</td>
    </tr>
    <tr>
    <td>حذف جواب</td>
    <td>متن</td>
    <td align="center">حذف جواب مربوط به متن</td>
  </tr>
  <tr>
    <td rowspan="6">لیست</td>
    <td>مخاطبین</td>
    <td align="center" rowspan="6">ارسال لیستی از مورد خواسته شده<br>در قالب پرونده متنی یا پیام</td>
  </tr>
  <tr>
    <td>خصوصی</td>
    </tr>
    <tr>
    <td>گروه</td>
    </tr>
    <tr>
    <td>سوپرگروه</td>
    </tr>
    <tr>
    <td>لینک</td>
  </tr>
  <tr>
    <td>پاسخ های خودکار</td>
  </tr>
  <tr>
    <td>مسدودیت</td>
    <td>شناسه</td>
    <td align="center">مسدود‌کردن(بلاک) کاربر با شناسه داده شده</td>
  </tr>
  <tr>
    <td>رفع مسدودیت</td>
    <td>شناسه</td>
    <td align="center">رفع مسدودیت کاربر با شناسه داده شده</td>
  </tr>
  <tr>
   <td rowspan="2">وضعیت مشاهده</td>
    <td>روشن</td>
    <td rowspan="2" align="center">خاموش و یا روشن‌کردن وضعیت مشاهده پیام‌ها<br>(فعال و غیر‌فعال‌کردن تیک دوم)</td>
    </tr>
    <tr>
    <td>خاموش</td>
    </tr>
  <tr>
    <td colspan="2">امار</td>
    <td align="center">ارسال آمار و وضعیت تبلیغ‌گر</td>
  </tr>
    <tr>
    <td colspan="2">وضعیت</td>
    <td align="center">ارسال وضعیت اجرایی تبلیغ‌گر</td>
  </tr>
  <tr>
    <td rowspan="4">ارسال به</td>
    <td>همه</td>
    <td rowspan="4" align="center">ارسال پیام جواب داده شده<br> به مورد خواسته شده</td>
    <td rowspan="4">&#x21BB;</td>
    </tr>
    <tr>
    <td>خصوصی</td>
    </tr>
    <tr>
    <td>گروه</td>
    </tr>
    <tr>
    <td>سوپرگروه</td>
    </tr>
  <tr>
    <td>ارسال به سوپرگروه</td>
    <td>متن</td>
    <td align="center">ارسال متن داده شده به تمام سوپرگروه ها</td>
  </tr>
  <tr>
    <td>ترک کردن</td>
    <td>شناسه</td>
    <td align="center">خروج از گروه با‌شناسه وارد شده<br>و حذف از اطلاعات گروه</td>
  </tr>
    <tr>
    <td>افزودن به همه</td>
    <td>شناسه</td>
    <td align="center">دعوت کردن کاربر با شناسه وارد شده به تمامی<br>گروه ها و سوپرگروه ها</td>
  </tr>
  <tr>
    <td colspan="2">راهنما</td>
    <td align="center">دریافت راهنمای تبلیغ‌گر</td>
  </tr>
   <tr>
    <th colspan="3">استفاده از اطلاعات تبچی</th>
  </tr>
  <tr>
    <td colspan="2">همگام سازی با تبچی</td>
  </tr>
</table>
<h6 dir="rtl">اساس کار تبلیغ‌گر تشخیص لینک و عضویت در هر گروه‌ها و پیروی از دستورات تعیین شده است.</h6>
<br>

<br><a href="https://telegram.me/Milad0S">@Milad0S</a>
