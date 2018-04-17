# 静态天气数据


eg:
 
```scala
import scala.io.Source
val city = "London,uk"
val url = "http://api.openweathermap.org/data/2.5/weather"

val response = Source.fromURL(s"$url?q=$city&units=imperial&mode=xml&APPID=9af8a451b625d01e9519a16aec3e7c14")
```