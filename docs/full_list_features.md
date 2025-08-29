# Full list of Features

## Discord Slash Commands
- **/alarm** - Eşleştirilmiş Akıllı Alarmların (Smart Alarms) görselini değiştirir.
- **/alias** - Bir komut veya karakter dizisi için kısayol oluşturur.
- **/blacklist** - Bir kullanıcıyı botu kullanmaktan engeller.
- **/cctv** - Anıtlar için CCTV kamera kodlarını getirir.
- **/craft** - Bir öğeyi üretmenin maliyetini gösterir.
- **/credentials** - Kimlik bilgilerini ayarlar.
- **/decay** - Bir öğenin çürüme süresini gösterir.
- **/help** - Yardım mesajını gösterir.
- **/item** - Bir öğenin detaylarını gösterir.
- **/leader** - Liderliği başka bir kullanıcıya devreder.
- **/map** - Oyundaki haritayı gösterir.
- **/market** - Vending makinelerindeki ürünleri arar veya takip eder.
- **/players** - Bağlı tüm oyuncuların Battlemetrics verilerini gösterir.
- **/recycle** - Bir öğeyi geri dönüştürmenin çıktısını gösterir.
- **/research** - Bir öğeyi araştırmanın maliyetini gösterir.
- **/reset** - Discord kanallarını sıfırlar.
- **/role** - rustplusplus kullanabilmesi için belirli bir rol ayarlar.
- **/storagemonitor** - Eşleştirilmiş Depo Monitörlerinin görselini değiştirir.
- **/switch** - Eşleştirilmiş Anahtarların görselini değiştirir.
- **/upkeep** - Bir öğenin bakım maliyetini gösterir.
- **/uptime** - rustplusplus’un çalışma süresini gösterir.
- **/voice** - rustplusplus’un sesli sohbete katılmasını sağlar.

## In-Game Commands
- **afk** - AFK (hareketsiz) takım arkadaşlarını gösterir.
- **alive** - En uzun süredir hayatta olan kişiyi gösterir.
- **cargo** - Cargoship hakkında bilgi gösterir.
- **chinook** - Chinook 47 hakkında bilgi gösterir.
- **connection/connections** - Son takım bağlantılarını gösterir.
- **craft** - Bir öğeyi üretmenin maliyetini gösterir.
- **death/deaths** - Son ölümleri gösterir.
- **decay** - Bir öğenin çürüme süresini gösterir.
- **events** - Son olayları gösterir.
- **heli** - Devriye Helikopteri hakkında bilgi verir.
- **large** - Büyük Petrol Platformu (Large Oil Rig) hakkında bilgi verir.
- **leader** - Liderliği başka bir kullanıcıya devreder.
- **marker/markers** - Gitmek için işaretler ayarlar.
- **market** - Vending makinelerindeki ürünleri arar veya takip eder.
- **mute** - rustplusplus’u oyun içinde susturur.
- **note/notes** - Not ekler.
- **offline** - Çevrimdışı takım arkadaşlarını gösterir.
- **online** - Çevrimiçi takım arkadaşlarını gösterir.
- **player/players** - Oyuncular hakkında Battlemetrics bilgisi gösterir.
- **pop** - Sunucunun nüfusunu gösterir.
- **prox** - Yakındaki takım arkadaşlarını gösterir.
- **recycle** - Bir öğeyi geri dönüştürmenin çıktısını gösterir.
- **research** - Bir öğeyi araştırmanın maliyetini gösterir.
- **send** - rustplusplus üzerinden bir Discord kullanıcısına mesaj gönderir.
- **small** - Küçük Petrol Platformu (Small Oil Rig) hakkında bilgi verir.
- **steamid** - Takım arkadaşının SteamID’sini gösterir.
- **team** - Takım bilgilerini gösterir (tüm takım üyelerinin isimleri).
- **time** - Oyundaki zamanı gösterir.
- **timer/timers** - Zamanlayıcı kurar.
- **tr** - İngilizceden başka bir dile çevirir.
- **trf** - Bir dilden başka bir dile çevirir.
- **tts** - Metni sese dönüştürür (Discord’da takım sohbeti açık olmalı).
- **unmute** - rustplusplus’u oyun içinde yeniden seslendirir.
- **upkeep** - Depo Monitörü ile bağlı Tool Cupboard bakımını kontrol eder.
- **uptime** - rustplusplus’un ve bağlı olduğu sunucunun çalışma süresini gösterir.
- **vendor** - Seyyar Satıcı hakkında bilgi verir.
- **wipe** - Son wipe’tan bu yana geçen süreyi gösterir.


## Smart Devices
> Pair Smart Devices such as `Smart Switches`, `Smart Alarms`, `Storage Monitors` and control them from Discord or In-Game teamchat.

- See [Smart Switches](smart_devices.md#smart-switches).
- See [Smart Switch Groups](smart_devices.md#smart-switch-groups).
- See [Smart Alarms](smart_devices.md#smart-alarms).
- See [Storage Monitors](smart_devices.md#storage-monitors).


## Rust Server Information
- See number of players, max capacity and queue size of the Rust Server.
- See the In-Game time and time till day/night.
- See how long ago wipe was.
- See Map Size.
- See Map Seed.
- See Map Salt.
- See Map Name.
- F1 console connect information.

## In-Game Event Notifications
> Receive notifications for In-Game Events such as:
- **Cargo Ship** - When it spawns, despawns, how long before it enters egress stage. How long time since it was last out. step-trace.
- **Patrol Helicopter** - When it spawns, despawns or gets taken down. How long time since it was last out and how long since it was taken down. step-trace.
- **Oil Rig** - When Oil Rig calls in Heavy Scientists and how long till the Locked Crate unlocks.
- **Chinook 47** - When it enters map and when it leaves.
- **Vending Machines** - Whenever a new Vending Machine appears on the map.

## Teammate Information
> Get information about teammates such as Online/Offline/AFK/Alive/Dead/Location/Paired/Leader.

## Other
- Connect through different Rust Servers seemingly through the `servers` Text-Channel in Discord.
- Easily access rustplusplus settings via the Discord Text-Channel `settings`.
- Run In-Game commands either from In-Game teamchat or from Discord Text-Channel `commands`.
- Communicate with teammates from In-Game to Discord and vice versa.
- Get activity information in the `activity` Text-Channel on Discord. Information such as Smart Devices not reachable, Teammate connect/disconnect/leave/join/death, Smart Alarms notify when triggered, Server went offline/online, Map Wipe Detection, Storage Monitor Decay Notification, Tracker notifications etc...
- Create Battlemetrics Trackers to track players or groups.
- Get Facepunch news in Discord.
