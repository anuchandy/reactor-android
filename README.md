# reactor-android
Reactor-Android: Reactor Extensions for Android

`reactor-android` module includes an implementation of Reactor [Scheduler](https://projectreactor.io/docs/core/release/api/reactor/core/scheduler/Scheduler.html) contract for Android. 

Following two static methods can be used to get a Scheduler implementation.

`AndroidSchedulers.mainThread()`: Scheduler backed by Android main Thread (UI Thread). 

`AndroidSchedulers.fromLooper(Looper)`: Scheduler backed by the provided android.os.Looper instance.

Refer [this sample](https://github.com/anuchandy/reactor-android-sample) for this Scheduler usage.