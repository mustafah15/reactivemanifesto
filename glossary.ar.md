# قائمة مصطلحات بيان الأنظمة التفاعلية

* [غير متزامن](#غير-متزامن)
* [الضغط الخلفي](#الضغط-الخلفي)
* [تجميع](#تجميع)
* [مكون](#مكون)
* [تفويض](#تفويض)
* [المرونة (في سياق قابلية التوسع)](#المرونة)
* [الفشل (في سياق الخطأ)](#الفشل)
* [العزل (و الاحتواء)](#العزل)
* [شفافية الموقع](#شفافية-الموقع)
* [القائمة-علي-الرسائل (في سياق الاعتماد علي الأحداث)](#القائمة-علي-الرسائل)
* [غير-محجوب](#غير-محجوب)
* [بروتوكول](#بروتوكول)
* [استنساخ](#استنساخ)
* [مصدر](#مصدر)
* [قابلية التوسع](#قابلية-التوسع)
* [النظام](#النظام)
* [المستخدم](#المستخدم)


## <a name="غير-متزامن"></a>غير-متزامن
The Oxford Dictionary defines asynchronous as _“not existing or occurring at the same time”_. In the context of this manifesto we mean that the processing of a request occurs at an arbitrary point in time, sometime after it has been transmitted from client to service. The client cannot directly observe, or synchronize with, the execution that occurs within the service. This is the antonym of synchronous processing which implies that the client only resumes its own execution once the service has processed the request.
