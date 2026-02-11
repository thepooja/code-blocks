## ViewModel

- Part of **MVVM**
- Holds UI state
- Survives rotation

---

## Live Data

1.  Why is LiveData lifecycle aware?

- “LiveData is lifecycle aware because it observes the lifecycle of Activity or Fragment and only notifies active observers (STARTED or RESUMED state).”

2. Flow vs LiveData — One Strong Difference

- “Flow is not lifecycle aware by default, but LiveData is lifecycle aware.”

- “Flow is cold stream and supports powerful operators like map, filter, combine, while LiveData is simpler and mainly used for UI observation.”

- “Flow is more powerful and supports backpressure handling, whereas LiveData is mainly UI-focused and lifecycle-aware.

## Model

## Explain the difference between MutableLiveData and LiveData

- setValue() or postValue()

## differences between MediatorLiveData and regular LiveData
