# moto-lamu-repo
Motorola moto g15 (lamu) документация (разблокировка загрузчика, кастомные прошивки, гайды)

**!!! ВНИМАНИЕ !!! Если не знаете что делаете не делайте этого вы можете soft/hard brick`нуть устройство**

# Разблокировка загрузчика
**!!! ВНИМАНИЕ !!! Никогда не прошивайте preloader самостоятельно высока вероядность hard brick`а**

Скачайте tanuki (https://files.kaerulabs.com/k/android/exploits/motorola/lamu)
и запустите его командой "bash tanuki.sh" и выполняйте инструкции от программы.
Если у вас после каких-то манипуляций с устройством оно перестало включаться то
скорее всегоу вас отвалился kaeru (которыйставится скриптом tanuki для 
разблокировки и фиксовнекоторых) просто опять прошейте его через tanuki.
# Прошивки
## LineageOS 
Скачать     : https://download.lineageos.org/devices/lamu/builds
Баги        : Нету багов.
Инсктрукция : https://wiki.lineageos.org/devices/lamu/install/variant1/
## GSI прошивки
Скачать     : Любая GSI чисто Project Treble прошивка
Баги        : Не проверял
Инструкция  : fastboot flash system <system.img>
# Recovery
## LineageOS Recovery (LOSR)
Устанавливается вместе с LineageOS
# Root
## Magisk
**1.** Скачайте APK: https://github.com/topjohnwu/Magisk/releases

**2.** Прошейте через recovery

**3.** Установите приложение Magisk если не установленно

**4.** Переустановите Magisk через приложение Magisk (и перезагрузетесь)
## KernelSU
**1.** Скачайте APK: https://github.com/tiann/KernelSU/releases

**2.** Установите Magisk

**3.** Установите прилложение KernelSU

**4.** Откройте оба приложения одновременно

**5.** Откройте Magisk и нажмите кнопку Удалить и там полностью удалите и перед

тем как оно полностью удалится переключитесь на KernelSU и там быстро запустите

установку KernelSU

**6.** Подочдите пока устройство само перезагрузится
