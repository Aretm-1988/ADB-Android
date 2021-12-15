# ADB-Android
# Сбросить кэш
./adb shell pm clear com.android.contacts
# Запустить приложение
./adb shell am start -n com.android.contacts/.activities.PeopleActivity
# Тап плюс
./adb shell input tap 1285 2745
# Tap поле Name
./adb shell input tap 323 1295
# Заполнить Name
./adb shell input text 5
# Tap Last Name
./adb shell input tap 299 1485
# Заполнить Last Name
./adb shell input text 5
# Tap Phone
./adb shell input tap 326 1686

# Заполнить Phone
./adb shell input text 5

# Tap Email
./adb shell input text 5 

# Заполнить Email
./adb shell input text 5 

# Нажать Save
./adb shell input tap 1341 128

# Выйти из приложения
./adb shell input keyevent 3
