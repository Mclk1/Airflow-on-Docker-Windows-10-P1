# Airflow on Docker -Windows 10 Kurulumu
 
 Program giriş seviye eğitim içeriği olduğundan dolayı Airflow orjinal yml dosyası sadeleştirilmiştir. Aşağıda yml dosyasından kaldırılan araç isimleri yazmaktadır.
 			
* redis:latest 
* airflow-worker 
* flower

Bu araçların dışında "LOAD_EXAMPLES" özelliği false edilerek örnek airflow Dag'larının yüklenmesi engellenmiştir. Örnek Dag'ları içe aktarmak için yml dosyasındaki AIRFLOW__CORE__LOAD_EXAMPLES: '' özelliği 'true' olmalıdır.
				
Dilerseniz güncel yml dosyasını airflow'un kendi web adresinden alabilirsiniz: https://airflow.apache.org/docs/apache-airflow/stable/start/docker.html

* WSL: https://docs.microsoft.com/en-us/windows/wsl/install-manual
* Docker Desktop: https://docs.docker.com/desktop/windows/install/
* Visual studio code: https://code.visualstudio.com/
