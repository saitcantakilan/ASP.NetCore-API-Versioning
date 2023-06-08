# ASP.NET Core API Versiyonlama Örneği

Bu repo, URL tabanlı API versiyonlama yaklaşımı kullanılmaktadır. API sürümü, URL'ye eklenen bir parametre ile belirtilir. Örneğin, `/api/v1/WeatherForecast` veya `/api/v2/WeatherForecast` gibi URL'ler kullanılarak farklı sürümlere erişim sağlanır.

API sürümleri, geriye dönük uyumluluk ilkesine göre yönetilir. Yeni bir sürüm, mevcut sürümle uyumlu olacak şekilde yeni özellikler ekler. Eski sürümlerde yapılan değişiklikler ise mümkün olduğunca geriye dönük uyumlu hale getirilir.
