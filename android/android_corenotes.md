## Activity Lifecycle

1. onCreate() – initialize UI
2. onStart() – visible
3. onResume() – user interaction
4. onPause() – partially visible
5. onStop() – not visible
6. onDestroy() – cleanup

## Fragment Lifecycle

onAttach()
onCreate()
onCreateView()
onViewCreated()
onStart()
onResume()

== fragment visible ==

onPause()
onStop()
onDestroyView()
onDestroy()
onDetach() - Fragment object destroyed

## What is Context? Types of Context?

- Context provides access to application resources, system services, and environment information.
  ### Types of Context

1. Application Context

2. Activity Context

## Difference between explicit and implicit intent

- Explicit Intent → internal app navigation
- Implicit Intent → system actions (camera, share)

## Launch Modes

1️⃣ standard (Default)

- New instance every time
- Use case: Normal flows , Forms, screens

2️⃣ singleTop

- If activity already on top → reuse

- Else → new instance
- Used for: Notifications , Search screens

3️⃣ singleTask

- Only ONE instance in task
- Clears above activities
- Used for: Dashboard , Home screen

4️⃣ singleInstance

- Runs in its own task

- No other activity allowed
- Used for:Call screens , Alarm apps

## Thread LifeCycle

New → Runnable → Running
→Blocked / Waiting
→Terminated
